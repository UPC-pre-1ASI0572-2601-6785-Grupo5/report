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

# Capítulo I: Introducción

## 1.1. Startup Profile

En la presente sección se expone información general relacionada con la startup desarrolladora de la propuesta.

## 1.1.1. Descripción de la Startup

Nova Asesors es una startup tecnológica enfocada en el desarrollo de soluciones digitales para facilitar el acceso a servicios de asesoría profesional. Surge como respuesta a la informalidad y dispersión existente en la postulación de consultores independientes.

Mediante una plataforma web, Nova Asesors busca optimizar el proceso de búsqueda y selección de especialistas, brindando a los usuarios una experiencia ágil, segura y accesible. De esta manera, se promueve una mejor toma de decisiones tanto en el ámbito personal como empresarial, sin intervenir directamente en la ejecución de las actividades del cliente.

La misión de Nova Asesors es brindar acceso eficiente y confiable a servicios de consultoría profesional mediante una plataforma digital que conecte a usuarios con expertos, contribuyendo al desarrollo de proyectos, negocios y objetivos personales.

La visión de Nova Asesors es consolidarse como una de las principales plataformas de consultoría digital en Latinoamérica, reconocida por su innovación tecnológica, calidad de servicio y confianza generada entre usuarios y profesionales afiliados.

El principal producto de la startup es FinTeka, una plataforma digital que conecta usuarios, empresas y profesionales especializados de diversas áreas, permitiendo buscar, comparar y contactar perfiles de manera eficiente. Además, facilita la gestión de agendas, reservas y comunicación dentro de un entorno integrado. FinTeka opera como una plataforma de intermediación orientada a la **postulación** y solicitud de servicios profesionales, donde la contratación final se realiza directamente entre las partes involucradas. Su finalidad es centralizar el acceso a asesoría profesional de forma organizada, confiable y accesible.

### 1.1.2. Perfiles de integrantes del equipo

| Miembros del equipo                                                                                                        | Código Estudiante | Carrera                | Conocimientos / Habilidades                                                                                                                                                                                 |
|----------------------------------------------------------------------------------------------------------------------------|-------------------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Mamani Marca, Gabriel Cristian <br><img src="../assets/GabrielMamani.png" alt="Gabriel" width="120" height="120"> <br> <br> | u202220659        | Ingeniería de Software | Soy estudiante de sexto o séptimo de la carrera de Ingeniería de Software. Durante el camino aprendí lenguajes como C++, Python, Java y .Net. También, sobre  gestores de base de datos como MongoDB y MySQL. |
|<br> Daiki Oscar Oshiro Yamashita <br><img src="../assets/Daiki.png" alt="Daiki" width="120" height="120"> |U20201F846|Ingeniería de Software|Soy estudiante de la carrera de Ingeniería de Software. Tengo interés en obtener nuevos conocimientos relacionados con mi carrera que me sean de utilidad para el futuro. Cuento con el conocimiento de diversos lenguajes Python, C++, PHP, C#.|
|Sergio Cesar Aguirre Castillo  <img width="120" height="120" alt="image" src="https://github.com/user-attachments/assets/fec79da1-1e9c-43b4-a5c1-b9b3c79f808c" />|U202310425|Ingeniería de Software|Soy estudiante de la carrera de Ingeniería de Software, actualmente cursando el séptimo ciclo. Tengo un gran interés en adquirir nuevos conocimientos relacionados con mi área que me permitan fortalecer mis habilidades y prepararme para los retos del futuro profesional. Cuento con experiencia en diversos lenguajes de programación como Python, C++, PHP, C#, Java y JavaScript, además de conocimientos en desarrollo web utilizando HTML, CSS y manejo básico de bases de datos como MySQL, lo que me permite adaptarme a distintos entornos de desarrollo y seguir aprendiendo nuevas tecnologías.|
|Anaely Burga Loarte <br><img src="../assets/foto.png" alt="Anaely Burga" width="120" height="120"> |U202118264|Ingeniería de Software|Soy estudiante de la carrera de Ingeniería de Software, con interés en el análisis de usuarios y el diseño de soluciones centradas en el usuario. Durante mi formación he desarrollado habilidades lo que me permite comprender mejor las necesidades del usuario y proponer soluciones innovadoras. Además, cuento con conocimientos en lenguajes de programación y herramientas tecnológicas que complementan mi perfil, permitiéndome adaptarme a distintos entornos de desarrollo y seguir aprendiendo continuamente.|
|Augusto Sebastian Montes Maza<br><img src="../assets/AugustoMontes.png" alt="Augusto Montes" width="120" height="120"> |U202218645|Ingeniería de Software|Estudiante de Ingeniería de Software con una visión global y capacidad de adaptación demostrada en entornos internacionales. Mi formación académica se complementa con una fuerte orientación al trabajo en equipo y la comunicación efectiva, habilidades potenciadas durante mis experiencias de trabajo y estudio. Me especializo en el diseño de soluciones centradas en el usuario y poseo la agilidad técnica necesaria para integrarme a diversos entornos de desarrollo, manteniendo un compromiso constante con el aprendizaje de nuevas tecnologías.|

<br>
<br>

## 1.2 Solution Profile

**Nombre del Producto:** FinTeka

**Descripción del producto:**

FinTeka es una plataforma web orientada a facilitar el acceso a servicios de asesoría profesional especializada, conectando a usuarios con expertos de diversas áreas de manera rápida, segura y eficiente. La propuesta busca centralizar en un solo entorno digital los principales procesos relacionados con la **postulación**, reduciendo la informalidad y mejorando la experiencia del usuario.

La plataforma permite buscar, comparar y seleccionar especialistas de acuerdo con criterios como categoría, experiencia, disponibilidad y valoraciones previas. Asimismo, ofrece herramientas para reservar sesiones, gestionar pagos y realizar seguimiento de las asesorías.

Del mismo modo, FinTeka incorpora funcionalidades que benefician tanto a los usuarios como a los consultores, tales como gestión de agendas en tiempo real, historial de sesiones, canales de comunicación directa y sistemas de reputación basados en calificaciones. En conjunto, estas características contribuyen a fortalecer la confianza, la organización y la calidad del servicio ofrecido.

**Plan Básico**

- Búsqueda de especialistas por categoría, experiencia y valoraciones.
- Visualización de perfiles profesionales con información relevante.
- Reserva de sesiones según disponibilidad.
- Sistema de calificaciones y comentarios.
- Historial básico de asesorías realizadas.
- Notificaciones de confirmación y recordatorios.

**Plan Premium**:

- Posicionamiento destacado del perfil del consultor dentro de la plataforma.
- Gestión avanzada de agenda con disponibilidad en tiempo real.
- Integración de pagos seguros dentro del sistema.
- Historial completo con seguimiento detallado de sesiones.
- Comunicación directa mediante chat entre usuario y consultor.
- Acceso a métricas de desempeño y reputación profesional.
- Herramientas avanzadas para la gestión de servicios.
- Soporte prioritario y atención extendida.

## 1.2.1. Antecedentes y problemática

**Antecedentes:**

En los últimos años, la transformación digital ha modificado la forma en que las personas y organizaciones acceden a diversos servicios, incluyendo aquellos vinculados con la asesoría profesional. El crecimiento del comercio electrónico, las plataformas colaborativas y los servicios remotos ha incrementado la demanda de soluciones digitales orientadas a facilitar la interacción entre proveedores especializados y potenciales clientes.

En el contexto peruano, el acceso progresivo a internet y el mayor uso de dispositivos móviles han favorecido la adopción de herramientas digitales para actividades comerciales, educativas y financieras. Paralelamente, pequeñas empresas, emprendedores y profesionales independientes requieren con mayor frecuencia orientación especializada en áreas como finanzas, derecho, tecnología, marketing y gestión empresarial.

No obstante, una parte importante de estos servicios continúa ofreciéndose mediante canales informales, como redes sociales, mensajería instantánea o recomendaciones personales. Esta situación dificulta la comparación entre alternativas disponibles, reduce la transparencia en precios y experiencia profesional, y limita la confianza entre las partes involucradas.

En ese sentido, surge la necesidad de implementar plataformas digitales que centralicen la oferta de asesoría profesional, optimicen los procesos de contacto y postulación, y brinden mayores garantías de seguridad, organización y calidad en el servicio.

**Problemáticas:**

Actualmente, muchas personas y organizaciones enfrentan dificultades para acceder a asesoría profesional confiable de manera rápida y ordenada. La búsqueda de especialistas suele realizarse a través de medios dispersos, lo que incrementa el tiempo de selección y dificulta la toma de decisiones informadas.

Asimismo, los profesionales independientes no siempre disponen de herramientas tecnológicas que les permitan gestionar adecuadamente su disponibilidad, reservas, pagos y comunicación con clientes. Como consecuencia, se reducen sus posibilidades de crecimiento y formalización dentro del mercado digital.

De igual manera, la ausencia de sistemas integrados para programar sesiones, procesar pagos y registrar valoraciones genera experiencias poco eficientes tanto para usuarios como para consultores. Esto limita la confianza, disminuye la continuidad del servicio y afecta la percepción de calidad.

Frente a esta situación, resulta pertinente el desarrollo de una solución digital que centralice la interacción entre usuarios y especialistas, simplifique los procesos operativos y fortalezca la transparencia en la postulación de servicios profesionales.

**Aplicación de la técnica 5W y 2H:**

A partir del análisis de los antecedentes y la problemática, se aplica la técnica de las 5W y 2H para estructurar la solución propuesta:

**What (Qué)**  
El problema identificado es la inexistencia de una plataforma centralizada que facilite el acceso a asesoría profesional especializada y que permita a los consultores ofrecer sus servicios de manera estructurada.

**When (Cuándo)**  
La necesidad se presenta de forma recurrente, cada vez que personas, emprendedores o empresas requieren orientación para resolver problemas, tomar decisiones o mejorar sus resultados.

**Where (Dónde)**  
La problemática se manifiesta en entornos personales, académicos y empresariales, especialmente en medios digitales donde la oferta de servicios se encuentra fragmentada.

**Who (Quiénes)**  
Los principales involucrados son usuarios que necesitan asesoría confiable y profesionales independientes que buscan captar clientes y gestionar sus servicios de manera eficiente.

**Why (Por qué)**  
La situación se origina por la falta de herramientas integrales que centralicen la búsqueda de especialistas, la reserva de sesiones, los pagos y la evaluación del servicio.

**How (Cómo)**  
FinTeka propone una plataforma web que integra búsqueda de expertos, perfiles profesionales, reservas, pagos seguros, comunicación directa y sistemas de valoración.

**How Much (Cuánto impacto)**  
La solución puede beneficiar a personas naturales, emprendedores, pequeñas empresas y consultores independientes, incrementando la eficiencia en la postulación de asesorías y ampliando el acceso a servicios especializados.

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statement

Actualmente, las personas, emprendedores y empresas que requieren asesoría profesional enfrentan dificultades para identificar especialistas confiables en un mercado altamente fragmentado. Con frecuencia, la búsqueda se realiza mediante recomendaciones informales o redes sociales, donde la información disponible no siempre resulta clara, verificable o suficiente para tomar decisiones adecuadas.

Esta situación genera demoras en la selección del profesional adecuado, escasa transparencia en precios y experiencia, dificultades para coordinar sesiones y limitada seguridad en los procesos de pago. Como consecuencia, la experiencia del usuario suele ser poco eficiente y con altos niveles de incertidumbre.

Por otro lado, los profesionales independientes carecen, en muchos casos, de herramientas digitales que les permitan organizar su disponibilidad, administrar reservas, fortalecer su reputación y ampliar su alcance comercial. Esto restringe sus oportunidades de crecimiento y formalización en entornos digitales.

Frente a esta problemática, FinTeka propone el desarrollo de una plataforma digital orientada a centralizar la relación entre usuarios y consultores, simplificando los procesos de **búsqueda, postulación y seguimiento** del servicio. La propuesta busca validar inicialmente el interés del mercado y, posteriormente, consolidar una solución integral que genere valor para ambas partes.

El principal reto consiste en construir una plataforma que transmita confianza, facilidad de uso, seguridad operativa y calidad en la experiencia ofrecida.

¿Cómo podríamos diseñar una plataforma digital confiable, eficiente e intuitiva que conecte a usuarios con especialistas profesionales, mejorando la experiencia de postulación y generando valor sostenible para clientes y consultores?

#### 1.2.2.2 Lean UX Assumptions

Con el fin de validar la propuesta de valor de FinTeka, se identificaron los principales supuestos relacionados con usuarios, negocio, resultados esperados y funcionalidades clave.

### Business Assumptions

- Existe una demanda creciente por servicios de asesoría profesional postulados mediante canales digitales.
- Los usuarios valoran plataformas que ofrezcan rapidez, seguridad y transparencia durante el proceso de postulación.
- Los consultores independientes están dispuestos a utilizar herramientas digitales para captar clientes y gestionar sus servicios.
- Un modelo basado en comisión por sesión y planes premium resulta viable para monetizar la plataforma.
- Las redes sociales y recomendaciones personales constituyen la principal competencia indirecta.
- Una propuesta especializada permitirá diferenciarse de plataformas genéricas de servicios.
- La generación de confianza inicial será un factor crítico para la adopción temprana del producto.

### User Assumptions

- Los usuarios necesitan encontrar especialistas confiables sin invertir tiempo excesivo en búsquedas informales.
- Las personas comparan experiencia, precio, disponibilidad y valoraciones antes de postular a un servicio.
- Los usuarios prefieren procesos simples de reserva y pago desde un solo entorno digital.
- Los consultores requieren herramientas para administrar agenda, reservas y reputación profesional.
- Tanto clientes como especialistas valoran una comunicación clara y ordenada.
- La facilidad de uso influirá directamente en la permanencia dentro de la plataforma.

### User Outcomes

- Los usuarios tomarán decisiones mejor informadas al contar con perfiles verificables y valoraciones visibles.
- El tiempo necesario para encontrar y contactar asesoría se reducirá significativamente.
- Los clientes percibirán mayor seguridad en pagos y postulación.
- Los consultores incrementarán su visibilidad y acceso a nuevos clientes.
- Ambas partes mejorarán la organización y seguimiento de sesiones programadas.

### Business Outcomes

