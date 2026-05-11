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


﻿# Capítulo I: Introducción

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

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1: Falta de Visibilidad y Control en el Consumo de Combustible**
Los gerentes de logística y operaciones en sectores críticos enfrentan dificultades para monitorear en tiempo real el consumo de combustible en sus tanques, dependiendo de reportes manuales o lecturas físicas poco frecuentes. La falta de una solución integrada impide conocer el "Burn Rate" exacto, lo que resulta en desabastecimientos inesperados y sobregiros presupuestales. ¿Cómo podemos crear una plataforma integral que permita a los dueños de operaciones monitorear en tiempo real el nivel y presión de sus tanques, mejorando la eficiencia en el control del gasto y la continuidad operativa?

**Problem Statement 2: Monitoreo Insuficiente de la Integridad de la Carga en Ruta**
Los proveedores de combustible tienen acceso limitado a herramientas que permitan monitorear aspectos críticos de la carga durante el transporte, como caídas bruscas de presión (robo por "ordeño") o desvíos de ruta. Esto limita su capacidad para detectar incidentes de seguridad de manera temprana. La falta de integración entre telemetría IoT y la gestión de pedidos contribuye a la falta de eficacia en el seguimiento de la carga. ¿Cómo podemos desarrollar una solución IoT integrada que permita monitorear en tiempo real la ubicación y el volumen de las cisternas, proporcionando datos precisos para mejorar la detección temprana de robos y facilitar una gestión logística más segura?

**Problem Statement 3: Coordinación Ineficiente de Pedidos de Reabastecimiento**
Los clientes corporativos a menudo encuentran difícil coordinar pedidos de combustible debido a la falta de una plataforma centralizada, dependiendo de llamadas o mensajes informales. Esto genera una mala gestión del tiempo y la imposibilidad de asegurar el suministro en momentos de alta demanda operativa. ¿Cómo podemos diseñar una funcionalidad dentro de la aplicación que facilite la coordinación de pedidos de combustible, permitiendo a los usuarios agendar, validar saldos y recibir confirmaciones de despacho de manera rápida, mejorando la disponibilidad del insumo?

**Problem Statement 4: Carencia de Evidencia Digital para Auditoría de Despachos**
Muchos usuarios tienen dificultades para validar que el volumen de combustible facturado coincida exactamente con lo ingresado al tanque debido a la falta de información centralizada e inmutable. La dependencia de guías de remisión físicas propensas a pérdida genera retrasos en la facturación y disputas financieras. ¿Cómo podemos implementar una funcionalidad que genere vouchers digitales automáticos basados en la telemetría del sensor, proporcionando información detallada sobre el volumen recibido para facilitar la auditoría y el cierre contable oportuno?

**Problem Statement 5: Alertas de Niveles Críticos Insuficientes**
Los encargados de planta a menudo olvidan programar reabastecimientos preventivos debido a la falta de alertas automatizadas basadas en el consumo real. La ausencia de una herramienta que gestione notificaciones de "nivel bajo" puede llevar a la paralización de maquinaria crítica, afectando la productividad. ¿Cómo podemos desarrollar un sistema de alertas dentro de la aplicación que notifique sobre niveles críticos y proyecciones de agotamiento, garantizando que no se pasen por alto las órdenes de compra necesarias para la salud operativa de la empresa?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**
* **Necesidad de Solución Integral:** Creemos que las empresas industriales necesitan una solución que combine la gestión de pedidos, el control de presupuestos y el monitoreo IoT en tiempo real.
* **Plataforma Web y Móvil Accesible:** Creemos que esta necesidad se resuelve con un dashboard web de control centralizado y una app móvil para supervisión en campo, garantizando una experiencia accesible para distintos perfiles operativos.
* **Clientes Iniciales:** Nuestros clientes iniciales serán empresas de minería, construcción y telecomunicaciones, así como proveedores mayoristas de hidrocarburos.
* **Valor Principal:** El valor #1 que los clientes buscan es la visibilidad total del inventario físico y la eliminación de mermas por robo en ruta.
* **Modelo de Ingresos:** Generaremos ingresos a través de suscripciones mensuales por cada nodo IoT instalado y planes premium de analítica predictiva de consumo.
* **Competencia y Diferenciación:** Nos diferenciamos al ofrecer una solución que vincula directamente el estado físico del combustible (IoT) con la transacción financiera y de auditoría (Software B2B).
* **Riesgos de Producto:** Un riesgo posible es la resistencia al cambio por parte del personal operativo. Superaremos esto mediante interfaces intuitivas y capacitación sobre el ahorro directo que genera el sistema.

**User Assumptions**
* **Quién es el Usuario:** Gerentes de logística que buscan control financiero y jefes de flota que requieren seguridad en el transporte.
* **Dónde Encaja el Producto:** El producto se integra en la rutina diaria de control de activos y en el proceso mensual de conciliación de cuentas por pagar.
* **Problemas del Producto:** Los usuarios pueden preocuparse por la conectividad en zonas remotas. Solucionaremos esto mediante protocolos de almacenamiento local en el hardware (Edge Computing) y sincronización automática.

**User Outcomes**
* **Para Clientes:** Auditar con precisión cada galón recibido y proyectar el gasto mensual para evitar sobregiros.
* **Para Proveedores:** Reducir pérdidas por robo en tránsito y automatizar la generación de evidencias para facturar sin retrasos.

**Business Outcomes**
* **Reducción de Mermas:** Disminuir en un 90% el robo de combustible en las rutas monitoreadas.
* **Posicionamiento:** Convertirse en el estándar tecnológico para la trazabilidad de hidrocarburos en operaciones críticas del país.

**Features Importantes:**
* Dashboard de monitoreo telemétrico en tiempo real (Nivel, Presión, GPS).
* Wizard de pedidos automatizado según niveles críticos.
* Generación de Vouchers Digitales PDF con firma electrónica.
* Alertas preventivas de reabastecimiento y detección de anomalías.
* Reportes de "Burn Rate" y proyecciones de consumo mensual.

#### 1.2.2.3. Lean UX Hypothesis Statements

* **Creemos que** al proporcionar una plataforma integral que permita gestionar pedidos y monitorear en tiempo real el nivel de los tanques, los **Gerentes de Logística** encontrarán más eficiente el control del suministro. **Sabremos que hemos tenido éxito cuando** observemos una reducción del 100% en paradas de planta por falta de combustible y una mayor satisfacción en la auditoría de activos.

* **Creemos que** al ofrecer una solución IoT que detecte caídas bruscas de presión y desvíos de ruta, los **Proveedores** podrán prevenir robos de manera temprana. **Sabremos que hemos tenido éxito cuando** veamos una disminución del 90% en reportes de mermas inexplicables y un aumento en la seguridad de la carga.

* **Creemos que** al permitir a los usuarios generar Vouchers Digitales basados en lecturas reales del sensor, los **Equipos Contables** podrán conciliar facturas más rápido. **Sabremos que hemos tenido éxito cuando** veamos una reducción del 70% en el tiempo dedicado a la validación manual de guías de remisión físicas.

* **Creemos que** al ofrecer un sistema de alertas automatizadas para niveles críticos, los **Encargados de Planta** cumplirán con los ciclos de reabastecimiento de manera constante. **Sabremos que hemos tenido éxito cuando** observemos una mayor puntualidad en las órdenes de compra y la eliminación de pedidos de emergencia costosos.

* **Creemos que** al integrar todas las funcionalidades de gestión y telemetría en una sola plataforma, los usuarios tendrán una experiencia operativa simplificada. **Sabremos que hemos tenido éxito cuando** veamos un aumento en la retención de clientes corporativos y una disminución en el uso de herramientas fragmentadas como Excel o WhatsApp.

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

﻿# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En el mercado actual, existen diversas soluciones orientadas a la gestión de combustible y logística, las cuales varían desde plataformas puramente de software hasta ecosistemas robustos de Internet de las Cosas (IoT). Para el contexto de **FuelTrack**, que ahora integra capacidades IoT (como sensores de nivel ultrasónicos o capacitivos en tanques para monitoreo en tiempo real y automatización de pedidos), hemos identificado a los siguientes competidores principales:

**Zavgar:** Es un software como servicio (SaaS) diseñado para la gestión de mantenimiento y consumo de combustible de flotas. Se integra con dispositivos de telemetría OBD-II (IoT) instalados en los vehículos para extraer datos precisos sobre el rendimiento y gasto de combustible. Aunque es muy fuerte en el monitoreo del consumo final, carece de un enfoque integral para la automatización de la cadena de suministro y pedidos directos a proveedores basándose en el nivel físico de los tanques.

**FuelCloud:** Es una solución tecnológica altamente orientada al IoT que combina hardware propietario y software basado en la nube para el control físico del despacho de combustible. Utilizan sensores y controladores conectados directamente en los tanques y surtidores para autorizar, medir y registrar en tiempo real cada gota de combustible extraída. Es un competidor directo en el ámbito de infraestructura, aunque su enfoque principal es el control interno (evitar robos o mermas) más que la optimización logística de pedidos B2B.

**Wialon:** Es una de las plataformas globales líderes en gestión de flotas y telemetría IoT. Permite la integración universal con miles de dispositivos GPS y sensores de nivel de combustible. Ofrece visualización en tiempo real, alertas automatizadas y reportes de consumo muy avanzados. Es un competidor indirecto muy fuerte; si bien no es un marketplace ni un gestor administrativo de pedidos, la infraestructura IoT que manejan resuelve una parte crítica de la logística de distribución que FuelTrack también busca optimizar.

### 2.1.1. Análisis competitivo

A continuación, se presenta el Competitive Analysis Landscape, el cual nos permite reconocer las fortalezas, debilidades, estrategias y el uso de tecnologías (especialmente IoT) de nuestros principales competidores, para así posicionar a FuelTrack estratégicamente en el mercado.

