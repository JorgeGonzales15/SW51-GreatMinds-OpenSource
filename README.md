![UPC_logo_transparente (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2ff342be-dc34-415c-925e-1e7133e49abf)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

# DESARROLLO DE APLICACIONES OPEN SOURCE

Sección SW51

Profesor: Velasquez Nuñez, Angel Augusto

***INFORME DE TRABAJO FINAL - TB1***

**Startup: GreatMinds**

**Producto:**

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
| 1.00 | 08/09/2022 | Jorge Gonzales, Paolo Espejo, Miguel Huaman, Tatiana Paucar, Jose Zarate | Implementación de startup profile, solution profile, segmento objetivo, competidores, entervistas, needfinding, journey map, product backlog, entre otros. Asimismo, la implementación de Landing Page Wireframe, Landing Page Mockup, Information Architecture, Software Architecture Context Diagram, Class Diagram, Software Configuration Management, entre otros. |

---
# Project Report Collaboration Insights

Link de repositorio Github: [Github](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource)

---
# Contenido 
## Tabla de contenidos


## [Capítulo I: Introducción](#capítulo-i-introducción)
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
  - [4.4.2. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.3. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
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
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Jorge Gonzales - TB1:** Se ha definido el alcance del proyecto, la temática, y la delegación de tareas. <br> **Paolo Espejo -TB1:** Se realizaron las entrevistas comunicando oralmente las preguntas necesarias para obtener información por parte del segmento objetivo y se realizó el analisis de todas las entrevistas sustendando al equipo las funcionalidades que desean los usuarios. <br> **Tatiana Paucar - TB1:** Se propuso el Lean UX process al equipo y consultándolo entre todo el equipo se hizo el desarrollo de este. Asimismo, se propuso el modelado de diagrama de clases y de base de datos. <br> **Miguel Huaman -TB1:** Se propuso el needfinding y se comunicó las caracteristicas de desarrollo a todo el equipo. <br> **Jose Zarate - TB1:** Se propuso ideas para el capítulo de Requirements Specification y los mockups y wireframes de la landing page. | Se distribuyeron diferentes actividades para el desarrollo del trabajo para que cada integrante pueda desempeñarse en un área en específica, luego pudimos realizar las tareas asignadas. Para finalizar, todos los integrantes del equipo lograron comunicar oralmente sus ideas de manera eficaz |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Jorge Gonzales - TB1:** Se realizaron propuestas escritas para los General Style Guidelines asimismo propuestas para los wireframes y mockups para la aplicación web. <br> **Paolo Espejo - TB1** Se realizó el planteamiento de las preguntas para las entrevistas y se hizo el analisis de estas. <br> **Tatiana Paucar - TB1:** Se plantearon en escrito el Lean UX Process y los diagramas de clases y de base de datos. <br> **Miguel Huaman - TB1:** Se plantearon los puntos del NeedFinding. <br> **Jose Zarate - TB1:** Se plantearon los mockups y wireframes de la landing page | Cada integrante desarrolló los items para esta entrega y comúnico sus aportes de manera escrita y formal para este sprint. |

---
# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

El startup que se introduce en el presente informe recibe como nombre “GreatMinds”. Actualmente conformado por un conjunto de estudiantes de la Universidad Peruana de Ciencias Aplicadas, con la ambición de querer ayudar a la sociedad con nuestra grán pasión a la tecnología e informática, creamos esta startup tomando como objetivo facilitar y mejorar la producción del sector agrícola del Perú. 

Como misión se plantea “Incrementar la producción agrícola con eficiencia, seguridad y transparencia entre productores y exportadores del Perú”. Asimismo, la visión de la startup plantea desarrollar la aplicación más reconocida en el Perú para gestionar cultivos de manera segura, sencilla y online.

### 1.1.2. Perfiles de integrantes del equipo

Mi nombre es Jorge Enrique Gonzales Carrión tengo 19 años de edad y curso el sexto ciclo de la carrera Ingeniería de Software. Me considero una persona con sentido de responsabilidad y la suficiente capacidad de trabajar en equipo aportando ideas innovadoras. Además, en cualidades me considero asertivo y colaborativo, puntos que pueden mejorar el proceso de elaboración de los distintos trabajos del curso. Finalmente, poseo conocimientos de programación que brindaron los ciclos anteriores al presente.

Mi nombre es Tatiana Medalith Paucar De La Cruz, tengo 19 años y soy estudiante del quinto ciclo de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona autodidacta, lo que me permite adquirir nuevos conocimientos de manera constante. Asimismo, me considero una persona bastante organizada y responsable en el ámbito académico. Además de ello, me gusta trabajar arduamente para lograr objetivos comunes dentro de un proyecto.

Mi nombre es Jose Daniel Zarate Castro y actualmente tengo 20 años. Soy un estudiante de Ingeniería de Software en el quinto ciclo de mi formación académica. Soy una persona muy orientada al trabajo en equipo y siempre estoy entusiasmado por colaborar y contribuir al máximo. Me considero un participante activo en cualquier proyecto o actividad que emprenda. Tengo una actitud empática hacia los demás y me esfuerzo por entender las necesidades y perspectivas de mis compañeros. En términos de conocimientos técnicos tengo conocimientos en Java, c# y Python.

Mi nombre es Miguel Ángel Huamán Cataño, tengo 19 años y actualmente estoy estudiando el 5to ciclo de la carrera de Ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona responsable que es capaz de lograr lo que se propone. Además, siempre tengo una actitud positiva y respetuosa con las demás personas. Poseo los conocimientos de programación brindados por la universidad y sé lo básico de algunos otros lenguajes de programación , soy capaz de aprender rápidamente sobre ciertos temas gracias a mi buena lógica y capacidad de aprendizaje.

Mi nombre es Paolo Andre Espejo Macuri, tengo 20 años de edad, estoy cursando el sexto ciclo de la carrera de Ingeniería de Software en la UPC. Soy hábil con las TICs y soy una persona creativa para proporcionar ideas innovadoras. Aprendo de forma rápida nuevos temas al practicarlos y se me da bien la programación y la solución de errores.

![paolo](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/db493790-9513-4fc1-b5de-e335d63043fe)

## 1.2. Solution Profile

En el presente punto, se pasará a la explicación detallada del producto solución, factor innovador y la forma en la cual será monetizada.

**Product Name**

La aplicación web recibirá el nombre “Ayni”, debido a que, en el lenguaje quechua, es un concepto de reciprocidad o mutualismo entre comunidades andinas. Además, se puede interpretar como un verbo, que se refiere a la cooperación entre miembros cuando un miembro brinda apoyo a otro, teniendo el derecho a recibir algo a cambio. Este concepto está presente en etnias que viven en Perú, Ecuador y Bolivia. 

**Product Description**

El software es innovador ya que se encarga de ofrecer un sistema de gestión para productos agrícolas que mejore la calidad de su producción para su venta o exportación con herramientas de registro, notificación y planificación. Debido a ello, está enfocado principalmente a los productores de cultivos, en donde ellos pueden hacer un plan de cultivo, registrar parcelas, gestionar insumos, obtener un historial de cultivos, gestionar sus costos y gastos y atender pedidos. Por otro lado también tenemos a los exportadores, que pueden realizar pedidos a los productores y dejar reseñas acerca de los servicios brindados.

**Monetización**

Nuestra aplicación será monetizada a través de publicidad sobre insumos para cultivar, de esta manera se cobrará por la aparición de publicidad en la aplicación a proveedores de insumos. De esta manera, nuestra aplicación se volverá un entorno completo para que los productores mejoren sus productos con los insumos que serán publicitados en la aplicación (libre elección de compra).

### 1.2.1 Antecedentes y problemática

En los últimos años, el sector agrícola en el Perú, ha presentado una tasa de empleo durante el segundo trimestre del año 2020 un aumento de un 22.6% y en el tercero, un 20.5%, a pesar de que la población ocupada a nivel nacional se contrajo un 39.6% y un 17.1% en dichos periodos, respectivamente, con respecto a los mismos de 2019, según el Instituto Nacional de Estadística e Informática (INEI). Asimismo, si bien el PBI nacional acumulado al tercer trimestre disminuyó un 14.5% con respecto al mismo periodo del año pasado, el PBI agropecuario aumentó un 0.8%, uno de los mejores resultados, según cifras del Banco Central de Reserva del Perú. Desafortunadamente, este sector no se libra de los diversos problemas para progresar pese a ser uno de los sectores más importantes para el desarrollo de Perú. Esta situación es resaltada por Moreno (2022, como se citó en Coordinadora de Entidades Extranjeras de Cooperación Internacional, 2022), quien expresó su preocupación por la situación precaria de los cultivos en los últimos años entre uno de los problemas que atraviesa el 24% de los empleados que pertenecen al sector agrario.

**Herramienta 5W y 2H**

**¿Qué? (What)**

Según el Ministerio de Desarrollo Agrario y Riego (MIDAGRI, 2022), las actividades agrarias son reconocidas por el desorden en la producción y la baja rentabilidad y competitividad. Por lo tanto, el problema identificado es la informalidad y el desorden en el proceso de producción y venta de los productos agrícolas, en consecuencia, se obtienen productos de mala calidad y ventas que si bien son de primer contacto entre productores y comerciantes, los precios tienden a ser regateados.

**¿Cuándo? (When)**

Este es un problema que se puede observar en todo en los grupos que se dedican a la producción de cultivos de manera informal, tradicional o incluso en cadenas de producción. Este problema está presente en todo el proceso de cultivo de los productos, además en todas 
las horas de trabajo de los agricultores se necesitan seguir una serie de pasos, donde estos pueden fallar durante el proceso ocasionando bajas en la calidad de los productos.

**¿Dónde? (Where)**

Para especificar dónde residen las problemáticas tenemos que observar el comportamiento de los mismos productos, por lo tanto, sus precios. Existen diversos factores que explicarían una contracción en los precios que reciben los agricultores. Por ejemplo, respecto de las papas, el MIDAGRI reporta que sus ingresos por kilogramo se redujeron, en promedio, a S/ 0.89, cuando en el mismo periodo de 2019 ascendían a S/ 1.08. Además, también se registró un incremento considerable de la producción nacional durante los primeros cuatro meses del año 2019, pues se acumuló un aumento interanual del 13.9%, mientras que en el mismo periodo esta apenas creció un 3.9%, lo que no fue respondido adecuadamente por la demanda y generó una disminución inicial de los precios. Posteriormente, la agudización de la presente crisis económica perjudicó considerablemente la masa salarial, lo cual implicaría un menor consumo de lo habitual y limitaría su recuperación. 

**¿Quién? (Who)**

Los principales afectados por las problemáticas relacionadas al sector agrario, según el INEI (2022), en el segundo trimestre del año 2022, 4.1 millones de personas trabajaron en el sector agrícola. Como se puede apreciar, esta cifra es considerablemente alta para abarcar tanto a los productores de cultivos como a los exportadores o comercializadores.

**¿Por qué? (Why)**

Moreno (2022, como se citó en CEECI, 2022) resaltó las causas de los problemas estructurales del sector agrario, entre ellos está el bajo nivel de desarrollo competitivo, la baja integración de los productores en la cadena de valor, el alto índice de familias de productores con escaso acceso al mercado y el inadecuado uso de recursos naturales en la producción.

**¿Cómo? (How)**

Este problema se diferencia bastante a la situación normal del sector agrícola, debido a que representan cifras de pérdidas de millones de soles bastante considerables con respecto a otros años. Esta tendencia si bien se mantiene constante debido a problemas tales como crisis, condiciones climáticas, erosiones de suelo, etc. En la pandemia COVID - 19 se tuvo un declive gracias al distanciamiento social.

**¿Cuánto? (How Much)**

El problema del bajo rendimiento de los cultivos en Perú se refleja en una pérdida diaria de hasta S/50,8 millones de soles debido a condiciones climáticas y falta de calidad en los productos según la Cámara de Comercio de Lima (2023). Por otro lado, en el año 2020 debido a la pandemia se obtuvo una pérdida por S/1611 millones de soles, producto de las medidas de aislamiento ante el COVID-19 (Gobierno de la República, 2020). Todas estas pérdidas siguen significando heridas para el sector agrícola, debido a ello, aún no se logra recuperar del todo.

**Conclusiones de las 5W + 2H**

Luego de haber desarrollado las 5W’s y 2H’s se logró desarrollar una visión general sobre la problemática, cuyo alcance es de ámbito nacional. Para conseguir resultados verídicos y garantizar el funcionamiento de la aplicación, se optará por presentar el producto solución a un público nacional. Existen pocas soluciones actuales a la problemática, para erradicar estas problemáticas se desarrollará una aplicación que permita la gestión de productos agrícolas que permita a los productores realizar funciones de mantenimiento tales como planificación de cultivos personalizado y no personalizado, registro de gastos y ganancias, gestión de insumos, reportes de producción y calidad y control de plagas. Por otro lado, como función de secuencia o tipo flujo dirigida a los comerciantes, tal que pueden realizar la compra de productos, que se compone de una búsqueda, venta y validación. Asimismo, se contará con un sistema de calificación y reseñas que se mostrará luego de realizar un pedido o compra. Tanto los productores y comerciantes accederán a la aplicación mediante un dispositivo electrónico con conexión a internet; las computadoras junto con un navegador serán el principal medio de acceso para la aplicación.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.

El propósito de “Ayni” es proporcionar al sector agrícola una solución tecnológica integral que permita planificar, monitorear y optimizar de manera eficiente las diversas actividades realizadas durante todas las etapas de producción de los cultivos. Esta solución responde a la problemática de la ausencia de una planificación precisa que permita a los agricultores manejar sus cultivos de manera adecuada y lograr una cosecha fructífera.

Actualmente, existen pocas aplicaciones de plataformas que ofrecen soluciones orientadas a la gestión de los cultivos en el sector agrícola. En ese sentido, nuestra plataforma busca ingresar al mercado como una alternativa diferenciadora, con el propósito de resolver los problemas a los que se enfrentan los productores agrícolas.

Sin embargo, hemos observado un factor crítico que perjudica la productividad agrícola: la falta de una herramienta integrada que permita tomar decisiones de manera informada. Como consecuencia, se hace un uso ineficiente de los recursos naturales y el rendimiento del terreno se reduce.

A partir de lo anterior, resulta posible plantear la principal interrogante que el proyecto propone resolver:

**¿Cómo mejorar el proceso de cultivo y la gestión de los recursos en el sector agrícola?**

#### 1.2.2.2. Lean UX Assumptions.

**Business Outcomes:**

Incremento de las transacciones de compra de productos agrícolas en un 30%.
Incrementar el número de usuarios de la plataforma de un 40%
Obtener ganancias a partir de los anuncios de insumos publicados en la plataforma.

**Users:**

Productores agrícolas que desean gestionar eficientemente sus cultivos
Personas que deseen comprar los productos agrícolas para uso propio o distribución

**User Outcomes & Benefits:**

- Productores:
Acceso a un mercado más amplio de compradores de productos agrícolas.
Aumento de la eficiencia en la gestión del inventario.
Posibilidad de obtener retroalimentación por parte de los compradores, para mejorar la calidad de sus productos.

- Comercializadores:
Simplicidad en la búsqueda de productos agrícolas y la comparación entre ellas.
Seguridad y eficiencia a la hora de realizar el proceso de compra.
Posibilidad de tener acceso a toda la información detallada del producto.

**Features Assumptions**
- Imágenes e información detallada  sobre los productos agrícolas ofrecidos en línea
- Función de reseña y calificación hacia los productos adquiridos
- Sección para ingresar los gastos, ingresos y a partir de ello, estimar las ganancias.
- Calendario agrícola que muestra las actividades a realizar
- Anuncios de insumos agrícolas

**User Assumptions**

1. **¿Quién es el usuario?**
Los usuarios de nuestra plataforma son pequeños y medianos agricultores que desean mejorar la gestión de sus cultivos. Asimismo, también está dirigido a las personas interesadas en comprar productos frescos y de calidad directamente de los productores.
2. **¿Dónde encaja nuestro producto en su trabajo o vida?**
Nuestro producto encaja en la vida diaria de los agricultores, debido a que les brinda una herramienta digital que les permite planificar, registrar y dar un seguimiento a todas las actividades agrícolas de manera más eficiente. Por otro lado, los compradores pueden encontrar y adquirir diversos productos agrícolas de buena calidad en nuestra plataforma.
3. **¿Qué problemas tiene nuestro producto? ¿Evitar?**
Nuestro producto puede enfrentar algunos desafíos como la percepción de ser compleja de usar por algunos agricultores. Para evitar ello, la interfaz debe lucir sencilla e interactiva. Además, se pueden incluir tutoriales acerca de la funcionalidad de la aplicación. 
4. **¿Cuándo y cómo es nuestro producto? ¿Usado?**
Nuestra aplicación está diseñada para ser utilizada por el agricultor durante todo el proceso de cultivo, que va desde la siembra hasta la cosecha y posterior venta de los productos. Asimismo, es útil para programar actividades, registrar datos importantes y recibir reportes. Los compradores podrán buscar productos y realizar pedidos.

5. **¿Qué características son importantes?**
 Algunas funcionalidades importantes en la aplicación serán la programación de actividades, el registro de los gastos y las ganancias, la gestión de los insumos, control de plagas, reportes detallados en base a la información ingresada, entre otros. Por otro lado, los compradores podrán utilizar la aplicación para buscar productos agrícolas  de buena calidad, obtener información acerca de estos, realizar pedidos y acceder a un sistema de calificación y reseñas.

6. **¿Cómo debe verse nuestro producto y cómo comportarse?**
La interfaz de nuestro producto debe ser sencilla e intuitiva para simplificar  su uso. Además, el tiempo de respuesta de las funcionalidades debe ser rápido para que el usuario no pierda interés al momento de utilizar la aplicación.


**Business Assumptions**

1. **Creemos que nuestros clientes necesitan** una mejor planificación de sus actividades agrícolas para maximizar la eficiencia de sus cultivos.
2. **Estas necesidades se pueden resolver con una** aplicación web que brinda la posibilidad de gestionar adecuadamente los procesos agrícolas y que permite la compra de productos agrícolas.
3. **El valor #1 que mi cliente quiere de mi servicio** es la capacidad de aumentar su eficiencia al organizarse mejor mediante la aplicación y una dinámica de compra y venta sencilla.
4. **El cliente también puede obtener beneficios adicionales como** el acceso directo a los mercados mediante un sistema de compra entre los consumidores y productores. Gracias a ello, los productores pueden obtener mayores ingresos. 
5. **Voy a adquirir la mayoría de mis clientes** mediante el marketing de boca a boca, o el anuncio mediante redes sociales o la radio.
6. **Haré dinero a través de** la publicación de anuncios por parte de personas que quieran ofrecer servicios o productos destinados a los agricultores, tales como fertilizantes u otros pesticidas.
7. **Mi competencia principal en el mercado** serán otras aplicaciones que ofrecen un servicio similar al planteado para este proyecto.
8. **Los venceremos debido a la simplicidad** de uso de nuestra aplicación y a la combinación de funcionalidades únicas que permiten combatir con problemas específicos, como el control de plagas, entre otros.
9. **El mayor riesgo es que** los agricultores y los compradores no utilicen la aplicación por considerarla demasiado compleja de usar o simplemente resistirse al cambio.
10. **Resolveremos esto a través de** la agregación de funcionalidades útiles para ambos segmentos objetivos.

#### 1.2.2.3. Lean UX Hypothesis Statements.

- **Creemos que** los agricultores necesitan organizar sus actividades diarias. 
**Sabremos que hemos tenido éxito**
cuando nuestra aplicación se vuelva parte de su rutina para cosechar.

- **Creemos que** los agricultores necesitan gestionar sus costos e ingresos.
**Sabremos que hemos tenido éxito**
cuando nuestra aplicación ayude a la economía de los clientes y maximizar la calidad de sus productos

- **Creemos que** los comerciantes o exportadores necesitan comprar productos de calidad y contacto directo con los productores
  **Sabremos que hemos tenido éxito**
cuando nuestra aplicación se vuelva el principal medio de comercio entre productores y comerciantes

- **Creemos que** los comerciantes deben calificar los productos que compraron 
**Sabremos que hemos tenido éxito**
cuando las calificaciones sustenten la calidad de los productos de los productores dentro de la aplicación

- **Creemos que** generamos ganancias por publicidad de insumos para agricultura dentro de la aplicación
**Sabremos que hemos tenido éxito**
cuando recibamos los fondos por brindar la publicidad a los proveedores de insumos

#### 1.2.2.4. Lean UX Canvas.

![canva](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/c0507000-b2bd-4708-b688-8caa5942e26e)

### 1.3. Segmentos objetivo.

| Tipo de Usuario | Productores que deseen mejorar la calidad de sus cultivos | Exportadores que deseen comercializar productos de calidad | 
| - | - | - |
| Geografico | País: Perú <br> Zona residencial: Zonas rurales que cuentan con campos de cultivo | País: Perú <br> Zona residencial: Zona aledaña a campos de cultivo |  
| Psicográfico | Clase Social: Media - Baja <br> Estilo de Vida: Deben ser personas con conocimientos familiares o técnicos de cultivos, que participen activamente en el cuidado de una parcela para obtener ganancias de la cosecha. | Clase social: No es relevante dado que pueden ser comerciantes independientes o entidades en conjunto. <br> Estilo de vida: Deben ser personas que se dedican a la compra/venta de productos agrícolas con contacto directo con los productores. |  
| Demográfico | Edad: 20-50 <br> Nivel de Ingreso: No es relevante, pues está dirigido a cualquier persona pero que se dedique a la producción de cultivo | Edad: 20-50 <br> Nivel de ingreso: No es relevante. | 


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.

**Ayni:**

![Ayni]()

Es una solución tecnológica integral en el campo agrícola, enfocada en elevar la eficiencia mediante la gestión agrícola y la dinámica de compra y venta. Su propuesta única radica en la eliminación de intermediarios, permitiendo a agricultores y comerciantes conectarse directamente para maximizar ingresos. Además, ofrece herramientas para la planificación y el monitoreo de actividades diarias, junto con la gestión de costos e ingresos.

**Agroptima:**

![Agroptima](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751325-58bb3ea1-e6b2-4ca1-ae64-d4ef889a7618.png)

Agroptima se destaca por su enfoque en la planificación agrícola y la mejora de la eficiencia en la gestión de cultivos. Ofrece herramientas para la planificación de labores y el seguimiento de actividades diarias. La plataforma brinda la capacidad de tomar decisiones basadas en datos precisos, ayudando a los agricultores a optimizar su producción y cosecha.

**Granular (Corteva Agriscience):**

![Corteva](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751271-ea49e5f2-819b-4bb6-8b32-01969ff9e374.png)

Granular es una solución integral que abarca desde la planificación hasta el análisis en la gestión agrícola. Con un amplio rango de funcionalidades, la plataforma busca mejorar la eficiencia y la toma de decisiones informadas. A través de ejemplos concretos y casos de éxito, Granular demuestra cómo su enfoque integral puede impulsar los resultados de los agricultores.

**FarmLogs (Climate FieldView):**

![Farmlogs](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751278-b5539362-f7a2-4aba-8d6a-767283b3edcf.png)

FarmLogs se concentra en mejorar el seguimiento de cultivos y la toma de decisiones basada en datos. La plataforma ofrece información en tiempo real para respaldar la toma de decisiones informada. Con contenido educativo y asociaciones con expertos en agricultura, FarmLogs empodera a los agricultores con herramientas para optimizar sus operaciones agrícolas.


### 2.1.1. Análisis competitivo.



<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 15%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 18%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th rowspan="2">¿Por qué llevar a cabo este análisis?</th>
<th colspan="5">Escriba en el recuadro la pregunta que busca responder o
el objetivo de este análisis.</th>
</tr>
<tr class="odd">
<th colspan="5">Llevar a cabo este análisis permite identificar las
ventajas competitivas y oportunidades de mejora de "" frente a
competidores clave, informando estrategias efectivas para destacar en el
mercado agrícola y atraer a agricultores y comerciantes.</th>
</tr>
<tr class="header">
<th></th>
<th></th>
<th>Ayni</th>
<th>Agroptima</th>
<th>Granular</th>
<th>FarmLogs</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil</th>
<th>Overview</th>
<th>"Ayni" es una solución tecnológica integral para la gestión de
actividades agrícolas que incluye planificación, monitoreo y
optimización de procesos.</th>
<th>Busca mejorar la planificación y el monitoreo de actividades
agrícolas para aumentar la eficiencia y optimizar los procesos en el
sector agrícola.</th>
<th>Granular es una plataforma integral de gestión agrícola que busca
mejorar la planificación, administración y análisis de operaciones
agrícolas.</th>
<th>FarmLogs es una plataforma que busca mejorar el seguimiento de
cultivos y la toma de decisiones basada en datos en la agricultura.</th>
</tr>
<tr class="header">
<th>Ventaja competitiva</th>
<th>Ofrece una plataforma única para la gestión agrícola y la dinámica
de compra y venta</th>
<th>Ofrece herramientas para la planificación de cultivos y el
seguimiento de labores, lo que ayuda a los agricultores a ser más
organizados.</th>
<th>Ofrece una plataforma completa para la gestión agrícola, abordando
aspectos desde la planificación hasta el análisis.</th>
<th>Ofrece herramientas para el seguimiento de cultivos y la
planificación de labores, lo que ayuda a los agricultores a tomar
decisiones informadas.</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil de Marketing</th>
<th>Mercado Objetivo</th>
<th>Agricultores, productores agrícolas y comerciantes que buscan
mejorar la eficiencia en la gestión de cultivos y la dinámica de
comercio.</th>
<th>Agricultores y productores agrícolas que buscan mejorar la
planificación y la gestión de sus cultivos.</th>
<th>Agricultores y productores agrícolas que buscan una solución
integral para la gestión agrícola.</th>
<th>Agricultores y productores agrícolas que buscan mejorar el
seguimiento y análisis de sus cultivos.</th>
</tr>
<tr class="header">
<th>Estrategias de marketing</th>
<th>Colabora con cooperativas agrícolas y comerciantes locales para
aumentar la visibilidad de la plataforma.</th>
<th>Utiliza videos educativos, webinar y eventos en línea.</th>
<th>Muestra casos de estudio y participa en ferias agrícolas para
promover la plataforma.</th>
<th>Colaboración con expertos en agricultura y agrónomos. Hace uso de
blogs.</th>
</tr>
<tr class="odd">
<th rowspan="3">Perfil de Producto</th>
<th>Productos &amp; Servicios</th>
<th>Planificación, monitoreo de actividades diarias, gestión de costos e
ingresos, dinámica de compraventa, calificación de productos y
publicidad de insumos.</th>
<th>Plataforma de gestión agrícola que incluye planificación de cultivos
y seguimiento de labores.</th>
<th>Plataforma de gestión agrícola con amplias características para
planificación, análisis y toma de decisiones.</th>
<th>Plataforma de gestión agrícola con herramientas para el seguimiento
y análisis de cultivos.</th>
</tr>
<tr class="header">
<th>Precios y Costos</th>
<th>Estructura de precios basada en suscripciones o uso.</th>
<th>Estructura de precios basada en suscripciones o uso.</th>
<th>Estructura de precios basada en suscripciones o uso.</th>
<th>Estructura de precios basada en suscripciones o uso.</th>
</tr>
<tr class="odd">
<th><p>Canales de distribución</p>
<p>(Web y/o Móvil)</p></th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
</tr>
<tr class="header">
<th rowspan="5">Análisis SWOT</th>
<th colspan="5">Realice esto para su startup y sus competidores. Sus
fortalezas deberían apoyar sus oportunidades y contribuir a lo que
ustedes definen como su posible ventaja competitiva.</th>
</tr>
<tr class="odd">
<th>Fortalezas</th>
<th>Enfoque en la gestión agrícola y la dinámica de compra y venta, lo
que agrega un valor único. Plataforma integral.</th>
<th>Enfoque en la planificación y el monitoreo agrícola. Herramientas
para la toma de decisiones.</th>
<th>Solución integral que aborda múltiples aspectos de la gestión
agrícola. Enfoque en la toma de decisiones.</th>
<th>Enfoque en el seguimiento de cultivos y la toma de decisiones basada
en datos. Datos en tiempo real.</th>
</tr>
<tr class="header">
<th>Debilidades</th>
<th>Puede enfrentar resistencia al cambio debido a la complejidad
percibida por algunos usuarios.</th>
<th>Puede carecer de funcionalidades adicionales como la dinámica de
compra y venta.</th>
<th>Puede ser percibido como complejo para algunos usuarios debido a su
amplia gama de características.</th>
<th>Puede carecer de funcionalidades adicionales como la dinámica de
compra y venta.</th>
</tr>
<tr class="odd">
<th>Oportunidades</th>
<th>Crear alianzas estratégicas con cooperativas agrícolas y
comerciantes locales para aumentar la adopción.</th>
<th>Expandir el alcance al ofrecer características adicionales para la
gestión de costos e ingresos.</th>
<th>Incorporar características adicionales que se centren en la dinámica
de compra y venta.</th>
<th>Incorporar características adicionales relacionadas con la compra y
venta para atraer a más agricultores y comerciantes.</th>
</tr>
<tr class="header">
<th>Amenazas</th>
<th>Competencia de soluciones establecidas en el mercado. Cambios en las
preferencias de los usuarios.</th>
<th>Competencia de soluciones integrales que también abordan la dinámica
de compra y venta.</th>
<th>Competencia de soluciones específicas que también se enfocan en la
dinámica de comercio.</th>
<th>Competencia de soluciones integrales que también abordan la dinámica
de comercio.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.


| Estrategia/ Táctica                          | Medidas a tomar                                         |
|----------------------------------------------|---------------------------------------------------------|
| Diferenciación en Dinámica de Compra y Venta | \- Destacar la ventaja de la compra y venta directa.    |
|                                              | \- Resaltar la eliminación de intermediarios.           |
|                                              | \- Alianzas con comerciantes para impulsar compradores. |
| Enfoque en la Economía                       | \- Maximizar rentabilidad y gestionar costos.           |
|                                              | \- Ofrecer herramientas de análisis económico.          |
| Publicidad de Insumos Agrícolas              | \- Resaltar acceso a insumos de calidad.                |
|                                              | \- Colaboraciones con proveedores de insumos.           |


## 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.

**Segmento Objetivo: Productores que quieren mejorar la calidad de sus ventas**
- **Preguntas principales**
  - En términos de cantidad, ¿considera que su producción es al por mayor o al por menor?
  - ¿Qué es lo que normalmente siembra en sus terrenos?
  - ¿Cómo es que vende lo que produce?
  - ¿Usted define el precio de venta o lo que hacen sus compradores?
  - Si el comprador es quien establece los precios, ¿considera que es adecuado?
  - ¿Alguna vez ha vendido sus productos a un precio bajo solo para vender todo lo que tenía?
  - ¿Le resulta difícil vender todo lo que produce?
  - Si no logra vender todo lo cosechado, ¿qué hace con la cantidad sobrante?
  - ¿Cuáles son sus objetivos a futuro con respecto a la producción de sus cultivos?
  - ¿Cuáles son las principales frustraciones que ha enfrentado en su trabajo como agricultor?

- **Preguntas de ámbito de gestión:**

  - ¿Para usted es complicado manejar las fechas durante todo el proceso de siembra? ¿Qué dificultades tiene?
  - ¿Se le olvidan las fechas en las que debe abonar o regar sus cosechas?
  - ¿Cómo gestiona normalmente sus cosechas?
  - ¿Qué datos considera importantes tener en cuenta para un seguimiento adecuado?
  - ¿Cómo evaluar que sus productos tienen una calidad superior luego de la cosecha?
  - ¿Qué tipo de dispositivos son de su preferencia o uso personal para el uso de programas o aplicaciones?
  - ¿Qué plataformas o redes sociales utilizan regularmente para adquirir información?
  - ¿Alguna vez ha usado una aplicación o programa que le ayude en la gestión?
  - Si tuviera la oportunidad de usar una aplicación que le ayude a gestionar sus siembras con un seguimiento de fechas y recomendaciones, ¿la utilizaría?
  - ¿Qué características considera importantes que deben incluirse en la aplicación?
  - ¿Qué canales de comunicación prefiere utilizar si necesita ayuda y capacitación?
  - ¿Cuál es el navegador que utiliza para acceder a internet?

**Segmento Objetivo: Comerciantes que quieren mejorar la calidad de sus ventas**
- **Preguntas principales**
  - En términos de cantidad, ¿considera que sus ventas son al por mayor o al por menor?
  - ¿Qué es lo que normalmente busca de los productos agrícolas?
  - ¿Cómo es que compra lo que desea comerciar?
  - ¿Usted define el precio de venta o lo hacen los productores?
  - Si el vendedor es quien establece los precios, ¿considera que es adecuado?
  - ¿Alguna vez ha comprado sus productos a un precio bajo solo para tener algo que vender?
  - ¿Le resulta difícil comprar lo que se ofrece en el mercado actual?
  - ¿Cuáles son sus objetivos a futuro con respecto a la exportación de productos agrícolas?
  - ¿Cuáles son las principales frustraciones que ha enfrentado en su trabajo como exportador?
- **Preguntas de ámbito de gestión**
  - ¿Para usted es complicado encontrar a productores para comprar sus productos? ¿Qué dificultades tiene?
  - ¿Se olvida de los pedidos que tiene pendiente a menudo?
  - ¿Cómo gestiona normalmente sus exportaciones?
  - ¿Qué datos considera importantes tener en cuenta para un seguimiento adecuado de la compra de productos?
  - ¿Cómo evaluar que los productos tienen una calidad superior luego de su compra?
  - ¿Qué tipo de dispositivos son de su preferencia o uso personal?
  - ¿Qué plataformas o redes sociales utilizan regularmente para adquirir información?
  - ¿Alguna vez ha usado una aplicación o programa que le ayude en la gestión?
  - Si tuviera la oportunidad de usar una aplicación que le ayude a realizar la compra de productos para exportar, ¿la utilizaría?
  - ¿Qué características considera importantes que deben incluirse en la aplicación?
  - ¿Qué canales de comunicación prefiere utilizar si necesita ayuda y capacitación?
  - ¿Cuál es el navegador que utiliza para acceder a internet?

### 2.2.2. Registro de entrevistas.

**Segmento Objetivo: Productores que quieren mejorar la calidad de sus ventas**

Entrevistado 1:

Nombre y apellidos: Jerónimo Vilcamiza Saldaña
Edad: 41 años
Distrito: El carmen - Chincha
Url: [Video Microsoft Teams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EXc-uBMZqwpIlzsRikopK7QByS0Aly3640gv24rnaIIqgg?e=nq1dGR)
Inicio: 0:00 
Fin: 7:43
Duración: 7:43

![entrevista1](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/8a677388-1d07-4e19-b9b4-0decb701f59a)

Resumen de la entrevista:
El entrevistado fue Don Gerónimo Vilcamiza Saldaña, él es un agricultor de 41 años que reside en el distrito de El Carmen, en la provincia de Chincha. Él nos menciona que  posee un terreno, donde normalmente cultiva maíz o palto. Asimismo, menciona que  indica que al momento de la cosecha, ofrece sus productos al por mayor a los intermediarios. En algunas ocasiones acepta precios bajos con el fin de no desperdiciar sus productos. No obstante, si eso sucede, comercializa sus productos en el mercado local.

Entrevistado 2:

Nombre y apellidos: Gian Ismael Castillón Paucar
Edad: 28 años
Distrito: El carmen - Chincha
Url: [Video Microsoft Teams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EXc-uBMZqwpIlzsRikopK7QByS0Aly3640gv24rnaIIqgg?e=nq1dGR)
Inicio: 7:43
Fin: 18:53
Duración: 11:10

![entrevista2](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/dcc9c0b5-2698-4a89-9afd-f3418cba35a2)

Resumen de la entrevista:

El entrevistado fue Gian Castillón Paucar, un jóven de 28 años que se dedica a la agricultura desde muy temprana edad, al igual que toda su familia. Se considera una persona perseverante, responsable y dedicada. Su principal cultivo es la palta y la pitahaya. Gian menciona que el precio es definido por los compradores y que ello generalmente se basa en la calidad del producto y la dinámica del mercado. Si no logra vender todos sus productos, lo ofrece en el mercado local. A futuro, planea obtener mayor producción de sus plantas de palto. Sin embargo, a veces enfrenta desafíos, como la falla de los motores, lo cual desencadena una alteración en el cronograma de riego. Gian nos comenta también que a veces es complicado organizarse, por ello utiliza un programa de excel y word para anotar las fechas de todas sus actividades agrícolas. Por último, la creación de una aplicación web que le ayude a organizarse le parece una gran idea. Sin embargo, cree que la aplicación debería brindar información adicional sobre los procesos de crecimiento de su planta.

Entrevistado 3:

Nombre y apellidos: Rolando Salvatierra
Edad: 50
Región: Junín 
Url: [Video Microsoft Teams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EXc-uBMZqwpIlzsRikopK7QByS0Aly3640gv24rnaIIqgg?e=nq1dGR)
Inicio: 18:53
Fin: 27:02
Duración: 08:09

![entrevsitado3](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/dc54cc29-50a7-46f8-8929-9ca4a2a5bc83)

Resumen de la entrevista:

 El entrevistado fue Rolando Salvatierra un agricultor de 50 años del departamento de Junín. Como agricultor considera que sus cosechas son enfocadas a una producción al por mayor, con respecto a sus sembríos son realizados dependiendo a la temporada del año siendo los principales productos maíces, papas y zanahorias. La venta de sus productos se efectúa cuando el comprador va hacia ellos ofreciéndo un precio según el mercado, además, comenta que hubo veces en donde sus productos no fueron vendidos en su totalidad y para poder terminar sus ventas tuvo que venderlas a un precio menor al promedio según el mercado. Con respecto a la gestión de sus sembríos no se le hace complicado porque lleva años en el rubro, sin embargo, también hay veces en que se le olvida las fechas de ciertas actividades por lo que considera que la aplicación le ayudaría mucho para poder tener una cosecha de calidad y considera que el uso de las redes sociales y servicio de videollamadas como Zoom son una buena forma de capacitación para el uso de la app.

**Segmento Objetivo: Comerciantes que quieren mejorar la calidad de sus ventas**

Entrevistado 4: 

Nombre y apellidos: André Luna
Edad: 25
Distrito: Lince - Lima
Url: [Video Microsoft Teams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EXc-uBMZqwpIlzsRikopK7QByS0Aly3640gv24rnaIIqgg?e=nq1dGR)
Inicio: 27:02
Fin: 35:37
Duración: 08:35

![entrevistado4](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/289905bc-abd5-4a1a-994b-9855c7e7e673)

Resumen de entrevista:

El entrevistado fue Andre Luna, un joven de 25 años que se dedica a ser asistente en un grupo de comercio de frutas y verduras desde hace unos años. Andre menciona que los precios son bien definidos por los productores y que se basa en la calidad de producto, la disponibilidad del producto y la temporada en la cual son cultivadas. A futuro se plantea crear una empresa o marca propia de comercio de productos agrícolas con reconocimiento a nivel nacional. SIn embargo, a veces tiene frustraciones como la desorganización e incumplimiento de los productores en lo acordado. André nos comentó que utilizó programas para manejar ventas o reuniones usando excel, pero que no es lo suficientemente eficiente para cumplir todas sus funciones de asistente de comerciante. Por último, la creación de una aplicación web que responda a sus principales inconvenientes para organizarse le parece una idea innovadora. Sin embargo, el desea que la principal funcionalidad sea la de buscar productos y poder hacer una compra con contacto directo con el vendedor.

Entrevistado 5:

Nombre y apellidos: Favio Onofre
Edad: 24
Distrito: Santiago de Surco - Lima
Url: [Video Microsoft Teams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EXc-uBMZqwpIlzsRikopK7QByS0Aly3640gv24rnaIIqgg?e=nq1dGR)
Inicio: 35:37
Fin: 44:03
Duración: 08:26

![entrevistado5](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/1db9b603-0d51-4cd1-a8f1-a06507ad8ec9)

Resumen de entrevista:
El entrevistado es Favio Onofre, un joven de 25 años que se dedica a ser asistente en un comercio familiar de venta de productos agrícolas. Favio nos comenta que la calidad es la prioridad de los productos que vende de tipo al por mayor, debido a ello en su lugar de trabajo tienen un proceso de calidad por el cual someten al producto a una serie de pasos. Por otro lado, nos dice que los precios se negocian según los acuerdos de los productores dado que ellos son los que generan la ganancia. A futuro quiere mejorar la calidad de los productos que vende siendo reconocido a nivel internacional. También, nos comentó que los inconvenientes que presentó en su trabajo fueron la desorganización de las compras o el contacto de proveedor. Por último, la creación de una aplicación web ayudaría mucho a su trabajo ya que facilita el contacto con los productores para concretar ventas.

Entrevistado 6:

Nombre y apellidos: Juli Carrión
Edad: 45
Distrito: Surco - Lima
Url: [Video Microsoft Teams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EXc-uBMZqwpIlzsRikopK7QByS0Aly3640gv24rnaIIqgg?e=nq1dGR)
Inicio:44:03
Fin: 48:53
Duración: 04:50

![entrevsitado 6](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/0a0a8d9e-5582-49dc-9bf7-1976f0e1cad1)

Resumen de entrevista: 
La entrevistada es Juli Carrión, una mujer de 45 años que se dedica a ser asistente en un pequeño comercio de venta de productos agrícolas. Juli nos dice que vende sus productos al por mayor. Además, que gestiona sus ventas de manera tradicional pero conservando la preferencia por la calidad de los productos que compra para posteriormente vender. Lamentablemente, tuvo que optar por decisiones tales como vender a bajo precio lo que le sobraba de productos, eso refleja una mala manera de gestionar los productos. Relacionado a ello, tuvo experiencias malas de que los proveedores de productos a veces no cumplen con su parte del trato incluso poniendo precios muy altos en la negociación. Sin embargo, ella piensa que una aplicación web que le ayude a comprar productos y hacerles un seguimiento, arreglaría sus problemas para sus ventas. Por último, nos dice que su dispositivo de preferencia es el celular, y el navegador que más usa es Google Chrome.

### 2.2.3. Análisis de entrevistas.

**Segmento Objetivo: Productores que quieren mejorar la calidad de sus ventas**

**Preguntas principales**

  - **En términos de cantidad, ¿considera que su producción es al por mayor o al por menor?**
  
    - El 100% de nuestros entrevistados consideran que su cosecha está destinada a realizar ventas al por mayor, sin embargo, hay casos donde para terminar todo el producto deciden vender sus cosechas al por menor.

- **¿Qué es lo que normalmente siembra en sus terrenos?**
  
  - Nuestros entrevistados tienen una variedad de cultivos entre los mencionados están el maíz, la palta, papas y zanahorias.

- **¿Cómo es que vende lo que produce?**
  
  - El 40% de nuestros entrevistados ofrecen sus cultivos a los compradores que visitan su puesto de venta al momento de la cosecha o en fechas cercanas a esta y el 60% lo hacen mediante intermediarios.

- **¿Usted define el precio de venta o lo que hacen sus compradores?**
  
  - El 100% menciona que el precio es dado por los compradores teniendo en cuenta el mercado.

- **Si el comprador es quien establece los precios, ¿considera que es adecuado?**
  
  - El 60% consideran que el precio es adecuado porque lo definen dependiendo de la competencia existente en el mercado y el 40% dicen que el precio que le dan a veces es muy bajo por lo que no están de acuerdo.

- **¿Alguna vez ha vendido sus productos a un precio bajo solo para vender todo lo que tenía?**
  
  - El 100% de nuestros entrevistados dicen que alguna vez los productos que les sobraron los vendieron a un precio bajo para terminarlo y obtener ganancias.

- **¿Le resulta difícil vender todo lo que produce?**
  
  - El 40% de nuestros entrevistados dicen que no es tan complicado vender todo a sus compradores, mientras que el 60% mencionan que sí es complicado porque los compradores realizan una selección de los productos que quieren comprar.

- **Si no logra vender todo lo cosechado, ¿qué hace con la cantidad sobrante?**
  
  - El 100% de nuestros entrevistados dicen que si se da el caso de sobrar productos lo venden al por menor en el mercado local.

- **Cuáles son sus objetivos a futuro con respecto a la producción de sus cultivos?**
  
  - El 100% mencionan que siempre plantean como objetivo con cada nueva plantación el incrementar la productividad y poder obtener más ganancias.

- **Cuáles son las principales frustraciones que ha enfrentado en su trabajo como agricultor?**
  
  - El 60% mencionan que las fallas mecánicas y la escasez de agua retrasaron su calendario además de que reduce la calidad de su producción, mientras que el 40% restante mencionan que lo peor que les pasa es que el clima no deja que sus cultivos prosperen.

**Preguntas de ámbito de gestión:**

- **¿Para usted es complicado manejar las fechas durante todo el proceso de siembra? ¿Qué dificultades tiene?**
  
  - Para el 60% de nuestros entrevistados si se le hace complicado el recordar las fechas porque tienen muchas a tener en cuenta y el 40% restante mencionan que no les resulta difícil porque ya tienen costumbre.

- **¿Se le olvidan las fechas en las que debe abonar o regar sus cosechas?**
  
  - El 60% dicen que si se olvidaron una fecha importante que le afectó en un futuro, mientras que el 40% restante dicen que como llevan un cronograma definido es difícil que se les pase alguna fecha.

- **¿Cómo gestiona normalmente sus cosechas?**
  
  - El 100% de nuestros entrevistados mencionan que tiene un proceso a seguir y generalmente se basan en conseguir una buena calidad para sus productos.

- **¿Qué datos considera importantes tener en cuenta para un seguimiento adecuado?**
  
  - El 60% de nuestros entrevistados consideran que el tener un control de fechas es lo más importante para poder hacer un seguimiento continuo, mientras que el 40% restante mencionan que además de las fechas también es necesario tener en cuenta características de cada planta.

- **¿Cómo evaluar que sus productos tienen una calidad superior luego de la cosecha?**
  
  - El 100% de nuestros entrevistados nos cuentan que para determinar que sí tuvieron una buena cosecha se basan en el tamaño del cultivo, el color y si no fueron afectados por plagas.

- **¿Qué tipo de dispositivos son de su preferencia o uso personal para el uso de programas o aplicaciones?**
  
  - El 60% de nuestros entrevistados usan como principal herramienta su celular inteligente y el 40% restante además de hacer uso a los celulares también cuentan con laptops y herramientas especiales enfocadas en la agricultura.

- **¿Qué plataformas o redes sociales utilizan regularmente para adquirir información?**
  
  - El 100% de nuestros entrevistados mencionan que su principal fuente de información es el sitio web “Youtube”.

- **¿Alguna vez ha usado una aplicación o programa que le ayude en la gestión?**
  
  - El 40% de los entrevistados dicen que si uso aplicaciones como excel o word para ayudarse en la gestión, mientras que el 60% restante nunca usaron aplicaciones sino que se ayudaban con cuadernos o anotaciones.

- **Si tuviera la oportunidad de usar una aplicación que le ayude a gestionar sus siembras con un seguimiento de fechas y recomendaciones, ¿la utilizaría?**
  
  - El 100% de nuestros entrevistados mencionan que si les ayudaría mucho porque tendrán una aplicación que les ayude con las fechas facilitandoles la gestión previniendo que no ocurra errores por olvidarse el cronograma además de que automatiza el proceso gestión que realizan.

- **¿Qué características considera importantes que deben incluirse en la aplicación?**
  
  - El 100% de nuestros entrevistados consideran que necesitan tener cronogramas y una función que les ayude a identificar la etapa en la que se encuentra su cultivo.

- **¿Qué canales de comunicación prefiere utilizar si necesita ayuda y capacitación?**
  
  - El 60% de los entrevistados consideran que los canales que prefieren usar son las llamadas y reuniones y el 40% restante además de eso, también le gustaría el uso de redes sociales y aplicaciones de videollamada.

- **Cuál es el navegador que utiliza para acceder a internet?**
  
  - El 100% de nuestros entrevistados usan Google Chrome para hacer uso de internet.

**Segmento Objetivo: Comerciantes que quieren mejorar la calidad de sus ventas**

**Preguntas principales**

  - **En términos de cantidad, ¿considera que sus ventas son al por mayor o al por menor?**
  
    - El 100% de los encuestados sostienen que sus ventas la hacen al por mayor, debido a cuestiones de dinero en las negociaciones.

- **¿Qué es lo que normalmente busca de los productos agrícolas?**
  
  - El 60% de los encuestados nos dicen que buscan calidad, mientras que el otro 40% buscan buenos precios para proceder con su compra.

- **¿Cómo es que compra lo que desea comerciar?**
  
  - El 100% de los encuestados sostienen que su compra es con contacto directo con el productos a través de una red social.

- **¿Usted define el precio de venta o lo hacen los productores?**
  
  - El 80% de los encuestados dicen que el precio de venta lo definen los productores mientras que el 20% aseguran que sí lo definen los productores, no es rentable.

- **Si el vendedor es quien establece los precios, ¿considera que es adecuado?**
  
  - El 60% de los encuestados sostienen que en base a su experiencia los precios son adecuados. Sin embargo, el 40% restante considera que el precio no es el adecuado.

- **¿Alguna vez ha comprado sus productos a un precio bajo solo para tener algo que vender?**
  
  - El 100% asegura que sí, debido a la escasez de recursos financieros y la necesidad de generar ingresos.

- **¿Le resulta difícil comprar lo que se ofrece en el mercado actual?**
  
  - El 100% sostiene que no debido a que hay varios contactos de productores y canales donde se puede contactar con ellos, además de la disponibilidad de productos de distintas calidades.

- **Cuáles son sus objetivos a futuro con respecto a la exportación de productos agrícolas?**
  
  - El 100% de los encuestados desean mejorar su calidad de sus productos o formar una empresa reconocida a nivel nacional.

- **Cuáles son las principales frustraciones que ha enfrentado en su trabajo como exportador?**
  
  - El 100% de los encuestados tienen como frustraciones experiencias relacionadas a estafas y retraso del pedido.

**Preguntas de ámbito de gestión:**

- **¿Para usted es complicado encontrar a productores para comprar sus productos? ¿Qué dificultades tiene?**
  
  - El 60% de los encuestados no tienen dificultades debido a la disponibilidad de los productos, mientras que el 40% presentan dificultades debido a los canales o plataformas donde encontrar productores.

- **¿Se olvida de los pedidos que tiene pendiente a menudo?**
  
  - El 100% de los encuestados no presentan estos inconvenientes gracias a que usan aplicaciones de recordatorios de eventos o calendarios.

- **¿Cómo gestiona normalmente sus exportaciones?**
  
  - El 60% de los encuestados dice que maneja sus ventas en programas como excel o a simple lápiz y papel para gestionar sus exportaciones. Mientras que el 40% restante no usa programas en específico.

- **¿Qué datos considera importantes tener en cuenta para un seguimiento adecuado de la compra de productos?**
  
  - El 100% de los encuestados dice que es importante saber la fecha de salida de la producción, debido a que se puede estimar la llegada de este, asimismo contar con seguimiento a tiempo real.

- **¿Cómo evaluar que los productos tienen una calidad superior luego de su compra?**
  
  - El 60% sostiene que los superiores del lugar de trabajo tienen procesos especiales para evaluar la calidad mientras que el 40% dice que evalúa la calidad con una muestra previa de la producción solicitada.

- **¿Qué tipo de dispositivos son de su preferencia o uso personal?**
  
  - El 60% de los encuestados dice que usa computadoras o laptops, mientras que el 40% solo usa celulares.

- **¿Qué plataformas o redes sociales utilizan regularmente para adquirir información?**
  
  - El 100% dice que no usa plataformas pero usan Facebook para buscar productos y contactar con los productores.

- **¿Alguna vez ha usado una aplicación o programa que le ayude en la gestión?**
  
  - El 100% dice que no ha usado ninguna aplicación para la gestión de compras.

- **Si tuviera la oportunidad de usar una aplicación que le ayude a realizar la compra de productos para exportar, ¿la utilizaría?**
  
  - El 100% de los encuestados dice que una aplicación con esta característica le ayudaría bastante en el proceso de compra debido a que sería en un entorno más formal que el contacto directo.

- **¿Qué características considera importantes que deben incluirse en la aplicación?**
  
  - El 100% de los encuestados coincidieron que debe tener funcionalidades como la de contactar con el productor y seguimiento de la compra.

- **¿Qué canales de comunicación prefiere utilizar si necesita ayuda y capacitación?**
  
  - El 60% de los encuestados sostiene que desearían canales de ayuda en Youtube de manera de videos tutoriales mientras que el 40% prefiere tutoriales dentro de la aplicación web.

- **Cuál es el navegador que utiliza para acceder a internet?**
  
  - El 100% de los encuestados usan Google Chrome como navegador habitual en sus dispositivos.

## 2.3. Needfinding.
### 2.3.1. User Personas.


Pequeños y medianos agricultores

![UserPersona1](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751299-3402707f-97d9-4385-8d61-a5d0d7955ce3.png)

Comerciantes o exportadores

![UserPersona2](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751302-80e7ff52-e36b-4bac-93f6-f09c7e0daa5f.png)

Link para visualización de los user persona:

[<u>https://www.canva.com/design/DAFgyK-40QQ/jKAjVHUZpaVKD71oZ6i3qA/edit?utm_content=DAFgyK-40QQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton</u>](https://www.canva.com/design/DAFgyK-40QQ/jKAjVHUZpaVKD71oZ6i3qA/edit?utm_content=DAFgyK-40QQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)


### 2.3.2. User Task Matrix.


| COMERCIALIZADORES             | FRECUENCIA | IMPORTANCIA |
|-------------------------------|------------|-------------|
| Explorar productos agrícolas  | Always     | High        |
| Realizar pedidos de productos | Often      | High        |
| Gestionar pedidos y entregas  | Always     | Medium      |
| Evaluar calidad de productos  | Always     | High        |
| Evaluar demanda y tendencias  | Often      | High        |

| AGRICULTORES                     | FRECUENCIA | IMPORTANCIA |
|----------------------------------|------------|-------------|
| Planificar actividades agrícolas | Always     | High        |
| Control de costos y ganancias    | Often      | High        |
| Gestionar insumos agrícolas      | Always     | High        |
| Monitoreo de plagas              | Always     | Medium      |
| Acceder a reportes detallados    | Often      | Medium      |
| Realizar ventas                  | Often      | High        |

Link para la visualización de los User Task Matrix:

[<u>https://www.canva.com/design/DAFgyK-40QQ/jKAjVHUZpaVKD71oZ6i3qA/edit?utm_content=DAFgyK-40QQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton</u>](https://www.canva.com/design/DAFgyK-40QQ/jKAjVHUZpaVKD71oZ6i3qA/edit?utm_content=DAFgyK-40QQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

**Tareas con Mayor Frecuencia e Importancia:**

- Frecuencia:

> Respecto al segmento objetivo de agricultores las tareas con mayor
> frecuencia son planear actividades agrícolas, gestionar insumos
> agrícolas y el monitoreo de plagas. Respecto a los comercializadores
> las tareas que se realizan el mayor número de veces son explorar
> productos agrícolas, gestionar pedidos y entregas, y evaluar la
> calidad de los productos.

- Importancia:

> Respecto al segmento objetivo de comercializadores las tareas con
> mayor importancias son explorar productos agrícolas, realizar pedidos
> de productos, evaluar la calidad de productos y evaluar la demanda y
> tendencias de los productos. Por otro lado, con respecto al segmento
> de agricultores las tareas más relevantes son planificar actividades
> agrícolas, control de costos y ganancias, gestionar insumos agrícolas
> y realizar las ventas de estos mismo.

**Principales diferencias y coincidencias:**

La principal diferencia entre las tareas de nuestros segmentos objetivo
se encuentra en la tarea sobre el monitoreo de plagas, así como la
gestión de los insumos agrícolas. Puesto que, los agricultores tienen un
conocimiento bien construido de como poder cultivar los alimentos de
calidad que van a ser vendidos posteriormente y asegurarse de que estos
mismos sean de alta calidad. Mientras que los comercializadores tienen
menos conocimientos de cómo realizar estas tareas.

Las tareas con mayor coincidencias dentro de este recuadro pueden ser la
evaluación de calidad de los productos. Esto se evidencia, ya que, los
comercializadores tienen la tarea de revisar la evaluación de estos
productos mediante la tarea de reporte detallado que tendrán los
agricultores. Por lo que ambos intervienen a la hora de realizar la
evaluación de la calidad de los productos.

### 2.3.3. User Journey Mapping.


El User Journey Mapping se utilizó para visualizar de manera integral la
experiencia de los usuarios al interactuar con la plataforma.
Proporciona una representación detallada de cada paso que los usuarios
realizan, sus emociones, puntos de contacto y puntos de fricción a lo
largo del proceso. Esto permite comprender mejor cómo los usuarios
interactúan con la aplicación, identificar oportunidades de mejora y
alinear el diseño con sus necesidades reales.

Segmento 1: Agricultores

![UserJourneyMap1](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/265284905-9e9d15f3-d00d-4309-80ea-8552a89dac0d.jpeg)

Segmento 2: Comercializadores

![UserJourneyMap2](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/265284902-b2b8a006-08fd-448d-92f4-aa8f01c87844.jpeg)


### 2.3.4. Empathy Mapping.


![EmpathyMap1](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751285-bcb85957-8bd7-47fa-93aa-d5dcb7f0abee.png)

![EmpathyMap2](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751281-ba5274bf-8a83-42c1-8aaa-8e03434dfbdb.png)


### 2.3.5. As-is Scenario Mapping.


Se utilizó un "AS-IS Scenario Mapping" para comprender y documentar la
situación actual o el estado actual de las interacciones de los usuarios
con la plataforma. Este enfoque permite capturar de manera detallada
cómo los usuarios se enfrentan a la aplicación en su forma actual, sus
acciones, emociones y puntos de fricción.

![As-is](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/263751316-cc05531c-4789-4988-9ea7-a930a1f3aa9c.png)

Visualización de los As-Is Scenario Mapping:

[<u>https://miro.com/app/board/uXjVMQLNH9s=/?share_link_id=67585397072</u>](https://miro.com/app/board/uXjVMQLNH9s=/?share_link_id=67585397072)


# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.
En esta parte se utilizó el “TO-BE Scenario Mapping” para ello se hizo una representación visual de cómo deberían ser los procesos después de implementar las mejoras y cambios sugeridos. Es una parte crucial de la metodología de mejora de procesos y ayuda a las organizaciones a visualizar cómo podrían ser sus operaciones optimizadas en el futuro.
![ToBe](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/364e9acb-a307-4de6-95f4-20148221907f)
## 3.2. User Stories.

|Epic ID|Título de épica|Descripción de la épica|
| - | - | - |
|EP01|Definición de funcionalidades de la aplicación web|Como usuario deseo que la aplicación posea características funcionales variadas para que me sirva de ayuda al momento de cultivar, vender y planificar.|
|EP02|Opciones relacionadas a la cuenta del usuario|Como usuario deseo poder realizar acciones de creación, actualización y otras relacionadas a una cuenta para poder guardar las configuraciones y utilizarlas desde distintos dispositivos|
|EP03|Definición de estructura del landing page |Como usuario deseo disponer de un landing page con información pertinente para conocer mejor acerca de la aplicación web |
|EP04|Definición de requisitos no funcionales|Como usuario deseo que la aplicación web cumpla con estándares de rendimiento y optimización para utilizarla sin inconvenientes |

| Epic/Story | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| - | - | - | - | - |
|HU-01|Registro de cuenta|Como usuario, quiero poder registrarme en la aplicación para acceder a las funcionalidades disponibles.|<p>Escenario 01: Usuario registra su cuenta</p><p>Caso 1:</p><p>Dado que el usuario se encuentra en la sección de registro </p><p>Cuando el usuario ingrese sus datos para el registro</p><p>Entonces su cuenta es registrada en la aplicación.</p><p></p>|EP02|
|HU-02|Inicio de sesión|Como usuario, quiero iniciar sesión para poder ingresar a mi cuenta|<p>Escenario 01: Usuario inicia sesión</p><p>Caso 1:</p><p>Dado que el usuario ha registrado su cuenta previamente,</p><p>Cuando el usuario ingrese su dirección de correo electrónico y contraseña válida,</p><p>Entonces se le permite ingresar a su cuenta y acceder a las funcionalidades.</p><p></p>|EP02|
|HU-03|Explorar productos agrícolas|Como comercializador quiero observar los productos disponibles para poder realizar los pedidos|<p>Escenario 01: Comercializador explora productos disponibles</p><p>Caso 1:</p><p>Dado que el comercializador ha iniciado sesión en la aplicación,</p><p>Cuando el comercializador navegue a la sección de productos agrícolas,</p><p>Entonces se le muestran los productos disponibles para explorar.</p><p></p>|EP01|
|HU-04|Realizar pedidos de productos|Como comercializador, quiero poder realizar los pedidos de productos agrícolas para poder realizar las entregas|<p>Escenario 01: Comercializador realiza un pedido de productos</p><p>Caso 1:</p><p>Dado que el comercializador ha explorado los productos y ha seleccionado los que desea pedir,</p><p>Cuando el comercializador confirma el pedido y especifica las cantidades,</p><p>Entonces se registra el pedido y se notifica al comercializador sobre el proceso de entrega.</p><p></p>|EP01|
|HU-05|Seguimiento de Pedidos y Entregas|Como comercializador, quiero poder observar el estado de los pedidos y entregas para poder sentirme más tranquilo|<p>Escenario 01: Comercializador sigue el estado de un pedido en curso</p><p>Caso 1:</p><p>Dado que el comercializador ha realizado un pedido y desea rastrear su estado,</p><p>Cuando el comercializador accede a la sección de seguimiento de pedidos,</p><p>Entonces se le proporciona información actualizada sobre el estado del pedido.</p><p></p>|EP01|
|HU-06|Acceder a Calificaciones y Reseñas|Como comercializador, quiero acceder a las calificaciones y reseñas dejadas por los agricultores para saber sobre la valoración de mis servicios|<p>Escenario 01: Comercializador accede a las calificaciones y reseñas</p><p>Caso 1:</p><p>Dado que el comercializador desea evaluar la satisfacción de los agricultores con sus productos,</p><p>Cuando el comercializador accede a la sección de calificaciones y reseñas,</p><p>Entonces puede ver las evaluaciones y comentarios proporcionados por los agricultores.</p><p></p>|EP01|
|HU-07|Observar registro de pedidos y entregas realizadas|Como comercializador, quiero observar los pedidos y entregas realizadas, para poder tomar decisiones de acuerdo al análisis de los registros|<p>Escenario 01: Comercializador analiza registros de pedidos y entregas</p><p>Caso 1:</p><p>Dado que el comercializador busca tomar decisiones informadas sobre su operación,</p><p>Cuando el comercializador accede a los registros de pedidos y entregas realizadas,</p><p>Entonces puede analizar los datos para identificar tendencias y patrones.</p><p></p>|EP01|
|HU-08|Planificar actividades agrícolas|Como agricultor, quiero ingresar los datos correspondientes para la planificación de las actividades agrícolas|<p>Escenario 01: Agricultor planifica actividades para un ciclo de cultivo</p><p>Caso 1:</p><p>Dado que el agricultor ha ingresado a la sección de planificación,</p><p>Cuando el agricultor ingresa los datos relevantes para las actividades agrícolas,</p><p>Entonces el sistema registra el plan y lo refleja en el calendario.</p><p></p>|EP01|
|HU-09|Registro de gastos y ganancias|Como agricultor, quiero registrar los gastos y las ganancias relacionadas con mis actividades agrícolas para poder llevar un control financiero|<p>Escenario 01: Agricultor registra gastos y ganancias para un ciclo de cultivo</p><p>Caso 1:</p><p>Dado que el agricultor desea llevar un registro financiero detallado,</p><p>Cuando el agricultor ingresa los gastos y las ganancias relacionados con sus actividades,</p><p>Entonces el sistema almacena los registros para su consulta posterior.</p><p></p>|EP01|
|HU-10|Gestión de Insumos Agrícolas|Como agricultor, quiero llevar un registro de los insumos agrícolas utilizados para analizarlo y tomar decisiones de acuerdo a ello|<p>Escenario 01: Agricultor registra uso de insumos en un cultivo</p><p>Caso 1:</p><p>Dado que el agricultor necesita mantener un registro de los insumos utilizados,</p><p>Cuando el agricultor ingresa los insumos utilizados en un cultivo específico,</p><p>Entonces el sistema registra la información para su análisis y planificación.</p><p></p>|EP01|
|HU-11|Control de Plagas|Como agricultor, quiero tener herramientas para identificar y controlar las plagas para que no puedan afectar los cultivos|<p>Escenario 01: Agricultor registra observaciones de plagas en un cultivo</p><p>Caso 1:</p><p>Dado que el agricultor detecta signos de plagas en sus cultivos,</p><p>Cuando el agricultor registra las observaciones y los detalles de las plagas identificadas,</p><p>Entonces el sistema proporciona recomendaciones para el control y seguimiento de las plagas.</p><p></p>|EP01|
|HU-12|Atender pedidos|Como usuario deseo ver los pedidos que tengo de manera rápida y fácil en una pantalla |<p>Escenario 01:</p><p>El usuario agricultor quiere atender un pedido que le interesó.</p><p>Caso 01:</p><p>Dado que el usuario necesita vender sus productos</p><p>Cuando reciba un pedido dentro de la aplicación</p><p>Entonces podrá atenderlo accediendo a sus productos y seleccionando uno de ellos para ver aceptar o rechazar el pedido</p>|EP01|
|HU-13|Visualización de características de la aplicación web|Como usuario deseo ver las principales características de la aplicación para decidir si usar el producto en mi trabajo|<p>Escenario 01:</p><p>El usuario visita la landing page.</p><p>Caso 01:</p><p>Dado que el usuario necesita una aplicación para aumentar la calidad de sus cultivos </p><p>Cuando el usuario busque en el navegador “Harvest Management”</p><p>Entonces accede a la landing page y visualiza las funcionalidades que le ofrece la aplicación web</p>|EP03|
|HU-14|Landing Page responsive|Como usuario deseo visitar la landing page desde cualquier dispositivo|<p>Escenario 01:</p><p>El usuario visita la landing page desde su celular</p><p>Caso 01:</p><p>Dado que el usuario necesita visitar la landing page desde un dispositivo remoto</p><p>Cuando visite la landing page desde el navegador de su celular</p><p>Entonces la landing page con su diseño responsive puede visualizarse adecuadamente en el navegador del dispositivo móvil</p>|EP03|
|HU-15|Botón Call to Action|Como usuario deseo ir a la aplicación web desde un solo botón |<p>Escenario 01: </p><p>El usuario quiere dirigirse a la aplicación web</p><p>Caso 01: </p><p>Dado que el usuario desea usar la aplicación web</p><p>Cuando esté en la sección donde se encuentre el botón call to action y lo uso</p><p>Entonces será dirigido a la aplicación web</p>|EP03|
|HU-16|Visualización de botones y texto amplia y notoria|Como usuario deseo ver los botones y la información de las secciones o pantalla para una mejor navegación|<p>Escenario 01:</p><p>El usuario quiere navegar por la aplicación sin forzar la vista</p><p>Caso 01:</p><p>Dado que el usuario desea ver los productos visualmente grandes </p><p>Cuando quiera analizar si el producto es de la calidad que espera</p><p>Entonces podrá visualizar el producto mejor y proseguir con la compra</p><p></p>|EP04|
|HU-17|Sistemas de búsqueda y paginación|Como usuario deseo encontrar los productos de manera rápida para no perder tiempo |<p>Escenario 01:</p><p>El usuario quiere encontrar un producto que compró hace unas semanas</p><p>Caso 01:</p><p>Dado que el usuario desea ver una compra que hizo hace semanas</p><p>Cuando quiera buscarlo en la sección de “Mis compras”</p><p>Entonces podrá buscarlo directamente en una barra de búsqueda</p>|EP04|


## 3.3. Impact Mapping.
Se utilizó el Impact Mapping para definir y visualizar los objetivos y resultados deseados en el proyecto para cada uno de los segmentos.
![ImpactMap](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/3ef9ef91-be98-451c-89b6-fae6e3ce98d5)
![ImpactMap](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/659162bf-af13-4dab-8226-02ac018ed162)
## 3.4. Product Backlog.

| #Orden | User Story Id | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
| - | - | - | - | - |
|01|HU01|Registro de cuenta|Como usuario, quiero poder registrarme en la aplicación para acceder a las funcionalidades disponibles.|2|
|02|HU02|Inicio de sesión|Como usuario, quiero iniciar sesión para poder ingresar a mi cuenta|3|
|03|HU03|Explorar productos agrícolas|Como comercializador quiero observar los productos disponibles para poder realizar los pedidos|3|
|04|HU04|Realizar pedidos de productos|Como comercializador, quiero poder realizar los pedidos de productos agrícolas para poder realizar las entregas|8|
|05|HU05|Seguimiento de Pedidos y Entregas|Como comercializador, quiero poder observar el estado de los pedidos y entregas para poder sentirme más tranquilo|8|
|06|HU06|Acceder a Calificaciones y Reseñas|Como comercializador, quiero acceder a las calificaciones y reseñas dejadas por los agricultores para saber sobre la valoración de mis servicios|2|
|07|HU07|Observar registro de pedidos y entregas realizadas|Como comercializador, quiero observar los pedidos y entregas realizadas, para poder tomar decisiones de acuerdo al análisis de los registros|2|
|08|HU08|Planificar actividades agrícolas|Como agricultor, quiero ingresar los datos correspondientes para la planificación de las actividades agrícolas|5|
|09|HU09|Registro de gastos y ganancias|Como agricultor, quiero registrar los gastos y las ganancias relacionadas con las actividades agrícolas para poder llevar un control financiero|3|
|10|HU10|Gestión de Insumos Agrícolas|Como agricultor, quiero llevar un registro de los insumos agrícolas utilizados para analizarlo y tomar decisiones de acuerdo con ello|3|
|11|HU11|Control de Plagas|Como agricultor, quiero tener herramientas para identificar y controlar las plagas para que no puedan afectar mis cultivos|3|
|12|HU-12|Atender pedidos|Como usuario deseo ver los pedidos que tengo de manera rápida y fácil en una pantalla|8|
|13|HU-13|Visualización de características de la aplicación web|Como usuario deseo ver las principales características de la aplicación para decidir si usar el producto en mi trabajo|5|
|14|HU-14|Landing Page responsive|Como usuario deseo visitar la landing page desde cualquier dispositivo|8|
|15|HU-15|Botón Call to Action|Como usuario deseo ir a la aplicación web desde un solo botón|5|
|16|HU-16|Visualización de botones y texto amplia y notoria|Como usuario deseo ver los botones y la información de las secciones o pantalla para una mejor navegación |3|
|17|HU-17|Sistemas de búsqueda y paginación|Como usuario deseo encontrar los productos de manera rápida para no perder tiempo|5|

# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.


Mediante la aplicación Ayni se busca que los usuarios gocen de una interfaz que transmite formalidad, profesionalismo y la serenidad que transmiten los paisajes de campos de cultivo de Perú. Por ello, el equipo tomó la decisión de emplear recursos visuales que capten la atención de los segmentos objetivos y que sean fáciles de identificar. Como estrategia se utilizaron colores pasivos, con temperaturas frías (verde y azul) junto con fuentes tipográficas con diferentes tamaños y espaciados ligeramente amplios, con el propósito de generar placer visual y lograr que el texto sea más visible. Cabe destacar que no se emplearán texturas, pues se busca mantener un aspecto mini

**Brand Overview**

El producto solución Ayni, surge a partir de la necesidad de mejorar la calidad de los productos de cultivo a través de mejorar los procesos y el flujo de ganancias de los productos y de los comerciantes respectivamente. A partir de esto, se propuso desarrollar una aplicación web que facilitará la planificación de cultivos, entre otras funciones con el fin de atender las necesidades previamente mencionadas.

**Brand Name**

El nombre del producto es Ayni. Este nombre nació de la lengua quechua para referirse al trabajo común y a la reciprocidad, que es lo que se desea para los clientes, nosotros les damos una aplicación web eficiente para ayudar a sus rutinas de cultivo y ellos nos dan el reconocimiento por facilitarles la tarea. Por otro lado, el logo de Ayni representa la esperanza y la vida a través de una hoja verde.

![Ayni Logo](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/ceb29e85-3c65-4758-85e6-feae0881ad60)


**Colores**

Colores primarios: El color primario empleado para el diseño del producto y para el logotipo es una escala de colores similares a la celeste aguamarina, el cual es una mezcla entre azul y verde que transmite balance, armonía, seguridad y novedad. Estas características permiten elaborar una interfaz no intrusiva, donde el fondo pasa desapercibido y como consecuencia, indirectamente otorga mayor prioridad al texto.

![Colores primarios](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/4a45a2af-990a-44f4-b4f8-7db5d0fc5133)

Colores secundarios: Como color secundario se seleccionó una escala de verdes, los cuales transmiten sentimientos tales como armonía, serenidad, sensación de crecimiento y están arraigados a conceptos como prestigio y bonanza económica, lo cual encaja a la perfección con el enfoque que buscamos potenciar de los agricultores.

![Colores secundarios](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/4e048e5c-9a84-459d-9965-e4891e8f2e3b)

Colores adicionales: Como colores adicionales se seleccionaron blanco, negro y dos tonalidades diferentes de rojo. Estos serán empleados dentro de la tipografía, botones y mensajes de la aplicación. El blanco también será empleado para algunos fondos que requieran que la visibilidad del texto resalte con mayor ímpetu.

![Adicionales](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/f7790537-54c7-4226-92bc-11323d7cf5b0)

**Tipografia:**

El equipo seleccionó la fuente de letra Archivo, un estilo tradicional y fácil de leer. La separación del interletraje es de 0,15 px, el interlineado es de 0,5 px y el tamaño de la fuente varía dependiendo de la finalidad de uso, por ejemplo, para los títulos se opta por un tamaño de 56 px, y para el texto redactado por el usuario 27 px. 

![Tipografia](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2e9abaf9-db14-4c7f-b000-2a60df98a8c6)

Tono de comunicación y lenguaje aplicado
El tipo de lenguaje a emplear será serio y formal junto con entusiasmo y serenidad. Dado que se agregarán mejoras y pasos que captarán la atención del usuario. Asimismo, se agregaron elementos para perfeccionar la interfaz y diseño final para los clientes.


### 4.1.2. Web Style Guidelines.

La página web está diseñada para mostrarse en el dispositivo que se esté usando, ya sea desde una computadora o dispositivo móvil, el sitio web estará disponible en ambas plataformas para proporcionar una mejor experiencia de usuario. Además, el patrón de diseño web usado es Flat Design, para que el usuario tenga una alta comprensión y una fácil interacción al momento de estar en la interfaz. 

Se utilizará el patrón 


## 4.2. Information Architecture.

En la presente sección, se establecerá la estructura del software según cada segmento objetivo. Del mismo modo, los distintos elementos que se emplearán en la navegación dentro de la aplicación. 

### 4.2.1. Organization Systems.

En el presente punto se indicará los grupos de información en los cuales se aplicarán los tipos de estructuración visual, además, se indicará para qué segmento objetivo está diseñado y que tipo de categorización se utilizará

**Segmento: Productores que desean mejorar su producción**

**Jerárquica:**

Lista de productos: los productores podrán visualizar sus productos que se mostrarán de manera ordenada mediante una lista. Con ello, los exportadores podrán ver los productos que tienen los productores

Lista de planificación de cultivo: Los productores luego de escoger un producto, se le mostrará sus planes de cultivo y asimismo empezar uno nuevo si no hay existentes. 

Historial de calidad de cultivos: Los productores podrán ver y registrar la calidad de los productos luego del proceso de cultivo, asimismo las cantidades serán registradas y posteriormente aparecerán en el historial como reportes o informes con los detalles. Con ello, los exportadores podrán ver los informes de calidad y cantidad de los productores.

Lista de los costos y ganancias: Los productores podrán gestionar sus costos y ganancias, visualizando una lista ordenada de costos separada de ganancias. Esta información puede registrarse si no hay existentes y los datos serán sumados según periodo de tiempo que introduzca el usuario o predeterminadamente en meses. 

**Secuencial:**

Atención de pedidos: En esta sección el productor puede atender los pedidos que realicen los exportadores de manera secuencial. Para ello, se deberá seguir ciertos pasos como la elección de aceptar el pedido o no, negociación de precio, selección de fecha, hora y lugar para la venta y la selección de método de pago.

**Matricial:**

Calendario de cultivo: En esta sección el usuario visualizará las acciones que debe realizar en ciertos días propios de cada plan de cultivo, también se presentará la opción de editar los horarios de los planes establecidos. Esta información se presentará en un calendario donde el usuario podrá visualizar los pasos seleccionando un dia.

**Segmento: Exportadores o comerciantes que desean vender productos de calidad**

**Jerárquica:**

Búsqueda de productos: El comerciante será capaz de buscar productos asimismo revisar el reporte de calidad y cantidad del cultivo donde fue extraído.

Calificación del servicio: El comerciante será capaz de realizar calificación en base a la producción que se pactó en la venta con el productor.

Historial de compras: El comerciante será capaz de revisar sus compras pasadas asimismo la información detallada como precio, detalle de producto, peso, fecha, hora y lugar de la compra.

**Secuencial:**

Pedido de productos: En esta sección, se necesitaran realizar ciertos pasos como selección del producto, revisión de informe de cultivo, añadir propuesta de precio, añadir fecha, hora y lugar para el pedido. Este proceso es obligatorio para la elección de atender un pedido por parte del productor e indispensable para realizar una venta.

Algunas de las funcionalidades ofrecidas van dirigidas a ambos segmentos objetivos, estas son:

**Jerarquica:**

Landing Page: En esta sección se presentará a los visitantes del sitio web estático y toda la información acerca del producto solución. Esta información se mostrará categorizada por secciones y organizada en base a su relevancia. Algunas de las secciones a presentar son: 

**Matricial:**
Menú de opciones: Tanto productores como exportadores contarán con un menú de opciones que le permita acceder a cada una de las funciones de Ayni. Estas se presentaron en una lista sin ningún orden en especifico, solo variara de acuerdo con el segmento al que pertenezca el usuario


### 4.2.2. Labeling Systems.

A continuación, el equipo mostrará el sistema de etiquetado que otorgará una descripción breve y clara de la información brindada por la Landing Page.

**Los encabezados serán los siguientes:**

- Inicio/Home: Sección preseleccionada por defecto que brindara una frase representativa y el logo de la aplicación, además brindara una idea principal del objetivo de esta.

- Sobre nosotros/About Us: Sección donde el cliente obtiene información acerca del equipo de desarrollo, será capaz de visualizar nuestra misión, visión, quienes somos y qué hacemos.

- Services/Funcionalidades: Sección dividida para cada segmento objetivo donde se mostrará las funcionalidades que otorga la aplicación para ellos.

- Contactanos/Contact Us: Sección donde se muestran nuestros canales de comunicación.

A continuación, el equipo mostrará el sistema de etiquetado que otorgará una descripción breve y clara de las funcionalidades brindadas por la aplicación web-

**Los encabezados son los siguientes:**

**Para productores:**

- Inicio/Home: En esta página preseleccionada por defecto que presentará los productos que tiene en cultivo además de mostrar las fechas con actividades provenientes de los planes de cultivo. Finalmente, saldrá publicidad de proveedores de insumos.

- Mis Productos/My Products: Página que muestra los productos existentes que están en proceso de cultivo. Además, si no hay productos existentes estará presente un botón para agregar uno.

- Gestión financiera / Financial Management : Página donde el usuario podrá registrar y ver sus costos y ganancias, tendrá la opción de añadir costos y gastos junto con una descripción, fecha y hora, separadas en filas y columnas.

- Mis Pedidos / My Orders: Página donde el usuario podrá ver y atender los pedidos que realicen los exportadores o comerciantes. 

**Para comerciantes:**

- Inicio/Home: Página preseleccionada por defecto que presentará el número de productos que se compró o publicidad, además de mostrar los pedidos que se acordaron recientemente.

- Search Products / Buscar productos: Página donde el comerciante podrá buscar los productos que desea vender, además se hará el contacto con el productor y acordar el precio. 

- Rate Products / Calificar productos: Página donde el comerciante podrá calificar los productos que compró a los productores. Esta calificación será en base a números.

### 4.2.3. SEO Tags and Meta Tags

En esta sección, se presentarán las etiquetas que identificarán y diferenciarán al sitio web de los demás en internet. Gracias a ellos, se podrá encontrar a Ayni en los diversos buscadores.

Para el sitio web estático:

Tittle: Ayni

Description: Ayni - GreatMinds Oficial Landing Page

Keywords: harvest management, sell crops, harvest suppliers

Authors: GreatMinds team

Para la aplicación web:

Tittle: Ayni

Description: Ayni - GreatMinds Oficial Web Page

Keywords: harvest management, sell crops, harvest suppliers, crop planning, 

Authors: GreatMinds team

### 4.2.4. Searching Systems.

En esta sección se presentarán los sistemas de búsqueda que se implementarán en la aplicación. Al hacer uso de esos sistemas, los usuarios podrán encontrar la información que requieran.

En el sitio web estático, los usuarios podrán utilizar la barra de navegación para buscar la información acerca del producto solución, paralelas funcionalidades se hará uso interactivo de un botón donde se alternará entre “Para productores” y “Para comerciantes”

**En la aplicación web:**

**Segmento: Productores que desean mejorar la calidad de sus productos**

- Mis productos: Esta sección le permitirá al productor realizar el seguimiento de sus cultivos. En esta sección luego el productor podrá realizar un plan de cultivo en la siguiente página luego de seleccionar el producto en “Mis productos”. En esta sección se podrá usar un buscador que contará con la función de filtro para los productos asimismo con la sección de planes de cultivo, donde se podrá realizar búsquedas de planes de cultivo predeterminado o hacer uno personalizado. Posteriormente, los resultados de esta búsqueda mostrarán una lista de lo deseado. 

- Gestión de finanzas: Esta sección le permitirá al usuario realizar registros de sus costos y ganancias. Debido a ello, desde estos registros se pueden almacenar en días del calendario. Por defecto estos costos aparecerán en orden de origen, sin embargo, puede aplicar un filtro para ver entre días de un mes en específico. 

- Mis pedidos: Esta sección le permitirá al usuario atender los pedidos que los comerciantes realicen, es de elección del productor atenderlos o no. Se mostrarán los pedidos en una lista según orden de origen predeterminadamente, pero estarán filtros para visualizar los pedidos según meses o días. 

**Segmento: Exportadores o comerciantes que desean mejorar la calidad de sus ventas**

- Búsqueda de productos: Esta sección es una de las más importantes para el flujo principal de la aplicación debido a ello, contará con un sistema de búsqueda mediante una barra para que los comerciantes busquen el producto en específico. En esta sección también se podrá acordar la venta, introducir un precio, fecha, hora y lugar. Posteriormente, se realiza la venta.


### 4.2.5. Navigation Systems.

A continuación, el equipo mostrará los sistemas de navegación con los que contará Ayni para permitir a los usuarios navegar de manera rápida y segura a cualquier bloque de información.

En el Landing Page, se cuenta con encabezados que representan a las diversas secciones que estarán presentes. Estas estarán ubicadas en la parte superior de la página como menú horizontal siempre presente a la hora de bajar y subir con el ratón. Para que el usuario no tenga que realizar una traslación de manera manual por toda la página para llegar a una sección, se podrá usar estos encabezados para ubicarse inmediatamente en el sector que se desee. Obviamente, el visitante tiene que haber leído el título del encabezado para asegurarse de que se ubicará en la zona adecuada. Gracias a esto, se genera una traslación fácil e intuitiva.

En el caso de la aplicación web, se presenta un proceso similar para el menú principal, se utilizarán diversas opciones que presenta para trasladarse a otra página del sitio web. Estas opciones variarán de acuerdo al segmento objetivo al que pertenezca el usuario. Del mismo modo, se utilizan listados para los grupos de elementos, Dentro de estas listas podrán aplicar filtros que permitan a los usuarios navegar entre esas opciones.


## 4.3. Landing Page UI Design.

En esta sección se mostrará el desarrollo visual del Landing Page. Para ello, se usuará la herramienta de diseño web Figma, debido a sus funciones y plugins que nos permite desarrollar el prototipo sin dificultades. Asimismo se evidenciará el uso de los Style Guidelines e Information architecture.
### 4.3.1. Landing Page Wireframe.

![wireframe landing2](https://user-images.githubusercontent.com/104078975/265294361-ba30a39c-91f2-4854-aae4-14e8560d2aa4.png) 

![wireframe landing1](https://user-images.githubusercontent.com/104078975/265294362-cf7b8b7d-a3c6-4886-a961-17ebea4f9f2f.png) 


Link: [Figma](https://www.figma.com/file/YR4NseDMnYS8ke5dmqMcdY/Desktop-landing-page-wireframes-(Copy)?type=design&node-id=0%3A1&mode=design&t=yZiv29XpOE5ltkCs-1)

### 4.3.2. Landing Page Mock-up.

Trabajando con los wireframes anteriormente mostrados, luego se aplicó los Style Guidelines para el uso de los colores. Como se aprecia, estos tienen un contraste llamativo en cada sección de la landing page. 

![mockup 1](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/ec07c500-0cfb-4f39-82e4-a686fdfb4472)

![mockup2](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/f64ce1f5-0dec-4122-a0b7-861ce29d93e0)

![mockup3](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/d3114afe-d556-4c53-a947-f4bc0926c29a)

Finalmente, aquí es un vistazo general a los mockups y wireframes:

![mockup and landing](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/55842aed-78b9-4f09-a20f-0659f0d435d3)

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

**Pantallas relacionadas a la busqueda de productos:**
![wireframe buscar productos](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/123ce308-a69e-4cc8-9588-3745ed3ae42b)

---
**Pantalla relacionada a la calificación de productos:**
![wireframe calificación](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/2c46b597-fe3e-4e69-aa34-cc8a40b91ad7)

---

**Pantallas relacionadas a costos y ganancias:**
![wireframe costos ganancias](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/30f14e2e-8adc-417c-a406-7fb943026a12)

---

**Pantallas relacionadas a la planfiicación de cultivos:**
![wireframe cultivo](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/26aff367-713e-47af-ac40-941afd604609)

---

**Pantallas relacionas a la gestión de insumos:**
![wireframe insumos](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/ed379d33-7bc0-45dc-8499-875fbf9802a4)

---

**Pantallas relacionadas a la atención de pedidos:**
![WIREFRAME PEDIDOS](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/f0a91929-f0a9-4196-81c4-055d4293b751)

---

**Pantallas relacionadas a la compra de productos:**
![wireframecompra compra](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/f4edf678-ee02-4bac-b573-69511dfbf2c4)

---

**Pantallas relacionadas al inicio de sesión:**
![wireframes login](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/47b3b986-960f-4112-ae75-eeda1826e6cb)

---

**Pantallas relacionadas al seguimiendo de compras:**
![wireframes seguimiento](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/24b5315d-764a-4adb-ac7d-4a5c024de5a2)

---

### 4.4.2. Web Applications Wireflow Diagrams.

En esta sección, se presentan los wireflows de la aplicación guiándose de las historias de usuario

**Usar Goal:** Como usuario, quiero poder registrarme en la aplicación para acceder a las funcionalidades disponibles.

**Task Flow:**
- Primero se observará la pantalla de inicio de sesión, en esta se puede o iniciar o registrarse
- Si accede a registrarse, se mostrará la pantalla de registro. Puede regresar a iniciar sesión o continuar
- Finalmente, se accede a la pantalla de selección de roles si es que se registra, para que acceda a la aplicación.

![Wireflow 1](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/69d3a980-ed25-4bec-8c8c-74fda207a54c)

---

**User Goal:** Como agricultor, quiero ingresar los datos correspondientes para la planificación de las actividades agrícolas. 

**Task Flow:**
- Primero se está en la pantalla de “Mis productos”
- Si presiona el botón de “Añadir nuevo producto”, se mostrará la pantalla para rellenar los datos del cultivo 
- Luego, se mostrará un dashboard para la planificación de cultivo, donde se irá introduciendo pasos para la planificación
- Finalmente, se mostrará el calendario de la planificación donde el usuario podrá introducir eventos

![Wireflow 2](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/2359dd6a-fd0e-430f-bcc1-ed1deeaa0002)

---

**User Goal:** Como agricultor, quiero registrar los gastos y las ganancias relacionadas con las actividades agrícolas para poder llevar un control financiero.

**Task Flow:**
- Primero se está en la pantalla de “Gestión Financiera”
- Se mostrarán los costos en un label y las ganancias en otro label
- Si el usuario le da click al botón “Ver más”, se mostrarán a detalle los costos o ganancias según haya elegido previamente
- Si el usuario le da click a “Registrar” en la sección que escogió, se mostrará la pantalla de registro.

![wireflow3](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/1d79971f-c505-424f-a5f8-40bda7b30f3f)

---

**User Goal:** Como agricultor, quiero llevar un registro de los insumos agrícolas utilizados para analizarlo y tomar decisiones de acuerdo a ello.

**Task Flow:**
- Primero se tiene que seleccionar un producto
- Luego el usuario da click al botón de “Insumos”
- Le aparecerá la pantalla de los insumos usados ya registrados en el producto

![wireflow 4](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/93fc2e8f-2b7c-4173-bc4c-42d1731ee347)

---

**User Goal:** Como usuario deseo ver los pedidos que tengo de manera rápida y fácil en una pantalla 

**Task Flow:**
- Primero el usuario tiene que estar en la sección del header “Mis pedidos”
- Luego, se mostrará la pantalla de pedidos con las listas de los pedidos pendientes
- Al seleccionar un pedido, el productor puede darle al botón de aceptar o rechazar pedido

![WIREFLOW 5](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/59d72b29-dabd-4ac3-80f6-a563e07aa88e)

---

**Sector: Comerciantes**

**User Goal:** Como comercializador quiero observar los productos disponibles para poder realizar los pedidos

**Task Flow:**

- Primero el usuario tiene que estar en la sección “Buscar Productos” 
- Luego se mostrará la pantalla con los productos disponibles y una descripción

![wireflow 6](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/ecc5275a-0845-40dc-943a-c064bb27dede)

---

**Usar Goal:** Como comercializador, quiero poder realizar los pedidos de productos agrícolas para poder realizar las entregas

**Task Flow:**
- Primero el usuario debe estar en la pantalla de buscar productos
- Luego debe seleccionar el producto que desee comprar
- Se debe dar click en comprar y aparecerá la pantalla de dashboard donde debe completar datos para la compra

![wireflow7](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/e12dacfd-6766-498f-976b-62bfb2a7271c)

---

**User Goal:** Como comercializador, quiero poder observar el estado de los pedidos y entregas para poder sentirme más tranquilo

**Task Flow:**

- Primero el usuario debe estar en la pestaña de “Mis compras”
- Seleccionar un producto y luego se le mostrará el estado de su compra e información
- Si hace click en el botón “Ver estado” podrá ver detalladamente el estado actual del producto

![wireflow 9](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/903e2d87-a0fc-4586-813c-bb6bf76109f8)

---

**User Goal:** Como comercializador, quiero acceder a las calificaciones y reseñas dejadas por los agricultores para saber sobre la valoración de mis servicios

**Task Flow:**
- Primero el usuario debe estar en la sección “Calificaciones” 
- En la siguiente pantalla se mostrará información de los productos que compró y una calificación en estrellas

![wireflow8](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/6b8f6c3a-b029-49ae-8815-8bcc50cff9ce)

---

### 4.4.2. Web Applications Mock-ups.

En esta sección, se presenta el diseño viusal y de interacción en formato de mockups del producto solución.

**Pantallas relacionadas a la busqueda de productos:**
![mockup inicio comerciante](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/57020957-243a-4b93-a669-f2a254027288)

---

**Pantalla relacionada a la calificación de productos:**
![mockup clasificacion](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/ee35a030-148b-4951-855d-7272ab087b8d)

---

**Pantallas relacionadas a costos y ganancias:**
![mockups gastos](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/b1463919-d119-4202-b408-21d03562b09e)

---

**Pantallas relacionadas a la planfiicación de cultivos:**
![registro de cultivo mockup](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/9c893aa4-2ad9-4b0d-93aa-18f4c04fc23a)

---

**Pantallas relacionas a la gestión de insumos:**
![mockup insumos y detalle de producto](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/275a6282-c9df-451a-ba40-29be05ea4545)

---

**Pantallas relacionadas a la atención de pedidos:**
![mockup atencios de pedidos](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/f19367a9-de9f-447a-9fce-55cd1fac4b12)

---

**Pantallas relacionadas a la compra de productos:**
![mockup compra](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/69981228-e074-42d6-b01a-23a639dbdda7)

---


**Pantallas relacionadas al inicio de sesión:**
![mockup login](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/9388e04d-56f4-4b21-b783-1c31a503c228)

---

**Pantallas relacionadas al seguimiendo de compras:**
![seguimiento](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/a5d9ff96-50b1-497f-8115-27e517c78031)

---

### 4.4.3. Web Applications User Flow Diagrams.

**User Goal:** Como agricultor, quiero llevar un registro de los insumos agrícolas utilizados para analizarlo y tomar decisiones de acuerdo a ello.

**Task Flow:**
- Primero se tiene que seleccionar un producto
- Luego el usuario da click al botón de “Insumos”
- Le aparecerá la pantalla de los insumos usados ya registrados en el producto
![user flow mis productos e insumos](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/2440130a-15a4-4bc8-9fa7-9ad51cfd5cba)

---

**User Goal:** Como comercializador, quiero poder observar el estado de los pedidos y entregas para poder sentirme más tranquilo

**Task Flow:**

- Primero el usuario debe estar en la pestaña de “Mis compras”
- Seleccionar un producto y luego se le mostrará el estado de su compra e información
- Si hace click en el botón “Ver estado” podrá ver detalladamente el estado actual del producto

![user flow seguimiento](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/86d99c6e-7108-49d1-9bee-8e1b27320c12)

---

**Usar Goal:** Como comercializador, quiero poder realizar los pedidos de productos agrícolas para poder realizar las entregas

**Task Flow:**
- Primero el usuario debe estar en la pantalla de buscar productos
- Luego debe seleccionar el producto que desee comprar
- Se debe dar click en comprar y aparecerá la pantalla de dashboard donde debe completar datos para la compra
  
![USERFLOW COMPRA](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/37aebbb8-db27-4be4-889a-320952d738dd)

---

**User Goal:** Como agricultor, quiero registrar los gastos y las ganancias relacionadas con las actividades agrícolas para poder llevar un control financiero.

**Task Flow:**
- Primero se está en la pantalla de “Gestión Financiera”
- Se mostrarán los costos en un label y las ganancias en otro label
- Si el usuario le da click al botón “Ver más”, se mostrarán a detalle los costos o ganancias según haya elegido previamente
- Si el usuario le da click a “Registrar” en la sección que escogió, se mostrará la pantalla de registro.

![userflow costos](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/26417dae-0fe5-415a-99eb-538ce4215e48)

---

**Usar Goal:** Como usuario, quiero poder registrarme en la aplicación para acceder a las funcionalidades disponibles.

**Task Flow:**
- Primero se observará la pantalla de inicio de sesión, en esta se puede o iniciar o registrarse
- Si accede a registrarse, se mostrará la pantalla de registro. Puede regresar a iniciar sesión o continuar
- Finalmente, se accede a la pantalla de selección de roles si es que se registra, para que acceda a la aplicación.
  
![userflow login](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/f07df25b-1a9a-475d-a610-24a3aec2e290)

---

**User Goal:** Como usuario deseo ver los pedidos que tengo de manera rápida y fácil en una pantalla 

**Task Flow:**
- Primero el usuario tiene que estar en la sección del header “Mis pedidos”
- Luego, se mostrará la pantalla de pedidos con las listas de los pedidos pendientes
- Al seleccionar un pedido, el productor puede darle al botón de aceptar o rechazar pedido

![userflow pedidos](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/26e1f55c-aa33-4d03-a2d4-d3f4c048bf0c)

---

**User Goal:** Como agricultor, quiero ingresar los datos correspondientes para la planificación de las actividades agrícolas. 

**Task Flow:**
- Primero se está en la pantalla de “Mis productos”
- Si presiona el botón de “Añadir nuevo producto”, se mostrará la pantalla para rellenar los datos del cultivo 
- Luego, se mostrará un dashboard para la planificación de cultivo, donde se irá introduciendo pasos para la planificación
- Finalmente, se mostrará el calendario de la planificación donde el usuario podrá introducir eventos
  
![userflow planifiación con agregado](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/274e9055-5147-4fed-8316-005be3413716)

---


**User Goal:** Como comercializador, quiero acceder a las calificaciones y reseñas dejadas por los agricultores para saber sobre la valoración de mis servicios

**Task Flow:**
- Primero el usuario debe estar en la sección “Calificaciones” 
- En la siguiente pantalla se mostrará información de los productos que compró y una calificación en estrellas

![user flow clasificación](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/ea2b5759-35d2-4e39-9cb7-f53ede138d12)

---

### 4.5. Web Applications Prototyping.

En esta sección, se puede acceder al prototipo en la herramienta Figma. Asismismo se pueden evidenciar los principios de arquitectura de información, esto hace que la aplicación se vea lo más eficiente posible.

**Principio de elección:**
Procuramos que la aplicación web posea una cantidad de secciones a todo momento, por lo que se cuenta con la barra superior siempre en la aplicación con 4 secciones, los cuales podrá acceder a las funcionalidades rapidamente desde cualquier pantalla.

**Principio de divulgación:**
La información presentada se separa por partes, de tal manera que el usuario encuentre lo que desee. Esto se evidencia en los detalles al seleccionar un cultivo.

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/d1677ee0-a6ce-494b-b406-d804be366f70)
Link de video: [Video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EX4ZpWMosmZPs7NUF4TaAA8BsIw_pJptxIo8rk014lsGKg?e=1m2JAk)

Link del prototipo: [Figma](https://www.figma.com/proto/tniolYyFGnxJ4QF4BLTZt8/Angular-Material-(Material-3-Design-Component-Figma-Library-For-Angular)-(Community)?type=design&node-id=563-11136&t=zMDrjfTjeys89byq-0&scaling=min-zoom&page-id=6%3A2) 
![prototype](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/970fa7d2-d4cd-4890-881a-b485773e922f)

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.

![structurizr-85725-Contexto](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/1a0fcaff-d404-4492-b1e3-d162f79bfbcb)


### 4.6.2. Software Architecture Container Diagrams.

![structurizr-85725-Contenedores](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/8a05b6fd-3add-490a-b2af-f42cefc88285)

### 4.6.3. Software Architecture Components Diagrams.

![structurizr-85725-Componente](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3f1545c7-7a40-42dc-9923-592d5562595e)

## 4.7. Software Object-Oriented Design.

En esta sección, se utilizará el enfoque de diseño orientado a objetos para desarrollar la aplicación web. Asimismo, se aplicarán los principios y conceptos fundamentales de la programación orientada a objetos.

### 4.7.1. Class Diagrams.

En esta sección, se presentarán los diagramas de clases, en las cuales se representan las clases y sus relaciones en el diseño orientado a objetos.

![Diagrama de clase](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/421d4185-8842-4a52-a824-c5e57c1ed9ee)

Link del diagrama de clases: [Lucidchart](https://lucid.app/lucidchart/da673808-9900-4ced-8184-01abaa761b59/edit?view_items=CDxqUGDDEZN7&invitationId=inv_b067fe97-c812-4a2d-93cc-f2436025b5db)

### 4.7.2. Class Dictionary.

Aquí se creará un diccionario detallado que describe cada una de las clases identificadas en los diagramas. 

**Order:** Esta clase representa los pedidos realizados por los compradores en la plataforma. Incluye información como la fecha de orden.

**Product:** Esta clase representa el producto que el agricultor/productor ofrece en la plataforma. Aquellos productos pueden ser tomates, maiz, paltos, etc. 

**Review:** Esta clase representa los comentarios y calificaciones que el comercializador o compradores dejan sobre los productos adquiridos y la experiencia de compra.

**Crop:** Esta clase representa el cultivo del productor y maneja la información como el tipo de planta en ese cultivo, la fecha de siembra y la fecha de cosecha prevista.

**Plants:** Esta clase representa a las plantas que son cultivadas en la parcela. Es útil para saber información útil sobre como cultivar una planta.

**Activities:** Esta clase representa las actividades agrícolas que los productores realizan en sus cultivos. 

**Reminder:** Esta clase representa los recordatorios que los agricultores/productores pueden configurar para recibir alertas sobre alguna actividad importante en su cultivo, como el abono, riego, entre otros.

## 4.8. Database Design.

En esta sección, se definirán las tablas y relaciones necesarias para almacenar y gestionar los datos de manera eficiente.

### 4.8.1. Database Diagram.

En esta sección, se presentará el diagrama de la base de datos, que muestra la estructura y las relaciones entre las tablas. 

![Database](https://github.com/upc-pre-202302-GreatMinds-SW51/SW51-GreatMinds-OpenSource/assets/104078975/ed2afd37-93ad-4fc7-b96d-8026b8e66c3e)

Link para visualizar el diagrama de base de datos: [Vertabelo](https://my.vertabelo.com/doc/lh2wueyLIyZXQviphxQgyZACCtfJVtKs)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

Utilizaremos principalmente como IDEs: Visual Studio Code o  WebStorm, cada una con su configuración debida para no causar conflictos con carpetas personalizadas de cada IDE. Más adelante se hará uso de IntelliJ IDEA para la implementación de las APIs.

Como herramientas de desarrollo se hará uso de la última versión disponible de Node.js. Para el frontend, se usará el framework web Angular versión 13. El cual se instalará mediante nvm en su versión de Windows. Como framework de diseño se usará Angular Material UI. Finalmente, para el backend, se utilizará el lenguaje de programación de Java.

Como herramientas SaSS, se usará GitHub como herramienta para colaboración de código. También usaremos Trello para la elaboración de los Product Backlog. Vertabelo, para la elaboración del diagrama de base de datos. Codegram, para la elaboración del diagrama de clases y LucidChart, para diagramas adicionales

Para el desarrollo del landing page, se decidió con el equipo usar HTML, JS y CSS. Para llevarlo a cabo se eligieron diversas herramientas tecnológicas de las cuales el equipo ya está acostumbrado y tienen un cierto dominio. Estas herramientos son las siguientes:

- Visual Studio Code: Es un editor de código gratuito, moderno y potente gracias a que cuenta con varias funciones y extensiones para trabajar con cualquier lenguaje de programación. Además es bastante conocida por todos los integrantes del equipo y debido a ello se decidió trabajar con Visual Studio Code. Para la instalación del programa, se puede  conseguir desde su página web oficial: una vez descargado se puede proceder con la instalación de forma rápida y fácil.

- Git y Github: Se usaron estas herramientas por la razón de que hoy en día es un estándar usar Git para el control de versiones de software y se eligió GitHub por ser la plataforma más popular y fácil de usar para crear y manejar repositorios, tener funciones para ver cambios, commits, pull request, entre otros. El enlace de descarga del instalador de GitHub Desktop es 

- Live Server: Finalmente, para acelerar el desarrollo del landing page, se usó esta extensión que sirve para visualizar los cambios inmediatamente después de alguna modificación en el código así se evita estar recargando la página, lo cual es un ahorro de tiempo y comodidad al desarrollar.


### 5.1.2. Source Code Management.

Como mencionamos anteriormente, se utilizará GitHub para llevar un control de las versiones de desarrollo y poder trabajar de forma colaborativa. Para ello, se creó una organización llamada: [Github Organización](https://github.com/upc-pre-202302-GreatMinds-SW51) 

Repositorio del landing page: [Repositorio Landing Page]() 

Repositorio pruebas de aceptación: [Github](https://github.com/upc-pre-202302-GreatMinds-SW51/acceptance-test-opensource) 


### 5.1.3. Source Code Style Guide & Conventions.

Referente a las convenciones o estilos de programación, se seguirá la guía de estilos de Google para programar en HTML (Google HTML) y CSS (CSS Style Guide). En el caso de la implementación del frontend, se utilizará Options API para el Framework Vue.
Respecto a las convenciones para el control de versiones en GitHub, se usará conventional commits tanto para las ramas como para los commits usando “<type>/<title>”. En cuanto a la creación de ramas, se usará features branches siguiendo el modelo de GitFlow con la misma nomenclatura descrita anteriormente. La rama principal será la rama main, que contendrá la versión de la aplicación desplegada. Además, todos los hotfixes se realizan en ella, para así poder tener los arreglos desplegados de forma automática.

### 5.1.4. Software Deployment Configuration.

Para el despliegue del Landing Page se utilizará Netlify, para el despliegue automático y gracias a su integración con GitHub se irá actualizando con cada commit realizado y para el Frontend de la aplicación se usará Netlify. Finalmente, para el despliegue del RESTful API, se usará Azure Web App Service.

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.

| Sprint # | 1 | 
| - | - | 
| **Sprint Planning Background** | - |
| Date | 2023 - 09 - 05 |
| Time | 19:00 PM |
| Location | Virtual via Google Meet |
| Prepared By | Gonzales Carrión, Jorge Enrique |
| Attendees (to planning meeting) | Gonzales Carrión, Jorge Enrique / Espejo Macuri, Paolo Andre / Paucar De La Cruz, Tatiana Medalith / Huaman Cataño, Miguel Ángel / Zarate Castro, Jose Daniel |
| Sprint 1 - Review Summary | No aplica (Es el primer Sprint) |
| Sprint 1 - Retrospective Summary  | No aplica (Es el primer Sprint) |
| **Sprint Goal & User Stories** | - |
| Sprint 1 Goal| El objetivo del presente Sprint es en desarrollar la Landing Page usando los wireframes y mockups diseñados previamente |
| Sprint 1 - Velocity | El equipo puede aceptar 20 Story Points|
| Sprint 1 - Story Points | La suma de los Story Points de los User Sotires que se atenderá es 18|

#### 5.2.1.2. Sprint Backlog 1.

Implementación del Landing Page acorde con las User Stories.

![sprint backlog arreglado](https://user-images.githubusercontent.com/104078975/265294372-30a30987-c90f-4579-8685-987a5ebc27e5.png)


#### 5.2.1.3. Development Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| Ayni_LandingPageOfficial | develop | d172a5f | feature: Creación de Landing  | - | 03/09/2023 |
| Ayni_LandingPageOfficial  | develop |  | feature: Benefits Section  | - | 06/09/2023 |
| Ayni_LandingPageOfficial  | develop | 8d3c4bf | feature/FunctionalitiesSection  | - | 05/09/2023 |
| Ayni_LandingPageOfficial  | develop | 47539a0 | Feature/aboutUsSection  | - | 05/09/2023 |
| Ayni_LandingPageOfficial  | develop | d8597c1 | feature/footer-responsive-callToActionSection  | - | 05/09/2023 |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Esta sección no fue posible integrar en la presente entrega debido a que el código realizado fue para el desarrollo de la landing page.

#### 5.2.1.5. Execution Evidence for Sprint Review.

En este apartado se hace presenta la implementación/despliegue de la landing page del producto solución Ayni.

![Sprint Evidence Landing (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/4da61194-1ee7-4012-a786-5dc804e68d2c)

Link del video: [Video Evidencia](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EboHBmisglROmEJioyVBF5YBZ_Pr7cydTYr8pFi8njPn8A?e=SJBY3T) 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

No se utilizó ningún servicio adicional, pues este primer Sprint solo consta de la implementación del landing page.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Como se mencionó, se utilizó Netlify para el despliegue automático del landing page con todos los cambios realizados por el equipo. Netlify se integra con nuestra organización en GitHub y luego con el repositorio, siendo la rama main la que utilizamos para el despliegue. El enlace es el siguiente: 
[Ayni Landin Page](https://aynilandingpage.netlify.app/)

#### 5.2.1.8. Team Collaboration Insights during Sprint.
