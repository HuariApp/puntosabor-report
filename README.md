
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

## 3.3. Product Backlog

## 3.4. Impact Mapping

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

En esta sección se detalla cómo se implementa, organiza y publica HuariApp, compuesto por tres componentes principales:

1. **Landing Page (HTML/CSS/JS estático):** publicada en GitHub Pages.
2. **Backend (C#/.NET 8):** API REST desplegada en Railway.
3. **Aplicación Móvil (Android/Kotlin con Jetpack Compose):** la interfaz principal del usuario, con las pantallas core de la plataforma.

El objetivo es mantener la consistencia del desarrollo entre los tres componentes y documentar las convenciones de código para futuras iteraciones.

### 5.1.1. Software Development Environment Configuration

**Landing Page (HuariqueHub-Landing)**
- Tecnologías: HTML5, CSS3, JavaScript (vanilla).
- Responsive Web Design: CSS (Flexbox/Grid + media queries).
- Editor: Visual Studio Code.
- Control de versiones: Git + GitHub.
- Plataforma de despliegue: GitHub Pages.

Estructura:
- `index.html` (página principal)
- `css/style.css` (hoja de estilos)
- `img/` (recursos de imágenes)

**Backend (HuariqueHub-Backend)**
- Framework: .NET 8
- Lenguaje: C#
- IDE: Visual Studio 2022 o Visual Studio Code con extensión C#.
- Control de versiones: Git + GitHub.
- Plataforma de despliegue: Railway (contenedor Docker + base de datos MySQL 8).
- **URL pública del backend:** <[https://huariquehub-backend.up.railway.app](https://puntosabor-backend-production-91fb.up.railway.app)>
- **Documentación de la API (Swagger / OpenAPI):** <[https://huariquehub-backend.up.railway.app/swagger](https://puntosabor-backend-production-91fb.up.railway.app/swagger/index.html)>

**Aplicación Móvil (HuariqueHub-App)**
- Lenguaje: Kotlin
- Framework UI: Jetpack Compose
- Nombre del proyecto: `HuariqueHub-Mobile`
- IDE: Android Studio.
- Control de versiones: Git + GitHub.

### 5.1.2. Source Code Management

**Repositorios GitHub (actual)**
- `HuariqueHub-Landing` (Landing Page estática HTML/CSS/JS, desplegada en GitHub Pages).
- `HuariqueHub-Backend` (API REST en C#/.NET 8, desplegada en Railway).
- `HuariqueHub-App` (Aplicación móvil Android/Kotlin con Jetpack Compose).

**Flujo de trabajo (GitFlow ligero)**
- **Ramas principales**
  - `main`: versión estable publicada.
  - `develop`: integración previa a publicación.
- **Ramas de apoyo**
  - `feature/*`: nuevas funcionalidades o mejoras (p. ej., `feature/US01-home-screen`, `feature/auth-login`).
  - `hotfix/*`: correcciones urgentes sobre `main`.

**Versionado Semántico**
- **X (major)**: cambios incompatibles (reestructura global de navegación/archivos).
- **Y (minor)**: nuevas secciones o funcionalidades compatibles.
- **Z (patch)**: correcciones menores (estilos, textos, enlaces).
- Ejemplos: `v1.0`, `v1.1`.

**Conventional Commits**

Formato general:
```
<type>[scope]: <descripción>
```
Ejemplos:
- `feat: agregar pantalla de home con lista de huariques`
- `feat(auth): implementar pantalla de login con Jetpack Compose`
- `fix(api): corregir endpoint de búsqueda por distrito`
- `docs: actualizar pasos de despliegue en README`

### 5.1.3. Source Code Style Guide & Conventions

**Landing Page -HTML**
- Estructura semántica: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
- Imágenes siempre con `alt`.
- Enlaces relativos y consistentes entre páginas.
- Scripts JS al final del `body` cuando corresponda.

**Landing Page -CSS**
- Uso de variables CSS (`:root { --color... }`) para colores y espaciados.
- Convención de clases en kebab-case (ej.: `.hero-title`, `.card-grid`).
- Layout con Flexbox y/o Grid.
- Media queries para puntos de quiebre (ej.: 960px, 760px, 560px).
- Estados y accesibilidad: `:hover`, `:focus-visible`, contraste adecuado.

**Landing Page -JavaScript**
- `const` / `let` (evitar `var`), funciones pequeñas y claras.
- Separar lógica de interacción del DOM cuando sea posible.
- Uso moderado de `localStorage` solo para preferencias/estado del cliente (si aplica).

**Backend -C# / .NET 8**
- Nombres en PascalCase para clases, métodos y propiedades.
- Estructura de capas: Domain, Application, Infrastructure, Presentation.
- Inyección de dependencias mediante el contenedor DI nativo de .NET.
- Métodos asíncronos con `async/await` (Task/Task<T>) para operaciones I/O.
- Documentación con comentarios XML (`///`) en métodos y clases públicas.

**Aplicación Móvil -Kotlin / Jetpack Compose**
- Variables y funciones en camelCase; clases y Composables en PascalCase.
- Composables pequeños, reutilizables y sin estado cuando sea posible.
- Navegación centralizada mediante `AppNavigation.kt` con Jetpack Compose Navigation.
- Corrutinas de Kotlin para operaciones asíncronas.
- Separación clara entre UI (`ui/screens/`) y datos (`data/model/`).

### 5.1.4. Software Deployment Configuration

Para la configuración del despliegue de PuntoSabor, se consideraron los entornos necesarios para publicar y ejecutar tanto la landing page como la aplicación móvil. El objetivo de esta configuración es permitir que el producto pueda ser probado por los usuarios y revisado por el equipo durante el avance del proyecto.

En esta etapa, la landing page se despliega como un sitio web estático, mientras que la aplicación móvil se ejecuta desde el entorno de desarrollo utilizando Android Studio. Esto permite validar la navegación, las pantallas principales y las funcionalidades implementadas durante el sprint.

#### Entorno de despliegue de la Landing Page

La landing page de PuntoSabor se publica mediante GitHub Pages, ya que esta herramienta permite alojar sitios estáticos de manera sencilla y accesible. Para ello, se utiliza el repositorio del proyecto, donde se almacenan los archivos HTML, CSS, JavaScript e imágenes necesarias para la presentación del producto.

Pasos considerados para el despliegue:

1. Subir los archivos de la landing page al repositorio de GitHub.
2. Verificar que la estructura de archivos sea correcta.
3. Activar GitHub Pages desde la configuración del repositorio.
4. Seleccionar la rama correspondiente para la publicación.
5. Validar que el sitio se visualice correctamente desde el enlace generado.
6. Revisar que las secciones principales sean accesibles desde el navegador.

#### Entorno de ejecución de la Aplicación Móvil

La aplicación móvil se desarrolla utilizando Kotlin y Jetpack Compose dentro de Android Studio. Para su ejecución, se utiliza un emulador Android o un dispositivo físico conectado al equipo de desarrollo.

Pasos considerados para la ejecución:

1. Clonar o descargar el repositorio del proyecto.
2. Abrir el proyecto en Android Studio.
3. Sincronizar las dependencias de Gradle.
4. Seleccionar un emulador o dispositivo Android.
5. Ejecutar la aplicación desde Android Studio.
6. Verificar el funcionamiento de las pantallas implementadas.

#### Consideraciones del despliegue

- La landing page debe mantenerse actualizada con la información principal del producto.
- La aplicación móvil debe ejecutarse correctamente en el entorno de pruebas.
- Los cambios deben registrarse mediante commits en GitHub.
- Las evidencias del despliegue deben incluir capturas de pantalla del sitio publicado y de la aplicación en ejecución.
- En futuras iteraciones, se podrá integrar un backend o servicios externos si el alcance del proyecto lo requiere.

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

Para el Sprint 1 se seleccionaron las historias de usuario más importantes para construir una primera versión funcional de PuntoSabor. Se priorizaron historias relacionadas con la presentación del producto, la búsqueda inicial de huariques y las primeras interacciones del usuario dentro de la aplicación móvil.

Las historias seleccionadas permiten mostrar un avance inicial tanto de la landing page como de la aplicación, manteniendo relación directa con los requisitos definidos previamente en la sección de User Stories.

| ID | User Story | Tipo | Epic relacionada | Responsable | Estado |
|---|---|---|---|---|---|
| US09 | Presentación de beneficios | Landing Page | EP04 | Becerra Llempen, Fabiola Dayane | Completado |
| US10 | Formulario de contacto | Landing Page | EP04 | Delgado Carrasco, Schneider | Completado |
| US01 | Búsqueda avanzada | App móvil | EP01 | Tumi Oliden, Manuel Ignacio | Completado |
| US02 | Visualización en mapa | App móvil | EP01 | Lopez Goitia, Carlos Alberto | Completado |
| US03 | Guardar favoritos | App móvil | EP01 | Vasquez Goicochea, Erick Alessander | Completado |
| US04 | Registro de nuevo huarique | App móvil | EP02 | Lopez Goitia, Carlos Alberto | Completado |
| US07 | Envío de reseñas | App móvil | EP03 | Becerra Llempen, Fabiola Dayane | Completado |
| US15 | Registro y login seguro | App móvil | EP07 | Tumi Oliden, Manuel Ignacio | Completado |

![alt text](assets/sprint_!.png)

El objetivo principal del Sprint 2 fue habilitar el flujo completo de PuntoSabor conectado al backend real, incorporando funcionalidades de gestión del propietario, preferencias, notificaciones, membresías y promociones. La gestión del avance se realizó en el tablero de Trello del equipo, donde cada tarea se movió por los estados To-Do → In-Process → To-Review → Done.

- **Tablero de Trello (Sprint 2):** https://trello.com/invite/b/6a3b6709fd34f6edb2cc21af/ATTI7be4b37d5e727ef6f2e8092804bf2c3192D51CB7/puntosabor-app

Tablero del Sprint 2 en Trello

![alt text](assets/trello_sprint2.png)

| Sprint # | User Story | | Work-Item / Task | | | | |
|---|---|---|---|---|---|---|---|
| | **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| Sprint 2 | US05 | Actualizar información del huarique | T-01 | Conectar formulario de edición a `PATCH /huariques/{id}` | Implementar pantalla CreateEditHuariqueScreen con integración al endpoint de actualización del backend | 5 | Vasquez Goicochea, Erick Alessander | Done |
| Sprint 2 | US11 | Configurar notificaciones | T-02 | Implementar pantalla de preferencias de notificaciones | Desarrollar NotificationsScreen con opciones para activar/desactivar tipos de notificaciones del usuario | 4 | Tumi Oliden, Manuel Ignacio | Done |
| Sprint 2 | US12 | Recibir notificaciones de nuevas reseñas | T-03 | Integrar `GET /notifications` y `PATCH /notifications/{id}/read` | Conectar la pantalla de notificaciones al backend para listar alertas y marcarlas como leídas | 4 | Becerra Llempen, Fabiola Dayane | Done |
| Sprint 2 | US16 | Recuperar contraseña | T-04 | Implementar ForgotPasswordScreen con `POST /auth/forgot-password` | Desarrollar pantalla de recuperación de contraseña integrada con el endpoint del backend | 3 | Vasquez Goicochea, Erick Alessander | Done |
| Sprint 2 | US17 | Guardar preferencias del usuario | T-05 | Integrar `GET /preferences` y `PUT /preferences` en PreferencesScreen | Implementar pantalla de preferencias con persistencia de tipo de comida, rango de precios y zona en el backend | 4 | Lopez Goitia, Carlos Alberto | Done |
| Sprint 2 | US18 | Sugerir huariques automáticamente | T-06 | Integrar `GET /huariques/suggestions` en HomeScreen | Conectar el endpoint de sugerencias para mostrar huariques personalizados según historial del usuario | 4 | Delgado Carrasco, Schneider | Done |
| Sprint 2 | US21 | Reportar información incorrecta | T-07 | Implementar `POST /reports` en HuariqueDetailScreen | Agregar opción de reporte en la pantalla de detalle del huarique integrada con el endpoint del backend | 3 | Tumi Oliden, Manuel Ignacio | Done |
| Sprint 2 | US23 | Seleccionar planes de membresía | T-08 | Integrar `GET /plans` y `POST /subscriptions` en SubscriptionScreen | Implementar pantalla de suscripción mostrando planes desde el backend con opción de activar membresía | 3 | Becerra Llempen, Fabiola Dayane | Done |
| Sprint 2 | US26 | Publicar promociones destacadas | T-09 | Integrar CRUD de promos en OwnerPromosScreen y CreateEditPromoScreen | Implementar gestión completa de promociones del propietario conectada a los endpoints `GET/POST/PATCH/DELETE /promos` | 5 | Vasquez Goicochea, Erick Alessander | Done |

Este Sprint Backlog permitió organizar el trabajo inicial del equipo y relacionar las tareas desarrolladas con las historias de usuario ya definidas en el proyecto. De esta manera, el avance del sprint mantiene coherencia con los requisitos funcionales de PuntoSabor.

El Sprint Backlog 3 se organizó tomando las funcionalidades pendientes del Product Backlog. Se priorizaron historias que completan la experiencia del usuario y del propietario dentro de PuntoSabor.

| ID | User Story | Descripción | Responsable | Estado |
|---|---|---|---|---|
| US20 | Horario verificado | Mostrar información actualizada sobre los horarios de atención del huarique. | Delgado Carrasco, Schneider | Done |
| US22 | Estado abierto/cerrado | Mostrar si un huarique se encuentra abierto o cerrado según su horario. | Becerra Llempen, Fabiola Dayane | Done |
| US24 | Pagar suscripción | Permitir al propietario seleccionar y pagar una membresía. | Lopez Goitia, Carlos Alberto | Done |
| US25 | Comprobantes | Permitir consultar la información relacionada con el pago realizado. | Vasquez Goicochea, Erick Alessander | Done |
| US26 | Promociones destacadas | Mejorar la visibilidad de las promociones dentro de los listados de la aplicación. | Tumi Oliden, Manuel Ignacio | Done |

Durante el sprint, las tareas fueron organizadas y revisadas de acuerdo con su avance. El equipo utilizó GitHub para registrar los cambios y mantener separados los avances realizados en la aplicación móvil y el backend.

### 5.2.2. Implemented Landing Page Evidence

Se ha hecho una landing page para la aplicación enfocandonos en que cumplan con las historias de usuario establecidas. Está landing page servira como punto de partidua para que nuevos usuarios usen nuestra aplicación.

El deploy de la landing page se hizo mediante GithubPages.

link: https://huariapp.github.io/PuntoSabor-Landing/

![alt text](assets/Landing_Page1.png)

![alt text](assets/Landing_Page2.png)

![alt text](assets/Landing_Page3.png)

![alt text](assets/Landing_Page4.png)

### 5.2.3. Implemented Frontend-Web Application Evidence

El FrontEnd fue realizado teniendo en cuenta los modelos hechos en los wireframes y mock-ups e igualmente se tomaron en cuenta las historias de usuarios.

link: https://punto-sabor-front.vercel.app

![alt text](assets/FrontEnd_1.png)

![alt text](assets/FrontEnd_2.png)

![alt text](assets/FrontEnd_3.png)

![alt text](assets/FrontEnd_4.png)

### 5.2.4. Acuerdo de Servicio - SaaS



### 5.2.5. Implemented Native-Mobile Application Evidence

La aplicación móvil de PuntoSabor fue desarrollada de forma incremental a lo largo de tres sprints:
 
**Sprint 1 — Pantallas core:**
- Login (correo y contraseña)
- Home con búsqueda, filtro por categorías y huariques destacados
- Detalle de huarique (categoría, dirección, teléfono, horario, descripción, valoración)
- Registro de reseñas (calificación + comentario)
- Marcado de favoritos
**Sprint 2 — Integración real con backend público (Railway):**
- Autenticación con JWT (login + registro con auto-login)
- Descubrimiento de huariques consumiendo `GET /huariques` (datos reales, ya no locales)
- Gestión del propietario: crear/editar huarique (`POST`/`PATCH /huariques`)
- Preferencias de usuario (`GET`/`PUT /preferences`)
- Notificaciones (`GET /notifications`, `PATCH /notifications/{id}/read`)
- Recuperación de contraseña (`POST /auth/forgot-password`)
- Suscripción a membresías (`GET /plans`, `POST /subscriptions`)
- Gestión de promociones del propietario (CRUD completo)
- Reporte de información incorrecta (`POST /reports`)
- Sugerencias personalizadas (`GET /huariques/suggestions`)
Durante esta etapa se detectaron y corrigieron bugs de contrato entre app y backend (verbo HTTP incorrecto en edición, falta de `categoryId`, ausencia de token tras registro).
 
**Sprint 3 — Cierre funcional:**
- Visualización de horario verificado del huarique
- Estado abierto/cerrado según horario
- Flujo de pago de suscripción (membresías)
- Comprobantes de pago
- Promociones destacadas con mayor visibilidad en los listados
**Evidencia de ejecución (emulador Android):**
 
| Funcionalidad | Evidencia |
|---|---|
| Login / Registro con JWT | Capturas de autenticación contra `/auth/login` y `/users` |
| Home con datos reales | Búsqueda, categorías y huariques destacados |
| Detalle + reseñas | Lectura y publicación de reseñas vía API |
| Gestión del propietario | Creación y edición de huarique conectada al backend |
| Horarios y estado | Visualización de horario y estado abierto/cerrado |
| Membresías y comprobantes | Flujo de suscripción y comprobante de pago |
| Promociones | Visualización de promociones destacadas |
 
**Repositorios:**
- App (nativa/Kotlin, Sprint 1-2): `HuariqueHub/HuariqueHub-App`
- App (Flutter, cross-platform): `HuariqueHub/HuariqueHub-AppFlutter`
---

### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

El backend de PuntoSabor está desarrollado en **.NET 8 / C#**, desplegado al **100% en Railway** (contenedor Docker + base de datos MySQL 8), accesible públicamente.
 
| Servicio | Endpoints principales | Estado |
|---|---|---|
| Auth | `POST /auth/login`, `POST /auth/forgot-password` | Integrado |
| Users | `POST /users`, `GET /users`, `GET/PATCH/DELETE /auth/users/{id}` | Integrado |
| Huariques | `GET /huariques`, `GET /huariques/{id}`, `POST`, `PATCH`, `DELETE /huariques/{id}`, `GET /huariques/suggestions` | Integrado |
| Categories | `GET /categories` | Integrado |
| Reviews | `GET /reviews`, `POST /reviews` | Integrado |
| Preferences | `GET /preferences`, `PUT /preferences` | Integrado |
| Notifications | `GET /notifications`, `PATCH /notifications/{id}/read` | Integrado |
| Plans / Subscriptions | `GET /plans`, `GET/POST /subscriptions` | Integrado |
| Promos | `GET/POST/PATCH/DELETE /promos`, `POST /promos/{id}/use` | Integrado |
| Reports | `POST /reports` | Integrado |
 
**Evidencia de despliegue:**
- Backend público: https://huariquehub-backend.up.railway.app
- Repositorio: https://github.com/HuariqueHub/HuariqueHub-Backend
---

### 5.2.7. RESTful API documentation

La documentación de la API está publicada mediante **Swagger/OpenAPI**, accesible directamente desde el navegador:
 
📄 **Swagger:** https://huariquehub-backend.up.railway.app/swagger
 
Esta documentación cubre todos los servicios integrados durante los tres sprints: huariques, usuarios, categorías, reseñas, preferencias, notificaciones, planes, suscripciones, promociones y reportes — permitiendo consultar contratos, parámetros y respuestas de cada endpoint.

### 5.2.8. Team Collaboration Insights

## 5.3. Video About-the-Product

En esta sección se presenta la primera versión del video About-the-Product de PuntoSabor, orientado a los visitantes del Landing Page y usuarios potenciales de la aplicación.

![alt text](assets/aboutProduct.png)

**URL del video:** https://drive.google.com/drive/folders/1Iqb5Lz3YxKQMyos2Oyqczd73CZMvspKV?usp=drive_link

**Duración:** 2 minutos

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
