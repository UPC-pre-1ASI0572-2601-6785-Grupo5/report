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

﻿##Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**FuelTrack** es una startup tecnológica fundada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), orientada a transformar la gestión de suministro de combustible en operaciones industriales críticas. A través de la integración de hardware IoT con una plataforma transaccional B2B, FuelTrack conecta a empresas solicitantes y proveedores mayoristas de hidrocarburos en un ecosistema digital unificado, brindando visibilidad en tiempo real sobre cada galón despachado, desde el tanque de la cisterna hasta el punto de entrega final.

A diferencia de las soluciones de software tradicionales, FuelTrack incorpora sensores embebidos en las unidades de transporte para monitorear de forma continua el nivel de combustible, la presión del tanque y la ubicación GPS de la flota. Esta telemetría se integra directamente con el flujo de pedidos, aprobaciones y comprobantes digitales de la plataforma, eliminando los puntos ciegos logísticos que hoy generan mermas, robos en tránsito y sobregiros presupuestales en sectores como minería, telecomunicaciones e infraestructura.

**Misión:**
Desarrollar soluciones tecnológicas que integren IoT y software transaccional para digitalizar y asegurar la cadena de suministro de hidrocarburos, eliminando la informalidad operativa y brindando trazabilidad total a empresas y proveedores en entornos industriales críticos.

**Visión:**
Convertirnos en el estándar de gestión inteligente de combustible B2B en Latinoamérica, siendo la plataforma de referencia para operaciones que exigen visibilidad financiera, control logístico y seguridad de carga en tiempo real.

### 1.1.2. Perfiles de integrantes del equipo


| Foto                                          | Nombre completo               | Código     | Carrera                | Habilidades técnicas y rol                                   |
|-----------------------------------------------|-------------------------------|------------|------------------------|--------------------------------------------------------------|
| <img width="260" height="280" alt="image" src="https://github.com/user-attachments/assets/dafe372e-7f1f-428c-bab5-933c2f00b5ba" /> | Aguirre Castillo, Sergio Cesar | U202310425 | Ingenieria de Software | Soy estudiante de la carrera de Ingeniería de Software, actualmente cursando el séptimo ciclo. Tengo un gran interés en adquirir nuevos conocimientos relacionados con mi área que me permitan fortalecer mis habilidades y prepararme para los retos del futuro profesional. Cuento con experiencia en diversos lenguajes de programación como Python, C++, PHP, C#, Java y JavaScript, además de conocimientos en desarrollo web utilizando HTML, CSS y manejo básico de bases de datos como MySQL, lo que me permite adaptarme a distintos entornos de desarrollo y seguir aprendiendo nuevas tecnologías. |
| <img width="260" height="280" alt="Cristian" src="../assets/foto_cristian.jpg" /> | Iparraguirre Rueda, Cristian Luis    | U202113111 | Ingeniería de Software | Soy estudiante de la carrera de Ingeniería de Software. Tengo interés en obtener nuevos conocimientos relacionados con mi carrera que me sean de utilidad para el futuro. Cuento con el conocimiento de diversos lenguajes Python, C++, PHP, C#. |
| <img width="260" height="100" alt="Cristian" src="../assets/foto_bryan.png" />           | Bryan Ronald Espejo Gamarra     | U202213278 | Ingeniería de Software | Soy estudiante de la carrera de Ingeniería de Software, con interés en adquirir y fortalecer conocimientos que aporten a mi desarrollo profesional. Cuento con habilidades en Backend, gestión de Bases de Datos, prácticas de DevOps y coordinación técnica de proyectos, lo que me permite comprender y participar en el desarrollo integral de soluciones de software. Además, poseo conocimientos en diversos lenguajes de programación como Python, C++, PHP y C#, los cuales he aplicado en distintos proyectos, fortaleciendo mi capacidad de análisis, diseño e implementación de sistemas. |
| ![Jocelyn Damaly Almerco Rojas](../assets/perfil_Jocelyn.jpg)          | Jocelyn Damaly Almerco Rojas     | u20221G068 | Ingeniería de Software | Soy estudiante de Ingeniería de Software. Tengo buen dominio en la elaboración de diagramas en C++ y manejo lenguajes como C++, SQL, CSS, HTML y JavaScript. Además, poseo conocimientos básicos en frameworks como Angular y Vue.js para el desarrollo frontend. Aporto al equipo con habilidades en análisis lógico, documentación técnica y diseño estructurado de software, contribuyendo a mantener la coherencia y calidad del proyecto.    |
| <img width="260" height="200" alt="Cristian" src="../assets/foto_renzo.png" /> | Renzo Andres Luque Minaya | U20221C275 | Ingeniería de Software | Estudiante de ingenieria de Software de 8vo ciclo en la UPC. Conocimiento en desarrollo Frontend, Backend, Cloud Deployment, Seguridad y Autenticación. Interes en nuevos conocimientos relacionados a la carrera y el futuro tech. |


## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

**Descripción del problema**
 
El sector de distribución de hidrocarburos en entornos industriales críticos —como minería, telecomunicaciones e infraestructura— enfrenta una paradoja operativa: a pesar de mover millones de dólares en combustible anualmente, la gestión de sus despachos sigue dependiendo de métodos informales como llamadas telefónicas, correos electrónicos y aplicaciones de mensajería. Esta desconexión entre el flujo físico del combustible y los sistemas de gestión genera pérdidas económicas significativas, riesgos de desabastecimiento y una opacidad financiera que dificulta la toma de decisiones en tiempo real.
 
La ausencia de telemetría integrada en las cisternas de transporte agrava el problema: los proveedores no pueden detectar mermas ni robos en ruta, los clientes no tienen visibilidad del estado real de su pedido, y los gerentes de logística operan con información desfasada que aumenta el riesgo de sobregiros presupuestales. La incorporación de tecnologías IoT representa la evolución natural para cerrar esta brecha entre el mundo físico y el sistema de gestión.
 
---
 
**Técnica 5W + 2H**
 
**What? (¿Qué?)**
La problemática central es la ausencia de un sistema integrado que conecte en tiempo real el estado físico de las cisternas de combustible —nivel de tanque, presión, ubicación GPS— con el flujo transaccional de pedidos, aprobaciones y comprobantes digitales entre empresas solicitantes y proveedores mayoristas. Esta desconexión genera mermas no detectadas, errores en la conciliación financiera y una trazabilidad prácticamente inexistente por despacho realizado.
 
**When? (¿Cuándo?)**
El problema se manifiesta de forma continua a lo largo de todo el ciclo de vida de un despacho: desde la generación manual del pedido hasta la entrega en campo, pasando por la validación del pago, la asignación de la cisterna y el monitoreo de la ruta. Se agudiza especialmente en operaciones nocturnas o en zonas remotas sin supervisión presencial, donde el riesgo de robo en tránsito es mayor.
 
**Where? (¿Dónde?)**
El problema ocurre principalmente en operaciones industriales ubicadas en zonas remotas o de difícil acceso —campamentos mineros, nodos de telecomunicaciones, obras de infraestructura— donde la infraestructura de control es limitada y la dependencia del combustible como insumo crítico es total. También afecta las bases logísticas de los proveedores mayoristas, donde la coordinación de despachos se realiza de forma manual y fragmentada.
 
**Who? (¿Quién?)**
Los principales afectados son los gerentes de logística y jefes de operaciones de empresas clientes, quienes carecen de visibilidad financiera en tiempo real; los controladores de flota y despachadores de proveedores mayoristas, que no pueden monitorear el estado de sus cisternas en ruta; y los choferes, que operan sin respaldo digital ante cualquier incidente durante el traslado.
 
**Why? (¿Por qué?)**
El problema persiste porque los métodos actuales de coordinación —correo, WhatsApp, papel— no tienen capacidad de integrarse con el estado físico real del combustible en tránsito. No existe un canal único que conecte la solicitud del cliente, la aprobación financiera, el monitoreo IoT de la cisterna y la generación automática del comprobante de entrega. Cada etapa opera de forma aislada, multiplicando los puntos de falla.
 
**How? (¿Cómo?)**
El problema se materializa cuando una cisterna sale a ruta sin que ningún sistema registre en tiempo real la variación del nivel de combustible. Cualquier pérdida —sea por robo, fuga o error de despacho— solo se detecta al comparar manualmente el volumen de salida con el de llegada, proceso que puede tomar horas o días. Paralelamente, el cliente no recibe actualizaciones automáticas del estado de su pedido y debe confirmar la recepción mediante llamadas o fotos enviadas por WhatsApp, lo que retrasa la facturación y la conciliación financiera.
 
