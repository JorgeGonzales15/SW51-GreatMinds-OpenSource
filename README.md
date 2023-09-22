![UPC_logo_transparente (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2ff342be-dc34-415c-925e-1e7133e49abf)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

# DESARROLLO DE APLICACIONES OPEN SOURCE

Sección SW51

Profesor: Velasquez Nuñez, Angel Augusto

***INFORME DE TRABAJO FINAL - TB1***

**Startup: GreatMinds**

**Producto: Ayni**

**Integrantes:**
- Espejo Macuri, Paolo Andre
- Gonzales Carrión, Jorge Enrique
- Huaman Catano, Miguel Angel
- Paucar De La Cruz, Tatiana Medalith
- Zarate Castro, Jose Daniel

Agosto del 2023

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
| 1.00 | 15/08/2023 | Gonzales Carrión, Jorge Enrique| Se realizó la caratula y el indice del informe. Además, todo los puntos correspondientes a solution profile, startup profile y antecedentes y problemáticas, segmentos objetivos. Se realizó el capitulo de General Style Guidelines, Wireframes, Mockups y sus respectivos wireflows y userflows. Se realizó los diagramas C4.|
| 1.10 | 20/08/2023 | Paucar De La Cruz, Tatiana Medalith | Se realizó los puntos de Lean UX Process, Diagrama de clase, diagrama de base de datos, registro de entrevistas (participando como entrevistador) |
| 1.20 | 21/08/2023 | Zarate Castro, Jose Daniel | Se realizó el As-Is Sceario Mapping, User task matrix, User Persona, User Journey Mapping, Estilos de la landing page|
| 1.30 | 21/08/2023 | Huaman Catano, Miguel Angel | Realizó el To-Be Scenario Mapping, User stories y epics y product backlog |
| 1.40 | 01/09/2023 | Espejo Macuri, Paolo Andre | Se realizaron las preguntas para las entrevistas para ambos sectores y participó de entrevistador en el registro de entrevistas. Se realizó el análisis de entrevistas. Se realizó mockups y wireframes.|
| 1.50 | 04/09/2023 | Gonzales Carrión, Jorge Enrique | Se realizó el registro de commits y contenido del capítulo 5. |
| 2.00 | 19/09/2023 | Gonzales Carrión, Jorge Enrique - Espejo Macuri, Paolo André | Se realizaron las correcciones del primer entregable |
---
# Project Report Collaboration Insights

TB1: Se han desarrollado las actividades correspondientes para la entrega TB1 en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: (https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource)

Para la elaboración del informe se realizaron actividades tales como: 
- Redactar y graficar en formato Markdown los puntos designados al integrante y posteriormente realizar commits para que el avance se guarde. 
- Elaborar los artefactos en las herramientas indicadas y posteriormente obtener el enlace de imagen mediante "Issues" dentro del repositorio del informe
- Se realizaron reuniones para coordinar el avance de los puntos del informe, además comunicar los avances del Sprint 1 correspondiente a la Landing Page
- Se realizaron branches dentro del repositorio del informe para separar el README.md principal en capitulos.

![commitsinformeopen](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/1665e68a-849a-4c87-887e-a5d7e17d6b6c)
 

---
# Contenido 
## Tabla de contenidos


## [Capítulo I: Introducción](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/blob/develop/Cap%C3%ADtulo%20I:%20Introducci%C3%B3n.md)
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
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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

## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo IV: Product Design](#capítulo-iv-product-design)
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
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

## [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
    - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
    - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.2.2. Sprint 2](#522-sprint-2)
    - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
    - [5.2.2.2. Sprint Backlog 2](#5222-sprint-backlog-2)
    - [5.2.2.3. Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
    - [5.2.2.4. Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
    - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
    - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
    - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
    - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)

## [Conclusiones](#conclusiones)

## [Referencias](#referencias)

## [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 3

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describe las acciones realizadas y enunciados de 
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro 
del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
| - | - | - |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Jorge Gonzales - TB1:** Se propuso mediante reunión el alcance del proyecto, la temática, y la delegación de tareas. <br> **Paolo Espejo -TB1:** Se realizaron las entrevistas comunicando oralmente las preguntas necesarias para obtener información por parte del segmento objetivo y se realizó el analisis de todas las entrevistas sustendando al equipo las funcionalidades que desean los usuarios. <br> **Tatiana Paucar - TB1:** Se comunicó con el equipo para plantear el desarrollo de contenido del Lean UX process. Asimismo, propuso ideas mediante reunión acerca  del desarrollo del  modelado de diagrama de clases y de base de datos. <br> **Miguel Huaman -TB1:** Se propuso mediante una reunión el desarrollo del needfinding y se comunicó las caracteristicas de desarrollo a todo el equipo. <br> **Jose Zarate - TB1:** Se propuso ideas a todo el equipo para el capítulo de Requirements Specification y los mockups y wireframes de la landing page. | Se distribuyeron diferentes actividades para el desarrollo del trabajo para que cada integrante pueda desempeñarse en un área en específica, luego pudimos realizar las tareas asignadas gracias a las ideas comunicadas entre todo el equipo de desarrollo. Para finalizar, todos los integrantes del equipo lograron comunicar oralmente sus ideas de manera eficaz |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Jorge Gonzales - TB1:** Se realizaron propuestas escritas para los General Style Guidelines asimismo propuestas para los wireframes y mockups para la aplicación web. <br> **Paolo Espejo - TB1** Se realizó el planteamiento de las preguntas para las entrevistas y se hizo el analisis de estas. <br> **Tatiana Paucar - TB1:** Se plantearon en escrito el Lean UX Process y los diagramas de clases y de base de datos. <br> **Miguel Huaman - TB1:** Se plantearon los puntos del NeedFinding. <br> **Jose Zarate - TB1:** Se plantearon los mockups y wireframes de la landing page | Cada integrante desarrolló los items para esta entrega y comúnico sus aportes de manera escrita y formal para este sprint. |