<table>
    <thead>
        <tr>
            <th colspan="6">Competitive Analysis Landscape</th>
        </tr>
        <tr>
            <th colspan="2">¿Por qué llevar a cabo este análisis?</th>
            <td colspan="4" style="text-align: justify">Este análisis se lleva a cabo para identificar las ventajas y desventajas de la integración IoT de FuelTrack frente a las soluciones existentes, comprendiendo cómo los competidores utilizan el hardware y software para el control de combustible, y así definir nuestra ventaja competitiva en la automatización de pedidos B2B.</td>
        </tr>
    </thead>
    <tbody style="text-align: left">
        <tr style="text-align: center">
            <th colspan="2">Competidores</th>
            <th>
                <div style="text-align: center">
                    <strong>FuelTrack</strong><br>
                    <img src="../assets/logo-fueltrack.jpg" height="120" alt="Logo FuelTrack"/>
                </div>
            </th>
            <th>
                <div style="text-align: center">
                    <strong>Zavgar</strong><br>
                    <img src="../assets/logo-zavgar.jpg" height="120" alt="Logo Zavgar"/>
                </div>
            </th>
            <th>
                <div style="text-align: center">
                    <strong>FuelCloud</strong><br>
                    <img src="../assets/logo-fuelcloud.jpg" height="120" alt="Logo FuelCloud"/>
                </div>
            </th>
            <th>
                <div style="text-align: center">
                    <strong>Wialon</strong><br>
                    <img src="../assets/logo-wialon.jpg" height="120" alt="Logo Wialon"/>
                </div>
            </th>
        </tr>
        <tr>
            <th rowspan="2"><strong>Perfil</strong></th>
            <td>Overview</td>
            <td>Plataforma integral basada en web y telemetría IoT (sensores DUT-E CAN) en cisternas en ruta y control de presupuesto (Burn Rate) que digitaliza y automatiza el proceso completo de pedido de combustible entre empresas y proveedores, basándose en lecturas de stock en tiempo real.</td>
            <td>SaaS para la gestión de flotas que se integra con dispositivos telemáticos (OBD-II) para monitorear el consumo de combustible, enfocado en eficiencia y reducción de costos operativos.</td>
            <td>Solución integral de hardware IoT y software para el control físico del despacho de combustible en tanques propios, autorizando y midiendo el flujo en tiempo real.</td>
            <td>Plataforma global de telemetría IoT y gestión de flotas que se integra con sensores de nivel de combustible y GPS para ofrecer reportes operativos avanzados y prevención de robos.</td>
        </tr>
        <tr>
            <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
            <td>Especialización en el flujo logístico B2B. Al integrar sensores IoT, elimina el error humano creando notificaciones y pedidos automáticos cuando el tanque llega a un nivel crítico, garantizando un abastecimiento ininterrumpido. Además, FuelTrack previene sobregiros financieros y robos en tránsito bloqueando vehículos remotamente, cerrando el ciclo con Vouchers PDF firmados digitalmente</td>
            <td>Implementación sin necesidad de hardware propietario pesado; centraliza la información de mantenimiento y gasto de combustible de la flota en un solo dashboard analítico.</td>
            <td>Control físico extremadamente riguroso mediante hardware instalado en el surtidor. Evita mermas y robos autorizando extracciones mediante PIN o tarjetas RFID.</td>
            <td>Compatibilidad universal con más de 2,400 dispositivos IoT del mercado. Trazabilidad de rutas en tiempo real y análisis profundo de variaciones de nivel de combustible.</td>
        </tr>
        <tr>
            <th rowspan="2"><strong>Perfil de Marketing</strong></th>
            <td>Mercado objetivo</td>
            <td>Empresas (mineras, constructoras, agrícolas) con monitoreo de flotas de cisternas que requieren abastecimiento constante, y proveedores de combustible que buscan automatizar sus ventas.</td>
            <td>Empresas con flotas vehiculares (transporte, logística) que desean monitorear y reducir el consumo interno de combustible.</td>
            <td>Empresas con tanques de combustible de autoconsumo e infraestructura física que necesitan control estricto de su inventario.</td>
            <td>Empresas logísticas, proveedores de combustible, integradores de sistemas GPS y corporaciones de transporte pesado.</td>
        </tr>
        <tr>
            <td>Estrategias de Marketing</td>
            <td>
                <ul>
                    <li>Demostraciones piloto de la automatización IoT en tanques de clientes clave.</li>
                    <li>Alianzas estratégicas B2B con empresas proveedoras.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Marketing digital B2B y contenido SEO sobre reducción de costos logísticos.</li>
                    <li>Integraciones con tarjetas de red de estaciones de servicio.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Venta consultiva presencial y asistencia a ferias industriales.</li>
                    <li>Red de distribuidores e instaladores de hardware petrolero.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Alianzas masivas con fabricantes de hardware IoT a nivel global.</li>
                    <li>Conferencias técnicas propias orientadas a la telemetría.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <th rowspan="3"><strong>Perfil del producto</strong></th>
            <td>Producto & servicios</td>
            <td>
                <ul>
                    <li><strong>Producto:</strong> Nodos IoT (sensores de nivel) instalados en tanques de clientes.</li>
                    <li><strong>Servicios:</strong> Plataforma web de trazabilidad, alertas automáticas de reabastecimiento y panel logístico para proveedores.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li><strong>Producto:</strong> Integración API con telemetría de vehículos.</li>
                    <li><strong>Servicios:</strong> Web app para reportes de consumo, gestión de mantenimiento y control de gastos.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li><strong>Producto:</strong> Controladores hardware IoT para válvulas y surtidores.</li>
                    <li><strong>Servicios:</strong> Software cloud para autorización de usuarios y control de inventario físico.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li><strong>Producto:</strong> Plataforma de software agnóstica a hardware.</li>
                    <li><strong>Servicios:</strong> Monitoreo GPS, alertas de robo, geocercas y análisis de sensores de nivel.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Precios y costos</td>
            <td>
                <ul>
                    <li>Costo único de adquisición/instalación del hardware IoT por tanque.</li>
                    <li>Suscripción mensual (SaaS) por acceso a la plataforma corporativa.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Modelo SaaS basado en el número de vehículos activos monitoreados en la plataforma.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Alta inversión inicial por el hardware IoT y su instalación especializada.</li>
                    <li>Licencia mensual/anual por el uso del software de gestión.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Modelo B2B modular basado en un pago por "activo conectado" al mes.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Canales de distribución</td>
            <td>
                <ul>
                    <li><strong>Web:</strong> Plataforma principal para la gestión corporativa y reportes.</li>
                    <li><strong>Físico:</strong> Instalación de sensores in-situ a través de técnicos.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li><strong>Web:</strong> Venta y onboarding 100% digital.</li>
                    <li><strong>Móvil:</strong> App de gestión y registro.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li><strong>Físico:</strong> Distribuidores de equipamiento industrial.</li>
                    <li><strong>Web/Móvil:</strong> Apps para visualizar la telemetría del tanque.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li><strong>Web:</strong> Red global de partners e integradores locales.</li>
                    <li><strong>Móvil:</strong> App para monitoreo en campo.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <th rowspan="4"><strong>Análisis SWOT</strong></th>
            <td>Fortalezas</td>
            <td>
                <ul>
                    <li>Integra hardware IoT directamente en el proceso administrativo B2B.</li>
                    <li>Automatiza el flujo completo, eliminando quiebres de stock.</li>
                    <li>Diseño UX moderno frente a interfaces industriales antiguas.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Implementación ágil al ser puramente software.</li>
                    <li>Gran capacidad analítica y reportes financieros automáticos.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Control físico irrefutable del surtidor de combustible.</li>
                    <li>Hardware muy robusto adaptado a entornos hostiles.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Líder global con plataforma altamente estable.</li>
                    <li>Agnóstico: compatible con casi cualquier hardware IoT existente.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Debilidades</td>
            <td>
                <ul>
                    <li>Dependencia de la instalación de infraestructura física (sensores).</li>
                    <li>El reto de introducir tecnología IoT en empresas muy tradicionales.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>No gestiona el pedido ni la comunicación con el proveedor mayorista.</li>
                    <li>Depende de la veracidad de datos de terceros.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Altos costos de barrera de entrada por el hardware.</li>
                    <li>Sobredimensionado para clientes que solo buscan gestionar la facturación logística.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Curva de aprendizaje muy pronunciada; requiere especialistas para configurarlo.</li>
                    <li>No resuelve la gestión de compra-venta comercial.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Oportunidades</td>
            <td>
                <ul>
                    <li>El Internet Industrial de las Cosas (IIoT) está ganando terreno rápidamente en el país.</li>
                    <li>Posibilidad de usar datos de sensores para predecir demanda (Big Data).</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Mayor presión corporativa por reducir la huella de carbono y gastos de flota.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Nuevas normativas de OSINERGMIN que exijan trazabilidad volumétrica obligatoria.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Expansión de redes celulares NB-IoT y 5G que facilitan el despliegue de sensores remotos.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Amenazas</td>
            <td>
                <ul>
                    <li>Sistemas ERP tradicionales que desarrollen sus propios módulos IoT nativos.</li>
                    <li>Problemas de conectividad rural que impidan la transmisión de datos de los sensores.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Fabricantes de vehículos que incluyan estos SaaS de fábrica.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Entrada de hardware IoT asiático de bajo costo y fácil instalación.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Startups de nicho que ofrezcan soluciones más sencillas y directas sin funciones innecesarias.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

Para definir nuestras estrategias frente a competidores como Zavgar, FuelCloud y Wialon, hemos desarrollado una **Matriz CAME** (Corregir, Afrontar, Mantener, Explotar) basada en nuestro análisis FODA competitivo. Esto nos permite trazar tácticas claras para aprovechar el entorno IoT y mitigar los riesgos del mercado y la competencia.

<table>
    <thead>
        <tr>
            <th colspan="3" style="text-align: center; font-size: 1.1em;">Matriz CAME para el desarrollo de estrategias en base al análisis FODA</th>
        </tr>
        <tr>
            <th style="width: 20%;">Análisis FODA cruzado</th>
            <th style="width: 40%;">Oportunidades (O)
                <ul style="font-weight: normal; text-align: left; font-size: 0.9em;">
                    <li>O1. Crecimiento del IIoT (Internet Industrial de las Cosas).</li>
                    <li>O2. Predicción de demanda mediante Big Data.</li>
                    <li>O3. Nuevas exigencias de trazabilidad de OSINERGMIN.</li>
                </ul>
            </th>
            <th style="width: 40%;">Amenazas (A)
                <ul style="font-weight: normal; text-align: left; font-size: 0.9em;">
                    <li>A1. Sistemas ERP desarrollando módulos IoT nativos.</li>
                    <li>A2. Baja conectividad de red en zonas rurales/mineras.</li>
                    <li>A3. Entrada de hardware IoT asiático de bajo costo.</li>
                </ul>
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Fortalezas (F)
                <ul style="font-weight: normal; text-align: left; font-size: 0.9em;">
                    <li>F1. Integración B2B (Pedido logístico + IoT).</li>
                    <li>F2. Automatización total de stock y reabastecimiento.</li>
                    <li>F3. Diseño UX moderno y accesible.</li>
                </ul>
            </th>
            <td>
                <strong>Estrategia (FO) Ofensivas: Explotar</strong>
                <ul style="text-align: left; font-size: 0.95em;">
                    <li><strong>Especialización B2B impulsada por datos (F1, O2):</strong> Utilizar los datos recopilados por nuestros sensores IoT para ofrecer a los proveedores reportes predictivos de demanda. Esto nos diferencia de Wialon o Zavgar, que solo muestran el consumo pasado, permitiendo a nuestros clientes anticipar sus ventas.</li>
                    <li><strong>Cumplimiento normativo automatizado (F2, O3):</strong> Posicionar FuelTrack como la herramienta definitiva para cumplir con las regulaciones de trazabilidad de OSINERGMIN, utilizando nuestra plataforma web moderna (F3) para generar reportes automáticos basados en las lecturas reales de los tanques.</li>
                </ul>
            </td>
            <td>
                <strong>Estrategia (FA) Defensivas: Mantener</strong>
                <ul style="text-align: left; font-size: 0.95em;">
                    <li><strong>Robustez frente a la desconexión (F2, A2):</strong> Desarrollar tácticas de almacenamiento local (Edge Computing) en nuestros nodos IoT. Si se pierde la conectividad en una mina o zona rural, el sensor guarda el registro y actualiza el stock/pedido automáticamente al recuperar la señal, superando la fiabilidad de la competencia de bajo costo.</li>
                    <li><strong>Diferenciación por valor y soporte (F1, F3, A3):</strong> Frente a la amenaza del hardware barato asiático, enfocar la estrategia de marketing en el valor del ecosistema completo (SaaS amigable + hardware) y el soporte técnico B2B local, algo que los importadores de dispositivos genéricos no pueden ofrecer.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <th>Debilidades (D)
                <ul style="font-weight: normal; text-align: left; font-size: 0.9em;">
                    <li>D1. Dependencia de instalación física en tanques.</li>
                    <li>D2. Resistencia tecnológica en empresas tradicionales.</li>
                </ul>
            </th>
            <td>
                <strong>Estrategia (DO) de Reorientación: Corregir</strong>
                <ul style="text-align: left; font-size: 0.95em;">
                    <li><strong>Instalación como servicio de adecuación (D1, O3):</strong> Para mitigar la fricción que causa la instalación de hardware físico (a diferencia de soluciones puramente software), empaquetaremos la instalación del sensor como un servicio de "Auditoría y Adecuación a normativas IIoT", agregando valor inmediato a la infraestructura del cliente.</li>
                    <li><strong>Pilotos de adopción tecnológica (D2, O1):</strong> Reducir la resistencia al cambio en el sector logístico ofreciendo programas piloto de 30 días. Demostraremos cómo el IoT elimina las fallas humanas en la medición manual, ganando su confianza antes de cobrar la suscripción completa.</li>
                </ul>
            </td>
            <td>
                <strong>Estrategia (DA) de Supervivencia: Afrontar</strong>
                <ul style="text-align: left; font-size: 0.95em;">
                    <li><strong>Alianzas de conectividad (D1, A2):</strong> Para asegurar el funcionamiento de nuestro hardware en zonas remotas, formaremos alianzas con proveedores de telecomunicaciones (tecnologías NB-IoT o LoRaWAN), garantizando a los clientes que su inversión no se perderá por falta de señal.</li>
                    <li><strong>Estrategia de API Abierta (D2, A1):</strong> Para evitar que las empresas tradicionales prefieran los módulos IoT nativos deficientes de sus propios ERP, FuelTrack ofrecerá integraciones sencillas (API REST). De este modo, en lugar de competir contra los ERP, nos convertiremos en una extensión especializada que alimenta de datos precisos a sus sistemas contables.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

Para comprender a profundidad las necesidades operativas y logísticas de nuestros segmentos objetivo, y validar la viabilidad de una solución basada en telemetría IoT y software transaccional, se han diseñado dos guías de entrevistas semiestructuradas. El objetivo principal es identificar los "puntos de dolor" en la cadena de suministro de hidrocarburos que el hardware y el software de FuelTrack buscan resolver.

---

#### A. Segmento: Empresas Solicitantes (Clientes Corporativos / Operaciones en Campo)

**Objetivo:** Identificar cómo la falta de visibilidad física del combustible afecta el presupuesto, la continuidad operativa y los procesos de auditoría financiera.

**Preguntas de exploración operativa:**
1. ¿Cómo gestionan actualmente la solicitud y recepción de combustible para sus operaciones en campo?
2. ¿Han sufrido paralizaciones o retrasos operativos por desabastecimiento de combustible? ¿Cómo impactó esto económicamente a la empresa?
3. ¿De qué manera monitorean hoy que el consumo de combustible no sobrepase el presupuesto mensual o la línea de crédito aprobada?
4. Al recibir una cisterna en campo, ¿qué método utilizan para validar que los galones facturados coincidan exactamente con lo ingresado a sus tanques?
5. ¿Qué nivel de visibilidad tienen sobre el trayecto del pedido desde que es aprobado hasta que llega al punto de entrega?
6. ¿Cómo manejan la documentación física (guías de remisión, vouchers) para sustentar el gasto ante el área de contabilidad?
7. ¿Qué tan complejo o lento es el proceso de conciliación mensual con su proveedor actual?
8. Si tuvieran un dashboard que mostrara en vivo la ubicación del combustible y su ritmo de gasto real (Burn Rate), ¿en qué medida mejoraría su toma de decisiones?

**Preguntas de perfil (Contexto):**
* ¿Cuál es su cargo y qué responsabilidad tiene sobre el suministro energético?
* ¿Qué edad tiene y cuál es su nivel de experiencia en el sector?
* ¿Qué herramientas digitales (ERPs, Excel, Apps móviles) utiliza con mayor frecuencia en su jornada laboral?

---

#### B. Segmento: Proveedores de Combustible (Distribuidores / Mayoristas)

**Objetivo:** Detectar pérdidas por mermas o robos en ruta, ineficiencias en la facturación por uso de papel y carencias en el monitoreo telemétrico de la flota.

**Preguntas de exploración logística:**
1. ¿Cómo monitorean actualmente el estado y la ubicación de sus cisternas una vez que salen de la planta de distribución?
2. ¿Han enfrentado incidentes de mermas inexplicables o robos de combustible ("ordeño") durante el tránsito? ¿Cómo logran detectar estos eventos?
3. ¿Cuentan actualmente con sensores que midan la presión o el nivel de los tanques de las cisternas en tiempo real?
4. ¿Cuánto tiempo transcurre en promedio desde que se realiza la entrega física hasta que el área administrativa recibe la confirmación firmada para facturar?
5. ¿De qué manera impacta el uso de documentos físicos (papel) en su flujo de caja y tiempos de cobranza?
6. Cuando un cliente solicita información sobre el estado de su pedido, ¿cuál es el proceso interno para darle una respuesta?
7. ¿Cómo reacciona su centro de control ante anomalías en ruta (paradas no programadas o desvios de trayectoria)?
8. ¿Estarían dispuestos a adoptar una solución que integre sensores IoT con una plataforma que automatice las guías digitales y elimine las mermas?

**Preguntas de perfil (Contexto):**
* ¿Cuál es su rol dentro de la estructura logística de la empresa?
* ¿Qué edad tiene y qué nivel de estudios posee?
* ¿Qué sistemas de rastreo GPS o gestión de flotas (FMS) utilizan actualmente?
* ¿Cómo describiría la apertura de su organización hacia la digitalización y el uso de hardware IoT?

### 2.2.2. Registro de entrevistas