- Alcanzar una tasa de conversión mínima del 25% de visitantes registrados durante los primeros tres meses.
- Lograr una retención del 60% de usuarios registrados en el primer trimestre.
- Conseguir que al menos el 80% de valoraciones sean positivas.
- Incorporar entre 50 y 100 consultores activos durante los primeros seis meses.
- Establecer entre 3 y 5 alianzas estratégicas iniciales con profesionales o comunidades especializadas.

### Feature Assumptions

- Buscador avanzado con filtros por categoría, precio, experiencia y disponibilidad.
- Perfiles profesionales con experiencia, certificaciones y reseñas.
- Sistema de reservas con calendario integrado.
- Pasarela de pagos segura.
- Historial de sesiones realizadas.
- Dashboard de seguimiento para usuarios.
- Panel administrativo para consultores.
- Sistema de calificaciones y comentarios.
- Notificaciones y recordatorios automáticos.
- Chat entre usuario y consultor.
- Reportes de desempeño para especialistas.
- Opciones premium para destacar perfiles.
- Integración con videollamadas.
- Soporte y atención al cliente.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### Hipótesis 1

Creemos que, si se implementa una plataforma digital que centralice la búsqueda y postulación de especialistas, los usuarios podrán acceder a asesoría profesional de manera más rápida, segura y ordenada. Esto se validará cuando aumente la cantidad de reservas completadas y disminuya el tiempo promedio entre la búsqueda inicial y la contratación del servicio.

- **Business Outcome:** Incremento en la cantidad de sesiones reservadas y en la tasa de conversión de usuarios registrados.  
- **Users:** Personas naturales, emprendedores y pequeñas empresas que requieren asesoría especializada.  
- **User Outcome:** Acceso eficiente a especialistas confiables y mejora en la experiencia de postulación.  
- **Feature:** Buscador por categorías, perfiles profesionales, sistema de reservas y pagos integrados.

##### Hipótesis 2

Creemos que, si se brindan herramientas de gestión para agenda, servicios y clientes dentro de una sola plataforma, los consultores mejorarán su productividad y ampliarán sus oportunidades comerciales. Esto se validará cuando aumente la cantidad de especialistas activos y el promedio de sesiones atendidas por profesional.

- **Business Outcome:** Crecimiento de la red de consultores registrados y mayor actividad dentro de la plataforma.  
- **Users:** Consultores independientes y profesionales especializados.  
- **User Outcome:** Mejor organización operativa, mayor visibilidad y nuevas oportunidades de ingresos.  
- **Feature:** Panel de gestión profesional, calendario de disponibilidad, historial de clientes y métricas de desempeño.

##### Hipótesis 3

Creemos que, si se incorpora un sistema de valoraciones y reseñas verificadas, aumentará la confianza de los usuarios al momento de seleccionar especialistas. Esto se validará cuando mejore la tasa de postulación desde perfiles visitados y aumente la recurrencia de uso.

- **Business Outcome:** Incremento en la conversión de visitas a reservas y mejora en la retención de usuarios.  
- **Users:** Usuarios que buscan asesoría y consultores que ofrecen sus servicios.  
- **User Outcome:** Mayor seguridad al elegir especialistas y fortalecimiento de reputación profesional.  
- **Feature:** Sistema de calificaciones, comentarios verificados y reputación visible en perfiles.

##### Hipótesis 4

Creemos que, si se habilitan canales de comunicación directa y seguimiento posterior a cada sesión, mejorará la continuidad del servicio y la satisfacción general del usuario. Esto se validará cuando aumente la cantidad de sesiones recurrentes con un mismo consultor y las valoraciones positivas posteriores a la atención.

- **Business Outcome:** Mayor tasa de recompra y fortalecimiento de fidelización.  
- **Users:** Usuarios que requieren acompañamiento continuo y especialistas que brindan asesorías periódicas.  
- **User Outcome:** Mejor experiencia de servicio, continuidad en el asesoramiento y relaciones profesionales sostenibles.  
- **Feature:** Chat interno, historial de sesiones, recordatorios y programación de seguimientos.

##### Hipótesis 5

Creemos que, si se ofrecen pagos seguros e integrados dentro de la plataforma, los usuarios percibirán mayor confianza y comodidad al contactar servicios profesionales. Esto se validará cuando disminuya el abandono en el proceso de pago y aumente el porcentaje de transacciones completadas.

- **Business Outcome:** Incremento de ingresos por comisiones y reducción de transacciones inconclusas.  
- **Users:** Usuarios postulantes y consultores afiliados.  
- **User Outcome:** Proceso de pago simple, seguro y confiable.  
- **Feature:** Pasarela de pago integrada, comprobantes automáticos y confirmación inmediata de reservas.

#### 1.2.2.4. Lean UX Canvas

<img src="../assets/UXCanvasF.png" alt="Lean UX Canvas" width="100%">

Tablero Miro: <https://miro.com/app/board/uXjVGhydm8Q=/?share_link_id=941421721219>

**Descripción del Canvas desarrollado:**

- **Business Problem:** dificultad para acceder a asesoría profesional confiable mediante canales digitales organizados.
- **Users and Customers:** personas que requieren asesoría especializada y consultores independientes.
- **User Benefits:** rapidez, confianza, transparencia, acceso a especialistas y facilidad de contacto.
- **Solution Ideas:** buscador de expertos, reservas online, pagos seguros, valoraciones y panel de gestión.
- **Hypotheses:** los usuarios contactarán más asesorías si existe confianza, facilidad de uso y especialistas verificados.
- **Most Important Thing to Learn First:** validar si los usuarios realmente pagarían por asesoría digital en una plataforma centralizada.
- **Least Amount of Work to Learn:** landing page, entrevistas, prototipo navegable y pruebas con usuarios iniciales.
- **Business Outcomes:** crecimiento de usuarios registrados, reservas completadas, retención y satisfacción.

## 1.3. Segmentos objetivo

### Segmento objetivo N.° 1: Personas que requieren asesoría profesional

**Descripción:**  
Este segmento está conformado por personas que necesitan orientación especializada en áreas como finanzas, derecho, tecnología, negocios, empleabilidad o desarrollo personal. Representan la demanda principal de la plataforma, al buscar soluciones confiables que respalden decisiones relevantes en el ámbito personal, académico o laboral.

**Aspectos demográficos:**  
Hombres y mujeres entre 20 y 45 años, pertenecientes principalmente a los niveles socioeconómicos B y C. Incluye estudiantes universitarios, profesionales jóvenes, emprendedores y trabajadores independientes con acceso frecuente a internet.

**Aspectos geográficos:**  
Ubicados principalmente en zonas urbanas del Perú, con mayor concentración en Lima Metropolitana, Arequipa, Trujillo, Chiclayo y otras ciudades con alta adopción digital.

**Aspectos psicográficos:**  
Valoran la eficiencia, la practicidad y el acceso rápido a información confiable. Buscan herramientas que simplifiquen procesos complejos y les permitan tomar decisiones con menor nivel de incertidumbre.

**Necesidades:**  

- Encontrar especialistas confiables según su necesidad.  
- Recibir asesoría personalizada y oportuna.  
- Contar con procesos claros de reserva y pago.  
- Acceder a una experiencia segura y transparente.

**Requisitos:**  

- Plataforma intuitiva y de fácil navegación.  
- Compatibilidad con dispositivos móviles y computadoras.  
- Información clara sobre experiencia, tarifas y disponibilidad.  
- Métodos de pago seguros.

**Objetivo:**  
Resolver necesidades específicas, optimizar tiempo y mejorar la calidad de sus decisiones mediante acceso rápido a conocimiento especializado.

### Segmento objetivo N.° 2: Consultores y profesionales independientes

**Descripción:**  
Este segmento está integrado por profesionales que brindan servicios de asesoría en áreas como derecho, contabilidad, psicología, finanzas, tecnología, marketing, recursos humanos y coaching. Utilizan la plataforma como canal de captación de clientes y herramienta de gestión operativa.

**Aspectos demográficos:**  
Hombres y mujeres entre 25 y 55 años, con formación técnica o universitaria, experiencia laboral previa y orientación al trabajo independiente o complementario.

**Aspectos geográficos:**  
Principalmente ubicados en Lima Metropolitana y capitales de región, aunque también incluye profesionales que prestan servicios remotos desde otras ciudades.

**Aspectos psicográficos:**  
Valoran la autonomía profesional, la generación de ingresos y el uso de tecnología para ampliar oportunidades comerciales. Buscan posicionamiento, eficiencia y crecimiento sostenido.

**Necesidades:**  

- Captar nuevos clientes de forma constante.  
- Gestionar agenda y reservas en un solo entorno.  
- Recibir pagos de manera segura.  
- Construir reputación mediante valoraciones verificadas.

**Requisitos:**  

- Plataforma confiable y profesional.  
- Herramientas de administración simples.  
- Visibilidad del perfil frente a potenciales clientes.  
- Reportes de actividad e ingresos.

**Objetivo:**  
Incrementar ingresos, optimizar la gestión de servicios y ampliar alcance profesional mediante canales digitales.

# Capítulo II: Requirements Elicitation & Analysis

En este capítulo se realizará el proceso de Análisis competitivo y Needfinding necesario para la identificación de las necesidades de nuestro segmento objetivo.

## 2.1. Competidores

### 2.1.1. Análisis Competitivo

# Competitive Analysis Landscape

| **¿Por qué llevar a cabo este análisis?** | ¿Nuestro servicio tiene lo necesario para poder salir adelante ante sus competidores más conocidos? |

|                       | <img src="../assets/FinTeka.png" width="100" height="100"><br>**Nova Asesors** | <img src="../assets/clarityfm.png" width="100" height="100"><br>**Clarity.fm** | <img src="../assets/superpeer.png" width="100" height="100"><br>**Superpeer** | <img src="../assets/maven.jpg" width="100" height="100"><br>**Maven** |
|-----------------------|-----------------------------------------------------------|---------------------------------------------|-------------------------------------------|--------------------------------------|
| **Perfil / Overview** | Plataforma que conecta expertos con usuarios para sesiones 1 a 1, pagos seguros, y perfiles verificados. Áreas: salud, tecnología, negocios y más. | Plataforma para contratar expertos para llamadas 1 a 1. Pago por minuto. Áreas: tecnología, marketing, negocios. | Videollamadas 1 a 1, eventos en vivo, suscripciones. Enfocado en creadores de contenido. | Cursos en vivo con expertos. Enfoque en aprendizaje colaborativo en temas técnicos y profesionales. |
| **Ventaja Competitiva** | Facilidad de uso, verificación rigurosa, pagos seguros, interfaz elegante. Proceso intuitivo para agendar y pagar. | Comunidad de expertos consolidada. Modelo flexible de pago por minuto. Integración con redes como LinkedIn. | Monetización con suscripciones. Fuerte en branding personal y creación de comunidad. | Experiencia de aprendizaje estructurada en cohortes. Foco en formación continua. |
| **Mercado Objetivo** | Personas y empresas que buscan asesoría profesional rápida. Especialmente pymes y usuarios individuales. | Emprendedores, freelancers y startups que buscan asesorías específicas y breves. | Creadores de contenido, coaches y expertos con audiencia propia. | Profesionales, empresas y universidades interesados en educación técnica y profesional. |
| **Estrategias de Marketing** | SEO, marketing en redes sociales, alianzas con universidades y cámaras de comercio. | SEO, contenido dirigido a comunidad emprendedora, campañas en Google y LinkedIn. | Promociones en redes sociales, branding de creadores, creación de comunidad activa. | Webinars, email marketing, alianzas con universidades y expertos reconocidos. |
| **Productos y Servicios** | Asesorías personalizadas, citas agendadas, pagos seguros, historial de sesiones, recomendaciones según preferencias. | Llamadas con expertos, cobro por minuto. Sin necesidad de sesiones largas. | Videollamadas, eventos en vivo, suscripciones mensuales para contenido exclusivo. | Cursos en vivo por cohortes, acceso a materiales y sesiones interactivas. |
| **Precios y Costos** | Comisión por sesión. Planes especiales para expertos frecuentes. Estructura de precios transparente. | Pago por minuto definido por el experto. Puede ser caro para sesiones largas. | Comisión por transacción + suscripciones mensuales opcionales. | Precio por curso (premium). Incluye materiales y acceso a sesiones. |
| **Canales de Distribución** | Web y aplicación móvil. Acceso intuitivo desde cualquier dispositivo. | Principalmente vía web. | Web y app móvil para mayor flexibilidad. | Solo vía web. Experiencia optimizada para aprendizaje. |
| **SWOT - Fortalezas** | Plataforma integral, experiencia fluida, verificación de expertos, interfaz intuitiva. | Comunidad de expertos establecida, pago flexible, integración profesional. | Monetización diversificada, enfoque en comunidad y branding personal. | Educación estructurada, interacción colaborativa, calidad en cohortes. |
| **SWOT - Debilidades** | Sin comunidad consolidada, alta dependencia de SEO/redes, recursos de marketing limitados. | Modelo puede ser costoso en consultas largas. Limitado a llamadas. | Requiere base de seguidores. Difícil para creadores nuevos. | Enfocado solo en educación profesional. Público limitado. |
| **SWOT - Oportunidades** | Alianzas institucionales, expansión a empresas, crecimiento en demanda remota. | Expandir servicios más allá de llamadas. Alta demanda en asesorías rápidas. | Ampliar a más mercados y formatos. Alianzas educativas. | Aumento del interés en educación digital, posibles alianzas. |
| **SWOT - Amenazas** | Competencia consolidada con base leal, marketing agresivo de expertos ya establecidos. | Plataformas como LinkedIn y Upwork. Red más amplia de profesionales. | Competencia con Patreon y otras plataformas de monetización. | Plataformas grandes como Coursera y edX. |
| **¿Tiene lo necesario para competir?** | Sí. Con su enfoque claro en asesorías profesionales, interfaz simple, y verificación rigurosa, Nova Asesors puede posicionarse como una alternativa sólida. Requiere reforzar comunidad y marketing inicial para destacarse. |

### 2.1.2. Estrategias y tácticas frente a competidores

## 1. Aprovechar la Fortaleza: Verificación de Expertos y Asesoría Profesional Personalizada

### Estrategia

Diferenciar la plataforma mediante un sistema de verificación más riguroso de los expertos y la oferta de asesorías personalizadas de alta calidad.

### Tácticas

- **Resaltar la verificación de expertos**:  
  Destacar el proceso de selección y verificación de los profesionales, asegurando que solo los más calificados estén disponibles, diferenciándose de plataformas como Clarity.fm.

