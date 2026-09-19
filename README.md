# Livva
<div align="center">

  <img src="assets/md-images-front/upc-logo.png" width="150px" />

  <p>Universidad Peruana de Ciencias Aplicadas</p>
  <p>Facultad de Ingeniería</p>
  <p>Carrera de Ingeniería de Software</p>

  <p>Ciclo académico 2026-20</p><br>

  <p><b>1ASI0730</b></p>
  <p><b>Aplicaciones Web</b></p>
  <p>NRC</p>
  <p><b>8168</b></p>
  <p><b>Informe de Trabajo Final</b></p>
  <p>Docente</p>
  <p><b>Sánchez Ponce, Alex Humberto</b></p>
  <p>Startup</p>
  <p><b>Livva Care</b></p><br>
  <p>Producto</p>
  <p><b>Livva</b></p>

</div>

<div align="center">
  <h3>Integrantes</h3>

  <table>
    <thead>
      <tr>
        <th>Código</th>
        <th>Apellidos y Nombres</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>U202321613</td>
        <td>Paredes Chavez, Carlos Augusto</td>
      </tr>
      <tr>
        <td>U202323369</td>
        <td>Torres Diaz, Rolando Andre</td>
      </tr>
      <tr>
        <td>U202418623</td>
        <td>Contreras Panuera, Fernando Fabrizio</td>
      </tr>
	<tr>
        <td>U202416147</td>
        <td>Cespedes Lezcano, Carlos Gabriel</td>
      </tr>
	<tr>
        <td>U20241f577</td>
        <td>Rivera Aguilar, Scarlet Josefina</td>
      </tr>
    </tbody>
  </table>
  <br>

  <p><b>Septiembre, 2026</b></p>

</div>

<div style="page-break-after: always;"></div>


## Registro de Versiones del Informe

| Versión | Fecha |  Autor   |                                                  Descripción de modificación                                                   |
| :-----: |:-----:|:--------:| :----------------------------------------------------------------------------------------------------------------------------: |
|   AV1   |       |  Todos   | Se agregó la primera versión del informe, incluyendo carátula, registro de versiones, perfiles del equipo, análisis inicial del problema, artefactos de UX, arquitectura preliminar y evidencias del Sprint 1. |

<div style="page-break-after: always;"></div>


## Project Report Collaboration Insights

A continuación, se presenta el repositorio utilizado para la elaboración colaborativa del informe del proyecto Livva.

#### Link del repositorio del Reporte:

- https://github.com/upc-pre-202620-1asi0730-8168-livva-care/livva-project-report

### Entrega AV1:

#### Participación por integrante:

##### Commits en el Project Report:

<div style="page-break-after: always;"></div>


# Contenido