**Segmento 1: El Cliente Corporativo (Demanda)**

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>1</td>
    <th>Nombre</th>
    <td>Maria Elena Muñoz</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>23</td>
    <th>Distrito</th>
    <td>Los Olivos</td>
  </tr>
  <tr>
    <th>Captura de la entrevista:</th>
    <td colspan="3">
      <img src="https://github.com/user-attachments/assets/524a2e4e-8539-49aa-8b13-b117c6db4d4f" alt="Captura de la entrevista" width="200">
    </td>
  </tr>
  <tr>
    <th>Resumen</th>
    <td colspan="3">
      La empresa gestiona el combustible de forma manual y sin control en tiempo real, lo que genera errores, desabastecimientos y pérdidas económicas. Además, existe poca visibilidad del transporte y problemas con la documentación, lo que dificulta la conciliación con proveedores. Una solución como FuelTech permitiría mejorar el control, optimizar la gestión y aumentar la eficiencia operativa.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310425_upc_edu_pe/IQCfkcUktPEWRauuu2W1srTQAboKi2wAirJeCJC7AZahiyY?e=MSTjfd">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">
      00:00 - 05:48
    </td>
  </tr>
</table>
<br>


<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>2</td>
    <th>Nombre</th>
    <td>Nicolas Pineda</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>22</td>
    <th>Distrito</th>
    <td>San Juan de Lurigancho</td>
  </tr>
  <tr>
    <th>Captura de la entrevista:</th>
<td colspan="3">
        <img width="350" height="200" alt="Entrevista 2" src="../assets/interview2_screenshot.png" /> 
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c275_upc_edu_pe/IQBqzoHpq9JwQr67PhjmhAadAer3MCKj-SyvnfFnDt4Dvi4?e=ly8uH3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>

<tr>
    <th>Resumen</th>
    <td colspan="3">
La empresa de transporte gestiona su suministro de combustible mediante procesos semi-manuales en Excel, lo que ocasiona paradas operativas de la flota y sobrecostos por compras de emergencia. Además, enfrentan una visibilidad muy limitada sobre el trayecto de los camiones y manejan la documentación en formato físico, lo que hace que la conciliación mensual con el proveedor sea lenta, demandante y propensa a descuadres. La implementación de un dashboard en tiempo real permitiría monitorear el consumo exacto, optimizar los pedidos, reducir los gastos logísticos y garantizar una total transparencia para las auditorías.    </td>
  </tr>

  <tr>
   <th>Timing</th>
    <td colspan="3">
         00:00 - 10:23
    </td>
  </tr>
</table>
<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>1</td>
    <th>Nombre</th>
    <td>Alexandra</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>42</td>
    <th>Distrito</th>
    <td>Lima</td>
  </tr>
  <tr>
    <th>Captura de la entrevista</th>
    <td colspan="3">
      <img src="../assets/cap2/ENTREVISTA-ALE.png" alt="Captura de la entrevista" width="400">
    </td>
  </tr>
  <tr>
    <th>Resumen</th>
    <td colspan="3">
      <strong>Resumen:</strong> Alexandra (Jefa de Operaciones, 42 años) indica que el proceso actual de solicitud de combustible es manual (vía WhatsApp y Excel), lo que ha provocado desabastecimiento y penalidades por caídas de SLAs. Señala una falta de control en tiempo real sobre la línea de crédito y el presupuesto (análisis "post-mortem"). Además, destaca la "caja negra" logística (visibilidad nula del trayecto de las cisternas) y la dificultad para validar galones ingresados frente a los facturados, confiando solo en guías físicas propensas a perderse. Afirma que un dashboard con ubicación en vivo y <em>Burn Rate</em> mejoraría radicalmente la toma de decisiones preventivas y agilizaría las conciliaciones con contabilidad, que actualmente toman de 3 a 4 días.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213278_upc_edu_pe/IQBBKGS1EeQyQJQiZVX4I9YbAUxrSRpnv4n9nhrrNoL_bHo?e=vCBVeM&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
   <th>Timing</th>
    <td colspan="3">
         00:00 - 04:30
    </td>
  </tr>
</table>
<br>

**Segmento 2: El Proveedor / Distribuidor (Oferta)**
<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>1</td>
    <th>Nombre</th>
    <td>Leonardo Gamboa</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>27</td>
    <th>Distrito</th>
    <td>Ate</td>
  </tr>
  <tr>
    <th>Captura de la entrevista:</th>
    <td colspan="3">
      <img src="../assets/cap2/Segmento2_Persona1.png" alt="Captura de la entrevista" width="200">
    </td>
  </tr>
  <tr>
    <th>Resumen</th>
    <td colspan="3">
      Leonardo Gamboa, conductor de cisterna con 8 años de experiencia, indicó que actualmente el monitoreo se limita al uso de GPS, sin información en tiempo real sobre el estado del combustible. Señaló que el control es manual y que las mermas o posibles robos se detectan recién al final del proceso, lo que genera desconfianza y penalizaciones injustas. Asimismo, destacó la dependencia de documentos físicos, lo que retrasa la facturación y genera riesgos de pérdida o deterioro. Considera que una solución digital con IoT sería útil siempre que sea sencilla de usar, reduzca errores y evite sanciones por situaciones fuera de su control.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://drive.google.com/file/d/11L819TbztDc0YqwB2WM7qR0-Egn5gLBC/view?usp=sharing">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">
      00:00 - 06:18
    </td>
  </tr>
</table>
<br>


<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>2</td>
    <th>Nombre</th>
    <td>Marllely Arias</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>23</td>
    <th>Distrito</th>
    <td>Lince</td>
  </tr>
  <tr>
    <th>Captura de la entrevista:</th>
    <td colspan="3">
      <img src="../assets/cap2/Segmento2_Persona2.png" alt="Captura de la entrevista" width="200">
    </td>
  </tr>
  <tr>
    <th>Resumen</th>
    <td colspan="3">
      Marllely Arias, de 23 años, describió que actualmente la empresa monitorea sus cisternas mediante GPS, lo que permite conocer su ubicación, pero sin información en tiempo real sobre el estado del combustible. Indicó que existen casos de mermas o posibles robos que se detectan de manera tardía, así como un control manual del combustible y una alta dependencia de documentos físicos, lo que retrasa la facturación y la atención a clientes. Considera que una solución basada en IoT y digitalización permitiría mejorar el control, reducir pérdidas y optimizar los procesos operativos.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://drive.google.com/file/d/1UBl6ci4B9Mjg_y2_GnBcxZ2FXDWzrbx9/view?usp=sharing">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">
      00:00 - 05:44
    </td>
  </tr>
</table>
<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>3</td>
    <th>Nombre</th>
    <td>Kevin Díaz</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>32</td>
    <th>Distrito</th>
    <td>Callao</td>
  </tr>
  <tr>
    <th>Captura de la entrevista:</th>
    <td colspan="3">
      <img src="../assets/cap2/Segmento2_Persona3.png" alt="Captura de la entrevista" width="200">
    </td>
  </tr>
  <tr>
    <th>Resumen</th>
    <td colspan="3">
      Kevin Díaz, coordinador logístico de 32 años, indicó que actualmente el monitoreo de cisternas se realiza únicamente mediante GPS, sin contar con información en tiempo real sobre el estado del combustible. Señaló que se han presentado mermas o posibles robos, los cuales se detectan de manera tardía al final del proceso. Asimismo, destacó que el control operativo y la facturación dependen en gran medida de documentos físicos, lo que genera retrasos y riesgos de pérdida de información. Considera que la implementación de una solución basada en IoT y digitalización permitiría mejorar el control, reducir pérdidas y optimizar la gestión logística.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://drive.google.com/drive/folders/1F7boyBz8lgLgsvLIgOnqx1KyeuxvCFUi">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">
      00:00 - 06:00
    </td>
  </tr>
</table>
<br>

### 2.2.3. Análisis de entrevistas

A partir de las entrevistas realizadas, se procedió a analizar las respuestas para identificar patrones de comportamiento, puntos de dolor y necesidades. Este análisis sustenta estadísticamente las características objetivas y subjetivas que servirán de base para la posterior construcción de nuestros arquetipos (User Personas).

#### Análisis del Segmento 1: Cliente Corporativo (Demanda)

Los entrevistados (Maria Elena, Nicolas y Alexandra) coinciden en que la gestión actual del suministro de combustible se sostiene en procesos manuales y herramientas ofimáticas (Excel) o canales informales (WhatsApp). Esto genera una "caja negra" logística donde el cliente no tiene visibilidad del trayecto de la cisterna, lo que a menudo resulta en desabastecimientos, paradas operativas y penalidades. Además, la fuerte dependencia de documentos físicos (guías de remisión) retrasa significativamente la conciliación contable. Para este grupo, es imperativo contar con un dashboard que centralice la información en tiempo real, ofrezca control del *Burn Rate* (presupuesto) y automatice el cruce de información para auditorías.

**Características Objetivas y Subjetivas:**

| Característica | Frecuencia (n/3) | Porcentaje | Entrevistas relacionadas |
| :--- | :--- | :--- | :--- |
| **(Objetiva)** Gestión manual de pedidos y control (Excel, WhatsApp) | 3/3 | **100%** | 1(Maria), 2(Nicolas), 3(Alexandra) |
| **(Objetiva)** Uso de documentación física para validar entregas y conciliar | 3/3 | **100%** | 1, 2, 3 |
| **(Objetiva)** Reporte de desabastecimientos, paradas o penalidades operativas | 3/3 | **100%** | 1, 2, 3 |
| **(Objetiva)** Necesidad de cruzar galones ingresados vs. facturados | 2/3 | **67%** | 2, 3 |
| **(Subjetiva)** Frustración por la "caja negra" logística (nula visibilidad en ruta) | 3/3 | **100%** | 1, 2, 3 |
| **(Subjetiva)** Preocupación constante por sobrecostos y control del presupuesto (*Burn Rate*) | 2/3 | **67%** | 2, 3 |
| **(Subjetiva)** Deseo de contar con un dashboard centralizado y en tiempo real | 3/3 | **100%** | 1, 2, 3 |

---

#### Análisis del Segmento 2: Proveedor / Distribuidor (Oferta)

Los entrevistados de este segmento (Leonardo, Marllely y Kevin) revelan que el estándar actual de la industria se limita al rastreo GPS tradicional, el cual solo brinda ubicación pero ignora el estado volumétrico de la carga. Esta limitación provoca que las mermas o robos ("ordeño") se detecten de forma muy tardía, recién al finalizar el proceso de entrega. Asimismo, expresan una profunda frustración administrativa: depender de que el chofer retorne con el papel físico firmado retrasa enormemente la facturación y el flujo de caja. Existe una disposición total hacia la adopción de sensores IoT y digitalización documental, siempre que el sistema reduzca errores operativos.

**Características Objetivas y Subjetivas:**

| Característica | Frecuencia (n/3) | Porcentaje | Entrevistas relacionadas |
| :--- | :--- | :--- | :--- |
| **(Objetiva)** Monitoreo actual limitado únicamente a ubicación GPS estándar | 3/3 | **100%** | 1(Leonardo), 2(Marllely), 3(Kevin) |
| **(Objetiva)** Detección tardía de mermas, robos o anomalías en el volumen | 3/3 | **100%** | 1, 2, 3 |
| **(Objetiva)** Dependencia de documentos en papel para el cierre y facturación | 3/3 | **100%** | 1, 2, 3 |
| **(Subjetiva)** Frustración por los retrasos en la facturación y cobranza por papeleo | 3/3 | **100%** | 1, 2, 3 |
| **(Subjetiva)** Inseguridad por penalizaciones injustas al no poder probar la integridad en ruta | 1/3 | **33%** | 1 |
| **(Subjetiva)** Disposición favorable hacia la adopción de telemetría IoT y digitalización | 3/3 | **100%** | 1, 2, 3 |
## 2.3. Needfinding

En el siguiente apartado, analizaremos a nuestros segmentos objetivos para identificar sus necesidades y en base a esto ofrecerles soluciones óptimas a sus problemas.

### 2.3.1. User Personas

**Segmento 1: El Cliente Corporativo (Demanda)**

<img src="../assets/User_persona1.png" alt="User persona - segmento 1" width="600"/>

_Imagen (N°2). Elaboración propia. Realizado en UXPressia_

**Segmento 2: El Proveedor / Distribuidor (Oferta)**

<img src="../assets/User_persona2.png" alt="User persona - segmento 2" width="600"/>

_Imagen (N°3). Elaboración propia. Realizado en UXPressia_
<br> 

### 2.3.2. User Task Matrix

En esta sección se presenta el *User Task Matrix*, el cual identifica y organiza las principales tareas que realizan los segmentos definidos para cumplir sus objetivos operativos. En esta matriz se destaca cómo la integración de tecnología **IoT** transforma procesos tradicionalmente manuales en flujos de monitoreo automatizado y toma de decisiones basada en datos en tiempo real.

**Segmento 1: Cliente Corporativo (Gestión de Operaciones y Logística)**

| Tareas del Usuario | Objetivo de la Tarea | Frecuencia | Importancia |
| :--- | :--- | :---: | :---: |
| **Monitorear niveles de stock (IoT)** | Evitar quiebres de stock mediante la lectura constante de sensores ultrasónicos. | Alta | Crítica |
| **Auditar consumo real vs. facturado** | Garantizar que el volumen de combustible pagado ingresó realmente al tanque. | Media | Alta |
| **Analizar "Burn Rate" diario** | Proyectar cuántos días de autonomía operativa quedan según el ritmo de gasto actual. | Alta | Alta |
| **Programar pedidos de reabastecimiento** | Automatizar la generación de órdenes de compra basada en niveles críticos del sensor. | Media | Alta |
| **Gestionar alertas de anomalías** | Reaccionar de forma inmediata ante caídas bruscas de nivel fuera del horario operativo. | Baja | Crítica |
| **Validar comprobantes digitales (Voucher)** | Agilizar la conciliación contable eliminando la dependencia de guías de remisión físicas. | Media | Media |

<br>

---

**Segmento 2: Proveedor / Distribuidor (Control de Flota y Despacho)**

