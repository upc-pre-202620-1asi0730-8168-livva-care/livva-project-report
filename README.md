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

# Anexos