**How Much? (¿Cuánto?)**
La magnitud del problema es considerable en términos económicos y operativos:
- El robo de combustible en tránsito (*"ordeño"*) representa pérdidas anuales de millones de dólares para las empresas de transporte en Latinoamérica.
- Más del 60% de los gerentes logísticos reportan dificultades para auditar el consumo exacto de combustible frente a lo presupuestado, debido a la fragmentación de la información en papel y canales dispersos.
- Las paradas no planificadas por desabastecimiento en operaciones extractivas o de infraestructura pueden costar decenas de miles de dólares por hora de inactividad.
- Se estima que la integración de telemetría y sistemas de gestión de flotas (FMS) puede reducir los tiempos de inactividad operativa hasta en un 25% y disminuir las mermas inexplicables en ruta de forma significativa.

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1: Procesos Operativos Manuales y Descoordinados**
Las empresas con operaciones críticas en campo y sus distribuidores mayoristas enfrentan serias dificultades al gestionar la solicitud y validación de despachos de combustible utilizando métodos manuales e informales (papel, correos, WhatsApp). Esta falta de estandarización genera retrasos, errores en la comunicación y cuellos de botella en la cadena de suministro.
*¿Cómo podemos crear una plataforma transaccional corporativa que elimine el uso de papel y automatice el flujo de solicitudes y aprobaciones de despachos de combustible entre clientes y proveedores, mejorando la eficiencia operativa?*

**Problem Statement 2: Riesgo de Sobregiros y Falta de Control Financiero**
Los gerentes de logística y operaciones tienen una visibilidad limitada y desfasada del "Burn Rate" (ritmo de gasto) frente a las líneas de crédito preaprobadas. Esta carencia de información en tiempo real aumenta significativamente el riesgo de sobregiros presupuestales y paralizaciones por falta de energía.
*¿Cómo podemos proveer un dashboard financiero interactivo que calcule y muestre en tiempo real el consumo por centros de costo y el ritmo de gasto, permitiendo un control proactivo del presupuesto?*

**Problem Statement 3: Puntos Ciegos Logísticos y Robo de Combustible**
Los proveedores mayoristas sufren pérdidas económicas debido al robo de combustible en ruta (mermas) y carecen de visibilidad sobre los signos vitales de su flota de cisternas. La incapacidad de monitorear en vivo el volumen de los tanques y detectar caídas bruscas de presión limita la respuesta rápida ante incidentes.
*¿Cómo podemos desarrollar un monitor logístico integrado con telemetría IoT que proporcione visibilidad en tiempo real del estado de los vehículos y genere alertas automáticas ante anomalías o posibles robos en ruta?*

**Problem Statement 4: Carencia de Trazabilidad y Auditoría en Despachos**
Las empresas enfrentan problemas de auditoría y demoras en la facturación debido a la dificultad de sustentar cada galón despachado con su respectiva Orden de Compra (OC), Centro de Costos y firma de recepción. La falta de evidencia digital inmutable retrasa los flujos de pago B2B.
*¿Cómo podemos diseñar un sistema de trazabilidad que garantice que cada entrega genere un comprobante digital (Voucher PDF) firmado y enlazado a la documentación financiera correspondiente, asegurando la transparencia total?*

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**
* **Necesidad de Solución Integral B2B:** Creemos que las empresas de infraestructura y minería, junto con sus proveedores, necesitan urgentemente un software de Field Service Management que integre telemetría IoT, control financiero y logística en tiempo real.
* **Plataforma Web y Móvil Accesible:** Creemos que el valor se entregará a través de un portal web corporativo (Cockpit) para los gerentes y, a futuro, una aplicación móvil offline-first para los choferes en zonas sin cobertura.
* **Clientes Iniciales:** Nuestros clientes iniciales serán empresas del sector minero, telecomunicaciones y construcción (ej. Minera Yanacocha, Gilat Peru) y grandes distribuidores de hidrocarburos.
* **Valor Principal:** El valor #1 que buscan los clientes es la garantía de abastecimiento sin sobregiros presupuestales, y para los proveedores, la prevención de robos y la aceleración de la facturación mediante guías digitales.
* **Modelo de Ingresos:** Generaremos ingresos mediante un modelo SaaS Multitenant B2B, cobrando suscripciones por volumen de transacciones o licencias de flota a las empresas distribuidoras.
* **Competencia y Diferenciación:** Nos diferenciamos de simples e-commerce o ERPs tradicionales al integrar hardware (sensores IoT) con software transaccional, creando un ecosistema inmutable y en tiempo real.