| Tareas del Usuario | Objetivo de la Tarea | Frecuencia | Importancia |
| :--- | :--- | :---: | :---: |
| **Rastreo telemétrico de cisternas** | Supervisar en tiempo real la ubicación, velocidad y cumplimiento de rutas de las unidades. | Alta | Alta |
| **Monitorear integridad de carga (IoT)** | Detectar aperturas de válvulas no autorizadas o caídas de presión del tanque en ruta. | Alta | Crítica |
| **Asignar unidades y rutas de despacho** | Optimizar la logística de entrega basándose en la demanda real reportada por el sistema. | Alta | Alta |
| **Validar entregas mediante Geocercas** | Confirmar de forma automática y digital que la unidad llegó al punto de entrega pactado. | Alta | Alta |
| **Gestionar alertas de "Ordeño" (Robo)** | Activar protocolos de seguridad y bloqueo ante la detección de extracción ilícita en tránsito. | Ocasional | Crítica |
| **Digitalizar evidencias de entrega** | Eliminar el uso de documentos físicos para acelerar el ciclo de facturación y cobranza. | Alta | Alta |
<br>

### 2.3.3. User Journey Mapping

En esta sección se presenta el *User Journey Mapping* para los segmentos identificados, con el objetivo de visualizar las acciones (Doing), pensamientos (Thinking) y emociones (Feeling) de los usuarios a lo largo del proceso de abastecimiento de combustible.  

Se considera un entorno mejorado mediante IoT, donde la información en tiempo real permite reducir incertidumbre, optimizar la toma de decisiones y mejorar la experiencia general del usuario.


**Segmento 1: El Cliente Corporativo (Demanda)**

<img src="../assets/Journey_Map1.png" alt="User persona - segmento 1" width="600"/>

_Imagen (N°2). Elaboración propia. Realizado en UXPressia_

**Segmento 2: El Proveedor / Distribuidor (Oferta)**

<img src="../assets/Journey_Map2.png" alt="User persona - segmento 2" width="600"/>

_Imagen (N°3). Elaboración propia. Realizado en UXPressia_
<br> 

### 2.3.4. Empathy Mapping

![empathymap_segmento1](../assets/empathymap_segmento1.png)
![empathymap_segmento2](../assets/empathymap_segmento2.png)

## 2.4. Big Picture EventStorming

Nos reunimos para realizar una lluvia de ideas preliminar sobre los eventos que tendría nuestro proyecto.

![BigPictureEventStorming](../assets/BigPictureEventStorming.png)

## 2.5. Ubiquitous Language

| Término | Definición | Segmentos relacionados |
|---------|------------|------------------------|
| **Requester (Solicitante)** | Usuario representante de una empresa requiere abastecimiento de combustible | Solicitante |
| **Supplier (Proveedor)** | Empresa que ofrece combustibles al por mayor y compite mediante precios, descuentos y promociones. | Proveedor |
| **Fuel (Combustible)** | Recurso energético que es ofertado por los proveedores. Ejemplos: gasohol, diésel, GNV. | Solicitante, Proveedor |
| **Plant (Planta)** | Punto de distribución del combustible perteneciente a al proveedor. | Solicitante, Proveedor |
| **Price per gallon (Precio por galón)** | Valor económico que el proveedor establece por cada galón de combustible. Puede variar según planta, tipo de combustible, etc. | Solicitante, Proveedor |
| **Discount (Descuento)** | Reducción aplicada sobre el precio ofrecido, ya sea por volumen, fidelización u otras condicioens. | Solicitante, Proveedor |
| **Quotation (Cotización)** | Propuesta formal que un proveedor genera detallando precios, productos, entre otras condiciones | Solicitante, Proveedor |
| **Price Table (Tabla de precios)** | Grilla o tabla que muestra los precios ofrecidos por planta, proveedor y tipo de combustible. | Solicitante |
| **Negotiation (Negociación)**   | Intercambio de condiciones entre solicitante y proveedor para alcanzar un acuerdo favorable para ambas partes. | Solicitante, Proveedor |
| **Consumption Volume (Volumen de consumo)** | Cantidad de combustible estimada que una empresa solicita regularmente en un periodo determinado. | Solicitante |
| **Purchase History (Historial de compras)** | Registro de cotizaciones y compras o pedidos previos hechos por el solicitante dentro del sistema. | Solicitante |

﻿# Capítulo III: Requirements Specification

### 3.1. User Stories

En esta sección se presentan los requisitos definidos junto con el conjunto de *User Stories* y *Epics* correspondientes a las necesidades identificadas del sistema. Las *User Stories* permiten al equipo de desarrollo comprender de manera clara las expectativas de los usuarios finales, facilitando así la priorización y planificación de las funcionalidades del producto.

