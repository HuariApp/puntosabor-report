
<div align="center">
  
<img src="./assets/upc-logo.png" alt="UPC Logo" width="150px">  



Universidad Peruana de Ciencias Aplicadas

Carrera de Ingeniería de Software

**1ASI0732**

**Diseño de Experimentos de Ingeniería de Software**

NRC

**9112**

**Informe del Trabajo Final**

Docente

**Lennin Percy Cenas Vasquez**

Equipo

**HuariApp**

Proyecto

**PuntoSabor**

**Integrantes**

| Código | Apellidos y Nombres |
| --- | --- |
| u20241d995 | Cesar Jair Contreras Rojas |
| u202321843 | Delgado Carrasco, Schneider |
| u202312700 | Lopez Goitia, Carlos Alberto |
| u202411282 | Montalván Palomino, Bruno Rodolfo |
| u202410772 | Razuri Alvarez, Matias Francesco |

**Período 202602**

**Setiembre 2026**

</div>

---

# Registro de versiones del informe

| Versión | Fecha | Autor | Descripción de modificación |
| --- | --- | --- | --- |
|  |  |  |  |
# Project Report Collaboration Insights

**Repositorio de la documentación del proyecto:** https://github.com/HuariApp/puntosabor-report.git

# Informe de Trabajo Final - HuariApp

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
| --- | --- | --- |
|  |  |  |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

En esta sección se presentan los requisitos definidos para PuntoSabor, expresados mediante User Stories y Epics. La tabla sigue la **plantilla oficial del enunciado**, dedicando una fila a cada Epic y a cada User Story, con las columnas **Story ID, Usuario, Prioridad, Epic, Título, Descripción y Criterios de Aceptación**. Cada User Story incluye criterios de aceptación claros y comprobables, redactados en tiempo presente y tercera persona, siguiendo la estructura Gherkin (Given-When-Then). Se consideran User Stories de la aplicación móvil, del sitio web estático (Landing Page, rol *Visitante*) y **Technical Stories** para el RESTful API (rol *Developer*).

