
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

HuariApp es una startup dedicada a la creación de soluciones tecnológicas diseñadas para impulsar la competitividad y el crecimiento de pequeños comercios locales, con un énfasis particular en el rubro gastronómico. Su propuesta central, PuntoSabor, consiste en una plataforma móvil que vincula a los comensales con "huariques", establecimientos de cocina tradicional que destacan por su autenticidad y calidad, pero que suelen carecer de exposición en el entorno digital.

El proyecto surge para resolver la brecha de visibilidad que enfrentan estos negocios frente a las grandes cadenas en las aplicaciones convencionales. 

Mediante una interfaz intuitiva, la herramienta permite a la comunidad descubrir y recomendar estos locales, validando un modelo de negocio sostenible basado en planes de visibilidad y membresías que fortalecen el ecosistema emprendedor local.

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

| Foto | Nombre | Descripción |
| --- | --- | --- |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### Las 5W's y 2H's

#### What? (¿Qué?)
El problema central radica en que los huariques, negocios gastronómicos pequeños y poco conocidos que ofrecen comida tradicional, tienen una presencia casi nula en el entorno digital, lo que impide que los consumidores puedan acceder fácilmente a alternativas de comida auténtica y a precios razonables más allá de los restaurantes con mayor popularidad.

#### Why? (¿Por qué?)
Los grandes establecimientos y cadenas dominan las plataformas de comida digitales gracias a su mayor capacidad de inversión y volumen de operaciones, desplazando a los huariques que no disponen de los recursos para competir en ese terreno. Esto crea un vacío importante: los usuarios no logran encontrar estos lugares con facilidad, y los huariques pierden potenciales oportunidades de crecimiento.

#### Where? (¿Dónde?)
El fenómeno ocurre principalmente en zonas urbanas y comunidades donde los huariques tienen presencia física, pero carecen de representación digital. Se hace especialmente evidente en mercados hispanohablantes, donde la gastronomía local es culturalmente rica, pero aún escasamente digitalizada.

#### When? (Cuándo?)
Se trata de una problemática persistente, cuya gravedad ha aumentado con la acelerada transformación digital del mercado gastronómico en los últimos años.

#### Who? (¿Quién?)
Existen dos grupos directamente perjudicados:

1. Los propietarios de huariques, quienes enfrentan dificultades para captar clientes y sostenerse frente a la competencia de restaurantes y cadenas con mayor presencia en medios digitales.

2. Los usuarios que buscan experiencias gastronómicas locales, económicas y genuinas, pero no cuentan con herramientas digitales adecuadas para encontrarlas.

#### How? (¿Cómo?)
El problema se expresa en la escasa o inexistente promoción digital de estos negocios, su ausencia en aplicaciones y mapas de referencia, la poca interacción con posibles clientes y la carencia de una comunidad que los recomiende y divulgue.

#### How much? (¿Cuánto?)
Esta brecha representa no solo una oportunidad económica sin aprovechar para los dueños de huariques, sino también una pérdida del patrimonio gastronómico cultural. A escala de mercado, miles de negocios pequeños y millones de usuarios permanecen al margen del ecosistema digital gastronómico.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Cada enunciado sigue la estructura estandarizada de Lean UX: **situación actual → problema observado → consecuencia para el segmento → reencuadre como oportunidad**. De esta forma el problema queda delimitado, asociado a un segmento concreto y verificable, en lugar de presentarse como una necesidad general.

**Problem Statement 1 — Explorador gastronómico**

Las plataformas gastronómicas actuales (Google Maps, delivery, redes sociales) fueron diseñadas para conectar a las personas con lugares para comer. Sin embargo, hemos observado que estas plataformas priorizan restaurantes y cadenas con mayor inversión publicitaria, por lo que los huariques auténticos, cercanos y económicos quedan poco visibles o con información incompleta y desactualizada. Esto provoca que el explorador gastronómico invierta tiempo y no confíe en lo que encuentra al momento de elegir dónde comer. **¿Cómo podríamos ayudar a los exploradores gastronómicos a descubrir huariques auténticos y cercanos, con información confiable que respalde su decisión?**

**Problem Statement 2 — Dueño o administrador de huarique**

Las herramientas de promoción digital existentes fueron pensadas para negocios con presupuesto y experiencia técnica. Hemos observado que la mayoría de los dueños de huariques cuenta con recursos limitados y poca familiaridad con estas herramientas, por lo que no logran mantener su negocio visible ni actualizado en el entorno digital. Esto provoca que pierdan oportunidades de captar nuevos clientes frente a competidores con mayor presencia. **¿Cómo podríamos permitir que los dueños de huariques publiquen y gestionen su negocio de forma sencilla, sin procesos técnicos complejos, para aumentar su visibilidad?**

**Problem Statement 3 — Plataforma PuntoSabor (negocio)**