Asimismo, cada *User Story* incluye sus respectivos *Acceptance Criteria*, los cuales establecen las condiciones necesarias para validar su correcta implementación y garantizar que los requerimientos sean cumplidos de forma efectiva.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| *EP01* | *Gestionar pedidos como solicitante* | Como solicitante, quiere registrar, consultar y ajustar pedidos con trazabilidad para reducir errores. | **Escenario 1:** Registrar pedido: **Given** que el solicitante completa datos válidos, **When** registra el pedido, **Then** el sistema crea el pedido con ID y estado inicial “Pendiente”.<br>**Escenario 2:** Consultar historial: **Given** que existen pedidos, **When** el solicitante solicita su historial, **Then** el sistema retorna la lista con estados actuales.<br>**Escenario 3:** Editar antes de confirmación: **Given** un pedido “Pendiente”, **When** solicita edición, **Then** el sistema permite modificar campos permitidos y registra cambios. | EP01 |
| *EP02* | *Gestionar pedidos como proveedor* | Como proveedor, quiere revisar y actualizar pedidos, coordinar asignaciones y notificar al cliente para ejecutar la entrega. | **Escenario 1:** Ver pedidos entrantes: **Given** que hay pedidos activos, **When** el proveedor los consulta, **Then** obtiene la lista con datos operativos y estado.<br>**Escenario 2:** Actualizar estado: **Given** un pedido activo, **When** lo cambia a “Confirmado/En ruta/Entregado/Rechazado”, **Then** el nuevo estado queda persistido y trazado.<br>**Escenario 3:** Notificar cambios: **Given** un cambio de estado, **When** se confirma, **Then** el sistema emite notificación al solicitante. | EP02 |
| *EP03* | *Asegurar identidad y acceso* | Como usuario del sistema, quiere autenticación, control por roles y MFA en operaciones sensibles para proteger la información. | **Escenario 1:** Autenticar: **Given** credenciales válidas, **When** inicia sesión, **Then** accede a recursos según su rol.<br>**Escenario 2:** Restringir por rol: **Given** sesión activa, **When** intenta acceder a un recurso de otro rol, **Then** el acceso es denegado.<br>**Escenario 3:** MFA en operación crítica: **Given** una acción sensible (p. ej., confirmación de pedido), **When** se ejecuta, **Then** requiere verificación adicional exitosa. | EP03 |
| *EP04* | *Informar la propuesta (Landing)* | Como visitante, quiere entender beneficios y flujo para registrarse según su segmento. | **Escenario 1:** Acceso público: **Given** acceso sin autenticación, **When** solicita información, **Then** el sistema presenta contenido informativo y llamados a registro.<br>**Escenario 2:** Derivar registro por segmento: **Given** interés de registro, **When** el visitante elige su segmento, **Then** el sistema lo redirige al flujo de alta correspondiente. | EP04 |
| *US01* | *Registrar pedido* | Como solicitante, quiere registrar pedidos para agilizar la solicitud y evitar llamadas. | **Escenario 1:** Registro válido: **Given** datos de pedido válidos, **When** envía la solicitud, **Then** el sistema crea el pedido con ID y estado “Pendiente”.<br>**Escenario 2:** Datos inválidos: **Given** datos incompletos/incorrectos, **When** intenta registrar, **Then** el sistema rechaza y detalla validaciones. | EP01 |
| *US02* | *Consultar historial de pedidos* | Como solicitante, quiere consultar su historial con estados y detalles. | **Escenario 1:** Con registros: **Given** pedidos existentes, **When** consulta historial, **Then** el sistema retorna pedidos con estado actual (“Pendiente/Confirmado/En ruta/Entregado/Rechazado”).<br>**Escenario 2:** Sin registros: **Given** ausencia de pedidos, **When** consulta, **Then** el sistema retorna lista vacía con causa. | EP01 |
| *US03* | *Editar pedido no confirmado* | Como solicitante, quiere editar parámetros antes de confirmación del proveedor. | **Escenario 1:** Pedido editable: **Given** pedido “Pendiente”, **When** solicita edición, **Then** el sistema permite modificar campos permitidos.<br>**Escenario 2:** Pedido no editable: **Given** pedido “Confirmado” o superior, **When** solicita edición, **Then** el sistema impide cambios y registra el intento. | EP01 |
| *US05* | *Actualizar pedido* | Como proveedor, quiere actualizar estado e información operativa del pedido. | **Escenario 1:** Cambio de estado: **Given** un pedido activo, **When** cambia su estado a uno permitido, **Then** el sistema persiste la transición con marca de tiempo.<br>**Escenario 2:** Cambio inválido: **Given** reglas de flujo, **When** intenta transición no permitida, **Then** el sistema rechaza y explica la regla. | EP02 |
| *US06* | *Notificar cambios al cliente* | Como proveedor, quiere que el cliente reciba notificaciones automáticas ante cambios del pedido. | **Escenario 1:** Notificación por estado: **Given** un cambio a “Confirmado/En ruta/Entregado/Rechazado”, **When** se registra, **Then** el sistema envía la notificación al solicitante.<br>**Escenario 2:** Falla de notificación: **Given** indisponibilidad del servicio de mensajería, **When** se intenta notificar, **Then** el sistema registra el error y reintenta según política. | EP02 |
| *US07* | *Cancelar o rechazar pedido* | Como proveedor, quiere rechazar/cancelar pedidos con motivo para mantener claridad. | **Escenario 1:** Rechazo con motivo: **Given** imposibilidad de atención, **When** registra rechazo con motivo, **Then** el sistema cambia estado y asocia la justificación.<br>**Escenario 2:** Cancelación operativa: **Given** pedido activo, **When** solicita cancelación con motivo, **Then** el sistema cambia a “Cancelado” y notifica al solicitante. | EP02 |
| *US08* | *Iniciar sesión* | Como usuario, quiere iniciar sesión con credenciales válidas. | **Escenario 1:** Éxito: **Given** credenciales válidas, **When** inicia sesión, **Then** el sistema autentica y emite token de acceso.<br>**Escenario 2:** Falla: **Given** credenciales inválidas, **When** intenta autenticarse, **Then** el sistema niega acceso sin revelar detalles. | EP03 |
| *US09* | *Registrar cuenta* | Como visitante, quiere crear una cuenta con rol (Solicitante/Proveedor). | **Escenario 1:** Alta válida: **Given** datos válidos, **When** confirma el alta, **Then** el sistema crea la cuenta y habilita acceso.<br>**Escenario 2:** Alta inválida: **Given** datos inválidos, **When** solicita alta, **Then** el sistema rechaza y detalla validaciones. | EP03 |
| *US10* | *Recuperar contraseña* | Como usuario, quiere recuperar acceso por correo. | **Escenario 1:** Correo registrado: **Given** un correo válido, **When** solicita recuperación, **Then** el sistema genera token de restablecimiento y lo envía.<br>**Escenario 2:** Correo no registrado: **Given** un correo no existente, **When** solicita recuperación, **Then** el sistema informa que no encuentra el identificador. | EP03 |
| *US11* | *Restringir acceso por rol* | Como administrador, quiere que cada usuario acceda solo a recursos de su rol. | **Escenario 1:** Acceso permitido: **Given** rol y permisos, **When** accede a su recurso, **Then** el sistema permite la operación.<br>**Escenario 2:** Acceso denegado: **Given** recurso de otro rol, **When** intenta acceso, **Then** el sistema deniega y audita. | EP03 |
| *US12* | *Verificar MFA en pedidos* | Como solicitante, quiere MFA al emitir pedidos para mayor seguridad. | **Escenario 1:** Verificación exitosa: **Given** MFA activo, **When** confirma un pedido, **Then** finaliza solo si la verificación adicional es válida.<br>**Escenario 2:** Verificación fallida: **Given** MFA activo, **When** falla la verificación, **Then** el sistema cancela la acción. | EP03 |
| *US13* | *Explorar landing* | Como usuario no autenticado, quiere visualizar la propuesta y caminos a registro. | **Escenario 1:** Información visible: **Given** acceso público, **When** solicita información, **Then** el sistema expone beneficios y flujo de valor.<br>**Escenario 2:** Derivación a registro: **Given** interés, **When** elige registrarse, **Then** el sistema dirige al alta según segmento. | EP04 |
| *TS01* | *Exponer endpoint de pedidos (POST)* | Como developer, quiere un endpoint REST para registrar pedidos. | **Escenario 1:** Request válido (201): **Given** payload válido, **When** invoca el endpoint, **Then** persiste y retorna 201 con ID.<br>**Escenario 2:** Request inválido (400): **Given** payload inválido, **When** invoca, **Then** retorna 400 con detalle de validación. | EP01 |
| *TS02* | *Emitir token de autenticación (JWT)* | Como developer, quiere servicio de autenticación con JWT. | **Escenario 1:** Credenciales válidas (200): **Given** credenciales correctas, **When** solicita token, **Then** retorna JWT y vencimiento.<br>**Escenario 2:** Credenciales inválidas (401): **Given** credenciales incorrectas, **When** solicita, **Then** retorna 401. | EP03 |
| *TS03* | *Enviar notificaciones por cambio de estado* | Como developer, quiere servicio que emite notificaciones ante cambios de pedido. | **Escenario 1:** Notificación emitida: **Given** cambio de estado, **When** se confirma, **Then** el servicio envía notificación al destinatario.<br>**Escenario 2:** Error de mensajería: **Given** caída del proveedor de mensajería, **When** intenta enviar, **Then** registra error y gestiona reintentos/backoff. | EP02 |
| *TS04* | *Registrar ubicación GPS en ruta* | Como developer, quiere registrar coordenadas para trazabilidad. | **Escenario 1:** Registro exitoso: **Given** coordenadas válidas, **When** se reciben, **Then** el sistema almacena con marca de tiempo y pedido asociado.<br>**Escenario 2:** Datos inválidos: **Given** coordenadas inválidas, **When** se reciben, **Then** el sistema rechaza y audita.<br>**Escenario 3:** Frecuencia de envío: **Given** un dispositivo IoT activo, **When** transmite datos, **Then** el sistema recibe coordenadas a intervalos configurados. | EP02 |
| *US14* | *Consultar Home pública* | Como visitante proveedor, quiere un resumen del valor de la solución. | **Escenario 1:** Resumen visible: **Given** acceso público, **When** consulta el inicio, **Then** el sistema presenta propósito y propuesta de valor.<br>**Escenario 2:** CTA disponible: **Given** interés del visitante, **When** solicita continuar, **Then** existe un camino a registro o contacto. | EP04 |
| *US15* | *Conocer About Us* | Como visitante, quiere conocer el equipo y propósito para generar confianza. | **Escenario 1:** Información del equipo: **Given** acceso a About, **When** lo solicita, **Then** el sistema presenta información institucional verificable.<br>**Escenario 2:** Principios de la solución: **Given** About, **When** lo consulta, **Then** el sistema presenta visión/valores. | EP04 |
| *US16* | *Entender cómo funciona* | Como visitante, quiere comprender el flujo de operación. | **Escenario 1:** Flujo comprensible: **Given** sección “Cómo funciona”, **When** la revisa, **Then** entiende la interacción solicitante–proveedor a alto nivel.<br>**Escenario 2:** Casos de uso: **Given** la sección, **When** la consulta, **Then** identifica ejemplos típicos del proceso. | EP04 |
| *US17* | *Enviar contacto* | Como visitante, quiere remitir un mensaje de contacto. | **Escenario 1:** Envío válido: **Given** datos válidos, **When** remite el mensaje, **Then** el sistema registra y confirma recepción.<br>**Escenario 2:** Datos faltantes: **Given** datos incompletos, **When** intenta enviar, **Then** el sistema rechaza e indica los campos requeridos. | EP04 |
| *US18* | *Aprobar pedido* | Como proveedor, quiere aprobar pedidos según stock disponible. | **Escenario 1:** Aprobación con stock: **Given** stock suficiente, **When** aprueba, **Then** el estado cambia a “Confirmado”.<br>**Escenario 2:** Rechazo por falta de stock: **Given** stock insuficiente, **When** decide no aprobar, **Then** registra motivo y cambia a “Rechazado”. | EP02 |
| *TS19* | *Despachar pedido* | Como proveedor, quiere marcar un pedido como despachado para notificar al cliente. | **Escenario 1:** Despacho válido: **Given** pedido “Confirmado”, **When** marca “En ruta/Despachado”, **Then** el sistema actualiza estado y registra hora de salida.<br>**Escenario 2:** Restricción sin confirmación: **Given** pedido sin confirmar, **When** intenta despachar, **Then** el sistema rechaza la transición.<br>**Escenario 3:** Envío de ubicación: **Given** un pedido en estado "En ruta", **When** el vehículo transmite su ubicación, **Then** el sistema recibe coordenadas GPS periódicamente y las asocia al pedido. | EP02 |
| *US20* | *Cerrar pedido* | Como proveedor, quiere cerrar el pedido cuando la entrega se confirma. | **Escenario 1:** Cierre tras confirmación: **Given** entrega confirmada por el solicitante, **When** ejecuta cierre, **Then** el pedido pasa a “Entregado/Finalizado” e impide modificaciones.<br>**Escenario 2:** Intento sin confirmación: **Given** sin confirmación, **When** intenta cerrar, **Then** el sistema rechaza la acción. | EP02 |
| *US21* | *Generar reporte de ventas* | Como proveedor, quiere reportes operativos por rango de fechas. | **Escenario 1:** Rango con datos: **Given** fechas válidas con ventas, **When** solicita el reporte, **Then** el sistema genera el resumen.<br>**Escenario 2:** Rango sin datos: **Given** rango vacío, **When** solicita, **Then** el sistema informa ausencia de resultados. | EP02 |
| *US22* | *Visualizar KPIs de pedidos (Solicitante)* | Como solicitante, quiere ver un resumen por estado. | **Escenario 1:** Con datos: **Given** pedidos, **When** consulta KPIs, **Then** ve conteos por estado.<br>**Escenario 2:** Sin datos: **Given** sin pedidos, **When** consulta KPIs, **Then** el sistema indica que no hay registros. | EP01 |
| *US23* | *Visualizar KPIs de pedidos (Proveedor)* | Como proveedor, quiere ver resumen operativo por estado. | **Escenario 1:** Con datos: **Given** pedidos, **When** consulta, **Then** ve KPIs por estado.<br>**Escenario 2:** Error de carga: **Given** falla de fuente, **When** consulta, **Then** el sistema indica error y permite reintentar. | EP02 |
| *TS05* | *Autenticar (endpoint login)* | Como developer, quiere endpoint de login. | **Escenario 1:** 200 con token: **Given** credenciales válidas, **When** envía request, **Then** obtiene 200 + JWT.<br>**Escenario 2:** 401: **Given** credenciales inválidas, **When** envía request, **Then** obtiene 401.<br>**Escenario 3:** 500: **Given** error interno, **When** procesa, **Then** retorna 500 y registra en logs. | EP03 |
| *TS06* | *Recuperar contraseña (endpoint)* | Como developer, quiere endpoint de recuperación. | **Escenario 1:** Correo válido (202): **Given** correo existente, **When** solicita, **Then** genera token y envía email.<br>**Escenario 2:** 404: **Given** correo no registrado, **When** solicita, **Then** retorna 404.<br>**Escenario 3:** 500: **Given** fallo de correo, **When** envía, **Then** 500 y traza error. | EP03 |
| *TS07* | *Cerrar sesión (endpoint logout)* | Como developer, quiere endpoint para invalidar sesión. | **Escenario 1:** 200: **Given** token válido, **When** solicita logout, **Then** invalida sesión.<br>**Escenario 2:** 401: **Given** token inválido/expirado, **When** solicita, **Then** retorna 401. | EP03 |
| *TS24* | *Asignar vehículo a pedido* | Como proveedor, quiere asignar vehículo a pedido confirmado. | **Escenario 1:** Asignación válida: **Given** vehículo disponible y pedido “Confirmado”, **When** asigna, **Then** queda vinculado.<br>**Escenario 2:** Vehículo ocupado: **Given** vehículo con conflicto, **When** intenta asignar, **Then** el sistema rechaza por superposición.<br>**Escenario 3:** Validar dispositivo IoT: **Given** un vehículo seleccionado, **When** se valida disponibilidad, **Then** el sistema verifica que el dispositivo GPS esté activo. | EP02 |
| *US25* | *Asignar conductor a pedido* | Como proveedor, quiere asignar conductor disponible. | **Escenario 1:** Asignación válida: **Given** conductor libre y pedido listo, **When** asigna, **Then** queda vinculado.<br>**Escenario 2:** Conflicto de horario: **Given** conductor asignado en el mismo tramo, **When** intenta asignar, **Then** el sistema rechaza y explica conflicto. | EP02 |
| *TS26* | *Validar disponibilidad de transporte* | Como proveedor, quiere verificar disponibilidad de vehículos antes de asignar. | **Escenario 1:** No disponible por superposición: **Given** vehículo con asignación en la misma ventana, **When** se consulta, **Then** se marca no disponible.<br>**Escenario 2:** Disponible: **Given** sin conflictos, **When** se consulta, **Then** es seleccionable.<br>**Escenario 3:** Carrera concurrente: **Given** asignación reciente por otro usuario, **When** intenta seleccionar, **Then** el sistema rechaza y actualiza disponibilidad.<br>**Escenario 4:** Estado en tiempo real: **Given** un vehículo con dispositivo IoT, **When** se consulta disponibilidad, **Then** el sistema usa datos en tiempo real para determinar si está ocupado. | EP02 |
| *US27* | *Consultar perfil* | Como usuario, quiere ver su perfil para revisar datos. | **Escenario 1:** Éxito: **Given** sesión activa, **When** consulta, **Then** el sistema retorna su información de perfil.<br>**Escenario 2:** Error de fuente: **Given** falla al obtener datos, **When** consulta, **Then** el sistema informa el error conservando la sesión. | EP03 |
| *US28* | *Actualizar perfil* | Como usuario, quiere actualizar sus datos vigentes. | **Escenario 1:** Guardado válido: **Given** cambios válidos, **When** confirma, **Then** el sistema persiste cambios.<br>**Escenario 2:** Validación: **Given** campos requeridos faltantes, **When** intenta guardar, **Then** el sistema rechaza la operación con detalle. | EP03 |
| *US29* | *Buscar pedido por código* | Como usuario, quiere localizar rápidamente un pedido por su código. | **Escenario 1:** Encontrado: **Given** código existente, **When** busca, **Then** el sistema retorna el pedido.<br>**Escenario 2:** No encontrado: **Given** código inexistente, **When** busca, **Then** el sistema informa ausencia de coincidencias. | EP01/EP02 |
| *US30* | *Filtrar pedidos por estado* | Como usuario, quiere filtrar pedidos por estado operativo. | **Escenario 1:** Filtro con resultados: **Given** estado con coincidencias, **When** filtra, **Then** el sistema retorna solo los pedidos de ese estado.<br>**Escenario 2:** Sin resultados: **Given** estado sin coincidencias, **When** filtra, **Then** el sistema informa que no hay resultados. | EP01/EP02 |
| *US31* | *Recibir notificación de aprobación/rechazo* | Como solicitante, quiere ser notificado cuando cambie el estado del pedido. | **Escenario 1:** Notificación visible: **Given** cambio de estado, **When** el solicitante accede, **Then** la notificación está disponible hasta marcar como leída. | EP01 |
| *TS32* | *Recibir notificación de despacho* | Como solicitante, quiere ser notificado cuando el pedido salga a entrega. | **Escenario 1:** Despacho confirmado: **Given** cambio a “En ruta/Despachado”, **When** consulta, **Then** la notificación está disponible y asociada al pedido.<br>**Escenario 2:** Notificación por proximidad: **Given** el pedido en ruta, **When** el dispositivo IoT detecta cercanía al destino, **Then** el sistema notifica al solicitante. | EP01 |
| *US33* | *Listar empresas solicitantes* | Como proveedor, quiere listar empresas para gestión de clientes. | **Escenario 1:** Lista con datos: **Given** empresas registradas, **When** consulta, **Then** el sistema retorna el listado con métricas operativas.<br>**Escenario 2:** Lista vacía: **Given** sin empresas, **When** consulta, **Then** el sistema informa ausencia de registros. | EP02 |
| *US34* | *Consultar detalle de empresa* | Como proveedor, quiere ver detalle e historial de una empresa. | **Escenario 1:** Con historial: **Given** empresa con pedidos, **When** consulta, **Then** el sistema retorna pedidos, cantidades y fechas.<br>**Escenario 2:** Sin historial: **Given** empresa sin pedidos, **When** consulta, **Then** el sistema informa que no hay historial. | EP02 |
| *US35* | *Visualizar gráfico de consumo* | Como solicitante, quiere visualizar consumo mensual. | **Escenario 1:** Con datos: **Given** pedidos históricos, **When** consulta, **Then** el sistema calcula y expone consumo mensual.<br>**Escenario 2:** Sin datos: **Given** sin pedidos, **When** consulta, **Then** el sistema informa falta de datos suficientes. | EP01 |
| *US36* | *Visualizar gráfico de ventas* | Como proveedor, quiere visualizar ventas por mes. | **Escenario 1:** Con datos: **Given** despachos realizados, **When** consulta, **Then** el sistema expone totales por mes.<br>**Escenario 2:** Sin datos: **Given** sin ventas, **When** consulta, **Then** el sistema informa que no hay datos suficientes. | EP02 |
| *US37* | *Descargar reporte en PDF* | Como usuario, quiere descargar resúmenes operativos en PDF. | **Escenario 1:** Exportación con datos: **Given** periodo con información, **When** solicita exportar, **Then** el sistema genera el documento.<br>**Escenario 2:** Exportación sin datos: **Given** periodo vacío, **When** solicita, **Then** el sistema informa que no hay contenido exportable.<br>**Escenario 3:** Falla de generación: **Given** error de backend, **When** exporta, **Then** el sistema informa el fallo y conserva sesión. | EP01/EP02 |
| *SP01* | *Investigar conciliación de pagos y validación automática* | Como equipo, quiere investigar opciones de integración (e.g., pasarela/conciliación bancaria) para reducir retrasos por validación manual. | **Escenario 1:** Documentación revisada: **Given** proveedores de pago seleccionados, **When** se revisa documentación y webhooks, **Then** se documentan flujos recomendados.<br>**Escenario 2:** PoC mínimo: **Given** entorno de pruebas, **When** se implementa PoC de conciliación, **Then** se registra en repo y se documentan resultados.<br>**Escenario 3:** Criterios de decisión: **Given** hallazgos, **When** se comparan costos/riesgos, **Then** se proponen alternativas y estimaciones. | EP02/EP03 |


### 3.2. Impact Mapping

En esta sección, se presenta el Impact Mapping para cada segmento objetivo. Esta técnica permite visualizar cómo las características del producto contribuyen a los objetivos de negocio y cómo se alinean con las necesidades de los usuarios.


<img width="1240" height="1402" alt="image" src="https://github.com/user-attachments/assets/bb99c7fe-a9b6-44c6-b95f-0905c0dded52" />

<img width="1240" height="1562" alt="image" src="https://github.com/user-attachments/assets/809da5ce-9426-4f49-973a-08d6658bbf29" />

### 3.3. Product Backlog

Utilizamos la escala de Fibonacci para la estimación de los Story Points.



| # Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
| :---: | :--- | :--- | :--- | :---: |
| 01 | US01 | Crear nuevo pedido | Como solicitante, quiere registrar pedidos para agilizar la solicitud y evitar llamadas. | 5 |
| 02 | US02 | Consultar historial de pedidos | Como solicitante, quiere consultar su historial con estados y detalles. | 3 |
| 03 | US03 | Editar pedido no confirmado | Como solicitante, quiere editar parámetros antes de confirmación del proveedor. | 5 |
| 04 | US04 | Confirmar recepción de pedido | Como solicitante, quiere confirmar la recepción del pedido para finalizar la entrega. | 3 |
| 05 | US05 | Actualizar pedido | Como proveedor, quiere actualizar estado e información operativa del pedido. | 5 |
| 06 | US06 | Notificar cambios al cliente | Como proveedor, quiere que el cliente reciba notificaciones automáticas ante cambios del pedido. | 5 |
| 07 | US07 | Cancelar o rechazar pedido | Como proveedor, quiere rechazar/cancelar pedidos con motivo para mantener claridad. | 3 |
| 08 | US08 | Iniciar sesión | Como usuario, quiere iniciar sesión con credenciales válidas. | 3 |
| 09 | US09 | Registrar cuenta nueva | Como visitante, quiere crear una cuenta con rol (Solicitante/Proveedor). | 3 |
| 10 | US10 | Recuperar contraseña | Como usuario, quiere recuperar acceso por correo. | 3 |
| 11 | US11 | Restringir acceso por rol | Como administrador, quiere que cada usuario acceda solo a recursos de su rol. | 2 |
| 12 | US12 | Verificar MFA en pedidos | Como solicitante, quiere MFA al emitir pedidos para mayor seguridad. | 5 |
| 13 | US13 | Explorar landing (pública) | Como usuario no autenticado, quiere visualizar la propuesta y caminos a registro. | 2 |
| 14 | TS01 | Exponer endpoint de pedidos (POST) | Como developer, quiere un endpoint REST para registrar pedidos. | 5 |
| 15 | TS02 | Emitir token de autenticación (JWT) | Como developer, quiere servicio de autenticación con JWT. | 5 |
| 16 | TS03 | Enviar notificaciones por cambio de estado | Como developer, quiere servicio que emite notificaciones ante cambios de pedido. | 3 |
| 17 | TS04 | Registrar ubicación GPS en ruta | Como developer, quiere registrar coordenadas para trazabilidad. | 5 |
| 18 | US14 | Consultar Home pública | Como visitante proveedor, quiere un resumen del valor de la solución. | 2 |
| 19 | US15 | Conocer About Us | Como visitante, quiere conocer el equipo y propósito para generar confianza. | 2 |
| 20 | US16 | Entender cómo funciona | Como visitante, quiere comprender el flujo de operación. | 2 |
| 21 | US17 | Enviar contacto | Como visitante, quiere remitir un mensaje de contacto. | 3 |
| 22 | US18 | Aprobar pedido | Como proveedor, quiere aprobar pedidos según stock disponible. | 3 |
| 23 | TS19 | Despachar pedido | Como proveedor, quiere marcar un pedido como despachado para notificar al cliente. | 5 |
| 24 | US20 | Cerrar pedido | Como proveedor, quiere cerrar el pedido cuando la entrega se confirma. | 3 |
| 25 | US21 | Generar reporte de ventas | Como proveedor, quiere reportes operativos por rango de fechas. | 5 |
| 26 | US22 | Visualizar KPIs de pedidos (Solicitante) | Como solicitante, quiere ver un resumen por estado. | 5 |
| 27 | US23 | Visualizar KPIs de pedidos (Proveedor) | Como proveedor, quiere ver resumen operativo por estado. | 5 |
| 28 | TS05 | Autenticar (endpoint login) | Como developer, quiere endpoint de login. | 5 |
| 29 | TS06 | Recuperar contraseña (endpoint) | Como developer, quiere endpoint de recuperación. | 3 |
| 30 | TS07 | Cerrar sesión (endpoint logout) | Como developer, quiere endpoint para invalidar sesión. | 2 |
| 31 | TS24 | Asignar vehículo a pedido | Como proveedor, quiere asignar vehículo a pedido confirmado. | 5 |
| 32 | US25 | Asignar conductor a pedido | Como proveedor, quiere asignar conductor disponible. | 3 |
| 33 | TS26 | Validar disponibilidad de transporte | Como proveedor, quiere verificar disponibilidad de vehículos antes de asignar. | 8 |
| 34 | US27 | Consultar perfil | Como usuario, quiere ver su perfil para revisar datos. | 2 |
| 35 | US28 | Actualizar perfil | Como usuario, quiere actualizar sus datos vigentes. | 3 |
| 36 | US29 | Buscar pedido por código | Como usuario, quiere localizar rápidamente un pedido por su código. | 2 |
| 37 | US30 | Filtrar pedidos por estado | Como usuario, quiere filtrar pedidos por estado operativo. | 2 |
| 38 | US31 | Recibir notificación de aprobación/rechazo | Como solicitante, quiere ser notificado cuando cambie el estado del pedido. | 3 |
| 39 | TS32 | Recibir notificación de despacho | Como solicitante, quiere ser notificado cuando el pedido salga a entrega. | 5 |
| 40 | US33 | Listar empresas solicitantes | Como proveedor, quiere listar empresas para gestión de clientes. | 3 |
| 41 | US34 | Consultar detalle de empresa | Como proveedor, quiere ver detalle e historial de una empresa. | 3 |
| 42 | US35 | Visualizar gráfico de consumo | Como solicitante, quiere visualizar consumo mensual. | 5 |
| 43 | US36 | Visualizar gráfico de ventas | Como proveedor, quiere visualizar ventas por mes. | 5 |
| 44 | US37 | Descargar reporte en PDF | Como usuario, quiere descargar resúmenes operativos en PDF. | 5 |
| 45 | SP01 | Investigar conciliación de pagos y validación | Como equipo, quiere investigar opciones de integración (e.g., pasarela/conciliación bancaria) para reducir retrasos por validación manual. | 8 |

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming
Se llevó a cabo un proceso de Event Storming para identificar los Bounded Contexts de nuestro sistema. Durante este proceso, se siguieron los pasos que se describen a continuación:

## Collect Domain Events

Se plantean eventos importantes de todos los grupos funcionales en tiempo pasado y nomenclatura en inglés.

<img width="585" height="622" alt="image" src="https://github.com/user-attachments/assets/d63f6d4c-b6b0-4428-b2c9-c9249941d636" />

## Timeline
<img width="899" height="302" alt="image" src="https://github.com/user-attachments/assets/b106fc48-1643-4278-9595-4173b6fd6bb4" />

<img width="856" height="285" alt="image" src="https://github.com/user-attachments/assets/76c6dcde-c783-4cf1-a26c-0a017d0130d6" />

## Pain and Pivotal Points
En este paso se resaltan con un diamante los eventos por aclarar o que requieren de más conocimientos de especialistas. Por otro lado, los pivotal points son puntos de cambios que se marcan con una barra vertical. Por otro lado, los pivotal points son puntos de cambios que se marcan con una barra vertical.

<img width="881" height="358" alt="image" src="https://github.com/user-attachments/assets/bb6336e9-1fe4-406d-ba5d-171455ae246b" />

<img width="577" height="357" alt="image" src="https://github.com/user-attachments/assets/36dfe51b-8b70-47ab-b7ce-1c40e95320f1" />

#### 4.1.1.1 Candidate Context Discovery

<img width="768" height="769" alt="image" src="https://github.com/user-attachments/assets/471b6c99-3999-4d43-8442-dfc5301b5a15" />

<img width="811" height="464" alt="image" src="https://github.com/user-attachments/assets/3bbde438-aed5-40e4-bb24-b453903588cf" />

### 4.1.1.2 Domain Message Flows Modeling

Dado el diagrama de eventos de EventStorming y el descubrimiento de contextos candidatos, el siguiente paso es modelar los flujos de mensajes. A través de la técnica de **Domain Storytelling**, hemos mapeado cómo colaboran los Bounded Contexts para resolver los casos de uso principales del negocio, detallando la coreografía de comandos, eventos, sistemas y políticas.

A continuación, se presentan los escenarios clave que garantizan la trazabilidad desde la solicitud comercial hasta la interacción física con el hardware de la cisterna:

**Escenario 1: Creación y Validación del Pedido.** En este escenario, el actor (Cliente Corporativo) interactúa con la plataforma mediante el comando `Create order`. Este flujo es capturado por el contexto de *Order & Payment*, el cual, a través de sus políticas internas, verifica la disponibilidad de stock y se comunica con el sistema externo bancario (*Bank System*). Solo cuando se emite el evento `Payment validated`, la política de negocio autoriza que el pedido pase a la fase de despacho logístico.

![Container Level Diagram](../assets/Scenario1.png)



**Escenario 2: Despacho y Telemetría IoT.** Una vez que el pedido está validado, el contexto de *Logistics & IoT Telemetry* inicia el proceso con el comando `Start dispatch`. Al emitirse el evento de despacho, se activa la política de rastreo en vivo (`Activate live tracking`), la cual interactúa directamente con el hardware (*GPS IoT Device*). A medida que el dispositivo transmite su ubicación, la política de distancia evalúa las coordenadas. Al cumplirse la condición, se dispara el evento `Geofence entered`, el cual es consumido por el contexto de *Fulfillment* para ejecutar finalmente el comando físico de `Unlock valve` en el hardware de la cisterna, asegurando una descarga controlada y sin mermas.

![Container Level Diagram](../assets/Scenario2.png)

### 4.1.1.3 Bounded Context Canvases

Se crearon lienzos de Bounded Context (Canvases) para cada uno de los contextos identificados en el proceso de EventStorming. La elaboración de estos lienzos siguió un proceso iterativo que incluye la definición general del contexto, destilación de reglas de negocio, captura del lenguaje ubicuo y el análisis de capacidades y dependencias. 

Estos lienzos ayudan a definir los límites de cada contexto, sus responsabilidades y las interacciones formales con otros contextos en el ecosistema de FuelTrack.

<br>

<table border="1" style="width:100%; border-collapse: collapse; text-align: left;">
  <tr>
    <td style="width:50%; padding: 10px;"><b>Name:</b> Order & Payment</td>
    <td style="width:50%; padding: 10px;"><b>Model Traits:</b> Draft, execute, audit, gateway</td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Description:</b><br>
      <small>Summary of purposes and responsibilities</small><br>
      Este contexto se encarga de la captura inicial de la solicitud comercial del cliente, la verificación de inventario disponible y la interacción con la pasarela bancaria para validar fondos.
    </td>
    <td style="padding: 10px;" rowspan="3">
      <b>Messages Consumed and Produced:</b><br><br>
      <i>Messages Consumed:</i><br>
      - <b>Command:</b> Create order<br>
      - <b>Command:</b> Validate payment<br><br>
      <i>Messages Produced:</i><br>
      - <b>Event:</b> Order created<br>
      - <b>Event:</b> Payment validated
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Strategic Classification:</b><br>
      <small>Domain: Core | Business Model: Compliance | Evolution: Custom built</small>
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Business Decisions:</b><br>
      <small>Key business rules, policies, and decisions</small><br>
      - <b>Policy:</b> Verify stock availability.<br>
      - <b>Policy:</b> If payment is valid, allow dispatch.
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Ubiquitous Language:</b><br>
      <small>Key domain terminology</small><br>
      <code>Order</code>, <code>Payment</code>, <code>Stock</code>, <code>Bank System</code>
    </td>
    <td style="padding: 10px;">
      <b>Dependencies and Relationships:</b><br>
      - <b>Message Suppliers:</b> Bank System (Provides payment confirmation)<br>
      - <b>Message Consumers:</b> Logistics & IoT Telemetry (Consumes validation to start dispatch)
    </td>
  </tr>
</table>

<br>

<table border="1" style="width:100%; border-collapse: collapse; text-align: left;">
  <tr>
    <td style="width:50%; padding: 10px;"><b>Name:</b> Logistics & IoT Telemetry</td>
    <td style="width:50%; padding: 10px;"><b>Model Traits:</b> Execute, monitor, track</td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Description:</b><br>
      <small>Summary of purposes and responsibilities</small><br>
      Es el núcleo operativo. Gestiona la asignación de la flota y procesa en tiempo real la telemetría (ubicación GPS) enviada por los sensores IoT para evaluar geocercas y prevenir mermas en ruta.
    </td>
    <td style="padding: 10px;" rowspan="3">
      <b>Messages Consumed and Produced:</b><br><br>
      <i>Messages Consumed:</i><br>
      - <b>Command:</b> Start dispatch<br>
      - <b>Event:</b> Payment validated<br>
      - <b>Event:</b> GPS location transmitted<br><br>
      <i>Messages Produced:</i><br>
      - <b>Event:</b> Vehicle assigned<br>
      - <b>Event:</b> Order dispatched<br>
      - <b>Event:</b> Geofence entered
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Strategic Classification:</b><br>
      <small>Domain: Core | Business Model: Core differentiator | Evolution: Custom built</small>
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Business Decisions:</b><br>
      <small>Key business rules, policies, and decisions</small><br>
      - <b>Policy:</b> Activate live tracking upon dispatch.<br>
      - <b>Policy:</b> Check distance to client constantly.
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Ubiquitous Language:</b><br>
      <small>Key domain terminology</small><br>
      <code>Vehicle</code>, <code>Dispatch</code>, <code>Telemetry</code>, <code>Live Tracking</code>, <code>Geofence</code>
    </td>
    <td style="padding: 10px;">
      <b>Dependencies and Relationships:</b><br>
      - <b>Message Suppliers:</b> Order & Payment, GPS IoT Device, Geofencing System<br>
      - <b>Message Consumers:</b> Fulfillment (Depends on Geofence entered event)
    </td>
  </tr>
</table>

<br>

<table border="1" style="width:100%; border-collapse: collapse; text-align: left;">
  <tr>
    <td style="width:50%; padding: 10px;"><b>Name:</b> Fulfillment</td>
    <td style="width:50%; padding: 10px;"><b>Model Traits:</b> Execute, physical interaction</td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Description:</b><br>
      <small>Summary of purposes and responsibilities</small><br>
      Ejecuta de forma segura la entrega física en campo. Interpreta la llegada a la geocerca para interactuar directamente con el hardware de la cisterna, evitando descargas no autorizadas.
    </td>
    <td style="padding: 10px;" rowspan="3">
      <b>Messages Consumed and Produced:</b><br><br>
      <i>Messages Consumed:</i><br>
      - <b>Event:</b> Geofence entered<br>
      - <b>Event:</b> Discharge flow registered<br><br>
      <i>Messages Produced:</i><br>
      - <b>Command:</b> Unlock valve<br>
      - <b>Event:</b> Order delivered
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Strategic Classification:</b><br>
      <small>Domain: Core | Business Model: Core differentiator | Evolution: Custom built</small>
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Business Decisions:</b><br>
      <small>Key business rules, policies, and decisions</small><br>
      - <b>Policy:</b> Unlock valve ONLY if inside geofence.<br>
      - <b>Policy:</b> Mark order completed when flow stops.
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Ubiquitous Language:</b><br>
      <small>Key domain terminology</small><br>
      <code>Smart Valve</code>, <code>Flowmeter</code>, <code>Discharge Flow</code>, <code>Fulfillment</code>
    </td>
    <td style="padding: 10px;">
      <b>Dependencies and Relationships:</b><br>
      - <b>Message Suppliers:</b> Logistics & IoT Telemetry, IoT Flowmeter<br>
      - <b>Message Consumers:</b> Smart Valve Hardware, Reporting
    </td>
  </tr>
