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
    - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
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
            - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
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

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:  
**ABET - EAC - Student Outcome 3**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET - EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.** | **Paredes Chavez, Carlos Augusto**<br>**AV1:**<br><br>**Torres Diaz, Rolando Andre**<br>**AV1:**<br><br>**Contreras Panuera, Fernando Fabrizio**<br>**AV1:**<br><br>**Cespedes Lezcano, Carlos Gabriel**<br>**AV1:**<br><br>**Rivera Aguilar, Scarlet Josefina**<br>**AV1:** | **AV1:** |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Paredes Chavez, Carlos Augusto**<br>**AV1:**<br><br>**Torres Diaz, Rolando Andre**<br>**AV1:**<br><br>**Contreras Panuera, Fernando Fabrizio**<br>**AV1:**<br><br>**Cespedes Lezcano, Carlos Gabriel**<br>**AV1:**<br><br>**Rivera Aguilar, Scarlet Josefina**<br>**AV1:** | **AV1:** |

<div style="page-break-after: always;"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup


### 1.1.2. Perfiles de integrantes del equipo

|   Código   | Nombre completo del integrante  | Descripción de la carrera                                          |                               Fotografía                                | Conocimientos y habilidades                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :--------: |:--------------------------------| :----------------------------------------------------------------- |:-----------------------------------------------------------------------:| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| U202321613 | Paredes Chavez, Carlos Augusto | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/carlos-paredes.PNG" width="150px" /> | Soy estudiante de Ingeniería de Software y tengo experiencia en el desarrollo de aplicaciones web, principalmente utilizando HTML, CSS, JavaScript, TypeScript y frameworks modernos. También cuento con conocimientos en bases de datos, control de versiones con Git y GitHub, y desarrollo tanto frontend como backend. Me interesa especialmente crear soluciones digitales funcionales, bien estructuradas y con una buena experiencia de usuario. Me considero una persona constante, responsable y con facilidad para aprender nuevas tecnologías. Busco seguir fortaleciendo mis conocimientos mediante proyectos prácticos que me permitan mejorar mis habilidades técnicas y prepararme para desenvolverme profesionalmente en el área de desarrollo de software. |
| U202323369 | Torres Diaz, Rolando Andre | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/rolando-torres.PNG" width="150px" /> | Soy Rolando Andre Torres Diaz, estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). A lo largo de la carrera he ido adquiriendo conocimientos en programación, desarrollo de software, bases de datos, diseño de aplicaciones y tecnologías web. Dentro del desarrollo de Livva participaré en distintas etapas del proyecto, como el análisis de requerimientos, el diseño de la solución, el desarrollo de funcionalidades, la gestión de la base de datos y la elaboración de la documentación. |           
| U202418623 | Contreras Panuera, Fernando Fabrizio | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/fernando-contreras.PNG" width="150px" /> | Soy estudiante de Ingeniería de Software y tengo conocimientos en el desarrollo de aplicaciones web, principalmente utilizando HTML, CSS, JavaScript y C++. También cuento con conocimientos en bases de datos, control de versiones con Git y GitHub, y desarrollo tanto frontend como backend. Me interesa especialmente crear soluciones digitales funcionales, bien estructuradas y que puedan brindar una buena experiencia de usuario. Me considero una persona constante, responsable y con facilidad para aprender nuevas tecnologías. Me gusta desarrollar proyectos prácticos que me permitan poner en práctica lo aprendido y mejorar progresivamente mis habilidades. Busco seguir fortaleciendo mis conocimientos durante mi formación universitaria y adquirir nuevas experiencias que me ayuden a crecer en el área del desarrollo de software. |
| U202416147 | Céspedes Lezcano, Carlos Gabriel | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/carlos-cespedes.PNG" width="150px" /> | Soy estudiante de Ingeniería de Software con experiencia en el desarrollo de aplicaciones web mediante HTML, CSS y JavaScript, además del manejo de bases de datos y control de versiones con Git. Me enfoco en construir soluciones digitales funcionales, bien estructuradas y orientadas a ofrecer una gran experiencia de usuario. Destaco por mi constancia, responsabilidad y capacidad para adaptarme rápidamente a nuevas tecnologías. Busco seguir consolidando mis competencias mediante el desarrollo de proyectos prácticos que me impulsen a crecer técnicamente y prepararme para el entorno profesional del software. |
| U20241f577 | Rivera Aguilar, Scarlet Josefina | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/scarlet-rivera.PNG" width="150px" /> | Actualmente me encuentro en el quinto ciclo de mi carrera y tengo un gran interés por el análisis de datos. Me considero una persona organizada, constante y con una fuerte motivación por aprender. Disfruto comprender el funcionamiento de las cosas, identificar fallas y plantear soluciones de mejora. Me desempeño adecuadamente en trabajo en equipo, incluso bajo presión, y valoro compartir mis conocimientos con los demás. |

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
          src="./assets/md-images-competitors/livva-care-logo.png"
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
        Livva Care es una startup InsurTech peruana que desarrolla Livva,
        una plataforma orientada a la intermediación digital de seguros
        vehiculares y de vida. La propuesta busca centralizar procesos como
        solicitud, contratación, consulta de pólizas, renovaciones y
        acompañamiento ante siniestros, conectando a los usuarios con
        compañías aseguradoras asociadas.
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
        digital durante diferentes etapas del ciclo del seguro. Además,
        incorpora una propuesta B2B para que las aseguradoras asociadas puedan
        utilizar Livva como canal de distribución y seguimiento de operaciones.
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
    <!-- PERFIL DE MARKETING -->
    <tr>
      <th rowspan="2">Perfil de Marketing</th>
      <td>
        <strong>Mercado objetivo</strong>
      </td>
      <td>
        Propietarios de vehículos particulares interesados en seguros
        vehiculares, personas interesadas en seguros de vida y compañías
        aseguradoras que buscan canales digitales de distribución y gestión
        de operaciones.
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
        y procesos, demostraciones de la plataforma y contacto comercial con
        compañías aseguradoras para desarrollar alianzas B2B.
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
    <!-- PERFIL DE PRODUCTO -->
    <tr>
      <th rowspan="3">Perfil de Producto</th>
      <td>
        <strong>Productos &amp; Servicios</strong>
      </td>
      <td>
        Livva plantea ofrecer intermediación digital de seguros vehiculares y
        de vida, registro y seguimiento de solicitudes, consulta de pólizas,
        gestión de beneficiarios, recordatorios de renovación, acompañamiento
        ante siniestros y herramientas de gestión para compañías aseguradoras
        asociadas.
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
        El precio final de cada seguro dependerá de las condiciones
        establecidas por la compañía aseguradora correspondiente. Livva Care
        plantea obtener ingresos derivados de la intermediación y mediante
        planes de suscripción B2B para compañías aseguradoras asociadas.
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
    <!-- SWOT -->
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
          <li>Especialización y experiencia en seguros vehiculares.</li>
          <li>Comparación entre distintas compañías aseguradoras.</li>
          <li>Acompañamiento durante cotización, contratación, siniestro y renovación.</li>
          <li>Proceso de cotización digital.</li>
          <li>Posicionamiento previo dentro del mercado peruano.</li>
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
          <li>Dependencia de acuerdos con compañías aseguradoras.</li>
          <li>Catálogo inicial limitado a seguros vehiculares y de vida.</li>
          <li>Necesidad de validar la disposición de las aseguradoras para utilizar los planes B2B.</li>
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
          <li>Interés de aseguradoras en ampliar sus canales digitales de distribución.</li>
          <li>Digitalización de procesos tradicionalmente asistidos.</li>
          <li>Incorporación progresiva de nuevas líneas de seguros.</li>
          <li>Desarrollo de servicios tecnológicos B2B para aseguradoras.</li>
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