- **Promocionar la asesoría personalizada**:  
  Desarrollar campañas de marketing que subrayen las soluciones específicas y adaptadas que ofrece la plataforma, en contraste con ofertas más generales de competidores.

### Valor Añadido

- Generar confianza entre los usuarios.  
- Incrementar la tasa de retención y fidelización.

---

## 2. Aprovechar la Oportunidad: Crecimiento de la Demanda de Asesoría Remota

### Estrategia

Posicionar la plataforma como una solución clave para la asesoría remota, capitalizando el aumento de la demanda post-pandemia.

### Tácticas

- **Campañas educativas sobre asesoría remota**:  
  Crear contenido en redes sociales, blogs y webinars destacando los beneficios de la plataforma.

- **Alianzas con empresas y asociaciones profesionales**:  
  Establecer relaciones estratégicas con colegios profesionales, asociaciones y empresas para ofrecer servicios constantes y generar ingresos adicionales.

- **Incorporar herramientas interactivas de alta calidad**:  
  Implementar funciones como videoconferencias, mensajería en tiempo real y un sistema de pago seguro para garantizar una experiencia eficiente y profesional.

---

## 3. Afrontar la Amenaza de Competidores Consolidados con Base de Usuarios Grandes

### Estrategia

Aplicar un enfoque de marketing centrado en la seguridad, confianza y valor agregado de la plataforma frente a competidores consolidados.

### Tácticas

- **Resaltar la seguridad de la plataforma**:  
  Comunicar que los usuarios contactan servicios seguros y de alta calidad gracias al sistema de verificación de expertos.

- **Modelo freemium para atraer usuarios**:  
  Ofrecer una versión básica gratuita con opción a características premium mediante suscripciones, atrayendo usuarios indecisos de competidores.

- **Segmentación y personalización de servicios**:  
  Ofrecer servicios especializados en sectores como asesoría legal, empresarial y financiera, diferenciándose de competidores más generalistas.

---

## 4. Aprovechar la Debilidad de la Dependencia de Posicionamiento en Buscadores (SEO) y la Visibilidad Inicial

### Estrategia

Implementar estrategias de marketing digital avanzadas para aumentar la visibilidad y atraer usuarios rápidamente.

### Tácticas

- **Marketing de contenido de valor**:  
  Crear artículos, videos y estudios de caso prácticos que resuelvan problemas comunes en la industria de asesoría, atrayendo tráfico orgánico.

- **Publicidad dirigida y marketing en redes sociales**:  
  Desarrollar campañas específicas para profesionales y empresas en sectores clave como tecnología, salud, derecho y negocios.

- **SEO local y alianzas estratégicas**:  
  Optimizar el sitio para búsquedas locales y colaborar con colegios profesionales e instituciones clave para aumentar la visibilidad en nichos específicos.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas Generales**

- ¿Cuál es su nombre?
- ¿Cuántos años tiene usted?
- ¿En qué ciudad y distrito reside? ¿Es un área urbana o rural?
- ¿A qué se dedica profesionalmente y qué tipo de asesoría está buscando?

**Preguntas Específicas**

##### 1. Personas Naturales (Usuarios en búsqueda de asesoría profesional)

**Preguntas principales:**

- Imagina que pudieras pedirle consejo a un experto en cualquier área de tu vida profesional, ¿qué área elegirías y qué te gustaría lograr con ese consejo?

- Si tuvieras que escoger entre una asesoría puntual para resolver un problema específico o un acompañamiento continuo a largo plazo, ¿cuál elegirías y por qué?

- Cuando necesitas encontrar un experto para una asesoría, ¿te sientes más cómodo buscando opiniones de otros usuarios (reseñas, recomendaciones) o prefieres confiar en las credenciales profesionales del asesor? ¿Por qué?

- Si pudieras personalizar una plataforma de asesoría profesional (como la facilidad de navegación, opciones de pago, o comunicación), ¿qué características tendría para que te sintieras cómodo usándola?

- En tus propias palabras, ¿cómo describirías la “experiencia ideal” al recibir asesoría online? ¿Qué elementos no pueden faltar en la plataforma o en la interacción con el asesor?

- ¿Qué tipo de indicadores o resultados específicos considerarías para determinar si una asesoría fue efectiva y valió la pena?

- En cuanto a la relación con tu asesor, ¿prefieres que sea más formal y profesional, o buscas una relación más cercana y personal, como la de un mentor?

- En una escala del 1 al 10, ¿qué tan importante es para ti que la plataforma te brinde recomendaciones sobre qué expertos son los más adecuados para tu consulta, siendo 1 nada importante y 10 extremadamente importante?

- Si tuvieras que elegir entre una plataforma con muchas funciones tecnológicas avanzadas o una más sencilla de usar pero con menos funcionalidades, ¿cuál preferirías? ¿Por qué?

- Piensa en la última vez que buscaste un experto para resolver un problema profesional o personal. ¿Qué te molestó más del proceso y qué características o mejoras te habrían facilitado la búsqueda de ese experto?

##### 2. Consultores y Profesionales (Proveedores de asesoría)

**Preguntas principales:**

- Si pudieras organizar tu negocio de asesoría de la manera más eficiente posible, ¿qué herramientas o procesos específicos usarías para atraer clientes y organizar las sesiones de manera efectiva?

- ¿Qué tipo de información sobre el cliente necesitas tener antes de la sesión para ofrecer el mejor servicio posible?

- ¿Qué te hace sentir más cómodo en una plataforma que gestiona tu agenda y pagos? ¿Prefieres una interfaz sencilla que solo cumpla con lo esencial o herramientas avanzadas que te permitan personalizar tu negocio de manera flexible?

- Si pudieras optimizar el proceso de pagos a través de una plataforma, ¿qué funcionalidades específicas te harían la vida más fácil (pago por sesión, suscripciones, facturación automática, etc.)?

- Cuando piensas en promocionar tus servicios de asesoría, ¿qué tipo de marketing digital te gustaría que la plataforma ofreciera para atraer nuevos clientes?

- Si un cliente te solicitara una consulta urgente, ¿qué tan fácil sería para ti gestionar y responder esa solicitud a través de una plataforma digital?

- Imagina que puedes organizar eventos grupales en tu especialidad (por ejemplo, seminarios o masterclasses). ¿Cómo te gustaría que la plataforma te ayudara a crear estos eventos?

- Si tuvieras que presentar una propuesta de asesoría a un nuevo cliente en línea, ¿qué elementos visuales o interactivos serían importantes para ti incluir en esa presentación?

- ¿¿Cómo prefieres que la plataforma te ayude a gestionar las interacciones posteriores a la asesoría, como el seguimiento con los clientes o la retroalimentación?

- Imagina que puedes ofrecer descuentos o promociones especiales a tus clientes a través de la plataforma. ¿Qué tipo de ofertas te gustaría ofrecer y cómo te gustaría gestionarlas?

### 2.2.2. Registro de entrevistas

- Segmento 1: Personas Naturales
- Entrevista 1:
- Nombre: Sara Giovanna Qwistgaard Horna
- Edad: 53
- Distrito: San Miguel
  
<img src="https://github.com/user-attachments/assets/0e0c9687-49cf-4163-bb94-7e8062090cac">

**Link: <https://acortar.link/RWaCr0>**

En la entrevista, la señora Sara Qwistgaard menciona que busca asesoría en el área de marketing. Además, nos cuenta cómo le gustaría su página de asesoría ideal y su mayor problema con las asesorías en general: los horarios.

- Entrevista 2:
- Nombre: Orlando Romero Flores
- Edad: 59
- Distrito: San Miguel
  
<img src="https://github.com/user-attachments/assets/10ba027c-e24e-43aa-9cb2-c8bb14c064be">

**Link: <https://acortar.link/WrhkQL>**

El entrevistado Orlando Romero, quien busca asesoría para administración de equipos de redes, nos relata cómo le gustaría que fuera su experiencia con asesorías online y con la plataforma en general, además de explicar cómo debería funcionar el foco principal de la plataforma.

- Entrevista 3:
- Nombre: Ingrid Noelia Zabala Lasso
- Edad: 33
- Distrito: San Miguel

<img src="https://github.com/user-attachments/assets/47c6166f-b129-4886-aabc-7f1110e1e900">

**Link: Link: <https://acortar.link/WyeuS7>**

La entrevistada busca asesoría en el área de defensoría médica para el tema legal de las prácticas médicas, y a partir de la entrevista nos da su punto de vista sobre lo indispensable de una asesoría en línea y cuál es el mayor problema que se tiene con los asesores en general.

- Segmento 2: Consultores y Profesionales
- Entrevista 1:
- Nombre: Augusto Montes
- Edad: 20
- Distrito: Jesus Maria
  
<img src="https://github.com/user-attachments/assets/95e8c874-a899-4e98-82f4-31870a74b1bb">

**Link: <https://acortar.link/NfWGsQ>**

La entrevista con Augusto Montes muestra que, para optimizar su negocio de asesoría profesional, busca una plataforma que combine la generación de leads cualificados con una agenda automatizada, lo que permitiría una reserva sin fricciones y recordatorios automáticos. Prefiere una interfaz equilibrada entre simplicidad y personalización, que permita etiquetar clientes, editar notas privadas y realizar integraciones con otras aplicaciones. En cuanto a pagos, valora la flexibilidad de contar con diferentes modalidades como pago por sesión, suscripciones recurrentes, facturación automática y pagos multimoneda para facilitar transacciones globales. Además, considera importante un sistema de marketing digital basado en referidos para atraer nuevos clientes. Para gestionar solicitudes urgentes, le gustaría contar con una opción de disponibilidad inmediata y la posibilidad de cobrar tarifas premium por consultas urgentes. También está interesado en organizar eventos grupales como seminarios o masterclasses, lo que podría generar más interacción y demanda para sus servicios.

- Entrevista 2:
- Nombre: Maria Fernanda Castillo Espinoza
- Edad: 22
- Distrito: Los olivos
  
<img src="https://github.com/user-attachments/assets/6b1b0eb2-35c1-4dbe-a263-fee7b6745f79">

**Link:  <https://acortar.link/TErjgY>**

La entrevista con María Fernanda Castillo destaca sus necesidades para optimizar su negocio de asesoría profesional. Busca una plataforma automatizada que permita a los clientes encontrar su perfil, ver disponibilidad en tiempo real y agendar directamente. Para ofrecer el mejor servicio, necesita conocer el tema que el cliente desea tratar, sus objetivos, si ha tenido asesorías previas y cualquier material relevante. Prefiere una interfaz sencilla, pero con opciones de personalización si es necesario. En cuanto al proceso de pagos, valora opciones como pago por sesión, suscripciones mensuales y facturación automática, con la prioridad de que los pagos se depositen rápidamente en su cuenta. Además, le gustaría que la plataforma ofreciera herramientas de marketing digital, como publicidad segmentada, posicionamiento en buscadores, creación de contenido y analítica de rendimiento. Para consultas urgentes, necesita una plataforma que permita ver y gestionar solicitudes en tiempo real, aceptar o reagendar desde su celular y recibir notificaciones eficientes. También está interesada en organizar eventos grupales como seminarios o masterclasses.

- Entrevista 3:
- Nombre: Julio Castro Alejos
- Edad: 24
- Distrito: Pueblo libre
  
<img src="https://github.com/user-attachments/assets/301f2480-1a5e-4671-bbed-48b7ab80f0fb">

**Link: <https://acortar.link/EQVuW5>**

Julio Castro busca una plataforma para gestionar eficientemente su negocio de asesorías. Identifica la necesidad de filtros que faciliten encontrar clientes adecuados y organizar sesiones con datos claros como fechas, duración y métodos de pago. Prefiere una interfaz sencilla pero con opciones avanzadas para personalizar su experiencia. Valora funcionalidades como pagos por sesión y suscripciones, además de integración con herramientas de marketing como Facebook Ads y YouTube. También destaca la utilidad de notificaciones para evitar conflictos de agenda y opciones para crear y gestionar eventos como seminarios. Finalmente, menciona la importancia de incluir elementos visuales como videos y portafolios para presentar propuestas a nuevos clientes.

### 2.2.3. Análisis de entrevistas

| Nombre                            | Preferencias y Recomendaciones |
|----------------------------------|--------------------------------|
| Sara Giovanna Qwistgaard Horna   | Prefiere basarse en el currículum y recomendaciones específicas de los asesores. Sugiere incluir recursos didácticos (artículos, fotos), asesorías más personales, rápidas y puntuales, y una plataforma sencilla de usar. Se queja de la falta de funcionalidad de búsqueda, que retrasó una cita. |
| Orlando Romero Flores             | Confía más en el currículum del asesor. Propone un sistema de recomendaciones personalizadas y recursos interactivos. Busca mayor formalidad profesional y mejor coordinación de horarios con el asesor, pues tuvo problemas de sincronización en su experiencia anterior. |
| Ingrid Noelia Zabala Lasso       | Da prioridad al currículum del asesor. Valora recursos como artículos, fotos e interactividad, además de una plataforma personalizada y fácil de usar. Experimentó dificultades para localizar al asesor, lo que generó desconfianza. |
| Augusto Montes                   | Requiere automatización para generar clientes cualificados y gestionar la agenda. Desea información detallada del cliente antes de la sesión. Interesado en funciones como pagos por sesión, suscripciones, facturación automática, y herramientas de marketing digital. |
| María Fernanda Castillo Espinoza | Busca una plataforma que facilite la generación de clientes y gestión de sesiones. Valora sistemas de pagos y suscripciones, además de herramientas para organizar eventos (seminarios, masterclasses) y realizar campañas segmentadas para promocionar sus servicios. |
| Julio Castro Alejos              | Desea gestión eficiente del negocio de asesoría, incluyendo organización de sesiones, promoción a través de redes sociales y YouTube, y una agenda flexible. Interesado en materiales visuales e interactivos para mejorar el atractivo de sus servicios. |

## 2.3. Needfinding

En esta sección se presenta el proceso de análisis de la información recolectada a partir de entrevistas y observación de usuarios potenciales. El objetivo es identificar necesidades, comportamientos, motivaciones y principales puntos de dolor, con el fin de sustentar el diseño de la solución.

Como resultado del proceso de needfinding, se desarrollan y presentan los siguientes artefactos de análisis:

- **User Personas:** representación de los perfiles de usuarios clave identificados, describiendo sus características, objetivos, necesidades y frustraciones.
- **User Task Matrix:** matriz que permite priorizar y analizar las tareas más relevantes que los usuarios realizan dentro del contexto del problema.
- **User Journey Maps:** mapeo de la experiencia del usuario a lo largo de su interacción con el servicio, identificando puntos de contacto, emociones y oportunidades de mejora.
- **Empathy Mapping:** herramienta que permite profundizar en lo que el usuario piensa, siente, dice y hace, facilitando una comprensión más humana de sus necesidades.
- **As-Is Scenario Mapping:** análisis del escenario actual del usuario antes de la solución, permitiendo identificar problemas, ineficiencias y oportunidades de innovación.

Este conjunto de artefactos permite construir una visión clara y estructurada del usuario, sirviendo como base fundamental para el diseño de la solución propuesta.

### 2.3.1. User Personas

A continuación, se presentan las fichas de **User Personas** elaboradas a partir del análisis de las entrevistas realizadas. Estas representaciones sintetizan los principales perfiles de usuarios identificados, sus necesidades, objetivos, motivaciones y principales puntos de dolor dentro del contexto de la solución.

---

#### Segmento #1: Solicitante de Servicios

![User Persona 1](https://raw.githubusercontent.com/1ASI0657-7943-2610/report/feature/chapter-02/assets/userpersona1.png)

Este perfil representa a los usuarios que buscan contactar servicios de asesoría o apoyo profesional de manera rápida, confiable y personalizada. Generalmente, son personas que valoran la eficiencia, la facilidad de uso de la plataforma y la seguridad al momento de seleccionar a un experto.

Sus principales necesidades se centran en encontrar profesionales calificados, reducir el tiempo de búsqueda y contar con una experiencia de servicio clara y sin fricciones. Entre sus principales frustraciones destacan la falta de confianza en plataformas poco verificadas y la dificultad para identificar expertos realmente confiables.

---

#### Segmento #2: Proveedores de Servicios

![User Persona 2](https://raw.githubusercontent.com/1ASI0657-7943-2610/report/feature/chapter-02/assets/userpersona2.png)

Este perfil corresponde a profesionales o expertos que ofrecen sus servicios dentro de la plataforma. Su principal objetivo es monetizar su conocimiento, ampliar su alcance y conectar con clientes potenciales de forma eficiente.

Entre sus necesidades destacan contar con una plataforma que les brinde visibilidad, un sistema de pagos seguro y herramientas que faciliten la gestión de sus servicios. Sus principales frustraciones incluyen la baja visibilidad en plataformas saturadas, la competencia elevada y la dificultad para captar clientes de calidad.

---

Estos dos segmentos permiten comprender de manera clara las dos partes fundamentales del ecosistema de la plataforma, facilitando el diseño de una solución equilibrada tanto para usuarios solicitantes como para proveedores de servicios.
  
### 2.3.2. User Task Matrix

A continuación se muestra el proceso para la realizacion del User Task Matrix para comprender las tareas que realizan los User Persona para cumplir sus objetivos.

**Segmento #1: Solicitante de Servicios**

| Tarea                         | Frecuencia    | Importancia      |
|-------------------------------|----------------|----------------|
| Buscar profesionales | Alta   | Alta   |
| Crear y configurar su perfil | Media   | Alta    |
| Realizar pagos por el servicio | Alta    | ALta   |
| Calificar al profesional | Media   | Media   |
| Coordinar fechas o entregas | Media  | Media  |
| Consultar opiniones o reseñas | Alta  | Alta  |

**Segmento #2: Proveedores de Servicios**

| Tarea                         | Frecuencia    | Importancia      |
|-------------------------------|----------------|----------------|
| Crear y configurar su perfil | Alta   | Alta   |
| Publicar servicios y actualizar info | Alta  | Alta    |
| Responder mensajes y consultas | Alta    | ALta   |
| Recibir pagos | Media   | Media   |
| Promocionar su perfil | Media  | Media  |
| Gestionar disponibilidad de horarios | Alta  | Alta  |

### 2.3.3. User Journey Mapping

A continuación se muestra el proceso para la realización del User Journey Mapping para los User Persona con el fin de entender las experiencias del usuario sin nuestra solución.

**Segmento #1: Solicitante de Servicios**

<img src="../assets/uxpressia1.png" width="900" height="600">

**Segmento #2: Proveedores de Servicios**

<img src="../assets/uxpressia2.png" width="900" height="600">

### 2.3.4. Empathy Mapping

A continuación se muestra el proceso para la realización del Empathy Mapping para los User Persona con el fin de entender lo que piensa, siente, oye, hace y observa.

**Segmento #1: Solicitante de Servicios**

<img src="../assets/empathy4.png" width="1400" height="600">

Link del Empathy Mapping: <https://docs.google.com/drawings/d/1ldThwGvffPsPR6Ea6FWCU5DBOGQAVvXugWDPmzPzgD8/edit?usp=sharing>

**Segmento #2: Proveedores de Servicios**

<img src="../assets/empathy.png" width="1400" height="600">

Link del Empathy Mapping: <https://docs.google.com/drawings/d/1iiU7QqJ-yt0utAPLlAPtQgQrVaNgFb6AWoq7JaNGiV0/edit>

### 2.3.5. As-is Scenario Mapping

A continuación se muestra el proceso para la realización del As-Is Scenario Mapping para los User Persona.

**Segmento #1: Solicitante de Servicios**

<img src="../assets/asis1.png" width="1400" height="600">

**Segmento #2: Proveedores de Servicios**

<img src="../assets/asis2.png" width="1400" height="600">

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

A continuación se presenta la realizacion del To-Be Scenario Mapping por cada user persona.

**Segmento #1: Solicitante de Servicios**

<img width="987" height="387" alt="image" src="https://github.com/user-attachments/assets/28606eac-975e-4424-b686-3a0b86625e71" />

**Segmento #2: Proveedores de Servicios**

<img width="980" height="370" alt="image" src="https://github.com/user-attachments/assets/76e71f62-eef6-4953-8e64-bc38dd8ffb6c" />

## 3.2 Requisitos funcionales y no funcionales

### 3.2.1 Requisitos Funcionales

**Leyenda de prefijos:**

- **CRRF** = *Core Reservation & Real-time Features*: funciones núcleo relacionadas con reservas, sesiones, mensajería en tiempo real y operación principal del servicio.  
- **CRF** = *Core Requirements Features*: funciones generales del negocio orientadas a usuarios y consultores.  
- **IRF** = *Identity Requirements Features*: funciones de identidad, autenticación, seguridad y control de acceso.  
- **PRF** = *Profile Requirements Features*: funciones relacionadas con perfiles, reputación y métricas de consultores.  
- **RF** = *Reporting / Resource Features*: funciones complementarias como publicaciones, reportes y moderación administrativa.  

| ID        | Descripción |
|-----------|-------------|
| CRRF-001  | El sistema debe verificar la disponibilidad de los consultores en tiempo real, validando que no existan conflictos de horario al momento de realizar una reserva. El intervalo solicitado no debe superponerse con otras sesiones confirmadas. En caso de conflicto, el sistema debe rechazar la reserva y sugerir horarios alternativos disponibles. |
| CRRF-002  | El sistema debe procesar las reservas mediante un flujo transaccional que incluya validación de disponibilidad, confirmación de datos y bloqueo temporal del horario seleccionado. Si el proceso no se completa dentro del tiempo establecido, el horario debe liberarse automáticamente. |
| CRRF-003  | El sistema debe permitir la reprogramación de sesiones conservando el historial de cambios realizados, incluyendo fecha original, nueva fecha y usuario responsable del cambio. |
| CRRF-004  | El sistema debe gestionar la comunicación en tiempo real entre usuarios y consultores mediante mensajería instantánea, garantizando envío, recepción y almacenamiento de mensajes. |
| CRRF-005  | El sistema debe registrar el historial completo de mensajes asociados a cada sesión, incluyendo emisor, receptor, fecha, hora y contenido. |
| CRRF-006  | El sistema debe calcular automáticamente la calificación promedio de cada consultor a partir de las valoraciones recibidas y actualizarla inmediatamente después de cada nueva reseña. |
| CRRF-007  | El sistema debe priorizar la visibilidad de consultores con plan premium en los resultados de búsqueda mediante reglas de ordenamiento por suscripción activa, relevancia y reputación. |
| CRRF-008  | El sistema debe gestionar el ciclo de vida de una sesión mediante estados: pendiente, confirmada, en curso, completada y cancelada. Toda transición debe quedar registrada para auditoría. |
| CRRF-009  | El sistema debe enviar recordatorios automáticos al usuario y consultor antes del inicio de cada sesión programada. |
| CRRF-010  | El sistema debe registrar trazabilidad completa sobre reservas, cancelaciones, reprogramaciones y cambios de estado de sesiones. |
| CRRF-011 | El sistema debe permitir que los consultores carguen documentos, títulos, certificaciones y evidencias profesionales en su perfil, para que los usuarios interesados evalúen directamente su experiencia y capacidad antes de contactar una asesoría. |
| CRF-001   | El sistema debe permitir al usuario buscar especialistas por categoría, experiencia, tarifa y calificación. |
| CRF-002   | El sistema debe actualizar dinámicamente los resultados cuando el usuario aplique filtros de búsqueda. |
| CRF-003   | El sistema debe permitir visualizar el perfil detallado de un consultor. Si no existe, debe mostrarse un mensaje adecuado. |
| CRF-004   | El sistema debe permitir al usuario cancelar una sesión programada conforme a las políticas definidas por la plataforma. |
| CRF-005   | El sistema debe permitir al usuario consultar sus sesiones programadas mostrando fecha, hora, estado y consultor asociado. |
| CRF-006   | El sistema debe permitir al usuario consultar el historial de asesorías realizadas. |
| CRF-007   | El sistema debe permitir al usuario calificar una sesión únicamente si se encuentra en estado completada, incluyendo puntuación y comentario opcional. |
| CRF-008   | El sistema debe permitir al usuario visualizar el detalle de una sesión específica con información completa del consultor y estado actual. |
| CRF-009   | El sistema debe permitir al consultor definir, modificar y eliminar su disponibilidad horaria sin generar conflictos con sesiones ya reservadas. |
| CRF-010   | El sistema debe permitir al consultor consultar sus sesiones agendadas mostrando usuario, fecha, hora y estado. |
| CRF-011   | El sistema debe permitir consultar la lista general de especialistas mostrando nombre, especialidad, calificación promedio y tarifa por sesión. |
| CRF-012   | El sistema debe permitir ordenar especialistas por precio, experiencia, calificación o disponibilidad. |
| CRF-013   | El sistema debe permitir gestionar categorías de especialización utilizadas en búsquedas y filtros. |
| CRF-014 | El sistema debe permitir a los usuarios visualizar documentos, certificaciones y antecedentes profesionales compartidos voluntariamente por el consultor dentro de su perfil público. |
| IRF-001   | El sistema debe permitir el registro de nuevos usuarios mediante correo electrónico, contraseña y nombre de usuario. |
| IRF-002   | El correo electrónico debe ser único, válido, no exceder 255 caracteres y almacenarse en minúsculas. |
| IRF-003   | La contraseña debe tener entre 8 y 128 caracteres e incluir al menos una letra minúscula y un dígito. |
| IRF-004   | El sistema debe permitir autenticación mediante correo electrónico y contraseña validando credenciales mediante comparación segura de hash. |
| IRF-005   | El sistema debe generar un token de acceso y un token de actualización al iniciar sesión correctamente. |
| IRF-006   | El sistema debe validar la vigencia, integridad y origen de los tokens utilizados en solicitudes protegidas. |
| IRF-007   | El sistema debe permitir al usuario autenticado consultar su información básica y roles asignados. |
| IRF-008   | El sistema debe permitir modificar contraseña y nombre de usuario previa validación de identidad. |
| IRF-009   | El sistema debe permitir recuperación de contraseña mediante correo electrónico verificado. |
| IRF-010   | El sistema debe implementar roles de usuario, consultor y administrador con permisos diferenciados. |
| PRF-001   | El sistema debe permitir la creación de perfiles asociados a cuentas registradas. |
| PRF-002   | El perfil debe incluir nombre, apellido e imagen opcional. |
| PRF-003   | Para consultores, el sistema debe habilitar campos de especialidades, descripción profesional, experiencia y tarifa por sesión. |
| PRF-004   | El sistema debe permitir consultar perfiles por identificador único. |
| PRF-005   | El sistema debe permitir a los consultores actualizar su perfil profesional y reflejar cambios inmediatamente. |
| PRF-006   | El sistema debe permitir visualizar valoraciones y comentarios públicos en el perfil del consultor. |
| PRF-007   | El sistema debe permitir consultar historial de asesorías tanto para usuarios como consultores según permisos. |
| PRF-008   | El sistema debe permitir a consultores visualizar métricas de desempeño como sesiones completadas, tasa de finalización, ingresos generados y reputación promedio. |
| RF-001    | El sistema debe permitir al consultor crear publicaciones informativas en su perfil indicando título, descripción y categoría. |
| RF-002    | El sistema debe permitir modificar publicaciones existentes registrando fecha de actualización. |
| RF-003    | El sistema debe permitir eliminar publicaciones y retirar su visibilidad pública. |
| RF-004    | El sistema debe permitir adjuntar imágenes o documentos a publicaciones respetando límites definidos por la plataforma. |
| RF-005    | El sistema debe permitir al usuario visualizar publicaciones del consultor ordenadas cronológicamente. |
| RF-006    | El sistema debe permitir al usuario acceder al detalle completo de una publicación con archivos adjuntos. |
| RF-007    | El sistema debe permitir enviar consultas relacionadas a una publicación o servicio ofrecido por el consultor. |
| RF-008    | El sistema debe permitir al administrador revisar reportes realizados por usuarios sobre contenido o comportamiento indebido. |
| RF-009    | El sistema debe permitir al administrador resolver reportes aplicando acciones correctivas. |
| RF-010    | El sistema debe permitir suspender temporal o permanentemente cuentas que incumplan políticas de uso. |
| RF-011    | El sistema debe permitir la visibilidad los documentos y certificados validados por la empresa dentro del perfil del consultor, garantizando transparencia. |

### 3.2.2 Requisitos no Funcionales

| ID | Descripción |
|----|-------------|
| RNF-001 | El sistema debe responder búsquedas de especialistas en un tiempo máximo de **2 segundos** para el 95% de solicitudes bajo una carga normal de hasta 150 usuarios concurrentes. |
| RNF-002 | El sistema debe procesar la creación y confirmación de reservas en un tiempo máximo de **3 segundos** para el 95% de transacciones. |
| RNF-003 | Toda comunicación entre cliente y servidor debe realizarse mediante **HTTPS con TLS 1.2 o superior**. |
| RNF-004 | Las contraseñas de los usuarios deben almacenarse utilizando algoritmos seguros como **BCrypt** con factor de costo mínimo de 10. |
| RNF-005 | El sistema debe validar el 100% de entradas del usuario y rechazar datos inválidos con respuestas **HTTP 400** en menos de 200 ms. |
| RNF-006 | La API REST debe documentarse mediante **OpenAPI 3.0 / Swagger**, cubriendo el 100% de endpoints públicos y privados. |
| RNF-007 | El sistema debe manejar errores devolviendo códigos HTTP adecuados (**200, 201, 400, 401, 403, 404, 500**) en el 100% de solicitudes procesadas. |
| RNF-008 | Las entidades principales del sistema deben utilizar identificadores **UUID versión 4** para garantizar unicidad global. |
| RNF-009 | Los parámetros críticos del sistema (credenciales, claves, tokens, conexiones) deben configurarse mediante **variables de entorno**. |
| RNF-010 | Los perfiles públicos de consultores deben cargar en un tiempo máximo de **1.5 segundos** para el 95% de solicitudes bajo carga normal. |
| RNF-011 | El sistema debe implementar control de acceso basado en roles (**RBAC**), validando permisos en cada solicitud protegida con una latencia menor a **50 ms**. |
| RNF-012 | El sistema debe registrar logs de autenticación, reservas, errores y operaciones críticas con niveles **INFO, WARN y ERROR**, conservando la información por un mínimo de **90 días**. |
| RNF-013 | El sistema debe ser compatible con despliegues en **Docker**, utilizando imágenes optimizadas cuyo tamaño no exceda los **500 MB**. |
| RNF-014 | La interfaz web debe ser compatible con las versiones vigentes de **Google Chrome, Mozilla Firefox, Microsoft Edge y Safari**. |
| RNF-015 | El sistema debe contar con diseño **responsive**, compatible con dispositivos móviles, tabletas y escritorio en resoluciones desde **360 px hasta 1920 px**. |
| RNF-016 | El sistema debe expirar sesiones inactivas de usuario luego de **30 minutos** sin actividad autenticada. |
| RNF-017 | El sistema debe bloquear automáticamente una cuenta luego de **5 intentos fallidos consecutivos** de inicio de sesión durante un periodo de **15 minutos**. |
| RNF-018 | El sistema debe permitir recuperación de contraseña mediante correo electrónico verificado con enlace temporal de validez máxima de **15 minutos**. |

### 3.3 User Stories

En esta sección se presentan los requisitos funcionales definidos para Finteka. Las User Stories permiten comprender las necesidades de los usuarios finales, priorizar funcionalidades y organizar el desarrollo incremental del sistema. Asimismo, cada historia incluye criterios de aceptación que validan su cumplimiento.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :---- | :---- | :---- | :---- | :---- |
| EP01 | Registro de usuarios | Implementar el registro de los usuarios para tanto los asesores como los clientes |  |  |
| US001 | Registrar un profesional | Como profesional. Quiero poder registrarme fácilmente en la plataforma como consultor. Para ofrecer mis servicios, gestionar mis horarios y comenzar a brindar asesoría a personas o empresas interesadas. | **Escenario 01: Registro exitoso.** Dado que soy un profesional interesado en ofrecer mis servicios, Cuando completo correctamente el formulario de registro con mis datos y lo envío, Entonces el sistema guarda la información, envía una notificación de recepción y muestra un mensaje indicando que el perfil será revisado.<br>**Escenario 02: Fallo en el registro.** Dado que soy un profesional que intenta registrarse, Cuando dejo campos obligatorios vacíos o ingreso datos inválidos, Entonces el sistema muestra mensajes de error y no permite enviar el formulario hasta corregir los datos. | EP01 |
| US002 | Registrar un cliente | Como usuario que busca asesoría profesional. Quiero poder registrarme fácilmente en la plataforma como cliente. Para acceder al listado de consultores disponibles, agendar sesiones y recibir asesoría especializada. | **Escenario 01: Registro exitoso.** Dado que soy un nuevo cliente que desea registrarse, Cuando completo correctamente el formulario de registro con mis datos, Entonces el sistema crea mi cuenta, me muestra un mensaje de bienvenida y me redirige al panel de usuario o inicio. <br>**Escenario 02: Registro con errores o campos incompletos.** Dado que intento registrarme con un correo ya registrado, Cuando ingreso el correo electrónico y lo envío, Entonces el sistema me notifica que ya existe una cuenta con ese correo y me sugiere iniciar sesión o recuperar la contraseña. | EP01 |
| EP02 | Búsqueda de servicios | Poder buscar asesorías y recibir ayuda para realizarla |  |  |
| US003 | Buscar profesionales disponibles | Como usuario. Quiero poder buscar y filtrar profesionales disponibles según mi necesidad. Para encontrar al experto más adecuado y reservar una sesión fácilmente. | **Escenario 01: Filtros por disponibilidad.** Dado que estoy buscando un profesional. Cuando aplico un filtro por fecha y hora. Entonces el sistema me muestra solo aquellos consultores que tienen horarios disponibles en ese rango. <br>**Escenario 02: Visualización de perfil profesional.** Dado que encontré un profesional que me interesa. Cuando hago clic en su perfil. Entonces puedo ver su información completa, experiencia, calificaciones, disponibilidad y tarifas. | EP02 |
| US004 | Recibir notificaciones de disponibilidad de profesionales | Como usuario. Quiero recibir notificaciones cuando un profesional que sigo esté disponible para sesiones. Para poder agendar una sesión cuando el profesional esté libre. | **Escenario 01: Notificación de disponibilidad.** Dado que estoy siguiendo a un profesional, Cuando el profesional actualiza su disponibilidad, Entonces recibo una notificación en mi correo o aplicación con los nuevos horarios disponibles.<br>**Escenario 02: Notificación para programar sesión.** Dado que recibo una notificación de disponibilidad, Cuando hago clic en la notificación, Entonces soy redirigido a la plataforma para poder agendar mi sesión con el profesional. | EP02 |
| US005 | Filtrar experto por tarifa | Como usuario quiero filtrar expertos por tarifa para ajustar mi búsqueda a mi presupuesto. | **Escenario 01: Filtro aplicado de manera exitosa.** Dado que elijo el rango de tarifa deseado. Cuando doy clic en Aplicar filtro. Entonces la plataforma me muestra la lista de expertos cuya tarifa se encuentra en el rango elegido. <br>**Escenario 02: El rango seleccionado no es válido.** Dado que ingreso valores inválidos de rango de tarifa. Cuando quiero aplicar el filtro. Entonces la plataforma muestra un mensaje de error sobre los valores de rango ingresados. | EP02 |
| EP03 | Gestión de Perfiles | Configurar e interactuar con los perfiles |  |  |
| US006 | Ver detalles del profesional | Como usuario. Quiero poder ver el perfil completo de un profesional. Para conocer su experiencia, especialidades, disponibilidad, tarifas y calificaciones antes de tomar una decisión. | **Escenario 01: Visualización de experiencia y especialidades.** Dado que estoy viendo el perfil de un consultor, Cuando navego por la sección de descripción profesional, Entonces puedo leer su formación, experiencia laboral y áreas de especialización. <br>**Escenario 02: Visualización de disponibilidad y tarifas.** Dado que estoy en el perfil de un profesional, Cuando reviso su disponibilidad, Entonces puedo ver los horarios libres para agendar una sesión y el costo por cada servicio. | EP03 |
| US007 | Calificar a un profesional | Como usuario. Quiero poder calificar y dejar un comentario sobre el profesional. Para compartir mi experiencia con otros usuarios y contribuir a la reputación del consultor. | **Escenario 01: Acceso a la opción de calificación tras una sesión completada.** Dado que he completado una sesión con un profesional, Cuando accedo al perfil del profesional, Entonces el sistema me muestra la opción de calificar al consultor correspondiente. <br>**Escenario 02: Envío de calificación y comentario.** Dado que tengo disponible la opción de calificación, Cuando selecciono una puntuación y escribo un comentario, Entonces el sistema guarda la calificación y la muestra públicamente en el perfil del profesional. | EP03 |
| US008 | Actualizar perfil de usuario | Como usuario. Quiero poder actualizar mi perfil en la plataforma. Para mantener mi información personal, preferencias y detalles de contacto actualizados. | **Escenario 01: Actualización exitosa del perfil.** Dado que soy un usuario que desea actualizar mi perfil, Cuando cambio mis datos personales, como el correo o número de teléfono y hago clic en "guardar", Entonces el sistema actualiza mi perfil y me muestra un mensaje de confirmación. <br>**Escenario 02: Error en la actualización del perfil.** Dado que soy un usuario que intenta actualizar mi perfil, Cuando ingreso datos inválidos, como un correo incorrecto, Entonces el sistema muestra un mensaje de error y me indica qué campo debe corregirse. | EP03 |
| US009 | Guardar profesionales como favoritos | Como usuario, quiero poder guardar profesionales como favoritos, para acceder fácilmente a sus perfiles en futuras búsquedas sin tener que encontrarlos nuevamente. | **Escenario 01: Agregar profesional a favoritos.** Dado que estoy viendo el perfil de un consultor, Cuando hago clic en el ícono de “favorito”, Entonces el profesional se añade a mi lista de favoritos y recibo una confirmación. <br>**Escenario 02: Visualización de lista de favoritos.** Dado que he marcado varios profesionales como favoritos, Cuando accedo a la sección “Favoritos” desde mi perfil, Entonces puedo ver una lista con sus nombres, especialidades y accesos directos a sus perfiles. <br>**Escenario 03: Eliminar profesional de favoritos.** Dado que ya no quiero mantener a un profesional en mi lista, Cuando hago clic en el ícono de “eliminar de favoritos”, Entonces este desaparece de mi lista y el sistema me muestra un mensaje de confirmación. | EP03 |
| US010 | Crear y gestionar servicios de profesional | Como profesional quiero crear y gestionar mis servicios para ofrecer distintos tipos de asesoría. | **Escenario 01: Agregar servicio nuevo.** Dado que quiero agregar un servicio nuevo para ofrecer asesoría. Cuando hago clic en Agregar servicio y selecciono la categoría. Entonces, la plataforma muestra un mensaje de servicio agregado de manera satisfactoria. <br>**Escenario 02: Eliminar servicio.** Dado que quiero eliminar un servicio que ya no deseo ofrecer. Cuando selecciono el servicio y hago clic en Eliminar servicio. Entonces, la plataforma muestra un mensaje de servicio eliminado de manera satisfactoria. | EP03 |
| US011 | Responder mensajes de clientes | Como profesional, quiero ver y responder los mensajes de los clientes para mantener buena comunicación. | **Escenario 01: Mensaje enviado de manera exitosa.** Dado que quiero comunicarme con un cliente. Cuando selecciono al cliente y selecciono en Enviar mensaje. Entonces, la plataforma muestra una confirmación de que el mensaje ha sido enviado. | EP03 |
| EP04 | Gestión de Sesiones y Seguimiento | Optimizar la experiencia de los usuarios y consultores antes, durante y después de las sesiones. |  |  |
| US012 | Realizar reserva de sesión | Como usuario. Quiero poder reservar una sesión con un profesional. Para asegurarme de contar con su tiempo disponible para recibir asesoría. | **Escenario 01: Reserva exitosa.** Dado que soy un usuario que desea agendar una sesión. Cuando selecciono un profesional, fecha y hora disponible. Entonces el sistema confirma la reserva y me envía una notificación. <br>**Escenario 02: Fallo en la reserva.** Dado que intento reservar un horario que ya no está disponible. Cuando elijo esa fecha y hora. Entonces el sistema muestra un mensaje de error y me sugiere otros horarios disponibles. | EP04 |
| US013 | Agendar seguimiento post-sesión | Como usuario, quiero poder agendar una sesión de seguimiento con el mismo consultor, para continuar con el proceso de asesoría. | **Escenario 01: Agendamiento desde historial.** Dado que he finalizado una sesión con un consultor, Cuando accedo al historial y selecciono “Agendar seguimiento”, Entonces puedo elegir fecha y hora y confirmar la nueva sesión. <br>**Escenario 02: Confirmación automática.** Dado que seleccioné un horario disponible, Cuando envío la solicitud de seguimiento, Entonces el sistema envía una notificación al consultor y confirma la cita. | EP04 |
| US014 | Tomar notas durante la sesión | Como consultor, quiero tener una sección para tomar notas durante la sesión, para guardar observaciones relevantes del cliente. | **Escenario 01: Acceso al bloc de notas.** Dado que estoy en una sesión activa, Cuando accedo al bloc de notas desde mi panel, Entonces puedo escribir y guardar comentarios privados. <br>**Escenario 02: Guardado automático.** Dado que estoy escribiendo notas durante la sesión, Cuando cierro el panel de notas, Entonces el sistema guarda automáticamente el contenido. | EP04 |
| US015 | Enviar recomendaciones tras sesión | Como consultor, quiero poder enviar al usuario una lista de recomendaciones o materiales luego de la sesión, para complementar la asesoría. | **Escenario 01: Envío de materiales.** Dado que terminé una sesión con un cliente, Cuando selecciono la opción “Enviar recomendaciones”, Entonces puedo adjuntar archivos o escribir sugerencias y enviarlas. <br>**Escenario 02: Visualización por el usuario.** Dado que el consultor me envió recomendaciones, Cuando abro la sesión desde el historial, Entonces puedo ver los materiales recibidos. | EP04 |
| US016 | Ver historial de sesiones | Como usuario. Quiero poder ver un historial de mis sesiones pasadas. Para poder revisar la información de las sesiones anteriores y hacer un seguimiento de mi progreso. | **Escenario 01: Visualización del historial de sesiones.** Dado que soy un usuario que ha tenido sesiones anteriores, Cuando accedo a la sección de historial de sesiones, Entonces puedo ver la lista de todas las sesiones pasadas, con fecha, profesional y detalles. <br>**Escenario 02: Visualización de detalles de una sesión.** Dado que estoy viendo el historial de mis sesiones, Cuando hago clic en una sesión específica, Entonces puedo ver los detalles completos, incluyendo notas o recomendaciones proporcionadas por el profesional. | EP04 |
| US017 | Calificar seguimiento de sesión | Como usuario, quiero poder calificar las sesiones de seguimiento por separado, para evaluar la mejora continua del servicio recibido. | **Escenario 01: Opción disponible tras sesión de seguimiento.** Dado que acabo de completar una sesión de seguimiento, Cuando reviso el historial de esa sesión, Entonces veo la opción de dejar una calificación específica para ella. <br>**Escenario 02: Publicación del comentario.** Dado que escribí una calificación y comentario, Cuando hago clic en “Enviar”, Entonces el sistema guarda y publica la valoración en el perfil del consultor.  | EP04 |
| US018 | Cancelar reserva de sesión | Como usuario. Quiero poder cancelar una reserva de sesión. Para poder modificar mis planes si surge un imprevisto. | <br>**Escenario 01: Cancelación exitosa.** Dado que tengo una sesión programada y deseo cancelarla, Cuando accedo a la opción de cancelación en mi perfil y confirmó la cancelación, Entonces el sistema cancela la sesión y me envía una notificación confirmando la cancelación. <br>**Escenario 02: Error al intentar cancelar.** Dado que intento cancelar una sesión programada en un horario muy cercano, Cuando intento cancelarla, Entonces el sistema muestra un mensaje de advertencia o bloqueo de la opción de cancelación. | EP04 |
| US019 | Notificaciones sobre estado de reserva | Como usuario quiero recibir notificaciones sobre el estado de mi reserva para estar informado en todo momento. | **Escenario 01: Notificación de recordatorio de sesión programada.** Dado que realicé una reserva con un profesional. Cuando hago clic en la notificación. Entonces recibo un detalle sobre la sesión programada junto al día y hora exacta. <br>**Escenario 02: Notificación sobre cancelación de sesión.** Dado que recibo una notificación de cancelación de sesión. Cuando hago clic en la notificación. Entonces soy redirigido a la plataforma para reagendar la sesión con el profesional. | EP04 |
| US20 | Pago en línea seguro al reservar una sesión de asesoría | Como cliente que necesita asesoría profesional quiero poder pagar en línea de forma segura al momento de reservar una sesión para asegurar mi cita con el consultor y evitar complicaciones en el proceso. | **Escenario 01: Pago exitoso.** Dado que el pago se ha procesado correctamente. Cuando la transacción se completa. Entonces el sistema debe mostrar un mensaje de confirmación y actualizar el estado de la reserva como “Confirmada”. <br>**Escenario 02: Fallo en el pago.** Dado que la transacción falla por cualquier motivo. Cuando el sistema detecta el error. Entonces muestra un mensaje al usuario de seleccionar otro método de pago. | EP04 |
| EP05 | Marketing y Crecimiento Profesional | Aumentar la visibilidad de los consultores y facilitar la adquisición de nuevos clientes. |  |  |
| US021 | Publicar testimonios destacados | Como consultor, quiero mostrar testimonios positivos de mis clientes en mi perfil, para generar mayor confianza en nuevos usuarios. | **Escenario 01: Selección de testimonios.** Dado que tengo varias calificaciones positivas, Cuando marco una como “destacada”, Entonces aparece resaltada en la parte superior de mi perfil. <br>**Escenario 02: Eliminación de un testimonio destacado.** Dado que quiero cambiar un testimonio, Cuando desmarco el actual, Entonces este ya no se muestra como destacado en mi perfil. | EP05 |
| US022 | Crear campañas promocionales | Como consultor, quiero poder crear promociones temporales (descuentos o asesorías grupales), para atraer más clientes. | **Escenario 01: Creación de descuento.** Dado que quiero lanzar una promoción, Cuando configuro una campaña con nombre, fecha y porcentaje de descuento, Entonces la promoción queda activa y visible en mi perfil. <br>**Escenario 02: Finalización automática de la campaña.** Dado que la campaña ya terminó, Cuando se alcanza la fecha de fin, Entonces la promoción se desactiva automáticamente. | EP05 |
| US023 | Ver estadísticas de perfil | Como consultor, quiero ver métricas sobre cuántas personas vieron mi perfil, reservaron sesiones o dejaron calificaciones, para medir mi rendimiento. | **Escenario 01: Visualización de métricas básicas.** Dado que accedo a la sección de estadísticas, Cuando ingreso a mi panel de consultor, Entonces puedo ver visitas al perfil, reservas y calificaciones recientes. <br>**Escenario 02: Filtros por fecha.** Dado que quiero analizar mi rendimiento, Cuando selecciono un rango de fechas, Entonces el sistema me muestra los datos correspondientes al período elegido. | EP05 |
| US024 | Gestionar campañas de referidos | Como consultor, quiero invitar a otros consultores o clientes a la plataforma mediante un sistema de referidos, para obtener beneficios por cada nuevo registro. | **Escenario 01: Generación de enlace de referido.** Dado que quiero invitar a nuevos usuarios, Cuando accedo a la sección de referidos, Entonces el sistema genera un enlace único para compartir. <br>**Escenario 02: Registro exitoso de un referido.** Dado que alguien se registra usando mi enlace, Cuando completa el registro, Entonces recibo una notificación y posibles recompensas por el referido. | EP05 |
| US025 | Optimizar visibilidad en buscador | Como consultor, quiero personalizar palabras clave para aparecer más fácilmente en los resultados de búsqueda dentro de la plataforma. | **Escenario 01: Edición de palabras clave del perfil.** Dado que deseo mejorar mi visibilidad, Cuando edito mi perfil y agrego palabras clave relevantes, Entonces mi perfil se ajusta a los criterios del buscador interno. <br>**Escenario 02: Aumento de visibilidad tras actualización.** Dado que añadí nuevas palabras clave, Cuando un usuario busca términos relacionados, Entonces mi perfil aparece mejor posicionado en los resultados. | EP05 |
| US026 | Ver Preguntas Frecuentes (FAQ) | Como usuario, quiero tener una sección de preguntas frecuentes, para poder resolver mis dudas rápidas sobre cómo usar la plataforma sin necesidad de contactar a soporte. | **Escenario 01: Visualización de respuestas.** Dado que tengo dudas sobre la plataforma, Cuando accedo a la sección "Ayuda", Entonces veo una lista de preguntas y al tocar una, se despliega la respuesta hacia abajo. | EP06 |
| US027 | Enviar sugerencia o reporte rápido | Como usuario, quiero tener un formulario simple de contacto, para poder enviar sugerencias de mejora o reportar algún error visual en la aplicación. | **Escenario 01: Envío exitoso.** Dado que quiero enviar un comentario, Cuando lleno el campo de texto y presiono "Enviar", Entonces la pantalla se limpia y la aplicación me muestra un mensaje emergente agradeciendo mi comentario. | EP06 |
| US028 | Compartir perfil del profesional | Como usuario, quiero poder compartir el perfil de un consultor, para poder recomendar sus servicios a mis amigos o colegas enviándoles un enlace. | **Escenario 01: Copiar enlace.** Dado que estoy viendo un perfil interesante, Cuando presiono el ícono de "Compartir", Entonces el sistema copia el enlace del perfil al portapapeles y me muestra un aviso de "Enlace copiado". | EP03 |
| US029 | Cambiar tema (Modo Oscuro / Claro) | Como usuario, quiero poder alternar entre un tema visual claro y oscuro, para adaptar la aplicación a mis preferencias visuales o a la iluminación del entorno. | **Escenario 01: Cambio a modo oscuro.** Dado que la aplicación está en modo claro, Cuando presiono el interruptor de cambio de tema en mi perfil, Entonces los colores de la interfaz cambian inmediatamente a una paleta oscura. | EP03 |

## 3.4. Impact Mapping

Impact map de nuestros segmentos objetivos:

<img width="1040" height="786" alt="image" src="https://github.com/user-attachments/assets/38070dbf-a433-4111-b885-decd80f64564" />

Link del Impact Mapping:<https://miro.com/app/board/uXjVJGsSlMY=/?share_link_id=357440759397>

## 3.5. Product Backlog

Utilizamos la escala de Fibonacci para la estimación de los Story Points.

| # Orden | User Story Id | Título | Descripción | Story Points |
| :--- | :--- | :--- | :--- | :--- |
| 01 | **US001** | Registro de profesionales | Como experto, deseo registrarme en la plataforma para ofrecer mis servicios y gestionar mi perfil profesional. | 3 |
| 02 | **US002** | Registro de clientes | Como usuario interesado, deseo crear una cuenta para buscar expertos y gestionar mis reservas. | 2 |
| 03 | **US003** | Búsqueda de profesionales disponibles | Como usuario interesado, deseo buscar todos los profesionales disponibles. | 2 |
| 04 | **US026** | Filtros de búsqueda de expertos | Como cliente, deseo filtrar consultores por especialidad y calificación para encontrar al asesor ideal rápidamente. | 5 |
| 05 | **US004** | Notificaciones de disponibilidad de profesionales | Como usuario interesado, deseo recibir notificaciones de disponibilidad del profesional. | 2 |
| 06 | **US005** | Filtros de expertos por tarifa | Como usuario quiero filtrar expertos por tarifa para ajustar mi búsqueda a mi presupuesto. | 5 |
| 07 | **US006** | Visualización de perfil profesional | Como cliente, deseo consultar la experiencia y formación del profesional para validar su capacidad técnica. | 2 |
| 08 | **US007** | Calificación de sesiones | Como cliente, deseo calificar y comentar el servicio recibido para ayudar a otros usuarios en su elección. | 3 |
| 09 | **US028** | Perfiles recomendados | Como administrador, deseo destacar perfiles profesionales para aumentar su visibilidad ante nuevos clientes. | 2 |
| 10 | **US008** | Actualización de perfil | Como usuario, deseo editar mi información personal y de contacto para mantener mi cuenta actualizada. | 2 |
| 11 | **US009** | Favoritos de profesionales | Como cliente, deseo guardar consultores en mi lista de favoritos para acceder a ellos rápidamente en el futuro. | 3 |
| 12 | **US010** | Gestión de disponibilidad | Como consultor, deseo configurar mi agenda de disponibilidad para que los clientes puedan agendar sin conflictos. | 8 |
| 13 | **US011** | Gestión de mensajes | Como consultor, quiero ver y responder los mensajes de los clientes para mantener buena comunicación. | 5 |
| 14 | **US012** | Agendamiento de sesiones | Como cliente, deseo seleccionar un horario y agendar una sesión para asegurar mi consultoría técnica. | 5 |
| 15 | **US013** | Seguimiento post-sesión | Como consultor, deseo registrar notas y tareas pendientes para dar un seguimiento adecuado al progreso del cliente. | 3 |
| 16 | **US014** | Apunte de notas de texto| Como consultor, quiero tener una sección para tomar notas durante la sesión, para guardar observaciones relevantes del cliente. | 2 |
| 17 | **US015** | Enviar recomendaciones tras sesión| Como consultor, quiero poder enviar al usuario una lista de recomendaciones o materiales luego de la sesión, para complementar la asesoría. | 3 |
| 18 | **US016** | Visualizar historial de sesiones| Como usuario. Quiero poder ver un historial de mis sesiones pasadas. Para poder revisar la información de las sesiones anteriores. | 5 |
| 19 | **US017** | Calificar seguimiento de sesión| Como usuario, quiero poder calificar las sesiones de seguimiento por separado, para evaluar la mejora continua del servicio recibido. | 5 |
| 20 | **US018** | Cancelar reserva de sesión| Como usuario. Quiero poder cancelar una reserva de sesión. Para poder modificar mis planes si surge un imprevisto. | 3 |
| 21 | **US027** | Confirmación de sesiones | Como consultor, deseo aceptar o rechazar solicitudes de sesiones para organizar mejor mi tiempo laboral. | 3 |
| 22 | **US019** | Notificaciones de alertas | Como usuario, deseo recibir notificaciones de disponibilidad y recordatorios para no perder mis sesiones programadas. | 3 |
| 23 | **US020** | Pago en línea seguro | Como cliente, deseo realizar el pago mediante la plataforma para confirmar mi reserva de manera automática. | 8 |
| 24 | **US021** | Publicar testimonios destacados | Como consultor, quiero mostrar testimonios positivos de mis clientes en mi perfil, para generar mayor confianza en nuevos usuarios. | 3 |
| 25 | **US022** | Crear campañas promocionales | Como consultor, quiero poder crear promociones temporales, para atraer más clientes. | 3 |
| 26 | **US023** | Ver estadísticas de perfil | Como consultor, quiero ver métricas sobre cuántas personas vieron mi perfil, reservaron sesiones o dejaron calificaciones, para medir mi rendimiento. | 5 |
| 27 | **US024** | Gestionar campañas de referidos | Como consultor, quiero invitar a otros consultores o clientes a la plataforma mediante un sistema de referidos, para obtener beneficios por cada nuevo registro. | 3 |
| 28 | **US025** | Optimizar visibilidad en buscador | Como consultor, quiero personalizar palabras clave para aparecer más fácilmente en los resultados de búsqueda dentro de la plataforma. | 3 |
| 29 | **US029** | SEO y Meta-datos | Como administrador, deseo configurar URLs amigables y metadatos para mejorar el posicionamiento de los expertos en buscadores. | 3 |

<div style="page-break-after: always;"></div>

# Capítulo IV: Product Architecture Design

## 4.1

## 4.1.1

## 4.1.2

## 4.1.3 Context Diagram

El System Context Diagram corresponde al primer nivel del modelo C4 y permite visualizar el sistema desde una perspectiva general. Su propósito es mostrar cómo FinTeka se relaciona con los principales actores externos y con los sistemas complementarios necesarios para su funcionamiento.

En este contexto, FinTeka se presenta como una plataforma digital orientada a conectar clientes con profesionales, facilitando procesos como búsqueda de especialistas, reservas de sesiones, pagos seguros y videollamadas.

En este Context Diagram se muestra a FinTeka como el sistema central que interactúa con los principales usuarios y servicios externos necesarios para su operación.

<img src="../assets/contextdiagram.jpg" style="width: 100%;" alt="diagramacontexto">

**Link del diagrama:** <https://online.visual-paradigm.com/share.jsp?id=343537383331342d32>

## 4.1.4 Approach driven ViewPoints Diagrams

#### Usuarios

El sistema admite los roles de Cliente y Profesional. El profesional gestiona su perfil, disponibilidad y servicios para atender la demanda, mientras que el cliente dispone de herramientas para buscar y reservar especialistas según sus necesidades.

#### Aplicación web

Espacio donde los usuarios interactúan con la plataforma, buscan profesionales, reservan sesiones, realizan pagos y gestionan citas. Los profesionales administran sus servicios, horarios y consultas recibidas.

#### API Rest

Actúa como puente hacia los servicios de backend para la obtención y despliegue de datos solicitados.

#### Bases de datos

Los servicios que requieren almacenamiento registran y consultan información relacionada con usuarios, reservas, pagos, calificaciones y disponibilidad en su base de datos correspondiente.

#### Servicios externos

Para brindar funcionalidades complementarias se integran servicios externos como PayPal para pagos seguros, Google Calendar para sincronización de citas, Zoom para reuniones virtuales y Gmail para registro y notificaciones por correo.

#### Microservicios

- Gestión de usuarios y perfiles: Encargado del registro, autenticación, roles y administración de perfiles de clientes y profesionales.
- Gestión de reservas: Responsable de la creación, modificación y cancelación de citas entre clientes y profesionales.
- Búsqueda y recomendación: Permite localizar profesionales según categoría, especialidad, calificación o disponibilidad.
- Calificaciones y reseñas: Administra opiniones y valoraciones luego de cada servicio realizado.

#### Microservicios de soporte

- Pagos: Encargado de comunicar y validar pagos realizados mediante PayPal.
- Notificaciones: Envía alertas sobre reservas, recordatorios, pagos confirmados o cambios de cita mediante correo o push notifications.
- Integración de calendario: Sincroniza eventos y recordatorios con Google Calendar.
- Videollamadas: Genera enlaces de reunión mediante Zoom para sesiones remotas.

<img src="../assets/containerdiagram.jpg" style="width: 100%;" alt="diagramacontenedores">

### Search and Recommendation - Diagrama de Componentes

A continuación, se muestra el diagrama de componentes correspondiente al microservicio Search and Recommendation. Su función principal es facilitar la localización de profesionales disponibles y sugerir opciones relevantes en la plataforma Finteka.

<img src="../assets/componentdiagram1.jpg" style="width: 100%;" alt="diagramacomponentes1">

### Session Management - Diagrama de Componentes

A continuación, se presenta el diagrama de componentes del microservicio Session Management. Su función es gestionar las citas entre usuarios y profesionales, enviando confirmaciones por correo e integrando canales de comunicación como Zoom y chat en tiempo real.

<img src="../assets/componentdiagram4.jpg" style="width: 100%;" alt="diagramacomponentes4">

### Reservation Management

A continuación, se presenta el diagrama de componentes del microservicio Reservation Management. Su función es administrar las reservas de asesorías dentro de Finteka, permitiendo registrar, consultar y actualizar las solicitudes realizadas por los usuarios.

<img src="../assets/componentdiagram3.jpg" style="width: 100%;" alt="diagramacomponentes3">

### Ratings and Reviews

A continuación, se presenta el diagrama de componentes del microservicio Ratings and Reviews. Su función es gestionar las valoraciones y comentarios realizados por los usuarios sobre las asesorías recibidas y los profesionales dentro de la plataforma Finteka.

<img src="../assets/componentdiagram2.jpg" style="width: 100%;" alt="diagramacomponentes2">

**Link de los diagramas:** <https://online.visual-paradigm.com/share.jsp?id=343537383331342d32>

## 4.1.5

## 4.1.6

## 4.1.7

# Conclusiones

- La investigación inicial permitió identificar que muchas personas y empresas presentan dificultades para acceder a asesoría profesional confiable debido a la fragmentación de la oferta y al uso de canales informales.
- El análisis del contexto digital evidenció una oportunidad de negocio relacionada con el crecimiento del uso de plataformas tecnológicas para contactar con servicios profesionales especializados.
- FinTeka se plantea como una solución viable al centralizar procesos como búsqueda de especialistas, reservas, pagos seguros, comunicación directa y reputación profesional en un solo entorno digital.
- La definición clara de segmentos objetivo permitió reconocer dos actores principales del ecosistema: usuarios que buscan asesoría y consultores que desean captar clientes y gestionar sus servicios.
- La aplicación de Lean UX facilitó validar supuestos de negocio, identificar riesgos tempranos y orientar el desarrollo hacia funcionalidades de mayor valor para el mercado.
- El proceso de Needfinding permitió comprender necesidades reales, motivaciones, comportamientos y puntos de dolor mediante herramientas centradas en el usuario.
- Los artefactos desarrollados, como User Personas, User Journey Mapping, Empathy Mapping y Scenario Mapping, contribuyeron a diseñar una experiencia alineada con las expectativas de los usuarios.
- El análisis competitivo demostró que existen plataformas internacionales posicionadas, pero también oportunidades de diferenciación para una propuesta enfocada en el mercado peruano y latinoamericano.
- La especificación de requisitos funcionales, no funcionales, historias de usuario e impact mapping proporciona una base sólida para el desarrollo técnico y la planificación del producto.
- FinTeka posee potencial de crecimiento sostenible gracias al avance de la digitalización, el aumento del trabajo remoto y la creciente demanda por asesorías profesionales en línea.

---

# Recomendaciones

- Validar continuamente la propuesta de valor mediante entrevistas, encuestas y pruebas con usuarios reales durante las primeras etapas del proyecto.
- Desarrollar un Producto Mínimo Viable (MVP) enfocado en funciones esenciales como registro, búsqueda de especialistas, reservas y sistema de valoraciones.
- Diseñar la plataforma considerando una experiencia intuitiva, rápida y adaptable tanto para usuarios como para consultores.
- Mantener actualizados los perfiles profesionales con información clara sobre experiencia, tarifas, disponibilidad y reputación.
- Aplicar metodologías centradas en el usuario de forma continua para detectar mejoras en navegación, procesos y satisfacción general.
- Implementar estrategias competitivas de diferenciación basadas en confianza, verificación de expertos y enfoque especializado en mercados locales.
- Establecer una arquitectura técnica robusta que contemple seguridad, rendimiento, disponibilidad y escalabilidad desde el inicio.
- Priorizar el desarrollo de requisitos críticos como autenticación segura, pagos integrados, reservas en tiempo real y mensajería interna.
- Gestionar el Product Backlog con metodologías ágiles, priorizando funcionalidades según valor de negocio y retroalimentación de usuarios.
- Planificar una estrategia de expansión progresiva, iniciando en el mercado peruano y escalando posteriormente hacia otros países de Latinoamérica.

# Referencias Bibliográficas

Chaffey, D., & Ellis-Chadwick, F. (2019). *Digital marketing* (7th ed.). Pearson.

Instituto Nacional de Estadística e Informática. (2024). *Estadísticas de las tecnologías de información y comunicación en los hogares*. INEI. <https://www.inei.gob.pe/>

Laudon, K. C., & Traver, C. G. (2023). *E-commerce: Business, technology, society* (18th ed.). Pearson.

Lean Startup Co. (2023). *Lean UX principles and agile product development*. <https://leanstartup.co/>

Ministerio de Transportes y Comunicaciones. (2023). *Reporte nacional de conectividad digital en el Perú*. Gobierno del Perú. <https://www.gob.pe/mtc>

Nielsen, J., & Budiu, R. (2013). *Mobile usability*. New Riders.

Organización para la Cooperación y el Desarrollo Económicos. (2023). *Digital economy outlook 2023*. OECD Publishing. <https://www.oecd.org/>

Osterwalder, A., Pigneur, Y., Bernarda, G., & Smith, A. (2020). *Value proposition design: How to create products and services customers want*. Wiley.

Ries, E. (2011). *The lean startup: How today’s entrepreneurs use continuous innovation to create radically successful businesses*. Crown Business.

Statista. (2024). *E-commerce and digital services market in Latin America*. <https://www.statista.com/>

World Bank. (2023). *Digital development overview*. The World Bank. <https://www.worldbank.org/>

# Anexos

# Capítulo I: Introducción

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
- **Necesidad de Solución Integral B2B:** Creemos que las empresas de infraestructura y minería, junto con sus proveedores, necesitan urgentemente un software de Field Service Management que integre telemetría IoT, control financiero y logística en tiempo real.
- **Plataforma Web y Móvil Accesible:** Creemos que el valor se entregará a través de un portal web corporativo (Cockpit) para los gerentes y, a futuro, una aplicación móvil offline-first para los choferes en zonas sin cobertura.
- **Clientes Iniciales:** Nuestros clientes iniciales serán empresas del sector minero, telecomunicaciones y construcción (ej. Minera Yanacocha, Gilat Peru) y grandes distribuidores de hidrocarburos.
- **Valor Principal:** El valor #1 que buscan los clientes es la garantía de abastecimiento sin sobregiros presupuestales, y para los proveedores, la prevención de robos y la aceleración de la facturación mediante guías digitales.
- **Modelo de Ingresos:** Generaremos ingresos mediante un modelo SaaS Multitenant B2B, cobrando suscripciones por volumen de transacciones o licencias de flota a las empresas distribuidoras.
- **Competencia y Diferenciación:** Nos diferenciamos de simples e-commerce o ERPs tradicionales al integrar hardware (sensores IoT) con software transaccional, creando un ecosistema inmutable y en tiempo real.

**User Assumptions**
- **Quién es el Usuario:** Gerentes de logística, jefes de operaciones en campo y controladores de flota / despachadores de empresas mayoristas.
- **Dónde Encaja el Producto:** FuelTrack se convierte en la herramienta central de operaciones diarias en las oficinas de logística y en los centros de control de monitoreo vehicular.
- **Problemas del Producto:** Existe el riesgo de resistencia al cambio tecnológico por parte de los choferes de cisternas. Se mitigará mediante interfaces de divulgación progresiva extremadamente simples y capacitaciones.

**User Outcomes**
- **Para el Cliente Corporativo (Demanda):** Visibilidad financiera total, prevención de desabastecimiento mediante pedidos ágiles (Wizard) y auditoría perfecta de cada galón consumido.
- **Para el Proveedor (Oferta):** Control telemétrico absoluto sobre sus cisternas, reducción drástica de robos en ruta y automatización de la recolección de firmas digitales para facturar más rápido.

**Business Outcomes**
- **Eficiencia Operativa:** Reducción sustancial del Lead Time (tiempo desde aprobación hasta entrega) y cumplimiento riguroso de los Acuerdos de Nivel de Servicio (SLA).
- **Posicionamiento en el Mercado:** Convertir a FuelTrack en el estándar de gestión de hidrocarburos B2B en operaciones críticas y zonas remotas.

**Features Importantes:**
- Wizard de Pedidos Inteligente (con cálculos de precios indexados).
- Dashboard de Inteligencia Operativa (Burn Rate, Centros de Costo).
- Monitor IoT Telemétrico (Integración con sensores DUT-E CAN, motor, batería).
- Radar y Alertas (Bloqueo remoto y detección de robos).
- Exportación de Vouchers Legales en PDF con firma digital.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que** al implementar un "Wizard de Pedidos Inteligente" que automatice el cálculo financiero frente a líneas de crédito, los gerentes de logística realizarán sus requerimientos de manera más segura y rápida. **Sabremos que hemos tenido éxito cuando** el tiempo promedio para colocar y aprobar una orden de combustible se reduzca en un 60% frente a los métodos tradicionales (correos/WhatsApp).
- **Creemos que** al proveer un "Monitor IoT" con telemetría en vivo y alertas de caída brusca de presión a los controladores de flota, los proveedores podrán detectar y reaccionar ante posibles robos o fugas al instante. **Sabremos que hemos tenido éxito cuando** los reportes de mermas inexplicables o pérdidas de combustible en ruta disminuyan en un 90%.
- **Creemos que** al incluir un "Dashboard de Inteligencia Operativa" que cruce el volumen despachado con el presupuesto mensual (Burn Rate) por centro de costo, los clientes corporativos tendrán un mejor control financiero. **Sabremos que hemos tenido éxito cuando** los incidentes de sobregiros presupuestales por abastecimiento de energía se reduzcan a cero.
- **Creemos que** al digitalizar el proceso de entrega y generar un "Voucher Legal PDF" como evidencia transaccional e inmutable, los proveedores de combustible cerrarán sus ciclos logísticos de forma más limpia. **Sabremos que hemos tenido éxito cuando** el tiempo de validación para proceder con la facturación al cliente pase de días a minutos.

#### 1.2.2.4. Lean UX Canvas

*(A continuación se presenta el Lean UX Canvas que resume la estrategia y validación del modelo de negocio de FuelTrack).*

![Lean UX Canvas FuelTrack](../docs/lean-ux-canvas.png)

---

## 1.3. Segmentos objetivo

**1. El Cliente Corporativo (Demanda)**

- **Descripción General:** Empresas con operaciones críticas, pesadas o en zonas remotas que dependen del suministro continuo de hidrocarburos para mantener su productividad (minería, telecomunicaciones, infraestructura y construcción).
- **Características Demográficas y Profesionales:**
  - **Rol / Puesto:** Gerentes de Logística, Jefes de Operaciones, Supervisores de Campamento o Nodos.
  - **Edad:** Profesionales entre 35 y 55 años, con alta responsabilidad sobre la continuidad operativa.
  - **Género:** Mayoritariamente masculino en campo, aunque cada vez más equitativo en áreas gerenciales logísticas.
  - **Ubicación:** Oficinas corporativas en zonas urbanas (Lima) con constante comunicación hacia campamentos o nodos rurales/remotos (ej. Amazonas, zonas mineras).
- **Información Estadística de Sustento:**
  - **Impacto Operativo:** Según estudios de logística industrial, las paradas no planificadas por falta de energía pueden costar a empresas extractivas o de infraestructura decenas de miles de dólares por hora.
  - **Control de Presupuesto:** Más del 60% de los gerentes logísticos afirman tener dificultades para auditar el consumo exacto de combustible frente a lo presupuestado debido a la fragmentación de la información en papel.

**2. El Proveedor / Distribuidor (Oferta)**

- **Descripción General:** Empresas mayoristas dedicadas a la comercialización y transporte de hidrocarburos que poseen flotas de cisternas especializadas y buscan asegurar la integridad de su carga hasta el destino final.
- **Características Demográficas y Profesionales:**
  - **Rol / Puesto:** Controladores de Flota (Centro de Monitoreo), Despachadores, Gerentes Comerciales.
  - **Edad:** Entre 28 y 50 años.
  - **Nivel Técnico:** Alto uso de monitores de rastreo GPS, manejo de turnos y coordinación constante con choferes de ruta pesada.
  - **Ubicación:** Bases de operaciones logísticas, plantas de refinería o distribución en zonas industriales.
- **Información Estadística de Sustento:**
  - **Mermas y Robos:** El robo de combustible en tránsito (conocido coloquialmente como "ordeño") representa pérdidas anuales de millones de dólares para las empresas de transporte en Latinoamérica.
  - **Transformación Digital en Flotas:** Se estima que la integración de telemetría y sistemas de gestión de flotas (FMS) mejora la eficiencia de despachos y reduce tiempos de inactividad operativa hasta en un 25%, justificando la necesidad de un monitor IoT dedicado como el de FuelTrack.

# Capítulo II: Requirements Elicitation & Analysis

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

### 2.1.2. Estrategias y tácticas frente a competidores

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
- ¿Cuál es su cargo y qué responsabilidad tiene sobre el suministro energético?
- ¿Qué edad tiene y cuál es su nivel de experiencia en el sector?
- ¿Qué herramientas digitales (ERPs, Excel, Apps móviles) utiliza con mayor frecuencia en su jornada laboral?

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
- ¿Cuál es su rol dentro de la estructura logística de la empresa?
- ¿Qué edad tiene y qué nivel de estudios posee?
- ¿Qué sistemas de rastreo GPS o gestión de flotas (FMS) utilizan actualmente?
- ¿Cómo describiría la apertura de su organización hacia la digitalización y el uso de hardware IoT?

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

*Imagen (N°2). Elaboración propia. Realizado en UXPressia*

**Segmento 2: El Proveedor / Distribuidor (Oferta)**

<img src="../assets/User_persona2.png" alt="User persona - segmento 2" width="600"/>

*Imagen (N°3). Elaboración propia. Realizado en UXPressia*
<br>

### 2.3.2. User Task Matrix

En esta sección se presenta el *User Task Matrix*, el cual identifica y organiza las principales tareas que realizan los segmentos definidos (Cliente Corporativo y Proveedor/Distribuidor) para cumplir sus objetivos operativos.  

Asimismo, se incorpora el enfoque de IoT (Internet of Things), donde dichas tareas se ven influenciadas por la disponibilidad de datos en tiempo real provenientes de sensores.

**Segmento 1: Cliente Corporativo (Operaciones y Logística)**

| **Task Matrix**                                                                 | **Frecuencia** | **Importancia** |
|---------------------------------------------------------------------------------|----------------|-----------------|
| Monitorear niveles de combustible en tanques (sensor ultrasónico)              | Alta           | Alta            |
| Supervisar consumo de combustible en tiempo real (flow meter)                  | Alta           | Alta            |
| Detectar variaciones anómalas en consumo                                       | Alta           | Alta            |
| Verificar condiciones del combustible (temperatura)                            | Media          | Media           |
| Coordinar pedidos de abastecimiento basados en datos reales                    | Media          | Alta            |
| Validar volumen recibido vs volumen despachado                                 | Alta           | Alta            |
| Supervisar presión del sistema durante descarga                                | Media          | Media           |
| Evaluar eficiencia del uso de combustible (análisis histórico)                 | Baja           | Alta            |
| Gestionar incidencias operativas relacionadas al suministro                    | Media          | Alta            |
| Comunicar estado del abastecimiento a la gerencia                              | Media          | Media           |
| Revisar alertas de bajo nivel o consumo irregular                              | Alta           | Alta            |
| Auditar consumo vs presupuesto                                                 | Baja           | Alta            |

<br>

---

**Segmento 2: Proveedor / Distribuidor (Control de Flota y Transporte)**

| **Task Matrix**                                                                 | **Frecuencia** | **Importancia** |
|---------------------------------------------------------------------------------|----------------|-----------------|
| Monitorear ubicación de cisternas en tiempo real (GPS)                          | Alta           | Alta            |
| Supervisar volumen de combustible transportado (flow meter)                     | Alta           | Alta            |
| Detectar pérdidas o robos durante el transporte                                 | Alta           | Alta            |
| Recibir alertas por caídas de presión o anomalías                               | Alta           | Alta            |
| Coordinar rutas y tiempos de entrega                                            | Alta           | Alta            |
| Validar volumen entregado vs volumen registrado                                 | Alta           | Alta            |
| Supervisar condiciones del combustible durante el transporte (temperatura)      | Media          | Media           |
| Registrar incidencias en ruta                                                   | Media          | Media           |
| Comunicarse con conductores para seguimiento operativo                          | Alta           | Media           |
| Analizar desempeño de rutas y unidades                                          | Baja           | Media           |
| Controlar el proceso de despacho de combustible                                 | Alta           | Alta            |
| Revisar alertas de desviación en ruta o consumo                                 | Alta           | Alta            |

<br>

### 2.3.3. User Journey Mapping

En esta sección se presenta el *User Journey Mapping* para los segmentos identificados, con el objetivo de visualizar las acciones (Doing), pensamientos (Thinking) y emociones (Feeling) de los usuarios a lo largo del proceso de abastecimiento de combustible.  

Se considera un entorno mejorado mediante IoT, donde la información en tiempo real permite reducir incertidumbre, optimizar la toma de decisiones y mejorar la experiencia general del usuario.

**Segmento 1: El Cliente Corporativo (Demanda)**

<img src="../assets/Journey_Map1.png" alt="User persona - segmento 1" width="600"/>

*Imagen (N°2). Elaboración propia. Realizado en UXPressia*

**Segmento 2: El Proveedor / Distribuidor (Oferta)**

<img src="../assets/Journey_Map2.png" alt="User persona - segmento 2" width="600"/>

*Imagen (N°3). Elaboración propia. Realizado en UXPressia*
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

# Capítulo III: Requirements Specification

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

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Order API Application** perteneciente al *Order & Dispatch Context*.

El diseño de los componentes sigue los principios de la **Arquitectura Limpia (Clean Architecture)**. Como se observa en el diagrama, el flujo de dependencias es estrictamente unidireccional. Las solicitudes HTTP ingresan a través de la capa de interfaz (`Order Controller`), son orquestadas por el servicio de aplicación (`Order Application Service`), y este finalmente delega la ejecución de las reglas corporativas al núcleo del sistema (`FuelOrder Aggregate`) y la persistencia de datos al repositorio (`Order Repository`). Esta separación garantiza que la lógica del negocio B2B sea completamente independiente del framework web y de la base de datos PostgreSQL.

![Component Diagram - Order Context](../assets/cap4/c4-component-order.png)

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

En este nivel de abstracción (Nivel 4 del Modelo C4), nos adentramos en el diseño táctico del **Order & Dispatch Context**. Para garantizar un modelo de software robusto y evitar el antipatrón de "modelo anémico", aplicamos los principios de Domain-Driven Design (DDD).

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

A continuación, se presenta el modelo de dominio interno. El *Aggregate Root* principal es `FuelOrder`, el cual actúa como límite transaccional para la creación y aprobación de pedidos B2B. Para asegurar la integridad de los datos financieros y de medición, se implementan *Value Objects* inmutables como `FuelVolume` y `Money`. Finalmente, la entidad `DispatchRoute` gestiona la asignación logística del camión.

![Class Diagram - Order Context](../assets/cap4/c4-class-order.png)

##### 4.2.1.6.2. Bounded Context Database Design Diagram

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

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Telemetry Service Application** perteneciente al *IoT & Telemetry Context*.

Al igual que en el resto del sistema, los componentes se organizan bajo los principios de la **Arquitectura Limpia (Clean Architecture)**. En este contexto altamente transaccional, el flujo de entrada principal es manejado por un consumidor de eventos (`IoT Event Consumer`) que escucha las tramas enviadas por los sensores de hardware. Estas tramas son procesadas por el servicio de aplicación (`Telemetry App Service`), el cual delega la detección de anomalías (como mermas de combustible o salidas de ruta) al modelo de dominio puro (`TruckTelemetry Aggregate`). Finalmente, el estado se persiste a través del repositorio (`Telemetry Repository`) en una base de datos optimizada. Este diseño aísla la compleja lógica matemática del dominio de la infraestructura externa de mensajería.

![Component Diagram - Telemetry Context](../assets/cap4/c4-component-telemetry.png)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

En este nivel (C4 Model - Nivel 4), detallamos el diseño táctico del **IoT & Telemetry Context**. Dado que este módulo procesa flujos masivos de datos en tiempo real (Event-Driven), el modelo de dominio está diseñado para ser altamente resiliente y reactivo.

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

El núcleo de este contexto es el *Aggregate Root* `TruckTelemetry`, responsable de consolidar y analizar el flujo de datos. Para garantizar la inmutabilidad de las mediciones físicas, se emplean *Value Objects* como `GeoLocation` (coordenadas GPS), `FuelVolume` (galones y presión) y `EngineStatus`. Una característica avanzada de este diseño es la emisión de *Domain Events* (ej. `FuelDropDetectedEvent`) cuando la lógica matemática detecta una anomalía severa, como una caída abrupta de presión que sugiere un robo de hidrocarburos.

![Class Diagram - Telemetry Context](../assets/cap4/c4-class-telemetry.png)

##### 4.2.2.6.2. Bounded Context Database Design Diagram

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

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Billing API Application** perteneciente al *Financial & Billing Context*.

Este módulo crítico está diseñado bajo los principios de la **Arquitectura Limpia (Clean Architecture)**. Las peticiones relacionadas con la facturación y el monitoreo de presupuesto ingresan por la capa de interfaz (`Billing Controller`). La orquestación es manejada por el servicio de aplicación (`Billing App Service`), el cual delega el cálculo del *Burn Rate* y la validación de saldos al modelo de dominio (`Financial Aggregate`).

Una característica clave de este contenedor es la inclusión de un adaptador (`ERP Gateway`) en la capa de infraestructura, el cual funciona como una Capa Anticorrupción (ACL) para comunicarse con los sistemas contables externos de los clientes (ej. SAP). Finalmente, los comprobantes inmutables se almacenan a través del repositorio (`Billing Repository`). Este diseño asegura que el núcleo financiero de FuelTrack no se acople a integraciones de terceros.

![Component Diagram - Billing Context](../assets/cap4/c4-component-billing.png)

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Billing API Application** perteneciente al *Financial & Billing Context*.

Este módulo crítico está diseñado bajo los principios de la **Arquitectura Limpia (Clean Architecture)**. Las peticiones relacionadas con la facturación y el monitoreo de presupuesto ingresan por la capa de interfaz (`Billing Controller`). La orquestación es manejada por el servicio de aplicación (`Billing App Service`), el cual delega el cálculo del *Burn Rate* y la validación de saldos al modelo de dominio (`Financial Aggregate`).

Una característica clave de este contenedor es la inclusión de un adaptador (`ERP Gateway`) en la capa de infraestructura, el cual funciona como una Capa Anticorrupción (ACL) para comunicarse con los sistemas contables externos de los clientes (ej. SAP). Finalmente, los comprobantes inmutables se almacenan a través del repositorio (`Billing Repository`). Este diseño asegura que el núcleo financiero de FuelTrack no se acople a integraciones de terceros.

![Component Diagram - Billing Context](../assets/cap4/c4-component-billing.png)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

En este nivel de diseño técnico (Nivel 4 del Modelo C4), se detalla la lógica de implementación del **Financial & Billing Context**. El diseño se centra en la precisión de los cálculos financieros y la integridad de los comprobantes de pago generados.

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

El diseño del dominio está centrado en el Aggregate Root `FinancialAccount`, el cual gestiona el saldo y la exposición crediticia del cliente. Se utilizan *Value Objects* para encapsular la lógica de cálculo del `BurnRate` (tasa de consumo) y el `CreditLimit`. La entidad `BillingVoucher` representa el documento legal de facturación generado tras un despacho exitoso. Este modelo asegura que no existan inconsistencias entre el combustible despachado y el monto facturado.

![Class Diagram - Billing Context](../assets/cap4/c4-class-billing.png)

##### 4.2.3.6.2. Bounded Context Database Design Diagram

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

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección, se aplica el Nivel 3 del Modelo C4 para visualizar la estructura interna del contenedor **Auth API Application** perteneciente al *Identity & Access Context*.

Este módulo fundamental sigue los lineamientos de la **Arquitectura Limpia (Clean Architecture)** para centralizar la seguridad de FuelTrack. Las solicitudes de autenticación y validación de tokens ingresan mediante la capa de interfaz (`Auth Controller`). El servicio de aplicación (`Identity App Service`) orquesta la emisión de tokens JWT y delega la validación de contraseñas y permisos granulares (RBAC) al modelo de dominio (`User & Role Aggregate`). Finalmente, las credenciales encriptadas se gestionan a través del repositorio (`Auth Repository`). Esta separación garantiza que la lógica de seguridad y el control de accesos sean invulnerables y agnósticos al resto de los microservicios.

![Component Diagram - Identity Context](../assets/cap4/c4-component-identity.png)

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

En este último apartado de diseño táctico (Nivel 4 del Modelo C4), nos enfocamos en el **Identity & Access Context**. El diseño de este módulo está estrictamente aislado del resto de Bounded Contexts para garantizar que la seguridad, autenticación y autorización sean transversales e inviolables.

##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

El modelo de dominio pivota sobre el *Aggregate Root* `UserAccount`. Para aplicar una seguridad robusta desde el diseño, la contraseña jamás se maneja como un texto plano, sino que se encapsula en un *Value Object* inmutable llamado `PasswordHash` que contiene la lógica de verificación criptográfica. Asimismo, se implementa la entidad `Role` para gestionar el Control de Acceso Basado en Roles (RBAC), permitiendo diferenciar los permisos de gerentes corporativos, despachadores y choferes de cisternas.

![Class Diagram - Identity Context](../assets/cap4/c4-class-identity.png)

##### 4.2.4.6.2. Bounded Context Database Design Diagram

El esquema físico en PostgreSQL para el contexto de identidad está altamente normalizado para soportar la asignación dinámica de roles y permisos. Se emplean tablas intermedias (`USER_ROLES` y `ROLE_PERMISSIONS`) para resolver las relaciones de muchos a muchos inherentes a una arquitectura RBAC completa.

![Database Diagram - Identity Context](../assets/cap4/c4-db-identity.png)



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