</table>

<br>

<table border="1" style="width:100%; border-collapse: collapse; text-align: left;">
  <tr>
    <td style="width:50%; padding: 10px;"><b>Name:</b> Reporting</td>
    <td style="width:50%; padding: 10px;"><b>Model Traits:</b> Audit, summary, notification</td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Description:</b><br>
      <small>Summary of purposes and responsibilities</small><br>
      Contexto de soporte encargado de recopilar la data transaccional y telemétrica final para generar los resúmenes de consumo, métricas de negocio y notificar a los clientes.
    </td>
    <td style="padding: 10px;" rowspan="3">
      <b>Messages Consumed and Produced:</b><br><br>
      <i>Messages Consumed:</i><br>
      - <b>Event:</b> Order delivered<br><br>
      <i>Messages Produced:</i><br>
      - <b>Event:</b> Consumption report generated<br>
      - <b>Event:</b> Notification sent
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Strategic Classification:</b><br>
      <small>Domain: Supporting | Business Model: Engagement | Evolution: Commodity</small>
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Business Decisions:</b><br>
      <small>Key business rules, policies, and decisions</small><br>
      - <b>Policy:</b> Generate final metrics based on delivered orders.
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <b>Ubiquitous Language:</b><br>
      <small>Key domain terminology</small><br>
      <code>Consumption Report</code>, <code>Metrics</code>, <code>Notification</code>, <code>Dashboard</code>
    </td>
    <td style="padding: 10px;">
      <b>Dependencies and Relationships:</b><br>
      - <b>Message Suppliers:</b> Fulfillment (Provides delivery confirmation)<br>
      - <b>Message Consumers:</b> Client / External Notification Services
    </td>
  </tr>
</table>

### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram

![System Landscape Diagram](/assets/SystemLandscapeDiagram.png)

#### 4.1.3.2. Software Architecture Context Level Diagrams
En esta sección se presenta el diagrama de contexto de la arquitectura de software, el cual ilustra a FuelTrack en el centro de las operaciones, interactuando de manera directa con sus usuarios objetivo y los sistemas físicos (hardware) de los que depende para su funcionamiento. Este primer nivel del modelo C4 nos permite tener una visión de alto nivel del alcance del ecosistema.

![Context Level Diagram](/assets/ContextLevelDiagram.png)

#### 4.1.3.3. Software Architecture Container Level Diagrams
En esta sección se presenta el diagrama de contenedores de la solución propuesta. Este diagrama detalla los contenedores de software y sus interrelaciones, proporcionando una visión general de la estructura interna del sistema.

![Container Level Diagram](/assets/ContainerLevelDiagram.png)

#### 4.1.3.4. Software Architecture Deployment Diagrams

El diagrama de despliegue muestra cómo se distribuyen los distintos componentes de software en su entorno de ejecución. El sistema está compuesto por una aplicación web (Vue.js) y una aplicación móvil (Flutter), las cuales se ejecutan en los navegadores y dispositivos de los usuarios. Estas aplicaciones se comunican mediante JSON/HTTPS con un API Gateway en la nube, el cual enruta las peticiones hacia un clúster de microservicios (IAM, Órdenes, Vouchers e IoT Monitoring) desarrollados en Python/FastAPI. Paralelamente, en el entorno físico de las cisternas, opera una Edge Application (C++) embebida que captura los datos de los sensores y los transmite vía MQTT hacia el backend. Todos los servicios internos realizan operaciones de lectura y escritura sobre un servidor de base de datos PostgreSQL centralizado. Además, la arquitectura se integra con sistemas en la nube externos como Google Maps para validación de rutas y geocercas, y Mercado Pago para procesar las transacciones B2B.

![Deployment Diagram](/assets/DeploymentDiagram.png)

## 4.2. Tactical-Level Domain-Driven Design
El Tactical-Level Domain-Driven Design permite profundizar en el diseño detallado de cada bounded context identificado durante el Strategic-Level Design, definiendo la estructura interna de cada contexto delimitado mediante sus respectivas capas arquitectónicas, entidades de dominio, servicios y patrones de implementación específicos para FuelTrack.

Esta fase táctica se enfoca en la implementación concreta de los bounded contexts, aplicando patrones DDD como Domain Layer, encargada de la lógica de negocio pura; Interface Layer, responsable de controladores y DTOs; Application Layer, orientada a la orquestación de casos de uso; e Infrastructure Layer, encargada de la persistencia, mensajería e integración con servicios externos. Cada contexto mantiene su autonomía e integridad, comunicándose con otros mediante interfaces bien definidas que preservan los límites del dominio.

### 4.2.1. Bounded Context: Order & Payment Context

#### 4.2.1.1. Domain Layer

La Domain Layer del bounded context **Order & Payment** contiene la lógica de negocio relacionada con la creación de pedidos de combustible, validación del presupuesto disponible, aprobación de órdenes y asignación de rutas de despacho dentro del sistema FuelTrack.

**Aggregate Root:**

- **FuelOrder:** Representa el pedido de combustible y actúa como raíz del agregado. Controla el ciclo de vida de la orden desde su creación hasta su aprobación, tránsito, entrega o rechazo.

**Entities:**

- **DispatchRoute:** Representa la ruta asignada para el despacho del pedido. Incluye información como el identificador de ruta, placa del camión y hora estimada de llegada.

**Value Objects:**

- **FuelVolume:** Representa el volumen solicitado de combustible, compuesto por una cantidad y una unidad de medida.
- **Money:** Representa el costo total del pedido, compuesto por monto y moneda.
- **OrderStatus:** Define los estados posibles de una orden: PENDING, APPROVED, IN_TRANSIT, DELIVERED y REJECTED.

**Domain Services:**

- **OrderValidationService:** Verifica que la orden cumpla con las condiciones necesarias para ser creada.
- **BudgetValidationService:** Valida que el presupuesto disponible del cliente sea suficiente para aprobar la orden.
- **RouteAssignmentService:** Gestiona la asignación de una ruta de despacho a una orden aprobada.


#### 4.2.1.2. Interface Layer

La Interface Layer expone las funcionalidades del contexto mediante controladores REST, permitiendo que los clientes corporativos creen pedidos, consulten su estado y visualicen la ruta asignada.

**Controllers:**

- **OrderController:** Gestiona la creación, consulta, aprobación y actualización del estado de las órdenes.
- **DispatchRouteController:** Permite consultar o asignar rutas de despacho asociadas a una orden.

**DTOs:**

- **CreateOrderRequest / CreateOrderResponse**
- **ApproveOrderRequest / ApproveOrderResponse**
- **AssignRouteRequest / AssignRouteResponse**
- **OrderStatusResponse**


#### 4.2.1.3. Application Layer

La Application Layer orquesta los casos de uso relacionados con la gestión de pedidos y asignación logística, coordinando la interacción entre controladores, agregados de dominio y repositorios.

**Command Handlers:**

- **CreateOrderCommandHandler:** Procesa la creación de una nueva orden de combustible.
- **ValidateBurnRateCommandHandler:** Valida el presupuesto disponible antes de aprobar la orden.
- **ApproveOrderCommandHandler:** Cambia el estado de la orden a aprobada cuando cumple las reglas de negocio.
- **AssignRouteCommandHandler:** Asigna una ruta de despacho a una orden aprobada.

**Application Services:**

- **OrderApplicationService:** Coordina el ciclo de vida de la orden de combustible.
- **DispatchApplicationService:** Coordina la asignación y actualización de rutas de despacho.


#### 4.2.1.4. Infrastructure Layer

La Infrastructure Layer implementa la persistencia de datos y la comunicación con componentes técnicos necesarios para almacenar órdenes y rutas.

**Repositories:**

- **OrderRepository:** Gestiona la persistencia de las órdenes en la tabla `FUEL_ORDERS`.
- **DispatchRouteRepository:** Gestiona la persistencia de las rutas en la tabla `DISPATCH_ROUTES`.

**Database Tables:**

- **FUEL_ORDERS:** Almacena la información principal de cada pedido, incluyendo cliente, volumen, costo, moneda, estado y fecha de creación.
- **DISPATCH_ROUTES:** Almacena las rutas asignadas a los pedidos, incluyendo placa del camión, hora estimada de llegada y fecha de despacho.

**External Services:**

- **CustomerBudgetService:** Permite validar el presupuesto disponible del cliente.
- **RoutingService:** Apoya la asignación de rutas para el despacho del combustible.

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams.

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Order API Application** perteneciente al *Order & Dispatch Context*. 

El diseño de los componentes sigue los principios de la **Arquitectura Limpia (Clean Architecture)**. Como se observa en el diagrama, el flujo de dependencias es estrictamente unidireccional. Las solicitudes HTTP ingresan a través de la capa de interfaz (`Order Controller`), son orquestadas por el servicio de aplicación (`Order Application Service`), y este finalmente delega la ejecución de las reglas corporativas al núcleo del sistema (`FuelOrder Aggregate`) y la persistencia de datos al repositorio (`Order Repository`). Esta separación garantiza que la lógica del negocio B2B sea completamente independiente del framework web y de la base de datos PostgreSQL.

![Component Diagram - Order Context](../assets/cap4/c4-component-order.png)

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams.

En este nivel de abstracción (Nivel 4 del Modelo C4), nos adentramos en el diseño táctico del **Order & Dispatch Context**. Para garantizar un modelo de software robusto y evitar el antipatrón de "modelo anémico", aplicamos los principios de Domain-Driven Design (DDD).

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams.

A continuación, se presenta el modelo de dominio interno. El *Aggregate Root* principal es `FuelOrder`, el cual actúa como límite transaccional para la creación y aprobación de pedidos B2B. Para asegurar la integridad de los datos financieros y de medición, se implementan *Value Objects* inmutables como `FuelVolume` y `Money`. Finalmente, la entidad `DispatchRoute` gestiona la asignación logística del camión.

![Class Diagram - Order Context](../assets/cap4/c4-class-order.png)

##### 4.2.1.6.2. Bounded Context Database Design Diagram.

Bajo el principio arquitectónico de *Database-per-Service*, este contexto administra su propia persistencia. El modelo físico en PostgreSQL refleja las entidades del dominio, optimizado para consultas transaccionales de pedidos de hidrocarburos.

![Database Diagram - Order Context](../assets/cap4/c4-db-order.png)


### 4.2.2. Bounded Context: IoT & Telemetry Context

#### 4.2.2.1. Domain Layer

La Domain Layer del contexto **IoT & Telemetry** gestiona la lógica relacionada con el monitoreo en tiempo real de las unidades de transporte mediante sensores IoT, permitiendo el registro de mediciones, análisis de anomalías y generación de alertas.

**Aggregate Root:**

- **TruckTelemetry:** Actúa como raíz del agregado y es responsable de registrar lecturas de sensores y analizar posibles anomalías en el comportamiento del vehículo.

**Entities:**

- **SensorReading:** Representa cada lectura capturada por los sensores del vehículo, incluyendo información temporal y estado de procesamiento.
- **TelemetryAlert:** Representa una incidencia detectada (por ejemplo, caída de presión o posible robo de combustible), almacenando su tipo, severidad y estado.

**Value Objects:**

- **GeoLocation:** Representa la ubicación geográfica del vehículo mediante latitud y longitud.
- **FuelVolume:** Representa el volumen de combustible y presión del tanque.
- **EngineStatus:** Representa el estado del motor, incluyendo si está encendido y el nivel de batería.

**Domain Services:**

- **AnomalyDetectionService:** Detecta eventos anómalos como caídas abruptas de combustible o comportamientos fuera de lo esperado.
- **GeofenceService:** Verifica si el vehículo se encuentra dentro de zonas permitidas.
- **TelemetryProcessingService:** Procesa las lecturas de sensores y coordina su análisis dentro del dominio.

#### 4.2.2.2. Interface Layer

La Interface Layer permite la recepción de datos provenientes de dispositivos IoT y la consulta de información de monitoreo por parte de los usuarios.

**Components:**

- **IoTEventConsumer:** Recibe y decodifica datos enviados desde sensores mediante el protocolo MQTT.
- **TelemetryController:** Expone endpoints para consultar el estado del vehículo, historial de lecturas y alertas generadas.

**DTOs:**

- **TelemetryDataDTO**
- **TelemetryResponseDTO**
- **AlertResponseDTO**


#### 4.2.2.3. Application Layer

La Application Layer orquesta el flujo de procesamiento de datos IoT, desde la recepción de lecturas hasta la generación de alertas.

**Application Services:**

- **TelemetryApplicationService:** Procesa eventos IoT, registra lecturas y coordina el análisis de datos.
- **AlertManagementService:** Gestiona la creación, almacenamiento y resolución de alertas.

#### 4.2.2.4. Infrastructure Layer

La Infrastructure Layer gestiona la comunicación con dispositivos físicos, mensajería y persistencia de datos optimizada para series de tiempo.

**Repositories:**

- **TelemetryRepository:** Gestiona la persistencia de lecturas en la tabla `SENSOR_READINGS`.
- **AlertRepository:** Gestiona la persistencia de alertas en la tabla `TELEMETRY_ALERTS`.
- **TrackingRepository:** Gestiona el estado actual del vehículo en la tabla `TRUCK_TRACKING`.

**Database Design:**

El diseño de la base de datos para este microservicio está optimizado para **series de tiempo (Time-Series Data)**.

- **SENSOR_READINGS:** Tabla de tipo *write-heavy*, donde se almacenan de forma inmutable todas las lecturas de sensores (ubicación, combustible, presión, estado del motor).
- **TELEMETRY_ALERTS:** Tabla que registra las incidencias detectadas, incluyendo tipo de alerta, severidad y estado de resolución.
- **TRUCK_TRACKING:** Tabla que mantiene el estado actual del vehículo y su última actualización.

**External Services:**

- **MQTTBrokerService:** Gestiona la comunicación con dispositivos IoT.
- **GPSIntegrationService:** Proporciona soporte para procesamiento de coordenadas y geolocalización.

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams.

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Telemetry Service Application** perteneciente al *IoT & Telemetry Context*.