El mercado de aplicaciones gastronómicas está dominado por propuestas generalistas centradas en restaurantes y cadenas conocidas. Hemos observado que ningún actor relevante se especializa en huariques ni construye comunidad alrededor de la comida local auténtica, por lo que existe un segmento desatendido tanto de usuarios como de pequeños negocios. Esto representa una oportunidad de diferenciación y de generación de ingresos recurrentes que hoy nadie está capturando. **¿Cómo podríamos posicionar a PuntoSabor como la plataforma de referencia para descubrir huariques, mediante comunidad, visibilidad local y un modelo de membresías accesible?**

#### 1.2.2.2. Lean UX Assumptions

#### Business Assumptions
- Se estima que PuntoSabor logrará convocar a un número considerable de dueños de huariques que buscan mayor visibilidad digital a través de membresías o planes publicitarios.

- Se prevé que la implementación de planes de membresía o publicidad genere ingresos recurrentes y estables para la startup.

- Se considera que el mercado gastronómico local está preparado para adoptar soluciones digitales accesibles que impulsen a los pequeños negocios y mejoren la experiencia de descubrimiento para los usuarios.

- Se parte del supuesto de que una comunidad activa de usuarios y propietarios de huariques favorecerá el crecimiento orgánico y la fidelización dentro de la plataforma.

#### User Assumptions
- Se estima que los usuarios priorizan hallar opciones de comida local genuina, económica y diferente a las que ofrecen las grandes aplicaciones.

- Se espera que los usuarios no solo exploren huariques a través de la app, sino que también contribuyan con calificaciones y reseñas que orienten a otros.

- Se considera que una interfaz sencilla, combinada con acceso a fotografías, especialidades del lugar, rangos de precios y mapas integrados, motivará un uso frecuente de la plataforma.

- Se supone que funciones como guardar favoritos y consultar rankings impulsarán a los usuarios a volver y recomendar PuntoSabor en su entorno cercano.

- Se asume que los propietarios o administradores de huariques valorarán y encontrarán sencillo el proceso de registrar y gestionar su negocio dentro de la app, con miras a aumentar su visibilidad.

- Se espera que estos usuarios proporcionen información completa y actualizada-fotos, especialidades, precios-para enriquecer la experiencia de quienes los visiten.

- Se estima que beneficios como la membresía y la dinámica comunitaria fomentarán que los propietarios mantengan su perfil activo y atractivo.

#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que ofrecer una plataforma fácil e intuitiva para descubrir huariques auténticos y económicos aumentará la cantidad de usuarios que visitan estos negocios. Sabremos que esto es cierto cuando al menos el 60% de los usuarios activos reporten haber visitado un huarique recomendado en la plataforma durante el primer mes de uso.

- Creemos que permitir a los dueños de huariques registrar y gestionar su negocio con fotos, especialidades y precios incentivará su participación activa y mejorará la calidad del contenido disponible. Sabremos que esto es cierto cuando al menos el 50% de los huariques registrados actualicen su información o respondan a reseñas dentro de los primeros tres meses tras su registro.

- Creemos que la integración de mapas y funciones de geolocalización facilitará a los usuarios encontrar huariques cercanos, aumentando la interacción y el uso recurrente de la app. Sabremos que esto es cierto cuando al menos el 70% de las búsquedas y accesos diarios incluyan el uso del mapa durante el primer mes de lanzamiento.

- Creemos que un sistema confiable de reseñas y calificaciones incentivará la confianza en los usuarios y motivará a más personas a utilizar PuntoSabor como su app de referencia para descubrir huariques. Sabremos que esto es cierto cuando el 80% de los huariques tengan al menos cinco reseñas activas y una valoración promedio superior a 4 estrellas en los primeros tres meses.

- Creemos que la oferta de planes de membresía y publicidad atraerá a suficientes dueños de huariques para generar ingresos recurrentes sostenibles. Sabremos que esto es cierto cuando el 30% de los huariques registrados contraten al menos un plan pago durante los primeros seis meses.

#### 1.2.2.4. Lean UX Canvas

![alt text](<assets/LeanUXCanvas-PuntoSabor.png>)

## 1.3. Segmentos objetivo

### Exploradores Gastronómicos

- Edad: 18 a 40 años.

- Estilo de vida: Activos, curiosos, buscan descubrir comida auténtica y económica.

- Uso de tecnología: Frecuente, usuarios habituales de apps móviles y web para buscar lugares para comer.

- Necesidad principal: Encontrar huariques poco conocidos con buena sazón y precios accesibles.

- Beneficios buscados: Acceso a recomendaciones confiables, mapas con ubicación cercana, y sistema de reseñas para tomar decisiones informadas.

### Dueños y Administradores de Huariques

- Perfil: Emprendedores y pequeños negocios de comida tradicional o casera.

- Necesidad principal: Promocionar su negocio, aumentar la visibilidad y atraer nuevos clientes de manera sencilla, accesible y rentable.

- Beneficios buscados: Herramienta accesible para gestionar su información en la plataforma, recibir retroalimentación valiosa y utilizar planes de membresía o publicidad para crecer.

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