**User Assumptions**
* **Quién es el Usuario:** Gerentes de logística, jefes de operaciones en campo y controladores de flota / despachadores de empresas mayoristas.
* **Dónde Encaja el Producto:** FuelTrack se convierte en la herramienta central de operaciones diarias en las oficinas de logística y en los centros de control de monitoreo vehicular.
* **Problemas del Producto:** Existe el riesgo de resistencia al cambio tecnológico por parte de los choferes de cisternas. Se mitigará mediante interfaces de divulgación progresiva extremadamente simples y capacitaciones.

**User Outcomes**
* **Para el Cliente Corporativo (Demanda):** Visibilidad financiera total, prevención de desabastecimiento mediante pedidos ágiles (Wizard) y auditoría perfecta de cada galón consumido.
* **Para el Proveedor (Oferta):** Control telemétrico absoluto sobre sus cisternas, reducción drástica de robos en ruta y automatización de la recolección de firmas digitales para facturar más rápido.

**Business Outcomes**
* **Eficiencia Operativa:** Reducción sustancial del Lead Time (tiempo desde aprobación hasta entrega) y cumplimiento riguroso de los Acuerdos de Nivel de Servicio (SLA).
* **Posicionamiento en el Mercado:** Convertir a FuelTrack en el estándar de gestión de hidrocarburos B2B en operaciones críticas y zonas remotas.

**Features Importantes:**
* Wizard de Pedidos Inteligente (con cálculos de precios indexados).
* Dashboard de Inteligencia Operativa (Burn Rate, Centros de Costo).
* Monitor IoT Telemétrico (Integración con sensores DUT-E CAN, motor, batería).
* Radar y Alertas (Bloqueo remoto y detección de robos).
* Exportación de Vouchers Legales en PDF con firma digital.

#### 1.2.2.3. Lean UX Hypothesis Statements

* **Creemos que** al implementar un "Wizard de Pedidos Inteligente" que automatice el cálculo financiero frente a líneas de crédito, los gerentes de logística realizarán sus requerimientos de manera más segura y rápida. **Sabremos que hemos tenido éxito cuando** el tiempo promedio para colocar y aprobar una orden de combustible se reduzca en un 60% frente a los métodos tradicionales (correos/WhatsApp).
* **Creemos que** al proveer un "Monitor IoT" con telemetría en vivo y alertas de caída brusca de presión a los controladores de flota, los proveedores podrán detectar y reaccionar ante posibles robos o fugas al instante. **Sabremos que hemos tenido éxito cuando** los reportes de mermas inexplicables o pérdidas de combustible en ruta disminuyan en un 90%.
* **Creemos que** al incluir un "Dashboard de Inteligencia Operativa" que cruce el volumen despachado con el presupuesto mensual (Burn Rate) por centro de costo, los clientes corporativos tendrán un mejor control financiero. **Sabremos que hemos tenido éxito cuando** los incidentes de sobregiros presupuestales por abastecimiento de energía se reduzcan a cero.
* **Creemos que** al digitalizar el proceso de entrega y generar un "Voucher Legal PDF" como evidencia transaccional e inmutable, los proveedores de combustible cerrarán sus ciclos logísticos de forma más limpia. **Sabremos que hemos tenido éxito cuando** el tiempo de validación para proceder con la facturación al cliente pase de días a minutos.

#### 1.2.2.4. Lean UX Canvas

*(A continuación se presenta el Lean UX Canvas que resume la estrategia y validación del modelo de negocio de FuelTrack).*

![Lean UX Canvas FuelTrack](../docs/lean-ux-canvas.png)

---

## 1.3. Segmentos objetivo

**1. El Cliente Corporativo (Demanda)**

* **Descripción General:** Empresas con operaciones críticas, pesadas o en zonas remotas que dependen del suministro continuo de hidrocarburos para mantener su productividad (minería, telecomunicaciones, infraestructura y construcción).
* **Características Demográficas y Profesionales:**
  * **Rol / Puesto:** Gerentes de Logística, Jefes de Operaciones, Supervisores de Campamento o Nodos.
  * **Edad:** Profesionales entre 35 y 55 años, con alta responsabilidad sobre la continuidad operativa.
  * **Género:** Mayoritariamente masculino en campo, aunque cada vez más equitativo en áreas gerenciales logísticas.
  * **Ubicación:** Oficinas corporativas en zonas urbanas (Lima) con constante comunicación hacia campamentos o nodos rurales/remotos (ej. Amazonas, zonas mineras).