## Índice

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
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
        - [ Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Personas](#231-user-personas)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.4. Big Picture Event Storming](#24-big-picture-eventstorming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>


# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio:** La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

En el siguiente cuadro se describen las acciones realizadas y los enunciados de conclusiones por parte del grupo, que permiten sustentar el cumplimiento del ABET – EAC - Student Outcome 5 durante la primera entrega del proyecto.

### AV1

| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
| **5.c1. Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Paredes Chavez, Carlos Augusto**<br>**AV1:** Participó en el refinamiento de la orientación general de Livva, contribuyendo a mantener consistencia entre la problemática, los segmentos objetivo y el alcance de la solución. Asimismo, desarrolló y refinó artefactos de análisis del dominio como el Big Picture EventStorming y el Ubiquitous Language, identificando eventos de negocio, actores, sistemas externos y conceptos relevantes. También colaboró en la definición del enfoque de las entrevistas y en la revisión de los artefactos desarrollados previamente para mantener trazabilidad entre las distintas secciones del proyecto.<br><br>**Torres Diaz, Rolando Andre**<br>**AV1:** Participó principalmente en el desarrollo del Capítulo IV, contribuyendo a la elaboración de los diferentes diagramas utilizados para representar la estructura y navegación de la propuesta. Su trabajo permitió transformar los requisitos y decisiones previamente definidas en representaciones visuales que facilitaron la comprensión de la experiencia planteada para Livva.<br><br>**Contreras Panuera, Fernando Fabrizio**<br>**AV1:** Participó en el desarrollo de los artefactos relacionados con la especificación de requisitos y definición de usuarios. Contribuyó en la elaboración de User Personas, Epics y User Stories, así como en diferentes elementos correspondientes al Capítulo III, procurando mantener relación entre las necesidades identificadas durante la investigación y las funcionalidades propuestas para Livva.<br><br>**Céspedes Lezcano, Carlos Gabriel**<br>**AV1:** Participó en la planificación y documentación del Sprint correspondiente a la primera entrega, así como en el desarrollo de la primera versión del Landing Page de Livva. Adicionalmente, colaboró en la elaboración de artefactos de diseño como Wireframes y Wireflows, relacionando la implementación inicial del producto con la experiencia de usuario definida por el equipo.<br><br>**Rivera Aguilar, Scarlet Josefina**<br>**AV1:** Participó principalmente en el desarrollo visual de la propuesta de Livva mediante la elaboración y refinamiento de Wireframes, Mock-ups y Wireflows. Su trabajo permitió representar gráficamente las principales interfaces y recorridos del usuario, manteniendo coherencia visual entre los segmentos objetivo, las funcionalidades propuestas y la futura Web Application. | Durante AV1, el equipo aplicó un esquema de liderazgo compartido en el que cada integrante asumió responsabilidad sobre diferentes componentes del proyecto. Las responsabilidades abarcaron investigación y modelado del dominio, especificación de requisitos, diseño UX/UI, diagramación, planificación del Sprint e implementación inicial del Landing Page. La revisión e integración de estos aportes permitió mantener coherencia entre las distintas etapas del desarrollo de Livva y avanzar hacia los objetivos definidos para la primera entrega. |
| **5.c2. Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Paredes Chavez, Carlos Augusto**<br>**AV1:** Coordinó sus actividades de análisis y documentación con los artefactos previamente desarrollados por el equipo, realizando ajustes en la definición del producto, Big Picture EventStorming y Ubiquitous Language cuando fue necesario mantener coherencia con el alcance acordado. Sus aportes fueron desarrollados mediante feature branches, commits y Pull Requests, permitiendo su revisión antes de ser incorporados a la rama `develop`.<br><br>**Torres Diaz, Rolando Andre**<br>**AV1:** Organizó el desarrollo de los diagramas del Capítulo IV considerando como entrada los requisitos, flujos y decisiones de diseño elaborados por otros integrantes. Coordinó estos artefactos con el resto del equipo para que las representaciones visuales fueran consistentes con la estructura y comportamiento planteados para el producto.<br><br>**Contreras Panuera, Fernando Fabrizio**<br>**AV1:** Desarrolló los artefactos correspondientes a User Personas, Epics, User Stories y otros elementos del Capítulo III, coordinando sus decisiones con los resultados obtenidos previamente durante Lean UX y UX Research. Esta relación permitió establecer requisitos que respondieran a las necesidades identificadas para los segmentos objetivo de Livva.<br><br>**Céspedes Lezcano, Carlos Gabriel**<br>**AV1:** Participó en la organización de las actividades correspondientes al Sprint y en la implementación del Landing Page, coordinando este desarrollo con los Wireframes y Wireflows definidos para la experiencia inicial. Su trabajo contribuyó a materializar parte de la propuesta planteada durante las etapas anteriores del proyecto y al cumplimiento de los objetivos establecidos para AV1.<br><br>**Rivera Aguilar, Scarlet Josefina**<br>**AV1:** Desarrolló y refinó Wireframes, Mock-ups y Wireflows considerando los requisitos y recorridos definidos por el equipo. Coordinó las decisiones gráficas con los demás integrantes para mantener consistencia entre las diferentes vistas y facilitar posteriormente su implementación en el Landing Page y la Web Application. | Durante la primera entrega, el equipo organizó el trabajo mediante la distribución de responsabilidades y la dependencia controlada entre los distintos artefactos. La investigación y definición del dominio sirvieron como entrada para la especificación de requisitos; estos requisitos orientaron los diagramas, Wireframes, Mock-ups y Wireflows; y dichos artefactos apoyaron posteriormente la planificación del Sprint y la implementación inicial del Landing Page. El uso de GitFlow, feature branches, Conventional Commits y Pull Requests permitió mantener trazabilidad de los aportes y facilitar su revisión e integración progresiva en el repositorio común. |

<div style="page-break-after: always;"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Livva Care** es una startup peruana orientada al desarrollo de soluciones digitales para facilitar el acceso, intermediación y gestión de seguros mediante experiencias web simples, centralizadas y orientadas al usuario.

Su producto principal, **Livva**, busca conectar digitalmente a los usuarios con productos de compañías aseguradoras asociadas, concentrándose inicialmente en seguros vehiculares y seguros de vida.

La propuesta de Livva Care no consiste en asumir las funciones propias de una compañía aseguradora. Las compañías asociadas mantienen responsabilidades como la evaluación del riesgo, determinación de condiciones, emisión de pólizas y resolución final de siniestros o solicitudes de indemnización. Livva se concentra en proporcionar una experiencia digital para facilitar la búsqueda de información, solicitud, consulta y gestión posterior de los seguros.

El modelo de negocio contempla ingresos derivados de la intermediación de seguros y de planes de suscripción propios de Livva, mediante los cuales los usuarios pueden acceder a beneficios adicionales de la plataforma.

Durante la primera etapa del producto, Livva Care se enfocará exclusivamente en dos segmentos: propietarios de vehículos particulares interesados en seguros vehiculares y personas interesadas en seguros de vida.

### Misión

Facilitar el acceso y la gestión de seguros mediante una experiencia digital clara, centralizada y accesible, ayudando a las personas a comprender, solicitar y administrar su protección de forma más sencilla y acompañada.

### Visión

Convertir a Livva Care en una plataforma digital referente en el Perú para la intermediación y gestión de seguros, reconocida por simplificar la relación entre las personas y sus seguros mediante una experiencia confiable, transparente y orientada a sus necesidades.

### 1.1.2. Perfiles de integrantes del equipo

|   Código   | Nombre completo del integrante  | Descripción de la carrera                                          |                               Fotografía                                | Conocimientos y habilidades                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :--------: |:--------------------------------| :----------------------------------------------------------------- |:-----------------------------------------------------------------------:| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| U202321613 | Paredes Chavez, Carlos Augusto | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/carlos-paredes.PNG" width="150px" /> | Soy estudiante de Ingeniería de Software y tengo experiencia en el desarrollo de aplicaciones web, principalmente utilizando HTML, CSS, JavaScript, TypeScript y frameworks modernos. También cuento con conocimientos en bases de datos, control de versiones con Git y GitHub, y desarrollo tanto frontend como backend. Me interesa especialmente crear soluciones digitales funcionales, bien estructuradas y con una buena experiencia de usuario. Me considero una persona constante, responsable y con facilidad para aprender nuevas tecnologías. Busco seguir fortaleciendo mis conocimientos mediante proyectos prácticos que me permitan mejorar mis habilidades técnicas y prepararme para desenvolverme profesionalmente en el área de desarrollo de software. |
| U202323369 | Torres Diaz, Rolando Andre | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/rolando-torres.PNG" width="150px" /> | Soy Rolando Andre Torres Diaz, estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). A lo largo de la carrera he ido adquiriendo conocimientos en programación, desarrollo de software, bases de datos, diseño de aplicaciones y tecnologías web. Dentro del desarrollo de Livva participaré en distintas etapas del proyecto, como el análisis de requerimientos, el diseño de la solución, el desarrollo de funcionalidades, la gestión de la base de datos y la elaboración de la documentación. |           
| U202418623 | Contreras Panuera, Fernando Fabrizio | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/fernando-contreras.PNG" width="150px" /> | Soy estudiante de Ingeniería de Software y tengo conocimientos en el desarrollo de aplicaciones web, principalmente utilizando HTML, CSS, JavaScript y C++. También cuento con conocimientos en bases de datos, control de versiones con Git y GitHub, y desarrollo tanto frontend como backend. Me interesa especialmente crear soluciones digitales funcionales, bien estructuradas y que puedan brindar una buena experiencia de usuario. Me considero una persona constante, responsable y con facilidad para aprender nuevas tecnologías. Me gusta desarrollar proyectos prácticos que me permitan poner en práctica lo aprendido y mejorar progresivamente mis habilidades. Busco seguir fortaleciendo mis conocimientos durante mi formación universitaria y adquirir nuevas experiencias que me ayuden a crecer en el área del desarrollo de software. |
| U202416147 | Céspedes Lezcano, Carlos Gabriel | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/carlos-cespedes.PNG" width="150px" /> | Soy estudiante de Ingeniería de Software con experiencia en el desarrollo de aplicaciones web mediante HTML, CSS y JavaScript, además del manejo de bases de datos y control de versiones con Git. Me enfoco en construir soluciones digitales funcionales, bien estructuradas y orientadas a ofrecer una gran experiencia de usuario. Destaco por mi constancia, responsabilidad y capacidad para adaptarme rápidamente a nuevas tecnologías. Busco seguir consolidando mis competencias mediante el desarrollo de proyectos prácticos que me impulsen a crecer técnicamente y prepararme para el entorno profesional del software. |
| U20241f577 | Rivera Aguilar, Scarlet Josefina | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/scarlet-rivera.PNG" width="150px" /> | Actualmente me encuentro en el quinto ciclo de mi carrera y tengo un gran interés por el análisis de datos. Me considero una persona organizada, constante y con una fuerte motivación por aprender. Disfruto comprender el funcionamiento de las cosas, identificar fallas y plantear soluciones de mejora. Me desempeño adecuadamente en trabajo en equipo, incluso bajo presión, y valoro compartir mis conocimientos con los demás. |

## 1.2. Solution Profile

La solución propuesta por Livva consiste en una plataforma web orientada a facilitar la intermediación y gestión digital de seguros vehiculares y de vida.

La experiencia busca acompañar al usuario durante diferentes etapas del ciclo del seguro, desde la búsqueda de información y solicitud inicial hasta la consulta y administración posterior de la póliza, incluyendo documentos, coberturas, beneficiarios, renovaciones y procesos relacionados con siniestros o solicitudes de indemnización.

Livva se plantea como un bróker digital que facilita la interacción entre los usuarios y las compañías aseguradoras asociadas. Las aseguradoras mantienen responsabilidades como la evaluación correspondiente, definición de las condiciones del producto, emisión de pólizas y resolución de solicitudes de cobertura o indemnización, mientras que Livva concentra la experiencia digital de intermediación y acompañamiento.

Como parte de su modelo de negocio, Livva ofrecerá planes de suscripción dirigidos a sus usuarios. Estos planes permitirán diferenciar el nivel de beneficios y servicios digitales disponibles dentro de la plataforma, manteniendo un alcance simplificado y viable para la primera versión del producto.

La solución está dirigida inicialmente a dos segmentos objetivo: propietarios de vehículos particulares interesados en seguros vehiculares y personas interesadas en contratar o gestionar seguros de vida.

Las compañías aseguradoras participan como organizaciones externas asociadas al ecosistema de Livva, pero no constituyen un segmento objetivo ni dispondrán de una aplicación empresarial propia dentro del alcance inicial del proyecto.

### 1.2.1. Antecedentes y Problemática

La contratación y posterior gestión de un seguro puede involucrar distintas etapas, documentos, conceptos y canales de comunicación.

En el caso de los seguros vehiculares, una persona debe buscar información, proporcionar datos sobre su vehículo, comprender las coberturas disponibles, revisar las condiciones de la póliza y conocer qué debe realizar ante un eventual accidente o siniestro.

En los seguros de vida, el usuario debe comprender conceptos relacionados con la cobertura, el monto asegurado y los beneficiarios, además de mantener disponible la información de su póliza y conocer los procedimientos relacionados con una eventual solicitud de indemnización.

Estas actividades pueden encontrarse distribuidas entre páginas web, documentos, correos electrónicos, llamadas telefónicas y otros canales de atención, dificultando que el usuario mantenga una visión clara y continua de la protección contratada.

Livva propone abordar esta situación mediante una plataforma que centralice digitalmente las principales actividades correspondientes a la solicitud y posterior gestión de seguros vehiculares y de vida.

#### Análisis preliminar mediante 5W2H

##### What?
**¿Qué sucede?**

- La búsqueda, contratación y administración de seguros puede involucrar información, documentos y actividades distribuidos entre distintas etapas y canales, dificultando que los usuarios comprendan y gestionen de manera continua su protección.

##### When
**¿Cuándo ocurre?**

- Durante diferentes momentos del ciclo de vida del seguro, como la búsqueda de información, cotización, solicitud, contratación, emisión, vigencia, renovación y atención de un siniestro o solicitud de indemnización.

##### Where
**¿Dónde ocurre?**

- Inicialmente, el proyecto se plantea para el mercado peruano y para interacciones realizadas mediante canales digitales entre los usuarios, Livva y las compañías aseguradoras asociadas. La experiencia principal se desarrollará mediante un Landing Page y una Web Application responsive integrados con los servicios de Livva.

##### Who
**¿Quiénes están involucrados?**

- Propietarios de vehículos particulares que tengan, hayan tenido o estén interesados en contratar un seguro vehicular.
- Personas mayores de edad que tengan, hayan considerado o estén interesadas en contratar un seguro de vida para proteger económicamente a sus familiares o beneficiarios.

Las compañías aseguradoras participan como entidades asociadas dentro del proceso de intermediación, pero no constituyen un segmento objetivo de la presente investigación.

##### Why
**¿Por qué es relevante?**

- Porque la utilidad de un seguro no termina después de su contratación. Los usuarios necesitan comprender sus coberturas, consultar la información de sus pólizas, mantener determinados datos actualizados y conocer qué acciones realizar ante una renovación, siniestro o solicitud de indemnización.

##### How?
**¿Cómo se aborda el problema actualmente?**

- Los usuarios recurren a compañías aseguradoras, corredores, páginas web y distintos canales comerciales o de atención para buscar, contratar y posteriormente administrar sus seguros. Livva propone centralizar digitalmente las principales etapas correspondientes a la intermediación y acompañamiento dentro de una experiencia web, ofreciendo adicionalmente planes de servicio propios que permitan acceder a distintos beneficios dentro de la plataforma.

##### How Much
**¿Cuál es el impacto?**

- El impacto depende de factores como el tipo de seguro, la cobertura contratada, los canales utilizados y la experiencia particular de cada usuario. Durante las entrevistas se buscará identificar el nivel de tiempo, esfuerzo, dificultad y comprensión percibido por los dos segmentos objetivo en los procesos actuales, evitando establecer cifras sin evidencia.

A partir del análisis preliminar, se identifica como principal oportunidad la creación de una experiencia digital que mantenga continuidad desde la búsqueda y solicitud de un seguro hasta su gestión posterior.

Livva administrará la experiencia de intermediación, organización de información y acompañamiento digital, mientras que la compañía aseguradora asociada conservará responsabilidades como la evaluación correspondiente, emisión de la póliza y resolución final de las solicitudes de cobertura o indemnización.

**Problema central:** las actividades relacionadas con la búsqueda, solicitud, contratación y posterior gestión de seguros vehiculares y de vida pueden encontrarse distribuidas entre diferentes procesos y canales, dificultando que los usuarios comprendan y administren su protección mediante una experiencia continua y centralizada.

### Objetivos

#### Objetivo General

Diseñar, desarrollar y desplegar una plataforma web de intermediación y gestión digital de seguros vehiculares y de vida que permita a los usuarios acceder a información, realizar solicitudes, consultar y administrar sus pólizas y dar seguimiento a procesos posteriores relacionados con su protección, mediante una experiencia clara, centralizada, accesible y adaptable a distintos dispositivos.

#### Objetivos Específicos

- **Facilitar la solicitud de seguros:** proporcionar flujos digitales diferenciados para seguros vehiculares y seguros de vida, permitiendo que los usuarios registren la información necesaria de forma clara y estructurada.

- **Centralizar la gestión de pólizas:** permitir que los usuarios consulten desde un mismo entorno información relevante como vigencia, coberturas, documentos y estado de sus seguros.

- **Apoyar la gestión de seguros vehiculares:** permitir el registro y consulta de vehículos asociados al usuario, así como el inicio y seguimiento básico de solicitudes relacionadas con seguros vehiculares.

- **Apoyar la gestión de seguros de vida:** permitir la solicitud de seguros de vida y la administración de información relacionada con beneficiarios.

- **Facilitar el seguimiento posterior a la contratación:** brindar mecanismos para registrar y consultar el estado de siniestros vehiculares y solicitudes de indemnización relacionadas con seguros de vida.

- **Mantener informado al usuario:** proporcionar notificaciones relacionadas con eventos relevantes como cambios de estado, renovación de pólizas, información pendiente o avances en procesos registrados.

- **Incorporar un modelo de suscripción:** ofrecer planes de Livva con beneficios diferenciados, permitiendo al usuario consultar, contratar, revisar y cancelar su suscripción mediante un flujo simplificado.

- **Integrar servicios externos:** utilizar al menos un servicio externo de terceros como parte de los procesos de la plataforma, priorizando una integración asociada al flujo de suscripción o pago en un entorno de prueba.

- **Garantizar una experiencia web consistente:** mantener coherencia entre el Landing Page y la Web Application, incluyendo diseño responsive, accesibilidad e internacionalización según los requisitos establecidos para el proyecto.

### Restricciones

#### Restricciones de Alcance

- **Segmentos objetivo:** la primera versión de Livva estará dirigida únicamente a propietarios de vehículos particulares y personas interesadas en seguros de vida.

- **Participación de compañías aseguradoras:** las aseguradoras serán consideradas entidades externas asociadas al ecosistema de Livva. No se desarrollará un portal B2B ni funcionalidades destinadas a empleados de compañías aseguradoras dentro del alcance inicial.

- **Intermediación y no aseguramiento:** Livva actuará como una plataforma de intermediación y acompañamiento digital. No asumirá funciones propias de una compañía aseguradora como evaluación actuarial, determinación real de primas, emisión legal de pólizas o resolución definitiva de siniestros e indemnizaciones.

- **Cotizaciones y productos:** las alternativas de seguros mostradas en el sistema serán representaciones académicas o datos previamente registrados. No se implementará un motor actuarial real para calcular primas.

- **Gestión de siniestros e indemnizaciones:** la primera versión permitirá registrar información y consultar estados básicos, pero no incluirá peritajes, evaluación automatizada de daños, liquidación de indemnizaciones ni pagos reales.

- **Suscripciones:** la gestión de suscripciones se limitará a consultar planes, seleccionar un plan, activar una suscripción, consultar su estado y cancelarla. No se implementarán procesos avanzados de facturación, impuestos, devoluciones, cupones o prorrateos.

- **Pagos:** cualquier integración de pago se realizará mediante un entorno de prueba o sandbox y tendrá fines exclusivamente académicos.

- **Servicios externos:** la solución dependerá de al menos un servicio externo de terceros para cubrir un proceso específico del sistema. La indisponibilidad de dicho servicio podrá limitar temporalmente la funcionalidad asociada.

#### Restricciones Técnicas

- La solución estará compuesta por un **Landing Page**, una **Web Application responsive** y un **RESTful API** desarrollado internamente.

- La Web Application deberá consumir el RESTful API propio para acceder a las principales capacidades del negocio.

- El backend deberá desarrollarse utilizando **ASP.NET Core y C#**, con persistencia mediante **Entity Framework Core** y una base de datos relacional compatible con el alcance del proyecto.

- La experiencia deberá contemplar internacionalización para **English (en_US)** y **Latin American Spanish (es_419)**, manteniendo inglés como idioma predeterminado según las especificaciones del curso.

- El Landing Page y la Web Application deberán considerar principios de accesibilidad, incluyendo atributos ARIA y diseño adaptable a diferentes tamaños de pantalla.

#### Restricciones de Tiempo

- El desarrollo del producto estará limitado al calendario académico del curso.

- El alcance funcional principal deberá poder diseñarse, implementarse, probarse y desplegarse en aproximadamente **12 semanas**, priorizando funcionalidades esenciales sobre procesos empresariales avanzados.

- Las funcionalidades deberán organizarse progresivamente entre los diferentes Sprints y entregables del curso, manteniendo coherencia entre el Product Backlog y los objetivos de cada Sprint.

#### Restricciones de Complejidad

- Se priorizará un MVP funcional y demostrable sobre la implementación completa de procesos reales del sector asegurador.

- No se incluirán en la primera versión funcionalidades como inteligencia artificial para recomendar seguros, firma digital, OCR, validación con RENIEC o SUNARP, aplicaciones móviles nativas, geolocalización de accidentes o integración directa con sistemas internos de aseguradoras.

### 1.2.2. Lean UX Process

Para Livva se aplica el Lean UX Process con el propósito de establecer explícitamente las principales creencias relacionadas con el problema, los segmentos objetivo, los resultados esperados y las características propuestas antes de asumirlas como hechos comprobados.

Estas creencias serán posteriormente contrastadas mediante las entrevistas realizadas a propietarios de vehículos particulares y personas interesadas en seguros de vida, así como mediante las posteriores actividades de validación del producto.

El proceso considera Business Assumptions, Business Outcome Assumptions, User Assumptions, User Outcome and Benefit Assumptions y Feature Assumptions. A partir de los Feature Assumptions se establecen los respectivos Lean UX Hypothesis Statements.

#### 1.2.2.1. Lean UX Problem Statements

La situación actual de la intermediación digital de seguros se ha centrado principalmente en personas que buscan seguros vehiculares o de vida mediante procesos que pueden involucrar distintas etapas, canales de comunicación, documentos e interacciones para completar la contratación y gestionar posteriormente su póliza.

Lo que los productos y servicios existentes no siempre logran abordar de manera integral es una experiencia digital continua que facilite tanto la comprensión y solicitud del seguro como la administración posterior de la información relacionada con la póliza, coberturas, beneficiarios, renovaciones y siniestros.

Livva abordará esta oportunidad mediante una plataforma digital de corretaje de seguros que proporcione flujos especializados para seguros vehiculares y de vida, centralice la información relacionada con las pólizas y acompañe digitalmente al usuario durante diferentes etapas del ciclo de vida del seguro. La plataforma podrá ofrecer distintos niveles de beneficios mediante planes de suscripción propios de Livva.

Nuestro enfoque inicial se centrará en propietarios de vehículos particulares que tengan, hayan tenido o estén interesados en contratar un seguro vehicular y en personas mayores de edad que tengan, hayan considerado o estén interesadas en contratar un seguro de vida para proteger económicamente a sus familiares o beneficiarios.

Sabremos que hemos tenido éxito cuando observemos que los usuarios completan los procesos digitales de solicitud mediante Livva, utilizan posteriormente la plataforma para consultar y gestionar información relacionada con sus seguros, realizan oportunamente acciones vinculadas con sus pólizas y una proporción de usuarios encuentra suficiente valor en los beneficios adicionales como para utilizar un plan de suscripción de Livva.

#### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions

**BA01.** Creemos que existe una oportunidad de crear valor digitalizando no solamente la solicitud inicial de un seguro, sino también diferentes actividades relacionadas con la gestión posterior de la póliza.

**BA02.** Consideramos que los seguros vehiculares y de vida poseen características suficientemente diferentes como para requerir flujos especializados, aunque pueden compartir funcionalidades como gestión de pólizas, documentación, notificaciones y asistencia relacionada con siniestros o indemnizaciones.

**BA03.** Creemos que los usuarios valorarán una experiencia que centralice información actualmente consultada mediante diferentes documentos o canales.

**BA04.** Creemos que el acompañamiento digital posterior a la contratación puede diferenciar a Livva de experiencias concentradas principalmente en la búsqueda o cotización inicial del seguro.

**BA05.** Creemos que Livva puede desarrollar un modelo de negocio sostenible combinando ingresos derivados de la intermediación de seguros contratados mediante la plataforma con ingresos recurrentes provenientes de planes de suscripción dirigidos a sus usuarios.

**BA06.** Creemos que comenzar con seguros vehiculares y de vida permitirá validar la propuesta de valor antes de incorporar nuevas categorías de seguros.

**BA07.** Creemos que determinados usuarios estarán dispuestos a contratar un plan de Livva si los beneficios adicionales proporcionan suficiente valor durante la contratación y gestión posterior de sus seguros.

##### Business Outcome Assumptions

**BOA01.** Creemos que el éxito de Livva se reflejará en un porcentaje creciente de usuarios que completan una solicitud de seguro después de iniciar el flujo correspondiente.

**BOA02.** Creemos que una reducción de solicitudes incompletas indicará que los procesos digitales guiados ayudan a los usuarios a proporcionar correctamente la información necesaria.

**BOA03.** Creemos que el uso recurrente de funcionalidades relacionadas con pólizas, documentos, beneficiarios, renovaciones y siniestros indicará que Livva genera valor después de la contratación inicial.

**BOA04.** Creemos que un aumento en la cantidad de usuarios que realizan oportunamente acciones relacionadas con sus pólizas indicará que las notificaciones y herramientas de seguimiento resultan útiles.

**BOA05.** Creemos que un incremento progresivo de seguros solicitados y gestionados mediante Livva contribuirá a la sostenibilidad del modelo de intermediación.

**BOA06.** Creemos que un porcentaje creciente de usuarios que seleccionan un plan de suscripción después de conocer sus beneficios indicará que la propuesta de valor adicional resulta relevante.

**BOA07.** Creemos que una proporción significativa de suscripciones que se mantienen activas durante su período correspondiente indicará que los beneficios del plan generan valor recurrente para los usuarios.

##### User Assumptions

**UA01.** Creemos que los propietarios de vehículos particulares desean comprender las coberturas y condiciones de un seguro vehicular antes de completar su contratación.

**UA02.** Creemos que los propietarios de vehículos valoran disponer de información clara sobre su póliza, documentos y coberturas desde un entorno digital centralizado.

**UA03.** Creemos que los propietarios de vehículos que experimentan un accidente o siniestro necesitan orientación clara sobre los pasos, información y documentación requeridos.

**UA04.** Creemos que las personas interesadas en seguros de vida pueden presentar dificultades para comprender conceptos como cobertura, monto asegurado y beneficiarios.

**UA05.** Creemos que los usuarios de seguros de vida valoran poder consultar y mantener actualizada la información relacionada con sus beneficiarios.

**UA06.** Creemos que los usuarios de ambos segmentos valoran recibir recordatorios sobre vencimientos, renovaciones, información pendiente u otras acciones relacionadas con sus seguros.

**UA07.** Creemos que los usuarios de ambos segmentos valoran tener sus pólizas, documentos y coberturas disponibles dentro de una misma plataforma.

**UA08.** Creemos que algunos usuarios de ambos segmentos pueden valorar beneficios adicionales relacionados con el acompañamiento, seguimiento y gestión digital de sus seguros lo suficiente como para considerar un plan de suscripción.

**UA09.** Creemos que los usuarios desean comprender claramente las diferencias entre los planes disponibles antes de decidir si un nivel de servicio adicional justifica su costo.

##### User Outcome and Benefit Assumptions

**UOBA01.** Los propietarios de vehículos desean completar la solicitud de un seguro comprendiendo claramente la información requerida, las coberturas disponibles y las características de la protección seleccionada.

**UOBA02.** Los propietarios de vehículos desean consultar fácilmente su póliza, documentos y coberturas y recibir orientación cuando ocurre un accidente o siniestro.

**UOBA03.** Las personas interesadas en seguros de vida desean comprender conceptos como cobertura, monto asegurado y beneficiarios antes de tomar una decisión de contratación.

**UOBA04.** Los usuarios de seguros de vida desean registrar, consultar y mantener actualizada la información de sus beneficiarios con facilidad.

**UOBA05.** Los usuarios de ambos segmentos desean disponer de información centralizada sobre sus seguros sin tener que reconstruir su historial mediante diferentes canales.

**UOBA06.** Los usuarios de ambos segmentos desean recibir información oportuna cuando deban realizar acciones relacionadas con la vigencia o gestión de sus seguros.

**UOBA07.** Los usuarios de ambos segmentos desean conocer de manera clara qué beneficios adicionales obtienen mediante cada plan de Livva para decidir si una suscripción se adapta a sus necesidades.

**UOBA08.** Los usuarios suscritos desean consultar fácilmente el plan contratado y el estado de su suscripción para mantener control sobre el servicio adquirido.

##### Feature Assumptions

**FA01.** Creemos que un flujo guiado para el registro del vehículo y la solicitud de seguro ayudará a los propietarios de vehículos a proporcionar correctamente la información necesaria y comprender mejor el proceso.

**FA02.** Creemos que un flujo guiado para la solicitud de seguro de vida, incluyendo información sobre cobertura, monto asegurado y beneficiarios, facilitará la comprensión y finalización del proceso.

**FA03.** Creemos que un espacio centralizado para consultar pólizas, documentos y coberturas facilitará a los usuarios la administración de sus seguros.

**FA04.** Creemos que una funcionalidad digital para consultar y actualizar beneficiarios permitirá a los usuarios de seguros de vida mantener esta información con mayor facilidad.

**FA05.** Creemos que un flujo guiado de asistencia ante siniestros o solicitudes de indemnización ayudará a los usuarios a comprender qué información, documentación y pasos son necesarios durante estos procesos.

**FA06.** Creemos que las notificaciones proactivas sobre vencimientos, renovaciones, información pendiente y cambios de estado ayudarán a los usuarios a realizar oportunamente las acciones relacionadas con sus seguros.

**FA07.** Creemos que ofrecer planes de suscripción claramente diferenciados, junto con un proceso sencillo para seleccionar, activar, consultar y cancelar una suscripción, permitirá a los usuarios acceder a niveles de servicio acordes con sus necesidades y contribuirá a generar ingresos recurrentes para Livva.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### HS01 — Solicitud guiada de seguro vehicular

Creemos que lograremos una mayor tasa de finalización de solicitudes de seguro vehicular.

Si los propietarios de vehículos particulares

Obtienen una experiencia de solicitud más clara y estructurada

Con un flujo guiado para el registro del vehículo y la solicitud del seguro.

##### HS02 — Solicitud guiada de seguro de vida

Creemos que lograremos una mayor tasa de finalización de solicitudes de seguro de vida.

Si las personas interesadas en seguros de vida

Obtienen mayor claridad sobre la cobertura, el monto asegurado y la información de sus beneficiarios

Con un flujo guiado para la solicitud de seguro de vida.

##### HS03 — Gestión centralizada de pólizas

Creemos que lograremos una mayor interacción de los usuarios con Livva después de la contratación.

Si los usuarios que poseen un seguro activo

Obtienen acceso centralizado a sus pólizas, documentos y coberturas

Con un espacio digital para la gestión de sus seguros.

##### HS04 — Gestión de beneficiarios

Creemos que lograremos reducir la dificultad asociada con la consulta y actualización de información de beneficiarios.

Si los usuarios que poseen un seguro de vida

Obtienen mayor control sobre la información de sus beneficiarios

Con una funcionalidad digital para consultar y actualizar beneficiarios.

##### HS05 — Asistencia ante siniestros e indemnizaciones

Creemos que lograremos que un mayor porcentaje de solicitudes relacionadas con siniestros o indemnizaciones sea registrado con la información requerida.

Si los usuarios que necesitan iniciar uno de estos procesos

Obtienen orientación clara sobre la información, documentación y pasos necesarios

Con un flujo guiado de asistencia y seguimiento.

##### HS06 — Notificaciones proactivas

Creemos que lograremos una mayor cantidad de acciones realizadas oportunamente en relación con la gestión de los seguros.

Si los usuarios con seguros activos

Obtienen información oportuna sobre vencimientos, renovaciones, información pendiente y cambios de estado

Con notificaciones proactivas y alertas dentro de Livva.

##### HS07 — Planes de suscripción Livva

Creemos que lograremos incrementar los ingresos recurrentes generados mediante la plataforma.

Si los usuarios de seguros vehiculares y de vida

Obtienen beneficios adicionales acordes con sus necesidades y comprenden claramente las diferencias entre los niveles de servicio

Con planes de suscripción de Livva que puedan seleccionar y gestionar digitalmente.

#### 1.2.2.4. Lean UX Canvas

![](./assets/md-images-lean-ux-canva/lean-ux-canvas.PNG)

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
Livva Care participa en el sector InsurTech y de corretaje digital de seguros en el mercado peruano. Para el análisis competitivo se han seleccionado tres empresas con propuestas digitales relacionadas con la intermediación y comercialización de seguros: **SeguroSimple, QuePlan y Seguros Falabella**.

SeguroSimple y QuePlan constituyen competidores directos debido a que utilizan plataformas digitales para intermediar productos de diferentes compañías aseguradoras y brindar asesoría durante el proceso de contratación. Seguros Falabella también representa una competencia relevante debido a su oferta digital de seguros vehiculares y de vida, así como por el respaldo del ecosistema comercial y financiero de Falabella.

El análisis busca identificar las principales ventajas, debilidades y características de estas propuestas para establecer oportunidades de diferenciación para Livva Care.

### 2.1.1. Análisis competitivo

Para comprender la posición preliminar de Livva Care frente a las alternativas existentes en el mercado, se desarrolló un **Competitive Analysis Landscape** considerando a SeguroSimple, QuePlan y Seguros Falabella.

El análisis compara aspectos relacionados con el perfil de cada empresa, su mercado objetivo, estrategias de marketing, productos y servicios, precios, costos y canales de distribución.






<table>
  <thead>
    <tr>
      <th colspan="6">Competitive Analysis Landscape</th>
    </tr>
    <tr>
      <td colspan="2">
        <strong>¿Por qué llevar a cabo este análisis?</strong>
      </td>
      <td colspan="4">
        ¿Cómo puede Livva Care posicionar a Livva como una alternativa
        especializada en la intermediación y gestión digital de seguros
        vehiculares y de vida frente a corredores y plataformas digitales
        de seguros ya existentes en el mercado peruano?
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>
          (En la cabecera colocar por cada competidor nombre y logo)
        </strong>
      </td>
      <th>
        Livva Care<br>
        <img
          src="./assets/md-images-competitors/livva-care-logo.PNG"
          alt="Livva Care"
          width="90"
        >
      </th>
      <th>
        SeguroSimple<br>
        <img
          src="./assets/md-images-competitors/seguro-simple-logo.png"
          alt="SeguroSimple"
          width="90"
        >
      </th>
      <th>
        QuePlan<br>
        <img
          src="./assets/md-images-competitors/queplan-logo.PNG"
          alt="QuePlan"
          width="90"
        >
      </th>
      <th>
        Seguros Falabella<br>
        <img
          src="./assets/md-images-competitors/seguros-falabella-logo.PNG"
          alt="Seguros Falabella"
          width="90"
        >
      </th>
    </tr>
  </thead>
  <tbody>
    <!-- PERFIL -->
    <tr>
      <th rowspan="2">Perfil</th>
      <td>
        <strong>Overview</strong>
      </td>
      <td>
        Livva Care es una startup InsurTech peruana que desarrolla Livva, una 
		plataforma orientada a la intermediación y gestión digital de seguros 
		vehiculares y de vida. La propuesta busca centralizar procesos como 
		solicitud, consulta de pólizas, beneficiarios, renovaciones y 
		acompañamiento ante siniestros o solicitudes de indemnización, 
		conectando digitalmente a los usuarios con compañías aseguradoras 
		asociadas e incorporando planes de suscripción propios para ofrecer 
		distintos niveles de beneficios dentro de la plataforma.
      </td>
      <td>
        SeguroSimple es un corredor digital de seguros peruano especializado
        principalmente en seguros vehiculares. Su plataforma permite cotizar
        alternativas de diferentes aseguradoras y brinda asesoría antes,
        durante y después de la contratación, incluyendo apoyo durante
        siniestros y renovaciones (SeguroSimple.com, s.f.).
      </td>
      <td>
        QuePlan es una plataforma digital orientada principalmente a la
        comparación y contratación de seguros de salud y seguros para
        empresas. Permite comparar productos de diferentes aseguradoras,
        visualizar coberturas y precios y recibir orientación durante el
        proceso de selección (QuePlan, s.f.).
      </td>
      <td>
        Seguros Falabella comercializa diferentes categorías de seguros
        mediante canales digitales y presenciales. Su oferta incluye seguros
        vehiculares, seguros de vida, SOAT, viajes y otros productos
        proporcionados por distintas compañías aseguradoras
        (Seguros Falabella, s.f.).
      </td>
    </tr>
    <tr>
      <td>
        <strong>Ventaja competitiva</strong><br>
        ¿Qué valor ofrece a los clientes?
      </td>
      <td>
        Livva Care busca diferenciarse mediante una experiencia especializada 
		inicialmente en seguros vehiculares y de vida, manteniendo continuidad
		digital durante diferentes etapas del ciclo del seguro. La propuesta 
		combina intermediación, gestión posterior de pólizas, acompañamiento ante
		eventos relacionados con la cobertura y planes de suscripción propios que
		permiten ofrecer distintos niveles de beneficios a los usuarios.
	  </td>
      <td>
        Permite comparar alternativas de distintas aseguradoras para seguros
        vehiculares y ofrece acompañamiento especializado durante el proceso
        de cotización, contratación, siniestro y renovación. También comunica
        una propuesta centrada en facilitar la elección y encontrar condiciones
        competitivas para el cliente.
      </td>
      <td>
        Permite comparar planes y coberturas de diferentes aseguradoras desde
        una única plataforma. La propuesta destaca la comparación imparcial,
        el acceso gratuito para el usuario y la posibilidad de recibir
        orientación adicional cuando sea necesaria.
      </td>
      <td>
        Combina una amplia variedad de productos aseguradores con el
        reconocimiento y ecosistema comercial de Falabella. Además, ofrece
        contratación digital de determinados productos y un portal en el que
        los clientes pueden consultar seguros, realizar pagos y registrar
        siniestros.
      </td>
    </tr>
    <tr>
      <th rowspan="2">Perfil de Marketing</th>
      <td>
        <strong>Mercado objetivo</strong>
      </td>
      <td>
        Propietarios de vehículos particulares interesados en contratar o
		gestionar seguros vehiculares y personas mayores de edad interesadas
		en contratar o gestionar seguros de vida para proteger económicamente
		a sus familiares o beneficiarios.
      </td>
      <td>
        Principalmente propietarios y conductores de vehículos interesados
        en comparar y contratar seguros vehiculares ofrecidos por diferentes
        compañías aseguradoras.
      </td>
      <td>
        Personas interesadas principalmente en seguros de salud y empresas
        que requieren productos como EPS, SCTR, responsabilidad civil,
        seguros colectivos y otras coberturas empresariales.
      </td>
      <td>
        Consumidores del mercado peruano interesados en productos como
        seguros vehiculares, seguros de vida, SOAT, seguros de viaje y otras
        coberturas, incluyendo usuarios relacionados con el ecosistema
        Falabella.
      </td>
    </tr>
    <tr>
      <td>
        <strong>Estrategias de marketing</strong>
      </td>
      <td>
        Se plantea utilizar presencia digital, contenido educativo relacionado
		con seguros vehiculares y de vida, comunicación clara sobre coberturas 
		y procesos, demostraciones de la plataforma y comunicación de los 
		beneficios incluidos en los diferentes planes de Livva. Los call-to-action 
		del Landing Page estarán orientados a dirigir a cada segmento hacia su
		flujo correspondiente dentro de la Web Application.
      </td>
      <td>
        Utiliza la cotización gratuita como mecanismo de captación, comunica
        la posibilidad de comparar aseguradoras y enfatiza elementos como
        ahorro, rapidez y asesoría especializada durante el proceso.
      </td>
      <td>
        Utiliza herramientas de comparación, contenido educativo,
        posicionamiento digital y comunicación basada en facilidad,
        transparencia y gratuidad para captar usuarios interesados en seguros.
      </td>
      <td>
        Utiliza campañas digitales, promociones, beneficios comerciales,
        presencia dentro del ecosistema Falabella y canales complementarios
        como web, atención telefónica y WhatsApp.
      </td>
    </tr>
    <tr>
      <th rowspan="3">Perfil de Producto</th>
      <td>
        <strong>Productos &amp; Servicios</strong>
      </td>
      <td>
        Livva plantea ofrecer intermediación digital de seguros vehiculares
		y de vida, registro y seguimiento de solicitudes, consulta centralizada
		de pólizas, gestión de beneficiarios, recordatorios relacionados con 
		la vigencia y renovación, acompañamiento ante siniestros o solicitudes
		de indemnización, notificaciones y planes de suscripción con beneficios
		diferenciados dentro de la plataforma.
      </td>
      <td>
        Cotización y comparación de seguros vehiculares de diferentes
        aseguradoras, acompañamiento durante la contratación, orientación
        frente a siniestros y soporte durante el proceso de renovación.
      </td>
      <td>
        Comparación y contratación de seguros de salud y soluciones dirigidas
        a empresas, incluyendo EPS, SCTR, responsabilidad civil, vida ley,
        accidentes personales y otros productos empresariales.
      </td>
      <td>
        Seguros vehiculares, seguros de vida, SOAT, seguros de viaje,
        protección de tarjetas y otros productos comercializados mediante
        compañías aseguradoras asociadas.
      </td>
    </tr>
    <tr>
      <td>
        <strong>Precios &amp; Costos</strong>
      </td>
      <td>
        El precio final de cada seguro dependerá de las condiciones establecidas
		por la compañía aseguradora correspondiente. Livva Care plantea obtener
		ingresos derivados de la intermediación de los seguros gestionados mediante
		la plataforma y mediante planes de suscripción dirigidos a los usuarios de
		Livva, cuyos precios dependerán del nivel de beneficios digitales ofrecidos.
      </td>
      <td>
        La cotización depende de factores como las características del
        vehículo, perfil del conductor y compañía aseguradora seleccionada.
        SeguroSimple indica que el proceso de cotización es gratuito para el
        usuario y que los pagos se realizan directamente a la aseguradora.
      </td>
      <td>
        Los precios dependen del seguro, cobertura, aseguradora y
        características del usuario o empresa. QuePlan indica que el uso de
        su plataforma de comparación no genera un costo para el usuario.
      </td>
      <td>
        Los precios varían de acuerdo con el producto, las condiciones del
        asegurado y la compañía aseguradora correspondiente. Determinados
        productos pueden incluir promociones o beneficios asociados al
        ecosistema Falabella.
      </td>
    </tr>
    <tr>
      <td>
        <strong>Canales de distribución</strong><br>
        (Web y/o Móvil)
      </td>
      <td>
        Landing Page y Web Application responsive accesibles mediante
        Internet.
      </td>
      <td>
        Plataforma web complementada con atención telefónica y asesoría
        durante el proceso de contratación.
      </td>
      <td>
        Plataforma web y portal para clientes, complementados con canales
        digitales y atención mediante asesores.
      </td>
      <td>
        Plataforma web, portal de clientes, canales del ecosistema Falabella,
        WhatsApp, atención telefónica y determinados puntos de atención
        presenciales.
      </td>
    </tr>
    <tr>
      <th colspan="2">Análisis SWOT</th>
      <td colspan="4">
        Se realiza el análisis para Livva Care y sus competidores. Las
        fortalezas de Livva Care deben apoyar sus oportunidades y contribuir
        a la posible ventaja competitiva de la propuesta.
      </td>
    </tr>
    <tr>
      <th rowspan="4">Análisis SWOT</th>
      <td>
        <strong>Fortalezas</strong>
      </td>
      <td>
        <ul>
          <li>Especialización inicial en seguros vehiculares y de vida.</li>
          <li>Propuesta orientada a distintas etapas del ciclo del seguro.</li>
          <li>Orientación tanto al asegurado como a las compañías aseguradoras.</li>
          <li>Propuesta B2B mediante herramientas de gestión para aseguradoras.</li>
          <li>Experiencia digital diseñada desde el inicio para canales web responsive.</li>
        </ul>
      </td>
      <td>
        <ul>
  		  <li>Especialización inicial en seguros vehiculares y de vida.</li>
  		  <li>Propuesta orientada a distintas etapas del ciclo del seguro.</li>
  		  <li>Centralización de pólizas, documentación y procesos relacionados con la gestión posterior.</li>
  		  <li>Modelo de servicio que combina intermediación con planes de suscripción dirigidos a los usuarios.</li>
  		  <li>Experiencia digital diseñada desde el inicio para canales web responsive.</li>
	    </ul>
      </td>
      <td>
        <ul>
          <li>Comparación de productos de diferentes aseguradoras.</li>
          <li>Plataforma gratuita para el usuario.</li>
          <li>Oferta tanto para personas como para empresas.</li>
          <li>Proceso de comparación digital.</li>
          <li>Presencia regional.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Reconocimiento de la marca Falabella.</li>
          <li>Amplia variedad de productos aseguradores.</li>
          <li>Acceso a diferentes compañías aseguradoras.</li>
          <li>Portal digital para clientes.</li>
          <li>Integración con un ecosistema comercial y financiero establecido.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <strong>Debilidades</strong>
      </td>
      <td>
        <ul>
  		  <li>Startup nueva y todavía en etapa de desarrollo.</li>
 		  <li>Ausencia inicial de reconocimiento de marca.</li>
  		  <li>Dependencia de relaciones y acuerdos con compañías aseguradoras.</li>
		  <li>Catálogo inicial limitado a seguros vehiculares y de vida.</li>
		  <li>Necesidad de validar qué beneficios generan suficiente valor para justificar una suscripción por parte de los usuarios.</li>
	    </ul>
      </td>
      <td>
        <ul>
          <li>Su posicionamiento visible está fuertemente concentrado en seguros vehiculares.</li>
          <li>La finalización de la contratación puede requerir participación de un asesor.</li>
          <li>Parte de la experiencia depende posteriormente de los procesos de cada aseguradora.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Su propuesta actual está fuertemente orientada a salud y seguros empresariales.</li>
          <li>Parte del valor de la plataforma se concentra en la comparación de productos.</li>
          <li>La experiencia final también depende de las aseguradoras cuyos productos comercializa.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>La amplitud de su catálogo reduce la especialización en seguros vehiculares y de vida.</li>
          <li>La experiencia se distribuye entre diferentes productos y canales.</li>
          <li>Parte de su diferenciación está vinculada al ecosistema Falabella.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <strong>Oportunidades</strong>
      </td>
      <td>
        <ul>
 	      <li>Mayor adopción de canales digitales para contratar y gestionar seguros.</li>
		  <li>Creciente interés de los usuarios por experiencias digitales de autoservicio.</li>
		  <li>Digitalización de procesos tradicionalmente asistidos.</li>
		  <li>Incorporación progresiva de nuevas líneas de seguros después de validar el producto inicial.</li>
		  <li>Desarrollo de servicios de valor agregado mediante planes de suscripción.</li>
		</ul>
      </td>
      <td>
        <ul>
          <li>Expandir sus procesos digitales posteriores a la contratación.</li>
          <li>Incorporar nuevas categorías de seguros.</li>
          <li>Incrementar funcionalidades de autoservicio.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Expandirse hacia nuevas categorías de seguros personales.</li>
          <li>Incrementar servicios digitales autoservidos.</li>
          <li>Ampliar productos dirigidos al mercado empresarial.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Aprovechar aún más la base de usuarios del ecosistema Falabella.</li>
          <li>Incrementar los procesos completamente digitales.</li>
          <li>Desarrollar experiencias más personalizadas.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <strong>Amenazas</strong>
      </td>
      <td>
        <ul>
          <li>Presencia de corredores digitales ya consolidados.</li>
          <li>Fortalecimiento de los canales digitales propios de las aseguradoras.</li>
          <li>Dificultad inicial para construir confianza.</li>
          <li>Entrada de nuevas soluciones InsurTech.</li>
          <li>Restricciones y obligaciones regulatorias relacionadas con la intermediación de seguros.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Aseguradoras que fortalezcan sus canales de venta directa.</li>
          <li>Nuevas plataformas InsurTech especializadas.</li>
          <li>Mayor competencia en servicios digitales de comparación.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Competidores con mayor especialización en determinadas categorías.</li>
          <li>Venta directa mediante plataformas de las aseguradoras.</li>
          <li>Nuevos comparadores y corredores digitales.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>InsurTechs con experiencias más especializadas y ágiles.</li>
          <li>Mayor capacidad digital de las propias compañías aseguradoras.</li>
          <li>Consumidores que prefieran contratar directamente con la aseguradora.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

El análisis SWOT evidencia que Livva Care se encuentra en una posición diferente a la de sus principales competidores debido a que se trata de una propuesta nueva que todavía debe desarrollar reconocimiento, confianza y relaciones con compañías aseguradoras.

Esta condición representa una debilidad inicial frente a empresas que ya poseen experiencia, canales establecidos y relaciones comerciales dentro del sector. Sin embargo, también permite que Livva Care diseñe su propuesta desde el inicio alrededor de una experiencia digital especializada.

Entre las principales oportunidades identificadas se encuentra la posibilidad de proporcionar una experiencia continua durante diferentes etapas del ciclo del seguro, incrementar las capacidades de autoservicio y desarrollar beneficios digitales adicionales que puedan ofrecerse mediante planes de suscripción de Livva.

De esta manera, la propuesta busca diferenciarse no solamente durante el proceso inicial de contratación, sino también mediante funcionalidades útiles durante la gestión posterior de los seguros.

Por otra parte, una de las principales amenazas corresponde al fortalecimiento de los canales digitales propios de las aseguradoras y a la presencia de corredores digitales con mayor experiencia dentro del mercado.

Las fortalezas y debilidades atribuidas a los competidores corresponden al análisis realizado a partir de las características observadas en sus propuestas digitales. Las oportunidades y amenazas representan una interpretación estratégica realizada por el equipo sobre el contexto competitivo.


### 2.1.2. Estrategias y tácticas frente a competidores

A partir del análisis competitivo realizado, Livva Care plantea las siguientes estrategias y tácticas preliminares para posicionar a Livva frente a las soluciones identificadas. Estas propuestas buscan aprovechar las oportunidades del mercado, utilizar las fortalezas de Livva, responder a las fortalezas de los competidores y aprovechar las limitaciones identificadas en sus propuestas.

#### 1. Aprovechar la fortaleza: especialización en seguros vehiculares y de vida

**Estrategia**

Posicionar a Livva como una plataforma especializada inicialmente en la intermediación y gestión digital de seguros vehiculares y de vida, evitando competir únicamente mediante la cantidad de productos o compañías aseguradoras disponibles.

La propuesta busca concentrarse en dos tipos de seguros y mantener una experiencia digital que acompañe al usuario durante diferentes etapas, desde la solicitud inicial hasta la consulta de pólizas, renovaciones y seguimiento de siniestros.

**Tácticas**

- **Flujos especializados por tipo de seguro:** diseñar procesos diferenciados para seguros vehiculares y seguros de vida, considerando la información y necesidades particulares de cada producto.
- **Terminología clara:** utilizar conceptos propios del dominio asegurador de manera consistente, acompañados de explicaciones comprensibles para usuarios que no poseen conocimientos especializados.
- **Gestión posterior a la contratación:** incorporar funcionalidades relacionadas con consulta de pólizas, beneficiarios, renovaciones, documentación y seguimiento de siniestros.
- **Priorización del alcance:** concentrar las primeras versiones de Livva en las funcionalidades de mayor valor para los segmentos objetivo antes de incorporar nuevas categorías de seguros.
- **Validación con usuarios:** utilizar las entrevistas y posteriormente las Validation Interviews para identificar cuáles de estas funcionalidades generan mayor valor.

**Valor añadido**

- Mayor adaptación de la experiencia a los seguros vehiculares y de vida.
- Reducción de funcionalidades innecesarias durante las primeras etapas del producto.
- Mayor continuidad entre la contratación y la gestión posterior del seguro.
- Experiencia más clara para usuarios que requieren comprender coberturas, pólizas y procedimientos relacionados con sus seguros.

#### 2. Aprovechar las debilidades de competidores: experiencias centradas en comparación y amplitud de productos

**Estrategia**

Diferenciar a Livva de plataformas cuya propuesta se concentra principalmente en comparar alternativas o comercializar una amplia variedad de productos, priorizando una experiencia especializada y continua durante el ciclo de vida del seguro.

SeguroSimple concentra gran parte de su propuesta digital en la comparación y contratación de seguros vehiculares de distintas aseguradoras, aunque también brinda acompañamiento durante siniestros y renovaciones (SeguroSimple.com, s.f.). Por su parte, QuePlan utiliza la comparación de precios, coberturas y aseguradoras como uno de los principales elementos de su propuesta, especialmente en seguros de salud y productos dirigidos a empresas (QuePlan, s.f.).

**Tácticas**

- **Centralización de información:** mantener solicitudes, pólizas, beneficiarios, documentos, renovaciones y registros relacionados con siniestros dentro de una misma plataforma.
- **Autoservicio digital:** permitir que el usuario consulte el estado de sus operaciones y actualice determinada información sin depender constantemente de la intervención de un asesor.
- **Experiencia posterior a la contratación:** mantener funcionalidades útiles durante la vigencia de la póliza y no limitar la interacción al proceso inicial de cotización.
- **Especialización antes que amplitud:** incorporar nuevas categorías de seguros únicamente cuando los productos iniciales hayan sido validados con los segmentos objetivo.
- **Comunicación orientada a comprensión:** presentar coberturas y condiciones utilizando información estructurada y lenguaje comprensible.

**Valor añadido**

- Menor dispersión de información entre distintos canales y etapas.
- Mayor capacidad de autoservicio para el usuario.
- Utilidad de Livva después de finalizar la contratación.
- Experiencia enfocada en comprender y gestionar la protección contratada, además de adquirirla.

#### 3. Afrontar las fortalezas de competidores consolidados

**Estrategia**

Frente a la experiencia, reconocimiento y relaciones comerciales previamente establecidas por SeguroSimple, QuePlan y Seguros Falabella, Livva Care buscará construir confianza mediante especialización, transparencia, trazabilidad y una experiencia digital consistente.

SeguroSimple se presenta como un corredor especializado en seguros vehiculares y trabaja con diferentes compañías aseguradoras, acompañando al usuario durante cotización, contratación, siniestro y renovación (SeguroSimple.com, s.f.). QuePlan permite comparar alternativas de diferentes compañías y comunica una propuesta basada en facilitar la comprensión y elección de los productos disponibles (QuePlan, s.f.). Seguros Falabella cuenta con una oferta amplia de seguros, incluyendo productos vehiculares y de vida, además de un portal en el que sus clientes pueden consultar seguros, realizar pagos y registrar siniestros (Seguros Falabella, s.f.).

**Tácticas**

- **Seguimiento de operaciones:** mostrar claramente al usuario el estado de solicitudes, pólizas, renovaciones y procesos relacionados con siniestros.
- **Historial centralizado:** conservar información relevante sobre las operaciones realizadas mediante Livva.
- **Transparencia de responsabilidades:** diferenciar claramente qué actividades corresponden a Livva como intermediario y cuáles corresponden a la compañía aseguradora.
- **Experiencia consistente:** mantener coherencia de contenido, navegación y comunicación entre el Landing Page y la Web Application.
- **Mejora basada en retroalimentación:** incorporar progresivamente cambios a partir de los resultados de Needfinding y Validation Interviews.
- **Transparencia de planes:** comunicar claramente las diferencias entre el servicio base y los beneficios adicionales de cada suscripción, evitando que el usuario confunda una suscripción de Livva con una póliza de seguro.

**Valor añadido**

- Mayor visibilidad sobre el estado de las operaciones relacionadas con el seguro.
- Reducción de incertidumbre durante procesos que pueden involucrar distintas etapas.
- Construcción progresiva de confianza mediante información clara y trazable.
- Experiencia coherente durante los diferentes puntos de contacto digitales de Livva.

#### 4. Aprovechar la oportunidad: relación continua mediante planes de suscripción

**Estrategia**

Desarrollar una propuesta de valor que permita mantener una relación continua con los usuarios más allá del proceso inicial de solicitud del seguro, ofreciendo beneficios digitales adicionales mediante planes de suscripción propios de Livva.

La suscripción no sustituye al seguro ni modifica las responsabilidades de las compañías aseguradoras. Corresponde a un servicio independiente ofrecido por Livva para proporcionar diferentes niveles de acompañamiento y funcionalidades dentro de la plataforma.

**Tácticas**

- **Planes claramente diferenciados:** establecer un número reducido de planes cuyos beneficios puedan compararse con facilidad.
- **Información transparente:** mostrar precio, periodicidad, beneficios y condiciones antes de la contratación.
- **Gestión autoservida:** permitir que los usuarios consulten el estado de su suscripción y puedan cancelarla sin intervención de personal de soporte.
- **Integración con servicio externo:** utilizar un proveedor de pagos en ambiente de prueba para soportar el proceso de activación de la suscripción.
- **Validación del valor:** utilizar entrevistas y sesiones de validación para identificar qué beneficios adicionales son realmente valorados.
- **Alcance progresivo:** evitar incluir funcionalidades financieras avanzadas durante la primera versión del producto.

**Valor añadido**

- Fuente adicional de ingresos recurrentes para Livva.
- Mayor continuidad en la relación con los usuarios.
- Posibilidad de ofrecer diferentes niveles de servicio.
- Mayor capacidad para validar qué funcionalidades generan valor recurrente.
- Integración de un servicio externo dentro del modelo funcional del producto.

## 2.2. Entrevistas

Con el propósito de comprender mejor las necesidades, dificultades y comportamientos de los potenciales usuarios de Livva, se realizarán entrevistas a personas que formen parte de los dos segmentos objetivo definidos para el proyecto.

Estas entrevistas permitirán obtener información cualitativa sobre la forma en que los usuarios buscan, contratan y administran actualmente sus seguros, así como identificar dificultades relacionadas con la comprensión de coberturas, documentación, renovaciones, beneficiarios y atención ante siniestros.

Los resultados obtenidos servirán para contrastar las suposiciones planteadas previamente durante el Lean UX Process y determinar cuáles de las funcionalidades propuestas para Livva generan mayor valor para los usuarios.

Los segmentos seleccionados para las entrevistas son:

- Propietarios de vehículos particulares interesados en seguros vehiculares.
- Personas interesadas en contratar o gestionar seguros de vida.

### 2.2.1. Diseño de entrevistas

Las entrevistas serán semiestructuradas, es decir, se tendrá una lista de preguntas preparadas, pero también se podrán realizar preguntas adicionales dependiendo de las respuestas del entrevistado.

El objetivo es conocer experiencias reales relacionadas con los seguros y encontrar necesidades que puedan ser tomadas en cuenta durante el desarrollo de Livva.

#### Segmento 1: Propietarios de vehículos particulares

**Perfil del entrevistado:**

Personas mayores de edad que tengan un automóvil o camioneta particular y que actualmente tengan un seguro vehicular, hayan tenido uno anteriormente o estén interesados en contratar uno.

**Objetivos:**

- Conocer cómo buscan y contratan seguros vehiculares.
- Identificar problemas durante la contratación.
- Conocer cómo administran actualmente su póliza.
- Identificar dificultades relacionadas con renovaciones y siniestros.
- Conocer qué funciones esperan de una plataforma digital de seguros.

**Preguntas:**

1. ¿Actualmente tienes o has tenido un seguro vehicular?

2. ¿Cómo buscaste o buscarías información para contratar un seguro para tu vehículo?

3. ¿Qué aspectos consideras más importantes al elegir un seguro vehicular?

4. ¿Has utilizado alguna página web para cotizar o comparar seguros? ¿Cómo fue tu experiencia?

5. ¿Qué dificultades has encontrado al momento de contratar o entender un seguro vehicular?

6. ¿Cómo consultas actualmente la información de tu póliza y tus coberturas?

7. ¿Has tenido algún accidente o siniestro? Si es así, ¿cómo fue el proceso con la aseguradora?

8. ¿Te gustaría recibir recordatorios sobre renovaciones, vencimientos o información pendiente?

9. ¿Te sería útil tener tus pólizas, documentos y coberturas en una sola plataforma?

10. ¿Qué función consideras más importante en una plataforma para gestionar tu seguro vehicular?

---

#### Segmento 2: Personas interesadas en seguros de vida

**Perfil del entrevistado:**

Personas mayores de edad que tengan actualmente un seguro de vida, hayan considerado contratar uno o estén interesadas en proteger económicamente a sus familiares o beneficiarios.

**Objetivos:**

- Conocer qué saben los usuarios sobre los seguros de vida.
- Identificar dificultades para comprender este tipo de seguro.
- Conocer qué factores consideran antes de contratar.
- Identificar necesidades relacionadas con la gestión de beneficiarios.
- Conocer qué funciones podrían ser útiles en una plataforma digital.

**Preguntas:**

1. ¿Actualmente tienes un seguro de vida o alguna vez has pensado en contratar uno?

2. ¿Qué sabes sobre el funcionamiento de un seguro de vida?

3. ¿Dónde buscarías información antes de contratar un seguro de vida?

4. ¿Qué aspectos considerarías más importantes al elegir un seguro de vida?

5. ¿Te resulta fácil entender conceptos como cobertura, monto asegurado y beneficiarios?

6. Si ya tienes un seguro de vida, ¿cómo consultas actualmente la información de tu póliza?

7. ¿Consideras fácil revisar o actualizar la información de tus beneficiarios?

8. ¿Te gustaría recibir recordatorios o notificaciones relacionadas con tu seguro?

9. ¿Te sería útil tener tus documentos, coberturas y beneficiarios en una sola plataforma?

10. ¿Qué función consideras más importante en una plataforma para gestionar un seguro de vida?

---

### 2.2.2. Registro de entrevistas

#### Registro de entrevistas del Segmento 1: Propietarios de vehículos particulares

| Entrevista | Nombres y apellidos | Edad | Distrito | Ocupación / cargo | Situación relacionada | Screenshot | Timing | Duración |
|---|---|---:|---|---|---|---|---|---|
| E01 | Carlos Alberto Lozano | 23 | Comas | Estudiante | Propietario de vehículo particular con seguro vehicular vigente | ![Carlos Lozano](assets/md-images-interviews/ss_CarlosLozano.PNG) | 00:00:00 - 00:03:50 | 03:50 |
| E02 | Yul Rivaldo Muñoz Bornás | 25 | Ate | Practicante de redes | Propietario de vehículo particular con seguro vehicular vigente; utiliza su vehículo principalmente para trasladarse | ![Rivaldo Muñoz](assets/md-images-interviews/ss_RivaldoMunoz.PNG) | 00:03:50 - 00:09:01 | 05:11 |
| E03 | Diego Miranda | 22 | Surquillo | Estudiante | Propietario de vehículo particular sin experiencia previa contratando seguros vehiculares | ![Diego Miranda](assets/md-images-interviews/ss_DiegoMiranda.PNG) | 00:09:01 - 00:13:21 | 04:20 |

#### Registro de entrevistas del Segmento 2: Personas interesadas en seguros de vida

| Entrevista | Nombres y apellidos | Edad | Distrito | Ocupación / cargo | Situación relacionada | Screenshot | Timing | Duración |
|---|---|---:|---|---|---|---|---|---|
| E04 | Azul Delgado Sanchez | 23 | Santiago de Surco | Estudiante universitario | Persona interesada en contratar un seguro de vida | ![Azul Delgado](assets/md-images-interviews/ss_AzulDelgado.png) | 00:13:21 - 00:19:36 | 06:15 |
<!-- | E05 | [Completar] | [Completar] | [Completar] | [Completar] | Persona interesada en contratar un seguro de vida | [Insertar imagen] | [Completar] | [mm:ss] |
| E06 | [Completar] | [Completar] | [Completar] | [Completar] | Persona interesada en contratar un seguro de vida | [Insertar imagen] | [Completar] | [mm:ss] |
-->

[Video de las entrevisas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321613_upc_edu_pe/IQDQawos-xc4RYxiC7U-FhUTARuGivS7Xwl13O9kQM_d4cY?e=rKwrYC)

### 2.2.3. Análisis de entrevistas

| Segmento | Variable de análisis | Resultado preliminar | Sustento |
|---|---|---|---|
| Propietarios de vehículos particulares | Dificultad para comparar coberturas, precios y condiciones entre aseguradoras | Sí, la información se encuentra distribuida entre páginas web, correos y conversaciones de WhatsApp, lo que dificulta comparar las alternativas disponibles | Entrevista E01 |
| Propietarios de vehículos particulares | Interés en centralizar la gestión del seguro vehicular | Sí, considera útil consultar pólizas, documentos, coberturas, vigencia y estado de siniestros desde una sola plataforma | Entrevista E01 |
| Propietarios de vehículos particulares | Dificultad para comprender términos y condiciones del seguro | Sí, algunas coberturas y condiciones utilizan términos técnicos que requieren ser revisados varias veces para comprenderlos | Entrevista E02 |
| Propietarios de vehículos particulares | Necesidad de recordatorios y seguimiento de renovaciones | Sí, estuvo cerca de superar la fecha de renovación y considera útiles las notificaciones para mantener vigente su seguro | Entrevista E02 |
| Propietarios de vehículos particulares | Necesidad de acompañamiento durante la primera contratación de un seguro | Sí, al no tener experiencia previa, requiere un proceso guiado que explique los requisitos, coberturas y pasos de contratación | Entrevista E03 |
| Propietarios de vehículos particulares | Preferencia por revisar las opciones antes de proporcionar datos personales | Sí, muestra incomodidad cuando las páginas solicitan información personal antes de presentar claramente los seguros y coberturas disponibles | Entrevista E03 |
| Personas interesadas en seguros de vida | Dificultad para comprender coberturas y condiciones de los seguros de vida | Sí presenta dificultad con términos técnicos como exclusiones y condiciones de cobertura | Entrevista E04 |
| Personas interesadas en seguros de vida | Interés en comparar distintas opciones de seguros de vida | Sí, considera importante comparar precios, coberturas y beneficios | Entrevista E04 |
| Personas interesadas en seguros de vida | Necesidad de registrar y gestionar beneficiarios de manera sencilla | Sí, considera útil realizar este proceso de forma digital | Entrevista E04 |
| Personas interesadas en seguros de vida | Interés en consultar solicitudes, pólizas y beneficios desde una plataforma digital | Sí, muestra interés en gestionar pólizas, documentos, beneficiarios y notificaciones desde una sola plataforma | Entrevista E04 |

## 2.3. Needfinding

### 2.3.1. User Personas

- Segmento 1 – Propietarios de vehículos particulares
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b9c99fc6-286a-4820-a0f5-c6eaa5d283c3" />

- Segmento 2 - Personas interesadas en seguros de vida
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9c0deac4-6b6a-4bd4-b25c-786ce5420b4f" />

### 2.3.2. User Task Matrix

A partir de las entrevistas realizadas, se identificaron las principales tareas que realizan actualmente los usuarios de cada segmento para buscar, contratar y gestionar sus seguros. Para cada tarea se considera su frecuencia aproximada y el nivel de importancia que representa dentro de la experiencia del usuario.

#### Segmento 1: Propietarios de vehículos particulares

| Tarea principal | Frecuencia | Importancia |
|---|---|---|
| Buscar información sobre seguros vehiculares | Ocasional | Alta |
| Comparar precios, coberturas, deducibles y condiciones | Ocasional | Alta |
| Consultar páginas de aseguradoras, comparadores o corredores | Ocasional | Alta |
| Solicitar orientación a conocidos, asesores o compañías aseguradoras | Ocasional | Media |
| Resolver dudas sobre coberturas, exclusiones y términos del seguro | Ocasional | Alta |
| Revisar la póliza y sus coberturas | Ocasional | Alta |
| Buscar y consultar documentos relacionados con el seguro | Ocasional | Alta |
| Verificar la vigencia del seguro | Ocasional | Alta |
| Gestionar la renovación del seguro | Anual | Alta |
| Revisar avisos sobre vencimientos, renovaciones o información pendiente | Ocasional | Alta |
| Comunicarse con la aseguradora ante un accidente o siniestro | Rara | Muy alta |
| Consultar los pasos que debe seguir ante un siniestro | Rara | Muy alta |
| Dar seguimiento al estado de un siniestro o solicitud | Rara | Muy alta |

**Notas:**  
En este segmento se observa que la búsqueda y comparación de información adquiere mayor relevancia durante la contratación o renovación del seguro. Los entrevistados también presentan dificultades para comprender determinados términos, coberturas y exclusiones, además de mantener la documentación distribuida entre distintos canales. Aunque los siniestros ocurren con poca frecuencia, las tareas relacionadas con su atención y seguimiento presentan una importancia muy alta debido a la necesidad de actuar correctamente ante estas situaciones.

---

#### Segmento 2: Personas interesadas en seguros de vida

| Tarea principal | Frecuencia | Importancia |
|---|---|---|
| Buscar información sobre seguros de vida | Ocasional | Alta |
| Comparar cobertura, costo, monto asegurado y condiciones | Ocasional | Alta |
| Consultar páginas de aseguradoras y otras fuentes digitales | Ocasional | Alta |
| Solicitar orientación a asesores para resolver dudas | Ocasional | Media |
| Comprender conceptos como cobertura, monto asegurado, exclusiones y beneficiarios | Ocasional | Alta |
| Revisar la información de la póliza | Ocasional | Alta |
| Buscar y consultar documentos relacionados con el seguro | Ocasional | Alta |
| Consultar la información de los beneficiarios | Ocasional | Alta |
| Solicitar cambios o actualización de beneficiarios | Rara | Alta |
| Verificar que la información personal y de beneficiarios esté actualizada | Ocasional | Alta |
| Revisar avisos relacionados con vigencia, pagos o información pendiente | Ocasional | Alta |
| Consultar los pasos necesarios ante una eventual solicitud de indemnización | Rara | Muy alta |
| Dar seguimiento a una solicitud de indemnización | Rara | Muy alta |

**Notas:**  
En este segmento destaca la necesidad de comprender correctamente las condiciones del seguro de vida y mantener organizada la información relacionada con la póliza y los beneficiarios. Los entrevistados recurren principalmente a canales digitales y, cuando existen dudas, pueden buscar orientación adicional mediante asesores. Las tareas asociadas con una eventual indemnización presentan baja frecuencia, pero una importancia muy alta debido al impacto que tienen para los beneficiarios.

### 2.3.3. User Journey Mapping

Segmento 1: Propietarios de vehículos particulares

<img width="1645" height="860" alt="image" src="https://github.com/user-attachments/assets/bbf9d24a-5f85-4cae-9f3b-9ea8d7c4f963" />

Segmento 2: Personas interesadas en seguros de vida

<img width="1649" height="862" alt="image" src="https://github.com/user-attachments/assets/ccf46038-ce30-4550-addb-66726ef21a36" />



### 2.3.4. Empathy Mapping

Empathy Map - Segmento 1

<img width="1050" height="1318" alt="Empathy Map - Propietarios de vehículos particulares" src="https://github.com/user-attachments/assets/c57d91db-2368-4c9c-a6a4-661cf64777c2" />

Empathy Map - Segmento 2

<img width="1050" height="1408" alt="Empathy map" src="https://github.com/user-attachments/assets/f2724724-6762-43be-9140-3744f0961c97" />


## 2.4. Big Picture EventStorming

El Big Picture EventStorming de Livva fue elaborado colaborativamente con el objetivo de comprender el dominio general de la intermediación y gestión digital de seguros vehiculares y de vida. Durante la sesión se identificaron los principales eventos de negocio que ocurren desde la solicitud de un seguro hasta la gestión posterior de pólizas, renovaciones, siniestros, indemnizaciones y suscripciones.

El modelado se desarrolló desde una perspectiva de negocio, identificando Domain Events, actores, sistemas externos, reglas de negocio y hotspots. Se evitó incorporar elementos técnicos propios del diseño de software, debido a que estos serán desarrollados posteriormente en el Design-Level EventStorming.

### Big Picture EventStorming

![Livva Big Picture EventStorming](assets/md-big-picture-event-storming/big-picture-event-storming.PNG)

El modelo muestra dos recorridos principales: seguros vehiculares y seguros de vida. En ambos casos, Livva facilita la solicitud y gestión digital, mientras que las compañías aseguradoras participan como entidades externas responsables de procesos como evaluación, emisión de pólizas, renovaciones y resolución de siniestros o indemnizaciones.

Después de la emisión de una póliza se identifica un ciclo común relacionado con su vigencia y renovación. Para seguros vehiculares se representa adicionalmente el registro y seguimiento de siniestros, mientras que en seguros de vida se diferencia el proceso de solicitud de indemnización realizado por los beneficiarios.

De manera transversal, se representa el proceso de suscripciones de Livva, desde la selección del plan hasta su activación o cancelación. Este flujo se mantiene separado de las pólizas de seguro, ya que una Livva Subscription representa un servicio de la plataforma y no un producto emitido por una aseguradora.

Finalmente, durante el modelado se identificaron hotspots relacionados con la sincronización de decisiones de las aseguradoras, información requerida para las solicitudes, validación de beneficiarios, estados de seguimiento y definición de beneficios de los planes. Estos puntos serán refinados en etapas posteriores del proyecto.

## 2.5. Ubiquitous Language

El Ubiquitous Language de Livva establece un vocabulario común para describir de forma consistente los principales conceptos del dominio de intermediación y gestión digital de seguros vehiculares y de vida.

Su propósito es facilitar la comunicación entre los integrantes del equipo durante el análisis, diseño, implementación y documentación del producto, evitando utilizar diferentes términos para representar un mismo concepto del negocio.

Los términos principales se expresan en inglés con el objetivo de mantener consistencia con el código fuente y los artefactos de Domain-Driven Design. Sus definiciones se presentan en español para facilitar su comprensión dentro del equipo.

Los conceptos se encuentran agrupados por áreas del dominio. Esta clasificación no representa Bounded Contexts definitivos, ya que estos serán identificados posteriormente durante el Design-Level EventStorming.

### Actors and Roles

| Term | Definition |
|---|---|
| **Visitor** | Persona que accede a la Landing Page de Livva sin haber iniciado sesión y puede consultar información pública sobre la plataforma, seguros y planes disponibles. |
| **Registered User** | Persona que posee una cuenta registrada en Livva y puede acceder a las funcionalidades disponibles dentro de la Web Application. |
| **Vehicle Owner** | Usuario propietario de un vehículo particular que puede registrarlo en Livva para utilizarlo dentro de una solicitud de seguro vehicular. |
| **Life Insurance Applicant** | Persona interesada en solicitar un seguro de vida mediante Livva. |
| **Applicant** | Usuario que ha iniciado o presentado una Insurance Application. |
| **Policyholder** | Persona titular de una Insurance Policy y responsable de la relación contractual asociada a dicha póliza. Puede ser diferente de la Insured Person en un seguro de vida. |
| **Insured Person** | Persona cuya vida se encuentra cubierta por una Life Insurance Policy. |
| **Beneficiary** | Persona designada en una Life Insurance Policy para recibir la prestación correspondiente cuando ocurre un Covered Event que da origen a una Indemnity Request. |

### Insurance Products and Applications

| Term | Definition |
|---|---|
| **Insurance Product** | Oferta de seguro proporcionada por una Insurance Company que establece determinadas coberturas, condiciones y características. |
| **Vehicle Insurance Product** | Insurance Product diseñado para proporcionar protección asociada a un vehículo particular. |
| **Life Insurance Product** | Insurance Product orientado a proporcionar protección económica relacionada con la vida de una Insured Person y sus Beneficiaries. |
| **Insurance Application** | Solicitud presentada por un usuario para iniciar el proceso de evaluación de un Insurance Product. |
| **Vehicle Insurance Application** | Insurance Application asociada a un vehículo registrado por un Vehicle Owner. |
| **Life Insurance Application** | Insurance Application presentada por una persona interesada en contratar un Life Insurance Product. |
| **Application Status** | Estado actual de una Insurance Application durante su proceso de evaluación, por ejemplo pendiente, en evaluación, aprobada o rechazada. |

### Policies and Coverage

| Term | Definition |
|---|---|
| **Insurance Policy** | Contrato de seguro emitido por una Insurance Company que establece las condiciones, coberturas, vigencia y participantes del seguro contratado. |
| **Vehicle Insurance Policy** | Insurance Policy correspondiente a un seguro vehicular y asociada a un Insured Vehicle. |
| **Life Insurance Policy** | Insurance Policy correspondiente a un seguro de vida que establece la protección de una Insured Person y sus Beneficiaries. |
| **Coverage** | Protección o conjunto de situaciones contempladas dentro de las condiciones de un Insurance Product o Insurance Policy. |
| **Vehicle** | Vehículo particular registrado por un usuario dentro de Livva. |
| **Insured Vehicle** | Vehicle que se encuentra cubierto por una Vehicle Insurance Policy. |
| **Policy Document** | Documento asociado a una Insurance Policy que contiene o respalda información relacionada con sus condiciones, coberturas y vigencia. |
| **Policy Expiration Date** | Fecha en la que finaliza la vigencia establecida de una Insurance Policy. |
| **Renewal** | Proceso mediante el cual se busca extender la vigencia de una Insurance Policy próxima a vencer. |
| **Renewal Request** | Solicitud iniciada por un Policyholder para comenzar el proceso de renovación de una Insurance Policy. |

### Vehicle Claims and Life Indemnities

| Term | Definition |
|---|---|
| **Vehicle Incident** | Evento ocurrido a un Insured Vehicle que potencialmente puede encontrarse relacionado con una Coverage de la póliza. |
| **Vehicle Claim** | Reporte realizado por el asegurado respecto a un Vehicle Incident para iniciar el proceso correspondiente con la Insurance Company. |
| **Claim Status** | Estado que representa el progreso de un Vehicle Claim durante su evaluación y resolución. |
| **Covered Event** | Evento contemplado dentro de las condiciones de una Insurance Policy y que puede originar una solicitud relacionada con la cobertura contratada. |
| **Indemnity Request** | Solicitud presentada por un Beneficiary para iniciar el proceso correspondiente a la prestación de un seguro de vida después de un Covered Event. |
| **Indemnity Status** | Estado que representa el progreso de una Indemnity Request durante su evaluación y resolución. |

### Subscriptions and Payments

| Term | Definition |
|---|---|
| **Subscription Plan** | Nivel de servicio ofrecido directamente por Livva que define un conjunto determinado de beneficios para sus usuarios. |
| **Livva Subscription** | Relación de servicio entre un Registered User y Livva originada por la contratación de un Subscription Plan. Es independiente de cualquier Insurance Policy. |
| **Subscription Status** | Estado actual de una Livva Subscription, por ejemplo activa, pendiente de activación o cancelada. |
| **Subscription Payment** | Pago asociado exclusivamente con la contratación de un Subscription Plan de Livva. No representa el pago de una prima de seguro. |
| **Subscription Activation** | Proceso mediante el cual el Subscription Plan seleccionado pasa a encontrarse activo para el usuario después de cumplirse las condiciones correspondientes. |
| **Subscription Cancellation** | Proceso mediante el cual un usuario solicita finalizar su Livva Subscription. |

### External Participants and Shared Concepts

| Term | Definition |
|---|---|
| **Insurance Company** | Organización externa responsable de ofrecer Insurance Products, evaluar Insurance Applications, emitir Insurance Policies y resolver procesos relacionados con renovaciones, Vehicle Claims e Indemnity Requests. |
| **Payment Provider** | Servicio externo utilizado por Livva para procesar o confirmar operaciones relacionadas con un Subscription Payment. |
| **Insurance Intermediation** | Proceso mediante el cual Livva facilita la relación entre los usuarios y las Insurance Companies sin asumir las funciones propias de una compañía aseguradora. |
| **Notification** | Comunicación generada por Livva para informar al usuario sobre un evento relevante relacionado con solicitudes, pólizas, renovaciones, siniestros, indemnizaciones o suscripciones. |

### Key Domain Distinctions

Para mantener consistencia dentro del dominio de Livva se establecen las siguientes diferencias conceptuales:

- **Insurance Policy ≠ Livva Subscription:** una Insurance Policy es emitida por una Insurance Company y representa un contrato de seguro. Una Livva Subscription corresponde a un servicio contratado directamente con Livva.

- **Vehicle Claim ≠ Indemnity Request:** un Vehicle Claim representa el reporte y seguimiento de un evento relacionado con un seguro vehicular, mientras que una Indemnity Request corresponde al proceso iniciado por un Beneficiary dentro de un seguro de vida.

- **Vehicle ≠ Insured Vehicle:** un Vehicle representa un vehículo registrado dentro de Livva, mientras que un Insured Vehicle representa un vehículo que ya se encuentra cubierto por una Vehicle Insurance Policy.

- **Policyholder ≠ Insured Person:** el Policyholder es el titular de la póliza, mientras que la Insured Person es la persona cuya vida se encuentra cubierta. Dependiendo del producto, ambos roles pueden corresponder a la misma persona o a personas diferentes.

- **Livva ≠ Insurance Company:** Livva facilita la intermediación y gestión digital de seguros, mientras que la Insurance Company mantiene la responsabilidad sobre evaluación, emisión de pólizas y resolución de procesos relacionados con la cobertura.

- **Subscription Payment ≠ Insurance Premium Payment:** el Subscription Payment corresponde al pago por un servicio propio de Livva. El pago de primas de seguros no forma parte del alcance inicial del proyecto.

# Capítulo III: Requirements Specification

## 3.1. User Stories

| Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con |
|---|---|---|---|---|
| US-01 | Conocer Livva | Como visitante, deseo conocer la propuesta de Livva para determinar si la plataforma puede ayudarme a gestionar mis seguros. | **Scenario 1: Consulta de información**<br>**Given** que el visitante accede al Landing Page<br>**When** consulta la información principal de Livva<br>**Then** el sistema presenta la propuesta de valor de la plataforma.<br><br>**Scenario 2: Servicios disponibles**<br>**Given** que el visitante revisa la información de Livva<br>**When** consulta los servicios disponibles<br>**Then** el sistema informa sobre seguros vehiculares y seguros de vida. | EP-01 |
| US-02 | Consultar beneficios de Livva | Como visitante, deseo conocer los beneficios de Livva para comprender las ventajas de utilizar la plataforma. | **Scenario 1: Beneficios disponibles**<br>**Given** que el visitante consulta el Landing Page<br>**When** revisa los beneficios de Livva<br>**Then** el sistema presenta los principales beneficios del servicio. | EP-01 |
| US-03 | Consultar información de seguro vehicular | Como visitante propietario de un vehículo, deseo conocer información sobre seguros vehiculares para evaluar si se ajustan a mis necesidades. | **Scenario 1: Información disponible**<br>**Given** que el visitante está interesado en un seguro vehicular<br>**When** consulta este tipo de seguro<br>**Then** el sistema presenta su descripción y beneficios principales. | EP-01 |
| US-04 | Consultar información de seguro de vida | Como visitante interesado en seguros de vida, deseo conocer información sobre este producto para evaluar si puede proteger económicamente a mis beneficiarios. | **Scenario 1: Información disponible**<br>**Given** que el visitante está interesado en un seguro de vida<br>**When** consulta este tipo de seguro<br>**Then** el sistema presenta su descripción y beneficios principales. | EP-01 |
| US-05 | Registrar una cuenta | Como usuario nuevo, deseo registrar una cuenta para utilizar los servicios de Livva. | **Scenario 1: Registro correcto**<br>**Given** que el usuario proporciona datos válidos y un correo no registrado<br>**When** solicita crear su cuenta<br>**Then** el sistema registra la cuenta correctamente.<br><br>**Scenario 2: Correo existente**<br>**Given** que el correo ya está registrado<br>**When** el usuario intenta crear una cuenta<br>**Then** el sistema rechaza el registro. | EP-02 |
| US-06 | Iniciar sesión | Como usuario registrado, deseo iniciar sesión para acceder a mi información y gestionar mis seguros. | **Scenario 1: Credenciales correctas**<br>**Given** que el usuario posee una cuenta registrada<br>**When** proporciona credenciales válidas<br>**Then** el sistema permite el acceso. | EP-02 |
| US-07 | Consultar perfil personal | Como usuario registrado, deseo consultar mi información personal para verificar mis datos registrados. | **Scenario 1: Consulta de perfil**<br>**Given** que el usuario ha iniciado sesión<br>**When** consulta su perfil<br>**Then** el sistema presenta la información asociada a su cuenta. | EP-02 |
| US-08 | Actualizar perfil personal | Como usuario registrado, deseo actualizar mis datos personales para mantener mi información vigente. | **Scenario 1: Actualización correcta**<br>**Given** que el usuario proporciona datos válidos<br>**When** solicita actualizar su perfil<br>**Then** el sistema guarda la nueva información. | EP-02 |
| US-09 | Registrar un vehículo | Como propietario de un vehículo, deseo registrar los datos de mi vehículo para utilizarlo en una solicitud de seguro. | **Scenario 1: Registro correcto**<br>**Given** que el usuario proporciona datos válidos del vehículo<br>**When** solicita registrarlo<br>**Then** el sistema almacena el vehículo asociado a su cuenta. | EP-03 |
| US-10 | Consultar vehículos registrados | Como propietario, deseo consultar mis vehículos registrados para saber cuáles están disponibles para solicitar un seguro. | **Scenario 1: Vehículos registrados**<br>**Given** que el usuario posee vehículos registrados<br>**When** consulta sus vehículos<br>**Then** el sistema presenta los vehículos asociados a su cuenta. | EP-03 |
| US-11 | Actualizar datos de un vehículo | Como propietario, deseo actualizar los datos de mi vehículo para mantener su información correcta. | **Scenario 1: Actualización válida**<br>**Given** que el vehículo pertenece al usuario<br>**When** proporciona información válida<br>**Then** el sistema guarda los cambios. | EP-03 |
| US-12 | Solicitar seguro vehicular | Como propietario de un vehículo, deseo solicitar un seguro vehicular para proteger mi vehículo ante posibles riesgos. | **Scenario 1: Solicitud correcta**<br>**Given** que el usuario posee un vehículo registrado y proporciona los datos requeridos<br>**When** envía la solicitud<br>**Then** el sistema registra la solicitud de seguro vehicular. | EP-03 |
| US-13 | Consultar solicitud de seguro vehicular | Como propietario de un vehículo, deseo consultar mi solicitud para conocer su estado. | **Scenario 1: Solicitud existente**<br>**Given** que el usuario posee una solicitud registrada<br>**When** consulta su solicitud<br>**Then** el sistema muestra la información y su estado actual. | EP-03 |
| US-14 | Solicitar seguro de vida | Como persona interesada en protección financiera, deseo solicitar un seguro de vida para brindar respaldo económico a mis beneficiarios. | **Scenario 1: Solicitud correcta**<br>**Given** que el usuario proporciona la información requerida<br>**When** envía la solicitud<br>**Then** el sistema registra la solicitud de seguro de vida. | EP-04 |
| US-15 | Consultar solicitud de seguro de vida | Como solicitante, deseo consultar mi solicitud de seguro de vida para conocer su estado. | **Scenario 1: Solicitud existente**<br>**Given** que existe una solicitud asociada al usuario<br>**When** consulta la solicitud<br>**Then** el sistema presenta su información y estado actual. | EP-04 |
| US-16 | Registrar beneficiario | Como titular de un seguro de vida, deseo registrar un beneficiario para indicar quién recibirá la protección correspondiente. | **Scenario 1: Registro correcto**<br>**Given** que el usuario proporciona información válida del beneficiario<br>**When** solicita registrarlo<br>**Then** el sistema almacena al beneficiario. | EP-04 |
| US-17 | Consultar beneficiarios | Como titular de un seguro de vida, deseo consultar mis beneficiarios para verificar quiénes están registrados. | **Scenario 1: Beneficiarios existentes**<br>**Given** que existen beneficiarios registrados<br>**When** el usuario consulta sus beneficiarios<br>**Then** el sistema presenta la información registrada. | EP-04 |
| US-18 | Actualizar beneficiario | Como titular de un seguro de vida, deseo actualizar la información de un beneficiario para mantener sus datos vigentes. | **Scenario 1: Actualización correcta**<br>**Given** que el beneficiario pertenece al usuario<br>**When** proporciona datos válidos<br>**Then** el sistema actualiza la información. | EP-04 |
| US-19 | Consultar pólizas | Como asegurado, deseo consultar mis pólizas para conocer los seguros que tengo contratados. | **Scenario 1: Pólizas disponibles**<br>**Given** que el usuario posee pólizas asociadas<br>**When** consulta sus pólizas<br>**Then** el sistema presenta las pólizas registradas. | EP-05 |
| US-20 | Consultar detalle de póliza | Como asegurado, deseo consultar los detalles de una póliza para conocer su cobertura y vigencia. | **Scenario 1: Póliza existente**<br>**Given** que la póliza pertenece al usuario<br>**When** consulta sus detalles<br>**Then** el sistema presenta la información correspondiente. | EP-05 |
| US-21 | Solicitar renovación de póliza | Como asegurado, deseo solicitar la renovación de una póliza para mantener mi cobertura vigente. | **Scenario 1: Renovación permitida**<br>**Given** que la póliza puede ser renovada<br>**When** el usuario solicita su renovación<br>**Then** el sistema registra la solicitud. | EP-05 |
| US-22 | Registrar un siniestro | Como asegurado, deseo registrar un siniestro para iniciar el proceso correspondiente con mi seguro. | **Scenario 1: Registro correcto**<br>**Given** que el usuario posee una póliza vigente y proporciona la información requerida<br>**When** registra el siniestro<br>**Then** el sistema almacena la solicitud. | EP-05 |
| US-23 | Consultar estado de siniestro | Como asegurado, deseo consultar el estado de un siniestro para conocer el avance de mi solicitud. | **Scenario 1: Siniestro existente**<br>**Given** que existe un siniestro registrado<br>**When** el usuario consulta su estado<br>**Then** el sistema presenta el estado actual. | EP-05 |
| US-24 | Recibir aviso de vencimiento | Como asegurado, deseo recibir información sobre el próximo vencimiento de una póliza para poder gestionar su renovación. | **Scenario 1: Póliza próxima a vencer**<br>**Given** que una póliza se aproxima a su fecha de vencimiento<br>**When** el sistema identifica esta condición<br>**Then** genera una notificación para el usuario. | EP-06 |
| US-25 | Consultar notificaciones | Como usuario, deseo consultar mis notificaciones para conocer eventos importantes relacionados con mis seguros. | **Scenario 1: Notificaciones existentes**<br>**Given** que el usuario posee notificaciones<br>**When** consulta sus notificaciones<br>**Then** el sistema presenta los avisos asociados a su cuenta. | EP-06 |
| US-26 | Registrar una compañía aseguradora | Como representante de una aseguradora, deseo registrar la información de mi compañía para participar en Livva. | **Scenario 1: Registro correcto**<br>**Given** que se proporciona información válida de la compañía<br>**When** se solicita su registro<br>**Then** el sistema registra la compañía aseguradora. | EP-07 |
| US-27 | Registrar un producto de seguro | Como representante de una aseguradora, deseo registrar un producto de seguro para ofrecerlo mediante Livva. | **Scenario 1: Registro correcto**<br>**Given** que la compañía está registrada y proporciona información válida<br>**When** registra un producto de seguro<br>**Then** el sistema almacena el producto asociado a la compañía. | EP-07 |
| US-28 | Consultar solicitudes recibidas | Como representante de una aseguradora, deseo consultar las solicitudes asociadas a mis productos para realizar su seguimiento. | **Scenario 1: Solicitudes disponibles**<br>**Given** que existen solicitudes asociadas a la compañía<br>**When** consulta las solicitudes<br>**Then** el sistema presenta las solicitudes correspondientes. | EP-07 |

### Epics

| Epic ID | Título | Descripción |
|---|---|---|
| EP-01 | Landing Page e información de Livva | Agrupa las funcionalidades orientadas a visitantes que desean conocer Livva, su propuesta de valor y los tipos de seguros disponibles. |
| EP-02 | Gestión de cuentas y perfiles | Agrupa las funcionalidades relacionadas con registro, autenticación y administración de información personal. |
| EP-03 | Gestión de seguros vehiculares | Agrupa las funcionalidades relacionadas con vehículos y solicitudes de seguros vehiculares. |
| EP-04 | Gestión de seguros de vida | Agrupa las funcionalidades relacionadas con solicitudes de seguros de vida y gestión de beneficiarios. |
| EP-05 | Gestión de pólizas y siniestros | Agrupa las funcionalidades relacionadas con consulta de pólizas, renovaciones, siniestros e indemnizaciones. |
| EP-06 | Notificaciones | Agrupa las funcionalidades relacionadas con avisos importantes para los usuarios. |
| EP-07 | Gestión de compañías aseguradoras | Agrupa las funcionalidades destinadas a las compañías aseguradoras asociadas con Livva. |

## 3.2. Impact Mapping

![Livva Impact Mapping](assets/md-images-impact-mapping/impact-map.png)

---

## 3.3. Product Backlog

| # Orden | User Story Id | Título | Descripción | Story Points |
|---:|---|---|---|---:|
| 1 | US-01 | Conocer Livva | Como visitante, deseo conocer la propuesta de Livva para determinar si la plataforma puede ayudarme a gestionar mis seguros. | 2 |
| 2 | US-03 | Consultar información de seguro vehicular | Como visitante propietario de un vehículo, deseo conocer información sobre seguros vehiculares para evaluar si se ajustan a mis necesidades. | 2 |
| 3 | US-04 | Consultar información de seguro de vida | Como visitante interesado en seguros de vida, deseo conocer información sobre este producto para evaluar si puede proteger económicamente a mis beneficiarios. | 2 |
| 4 | US-02 | Consultar beneficios de Livva | Como visitante, deseo conocer los beneficios de Livva para comprender las ventajas de utilizar la plataforma. | 1 |
| 5 | US-05 | Registrar una cuenta | Como usuario nuevo, deseo registrar una cuenta para utilizar los servicios de Livva. | 3 |
| 6 | US-06 | Iniciar sesión | Como usuario registrado, deseo iniciar sesión para acceder a mi información y gestionar mis seguros. | 3 |
| 7 | US-09 | Registrar un vehículo | Como propietario de un vehículo, deseo registrar los datos de mi vehículo para utilizarlo en una solicitud de seguro. | 3 |
| 8 | US-12 | Solicitar seguro vehicular | Como propietario de un vehículo, deseo solicitar un seguro vehicular para proteger mi vehículo ante posibles riesgos. | 5 |
| 9 | US-13 | Consultar solicitud de seguro vehicular | Como propietario de un vehículo, deseo consultar mi solicitud para conocer su estado. | 3 |
| 10 | US-14 | Solicitar seguro de vida | Como persona interesada en protección financiera, deseo solicitar un seguro de vida para brindar respaldo económico a mis beneficiarios. | 5 |
| 11 | US-16 | Registrar beneficiario | Como titular de un seguro de vida, deseo registrar un beneficiario para indicar quién recibirá la protección correspondiente. | 3 |
| 12 | US-15 | Consultar solicitud de seguro de vida | Como solicitante, deseo consultar mi solicitud de seguro de vida para conocer su estado. | 3 |
| 13 | US-19 | Consultar pólizas | Como asegurado, deseo consultar mis pólizas para conocer los seguros que tengo contratados. | 3 |
| 14 | US-20 | Consultar detalle de póliza | Como asegurado, deseo consultar los detalles de una póliza para conocer su cobertura y vigencia. | 3 |
| 15 | US-22 | Registrar un siniestro | Como asegurado, deseo registrar un siniestro para iniciar el proceso correspondiente con mi seguro. | 5 |
| 16 | US-23 | Consultar estado de siniestro | Como asegurado, deseo consultar el estado de un siniestro para conocer el avance de mi solicitud. | 3 |
| 17 | US-21 | Solicitar renovación de póliza | Como asegurado, deseo solicitar la renovación de una póliza para mantener mi cobertura vigente. | 3 |
| 18 | US-24 | Recibir aviso de vencimiento | Como asegurado, deseo recibir información sobre el próximo vencimiento de una póliza para poder gestionar su renovación. | 3 |
| 19 | US-17 | Consultar beneficiarios | Como titular de un seguro de vida, deseo consultar mis beneficiarios para verificar quiénes están registrados. | 2 |
| 20 | US-18 | Actualizar beneficiario | Como titular de un seguro de vida, deseo actualizar la información de un beneficiario para mantener sus datos vigentes. | 3 |
| 21 | US-10 | Consultar vehículos registrados | Como propietario, deseo consultar mis vehículos registrados para saber cuáles están disponibles para solicitar un seguro. | 2 |
| 22 | US-11 | Actualizar datos de un vehículo | Como propietario, deseo actualizar los datos de mi vehículo para mantener su información correcta. | 3 |
| 23 | US-26 | Registrar una compañía aseguradora | Como representante de una aseguradora, deseo registrar la información de mi compañía para participar en Livva. | 5 |
| 24 | US-27 | Registrar un producto de seguro | Como representante de una aseguradora, deseo registrar un producto de seguro para ofrecerlo mediante Livva. | 5 |
| 25 | US-28 | Consultar solicitudes recibidas | Como representante de una aseguradora, deseo consultar las solicitudes asociadas a mis productos para realizar su seguimiento. | 3 |
| 26 | US-25 | Consultar notificaciones | Como usuario, deseo consultar mis notificaciones para conocer eventos importantes relacionados con mis seguros. | 2 |
| 27 | US-07 | Consultar perfil personal | Como usuario registrado, deseo consultar mi información personal para verificar mis datos registrados. | 2 |
| 28 | US-08 | Actualizar perfil personal | Como usuario registrado, deseo actualizar mis datos personales para mantener mi información vigente. | 3 |

# Capítulo IV: Product Design

## 4.1. Style Guidelines

Las Style Guidelines de Livva establecen los lineamientos visuales y comunicacionales que se aplicarán de manera consistente en los productos digitales de la solución. Estas guías definen una base común para el Landing Page y la Web Application, considerando elementos como la identidad visual, tipografía, paleta de colores, espaciado, tono de comunicación y patrones de interacción. Su propósito es mantener una experiencia coherente, reconocible, accesible y fácil de utilizar para los segmentos objetivo de Livva.

### 4.1.1. General Style Guidelines

Las General Style Guidelines de Livva definen los criterios visuales y comunicacionales que permiten mantener una identidad consistente en los productos digitales de la solución. Estas decisiones toman como base la propuesta visual desarrollada para el Landing Page y buscan transmitir confianza, claridad, accesibilidad y simplicidad a los segmentos objetivo relacionados con seguros vehiculares y seguros de salud.

#### Branding

La identidad visual de Livva busca comunicar una imagen moderna, confiable y cercana. La marca utiliza el nombre “Livva” como elemento principal de reconocimiento, acompañado por una propuesta visual limpia y minimalista. El diseño evita elementos innecesarios y prioriza la claridad en la presentación de la información, con el objetivo de reducir la complejidad asociada a la búsqueda y comparación de seguros.

La propuesta de marca se orienta a transmitir seguridad y confianza sin utilizar una comunicación excesivamente formal. Esto permite que Livva mantenga una imagen profesional y, al mismo tiempo, accesible para usuarios que buscan información relacionada con seguros vehiculares y de salud.

#### Typography

Livva utiliza la familia tipográfica Poppins como fuente principal para la experiencia web. Esta tipografía fue seleccionada por su legibilidad, apariencia moderna y variedad de pesos, lo que permite establecer una jerarquía visual clara entre títulos, subtítulos, textos descriptivos y elementos interactivos.

Se emplean pesos más altos para títulos y elementos relevantes, mientras que los textos descriptivos utilizan pesos regulares. La jerarquía tipográfica facilita el recorrido visual del usuario y permite diferenciar rápidamente la información principal de los contenidos complementarios.

![Landing Page Tipografia](assets/md-images-product-design/popping.jpg)

#### Colors

La paleta de colores de Livva utiliza principalmente tonalidades de azul, blanco y tonos neutros. El azul funciona como color principal de la marca y se utiliza en botones, elementos destacados, enlaces y componentes interactivos. Este color busca reforzar conceptos asociados a confianza, seguridad y estabilidad.

El blanco y los tonos claros se utilizan como fondos para mantener una interfaz limpia y facilitar la lectura. Los tonos oscuros se emplean principalmente en títulos y textos de alta relevancia, mientras que los tonos grises se utilizan en textos secundarios y elementos de apoyo.

![Landing Page Color Azul](assets/md-images-product-design/color-blue.png)
![Landing Page Color Blanco](assets/md-images-product-design/color-white.png)
![Landing Page Color Negro](assets/md-images-product-design/color-black.png)
![Landing Page Color Gris](assets/md-images-product-design/color-gray.png)

#### Spacing

El sistema de espaciado de Livva busca mantener una distribución ordenada de los contenidos y evitar la saturación visual. Se aplican márgenes y espacios consistentes entre secciones, tarjetas, botones, títulos y bloques de texto.

El Landing Page utiliza contenedores centrados con un ancho máximo definido, permitiendo mantener una adecuada distribución del contenido en pantallas grandes. En dispositivos de menor tamaño, el espaciado se adapta mediante reglas de responsive design para conservar la legibilidad y facilidad de interacción.

#### Tone of Voice

El tono de comunicación de Livva se caracteriza por ser serio, respetuoso, claro y sereno. Debido a que la plataforma aborda decisiones relacionadas con seguros y protección personal, se evita un lenguaje excesivamente informal o irreverente.

La comunicación busca explicar la información de manera directa y comprensible, reduciendo el uso de términos complejos y priorizando mensajes orientados a facilitar la toma de decisiones. Al mismo tiempo, mantiene un tono cercano que permita generar confianza y reducir la percepción de complejidad asociada al proceso de selección de seguros.

### 4.1.2. Web Style Guidelines

Las Web Style Guidelines de Livva establecen los criterios visuales y de interacción específicos para la experiencia web, asegurando consistencia entre las diferentes secciones del Landing Page y sirviendo como referencia para el desarrollo posterior de la Web Application. Estas reglas buscan mantener una interfaz clara, predecible y accesible para los usuarios.

#### Navigation Bar

La barra de navegación se mantiene visible en la parte superior de la página y permite el acceso directo a las principales secciones del Landing Page. Los enlaces utilizan etiquetas breves y descriptivas como Inicio, Seguros, Planes, Nosotros y Contacto, con el objetivo de facilitar la orientación del usuario.

Los elementos principales de acción, como “Iniciar Sesión” y “Empezar Gratis”, se diferencian visualmente mediante botones con estilos de mayor énfasis. La navegación mantiene una distribución ordenada y se adapta a diferentes tamaños de pantalla mediante responsive design.

#### Buttons

Los botones utilizan bordes redondeados, tipografía legible y una jerarquía visual basada en su nivel de importancia. Los botones principales utilizan el color azul de la marca con texto blanco, mientras que las acciones secundarias emplean estilos con borde y fondo transparente.

Los botones incluyen estados visuales de interacción, como cambios de color durante el estado hover, con el objetivo de proporcionar retroalimentación al usuario y reforzar la percepción de interactividad.

#### Cards

Las tarjetas se utilizan para presentar información relacionada con los tipos de seguro, planes y otros contenidos relevantes de manera independiente y fácil de identificar. Estas utilizan fondos claros, bordes suaves, esquinas redondeadas y separación suficiente entre elementos.

En la sección de seguros, las cards permiten diferenciar las soluciones de Seguro Vehicular y Seguro de Salud. En la sección de planes, las tarjetas permiten comparar características y beneficios, utilizando mayor énfasis visual en la alternativa recomendada.

#### Forms

Los formularios siguen una estructura vertical y utilizan labels visibles asociados a cada campo de entrada. Los inputs y textareas incluyen espacios suficientes, bordes definidos y estados de focus que permiten identificar claramente el elemento activo.

Se busca evitar depender únicamente de placeholders para comunicar el propósito de cada campo, favoreciendo la accesibilidad y comprensión de la interfaz.

#### Interaction States

Los principales componentes interactivos consideran estados visuales de hover y focus. Estos estados permiten comunicar al usuario qué elementos pueden ser seleccionados o activados.

El selector de modalidad de pago mensual y anual utiliza un cambio visual para representar el estado seleccionado, mientras que los botones y enlaces modifican su apariencia al recibir interacción.

#### Responsive Web Design

La interfaz de Livva utiliza un enfoque responsive para adaptar la presentación del contenido a distintos tamaños de pantalla. En resoluciones de escritorio se emplean distribuciones de varias columnas, mientras que en tablets y dispositivos móviles los componentes se reorganizan progresivamente en menos columnas.

Las secciones de seguros, planes, información institucional, contacto y footer modifican su distribución para mantener la legibilidad y facilidad de interacción en pantallas reducidas. Los botones y elementos de navegación también ajustan su disposición para evitar desbordamientos horizontales.

#### Accessibility

La experiencia web considera prácticas básicas de accesibilidad, como el uso de labels asociados a formularios, atributos ARIA en componentes de navegación e interacción, estados de focus visibles y una estructura semántica basada en elementos HTML5.

Asimismo, los componentes decorativos que no aportan información adicional al usuario utilizan atributos que permiten evitar interpretaciones innecesarias por parte de tecnologías de asistencia.

## 4.2. Information Architecture

La arquitectura de información de Livva establece la forma en que se organiza, presenta y relaciona el contenido dentro de la experiencia digital. Su objetivo es facilitar que los usuarios puedan comprender la estructura de la plataforma, identificar rápidamente las opciones disponibles y acceder a la información necesaria con el menor esfuerzo posible.

La propuesta considera tanto el Landing Page como la futura Web Application, manteniendo criterios consistentes de organización, etiquetado, navegación y búsqueda. Para ello, se prioriza una estructura clara y progresiva que permita a los usuarios reconocer las secciones principales, comprender la relación entre los contenidos y completar sus objetivos de manera eficiente.

### 4.2.1. Organization Systems

Livva utiliza principalmente un sistema de organización jerárquico y por tópicos, con el objetivo de presentar la información de forma clara y facilitar que los usuarios identifiquen rápidamente las secciones principales de la experiencia digital.

En el Landing Page, la información se organiza de manera jerárquica desde los contenidos de mayor relevancia hacia información más específica. La sección inicial presenta la propuesta de valor de Livva y los principales call-to-action, seguida por las soluciones de seguro, planes disponibles, información sobre la plataforma y medios de contacto.

La categorización por tópicos permite agrupar el contenido de acuerdo con su propósito. En la sección de Seguros se distinguen las dos soluciones principales consideradas por Livva: Seguro Vehicular y Seguro de Salud. Esto permite que cada segmento objetivo pueda identificar con facilidad el contenido relacionado con sus necesidades.

La sección de Planes utiliza una organización comparativa, permitiendo presentar diferentes alternativas de servicio con sus respectivos beneficios y precios. De esta manera, el usuario puede contrastar las opciones disponibles antes de realizar una elección.

En la futura Web Application se mantendrá una organización jerárquica basada en las principales funcionalidades de la plataforma. Las opciones relacionadas con gestión de seguros, información del usuario y otras funcionalidades se agruparán de acuerdo con su propósito, buscando reducir la cantidad de pasos necesarios para acceder a la información.

Asimismo, determinados procesos podrán utilizar una organización secuencial cuando el usuario deba completar una serie de pasos para alcanzar un objetivo, como seleccionar una alternativa de seguro, registrar información o completar una operación dentro de la plataforma.

### 4.2.2. Labeling Systems

El sistema de etiquetado de Livva busca representar la información mediante nombres simples, breves y comprensibles, reduciendo la posibilidad de confusión durante la navegación. Las etiquetas utilizadas en el Landing Page se relacionan directamente con el contenido al que permiten acceder y mantienen una terminología consistente en toda la experiencia.

La navegación principal utiliza las etiquetas “Inicio”, “Seguros”, “Planes”, “Nosotros” y “Contacto”. Cada una representa de forma directa el contenido asociado a su sección, permitiendo que el usuario anticipe el tipo de información que encontrará antes de seleccionarla.

La etiqueta “Seguros” agrupa las principales soluciones consideradas dentro del alcance de Livva. Dentro de esta sección se utilizan las denominaciones “Seguro Vehicular” y “Seguro de Salud”, manteniendo una correspondencia directa con los dos segmentos objetivo definidos para el proyecto.

La etiqueta “Planes” identifica la sección en la que se presentan las alternativas de servicio y sus respectivos beneficios. Para diferenciar las opciones se emplean nombres como “Plan Básico” y “Livva Pro”, facilitando la comparación entre niveles de servicio.

Las acciones principales utilizan etiquetas orientadas a la intención del usuario, como “Cotizar mi Seguro”, “Ver Coberturas”, “Iniciar Sesión”, “Empezar Gratis”, “Elegir Plan” y “Enviar mensaje”. Estas etiquetas utilizan verbos de acción y buscan comunicar claramente el resultado esperado de la interacción.

En la futura Web Application se mantendrá el mismo criterio de simplicidad y consistencia, utilizando etiquetas breves y relacionadas directamente con las tareas del usuario. Se evitarán nombres técnicos o ambiguos que puedan dificultar la comprensión de la funcionalidad.

### 4.2.3. SEO Tags and Meta Tags

Livva utiliza etiquetas SEO y Meta Tags con el objetivo de mejorar la identificación del contenido por parte de los motores de búsqueda y proporcionar información descriptiva sobre las principales páginas de la experiencia digital. Estas etiquetas permiten comunicar de manera estructurada el propósito de cada página, su contenido principal y la autoría del producto.

Para el Landing Page se establecen los siguientes valores:

| Tag | Valor |
|---|---|
| Title | Livva - La plataforma inteligente para tu seguro ideal |
| Description | Livva te permite comparar y gestionar alternativas de seguros vehiculares y de salud de forma simple, clara y digital. |
| Keywords | seguros, seguro vehicular, seguro de salud, comparación de seguros, Livva |
| Author | Livva Care |

Estas etiquetas se incluyen dentro del elemento `<head>` del documento HTML y permiten describir de manera resumida el contenido principal del Landing Page.

En la futura Web Application se utilizarán Meta Tags específicos de acuerdo con el propósito de cada vista principal, manteniendo una estructura consistente y utilizando términos relacionados directamente con las funcionalidades disponibles para el usuario.

A medida que se implementen nuevas páginas y vistas, los valores de Title y Description se adaptarán al contenido específico de cada sección, evitando descripciones genéricas y procurando que cada página pueda identificarse claramente.

### 4.2.4. Searching Systems

El sistema de búsqueda de Livva se plantea de acuerdo con el volumen y tipo de información disponible en cada producto digital.

En el Landing Page no se implementa una barra de búsqueda debido a que el contenido se encuentra organizado en pocas secciones claramente identificadas mediante la navegación principal. El usuario puede acceder directamente a las secciones de Inicio, Seguros, Planes, Nosotros y Contacto sin necesidad de realizar búsquedas internas.

En la futura Web Application se incorporarán mecanismos de búsqueda y filtrado para facilitar el acceso a información relacionada con seguros, alternativas disponibles y elementos gestionados por el usuario.

Para las alternativas de seguros se podrá considerar una búsqueda complementada con filtros según características relevantes, como tipo de seguro, rango de precio, nivel de cobertura u otros criterios definidos durante la implementación de la plataforma.

Los resultados se presentarán de forma estructurada mediante listas o tarjetas, permitiendo al usuario identificar rápidamente la información principal de cada alternativa y acceder a su detalle.

El sistema de búsqueda deberá mantener criterios de simplicidad y claridad, evitando presentar una cantidad excesiva de filtros al mismo tiempo. Los filtros seleccionados deberán ser visibles para el usuario y permitir su modificación o eliminación de manera sencilla.

### 4.2.5. Navigation Systems

El sistema de navegación de Livva busca permitir que los usuarios recorran la experiencia digital de manera sencilla, predecible y con el menor número de pasos posible.

En el Landing Page se utiliza una navegación principal ubicada en la parte superior de la interfaz. Esta incluye accesos directos a las secciones Inicio, Seguros, Planes, Nosotros y Contacto. Cada opción permite realizar un desplazamiento directo hacia la sección correspondiente dentro de la misma página.

Además de la navegación principal, se utilizan call-to-action ubicados en puntos estratégicos de la interfaz. Entre ellos se encuentran “Cotizar mi Seguro”, “Ver Coberturas”, “Iniciar Sesión”, “Empezar Gratis” y “Elegir Plan”. Estas acciones permiten dirigir al usuario hacia contenido relacionado con sus objetivos y, posteriormente, hacia las vistas correspondientes de la Web Application.

El footer complementa la navegación mediante accesos a secciones principales y enlaces relacionados con información legal, como Términos y Condiciones y Política de Privacidad.

En dispositivos de menor tamaño, la distribución de los elementos de navegación se adapta mediante responsive design, reorganizando los enlaces y botones para conservar su visibilidad y facilidad de interacción.

En la futura Web Application, la navegación se organizará de acuerdo con las principales tareas del usuario. Se mantendrán etiquetas consistentes con el Landing Page y se utilizarán elementos de navegación que permitan acceder a las funcionalidades relacionadas con la gestión y consulta de seguros, información del usuario y otras operaciones definidas en los User Stories.

Los flujos de navegación buscarán mantener rutas claras entre las distintas vistas, proporcionando retroalimentación visual y evitando que el usuario pierda el contexto de la tarea que está realizando.

## 4.3. Landing Page UI Design

La propuesta de interfaz de usuario del Landing Page de Livva traduce las decisiones establecidas en las Style Guidelines y en la Information Architecture hacia una experiencia visual clara, consistente y orientada a los segmentos objetivo. El diseño prioriza la comprensión rápida de la propuesta de valor, la identificación de las soluciones de Seguro Vehicular y Seguro de Salud, así como el acceso sencillo a los principales call-to-action.

La interfaz ha sido planteada siguiendo criterios de jerarquía visual, simplicidad, accesibilidad y responsive design, buscando mantener una experiencia coherente tanto en navegadores de escritorio como en dispositivos móviles.

### 4.3.1. Landing Page Wireframe
Los wireframes del Landing Page de Livva representan la distribución preliminar de los principales elementos de la interfaz antes de aplicar los estilos visuales definitivos. Estos diseños permiten visualizar la organización del contenido, jerarquía de información, ubicación de los call-to-action y estructura general de navegación.

A continuación, se presentan los wireframes correspondientes a la versión Desktop Web Browser del Landing Page.

#### Desktop Web Browser

![Landing Page Wireframe Desktop 1](assets/md-images-product-design/landing-wireframe-desktop-1.png)

![Landing Page Wireframe Desktop 2](assets/md-images-product-design/landing-wireframe-desktop-2.png)

![Landing Page Wireframe Desktop 3](assets/md-images-product-design/landing-wireframe-desktop-3.png)

![Landing Page Wireframe Desktop 4](assets/md-images-product-design/landing-wireframe-desktop-4.png)

![Landing Page Wireframe Desktop 5](assets/md-images-product-design/landing-wireframe-desktop-5.png)

#### Mobile Web Browser
![Landing Page Wireframe Movil 1](assets/md-images-product-design/landing-wireframe-movil-1.png)

![Landing Page Wireframe Movil 2](assets/md-images-product-design/landing-wireframe-movil-2.png)

![Landing Page Wireframe Movil 3](assets/md-images-product-design/landing-wireframe-movil-3.png)

![Landing Page Wireframe Movil 4](assets/md-images-product-design/landing-wireframe-movil-4.png)

![Landing Page Wireframe Movil 5](assets/md-images-product-design/landing-wireframe-movil-5.png)

### 4.3.2. Landing Page Mock-up
![Landing Page MockUp Desktop 1](assets/md-images-product-design/Landing-mockup-Desktop-1.png)

![Landing Page MockUp Desktop 2](assets/md-images-product-design/Landing-mockup-Desktop-2.png)

![Landing Page MockUp Desktop 3](assets/md-images-product-design/Landing-mockup-Desktop-3.png)

![Landing Page MockUp Desktop 4](assets/md-images-product-design/Landing-mockup-Desktop-4.png)

![Landing Page MockUp Desktop 5](assets/md-images-product-design/Landing-mockup-Desktop-5.png)

#### Mobile Web Browser
![Landing Page MockUp Movil 1](assets/md-images-product-design/Landing-mockup-Movil-1.png)

![Landing Page MockUp Movil 2](assets/md-images-product-design/Landing-mockup-Movil-2.png)

![Landing Page MockUp Movil 3](assets/md-images-product-design/Landing-mockup-Movil-3.png)

![Landing Page MockUp Movil 4](assets/md-images-product-design/Landing-mockup-Movil-4.png)

![Landing Page MockUp Movil 5](assets/md-images-product-design/Landing-mockup-Movil-5.png)

## 4.4. Web Applications UX/UI Design
El diseño UX/UI de la Web Application de Livva se desarrolla tomando como base los resultados obtenidos durante el proceso de UX Research, los User Stories definidos en el Product Backlog y los lineamientos visuales establecidos previamente.

El objetivo de esta sección es representar la estructura, navegación e interacción de las principales funcionalidades de la aplicación, asegurando que los usuarios puedan completar sus tareas de manera clara y eficiente.

Para ello, se desarrollarán wireframes, wireflows, mock-ups y user flow diagrams que permitan visualizar tanto la distribución de los elementos de la interfaz como los diferentes recorridos que pueden realizar los usuarios dentro de la Web Application.

### 4.4.1. Web Applications Wireframes
Los wireframes de la Web Application de Livva representan la estructura y distribución preliminar de las principales pantallas de la plataforma. Estos diseños permiten visualizar la ubicación de los elementos de navegación, formularios, tarjetas, botones y secciones de contenido antes de aplicar el diseño visual definitivo.

![wireframe 1](assets/md-livva-webapp-wireframes/wireframe-1.png)
![wireframe 2](assets/md-livva-webapp-wireframes/wireframe-2.png)
![wireframe 3](assets/md-livva-webapp-wireframes/wireframe-3.png)
![wireframe 4](assets/md-livva-webapp-wireframes/wireframe-4.png)
![wireframe 5](assets/md-livva-webapp-wireframes/wireframe-5.png)
![wireframe 6](assets/md-livva-webapp-wireframes/wireframe-6.png)
![wireframe 7](assets/md-livva-webapp-wireframes/wireframe-7.png)
![wireframe 8](assets/md-livva-webapp-wireframes/wireframe-8.png)
![wireframe 9](assets/md-livva-webapp-wireframes/wireframe-9.png)
![wireframe 10](assets/md-livva-webapp-wireframes/wireframe-10.png)
![wireframe 11](assets/md-livva-webapp-wireframes/wireframe-11.png)
![wireframe 12](assets/md-livva-webapp-wireframes/wireframe-12.png)
![wireframe 13](assets/md-livva-webapp-wireframes/wireframe-13.png)
![wireframe 14](assets/md-livva-webapp-wireframes/wireframe-14.png)
![wireframe 15](assets/md-livva-webapp-wireframes/wireframe-15.png)
![wireframe 16](assets/md-livva-webapp-wireframes/wireframe-16.png)
![wireframe 17](assets/md-livva-webapp-wireframes/wireframe-17.png)
![wireframe 18](assets/md-livva-webapp-wireframes/wireframe-18.png)
![wireframe 19](assets/md-livva-webapp-wireframes/wireframe-19.png)

### 4.4.2. Web Applications Wireflow Diagrams
![wiereflow Diagrams](assets/md-livva-webapp-wireframes/WebApplicationsWireflowDiagrams.png)

### 4.4.3. Web Applications Mock-ups
![mockup 1](assets/md-livva-webapp-mockups/mockup1.png)
![mockup 2](assets/md-livva-webapp-mockups/mockup2.png)
![mockup 3](assets/md-livva-webapp-mockups/mockup3.png)
![mockup 4](assets/md-livva-webapp-mockups/mockup4.png)
![mockup 5](assets/md-livva-webapp-mockups/mockup5.png)
![mockup 6](assets/md-livva-webapp-mockups/mockup6.png)
![mockup 7](assets/md-livva-webapp-mockups/mockup7.png)
![mockup 8](assets/md-livva-webapp-mockups/mockup8.png)
![mockup 9](assets/md-livva-webapp-mockups/mockup9.png)
![mockup 10](assets/md-livva-webapp-mockups/mockup10.png)
![mockup 11](assets/md-livva-webapp-mockups/mockup11.png)
![mockup 12](assets/md-livva-webapp-mockups/mockup12.png)
![mockup 13](assets/md-livva-webapp-mockups/mockup13.png)
![mockup 14](assets/md-livva-webapp-mockups/mockup14.png)
![mockup 15](assets/md-livva-webapp-mockups/mockup15.png)
![mockup 16](assets/md-livva-webapp-mockups/mockup16.png)
![mockup 17](assets/md-livva-webapp-mockups/mockup17.png)
![mockup 18](assets/md-livva-webapp-mockups/mockup18.png)
![mockup 19](assets/md-livva-webapp-mockups/mockup19.png)

### 4.4.4. Web Applications User Flow Diagrams

![Flow Diagrams](assets/md-livva-webapp-mockups/flow-diagrams.png)

## 4.5. Web Applications Prototyping

En esta sección se presenta el prototipo interactivo de la Web Application de Livva, desarrollado a partir de los mock-ups y User Flow Diagrams definidos previamente.

El prototipo permite simular la navegación entre las principales vistas de la aplicación y validar la secuencia de interacción que siguen los usuarios para completar sus tareas principales. Las conexiones entre pantallas fueron definidas considerando los recorridos planteados en los User Flows y el sistema de navegación establecido para la aplicación.

Se consideraron las principales funcionalidades de En esta sección se presenta el prototipo interactivo de la Web Application de Livva, desarrollado a partir de los mock-ups y User Flow Diagrams definidos previamente.

El prototipo permite simular la navegación entre las principales vistas de la aplicación y validar la secuencia de interacción que siguen los usuarios para completar sus tareas principales. Las conexiones entre pantallas fueron definidas considerando los recorridos planteados en los User Flows y el sistema de navegación establecido para la aplicación.

Se consideraron las principales funcionalidades de Livva, como el acceso a la plataforma, visualización del dashboard, consulta y gestión de seguros, reservas, mantenimiento, disponibilidad y seguimiento de servicios.

A continuación, se presenta una captura del prototipo en funcionamiento y el enlace al video de demostración, donde se muestran los principales flujos de navegación e interacción de la aplicación.
![Web Application Prototype](assets/md-livva-webapp-mockups/Prototipo.png)

**Video:** [Livva Web Application Prototype](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416147_upc_edu_pe/IQD5jQ6ZTjOhTqA-9nM85_AEAWTpRawI7w60mHgOE26IJLs?e=FBk1S2&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

**Event Storming**

![Design-Level Event Storming](assets/md-big-picture-event-storming/big-picture-event-storming.PNG)

---

### 4.6.2. Software Architecture Context Diagram

![Software Architecture Context Diagram](assets/md-images-c4-diagrams/software-architecture-context-diagram.png)

---

### 4.6.3. Software Architecture Container Diagrams

![Software Architecture Container Diagram](assets/md-images-c4-diagrams/software-architecture-container-diagram.png)

---

### 4.6.4. Software Architecture Components Diagrams

![Web Application Component Diagram](assets/md-images-c4-diagrams/web-application-component-diagram.png)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

#### Identity & Profile Management Class Diagram

![Identity & Profile Management Class Diagram](assets/md-images-class-diagrams/identity-profile-management-class-diagram.png)

---

#### Insurance Request Management Class Diagram

![Insurance Request Management Class Diagram](assets/md-images-class-diagrams/insurance-request-management-class-diagram.png)

---

#### Policy Management Class Diagram

![Policy Management Class Diagram](assets/md-images-class-diagrams/policy-management-class-diagram.png)

---

#### Insurance Company, Product & Subscription Management Class Diagram

![Insurance Company, Product & Subscription Management Class Diagram](assets/md-images-class-diagrams/insurancecompany-product-subsmanagement-class-diagram.png)
## 4.8. Database Design

### 4.8.1. Database Diagrams

### Indentity & Profile Management Bounded Context Database Design Diagram
![Identity & Profile Management Bounded Context Database Design Diagram](assets/md-images-database-diagrams/identity-and-profile-management.PNG)

### Insurance Offering & Applications Bounded Context Database Design Diagram
![Insurance Offering & Applications Bounded Context Database Design Diagram](assets/md-images-database-diagrams/insurance-offering-and-applications.png)

### Policy Management Bounded Context Database Design Diagram
![Policy Management Bounded Context Database Design Diagram](assets/md-images-database-diagrams/policy-management.png)

### Claims & Indemnities Bounded Context Database Design Diagram
![Claims & Indemnities Bounded Context Database Design Diagram](assets/md-images-database-diagrams/claims-and-indemnities.png)

### Subscription Management Bounded Context Database Design Diagram
![Subscription Management Bounded Context Database Design Diagram](assets/md-images-database-diagrams/subscription-management.png)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Aspect Leaders and Collaborators

#### 5.2.1.3. Sprint Backlog 1

#### 5.2.1.4. Development Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones

## Conclusiones y recomendaciones

# Bibliografía

QuePlan. (s.f.-a). *Seguros de salud: compara y ahorra*. https://queplan.pe/Comparar/Seguros-de-Salud

QuePlan. (s.f.-b). *Seguros EPS para empresas: compara y ahorra*. https://queplan.pe/Comparar/EPS/Empresa

SeguroSimple.com. (s.f.). *Seguro vehicular: cotiza y compara los mejores precios*. https://www.segurosimple.com/pe/Seguro-Vehicular

Seguros Falabella. (s.f.-a). *Acceso clientes*. https://clientes.segurosfalabella.com.pe/

Seguros Falabella. (s.f.-b). *Seguro vehicular full cobertura*. https://auto.segurosfalabella.com.pe/

Seguros Falabella. (s.f.-c). *Seguros de vida*. https://www.segurosfalabella.com.pe/seguros-de-vida

# Anexos