Entre las principales oportunidades identificadas se encuentra la posibilidad de proporcionar una experiencia continua durante diferentes etapas del seguro y desarrollar herramientas B2B que permitan a las aseguradoras utilizar Livva como un canal adicional de distribución y seguimiento de operaciones.

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

**Valor añadido**

- Mayor visibilidad sobre el estado de las operaciones relacionadas con el seguro.
- Reducción de incertidumbre durante procesos que pueden involucrar distintas etapas.
- Construcción progresiva de confianza mediante información clara y trazable.
- Experiencia coherente durante los diferentes puntos de contacto digitales de Livva.

#### 4. Aprovechar la oportunidad: canal digital B2B para compañías aseguradoras

**Estrategia**

Desarrollar una propuesta que genere valor no solamente para las personas que contratan seguros, sino también para las compañías aseguradoras que utilicen Livva como canal digital de distribución y gestión de operaciones.

Las plataformas analizadas muestran públicamente una propuesta fuertemente orientada al consumidor final. SeguroSimple destaca la comparación y contratación de seguros vehiculares, QuePlan la comparación y elección de productos aseguradores, mientras que Seguros Falabella ofrece diferentes seguros mediante su ecosistema de canales digitales (SeguroSimple.com, s.f.; QuePlan, s.f.; Seguros Falabella, s.f.).

Livva Care plantea aprovechar esta oportunidad mediante herramientas B2B destinadas a compañías aseguradoras asociadas.

**Tácticas**

- **Portal para aseguradoras:** proporcionar un espacio donde las compañías asociadas puedan consultar las operaciones generadas mediante Livva.
- **Información estructurada:** registrar solicitudes mediante formatos consistentes que faciliten su posterior procesamiento.
- **Seguimiento de operaciones:** permitir consultar estados y trazabilidad de las solicitudes originadas mediante la plataforma.
- **Analítica básica:** proporcionar indicadores relacionados con solicitudes, productos y operaciones gestionadas mediante Livva.
- **Planes de suscripción B2B:** plantear diferentes niveles de servicio según las capacidades ofrecidas a cada compañía aseguradora.
- **Incorporación progresiva de aliados:** iniciar con un conjunto reducido de compañías y utilizar los resultados obtenidos para facilitar futuras alianzas.

**Valor añadido**

- Nuevo canal digital de distribución para las compañías aseguradoras asociadas.
- Mayor trazabilidad de las operaciones originadas mediante Livva.
- Información organizada para facilitar la gestión de solicitudes.
- Posibilidad de desarrollar una relación comercial recurrente mediante planes B2B.
- Diferenciación de Livva mediante una propuesta orientada simultáneamente al usuario final y a las compañías aseguradoras.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

## 2.4. Big Picture Event Storming

## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. User Stories

## 3.1. User Stories

## 3.2. Impact Mapping

## 3.3. Product Backlog

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

### 4.6.2. Software Architecture Context Diagram

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

## 4.8. Database Design

### 4.8.1. Database Diagrams

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