* **Información Estadística de Sustento:**
  * **Impacto Operativo:** Según estudios de logística industrial, las paradas no planificadas por falta de energía pueden costar a empresas extractivas o de infraestructura decenas de miles de dólares por hora.
  * **Control de Presupuesto:** Más del 60% de los gerentes logísticos afirman tener dificultades para auditar el consumo exacto de combustible frente a lo presupuestado debido a la fragmentación de la información en papel.

**2. El Proveedor / Distribuidor (Oferta)**

* **Descripción General:** Empresas mayoristas dedicadas a la comercialización y transporte de hidrocarburos que poseen flotas de cisternas especializadas y buscan asegurar la integridad de su carga hasta el destino final.
* **Características Demográficas y Profesionales:**
  * **Rol / Puesto:** Controladores de Flota (Centro de Monitoreo), Despachadores, Gerentes Comerciales.
  * **Edad:** Entre 28 y 50 años.
  * **Nivel Técnico:** Alto uso de monitores de rastreo GPS, manejo de turnos y coordinación constante con choferes de ruta pesada.
  * **Ubicación:** Bases de operaciones logísticas, plantas de refinería o distribución en zonas industriales.
* **Información Estadística de Sustento:**
  * **Mermas y Robos:** El robo de combustible en tránsito (conocido coloquialmente como "ordeño") representa pérdidas anuales de millones de dólares para las empresas de transporte en Latinoamérica.
  * **Transformación Digital en Flotas:** Se estima que la integración de telemetría y sistemas de gestión de flotas (FMS) mejora la eficiencia de despachos y reduce tiempos de inactividad operativa hasta en un 25%, justificando la necesidad de un monitor IoT dedicado como el de FuelTrack.


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




## Conclusiones

<br>
Alaminkarno. (2024, enero 8). DDD (Domain-Driven Design) in Flutter – Too much or just right? DEV Community. https://dev.to/alaminkarno/ddd-domain-driven-design-in-flutter-too-much-or-just-right-d1g

Allen, C. (2024). The impact of book clubs on millennials: Best way to instill a love of reading. Recuperado de <https://catherineallenblog.com/the-impact-of-book-clubs-on-millennials-best-way-to-instill-a-love-of-reading>

Alvarez, A. (2020, 5 de agosto). 5W2H: Qué significa, para qué sirve, cómo aplicarla y algunos ejemplos. LeanConstructionMexico. <https://www.leanconstructionmexico.com.mx/post/5w2h-qué-significa-para-qué-sirve-cómo-aplicarla-y-algunos-ejemplos>

Dart Packages. (s. f.). pub.dev. <https://pub.dev>

Fabiana, E., & Vega, J. (2022). La motivación en el aprendizaje de la lectura en los estudiantes. Revista EDUCARE - UPEL-IPB - Segunda Nueva Etapa 2.0, 26(Extraordinario), 476–493. <https://doi.org/10.46498/reduipb.v26iExtraordinario.1641>

Flutter Dev. (s. f.). Flutter documentation. <https://docs.flutter.dev>

Google Fonts. (s. f.). Alexandria. <https://fonts.google.com/specimen/Alexandria>

Google Fonts. (s. f.). Asap Condensed. <https://fonts.google.com/specimen/Asap+Condensed>

Mamani, B., Chata, L., & Choque, D. (2024). Efecto del uso de Tik Tok en el rendimiento académico de estudiantes de 5to grado . Revista Tribunal, 4(9), 161-175. <https://doi.org/10.59659/revistatribunal.v4i9.71>

Ministerio de Cultura del Perú & Instituto Nacional de Estadística e Informática. (2023). Encuesta Nacional de Lectura 2022: Informe de lectores y no lectores. Recuperado de <https://perulee.pe/sites/default/files/ENL%202022%20-%20Informe%20de%20lectores%20y%20no%20lectores.pdf>

Statista. (2024). Hablemos de los clubes de lectura y por qué esta tendencia va en aumento. Recuperado de <https://globaltag.mx/uncategorized/leer-esta-de-moda-hablemos-de-los-clubes-de-lectura-y-por-que-esta-tendencia-va-en-aumento/>

Torres-Vega, E. (2025). Comprensión lectora en estudiantes de secundaria en Perú. Horizontes. Revista De Investigación En Ciencias De La Educación, 9(36), 177–187. <https://doi.org/10.33996/revistahorizontes.v9i36.909>


