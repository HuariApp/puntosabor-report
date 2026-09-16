
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
| 0.1.0 | 09/09/206 | @CesarJrCR | docs: Agregar todos los puntos del informe |
| 0.1.1 | 13/09/206 | @CesarJrCR | docs: Agregar contenido para todos los capitulos |
| 0.1.2 | 13/09/206 | @CarlosAlb101 | docs: Agregar diagramas de clase de base de datos |
| 0.1.3 | 13/09/206 | @u202410772 | docs: Agregar userflows |
| 0.1.4 | 15/09/206 | @br1rodolfo| docs: Agragar style guidelines |

# Project Report Collaboration Insights

**Repositorio de la documentación del proyecto:** https://github.com/HuariApp/puntosabor-report.git

<img src="assets/Insight.png" alt="Collaboration Insigths">

# Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](#21-competidores)
        - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Personas](#231-user-personas)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
        - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Product Backlog](#33-product-backlog)
    - [3.4. Impact Mapping](#34-impact-mapping)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
        - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
            - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
            - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
        - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
        - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
        - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
        - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
    - [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
        - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
        - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
    - [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
        - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
        - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
        - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
        - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
    - [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
    - [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
        - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
        - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
        - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
    - [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
        - [4.9.1. Class Diagrams](#491-class-diagrams)
        - [4.9.2. Class Dictionary](#492-class-dictionary)
    - [4.10. Database Design](#410-database-design)
        - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)
- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Product Implementation & Deployment](#52-product-implementation--deployment)
        - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
        - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
        - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
        - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)
        - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
        - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
        - [5.2.7. RESTful API documentation](#527-restful-api-documentation)
        - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
    - [5.3. Video About-the-Product](#53-video-about-the-product)
- [Capítulo VI: Product Verification & Validation](#capítulo-vi-product-verification--validation)
    - [6.1. Testing Suites & Validation](#61-testing-suites--validation)
        - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
        - [6.1.2. Core Integration Tests](#612-core-integration-tests)
        - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
        - [6.1.4. Core System Tests](#614-core-system-tests)
    - [6.2. Static testing & Verification](#62-static-testing--verification)
        - [6.2.1. Static Code Analysis](#621-static-code-analysis)
            - [6.2.1.1. Coding standard & Code conventions](#6211-coding-standard--code-conventions)
            - [6.2.1.2. Code Quality & Code Security](#6212-code-quality--code-security)
        - [6.2.2. Reviews](#622-reviews)
    - [6.3. Validation Interviews](#63-validation-interviews)
        - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
        - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
        - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
    - [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)
        - [6.4.1. Auditoría realizada](#641-auditoría-realizada)
            - [6.4.1.1. Información del grupo auditado](#6411-información-del-grupo-auditado)
            - [6.4.1.2. Cronograma de auditoría realizada](#6412-cronograma-de-auditoría-realizada)
            - [6.4.1.3. Contenido de auditoría realizada](#6413-contenido-de-auditoría-realizada)
        - [6.4.2. Auditoría recibida](#642-auditoría-recibida)
            - [6.4.2.1. Información del grupo auditor](#6421-información-del-grupo-auditor)
            - [6.4.2.2. Cronograma de auditoría recibida](#6422-cronograma-de-auditoría-recibida)
            - [6.4.2.3. Contenido de auditoría recibida](#6423-contenido-de-auditoría-recibida)
            - [6.4.2.4. Resumen de modificaciones para subsanar hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)
- [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)
    - [7.1. Continuous Integration](#71-continuous-integration)
        - [7.1.1. Tools and Practices](#711-tools-and-practices)
        - [7.1.2. Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
    - [7.2. Continuous Delivery](#72-continuous-delivery)
        - [7.2.1. Tools and Practices](#721-tools-and-practices)
        - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
    - [7.3. Continuous deployment](#73-continuous-deployment)
        - [7.3.1. Tools and Practices](#731-tools-and-practices)
        - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
    - [7.4. Continuous Monitoring](#74-continuous-monitoring)
        - [7.4.1. Tools and Practices](#741-tools-and-practices)
        - [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)
        - [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)
        - [7.4.4. Notification Pipeline Components](#744-notification-pipeline-components)
- [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
    - [8.1. Experiment Planning](#81-experiment-planning)
        - [8.1.1. As-Is Summary](#811-as-is-summary)
        - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
        - [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)
        - [8.1.4. Question Backlog](#814-question-backlog)
        - [8.1.5. Experiment Cards](#815-experiment-cards)
    - [8.2. Experiment Design](#82-experiment-design)
        - [8.2.1. Hypotheses](#821-hypotheses)
        - [8.2.2. Domain Business Metrics](#822-domain-business-metrics)
        - [8.2.3. Measures](#823-measures)
        - [8.2.4. Conditions](#824-conditions)
        - [8.2.5. Scale Calculations and Decisions](#825-scale-calculations-and-decisions)
        - [8.2.6. Methods Selection](#826-methods-selection)
        - [8.2.7. Data Analytics: Goals, KPIs and Metrics Selection](#827-data-analytics-goals-kpis-and-metrics-selection)
        - [8.2.8. Web and Mobile Tracking Plan](#828-web-and-mobile-tracking-plan)
    - [8.3. Experimentation](#83-experimentation)
        - [8.3.1. To-Be User Stories](#831-to-be-user-stories)
        - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)
        - [8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
            - [8.3.3.1. To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)
            - [8.3.3.2. Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)
            - [8.3.3.3. Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)
            - [8.3.3.4. Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)
            - [8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
            - [8.3.3.6. Team Collaboration Insights](#8336-team-collaboration-insights)
            - [Matriz de Evaluación Ética y de Impacto](#matriz-de-evaluación-ética-y-de-impacto)
        - [8.3.4. To-Be Validation Interviews](#834-to-be-validation-interviews)
            - [8.3.4.1. Diseño de Entrevistas](#8341-diseño-de-entrevistas)
            - [8.3.4.2. Registro de Entrevistas](#8342-registro-de-entrevistas)
    - [8.4. Experiment Aftermath & Analysis](#84-experiment-aftermath--analysis)
        - [8.4.1. Analysis and Interpretation of Results](#841-analysis-and-interpretation-of-results)
        - [8.4.2. Re-scored and Re-prioritized Question Backlog](#842-re-scored-and-re-prioritized-question-backlog)
    - [8.5. Continuous Learning](#85-continuous-learning)
        - [8.5.1. Shareback Session Artifacts: Learning Workflow](#851-shareback-session-artifacts-learning-workflow)
    - [8.6. To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)
        - [8.6.1. About-the-Product Intro Video](#861-about-the-product-intro-video)
        - [8.6.2. Resumen usando Gees FrameWork](#862-resumen-usando-gees-framework)
- [Conclusiones](#conclusiones)

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
| --- | --- | --- |
| Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software | **Cesar Jair Contreras Rojas:** Realicé el procesamiento y análisis sistemático de las entrevistas a los segmentos objetivo (Exploradores Gastronómicos y Dueños de Huariques), garantizando el tratamiento confidencial y transparente de los datos recolectados, así como la interpretación objetiva de los puntos de dolor reportados por los usuarios.<br><br>**Bruno Rodolfo Montalván Palomino:** Redacté el Acuerdo de Servicio - SaaS (5.2.4), estableciendo de forma transparente los derechos y obligaciones de los usuarios, incluyendo la política de cancelación de membresías sin cláusulas ambiguas ni abusivas. También verifiqué que la documentación de Style Guidelines (4.1) reflejara con precisión el código real de las cuatro plataformas, corrigiendo datos (colores, tipografías, radios de componentes) que no coincidían con la implementación real.<br><br>**Matias Francesco Razuri Alvarez:** Se elaboraron los Wireframes, Wireflow Diagrams, Mock-ups y User Flow Diagrams de la aplicación web PuntoSabor, aplicando principios de diseño inclusivo y asegurando que las interfaces reflejen información veraz y accesible para los usuarios. Se respetaron convenciones de usabilidad y se documentaron los flujos con happy paths y unhappy paths, reconociendo que un diseño incorrecto puede generar experiencias engañosas o perjudiciales para el usuario final. Asimismo, se mejoró la documentación de secciones previas del informe para garantizar mayor claridad y coherencia en la información presentada.<br><br>**Lopez Goitia, Carlos Alberto:** Elaboré el apartado de seguridad y privacidad para la gestión de usuarios, garantizando que el almacenamiento de credenciales y datos sensibles de los dueños de huariques cumpla con estándares de encriptación y protección de datos personales.<br><br>**Delgado Carrasco, Schneider:** Diseñé los modelos de base de datos relacionales y no relacionales asegurando la integridad referencial y estableciendo restricciones de acceso éticas para proteger las métricas comerciales internas de cada negocio frente a terceros. | **AV1:** En conjunto, el equipo ha definido la problemática del negocio y los perfiles de solución garantizando el manejo ético y confidencial de la información obtenida en las entrevistas a los segmentos objetivo, delimitando con honestidad técnica el alcance de la plataforma. |
| Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales | **Cesar Jair Contreras Rojas:** Sinteticé las necesidades, frustraciones y expectativas clave identificadas en el análisis de entrevistas para evaluar el impacto socioeconómico que genera la plataforma en la visibilización de pequeños huariques y en la mejora de la experiencia de descubrimiento gastronómico.<br><br>**Bruno Rodolfo Montalván Palomino:** Al definir la política de cancelación y reembolsos en el Acuerdo de Servicio, evalué su impacto económico sobre los dueños de huarique, un segmento con recursos limitados, buscando que la condición fuera razonable y no perjudicara a los pequeños emprendedores que el proyecto busca beneficiar.<br><br>**Matias Francesco Razuri Alvarez:** Al diseñar los User Flow Diagrams y Wireflow Diagrams, se consideró el impacto social de la plataforma PuntoSabor en comunidades locales, dado que la solución busca visibilizar y apoyar a pequeños negocios gastronómicos (huariques) que operan en contextos económicos vulnerables. Se diseñaron flujos para el segmento propietario que facilitan el acceso a herramientas digitales sin requerir conocimientos técnicos avanzados, contribuyendo a la inclusión digital de emprendedores locales.<br><br>**Lopez Goitia, Carlos Alberto:** Evalué el impacto de la latencia y el consumo de datos móviles en la app, optimizando las peticiones al servidor para que los usuarios finales con planes de datos limitados puedan navegar por el catálogo sin un consumo excesivo de recursos.<br><br>**Delgado Carrasco, Schneider:** Analicé la viabilidad técnica y el costo de infraestructura en la nube para el despliegue del backend, asegurando que los costos operativos permitan mantener tarifas accesibles para los microempresarios gastronómicos. | **AV1:** De forma colaborativa, el equipo evaluó el impacto socioeconómico y ambiental de la solución mediante el análisis competitivo, el desarrollo del Lean UX Canvas y la definición de escenarios As-Is y To-Be orientados a optimizar recursos. |
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de sistemas de información | **Cesar Jair Contreras Rojas:** Elaboré los diagramas de componentes de la arquitectura del sistema para definir la estructura modular de la solución y colaboré en la gestión organizada de los entregables técnicos requeridos por el equipo.<br><br>**Bruno Rodolfo Montalván Palomino:** Colaboré en el repositorio compartido de GitHub aportando en secciones de Style Guidelines, To-Be Scenario Mapping y el Acuerdo de Servicio, coordinando con commits siguiendo Conventional Commits y validando la información contra el trabajo ya entregado por otros integrantes antes de escribir contenido nuevo.<br><br>**Matias Francesco Razuri Alvarez:** Se colaboró activamente con el equipo en la definición del diseño de la aplicación web, asumiendo la responsabilidad de las secciones 4.6.1 (Wireframes), 4.6.2 (Wireflow Diagrams), 4.6.3 (Mock-ups) y 4.6.4 (User Flow Diagrams). Se coordinó con los demás integrantes para que los flujos diseñados fueran consistentes con los User Stories y Epics definidos por el equipo, asegurando coherencia entre el diseño y los requisitos funcionales establecidos colectivamente.<br><br>**Lopez Goitia, Carlos Alberto:** Coordiné la integración de la API REST del backend con los componentes de la interfaz móvil, asegurando que las respuestas de los endpoints coincidan con la estructura de datos requerida por el equipo de frontend.<br><br>**Delgado Carrasco, Schneider:** Participé en la estructuración del Product Backlog técnico, desglosando los requerimientos del sistema en User Stories orientadas a la arquitectura e implementando pruebas de rendimiento para validar el backend. | **AV1:** El grupo trabajó de manera coordinada organizando el Product Backlog, definiendo la arquitectura del sistema (DDD), los diagramas de base de datos y la gestión del código fuente en entornos compartidos para garantizar entregables técnicos eficientes. |
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de tecnologías de la información. | **Cesar Jair Contreras Rojas:** Modelé los wireflows de la aplicación conectando las pantallas clave de la experiencia de usuario y traduciendo directamente los requerimientos del dominio de los huariques y exploradores gastronómicos en un flujo de navegación intuitivo.<br><br>**Bruno Rodolfo Montalván Palomino:** Profundicé en el dominio de la gastronomía local informal (huariques) al redactar el Acuerdo de Servicio y validar la documentación de diseño, familiarizándome con dinámicas del sector como los modelos de membresía para pequeños negocios y sus limitaciones tecnológicas típicas.<br><br>**Matias Francesco Razuri Alvarez:** A través del diseño de los flujos y pantallas de PuntoSabor, se profundizó en el dominio de la gastronomía local peruana, específicamente en el ecosistema de los huariques como tipo de negocio con características propias: informalidad, dependencia de la clientela local, ausencia de presencia digital y necesidad de herramientas simples. Se diseñaron flujos diferenciados para dos segmentos: el explorador (usuario consumidor) y el propietario (dueño del huarique), reflejando un entendimiento claro de sus necesidades y comportamientos dentro de este dominio.<br><br>**Lopez Goitia, Carlos Alberto:** Modelé el subdominio de geolocalización y búsqueda por cercanía, traduciendo las reglas de negocio del sector gastronómico sobre radio de alcance y disponibilidad de platos en tiempo real.<br><br>**Delgado Carrasco, Schneider:** Estructuré el Bounded Context de gestión de menús y promociones, alineando el esquema de datos a la dinámica operativa real de los huariques y su constante cambio de oferta diaria. | **AV1:** El equipo investigó a fondo el dominio del mercado mediante el levantamiento de requerimientos, la construcción del Ubiquitous Language, el perfilado de User Personas y la estructuración del Impact Mapping adaptado a las necesidades del sector. |
| Conocimientos de nuevos métodos de colaboración y comunicación | **Cesar Jair Contreras Rojas:** Utilicé herramientas modernas de diseño y maquetación colaborativa para la creación iterativa de los wireflows y coordiné la integración del análisis de entrevistas en la documentación del repositorio.<br><br>**Bruno Rodolfo Montalván Palomino:** Utilicé GitHub para control de versiones y commits siguiendo buenas prácticas de gestión para asegurar que la documentación se mantenga precisa.<br><br>**Matias Francesco Razuri Alvarez:** Se utilizaron herramientas modernas de diseño y documentación para elaborar los artefactos de UX/UI de la entrega, incluyendo la generación de Mock-ups en HTML para facilitar su importación a Figma mediante la técnica "HTML to Figma", optimizando los tiempos de trabajo colaborativo. Se aplicaron convenciones de nomenclatura y estructura acordadas con el equipo para mantener consistencia en los archivos entregados. Además, se mejoró la documentación de secciones previas del informe aplicando las convenciones de Markdown y GitFlow definidas por el equipo en el repositorio de GitHub.<br><br>**Lopez Goitia, Carlos Alberto:** Implementé flujos de integración continua (CI/CD) utilizando GitHub Actions para automatizar las pruebas unitarias y la validación de código antes de mergear ramas a la producción.<br><br>**Delgado Carrasco, Schneider:** Utilicé herramientas de documentación de APIs como Postman y Swagger para mantener un catálogo de endpoints actualizado y accesible de forma transparente para todo el equipo de desarrollo. | **AV1:** En conjunto, el equipo adoptó metodologías ágiles e innovadoras como Lean UX Process, diagramado UI/UX en herramientas colaborativas, y flujos de trabajo basados en Source Code Management y DevOps para asegurar una comunicación fluida e integrada. |

# Capítulo I: Introducción

## 1.1. Startup Profile

HuariApp es una startup dedicada a la creación de soluciones tecnológicas diseñadas para impulsar la competitividad y el crecimiento de pequeños comercios locales, con un énfasis particular en el rubro gastronómico. Su propuesta central, PuntoSabor, consiste en una plataforma móvil que vincula a los comensales con "huariques", establecimientos de cocina tradicional que destacan por su autenticidad y calidad, pero que suelen carecer de exposición en el entorno digital.

El proyecto surge para resolver la brecha de visibilidad que enfrentan estos negocios frente a las grandes cadenas en las aplicaciones convencionales. 

Mediante una interfaz intuitiva, la herramienta permite a la comunidad descubrir y recomendar estos locales, validando un modelo de negocio sostenible basado en planes de visibilidad y membresías que fortalecen el ecosistema emprendedor local.

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo
<table border="1">
  <thead>
    <tr>
      <th>Foto</th>
      <th>Nombre completo</th>
      <th>Código</th>
      <th>Carrera</th>
      <th>Habilidades técnicas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td><img src="assets/chapter-1/members/Matias.png"
       alt="Matias Francesco Razuri Alvarez"></td>
      <td>Matias Francesco Razuri Alvarez</td>
      <td>u202410772</td>
      <td>Ingeniería de Software</td>
      <td>Soy un estudiante de Ingeniería de Software, tengo conocimientos en lenguaje C++, Python, tecnologías web (HTML/CSS), bases de datos SQL y NoSQL (MongoDB), integración de APIs, patrones de diseño de software y metodologías ágiles (Scrum). Tengo varias habilidades en trabajo en equipo, resolución de problemas, organización orientada a entregas anticipadas y apertura para incorporar diversos aportes en proyectos de software.</td>
    </tr>
    <tr>
      <td><img src="assets/chapter-1/members/Bruno.jpg"
       alt="Bruno Rodolfo Montalván Palomino"></td>
      <td>Bruno Rodolfo Montalván Palomino</td>
      <td>u202411282</td>
      <td>Ingeniería de Software</td>
      <td>Soy un estudiante de Ingeniería de Software, con conocimientos en programación con Python, desarrollo Full Stack, bases de datos SQL y MongoDB, diseño y consumo de APIs, arquitectura de software, Git y control de versiones. Habilidades en análisis y resolución de problemas, diseño de soluciones, desarrollo de aplicaciones y trabajo colaborativo.</td>
    </tr>
    <tr>
      <td>
  <img src="assets/chapter-1/members/schneider.jpeg"
       alt="Schneider Carlos Alberto Delgado Carrasco">
</td>
      <td>Schneider Carlos Alberto Delgado Carrasco</td>
      <td>u202321843</td>
      <td>Ingeniería de Software</td>
      <td>Soy estudiante de Ingeniería de Software en la UPC, con conocimientos en programación y bases de datos. Me interesa la tecnología, la innovación y el desarrollo de soluciones digitales que mejoren la vida de las personas. Estoy comprometido con mi formación y busco nuevos retos que me permitan crecer a nivel académico y personal.</td>
    </tr>
            <tr>
      <td>
  <img src="assets/chapter-1/members/cesar.png"
       alt="Cesar Jair Contreras Rojas">
</td>
      <td>Cesar Jair Contreras Rojas</td>
      <td>u20241d995</td>
      <td>Ingeniería de Software</td>
      <td>Soy un estudiante de ing. de software de la UPC, tengo conocimientos de programación al igual que todos mis compañeros. Me gusta encontrar soluciones tecnológicas a problemas de mundo real</td>
    </tr>
  </tbody>
</table>



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

Para la elaboración del To-Be Scenario Mapping, el equipo siguió un proceso estructurado en cuatro etapas. Primero, en la etapa de **preparación**, se revisaron los As-Is Scenario Mapping ya construidos para ambos segmentos, identificando los puntos de fricción marcados en las filas de Thinking y Feeling como los elementos prioritarios a transformar. Luego, en la **lluvia de ideas individual**, cada integrante propuso de forma independiente cómo debería sentirse y pensar el usuario en cada fase si PuntoSabor ya existiera y resolviera esas fricciones, apoyándose en las funcionalidades definidas en el Solution Profile. Posteriormente, en la etapa de **revisión**, el equipo consolidó las propuestas individuales, descartando duplicados y unificando el lenguaje. Finalmente, se procedió a la **identificación y nombramiento de fases como columnas**, manteniendo la misma cantidad y secuencia de fases del As-Is para facilitar la comparación directa entre ambos mapas.

Acá se muestran las capturas del To-Be Scenario Mapping de cada segmento objetivo.

#### To-Be Scenario Mapping — Segmento 1: Exploradores Gastronómicos

<img src="./assets/ToBeScenarioMapping_seg-1.png" alt="To-Be Scenario seg-1" width="1000px">  

**Comparación con el As-Is y cambios que ofrece el To-Be:**
- En **Descubrimiento**, el As-Is mostraba frustración por no encontrar nada distinto a las cadenas grandes; el To-Be elimina esa fricción mediante un buscador especializado exclusivamente en huariques.
- En **Selección inicial**, la desconfianza hacia reseñas potencialmente falsas se transforma en confianza, gracias a un sistema de reseñas verificadas propio de la plataforma (no disperso entre redes sociales).
- En **Visita**, la duda de "ojalá sea tan bueno como en las fotos" disminuye porque la información proviene de una comunidad especializada y no de publicidad pagada de grandes cadenas.
- En **Evaluación posterior**, el deseo insatisfecho de "un espacio especializado solo para huariques" pasa a estar resuelto: PuntoSabor es exactamente ese espacio, y el usuario ahora contribuye activamente a él.

#### To-Be Scenario Mapping — Segmento 2: Dueños de Huariques

<img src="./assets/ToBeScenarioMapping_seg-2.png" alt="To-Be Scenario seg-2" width="1000px">

**Comparación con el As-Is y cambios que ofrece el To-Be:**
- En **Promoción**, la sensación de no poder competir con restaurantes grandes se reemplaza por una herramienta diseñada específicamente para negocios pequeños, sin costos ni complejidad técnica.
- En **Registro de información**, el proceso manual en cuadernos/Excel (que generaba estrés y cansancio) se sustituye por un registro digital simple desde el propio celular del propietario.
- En **Visibilidad online**, la frustración de "casi nadie me sigue" se transforma en aparición activa dentro de las búsquedas de usuarios reales interesados en huariques, sin depender de saber usar redes sociales.
- En **Relación con clientes**, la impotencia por falta de herramientas da paso a una comunicación directa y bidireccional mediante reseñas y notificaciones, algo que antes no existía en su proceso.

**Resumen de fases:**

| Segmento | Fases As-Is | Fases To-Be |
|---|---|---|
| Exploradores Gastronómicos | Descubrimiento de opciones, Selección inicial, Visita al huarique, Evaluación posterior | Se mantienen las mismas 4 fases; cambia la experiencia dentro de cada una |
| Dueños de Huariques | Promoción tradicional, Registro de información, Visibilidad online, Relación con clientes, | Se mantienen las mismas 4 fases |


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
