<div align="center">

# Universidad Peruana de Ciencias Aplicadas (UPC)
## Ingeniería de Software

![Logo de la UPC](./assets/logo-upc.png)

### Desarrollo de Soluciones IoT (1ASI0572)
**Ciclo Académico:** 2026-10  
**NRC:** 6785  

**Profesor:** Marco Antonio Leon Baca

# Informe de Trabajo Final

**Startup:** FuelTrack  
**Producto:** FuelTrack  

### Relación de Integrantes:
U202310425 - AGUIRRE CASTILLO, Sergio Cesar

U20221G068 - ALMERCO ROJAS, Jocelyn Damaly

U202213278 - ESPEJO GAMARRA, Bryan Ronald

U202113111 - IPARRAGUIRRE RUEDA, Cristian Luis

U20221C275 - LUQUE MINAYA, Renzo Andrés

**Mes y año:** Abril 2026

</div>

<br>

---

## Registro de Versiones del Informe
El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto.

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="7" style="text-align: center; vertical-align: middle;"><b>TB1</b></td>
      <td>11/04/2026</td>
      <td>Aguirre Castillo, Sergio Cesar</td>
      <td>Desarrollo del capítulo 3</td>
    </tr>
    <tr>
      <td>14/04/2026</td>
      <td>Jocelyn Damaly Almerco almeroc Rojas</td>
      <td>Desarrollo puntos 2.1, 2.3, 2.3.1</td>
    </tr>
    <tr>
      <td>16/04/2026</td>
      <td>Iparraguirre Rueda, Cristian Luis</td>
      <td>Desarrollo el capítulo 1 y punto 3.2</td>
    </tr>
    <tr>
      <td>18/04/2026</td>
      <td>Aguirre Castillo, Sergio Cesar</td>
      <td>Desarrollo de los puntos 2.3.2 a 2.3.5</td>
    </tr>
    <tr>
      <td>20/04/2026</td>
      <td>Jocelyn Damaly Almerco almeroc Rojas</td>
      <td>Revisión general del documento</td>
    </tr>
    <tr>
      <td>20/04/2026</td>
      <td>Iparraguirre Rueda, Cristian Luis</td>
      <td>Desarrollo de conclusiones y recomendaciones del proyecto</td>
    </tr>
    <tr>
      <td>20/04/2026</td>
      <td>Bryan Ronald Espejo Gamarra</td>
      <td>Elaborar presentación tras revisión del documento</td>
    </tr>
    <tr>
     <table>
  <thead>