Al igual que en el resto del sistema, los componentes se organizan bajo los principios de la **Arquitectura Limpia (Clean Architecture)**. En este contexto altamente transaccional, el flujo de entrada principal es manejado por un consumidor de eventos (`IoT Event Consumer`) que escucha las tramas enviadas por los sensores de hardware. Estas tramas son procesadas por el servicio de aplicación (`Telemetry App Service`), el cual delega la detección de anomalías (como mermas de combustible o salidas de ruta) al modelo de dominio puro (`TruckTelemetry Aggregate`). Finalmente, el estado se persiste a través del repositorio (`Telemetry Repository`) en una base de datos optimizada. Este diseño aísla la compleja lógica matemática del dominio de la infraestructura externa de mensajería.

![Component Diagram - Telemetry Context](../assets/cap4/c4-component-telemetry.png)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams.

En este nivel (C4 Model - Nivel 4), detallamos el diseño táctico del **IoT & Telemetry Context**. Dado que este módulo procesa flujos masivos de datos en tiempo real (Event-Driven), el modelo de dominio está diseñado para ser altamente resiliente y reactivo.

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams.

El núcleo de este contexto es el *Aggregate Root* `TruckTelemetry`, responsable de consolidar y analizar el flujo de datos. Para garantizar la inmutabilidad de las mediciones físicas, se emplean *Value Objects* como `GeoLocation` (coordenadas GPS), `FuelVolume` (galones y presión) y `EngineStatus`. Una característica avanzada de este diseño es la emisión de *Domain Events* (ej. `FuelDropDetectedEvent`) cuando la lógica matemática detecta una anomalía severa, como una caída abrupta de presión que sugiere un robo de hidrocarburos.

![Class Diagram - Telemetry Context](../assets/cap4/c4-class-telemetry.png)

##### 4.2.2.6.2. Bounded Context Database Design Diagram.

El diseño de la base de datos exclusiva para este microservicio está optimizado para series de tiempo (Time-Series Data). La tabla `SENSOR_READINGS` es de solo inserción (Write-Heavy) para registrar el histórico inmutable, mientras que `TELEMETRY_ALERTS` almacena la auditoría de las incidencias detectadas.

![Database Diagram - Telemetry Context](../assets/cap4/c4-db-telemetry.png)


### 4.2.3. Bounded Context: Financial & Billing Context

#### 4.2.3.1. Domain Layer

La Domain Layer del contexto **Financial & Billing** gestiona la lógica financiera del sistema, incluyendo el control de saldo del cliente, validación de crédito, cálculo de consumo y generación de comprobantes de facturación.

**Aggregate Root:**

- **FinancialAccount:** Actúa como raíz del agregado y gestiona el saldo disponible del cliente, la exposición crediticia y la validación de capacidad de pago.

**Entities:**

- **BillingVoucher:** Representa el comprobante de facturación generado a partir de una orden, incluyendo el monto total y los impuestos asociados.

**Value Objects:**

- **Money:** Representa valores monetarios mediante monto y tipo de moneda.
- **BurnRate:** Representa la tasa de consumo del cliente, incluyendo consumo promedio diario y proyección de días restantes de combustible.
- **CreditLimit:** Representa el límite de crédito del cliente y su exposición actual.

**Domain Services:**

- **CreditValidationService:** Valida si el cliente cuenta con suficiente crédito disponible.
- **BillingCalculationService:** Calcula montos totales, impuestos y generación de vouchers.
- **FinancialMonitoringService:** Analiza el consumo del cliente y su comportamiento financiero.

#### 4.2.3.2. Interface Layer

La Interface Layer expone las funcionalidades financieras a través de endpoints REST, permitiendo la consulta de estados financieros, generación de comprobantes y monitoreo de consumo.

**Controllers:**

- **BillingController:** Expone endpoints para facturación, consulta de saldos y reportes financieros.

**DTOs:**

- **CreateInvoiceRequest / Response**
- **BillingSummaryResponse**
- **CreditValidationResponse**
- **TransactionHistoryResponse**

#### 4.2.3.3. Application Layer

La Application Layer orquesta los casos de uso financieros, coordinando la generación de comprobantes, validación de crédito y registro de transacciones.

**Application Services:**

- **BillingApplicationService:** Gestiona la generación de vouchers y cálculo de consumo.
- **FinancialAccountService:** Coordina operaciones sobre cuentas financieras.
- **TransactionManagementService:** Registra y consulta transacciones financieras.

4.2.3.4. Infrastructure Layer

La Infrastructure Layer gestiona la persistencia de datos financieros y la integración con sistemas externos.

**Repositories:**

- **BillingRepository:** Gestiona la persistencia de comprobantes en la tabla `INVOICES`.
- **AccountRepository:** Gestiona la información de cuentas en la tabla `BILLING_ACCOUNTS`.
- **TransactionRepository:** Gestiona el historial de transacciones en la tabla `TRANSACTION_LOGS`.

**Database Design**

El diseño de la base de datos sigue el principio de **Database-per-Service**, donde este contexto administra su propia persistencia financiera.

- **BILLING_ACCOUNTS:** Almacena el saldo actual, límite de crédito y última conciliación del cliente.
- **INVOICES:** Registra los comprobantes generados por cada orden, incluyendo montos totales, impuestos y estado.
- **TRANSACTION_LOGS:** Mantiene un historial inmutable de todas las transacciones financieras realizadas.

**External Services**

- **ERP Gateway:** Actúa como una capa anticorrupción (ACL) para integrarse con sistemas contables externos (ej. SAP).
- **PaymentIntegrationService:** Permite la validación de operaciones financieras externas.

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams.

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Billing API Application** perteneciente al *Financial & Billing Context*.

Este módulo crítico está diseñado bajo los principios de la **Arquitectura Limpia (Clean Architecture)**. Las peticiones relacionadas con la facturación y el monitoreo de presupuesto ingresan por la capa de interfaz (`Billing Controller`). La orquestación es manejada por el servicio de aplicación (`Billing App Service`), el cual delega el cálculo del *Burn Rate* y la validación de saldos al modelo de dominio (`Financial Aggregate`). 

Una característica clave de este contenedor es la inclusión de un adaptador (`ERP Gateway`) en la capa de infraestructura, el cual funciona como una Capa Anticorrupción (ACL) para comunicarse con los sistemas contables externos de los clientes (ej. SAP). Finalmente, los comprobantes inmutables se almacenan a través del repositorio (`Billing Repository`). Este diseño asegura que el núcleo financiero de FuelTrack no se acople a integraciones de terceros.

![Component Diagram - Billing Context](../assets/cap4/c4-component-billing.png)


#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams.

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Billing API Application** perteneciente al *Financial & Billing Context*.

Este módulo crítico está diseñado bajo los principios de la **Arquitectura Limpia (Clean Architecture)**. Las peticiones relacionadas con la facturación y el monitoreo de presupuesto ingresan por la capa de interfaz (`Billing Controller`). La orquestación es manejada por el servicio de aplicación (`Billing App Service`), el cual delega el cálculo del *Burn Rate* y la validación de saldos al modelo de dominio (`Financial Aggregate`). 

Una característica clave de este contenedor es la inclusión de un adaptador (`ERP Gateway`) en la capa de infraestructura, el cual funciona como una Capa Anticorrupción (ACL) para comunicarse con los sistemas contables externos de los clientes (ej. SAP). Finalmente, los comprobantes inmutables se almacenan a través del repositorio (`Billing Repository`). Este diseño asegura que el núcleo financiero de FuelTrack no se acople a integraciones de terceros.

![Component Diagram - Billing Context](../assets/cap4/c4-component-billing.png)





#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams.

En este nivel de diseño técnico (Nivel 4 del Modelo C4), se detalla la lógica de implementación del **Financial & Billing Context**. El diseño se centra en la precisión de los cálculos financieros y la integridad de los comprobantes de pago generados.

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams.

El diseño del dominio está centrado en el Aggregate Root `FinancialAccount`, el cual gestiona el saldo y la exposición crediticia del cliente. Se utilizan *Value Objects* para encapsular la lógica de cálculo del `BurnRate` (tasa de consumo) y el `CreditLimit`. La entidad `BillingVoucher` representa el documento legal de facturación generado tras un despacho exitoso. Este modelo asegura que no existan inconsistencias entre el combustible despachado y el monto facturado.

![Class Diagram - Billing Context](../assets/cap4/c4-class-billing.png)

##### 4.2.3.6.2. Bounded Context Database Design Diagram.

El esquema de base de datos para este contexto está diseñado para mantener un historial de transacciones inmutable. La tabla `BILLING_ACCOUNTS` almacena los saldos actuales, mientras que `INVOICES` y `TRANSACTION_LOGS` registran cada movimiento financiero con marcas de tiempo precisas para fines de auditoría.

![Database Diagram - Billing Context](../assets/cap4/c4-db-billing.png)

### 4.2.4. Bounded Context: Identity & Access Context

#### 4.2.4.1. Domain Layer

La Domain Layer del contexto **Identity & Access** gestiona la lógica relacionada con la autenticación, autorización y control de acceso de los usuarios dentro del sistema FuelTrack.

**Aggregate Root:**

- **UserAccount:** Actúa como raíz del agregado y es responsable de la autenticación del usuario, asignación de roles y validación de permisos.

**Entities:**

- **Role:** Representa los roles asignados a los usuarios del sistema, incluyendo su nombre y descripción.

**Value Objects:**

- **EmailAddress:** Representa el correo electrónico del usuario, incluyendo validación de formato y verificación.
- **PasswordHash:** Representa la contraseña encriptada del usuario, incluyendo el hash y el salt, así como la lógica de verificación.
  
**Domain Services:**

- **AuthenticationService:** Gestiona la validación de credenciales de acceso.
- **AuthorizationService:** Verifica permisos y roles del usuario (RBAC).
- **PasswordPolicyService:** Define reglas de seguridad para contraseñas. 


#### 4.2.4.2. Interface Layer

La Interface Layer permite la interacción de los usuarios con el sistema mediante endpoints REST para autenticación y validación de acceso.

**Controllers:**

- **AuthController:** Expone endpoints para login, validación de tokens y control de acceso.

**DTOs:**

- **LoginRequest / LoginResponse**
- **TokenValidationRequest / Response**
- **UserAuthResponse**


#### 4.2.4.3. Application Layer

La Application Layer orquesta los procesos de autenticación, emisión de tokens y validación de permisos.

**Application Services:**

- **IdentityApplicationService:** Coordina el proceso de autenticación y generación de tokens JWT.
- **AccessControlService:** Gestiona la validación de roles y permisos.

#### 4.2.4.4. Infrastructure Layer

La Infrastructure Layer gestiona la persistencia de usuarios, roles y credenciales, así como la generación de tokens de acceso.

**Repositories:**

- **AuthRepository:** Gestiona la persistencia de usuarios, roles y credenciales en la base de datos.

**Database Design**

El diseño de la base de datos sigue el principio de **Database-per-Service**, donde este contexto administra su propia persistencia de identidad y acceso.

- **AUTH_DATABASE:** Almacena información de usuarios, roles y credenciales encriptadas.
- Los datos incluyen identificadores de usuario, roles asignados y hashes de contraseñas con sus respectivos mecanismos de seguridad.

**External Services**

- **TokenService:** Generación y validación de tokens JWT.
- **EncryptionService:** Manejo de hashing y verificación de contraseñas.

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams.

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Auth API Application** perteneciente al *Identity & Access Context*.

Este módulo fundamental sigue los lineamientos de la **Arquitectura Limpia (Clean Architecture)** para centralizar la seguridad de FuelTrack. Las solicitudes de autenticación y validación de tokens ingresan mediante la capa de interfaz (`Auth Controller`). El servicio de aplicación (`Identity App Service`) orquesta la emisión de tokens JWT y delega la validación de contraseñas y permisos granulares (RBAC) al modelo de dominio (`User & Role Aggregate`). Finalmente, las credenciales encriptadas se gestionan a través del repositorio (`Auth Repository`). Esta separación garantiza que la lógica de seguridad y el control de accesos sean invulnerables y agnósticos al resto de los microservicios.

![Component Diagram - Identity Context](../assets/cap4/c4-component-identity.png)

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams.

En este último apartado de diseño táctico (Nivel 4 del Modelo C4), nos enfocamos en el **Identity & Access Context**. El diseño de este módulo está estrictamente aislado del resto de Bounded Contexts para garantizar que la seguridad, autenticación y autorización sean transversales e inviolables.

##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams.

El modelo de dominio pivota sobre el *Aggregate Root* `UserAccount`. Para aplicar una seguridad robusta desde el diseño, la contraseña jamás se maneja como un texto plano, sino que se encapsula en un *Value Object* inmutable llamado `PasswordHash` que contiene la lógica de verificación criptográfica. Asimismo, se implementa la entidad `Role` para gestionar el Control de Acceso Basado en Roles (RBAC), permitiendo diferenciar los permisos de gerentes corporativos, despachadores y choferes de cisternas.

![Class Diagram - Identity Context](../assets/cap4/c4-class-identity.png)

##### 4.2.4.6.2. Bounded Context Database Design Diagram.

El esquema físico en PostgreSQL para el contexto de identidad está altamente normalizado para soportar la asignación dinámica de roles y permisos. Se emplean tablas intermedias (`USER_ROLES` y `ROLE_PERMISSIONS`) para resolver las relaciones de muchos a muchos inherentes a una arquitectura RBAC completa.

![Database Diagram - Identity Context](../assets/cap4/c4-db-identity.png)

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines
### 5.1.2. Web, Mobile and Iot Style Guidelines
## 5.2 Information Architecture
### 5.2.1. Organization Systems
### 5.2.2. Labeling Systems
### 5.2.3. SEO Tags and Meta Tags
### 5.2.4. Searching Systems
### 5.2.5. Navigation Systems

## 5.3 Landing Page UI Design
### 5.3.1. Landing Page Wireframe
### 5.3.2. Landing Page Mock-up

## 5.4 Applications UX/UI Design
### 5.4.1. Applications Wireframes
### 5.4.2. Applications Wireflow Diagrams
### 5.4.3. Applications Mock-ups
### 5.4.4. Applications User Flow Diagrams

## 5.5 Applications Prototyping

## 5.6 IoT Device Design


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