La prioridad se expresa como **Alta / Media / Baja** según el valor para el negocio y su contribución al flujo principal, criterio que se mantiene coherente con el orden del Product Backlog (sección [3.3](#33-product-backlog)).

**Definición de Epics**

| Story ID | Usuario | Prioridad | Epic | Título | Descripción | Criterios de Aceptación |
|---|---|---|---|---|---|---|
| EP01 | Usuario | Alta | EP01 | Descubrimiento de huariques | Agrupa las funcionalidades que permiten a los usuarios buscar, ubicar y guardar huariques. | N/A (Epic) |
| EP02 | Dueño | Alta | EP02 | Gestión de huariques | Permite a los dueños registrar, actualizar y enriquecer la información de sus huariques. | N/A (Epic) |
| EP03 | Usuario, Sistema | Alta | EP03 | Reseñas y calificaciones | Reúne la publicación, calificación y moderación de reseñas sobre los huariques. | N/A (Epic) |
| EP04 | Visitante | Alta | EP04 | Landing Page | Sitio web estático que presenta la propuesta de valor y permite el contacto con el equipo. | N/A (Epic) |
| EP05 | Usuario, Dueño | Baja | EP05 | Notificaciones | Gestión de alertas y preferencias de notificación para usuarios y dueños. | N/A (Epic) |
| EP06 | Developer | Alta | EP06 | API RESTful (Technical Stories) | Servicios backend que exponen las operaciones para los productos digitales. | N/A (Epic) |
| EP07 | Usuario | Alta | EP07 | Autenticación y gestión de cuenta | Registro, inicio de sesión y recuperación de credenciales de forma segura. | N/A (Epic) |
| EP08 | Usuario | Media | EP08 | Recomendaciones y preferencias | Personalización de la experiencia a partir de preferencias e historial del usuario. | N/A (Epic) |
| EP09 | Usuario, Sistema | Media | EP09 | Información y estado del huarique | Mantiene actualizada y confiable la información operativa (horarios, estado, reportes). | N/A (Epic) |
| EP10 | Dueño, DueñoPro | Media | EP10 | Membresías, pagos y promociones | Modelo de ingresos: planes, pagos, comprobantes y promociones destacadas. | N/A (Epic) |

**User Stories y Technical Stories**

| Story ID | Usuario | Prioridad | Epic | Título | Descripción | Criterios de Aceptación |
|---|---|---|---|---|---|---|
| US01 | Usuario | Alta | EP01 | Filtrar huariques | Como usuario, quiero filtrar huariques por ubicación, tipo de comida y precio para encontrar opciones acordes a mis preferencias. | **Escenario 1:** Dado que el usuario selecciona filtros válidos, Cuando ejecuta la búsqueda, Entonces el sistema muestra solo los huariques que coinciden con los filtros aplicados. <br><br> **Escenario 2:** Dado que no existen huariques que coincidan con los filtros, Cuando el usuario ejecuta la búsqueda, Entonces el sistema muestra un mensaje indicando que no se encontraron resultados. <br><br> **Escenario 3:** Dado que el usuario no selecciona filtros, Cuando ejecuta la búsqueda, Entonces el sistema muestra la lista general de huariques disponibles. |
| US02 | Usuario | Alta | EP01 | Visualizar huariques en mapa | Como usuario, quiero visualizar la ubicación de los huariques en un mapa para identificar fácilmente cómo llegar a ellos. | **Escenario 1:** Dado que el usuario accede a la vista de mapa, Cuando la pantalla termina de cargar, Entonces el sistema muestra los huariques mediante marcadores de ubicación. <br><br> **Escenario 2:** Dado que el usuario selecciona un marcador del mapa, Cuando pulsa sobre este, Entonces el sistema muestra un resumen con nombre, dirección y calificación del huarique. |
| US03 | Usuario | Media | EP01 | Guardar huariques favoritos | Como usuario, quiero guardar huariques como favoritos para consultarlos nuevamente de forma rápida. | **Escenario 1:** Dado que el usuario selecciona la opción de favorito en un huarique, Cuando confirma la acción, Entonces el sistema agrega el huarique a su lista de favoritos. <br><br> **Escenario 2:** Dado que el usuario accede a la sección de favoritos, Cuando la pantalla carga, Entonces el sistema muestra los huariques guardados previamente. |
| US04 | Dueño | Alta | EP02 | Registrar un nuevo huarique | Como dueño, quiero registrar un nuevo huarique con información básica para que aparezca en la plataforma. | **Escenario 1:** Dado que el dueño completa todos los campos obligatorios con datos válidos, Cuando envía el formulario, Entonces el sistema registra el huarique correctamente. <br><br> **Escenario 2:** Dado que el dueño deja campos obligatorios vacíos, Cuando intenta registrar el huarique, Entonces el sistema solicita completar los datos faltantes. |
| US05 | Dueño | Media | EP02 | Actualizar información del huarique | Como dueño, quiero actualizar la información de mi huarique para mantener sus datos correctos y vigentes. | **Escenario 1:** Dado que el dueño modifica datos válidos del huarique, Cuando guarda los cambios, Entonces el sistema actualiza la información correctamente. <br><br> **Escenario 2:** Dado que el dueño ingresa información incompleta o inválida, Cuando intenta guardar los cambios, Entonces el sistema muestra un mensaje de validación. |
| US06 | Dueño | Media | EP02 | Gestionar contenido multimedia | Como dueño, quiero subir fotos y videos de mi huarique para mostrar mejor mi negocio a los usuarios. | **Escenario 1:** Dado que el dueño selecciona un archivo permitido, Cuando lo sube al perfil del huarique, Entonces el sistema almacena y muestra el contenido multimedia. <br><br> **Escenario 2:** Dado que el dueño selecciona un archivo no permitido, Cuando intenta subirlo, Entonces el sistema muestra un mensaje indicando los formatos aceptados. |
| US07 | Usuario | Alta | EP03 | Publicar reseñas | Como usuario, quiero publicar una reseña y calificación sobre un huarique para compartir mi experiencia con otros usuarios. | **Escenario 1:** Dado que el usuario completa la reseña y selecciona una calificación válida, Cuando confirma el envío, Entonces el sistema publica la reseña en el perfil del huarique. <br><br> **Escenario 2:** Dado que el usuario ya publicó una reseña sobre el mismo huarique, Cuando intenta publicar otra, Entonces el sistema impide el registro duplicado. |
| US08 | Sistema | Media | EP03 | Moderar reseñas inapropiadas | Como sistema, quiero detectar reseñas inapropiadas para evitar contenido ofensivo dentro de la plataforma. | **Escenario 1:** Dado que una reseña contiene lenguaje ofensivo, Cuando el usuario intenta publicarla, Entonces el sistema bloquea la publicación o la marca para revisión. |
| US09 | Visitante | Alta | EP04 | Mostrar beneficios en la landing page | Como visitante, quiero ver los beneficios de PuntoSabor en la landing page para comprender el valor de la plataforma. | **Escenario 1:** Dado que el visitante accede a la landing page, Cuando la página termina de cargar, Entonces el sistema muestra los beneficios principales para usuarios y dueños de huariques. |
| US10 | Visitante | Media | EP04 | Enviar consultas desde el formulario de contacto | Como visitante, quiero enviar consultas mediante un formulario de contacto para comunicarme con el equipo de PuntoSabor. | **Escenario 1:** Dado que el visitante completa correctamente todos los campos requeridos, Cuando envía el formulario, Entonces el sistema registra la consulta y muestra una confirmación. <br><br> **Escenario 2:** Dado que el visitante deja campos obligatorios vacíos, Cuando intenta enviar el formulario, Entonces el sistema solicita completar los datos faltantes. |
| US11 | Usuario | Baja | EP05 | Configurar notificaciones | Como usuario, quiero activar o desactivar notificaciones para recibir solo la información que me interesa. | **Escenario 1:** Dado que el usuario modifica sus preferencias de notificación, Cuando guarda los cambios, Entonces el sistema actualiza la configuración seleccionada. |
| US12 | Dueño | Baja | EP05 | Recibir notificaciones de nuevas reseñas | Como dueño, quiero recibir alertas cuando mi huarique reciba nuevas reseñas para responder oportunamente a los usuarios. | **Escenario 1:** Dado que un usuario publica una reseña aprobada, Cuando la reseña queda registrada, Entonces el sistema notifica al dueño del huarique. |
| US13 | Developer | Alta | EP06 | Consultar huariques mediante API | Como developer, quiero consultar huariques mediante filtros en la API para integrar la búsqueda con la aplicación móvil. | **Escenario 1:** Dado que la petición contiene parámetros válidos, Cuando la API procesa la solicitud, Entonces devuelve los huariques que cumplen los criterios enviados. <br><br> **Escenario 2:** Dado que la petición contiene parámetros inválidos, Cuando la API procesa la solicitud, Entonces devuelve un mensaje de error claro. |
| US14 | Developer | Alta | EP06 | Registrar y actualizar huariques mediante API | Como developer, quiero crear y actualizar huariques mediante la API para gestionar la información desde los productos digitales. | **Escenario 1:** Dado que la petición contiene datos válidos, Cuando la API procesa el registro, Entonces crea el huarique y devuelve una respuesta exitosa. <br><br> **Escenario 2:** Dado que la petición contiene datos válidos de actualización, Cuando la API procesa la solicitud, Entonces actualiza la información del huarique. |
| US15 | Usuario | Alta | EP07 | Registrar e iniciar sesión de forma segura | Como usuario, quiero crear una cuenta e iniciar sesión con credenciales seguras para acceder a mi perfil. | **Escenario 1:** Dado que el usuario ingresa datos válidos de registro, Cuando envía el formulario, Entonces el sistema crea la cuenta correctamente. <br><br> **Escenario 2:** Dado que el usuario ingresa credenciales válidas, Cuando inicia sesión, Entonces el sistema le permite acceder a su cuenta. <br><br> **Escenario 3:** Dado que el usuario ingresa credenciales incorrectas, Cuando intenta iniciar sesión, Entonces el sistema muestra un mensaje de error. <br><br> **Escenario 4:** Dado que el usuario deja campos vacíos, Cuando intenta continuar, Entonces el sistema solicita completar los datos requeridos. |
| US16 | Usuario | Media | EP07 | Recuperar contraseña | Como usuario, quiero recuperar mi contraseña para volver a acceder a mi cuenta en caso de olvido. | **Escenario 1:** Dado que el usuario ingresa un correo registrado, Cuando solicita la recuperación, Entonces el sistema envía instrucciones para restablecer la contraseña. <br><br> **Escenario 2:** Dado que el usuario ingresa un correo no registrado, Cuando solicita la recuperación, Entonces el sistema muestra un mensaje informativo. |
| US17 | Usuario | Media | EP08 | Guardar preferencias del usuario | Como usuario, quiero guardar mis preferencias de cocina, presupuesto y ubicación para recibir recomendaciones personalizadas. | **Escenario 1:** Dado que el usuario ingresa preferencias válidas, Cuando confirma la configuración, Entonces el sistema guarda las preferencias en su perfil. <br><br> **Escenario 2:** Dado que el usuario tiene preferencias guardadas, Cuando accede a recomendaciones, Entonces el sistema muestra huariques relacionados con esos criterios. |
| US18 | Usuario | Baja | EP08 | Sugerir huariques automáticamente | Como usuario, quiero recibir sugerencias de huariques basadas en mi historial para descubrir opciones relacionadas con mis intereses. | **Escenario 1:** Dado que el usuario tiene historial de búsquedas o favoritos, Cuando accede a recomendaciones, Entonces el sistema muestra huariques similares. <br><br> **Escenario 2:** Dado que el usuario no tiene historial, Cuando accede a recomendaciones, Entonces el sistema muestra huariques populares de la zona. |
| US19 | Usuario | Media | EP08 | Recomendar huariques cercanos | Como usuario, quiero recibir recomendaciones de huariques cercanos a mi ubicación para encontrar opciones próximas. | **Escenario 1:** Dado que el usuario concede permiso de ubicación, Cuando accede a la sección “Cerca de mí”, Entonces el sistema muestra huariques dentro del radio definido. <br><br> **Escenario 2:** Dado que el usuario no concede permiso de ubicación, Cuando accede a la sección, Entonces el sistema solicita permisos o permite una búsqueda manual. |
| US20 | Usuario | Baja | EP09 | Verificar horarios de huariques | Como usuario, quiero ver si el horario de un huarique fue confirmado recientemente para evitar información desactualizada. | **Escenario 1:** Dado que el dueño actualizó el horario recientemente, Cuando el usuario entra al perfil del huarique, Entonces el sistema muestra la etiqueta “Horario verificado”. <br><br> **Escenario 2:** Dado que no existen actualizaciones recientes, Cuando el usuario entra al perfil, Entonces el sistema muestra la etiqueta “Horario no verificado”. |
| US21 | Usuario | Baja | EP09 | Reportar información incorrecta | Como usuario, quiero reportar datos incorrectos de un huarique para contribuir a mantener actualizada la información. | **Escenario 1:** Dado que el usuario detecta información incorrecta, Cuando envía un reporte, Entonces el sistema registra el reporte para revisión. <br><br> **Escenario 2:** Dado que el reporte fue revisado y corregido, Cuando el usuario consulta el huarique, Entonces el sistema muestra la información actualizada. |
| US22 | Sistema | Media | EP09 | Mostrar estado abierto o cerrado | Como sistema, quiero mostrar si un huarique está abierto o cerrado para orientar mejor la decisión del usuario. | **Escenario 1:** Dado que el sistema cuenta con información reciente del horario, Cuando el usuario accede al perfil, Entonces muestra el estado “Abierto ahora” o “Cerrado”. <br><br> **Escenario 2:** Dado que no hay datos suficientes para validar el estado, Cuando el usuario accede al perfil, Entonces muestra el aviso “Estado no confirmado”. |
| US23 | Dueño | Media | EP10 | Seleccionar planes de membresía | Como dueño, quiero elegir entre planes de membresía con distintos beneficios para aumentar la visibilidad de mi huarique. | **Escenario 1:** Dado que el dueño selecciona un plan disponible, Cuando confirma la elección, Entonces el sistema activa la membresía correspondiente. <br><br> **Escenario 2:** Dado que el dueño solicita cambiar de plan, Cuando confirma la modificación, Entonces el sistema programa el cambio para el siguiente periodo disponible. |
| US24 | Dueño | Media | EP10 | Pagar suscripción | Como dueño, quiero pagar mi membresía mediante tarjeta o billetera digital para mantener activo mi plan. | **Escenario 1:** Dado que el dueño ingresa datos de pago válidos, Cuando confirma la operación, Entonces el sistema registra el pago y activa la suscripción. <br><br> **Escenario 2:** Dado que el dueño ingresa datos de pago inválidos, Cuando confirma la operación, Entonces el sistema muestra un mensaje de error y no activa la suscripción. |
| US25 | Dueño | Baja | EP10 | Descargar comprobantes de pago | Como dueño, quiero descargar comprobantes mensuales de mis pagos para llevar control contable de mi membresía. | **Escenario 1:** Dado que el dueño accede a la sección de facturación, Cuando selecciona un mes con pago registrado, Entonces el sistema permite descargar el comprobante correspondiente. <br><br> **Escenario 2:** Dado que existe un pago pendiente o fallido, Cuando el dueño revisa la facturación, Entonces el sistema muestra un aviso de pago pendiente. |
| US26 | Dueño Pro | Media | EP10 | Publicar promociones destacadas | Como dueño Pro, quiero publicar promociones destacadas para aumentar la visibilidad de mi huarique en los listados. | **Escenario 1:** Dado que el dueño Pro configura una promoción con fechas y cupos válidos, Cuando la publica, Entonces el sistema la muestra como destacada en los listados. <br><br> **Escenario 2:** Dado que la promoción alcanza su fecha de finalización, Cuando el usuario revisa los listados, Entonces el sistema deja de mostrarla como promoción activa. |
| US27 | Usuario | Media | EP07 | Gestionar cuenta y perfil | Como usuario, quiero ver mi perfil, actualizar mi nombre y eliminar mi cuenta para tener control sobre mis datos personales. | **Escenario 1:** Dado que el usuario accede a su perfil, Cuando la pantalla carga, Entonces el sistema muestra su nombre, correo y rol. <br><br> **Escenario 2:** Dado que el usuario edita su nombre con un valor válido, Cuando guarda los cambios, Entonces el sistema actualiza el nombre y lo refleja en la sesión. <br><br> **Escenario 3:** Dado que el usuario confirma la eliminación de su cuenta, Cuando acepta la acción, Entonces el sistema elimina la cuenta y cierra la sesión. |

## 3.3. Product Backlog

El Product Backlog reúne las User Stories de la sección [3.1](#31-user-stories) con su estimación en Story Points y su priorización. El orden lo determina el **valor para el negocio** y la contribución al flujo principal de descubrimiento de huariques; por ello, las historias de descubrimiento y presentación del producto (incluida la Landing Page, considerada desde el primer sprint) se ubican antes que las de seguridad o configuración, evitando el error de iniciar el backlog con autenticación.

**Documento del Product Backlog y herramienta de gestión del avance.** El backlog se mantiene de forma viva en **Trello**, herramienta indicada para el control del proyecto, donde cada User Story es una tarjeta con su estimación, prioridad, responsable y estado (To-Do / In-Process / To-Review / Done). La tabla siguiente es la exportación de referencia de ese tablero al informe.

- **Tablero de Trello (Product Backlog y control de sprints):** 
https://trello.com/invite/b/6a3b6709fd34f6edb2cc21af/ATTI7be4b37d5e727ef6f2e8092804bf2c3192D51CB7/puntosabor-app
- **Repositorio del informe (documento del backlog en Markdown):** <https://github.com/HuariApp/puntosabor-report>

## 3.4. Impact Mapping

![ImpactMap](assets/ImpactmapPuntoSabor.png)

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

### 4.1.3. Mobile Style Guidelines

#### 4.1.3.1. iOS Mobile Style Guidelines

#### 4.1.3.2. Android Mobile Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

### 4.4.2. Mobile Applications Wireflow Diagrams

### 4.4.3. Mobile Applications Mock-ups

### 4.4.4. Mobile Applications User Flow Diagrams

## 4.5. Mobile Applications Prototyping

### 4.5.1. Android Mobile Applications Prototyping

### 4.5.2. iOS Mobile Applications Prototyping

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes

### 4.6.2. Web Applications Wireflow Diagrams

### 4.6.3. Web Applications Mock-ups

### 4.6.4. Web Applications User Flow Diagrams

## 4.7. Web Applications Prototyping

## 4.8. Domain-Driven Software Architecture

### 4.8.1. Software Architecture Context Diagram

### 4.8.2. Software Architecture Container Diagrams

### 4.8.3. Software Architecture Components Diagrams

## 4.9. Software Object-Oriented Design

### 4.9.1. Class Diagrams

### 4.9.2. Class Dictionary

## 4.10. Database Design

### 4.10.1. Relational/Non-Relational Database Diagram

# Capítulo V: Product Implementation

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

### 5.2.2. Implemented Landing Page Evidence

### 5.2.3. Implemented Frontend-Web Application Evidence

### 5.2.4. Acuerdo de Servicio - SaaS

### 5.2.5. Implemented Native-Mobile Application Evidence

### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

### 5.2.7. RESTful API documentation

### 5.2.8. Team Collaboration Insights

## 5.3. Video About-the-Product

# Capítulo VI: Product Verification & Validation

## 6.1. Testing Suites & Validation

### 6.1.1. Core Entities Unit Tests

### 6.1.2. Core Integration Tests

### 6.1.3. Core Behavior-Driven Development

### 6.1.4. Core System Tests

## 6.2. Static testing & Verification

### 6.2.1. Static Code Analysis

#### 6.2.1.1. Coding standard & Code conventions

#### 6.2.1.2. Code Quality & Code Security

### 6.2.2. Reviews

## 6.3. Validation Interviews

### 6.3.1. Diseño de Entrevistas

### 6.3.2. Registro de Entrevistas

### 6.3.3. Evaluaciones según heurísticas

## 6.4. Auditoría de Experiencias de Usuario

### 6.4.1. Auditoría realizada

#### 6.4.1.1. Información del grupo auditado

#### 6.4.1.2. Cronograma de auditoría realizada

#### 6.4.1.3. Contenido de auditoría realizada

### 6.4.2. Auditoría recibida

#### 6.4.2.1. Información del grupo auditor

#### 6.4.2.2. Cronograma de auditoría recibida

#### 6.4.2.3. Contenido de auditoría recibida

#### 6.4.2.4. Resumen de modificaciones para subsanar hallazgos

# Capítulo VII: DevOps Practices

## 7.1. Continuous Integration

### 7.1.1. Tools and Practices

### 7.1.2. Build & Test Suite Pipeline Components

## 7.2. Continuous Delivery

### 7.2.1. Tools and Practices

### 7.2.2. Stages Deployment Pipeline Components

## 7.3. Continuous deployment

### 7.3.1. Tools and Practices

### 7.3.2. Production Deployment Pipeline Components

## 7.4. Continuous Monitoring

### 7.4.1. Tools and Practices

### 7.4.2. Monitoring Pipeline Components

### 7.4.3. Alerting Pipeline Components

### 7.4.4. Notification Pipeline Components

# Capítulo VIII: Experiment-Driven Development

## 8.1. Experiment Planning

### 8.1.1. As-Is Summary

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

### 8.1.3. Experiment-Ready Questions

### 8.1.4. Question Backlog

### 8.1.5. Experiment Cards

## 8.2. Experiment Design

### 8.2.1. Hypotheses

### 8.2.2. Domain Business Metrics

### 8.2.3. Measures

### 8.2.4. Conditions

### 8.2.5. Scale Calculations and Decisions

### 8.2.6. Methods Selection

### 8.2.7. Data Analytics: Goals, KPIs and Metrics Selection

### 8.2.8. Web and Mobile Tracking Plan

## 8.3. Experimentation

### 8.3.1. To-Be User Stories

### 8.3.2. To-Be Product Backlog

### 8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle

#### 8.3.3.1. To-Be Sprint Backlogs

#### 8.3.3.2. Implemented To-Be Landing Page Evidence

#### 8.3.3.3. Implemented To-Be Frontend-Web Application Evidence

#### 8.3.3.4. Implemented To-Be Native-Mobile Application Evidence

#### 8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence

#### 8.3.3.6. Team Collaboration Insights

### Matriz de Evaluación Ética y de Impacto

### 8.3.4. To-Be Validation Interviews

#### 8.3.4.1. Diseño de Entrevistas

#### 8.3.4.2. Registro de Entrevistas

## 8.4. Experiment Aftermath & Analysis

### 8.4.1. Analysis and Interpretation of Results

### 8.4.2. Re-scored and Re-prioritized Question Backlog

## 8.5. Continuous Learning

### 8.5.1. Shareback Session Artifacts: Learning Workflow

## 8.6. To-Be Software Platform Pre-launch

### 8.6.1. About-the-Product Intro Video

### 8.6.2. Resumen usando Gees FrameWork

## Conclusiones

## Bibliografía

## Anexos