## Project Report Collaboration Insights
El repositorio para el Project Report en la organización de GitHub del equipo se encuentra en el siguiente enlace:
* **URL del Repositorio:** [https://github.com/UPC-pre-1ASI0572-2601-6785-Grupo5/report](https://github.com/UPC-pre-1ASI0572-2601-6785-Grupo5/report)

Durante la elaboración de esta entrega, el equipo colaboró utilizando GitFlow. *(Nota: Aquí se insertarán las capturas en imagen de los analíticos de colaboración y commits en GitHub antes de la entrega final)*.

## Contenido
 
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmento objetivo](#13-segmento-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation-&-analysis)
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
  - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
    - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
        - [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
            - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
            - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
            - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
        - [4.1.2. Context Mapping](#412-context-mapping)
        - [4.1.3. Software Architecture](#413-software-architecture)
            - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
            - [4.1.3.2. Software Architecture   Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
             - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
            - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
    - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
        - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context-bounded-context-name)
            - [4.2.X.1. Domain Layer](#42x1-domain-layer)
            - [4.2.X.2. Interface Layer](#42x2-interface-layer)
            - [4.2.X.3. Application Layer](#42x3-application-layer)
            - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
            - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
                - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
    - [5.1. Style Guidelines](#51-style-guidelines)
        - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
        - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
    - [5.2. Information Architecture](#52-information-architecture)
        - [5.2.1. Organization Systems](#521-organization-systems)
        - [5.2.2. Labeling Systems](#522-labeling-systems)
        - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
        - [5.2.4. Searching Systems](#524-searching-systems)
        - [5.2.5. Navigation Systems](#525-navigation-systems)
    - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
        - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
        - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
    - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
        - [5.4.1. Applications Wireframes](#541-applications-wireframes)
        - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
        - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
        - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
    - [5.5. Applications Prototyping](#55-applications-prototyping)
    - [5.6. IoT Device Design](#56-iot-device-design)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
    - [6.1. Software Configuration Management](#61-software-configuration-management)
        - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
        - [6.1.2. Source Code Management](#612-source-code-management)
        - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
        - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
    - [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
        - [6.2.X. Sprint n](#62x-sprint-n)
            - [6.2.X.1. Sprint Planning n](#62x1-sprint-planning-n)
            - [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
            - [6.2.X.3. Sprint Backlog n](#62x3-sprint-backlog-n)
            - [6.2.X.4. Development Evidence for Sprint Review](#62x4-development-evidence-for-sprint-review)
            - [6.2.X.5. Testing Suite Evidence for Sprint Review](#62x5-testing-suite-evidence-for-sprint-review)
            - [6.2.X.6. Execution Evidence for Sprint Review](#62x6-execution-evidence-for-sprint-review)
            - [6.2.X.7. Services Documentation Evidence for Sprint Review](#62x7-services-documentation-evidence-for-sprint-review)
            - [6.2.X.8. Software Deployment Evidence for Sprint Review](#62x8-software-deployment-evidence-for-sprint-review)
            - [6.2.X.9. Team Collaboration Insights during Sprint](#62x9-team-collaboration-insights-during-sprint)
    - [6.3. Validation Interviews](#63-validation-interviews)
        - [6.3.1. Interview Design](#631-interview-design)
        - [6.3.2. Interview Records](#632-interview-records)
        - [6.3.3. Heuristic Evaluations](#633-heuristic-evaluations)
    - [6.4. Video About-the-Product](#64-video-about-the-product)

- [Conclusiones](#conclusiones)

    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Video About-the-Team](#video-about-the-team)

- [Bibliografía](#bibliografía)

- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome
Objetivo general, ABET – EAC - Student Outcome 7: Aprendizaje Continuo y Autónomo.

| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **Aguirre Castillo, Sergio Cesar** <br> **TB1:** Actualicé y apliqué conocimientos en desarrollo de software utilizando lenguajes como Python, C# y JavaScript durante el desarrollo de FuelTrack. Participé en la implementación de funcionalidades del sistema y reforcé buenas prácticas de programación para mejorar la calidad del código. <br><br> **Almerco Rojas, Jocelyn Damaly** <br> **TB1:** Actualicé y apliqué conocimientos en diseño y modelado de software, elaborando diagramas y apoyando en la documentación técnica del sistema FuelTrack, asegurando una estructura clara y organizada. <br><br> **Espejo Gamarra, Bryan Ronald** <br> **TB1:** Actualicé conocimientos en backend, bases de datos y DevOps, participando en la configuración y soporte técnico del sistema FuelTrack, asegurando su correcto funcionamiento. <br><br> **Iparraguirre Rueda, Cristian Luis** <br> **TB1:** Actualicé conocimientos en desarrollo de software utilizando lenguajes como Python, C++ y C#, apoyando en la implementación de funcionalidades del sistema y fortaleciendo mis habilidades técnicas. <br><br> **Luque Minaya, Renzo Andrés** <br> **TB1:** Actualicé conocimientos en desarrollo frontend, despliegue en la nube y seguridad, participando en la construcción de interfaces y en la configuración del sistema FuelTrack. | **Aguirre Castillo, Sergio Cesar** <br> **TB1:** La actualización de conocimientos permitió mejorar la calidad del desarrollo y optimizar la implementación de funcionalidades del sistema. <br><br> **Almerco Rojas, Jocelyn Damaly** <br> **TB1:** La actualización en diseño y documentación permitió estructurar de manera clara el sistema, facilitando su desarrollo. <br><br> **Espejo Gamarra, Bryan Ronald** <br> **TB1:** La actualización en backend y bases de datos permitió mejorar el rendimiento y la estabilidad del sistema. <br><br> **Iparraguirre Rueda, Cristian Luis** <br> **TB1:** La actualización de conocimientos técnicos permitió fortalecer las competencias en programación y contribuir al desarrollo del sistema. <br><br> **Luque Minaya, Renzo Andrés** <br> **TB1:** La actualización en frontend y despliegue permitió mejorar la experiencia de usuario y la disponibilidad del sistema. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.** | **Aguirre Castillo, Sergio Cesar** <br> **TB1:** Reconocí la importancia del aprendizaje continuo al investigar nuevas tecnologías y buenas prácticas de desarrollo para mejorar mi desempeño en FuelTrack. <br><br> **Almerco Rojas, Jocelyn Damaly** <br> **TB1:** Reconocí la necesidad del aprendizaje continuo al investigar nuevas herramientas de modelado y documentación para mejorar la calidad del sistema. <br><br> **Espejo Gamarra, Bryan Ronald** <br> **TB1:** Reconocí la importancia del aprendizaje continuo al investigar nuevas tecnologías de backend y DevOps para optimizar el sistema. <br><br> **Iparraguirre Rueda, Cristian Luis** <br> **TB1:** Reconocí la necesidad del aprendizaje continuo al reforzar conocimientos en programación y nuevas herramientas de desarrollo. <br><br> **Luque Minaya, Renzo Andrés** <br> **TB1:** Reconocí la importancia del aprendizaje continuo al investigar nuevas tecnologías de frontend, cloud y seguridad para mejorar el sistema FuelTrack. | **Aguirre Castillo, Sergio Cesar** <br> **TB1:** El aprendizaje continuo permite mantenerse actualizado y desarrollar soluciones más eficientes y escalables. <br><br> **Almerco Rojas, Jocelyn Damaly** <br> **TB1:** El aprendizaje permanente permite mejorar la calidad del diseño y la documentación del software. <br><br> **Espejo Gamarra, Bryan Ronald** <br> **TB1:** El aprendizaje continuo permite optimizar el rendimiento del sistema y adaptarse a nuevas tecnologías. <br><br> **Iparraguirre Rueda, Cristian Luis** <br> **TB1:** El aprendizaje permanente fortalece las habilidades técnicas necesarias para el desarrollo de software. <br><br> **Luque Minaya, Renzo Andrés** <br> **TB1:** El aprendizaje continuo permite mejorar la experiencia de usuario y la seguridad del sistema. |






#### 6.2.1.1. Sprint Planning 1.
En el Sprint Planning 1, se llevó a cabo una sesión de planificación para la elaboración de la primera versión de las soluciones de FuelTrack. Se dividieron las secciones a programar entre los integrantes, además se determinó el plazo de entrega de estas tareas.

<table>
  <thead>
    <tr>
      <th style="text-align:center">Sprint #</th>
      <th style="text-align:center">Sprint 1</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Date</td>
      <td style="text-align:center">05-04-2026</td>
    </tr>
    <tr>
      <td style="text-align:center">Time</td>
      <td style="text-align:center">08:00 pm</td>
    </tr>
    <tr>
      <td style="text-align:center">Location</td>
      <td style="text-align:center">Google Meet</td>
    </tr>
    <tr>
      <td style="text-align:center">Prepared By</td>
      <td style="text-align:center">Sergio Aguirre</td>
    </tr>
    <tr>
      <td style="text-align:center">Attendees</td>
      <td style="text-align:center">Sergio Aguirre, Jocelyn Almerco, Bryan Espejo, Cristian Iparraguirre y Renzo Luque</td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint n – 1 Review Summary </td>
      <td style="text-align:center">Al ser el 1er sprint, aun no se contempla un review de un sprint anterior.</td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint n – 1 Retrospective Summary </td>
      <td style="text-align:center">Al ser el 1er sprint, aun no se contempla un review de un sprint anterior.</td>
    </tr>
    <tr>
      <td colspan="2"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 1 Goal</td>
      <td style="text-align:center">Implementar la primera versión de la Landing Page, autenticación de usuarios y registro básico de pedidos.</td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 1 Velocity</td>
      <td style="text-align:center">45</td>
    </tr>
    <tr>
      <td style="text-align:center">Sum of Story Points</td>
      <td style="text-align:center">45</td>
    </tr>
  </tbody>
</table>

#### 6.2.1.2. Aspect Leaders and Collaborators.

<table>
  <tr>
    <td> <strong>Team Member </td>
    <td> <strong>Github Username </td>
    <td> <strong>Sprint 1 Leader (L) / Collaborator (C) </td> 
  </tr>
  <tr>
    <td> Sergio Aguirre </td>
    <td> seratt15a </td>
    <td> Leader (L) </td>
  </tr>
  <tr>
    <td> Jocelyn Almerco </td>
    <td> Damaly29 </td>
    <td> Collaborator (C) </td>
  </tr>
  <tr>
    <td> Bryan Espejo </td>
    <td> SaeBryxn </td>
    <td>  Collaborator (C) </td>
  </tr>
  <tr>
    <td> Cristian Iparraguirre </td>
    <td> cristianipa7 </td>
    <td>  Collaborator (C) </td>
  </tr>
  <tr>
    <td> Renzo Luque </td>
    <td> renzoluquem </td>
    <td>  Collaborator (C) </td>
  </tr>
</table>

#### 6.2.1.3. Sprint Backlog 1.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td   colspan="7"> <strong>Sprint 1</strong> </td>
  </tr>
   <tr>
    <td   colspan="2"> <strong>User Story</strong></td>
    <td   colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>Description</strong></td>
    <td  > <strong>Estimation (Hours)</strong></td>
    <td  > <strong>Assigned To</strong></td>
    <td  > <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!-- US13: Explorar landing -->
  <tr>
    <td rowspan="2">US13</td>
    <td rowspan="2">Explorar landing (pública)</td>
    <td>TA01</td>
    <td>Estructura de Landing Page</td>
    <td>Crear la estructura HTML/CSS de la Landing Page.</td>
    <td>3</td>
    <td>Jocelyn Almerco</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Despliegue y pruebas</td>
    <td>Desplegar el Frontend y verificar accesibilidad.</td>
    <td>2</td>
    <td>Cristian Iparraguirre</td>
    <td>Done</td>
  </tr>
  <!-- US14: Consultar Home pública -->
  <tr>
    <td rowspan="1">US14</td>
    <td rowspan="1">Consultar Home pública</td>
    <td>TA01</td>
    <td>Diseño de la vista Home</td>
    <td>Implementar la vista Home con el resumen de la solución.</td>
    <td>3</td>
    <td>Renzo Luque</td>
    <td>Done</td>
  </tr>
  <!-- US15: Conocer About Us -->
  <tr>
    <td rowspan="2">US15</td>
    <td rowspan="2">Conocer About Us</td>
    <td>TA01</td>
    <td>Diseño de sección About Us</td>
    <td>Maquetar sección About Us con la información del equipo.</td>
    <td>2</td>
    <td>Bryan Espejo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Recopilación de información</td>
    <td>Agregar fotos y perfiles de los miembros.</td>
    <td>1</td>
    <td>Sergio Aguirre</td>
    <td>Done</td>
  </tr>
  <!-- US16: Entender cómo funciona -->
  <tr>
    <td rowspan="2">US16</td>
    <td rowspan="2">Entender cómo funciona</td>
    <td>TA01</td>
    <td>Diseño de sección Cómo funciona</td>
    <td>Crear los pasos del flujo de operación en la UI.</td>
    <td>3</td>
    <td>Renzo Luque</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Recursos gráficos</td>
    <td>Agregar iconos e imágenes explicativas.</td>
    <td>2</td>
    <td>Jocelyn Almerco</td>
    <td>Done</td>
  </tr>
  <!-- US17: Enviar contacto -->
  <tr>
    <td rowspan="2">US17</td>
    <td rowspan="2">Enviar contacto</td>
    <td>TA01</td>
    <td>Crear formulario HTML</td>
    <td>Maquetar el formulario de contacto en Frontend.</td>
    <td>2</td>
    <td>Cristian Iparraguirre</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Conectar validaciones</td>
    <td>Agregar validaciones de campos en el formulario.</td>
    <td>2</td>
    <td>Bryan Espejo</td>
    <td>Done</td>
  </tr>
  <!-- US08: Iniciar sesión -->
  <tr>
    <td rowspan="3">US08</td>
    <td rowspan="3">Iniciar sesión</td>
    <td>TA01</td>
    <td>Vista de Login</td>
    <td>Crear la vista de inicio de sesión en Frontend.</td>
    <td>2</td>
    <td>Renzo Luque</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Integración con Backend</td>
    <td>Conectar formulario de Login con el API.</td>
    <td>3</td>
    <td>Sergio Aguirre</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA03</td>
    <td>Almacenamiento de Token</td>
    <td>Guardar el token JWT de forma segura en el cliente.</td>
    <td>2</td>
    <td>Jocelyn Almerco</td>
    <td>Done</td>
  </tr>
  <!-- TS05: Autenticar (endpoint login) -->
  <tr>
    <td rowspan="2">TS05</td>
    <td rowspan="2">Autenticar (endpoint login)</td>
    <td>TA01</td>
    <td>Crear controlador Auth</td>
    <td>Implementar el controlador y rutas de autenticación.</td>
    <td>3</td>
    <td>Sergio Aguirre</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Lógica de verificación</td>
    <td>Validar credenciales contra la base de datos.</td>
    <td>4</td>
    <td>Cristian Iparraguirre</td>
    <td>Done</td>
  </tr>
  <!-- TS02: Emitir token de autenticación (JWT) -->
  <tr>
    <td rowspan="1">TS02</td>
    <td rowspan="1">Emitir token de autenticación (JWT)</td>
    <td>TA01</td>
    <td>Servicio JWT</td>
    <td>Configurar e implementar la emisión de tokens JWT.</td>
    <td>4</td>
    <td>Bryan Espejo</td>
    <td>Done</td>
  </tr>
  <!-- US09: Registrar cuenta nueva -->
  <tr>
    <td rowspan="2">US09</td>
    <td rowspan="2">Registrar cuenta nueva</td>
    <td>TA01</td>
    <td>Vista de Registro</td>
    <td>Crear la interfaz de registro de usuarios.</td>
    <td>3</td>
    <td>Jocelyn Almerco</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Integración de Registro</td>
    <td>Conectar formulario de registro con el API correspondiente.</td>
    <td>3</td>
    <td>Renzo Luque</td>
    <td>Done</td>
  </tr>
  <!-- TS01: Exponer endpoint de pedidos (POST) -->
  <tr>
    <td rowspan="2">TS01</td>
    <td rowspan="2">Exponer endpoint de pedidos (POST)</td>
    <td>TA01</td>
    <td>Modelo y Esquema</td>
    <td>Crear el modelo de la BD y esquema de validación para pedidos.</td>
    <td>4</td>
    <td>Cristian Iparraguirre</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Servicio y Controlador</td>
    <td>Implementar lógica para registrar un nuevo pedido.</td>
    <td>4</td>
    <td>Bryan Espejo</td>
    <td>Done</td>
  </tr>
  <!-- US01: Crear nuevo pedido -->
  <tr>
    <td rowspan="2">US01</td>
    <td rowspan="2">Crear nuevo pedido</td>
    <td>TA01</td>
    <td>Formulario de pedido</td>
    <td>Crear la vista para la solicitud de pedidos.</td>
    <td>4</td>
    <td>Sergio Aguirre</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Envío de datos</td>
    <td>Integrar vista con el endpoint POST de pedidos.</td>
    <td>3</td>
    <td>Renzo Luque</td>
    <td>Done</td>
  </tr>
</table>

#### 6.2.1.4. Development Evidence for Sprint Review.

#### 6.2.1.5. Testing Suite Evidence for Sprint Review.

#### 6.2.1.6. Execution Evidence for Sprint Review.

#### 6.2.1.7. Services Documentation Evidence for Sprint Review.

#### 6.2.1.8. Software Deployment Evidence for Sprint Review.

#### 6.2.1.9. Team Collaboration Insights during Sprint.
