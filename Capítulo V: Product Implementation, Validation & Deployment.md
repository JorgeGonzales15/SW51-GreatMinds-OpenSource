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

- Discord: Aunque originalmente se diseñó como una plataforma de comunicación para gamers, Discord también se utiliza para diseñar y crear comunidades en línea y mejorar la experiencia de usuario a través de la comunicación y colaboración en grupos.

- WhatsApp: WhatsApp es una aplicación de mensajería instantánea que se utiliza para la comunicación en tiempo real. Aunque no es una herramienta de gestión de proyectos, se puede usar para mantenerse en contacto con miembros del equipo y colaborar en cierta medida.

- Zoom: Zoom es una plataforma de comunicación que ofrece videoconferencias y reuniones en línea. Aunque se utiliza principalmente para comunicarse y realizar reuniones virtuales, también puede ser útil para la gestión de proyectos remotos y la colaboración en tiempo real.

**Requirements Management:**

- Miro: Miro es una plataforma de pizarra en línea que se utiliza para colaborar en la ideación, planificación y diseño de proyectos. Es especialmente útil para la colaboración visual, como la creación de mapas mentales, diagramas y prototipos.

- Google Docs: Google Docs es una suite de aplicaciones de procesamiento de texto, hojas de cálculo y presentaciones en línea. Aunque no es específicamente una herramienta de gestión de requisitos, se puede utilizar para documentar y colaborar en la definición y seguimiento de requisitos de proyectos.

**Product UX/UI Design:**

- Figma: Figma es una herramienta de diseño de interfaz de usuario (UI) y experiencia de usuario (UX) basada en la nube. Se utiliza para crear prototipos interactivos, diseños de aplicaciones y colaboración en tiempo real en proyectos de diseño.

- UXPressia: UXPressia es una herramienta especializada en la creación de mapas de experiencia de usuario, perfiles de clientes y otros elementos relacionados con el diseño de UX. Ayuda a visualizar y comprender la experiencia del usuario en un producto o servicio.
  
- LucidChart: es una herramienta para crear diagramas de clases, flujo y entre otros, de manera facil e intuitiva. Nos va a servir para hacer los user flows y el diagrama de clases para el proyecto.

**Software Development:**

Visual Studio Code: Visual Studio Code es un editor de código fuente altamente configurable y ampliable. Se utiliza principalmente para la codificación, depuración y desarrollo de software en varios lenguajes de programación.

Git: Git es un sistema de control de versiones distribuido. Aunque no es un programa en sí mismo, es una tecnología esencial para el desarrollo de software y se usa para rastrear cambios en el código fuente y facilitar la colaboración entre programadores.

**Software Documentation:**

GitHub: GitHub es una plataforma de desarrollo colaborativo que utiliza el sistema de control de versiones Git. Se utiliza para alojar, revisar y colaborar en proyectos de desarrollo de software, lo que facilita la colaboración entre desarrolladores.


**Software Testing:**

Lenguaje Gherkin: El lenguaje Gherkin es un lenguaje de dominio específico utilizado para escribir pruebas de aceptación en un formato legible por humanos. Se utiliza junto con herramientas de prueba de comportamiento, como Cucumber, para automatizar pruebas funcionales.

### 5.1.2. Source Code Management.

Como mencionamos anteriormente, se utilizará GitHub para llevar un control de las versiones de desarrollo y poder trabajar de forma colaborativa. Para ello, se creó una organización llamada: (https://github.com/upc-pre-202302-GreatMinds-SW51) 

Repositorio del landing page: (https://github.com/upc-pre-202302-GreatMinds-SW51/Ayni_LandingPageOfficial/tree/Release/1.0) 

Repositorio pruebas de aceptación: (https://github.com/upc-pre-202302-GreatMinds-SW51/acceptance-test-opensource) 

Repositorio Frontend: (https://github.com/upc-pre-202302-GreatMinds-SW51/AyniFrontend) 

Repositorio de uso para usar el servicio de JSONPlaceholder: (https://github.com/JorgeGonzales15/AyniDBPrueba) 

Repositorio de Backend: (https://github.com/upc-pre-202302-GreatMinds-SW51/AyniBackend)

### 5.1.3. Source Code Style Guide & Conventions.

A continuación, se darán a conocer las convenciones, formatos, estilos y entre otras propiedades de los lenguajes trabajados en la presente solución las cuales son: HTML, JavaScript/TypeScript, CSS:

- HTML: Se hará uso de la guía “HTML Style Guide and Coding” de la página W3Schools, la cual menciona las convenciones y estándares de este lenguaje de etiquetas. Hemos considerado las siguientes como las más importantes:

- Declarar siempre el tipo documento: Es decir, colocar siempre la etiqueta en la primera línea del código.

- Utilizar el nombre de las etiquetas y sus atributos en minúscula: Por un tema de estética y orden del código para que este se vea más limpio y sea más fácil de escribir.

- Cerrar todas las etiquetas: Esto evita futuros problemas o errores de sintaxis.

- Siempre coloca comillas para los valores de los atributos de las etiquetas: De esta forma los valores son más fáciles de leer y se deben utilizar obligatoriamente si este contiene espacios.

- Especificar siempre los atributos alt, width y height para las imágenes: Es importante en caso de que la imagen no se pueda mostrar por algún motivo y también ayuda con el tema de la accesibilidad de los usuarios.

- No omitir la etiqueta ni los metadatos: Estas etiquetas son importantes para la optimización de motores de búsqueda (SEO).

CSS: Se siguió la guía “Google HTML/CSS Style Guide” donde se indican las convenciones, reglas y buenas prácticas para este lenguaje. Hemos considerado las siguientes recomendaciones como las más destacadas:

- Nombre de clases: Se recomienda usar nombres generales para las clases, no deben ser específicas por la razón de que deben comportarse como padres.

- Usar nombres de clase cortos: Se recomienda utilizar nombres de clase que sean cortos y descriptivos, para transmitir la idea de lo que representa de manera concisa.

- Usar delimitadores de nombres de clase adecuados: Se debe de separar las palabras en los nombres de clase con solo guiones.

- Evitar los selectores de ID: No se recomienda implementar este tipo de selectores, por la razón de que estos deben ser únicos en toda la página y en proyectos grandes que tengan muchos componentes es difícil de garantizar esa unicidad, es preferible usar selectores de clase.

- Usar propiedades abreviadas: Es muy recomendable usar propiedades que soporten ser declarados de forma abreviada (por ejemplo, la propiedad padding, margin, border, etc.) por la razón de que reduce de forma significativa la cantidad de líneas de código, y es más legible para el programador o diseñador.

- JavaScript: Se consideró importante seguir una guía de buenas prácticas para un mejor desarrollo del código, para este caso se eligió la guía de la wiki “JavaScript best practices“ del World Wide Web (W3C). Lo cual se destaca lo siguiente:

- Usar nombres cortos y fáciles de leer: Es recomendable nombrar adecuadamente las variables, clases, funciones y otros elementos para que sea más sencillo de leer y comprender.

- Evitar el uso de variables globales (keyword “var”): No se recomienda el uso de este tipo de variables en un proyecto, porque pueden generar muchos errores a medida que el proyecto crece y estas pueden sobrescribirse fácilmente afectando el valor y se pueden declarar otros elementos como funciones con el mismo nombre de la variable y generar errores.

- Comentar y documentar lo necesario: Se recomienda comentar líneas de código que son complejos de entender a simple vista explicando o dejando mensajes para que otros programadores lo entiendan.

- Usar notaciones sencillas de entender: Javascript cuenta con diversas notaciones y operadores para crear o modificar ciertas estructuras de datos como objetos, arrays, selectivas, etc.

Gherkin: Se consideró conveniente usar la guía y convenciones que se mencionan en “Gherkin Conventions for Readable Specifications” para una correcta realización de las pruebas. A continuación, se mencionan los puntos que consideramos más importantes para nuestro trabajo:

- Los bloques “Give-When-Then” deben ser diferenciados: Se recomienda usar una correcta indentación de esos bloques para identificar mejor las secciones de la prueba y también añadiendo la keyword “And” para añadir otra línea en los pasos y otro bloque.

- Usar tablas para los pasos: Si uno de los pasos requiere de más información es recomendable usar tablas para organizar dicha información y tenga un aspecto más ordenado.

- Usar comillas simples para los parámetros: Se recomienda esta práctica para una mejor legibilidad de los parámetros en un paso y tener una sintaxis más simple.

- Separar los escenarios con comentarios: Si se da el caso de tener muchos escenarios en una prueba, es usar los comentarios como separadores para que visualmente sea más organizado, fácil de leer y distinguir mejor.

En resumen, las convenciones o estilos de programación, se seguirá la guía de estilos de Google para programar en HTML (Google HTML), CSS (CSS Style Guide) y JavaScript (JS) en el caso de la landing page. En el caso de la implementación del frontend, se utilizará Angular Framework utilizando HTML5, CSS3 y JavaScript para aspectos estáticos de templates y TypeScript como lenguaje de programación.

Para el almacenamiento y control de versiones de código se utilizará GIT gestionado desde 
GitHub aplicando GitFlow Workflow, Conventional Commits y Semantic Versioning. Además, todos los hotfixes se realizan en ella, para así poder tener los arreglos desplegados de forma automática. 

![commitslandingopennet](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/04c9b1bb-5cb3-46b5-9cd0-435367c79865) 

El lenguaje de diseño de Landing Page y Web Applications estará basado en Material Design. Como biblioteca de componentes de UI se utilizará Angular Material.

Para el desarrollo de Web Services, se realizará bajo RESTful API architectural style y se hará uso de Spring Boot Framework, utilizando Java como lenguaje de Programación. 


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
| Ayni_LandingPageOfficial  | develop | ce9ff1b | feature/Benefits-section  | - | 06/09/2023 |
| Ayni_LandingPageOfficial  | develop | 8d3c4bf | feature/FunctionalitiesSection  | - | 05/09/2023 |
| Ayni_LandingPageOfficial  | develop | 47539a0 | Feature/aboutUsSection  | - | 05/09/2023 |
| Ayni_LandingPageOfficial  | develop | d8597c1 | feature/footer-responsive-callToActionSection  | - | 05/09/2023 |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Esta sección no fue posible integrar en la presente entrega debido a que el código realizado fue para el desarrollo de la landing page.

#### 5.2.1.5. Execution Evidence for Sprint Review.

En este apartado se hace presenta la implementación/despliegue de la landing page del producto solución Ayni.

![Sprint Evidence Landing (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/4da61194-1ee7-4012-a786-5dc804e68d2c)

Link del video: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EboHBmisglROmEJioyVBF5YBZ_Pr7cydTYr8pFi8njPn8A?e=SJBY3T) 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

No se utilizó ningún servicio adicional, pues este primer Sprint solo consta de la implementación del landing page.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Como se mencionó, se utilizó Netlify para el despliegue automático del landing page con todos los cambios realizados por el equipo. Netlify se integra con nuestra organización en GitHub y luego con el repositorio, siendo la rama main la que utilizamos para el despliegue. El enlace es el siguiente: 
(https://aynilandingpage.netlify.app/)

#### 5.2.1.8. Team Collaboration Insights during Sprint.

Las actividades para el presente Sprint se repartieron en base a las secciones de la landing page que se plantearon como equipo previamente, para ello, se realizaron primero los styles en un archivo aparte .css y luego entre todo el equipo se desarrolló el index.html. De esta manera, el desarrollo de la landing page fue organizada y eficiente. A continuación, se mostrarán las evidencias de los commits:

![commitsopenlanding](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/29bb038a-a3f8-4af5-836c-5daacc57995b)

![commitslandingopennet](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/04c9b1bb-5cb3-46b5-9cd0-435367c79865)

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2.

| Sprint # | 2 | 
| - | - | 
| **Sprint Planning Background** | - |
| Date | 2023 - 09 - 19 |
| Time | 19:00 PM |
| Location | Virtual via Google Meet |
| Prepared By | Gonzales Carrión, Jorge Enrique |
| Attendees (to planning meeting) | Gonzales Carrión, Jorge Enrique / Espejo Macuri, Paolo Andre / Paucar De La Cruz, Tatiana Medalith / Huaman Cataño, Miguel Ángel / Zarate Castro, Jose Daniel |
| Sprint 1 - Review Summary | Se realizó la landing page implementado con css y html, a raiz de los mockups de diseño|
| Sprint 1 - Retrospective Summary  | Mejorar en puntos de la documentación del informe |
| **Sprint Goal & User Stories** | - |
| Sprint 2 Goal| El objetivo del presente Sprint es en desarrollar el fronted de la aplicación web y corregir los errores del sprint anterior|
| Sprint 2 - Velocity | El equipo puede aceptar 28 Story Points|
| Sprint 2 - Story Points | La suma de los Story Points de los User Sotires que se atenderá es (26)|

#### 5.2.2.2. Sprint Backlog 2.


<table><tr><th valign="top">Sprint 2</th><th colspan="7" valign="top">Sprint: Implementar el frontend de las principales historias de usuario del product backlog </th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Description</td><td valign="top">Estimation (Hours)</td><td valign="top">Assigned To</td><td valign="top"><p>Status </p><p>(To-do / </p><p>InProcess / </p><p>To Review / </p><p>Done)</p></td></tr>
<tr><td rowspan="3" valign="top">HU-07</td><td rowspan="3" valign="top">Planificar actividades agrícolas</td><td valign="top">08\.1</td><td valign="top">Implementar fake-api</td><td valign="top">Implementar fake api para posts o gets de entidades</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.2</td><td valign="top">Implementar estilos </td><td valign="top">Diseñar la página con los Styles Guidelines definidos</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.3</td><td valign="top">Implementar stepper </td><td valign="top">El stepper consta de 3 pasos y cada uno es de un componente</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">HU-04</td><td rowspan="3" valign="top">Realizar pedidos de productos</td><td valign="top">08\.1</td><td valign="top">Implementar fake-api</td><td valign="top">Implementar fake api para posts o gets de entidades</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.2</td><td valign="top">Implementar estilos </td><td valign="top">Diseñar la página con los Styles Guidelines definidos</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.3</td><td valign="top">Implementar stepper </td><td valign="top">El stepper consta de 3 pasos y cada uno es de un componente</td><td valign="top">5</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">HU-03</td><td rowspan="3" valign="top">Explorar productos agrícolas</td><td valign="top">03\.1</td><td valign="top">Implementar estilos</td><td valign="top">Diseñar los estilos para las páginas</td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">03\.2</td><td valign="top">Implementar formularios</td><td valign="top">Implementar formularios para añadir cultivos</td><td valign="top">5</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">03\.3</td><td valign="top">Implementar página de productos</td><td valign="top">Implementar cars para explorar los productos agrícolas</td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">HU-08</td><td rowspan="3" valign="top">Registro de gastos y ganancias</td><td valign="top">09\.1</td><td valign="top">Implementar estilos </td><td valign="top">Diseñar los estilos para las páginas</td><td valign="top">4</td><td valign="top">Jorge Gonzales Carrión</td><td valign="top">Done</td></tr>
<tr><td valign="top">09\.2</td><td valign="top">Implementar las listas de costos y ganancias</td><td valign="top">Implementar con las listbox con el framework requerido</td><td valign="top">5</td><td valign="top">Jorge Gonzales Carrión</td><td valign="top">Done</td></tr>
<tr><td valign="top">09\.3</td><td valign="top">Cards con información de costos y gastos</td><td valign="top">Implementar cards con la información de costos y gatos</td><td valign="top">5</td><td valign="top">Jorge Gonzales Carrión</td><td valign="top">Done</td></tr>
<tr><td valign="top">HU-18</td><td valign="top">Sección principal (“Home”)</td><td valign="top">21\.1</td><td valign="top">Paginas de “Home”</td><td valign="top">Implementar páginas de “Home”</td><td valign="top">4</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
<tr><td valign="top">HU-01</td><td valign="top">Selección de roles</td><td valign="top">01\.1</td><td valign="top">Pantallas de selección de roles</td><td valign="top">Implementar la selección de roles mediante componentes</td><td valign="top">4</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
<tr><td valign="top">HU-02</td><td valign="top">Inicio de sesión</td><td valign="top">02\.2</td><td valign="top">Pantallas de inicio de sesión</td><td valign="top">Implementar inicio de sesión mediante componentes</td><td valign="top">4</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
</table>

#### 5.2.2.3. Development Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| AyniFrontend | costs-and-bills | f72191e| chore: added needed dependencies. | - | 17/09/2023  |
| AyniFrontend | costs-and-bills | 33821e3 | feat: added cost and bills list and buttons | - | 22/09/2023 |
| AyniFrontend  | costs-and-bills | 05a1af9 | feat: added cost and bills list and buttons  | - | 22/09/2023 |
| AyniFrontend  | costs-and-bills | 50d9468 | feat: added dialog form and tables | - | 22/09/2023 |
|  AyniFrontend | costs-and-bills | 3a0a888  | feat: added cost section and forms | - | 22/09/2023 |
|  AyniFrontend | costs-and-bills | bc8bcd1 | feat: added gain section and forms | - | 23/09/2023 |
|  AyniFrontend | authentication-and-home | 2063194 | feat: added signin, signup, select-rol, homeFarmer, homeMerchant | - | 23/09/2023 |
|  AyniFrontend | sales-and-crops | c4ae259 | chore: fixed | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | 795bf7a | feat: Added db.json and routes.json | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | e36a1d3 | feat: Added base service | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | 46cf7dd | feat: Added sales service and model | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | fe26b1d | feat: Added sales step 1 component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | 095a3e9 | feat: Added sales step 2 component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | a8970e6 | feat: Added sales step 3 component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | fed6477 | feat: Added sales dialog component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | c2594d7 | feat: Added sales stepper component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | db081c5 | feat: Added crops service and model | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | e4eb751 | feat: Added crops step 1 component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | bd5a01a | feat: Added crops step 2 component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | d542212 | feat: Added crops step 3 component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | fd2f671 | feat: Added crops dialog component | - | 24/09/2023 |
|  AyniFrontend | sales-and-crops | 252bca9 | feat: Added crops stepper component | - | 24/09/2023 |
|  AyniFrontend | explore-and-add-products | 75ac20c | chored: added more products for db.json | - | 25/09/2023 |
|  AyniFrontend | explore-and-add-products | 50f48d2 | feat(shopping): added product model and services | - | 25/09/2023 |
|  AyniFrontend | explore-and-add-products | 9e76d00 | feat(shopping): added products page and product details page | - | 25/09/2023 |

#### 5.2.2.4. Testing Suite Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| acceptance-test-opensource | main | ff04b60 | Acceptance_test_09.feature | - | 24/09/2023 |
| acceptance-test-opensource | main | 1b8f502 | Acceptance_test_07.feature | - | 24/09/2023 |
| acceptance-test-opensource  | main | da19cab  | Acceptance_test_05.feature  | - | 24/09/2023 |
| acceptance-test-opensource  | main | ee834b6 | Acceptance_test_06.feature | - | 24/09/2023 |
| acceptance-test-opensource  | main | ec958e2 | Acceptance_test_08.feature | - | 24/09/2023 |
| acceptance-test-opensource  | main | 011f428 | Acceptance_test_10.feature | - | 24/09/2023 |
| acceptance-test-opensource  | main | d1d5a6a | Acceptance_test_11.feature | - | 24/09/2023 |

#### 5.2.2.5. Execution Evidence for Sprint Review.

El producto del desarrollo del presente sprint, está reflejado en el siguiente video, donde se muestra todo lo logrado en este sprint. A continuación el link del video:

![image](https://user-images.githubusercontent.com/104078975/270459815-4b5cf797-da63-4a83-9355-9fe4c0ad2370.png)

Link del video: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EaDY_7OrBVNGsjAXORTlPisBfycb7Bn6bKcMeajAVDzhJw?e=Dcavps) 

#### 5.2.2.6. Services Documentation Evidence for Sprint Review.

| Endpoint | Detalles |
| - | - | 
| /signin| Como ruta default tenemos esta, que a la vez es la pantalla de inicio de sesión | 
| /signup | En esta ruta se muestra la pantalla de registro de usuario | 
| /finance  | En este endpoint se muestra la pantalla relacionada la vista previa de costos y ganancias del tipo usuario agricultor | 
| /costs  | En este endpoint se muestra la pantalla relacionada la vista a detalle de los costos generados del tipo usuario agricultor | 
| /bills  | En este endpoint se muestra la pantalla relacionada la vista a detalle de las ganancias generados del tipo usuario agricultor | 
| /products  | En este endpoint se muestra la pantalla relacionada la vista previa de los productos del del tipo usuario agricultor | 
| /sales  | Este endpoint corresponde al procedimiento de compra de pedido del tipo de usuario comerciante |


#### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Para realizar el proceso de despliegue de lo desarrollado en el Sprint 2, a continuación se detallará paso a paso el procedimiento del despliegue:

Ejecutamos el comando “ng build” en la ruta de nuestro projecto en angular, nos muestra lo siguiente:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/59453bc9-dac5-4ec4-9a75-7e5d6a3bced2)

Se genera la carpeta dist:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/de612d0d-f8dc-4880-a0bf-fde275b96aa8)

Se añade el archivo “netlify.toml” para que netlify pueda entender las rutas de nuestro programa en angular con la siguiente configuración:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/85f73994-0a0a-44f3-ad92-46e12988be51)

Por último, vamos a netlify a la sección que nos permite desplegar nuestra aplicación manualmente para evitar errores:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/0a454407-893f-4f98-87e0-0148f38ccf95)

Y pasamos la carpeta que se encuentra dentro de la carpeta dist generada en nuestro proyecto:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/7b51f439-869e-42b1-89fb-b72966cd289d)

De esta manera el avance del Sprint 2 queda desplegado, a continuación se mostrará la evidencia del despliegue junto con la fecha que se realizó:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/4b49ccb0-3bb6-4ca5-8387-161d80b16049)

Adicionalmente, se usó JSONPlaceholder para albergar los datos dentro del archivo "db.json", que durante el desarrollo del sprint se trabajó como "localhost:XXXX", gracias a JSONPlaceholder se podrá realizar el método GET cuando la aplicación esté desplegada. A continuación el link:

Link del JSONPlaceholder: (https://my-json-server.typicode.com/JorgeGonzales15/AyniDBPrueba) 

Finalmente, se logró desplegar con exito todo el desarrollo trabajado en el Sprint2. A continuación el link:

Link del frontend desplegado: (https://ayni-frontend.netlify.app/signin) 


#### 5.2.2.8. Team Collaboration Insights during Sprint.
Las actividades para el presente Sprint se repartieron en base a la priorización de historias de usuario dentro del producto backlog referidas a las funcionalidades principales de la aplicación web, para ello, se realizaron primero branches por features abordados dentro del sprint para que cada integrante trabaje en esas branches y luego realice el push para ver los cambios. De esta manera, el desarrollo del frontend fue organizada y eficiente. A continuación, se mostrarán las evidencias de los commits:

![Pulse sprint2](https://user-images.githubusercontent.com/104078975/270454769-9d9e3b8f-20c0-494f-82e9-6894ed4acd68.png) 
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/18806c49-8062-49bf-a64f-5011509b9cee)


Network:

![network sprint2](https://user-images.githubusercontent.com/104078975/270454953-c1cbf6c8-dfbc-4afa-809f-f26872b563df.png)
![Network2 srpint2](https://user-images.githubusercontent.com/104078975/270455044-3c869d76-e568-4568-981b-f46ff2f0b0e0.png)

### 5.2.3. Sprint 3
#### 5.2.3.1. Sprint Planning 3.

El Sprint #3 tiene como fecha de inicio el 10/10/2023 y como meta plantea resolver los errores de la primera versión del frontend y adicionar más vistas para lograr una neuva versión que abarque todas las funcionalidades planteadas por el equipo de desarrollo. Además, desarrollar la primera versión de backend para que la aplicación funcione correctamente.

| Sprint # | 3 | 
| - | - | 
| **Sprint Planning Background** | - |
| Date | 2023 - 10 - 15 |
| Time | 19:00 PM |
| Location | Virtual via Google Meet |
| Prepared By | Gonzales Carrión, Jorge Enrique |
| Attendees (to planning meeting) | Gonzales Carrión, Jorge Enrique / Espejo Macuri, Paolo Andre / Paucar De La Cruz, Tatiana Medalith / Huaman Cataño, Miguel Ángel / Zarate Castro, Jose Daniel |
| Sprint 2 - Review Summary | Se realizó un avance de Web Applications |
| Sprint 2 - Retrospective Summary  | Añadir el enlace a Web Applications mediante el botón Call To Action de la Landing Page. <br> Mejorar el diseño de Web Applications. <br> Corregir la documentación |
| **Sprint Goal & User Stories** | - |
| Sprint 3 Goal| Desarrollar la primera versión de Web Services y mejorar Web Applications |
| Sprint 3 - Velocity | El equipo puede aceptar 35 Story Points|
| Sprint 3 - Story Points | La suma de los Story Points de los User Sotires que se atenderá es (33)|

#### 5.2.3.2. Sprint Backlog 3.

En el tercer Sprint Backlog, el equipo completó el frontend, actualizó la landing page para que se pueda redirigir a la aplicación web con el botón call-to-action, y desarrolló una primera versión de backend según reglas de negocio definidas. La herramienta utilizada para manejar las tareas de los miembros del equipo fue Trello. Esta herramienta permitió que se pueda dividir todas las user stories y technical stories en tareas. El objetivo principal del sprint es implementar nueva versión de frontend y las principales technical stories referidas al backend.

Link Trello: (https://trello.com/invite/b/afgi3Iby/ATTIb455d07068fc39cdfde8bf1f2eec39d2600FE94F/ayni)


<table><tr><th valign="top">Sprint 3</th><th colspan="7" valign="top">Implementar nueva versión de frontend y las principales technical stories referidas al backend</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Description</td><td valign="top">Estimation (Hours)</td><td valign="top">Assigned To</td><td valign="top"><p>Status </p><p>(To-do / </p><p>InProcess / </p><p>To Review / </p><p>Done)</p></td></tr>
<tr><td rowspan="2" valign="top">HU-06</td><td rowspan="2" valign="top">Acceder a Calificaciones y Reseñas</td><td valign="top">06\.1</td><td valign="top">Implementar vistas con estilos</td><td valign="top">Realizar los estilos para los componentes creados</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td valign="top">06\.2</td><td valign="top">Implementar calificaciones </td><td valign="top">Realizar los componentes relacionados a las calificaciones</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">HU-05</td><td rowspan="3" valign="top">Seguimiento de Pedidos y Entregas</td><td valign="top">05\.1</td><td valign="top">Implementar vistas con estilos</td><td valign="top">Realizar los estilos para los componentes creados</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td valign="top">05\.2</td><td valign="top">Implementar stepper</td><td valign="top">El stepper consta de 3 pasos y cada uno es de un componente</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td valign="top">05\.3</td><td valign="top">Implementar cards</td><td valign="top">Implementar componentes tipo cards para la visualización de información</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">HU-09</td><td rowspan="2" valign="top">Atender pedidos</td><td valign="top">09\.1</td><td valign="top">Implementar vistas con estilos</td><td valign="top">Realizar los estilos para los componentes creados</td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">09\.2</td><td valign="top">Implementar cards</td><td valign="top">Implementar componentes tipo cards para la visualización de información</td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">HU-12</td><td valign="top">Botón Call To Action</td><td valign="top">12\.1</td><td valign="top">Implementar vinculación al botón call to action </td><td valign="top">Realizar la vinculación en HTTP del botón call to action dentro de la landing page </td><td valign="top">2</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
<tr><td valign="top">HU-14</td><td valign="top">Sistemas de búsqueda y paginación</td><td valign="top">14\.1</td><td valign="top">Implementar paginación y barras de búsquedas en las secciones de la app web</td><td valign="top">Implementar componentes de paginación y barras de búsquedas en las secciones de la app web</td><td valign="top">4</td><td valign="top">Jorge Gonzales</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">TS-01</td><td rowspan="2" valign="top"><p>Autenticación, creación y obtención de usuarios</p><p></p><p></p></td><td valign="top">T01.1</td><td valign="top">Implementar la creación de usuarios</td><td valign="top">Desarrollar la creación de usuarios dentro del backend</td><td valign="top">4</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
<tr><td valign="top">T02.2</td><td valign="top">Implementar seguridad en los usuarios</td><td valign="top">Desarrollar la implementación de seguridad para el password de los usuarios</td><td valign="top">4</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
<tr><td valign="top">TS-02</td><td valign="top"><p>Creación y obtención de cultivos</p><p></p></td><td valign="top">T02.1</td><td valign="top">Implementar la obtención y creación de cultivos</td><td valign="top">Desarrollar la obtención y creación de cultivos dentro del backend</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td valign="top">TS-03</td><td valign="top">Obtención y creación de registros financieros (costos y ganancias)</td><td valign="top">T03.1</td><td valign="top">Implementar la obtención y creación de registros financieros </td><td valign="top">Desarrollar la obtención y creación de registros financieros<br>dentro del backend</td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">TS-04</td><td valign="top"><p>Obtención y creación para productos agrícolas</p><p></p><p></p></td><td valign="top">T04.1</td><td valign="top">Implementar la obtención y creación de productos</td><td valign="top">Desarrollar la obtención de productos dentro del backend</td><td valign="top">4</td><td valign="top">Jorge Gonzales</td><td valign="top">Done</td></tr>
<tr><td valign="top">TS-05</td><td valign="top">Obtención y creación de órdenes de productos de cultivo</td><td valign="top">T05.1</td><td valign="top"><p>Implementar la obtención y  creación de órdenes de productos de cultivo</p><p></p></td><td valign="top">Desarrollar la obtención  y creación de órdenes de productos de cultivo dentro del backend</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
</table>


#### 5.2.3.3. Development Evidence for Sprint Review.

Como parte de las evidencias del sprint review, se demuestran mediante una tabla. Como el sprint #3 abarca adiciones y corecciones dentro del frontend, asimismo, desarrollo de la primera versión de backend, se muestran los commits de ambos repositorios.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| AyniFrontend | feature/orders | dcf13e6 | feat: Added route for orders and updated JSON file | - | 13/10/2023  |
| AyniFrontend | feature/orders | af2e797 | feat(users): Created model and service for users | - | 13/10/2023  |
| AyniFrontend | feature/orders | e68a489 | feat(orders): Created model and service for orders | - | 13/10/2023 |
| AyniFrontend | feature/orders | 938eeb9 | feat(orders): Added order requests component | - | 13/10/2023 |
| AyniFrontend | feature/orders | e80c0c3 | feat(orders): Added order dialog component | - | 13/10/2023 |
| AyniFrontend | feature/orders | 0014a4c | feat: added custom pagination | - | 14/10/2023 |
| AyniFrontend | feature/rates | a80c3c6 | Add files via upload | - | 17/10/2023 |
| AyniFrontend | feature/rates | 69904a9 | Update app.module.ts | - | 17/10/2023 |
| AyniFrontend | feature/rates | 16924cf | Update app-routing.module.ts | - | 17/10/2023 |
| AyniFrontend | feature/rates | 23c8c3e | Update navigation.component.ts | - | 17/10/2023 |
| AyniFrontend | feature/purchases | e55bf2e | feat: Added cancel dialog component | - | 18/10/2023 |
| AyniFrontend | feature/purchases | 3e1943b | refactor: Folder changed | - | 18/10/2023 |
| AyniFrontend | feature/purchases | 53bcb24 | feat: Added purchase card content | - | 18/10/2023 |
| AyniFrontend | feature/purchases | 5ffc8ac | feat: Added purchases main content component | - | 18/10/2023 |
| AyniFrontend | feature/purchases | cc82f5c | feat: Added Progress Bar Module and fixed problems | - | 21/10/2023 |
| AyniBackend | feature/users | 6a85870 | feat(authentication): Added domain objects | - | 28/10/2023 |
| AyniBackend | feature/users | ca21d8c | feat(authentication): Added web security configuration, repositories and command & query | - | 28/10/2023 |
| AyniBackend | feature/users | 073f611 | feat(authentication): Added resources and transform classes | - | 28/10/2023 |
| AyniBackend | feature/users | b960e12 | feat(authentication): Added authcontroller | - | 28/10/2023 |
| AyniBackend | feature/users | d94e6dc | feat: Added database & JPA configurations and APP properties for JWT auth | - | 28/10/2023 |
| AyniBackend | feature/transactions | 6edc2d8b | feat(transaction): add Transaction entity with fields and methods | - | 30/10/2023 |
| AyniBackend | feature/transactions | 1927ae5 | feat(transaction): update Transaction entity with fields and methods | - | 30/10/2023 |
| AyniBackend | feature/transactions | a80590c | feat(transaction): add Transaction query and command | - | 30/10/2023 |
| AyniBackend | feature/transactions | a8e766a | feat(transaction): add Transaction service for query and command | - | 30/10/2023 |
| AyniBackend | feature/transactions | 1dcb815 | chore(transaction): Create TransactionRepository for JPA persistence | - | 30/10/2023 |
| AyniBackend | feature/transactions | a16b95a | feat(transaction): Create resource classes for transaction handling | - | 30/10/2023 |
| AyniBackend | feature/transactions | a169446 | feat(transaction): Add resource-to-entity and entity-to-resource assemblers | - | 30/10/2023 |
| AyniBackend | feature/transactions | 0c1d0c9 | feat(transaction): Implement TransactionController for managing financial transactions | - | 30/10/2023 |
| AyniBackend | feature/transactions | 54e8934 | chore(entity): Remove some entities | - | 30/10/2023 |
| AyniBackend | feature/orders | 7796efb | update orders | - | 01/11/2023 |
| AyniBackend | feature/crops | 7a92d41 | feat: Added open api dependency | - | 01/11/2023 |
| AyniBackend | feature/crops | 7ea4f82 | feat: Added crop aggregate | - | 01/11/2023 |
| AyniBackend | feature/crops | d74fcc3 | feat: Added crop queries | - | 01/11/2023 |
| AyniBackend | feature/crops | 4efa20e | feat: Added crop services | - | 01/11/2023 |
| AyniBackend | feature/crops | 1ce4ed4 | feat: Added crop services implementation | - | 01/11/2023 |
| AyniBackend | feature/crops | 7af3698 | feat: Added crop create command | - | 01/11/2023 |
| AyniBackend | feature/crops | 0c773fb | feat: Added crop repository | - | 01/11/2023 |
| AyniBackend | feature/crops | 44f2644 | feat: Added crop resources | - | 01/11/2023 |
| AyniBackend | feature/crops | 1955870 | feat: Added crop resources assembler | - | 01/11/2023 |
| AyniBackend | feature/crops | 779e24a | feat: Added crop controller | - | 01/11/2023 |
| AyniBackend | feature/products | 8d0f3ed | feat: Added product entity | - | 01/11/2023 |
| AyniBackend | feature/products | 58cfde9 | feat: Added product commands and queries | - | 01/11/2023 |
| AyniBackend | feature/products | 4a282b5 | feat: Added product services | - | 01/11/2023 |
| AyniBackend | feature/products | 4a282b5 | feat: Added product services | - | 01/11/2023 |
| AyniBackend | feature/products | 0b34fd4 | feat: Added product service implementation | - | 01/11/2023 |
| AyniBackend | feature/products | 5d94a97 | feat: Added product repository | - | 01/11/2023 |
| AyniBackend | feature/products | c65a389 | feat: Added product resource | - | 01/11/2023 |
| AyniBackend | feature/products | 2a61994 | feat: Added product resource assembler | - | 01/11/2023 |
| AyniBackend | feature/products | 5724216 | feat: Added product controller | - | 01/11/2023 |


#### 5.2.3.4. Testing Suite Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| acceptance-test-opensource  | main | 1c64cba | Acceptance_test_12.feature | - | 22/10/2023 |
| acceptance-test-opensource  | main | cc93580 | Acceptance_test_13.feature | - | 22/10/2023 |
| acceptance-test-opensource  | main | d5abf52 | Acceptance_test_14.feature | - | 22/10/2023 |
| acceptance-test-opensource  | main | 25f8bb8 | Acceptance_test_15.feature | - | 22/10/2023 |
| acceptance-test-opensource  | main | 340fa4d | Acceptance_test_16.feature | - | 22/10/2023 |
| acceptance-test-opensource  | main | 1c70628 | Acceptance_test_17.feature | - | 01/11/2023 |
| acceptance-test-opensource  | main | aab5abd | Acceptance_test_18.feature | - | 01/10/2023 |
| acceptance-test-opensource  | main | 4dc7e8b | Acceptance_test_19.feature | - | 01/10/2023 |
| acceptance-test-opensource  | main | aee165b | Acceptance_test_20.feature | - | 01/10/2023 |
| acceptance-test-opensource  | main | e57f04a | Acceptance_test_21.feature | - | 01/10/2023 |

#### 5.2.3.5. Execution Evidence for Sprint Review.

En el sprint 3 se alcanzó a desarrollar una primera versión del backend y una nueva de frontend de la aplicación web "Ayni". Por lo tanto, se muestran nuevas vistas relevantes a funcionalidades importantes. A continuación se muestran algunas evidencias:

- HU-06:
  
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3bab4b52-6a29-480c-8172-42245f49463b)

- HU-05:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/9ebdc7fd-69af-41b0-9b6c-4347d239cd30)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/76ced74a-ecb3-4f64-8064-e2872ff9687f)

- HU-09:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/cd616c7b-51b5-40a4-b53a-bd61fd5bb75a)

- HU-12:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/2b42778c-0c00-4de5-9b3c-9c41768c395f)

- Backend: 

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/e29952bf-8363-4881-a1d9-3376d20e8700)




El producto del desarrollo del presente sprint, está reflejado en el siguiente video, donde se muestra todo lo logrado en este sprint. A continuación el link del video:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/7ab15a2c-cf6e-46c2-b3e9-1d74e9469b00)


Link del video: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EQmd9iN-XUZFlTSUv43r9R8BMQFlmJ6z_OfzMRm2Ehdf6g?e=6EZtcH) 

#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

En esta sección, se documentará los endpoints de Web Services, en este sprint se logró abarcar gran parte de los endpoints planteados para la aplicación. Sin embargo, todavía queda adicionar más metodos de regla de negocio. Con respecto a la documentación, se usó OpenApi para documentar la interacción de los usuarios con los controllers  El link del repositorio de WebServices: (https://github.com/upc-pre-202302-GreatMinds-SW51/AyniBackend).

Commits relacionados con documentación:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| AyniBackend | feature/crops | 7a92d41 | feat: Added open api dependency | - | 01/11/2023 |
| AyniBackend | develop | 22e41ae | docs: added open api configuration bean | - | 02/11/2023 |

| Acciones | Endpoint | Detalles | Enlace | Datos de muestra |
| - | - | - | - | - |
| POST | /api/auth/signin | En este endpoint se puede iniciar sesión | http://localhost:8080/swagger-ui/index.html#/Authentication/authenticateUser | username: "Juan" <br> "password: contrasenia" |
| POST | /api/auth/signup | En este endpoint se puede crear el usuario  | http://localhost:8080/swagger-ui/index.html#/Authentication/registerUser | username: "Juan" <br> email: "Juan@gmail.com" <br> "role: farmer" <br> "password: contrasenia" |
| POST | /api/v1/transactions  | En este endpoint se puede realizar el registro de una transacción, de tipo costo o gasto, de igual manera obtenerlos, actualizarlos y borrarlos| http://localhost:8080/swagger-ui/index.html#/Transactions/createTransaction |  "costName": "gasolina", "description": "3 galones de gasolina", "type": "costo", "price": 500, "quantity": 3 |
| GET | /api/v1/transactions  | En este endpoint se puede realizar la obtención de todos los registros de costos o ganancias | http://localhost:8080/swagger-ui/index.html#/Transactions/getAllTransactions | - |
| GET | /api/v1/transactions/{transationId}  | En este endpoint se puede realizar la obtención de un registros de costos o ganancias por id | http://localhost:8080/swagger-ui/index.html#/Transactions/getTransactionById | transactionId: 1 |
| PUT | /api/v1/transactions/{transationId}  | En este endpoint se puede realizar la actualización de una transacción de tipo costo o gasto | http://localhost:8080/swagger-ui/index.html#/Transactions/updateTransaction | transaction Id: 1 // "costName": "gasolina", "description": "3 galones de gasolina", "type": "costo", "price": 500, "quantity": 3|
| DELETE | /api/v1/transactions/{transationId}  | En este endpoint se puede realizar la eliminación de una transacción, de tipo costo o gasto | http://localhost:8080/swagger-ui/index.html#/Transactions/deleteTransaction | transactionId: 1 |
| POST | api/v1//products  | En este endpoint se puede utilizar para registrar un producto | http://localhost:8080/swagger-ui/index.html#/Products/createProduct |   "name": "Cultivo fresco de manzana", "description": "Manzanas frescas", "distance": "12", "depth": "5 centimetros", "weather": "19 centigrados", "groundType": "buena caldad", "season": "verano", "imageUrl": "string" |
| GET | api/v1/products  | En este endpoint se puede utilizar para obtener todos los productos | http://localhost:8080/swagger-ui/index.html#/Products/getAllProducts | - |
| GET | api/v1/products/{productId}  | En este endpoint se puede utilizar para obtener todos un producto por Id | http://localhost:8080/swagger-ui/index.html#/Products/getProductById | productId: 1 |
| GET | api/v1/products/{productId}/crops | En este endpoint se puede utilizar para obtener todos los cultivos del producto | http://localhost:8080/swagger-ui/index.html#/Products/getAllCropsByProductId | productId: 1 |
| GET | api/v1/products/{productId}/crops/{cropId} | En este endpoint se puede utilizar para obtener un cultivo en especifico de un producto en especifico | http://localhost:8080/swagger-ui/index.html#/Products/getCropByProductIdAndCropId | productId: 1, cropId: 1 |
| POST | api/v1/crops  | En este endpoint se puede utilizar para registrar un cultivo | http://localhost:8080/swagger-ui/index.html#/Crops/createCrop | "name": "Papa", "undergrowth": true, "fertilize": true, "oxygenate": true, "line": true, "hole": true, "watered": 32, "pestCleaning": 1,"productId": 1 |
| GET | api/v1/crops  | En este endpoint se puede utilizar para obtener todos los cultivo | http://localhost:8080/swagger-ui/index.html#/Crops/getAllCrops | - |
| GET | api/v1/crops/{cropId}  | En este endpoint se puede utilizar para un cultivo por Id | http://localhost:8080/swagger-ui/index.html#/Crops/getCropById | cropId: 1 |
| POST | api/v1/orders  | En este endpoint se puede utilizar para registrar una orden | http://localhost:8080/swagger-ui/index.html#/Orders/createOrder |   "description": "Papayas muy buenas", "totalPrice": 15, "quantity": 3, "paymentMethod": "mastercard", "status": "On Package", "saleId": 1, "orderedBy": 1, "acceptedBy": 2, "orderedDate": "2023-11-02T13:16:02.798Z" |
| POST | api/v1/orders/{orderId}/qualifications  | En este endpoint se puede utilizar para cambiar el estado de una orden | http://localhost:8080/swagger-ui/index.html#/Orders/qualifyOrder | orderId: 1 |
| POST | api/v1/orders/{orderId}/finalizations | En este endpoint se puede utilizar para cambiar el estado de una orden | http://localhost:8080/swagger-ui/index.html#/Orders/finalizeOrder | orderId: 1 |
| GET | api/v1/orders  | En este endpoint se puede utilizar para obtener todas las ordenes | http://localhost:8080/swagger-ui/index.html#/Orders/getAllOrders | - |
| GET | api/v1/orders/{orderId}  | En este endpoint se puede utilizar para obtener una orden por Id | http://localhost:8080/swagger-ui/index.html#/Orders/getOrderById | orderId: 1 |
| PUT | api/v1/orders{orderId}  | En este endpoint se puede actualizar una orden por Id | http://localhost:8080/swagger-ui/index.html#/Orders/updateOrder | orderId: 1 |
| DELETE | api/v1/orders/{orderId}  | En este endpoint se puede eliminar una orden por Id | http://localhost:8080/swagger-ui/index.html#/Orders/deleteOrder | orderId: 1 |
| POST | api/v1/sales  | En este endpoint se puede utilizar para registrar una venta | http://localhost:8080/swagger-ui/index.html#/Sales/createSale |   "name": "Venta de camote", "description": "buena venta", "unitPrice": 24, "quantity": 2, "imageUrl": "string" |
| GET | api/v1/sales  | En este endpoint se puede utilizar para obtener todas las ventas | http://localhost:8080/swagger-ui/index.html#/Sales/getAllSales | - |
| GET | api/v1/sales/{salesId}  | En este endpoint se puede utilizar para obtener una venta por Id | http://localhost:8080/swagger-ui/index.html#/Sales/getSaleById | saleId: 1 |
| GET | api/v1/sales/{salesId}/orders/{orderId}  | En este endpoint se puede utilizar para obtener una venta por Id en especifico vinculado a una orden por Id en especifico | http://localhost:8080/swagger-ui/index.html#/Sales/getOrderBySaleIdAndOrderId | saleId: 1, orderId: 1 |

Capturas de documentación: 
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/dd20e070-e5d9-4e4e-adcb-94844cc0306b)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/93a12b61-d9e7-4413-a26b-7e208aea0188)

Registro de una venta:
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/a3ecaf14-280f-4dd7-9cb0-98561748f0e9)

Registro de un producto:
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/a6ed3e07-37e0-4e2c-af54-88fc2f1ba8ce)


#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

Para realizar el proceso de despliegue de lo desarrollado en el Sprint 3 con respecto a la neuva versión de Web Applications, a continuación se detallará paso a paso el procedimiento del despliegue:

Ejecutamos el comando “ng build” en la ruta de nuestro projecto en angular, nos muestra lo siguiente:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/59453bc9-dac5-4ec4-9a75-7e5d6a3bced2)

Se genera la carpeta dist:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/de612d0d-f8dc-4880-a0bf-fde275b96aa8)

Se añade el archivo “netlify.toml” para que netlify pueda entender las rutas de nuestro programa en angular con la siguiente configuración:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/85f73994-0a0a-44f3-ad92-46e12988be51)

Por último, vamos a netlify a la sección que nos permite desplegar nuestra aplicación manualmente para evitar errores:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/0a454407-893f-4f98-87e0-0148f38ccf95)

Y pasamos la carpeta que se encuentra dentro de la carpeta dist generada en nuestro proyecto:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/7b51f439-869e-42b1-89fb-b72966cd289d)

De esta manera el avance del Sprint 3 queda desplegado

Link de nueva versión de Landing Page: (https://ayni-landing-page-en.netlify.app/)

Link de nueva versión de frontend: (https://ayni-frontend-open.netlify.app/signin)

Para el despliegue del backend, se usó primero Railway, donde se creó un servicio para el hosting de la base de datos:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3d0be4c7-c43c-4118-ab22-2a12326cb21c)

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/4118ae25-dd34-42e0-be46-9c81ed28d9b4)

Link de base de datos: (https://railway.app/project/781f3e33-7e5c-4896-9802-32175ce32926/service/a7820df3-55e5-46f5-89b7-053902225105)

Luego, se usó Zeaburn para el despliegue del backend, primero se crea un espacio de trabajo:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/48b2b442-60c2-4faf-8fed-bcf35910e529)


Posteriormente, se vincula con Github para realizar el deploy y este es el resultado:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/47892f19-bc27-4d30-8f42-60166e22f131)

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/28dc074c-36d6-439b-9d1e-6c2cc072a6d4)

Como se puede observar, cada vez que se haga un push a la rama master, se realiza un build nuevo para que se apliquen los cambios realizados en el proyecto.

Sin embargo, solo da 7 días de prueba para hacer deploys. Por lo tanto, se buscarán mejores alternativas

Como se puede observar, cada vez que se haga un push a la rama master, se realiza un build nuevo para que se apliquen los cambios realizados en el proyecto.

Sin embargo, solo da 7 días de prueba para hacer deploys. Por lo tanto, se buscarán mejores alternativas

El link es el siguiente: (https://ayni-api.zeabur.app/swagger-ui/index.html#)

#### 5.2.3.8. Team Collaboration Insights during Sprint.


| Alumno | Actividad | 
| - | - | 
| Espejo Macuri, Paolo Andre  | Desarrollo de backend, mejora y adición de vistas de frontend | 
| Gonzales Carrión, Jorge Enrique  | Desarrollo de backend y despliegue | 
| Huaman Catano, Miguel Angel  | Desarrollo de backend, adición de vistas de frontend | 
| Paucar De La Cruz, Tatiana Medalith  | Desarrollo de backend, mejora y adición de vistas de frontend | 
| Zarate Castro, Jose Daniel  | Desarrollo de backend y despliegue frontend| 


Repositorio Frontend:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/91c515b6-ac50-47a6-af98-1697531a52e3)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/054f1a3f-a2df-420e-9c6a-cb77fad4d7cc)


Repositorio Backend:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/b29afa00-db8c-4f78-991b-07587fcfa604)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/5afc0c44-1d04-4a28-af8a-87417f2ee600)

### 5.2.4. Sprint 4
#### 5.2.4.1. Sprint Planning 4.

El Sprint #4 tiene como fecha de inicio el 11/11/2023 y como meta plantea resolver los errores de la versión previa del frontend y adicionar más vistas para lograr versión final que abarque todas las funcionalidades planteadas por el equipo de desarrollo. Además, desarrollar la versión final del backend para que sea utlizada como servicio en el frontend.

| Sprint # | 4 | 
| - | - | 
| **Sprint Planning Background** | - |
| Date | 2023 - 11 - 11 |
| Time | 17:00 PM |
| Location | Virtual via Google Meet |
| Prepared By | Gonzales Carrión, Jorge Enrique |
| Attendees (to planning meeting) | Gonzales Carrión, Jorge Enrique / Espejo Macuri, Paolo Andre / Paucar De La Cruz, Tatiana Medalith / Huaman Cataño, Miguel Ángel / Zarate Castro, Jose Daniel |
| Sprint 3 - Review Summary | Se realizó un avance de Web Applications |
| Sprint 3 - Retrospective Summary  |       |
| **Sprint Goal & User Stories** | - |
| Sprint 4 Goal| Implementar versión final y levantar observaciones de web applications y versión final de web services acorde con las Technical Stories y User Stories planteadas |
| Sprint 4 - Velocity | El equipo puede aceptar 20 Story Points|
| Sprint 4 - Story Points | La suma de los Story Points de los User Sotires que se atenderá es (19)|



#### 5.2.4.2. Sprint Backlog 4.

En el cuarto Sprint Backlog, el equipo complementó el frontend con correcciones en las vistas, asimismo se implementó el backend como servicio para que sea usado con el frontend. Con respecto al backend, se realizaron algunas reglas de negocio para que sean utilizadas en las funciones del frontend de una mejor manera. El objetivo principal del sprint es implementar versión final y levantar observaciones de web applications y versión final de web services acorde con las Technical Stories y User Stories planteadas.

Link Trello: (https://trello.com/invite/b/afgi3Iby/ATTIb455d07068fc39cdfde8bf1f2eec39d2600FE94F/ayni)

<table><tr><th valign="top">Sprint 4</th><th colspan="7" valign="top">Implementar versión final y levantar observaciones de web applications y versión final de web services acorde con las Technical Stories y User Stories planteadas</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Description</td><td valign="top">Estimation (Hours)</td><td valign="top">Assigned To</td><td valign="top"><p>Status </p><p>(To-do / </p><p>InProcess / </p><p>To Review / </p><p>Done)</p></td></tr>
<tr><td rowspan="2" valign="top">TS-06</td><td rowspan="2" valign="top"><p>Seguridad y encriptación para la creación de usuarios</p><p></p><p></p></td><td valign="top">T06.1</td><td valign="top">Implementar JWT para la autorización de usuarios</td><td valign="top">Desarrollar métodos y clases para handlers y tokens para la implementación de JWT</td><td valign="top">4</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
<tr><td valign="top">T06.2</td><td valign="top">Documentar características de autorización Bearer</td><td valign="top">Realizar la documentación relacionada a Bearer </td><td valign="top">1</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
<tr><td valign="top">TS-07</td><td valign="top"><p>Obtención de un cultivo en específico </p><p></p></td><td valign="top">T07.1</td><td valign="top">Implementar la obtención de un cultivo en específico</td><td valign="top">Desarrollar la obtención de un cultivo en específico por su id con la operación RESTful API (GET)  </td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">TS-08</td><td rowspan="3" valign="top">Obtención de productos en venta relacionados a cultivos</td><td valign="top">T08.1</td><td valign="top">Implementar la obtención de un producto en específico</td><td valign="top">Desarrollar la obtención de un producto en específico por su id con la operación RESTful API (GET) </td><td valign="top">4</td><td valign="top">Jorge Gonzales</td><td valign="top">Done</td></tr>
<tr><td valign="top">T08.2</td><td valign="top">Implementar la obtención de todos los cultivos ligados a un producto</td><td valign="top">Desarrollar la obtención de todos los cultivos ligados a un producto en específico por su id con la operación RESTful API (GET) </td><td valign="top">4</td><td valign="top">Jorge Gonzales</td><td valign="top">Done</td></tr>
<tr><td valign="top">T08.3</td><td valign="top">Implementar la obtención de un cultivo en específico de un producto en específico</td><td valign="top">Desarrollar la obtención de un cultivo en específico por su id de un producto ligado a él en específico por su id con la operación RESTful API (GET) </td><td valign="top">4</td><td valign="top">Jorge Gonzales</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">TS-09</td><td rowspan="2" valign="top"><p>Obtención y creación de ventas (sales)</p><p></p><p></p></td><td valign="top">T09.1</td><td valign="top">Implementar la obtención y creación de ventas</td><td valign="top">Desarrollar la obtención de ventas dentro del backend con la operación RESTful API (GET) y la creación de una venta con  la operación RESTful API (POST) </td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">T09.2</td><td valign="top">Implementar la obtención de una venta en específico</td><td valign="top">Desarrollar la obtención de una venta en específico por su id con la operación RESTful API (GET) </td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top"></td></tr>
<tr><td valign="top"></td><td valign="top">T09.3</td><td valign="top">Implementar la obtención de una venta en específico ligada a una orden en específico</td><td valign="top">Desarrollar la obtención de un venta en específico por su id de una orden ligada a él en específico por su id con la operación RESTful API (GET) </td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top"></td></tr>
<tr><td valign="top">TS-10</td><td valign="top">Cambiar estado de órdenes (orders) </td><td valign="top">T10.1</td><td valign="top"><p>Implementar el cambio de estado de una orden</p><p></p></td><td valign="top">Desarrollar el cambio de estado de una orden mediante la operación RESTful API (POST)  </td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
</table>



#### 5.2.4.3. Development Evidence for Sprint Review.

Como parte de las evidencias del sprint review, se demuestran mediante una tabla. Como el sprint #4 abarca la versión final de frontend, asimismo, desarrollo de la versión final de backend, se muestran los commits de ambos repositorios.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| AyniBackend | develop | 5e5529c | fix: Fixed transaction problems | - | 14/11/2023  |
| AyniBackend | develop | 7b2aff1 | feat: Add cors configuration | - | 14/11/2023  |
| AyniFrontend | develop | 41cc7fa | fix: Fixed errors | - | 14/11/2023  |
| AyniBackend | feature/authentication | ed54352 | feat(User): Added lombok getters and setters, and attributes createdAt and updatedAt. | - | 17/11/2023  |
| AyniBackend | feature/authentication | e9d92c1 | feat(User): Added new functions to commands and query services contract and implementations | - | 17/11/2023  |
| AyniBackend | feature/authentication | e9d92c1 | feat(UserCommand): Added new commands. | - | 17/11/2023  |
| AyniBackend | feature/authentication | 874ba03 | feat(authentication): Added token service. | - | 17/11/2023  |
| AyniBackend | feature/authentication | f3d625a | feat(authentication): Added UserDetailsImpl ,UserDetailsServiceImpl, TokenBuilder and UnauthorizedHandler | - | 17/11/2023  |
| AyniBackend | feature/authentication | f3f73ec | feat(User): Added Users Controller and updated resources and transform objects. | - | 17/11/2023  |
| AyniBackend | feature/authentication | 925f27e | feat: Update Open Api Config and Dependencies. | - | 17/11/2023  |
| AyniBackend | feature/authentication | 2ac959d | feat: Update application.properties | - | 17/11/2023  |
| AyniBackend | feature/authentication | 22392d0 | chore: Deleting deprecated files. | - | 17/11/2023  |
| AyniBackend | feature/authentication | fe059a6 | fix: fix auth controller and update database | - | 17/11/2023  |
| AyniFrontend | develop | 9daf1af | fix: Fixed errors | - | 17/11/2023  |
| AyniFrontend | develop | d607713 | feat(auth): Added token storage. | - | 17/11/2023  |
| AyniFrontend | develop | 6f18c55 | feat(auth): Added token storage. | - | 17/11/2023  |
| AyniFrontend | develop | b551db9 | feat(auth): Added AuthInterceptor.ts | - | 17/11/2023  |
| AyniFrontend | develop | 6b380dc | fix(services): Updated base path for services | - | 17/11/2023  |
| AyniFrontend | develop | 01e2af4 | fix(farmer): Updated farmer and select-rol components. | - | 17/11/2023  |
| AyniFrontend | develop | 77e7aa4 | fix(merchant): Updated merchant component | - | 17/11/2023  |
| AyniFrontend | develop | e13d313 | fix(auth): Updated auth components. | - | 17/11/2023  |
| AyniFrontend | develop | 8ffb07e | fix(services): Updated base path for services. | - | 17/11/2023  |
| AyniFrontend | develop | 333a7bd | fix: fix bugs with services | - | 17/11/2023  |
| AyniBackend | feature/authentication | 97338a5 | fix: fix cors | - | 18/11/2023  |
| AyniBackend | feature/authentication | d2bb162 | fix(auth): Update WebSecurityConfiguration.java | - | 18/11/2023  |
| AyniBackend | develop | 905bb4a | feat: Added rate entity | - | 18/11/2023  |
| AyniBackend | develop | 7732dd2 | chore: Changed database | - | 18/11/2023  |
| AyniBackend | develop | 79d9655 | chore: Added user controller | - | 19/11/2023  |
| AyniFrontend | feature/rates_imp | 0c825ee | fix: Fixed bugs that affect the flow | - | 19/11/2023  |
| AyniFrontend | feature/rates_imp | 373a109 | feat: Added external service implementation | - | 19/11/2023  |
| AyniFrontend | feature/rates_imp | a1bafc6 | fix: fixed dialogs and content cards | - | 19/11/2023  |
| AyniFrontend | feature/rates_imp | d6c76d8 | fix: fixed tags and stepper content | - | 19/11/2023  |
| AyniFrontend | feature/rates_imp | 502081e | fix: Fixed bugs | - | 19/11/2023  |
| AyniFrontend | feature/rates_imp | e1ac0db | fix: fixed tags | - | 19/11/2023  |
| Ayni_LandingPageOfficial | develop | f380866 | feat: Update landing page. | - | 22/11/2023  |
| Ayni_LandingPageOfficial | develop | f9757d9 | Update index.html | - | 22/11/2023  |
| Ayni_LandingPageOfficial | develop | c74d947 | Update about the team section | - | 22/11/2023  |
| Ayni_LandingPageOfficial | develop | 3b4590b | Update index.html | - | 22/11/2023  |
| Ayni_LandingPageOfficial | develop | e4b26c5 | Update script.js | - | 22/11/2023  |


#### 5.2.4.4. Testing Suite Evidence for Sprint Review.

En esta sección, se mostrarán las evidencias correspondientes a testing, para el Sprint 4 se realizaron pruebas unitarias para validar el funcionamiento de los endpoints. Además, de mostrar los features relacionados a los Terchnical Stories abordados en este Sprint. 

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| acceptance-test-opensource  | main | ad869c8 | Acceptance_test_22.feature | - | 15/11/2023 |
| acceptance-test-opensource  | main | 8e17033 | Acceptance_test_23.feature | - | 15/11/2023 |
| acceptance-test-opensource  | main | 7e16f90 | Acceptance_test_24.feature | - | 15/11/2023 |
| acceptance-test-opensource  | main | 957a19c | Acceptance_test_25.feature | - | 15/11/2023 |
| acceptance-test-opensource  | main | 4b6432d | Acceptance_test_26.feature | - | 15/11/2023 |
| AyniBackend  | develop | 7dc00d2 | feat: Added tests | - | 22/11/2023 |

A continuación se muestran capturas de 2 pruebas unitarias realizadas en el proyecto de Web Services:

- Esta prueba es para confirmar que se cambió el estado de una orden a calificado:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/285027274-864b203b-b2f7-4b49-84cc-9ebc38a4450b.png)


- Esta prueba es para confirmar que se cambió el estado de una orden a finalizado:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/285027405-1bf03910-1e0d-4953-9f21-e15c477fa68b.png)

Finalmente, las pruebas unitarias son ejecutadas y tuvieron exito:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/285027791-96b643ab-6285-41ec-92ba-3bef87bc4fe9.png)


A continuación se muestra los features relacionados a las technical y user stories:

Este feature está relacionado a la Technical Story #6
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284334754-89dd607d-beb5-43b7-935d-7d40230aa4bb.png)


Este feature está relacionado a la Technical Story #7
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284319171-aff3290d-39c4-4e34-9a58-159cbb69e521.png)

Este feature está relacionado a la Technical Story #8
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284319284-4e25853d-1f40-4188-b01f-0ee02251b8ef.png)

Este feature está relacionado a la Technical Story #9
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284319448-9c700eab-0237-48fc-a51c-cfcbbae43329.png)

Este feature está relacionado a la Technical Story #10
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284319866-2b34b6bb-7ab5-48ec-bd6a-475e9c4b1747.png)


A continuación se muestra los archivos .spec.ts creados del frontend usando Angular de componentes importantes: 

Componente de ventas:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284322054-9f78331a-4a4c-43b0-8352-b04d4036390c.png)

Componente de compra de productos:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284321935-7bb50a9f-6f39-4672-a1e5-d1dc975ad590.png)

Componente de contenido de productos:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284322279-8882b09d-6411-40c2-93e9-d38d42256227.png)

Componente principal de tabla de finanzas:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284322449-22829b8d-2b8e-4a81-aed8-23a1ab2c6745.png)

Componente de calificaciones:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284322611-50054528-8c90-49e7-b54f-f1b7d317202c.png)

Modelo de cultivos:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284322869-7ca3a953-0d8f-4ddf-ae49-176c42c2d17a.png)





#### 5.2.4.5. Execution Evidence for Sprint Review.


En el sprint 4 se alcanzó a desarrollar la ultima versión del backend y frontend de la aplicación web "Ayni". Por lo tanto, se muestran nuevas vistas y endpoints relevantes a funcionalidades. A continuación se muestran algunas evidencias:

- TS-06 (Seguriad y encriptación para la creación de usuarios)

Endpoints de authentication:
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284427843-3e7f2077-92d7-4c71-9a5e-5b4e34eb345f.png)

Creación de usuario:
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284427890-14ff8f05-7758-4e0d-a458-02a00868402b.png)

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284427989-0739dafe-bd4a-4674-b301-a1fd59f60247.png)

Inicio de sesión de usuario:
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428016-708f64bf-93fd-4976-ae2c-426cf0133359.png)


![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428132-baf469fb-5567-4d99-a8e9-f4de9dd556cc.png)


- TS-07 (Obtención de un cultivo en específico):

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428202-c9cc265d-b7ce-4b7b-a0c3-d0f82efb0f9a.png)



- TS-08 (Obtención de productos en venta relacionados a un cultivo):

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428242-0fad0863-b96e-452e-9cb0-3028d6b4cb23.png)




- TS-09 ( Obtención y creación de ventas (sales) )

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428288-e528b0b8-86ab-4115-b214-e5494876a3fb.png)





- TS-10 (Cambiar de estado a las ordenes):

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428350-2d6cf8db-3a41-4e31-b9ba-c69c741d9250.png)


En el sprint 3 se alcanzó a desarrollar una primera versión del backend y una nueva de frontend de la aplicación web "Ayni". Por lo tanto, se muestran nuevas vistas relevantes a funcionalidades importantes. A continuación se muestran algunas evidencias:

- TS-06:
  


- TS-07:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/69d06e11-3634-47f8-9479-ead709f314c2)


- TS-08:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/b2e5eb34-f6fe-4f3d-8b41-5836b3367999)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/36d9ab49-f2ce-43a3-93b8-e98db5bc7bd9)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/46bb3517-a3ae-4ed2-a663-8e25deade98d)


- TS-09:
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/df6bfca4-b30c-43a9-af1d-5dffa217c141)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/823e468e-3b94-4a2e-946a-9618b9dc266d)



- TS-10: 
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3288f819-a037-4cf6-85a1-c6c3bcbc352c)



El producto del desarrollo del presente sprint, está reflejado en el siguiente video, donde se muestra todo lo logrado en este sprint. A continuación el link del video:



Link del video: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EfP2qBfYF0dBvyIwQjN_qAcBdRcTugJ0D6NK3T3k23VlXg?e=71od8y&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19) 


#### 5.2.4.6. Services Documentation Evidence for Sprint Review.

En esta sección, se documentará los endpoints de Web Services, en este sprint se logró abarcar gran parte de los endpoints planteados para la aplicación. Sin embargo, todavía queda adicionar más metodos de regla de negocio. Con respecto a la documentación, se usó OpenApi para documentar la interacción de los usuarios con los controllers  El link del repositorio de WebServices: (https://github.com/upc-pre-202302-GreatMinds-SW51/AyniBackend).

Commits relacionados con documentación:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| AyniBackend | develop | 7b2aff1 | feat: Add cors configuration | - | 14/11/2023  |
| AyniBackend | feature/authentication | 925f27e | feat: Update Open Api Config and Dependencies. | - | 17/11/2023  |


| Acciones | Endpoint | Detalles | Enlace | Datos de muestra |
| - | - | - | - | - |
| POST | /api/v1/auth/signin | En este endpoint se puede iniciar sesión | http://localhost:8080/swagger-ui/index.html#/Authentication/authenticateUser | username: "Juan" <br> "password: contrasenia" |
| POST | /api/v1/auth/signup | En este endpoint se puede crear el usuario  | http://localhost:8080/swagger-ui/index.html#/Authentication/registerUser | username: "Juan" <br> email: "Juan@gmail.com" <br> "role: farmer" <br> "password: contrasenia" |
| GET | /api/v1/users  | En este endpoint se puede realizar la obtención de todos los usuarios registrados | http://localhost:8080/swagger-ui/index.html#/Users/getAllUsers | - |
| GET | /api/v1/users/{userId}  | En este endpoint se puede realizar la obtención de un usuario por id | http://localhost:8080/swagger-ui/index.html#/User/getUserById | userId: 1 |


| Acciones | Endpoint | Detalles | Enlace | Datos de muestra |
| - | - | - | - | - |
| POST | /api/auth/signin | En este endpoint se puede iniciar sesión | http://localhost:8080/swagger-ui/index.html#/Authentication/authenticateUser | username: "Juan" <br> "password: contrasenia" |
| POST | /api/auth/signup | En este endpoint se puede crear el usuario  | http://localhost:8080/swagger-ui/index.html#/Authentication/registerUser | username: "Juan" <br> email: "Juan@gmail.com" <br> "role: farmer" <br> "password: contrasenia" |
| POST | /api/v1/transactions  | En este endpoint se puede realizar el registro de una transacción, de tipo costo o gasto, de igual manera obtenerlos, actualizarlos y borrarlos| http://localhost:8080/swagger-ui/index.html#/Transactions/createTransaction |  "costName": "gasolina", "description": "3 galones de gasolina", "type": "costo", "price": 500, "quantity": 3 |
| GET | /api/v1/transactions  | En este endpoint se puede realizar la obtención de todos los registros de costos o ganancias | http://localhost:8080/swagger-ui/index.html#/Transactions/getAllTransactions | - |
| GET | /api/v1/transactions/{transationId}  | En este endpoint se puede realizar la obtención de un registros de costos o ganancias por id | http://localhost:8080/swagger-ui/index.html#/Transactions/getTransactionById | transactionId: 1 |
| PUT | /api/v1/transactions/{transationId}  | En este endpoint se puede realizar la actualización de una transacción de tipo costo o gasto | http://localhost:8080/swagger-ui/index.html#/Transactions/updateTransaction | transaction Id: 1 // "costName": "gasolina", "description": "3 galones de gasolina", "type": "costo", "price": 500, "quantity": 3|
| DELETE | /api/v1/transactions/{transationId}  | En este endpoint se puede realizar la eliminación de una transacción, de tipo costo o gasto | http://localhost:8080/swagger-ui/index.html#/Transactions/deleteTransaction | transactionId: 1 |
| POST | api/v1/products  | En este endpoint se puede utilizar para registrar un producto | http://localhost:8080/swagger-ui/index.html#/Products/createProduct | "name": "Zanahoria","description": "Rica zanahora","recommendedCultivationDistance": "12","recommendedCultivationDepth": "2","recommendedGrowingClimate": "Templado","recommendedSoilType": "Arenoso","recommendedGrowingSeason": "Otoño","imageUrl": "imagen","userId": 1 |
| GET | api/v1/products  | En este endpoint se puede utilizar para obtener todos los productos | http://localhost:8080/swagger-ui/index.html#/Products/getAllProducts | - |
| GET | api/v1/products/{productId}  | En este endpoint se puede utilizar para obtener todos un producto por Id | http://localhost:8080/swagger-ui/index.html#/Products/getProductById | productId: 1 |
| GET | api/v1/products/{productId}/crops | En este endpoint se puede utilizar para obtener todos los cultivos del producto | http://localhost:8080/swagger-ui/index.html#/Products/getAllCropsByProductId | productId: 1 |
| GET | api/v1/products/{productId}/crops/{cropId} | En este endpoint se puede utilizar para obtener un cultivo en especifico de un producto en especifico | http://localhost:8080/swagger-ui/index.html#/Products/getCropByProductIdAndCropId | productId: 1, cropId: 1 |
| POST | api/v1/crops  | En este endpoint se puede utilizar para registrar un cultivo | http://localhost:8080/swagger-ui/index.html#/Crops/createCrop | "name": "Papa","pickUpWeed": true,"fertilizeCrop": true,"oxygenateCrop": false,"makeCropLine": true,"makeCropHole": true,"wateringDays": 12,"pestCleanupDays": 3,"productId": 1,"userId": 1 |
| GET | api/v1/crops  | En este endpoint se puede utilizar para obtener todos los cultivo | http://localhost:8080/swagger-ui/index.html#/Crops/getAllCrops | - |
| GET | api/v1/crops/{cropId}  | En este endpoint se puede utilizar para un cultivo por Id | http://localhost:8080/swagger-ui/index.html#/Crops/getCropById | cropId: 1 |
| POST | api/v1/orders  | En este endpoint se puede utilizar para registrar una orden | http://localhost:8080/swagger-ui/index.html#/Orders/createOrder |   "description": "Papayas muy buenas", "totalPrice": 15, "quantity": 3, "paymentMethod": "mastercard", "status": "On Package", "saleId": 1, "orderedBy": 1, "acceptedBy": 2, "orderedDate": "2023-11-02T13:16:02.798Z" |
| POST | api/v1/orders/{orderId}/qualifications  | En este endpoint se puede utilizar para cambiar el estado de una orden | http://localhost:8080/swagger-ui/index.html#/Orders/qualifyOrder | orderId: 1 |
| POST | api/v1/orders/{orderId}/finalizations | En este endpoint se puede utilizar para cambiar el estado de una orden | http://localhost:8080/swagger-ui/index.html#/Orders/finalizeOrder | orderId: 1 |
| GET | api/v1/orders  | En este endpoint se puede utilizar para obtener todas las ordenes | http://localhost:8080/swagger-ui/index.html#/Orders/getAllOrders | - |
| GET | api/v1/orders/{orderId}  | En este endpoint se puede utilizar para obtener una orden por Id | http://localhost:8080/swagger-ui/index.html#/Orders/getOrderById | orderId: 1 |
| PUT | api/v1/orders{orderId}  | En este endpoint se puede actualizar una orden por Id | http://localhost:8080/swagger-ui/index.html#/Orders/updateOrder | orderId: 1 |
| DELETE | api/v1/orders/{orderId}  | En este endpoint se puede eliminar una orden por Id | http://localhost:8080/swagger-ui/index.html#/Orders/deleteOrder | orderId: 1 |
| POST | api/v1/sales  | En este endpoint se puede utilizar para registrar una venta | http://localhost:8080/swagger-ui/index.html#/Sales/createSale |   "name": "Venta de camote", "description": "buena venta", "unitPrice": 24, "quantity": 2, "imageUrl": "https://www.gob.mx/cms/uploads/article/main_image/20333/camote1.jpg" |
| GET | api/v1/sales  | En este endpoint se puede utilizar para obtener todas las ventas | http://localhost:8080/swagger-ui/index.html#/Sales/getAllSales | - |
| GET | api/v1/sales/{salesId}  | En este endpoint se puede utilizar para obtener una venta por Id | http://localhost:8080/swagger-ui/index.html#/Sales/getSaleById | saleId: 1 |
| GET | api/v1/sales/{salesId}/orders/{orderId}  | En este endpoint se puede utilizar para obtener una venta por Id en especifico vinculado a una orden por Id en especifico | http://localhost:8080/swagger-ui/index.html#/Sales/getOrderBySaleIdAndOrderId | saleId: 1, orderId: 1 |
| POST | api/v1/rates  | En este endpoint se puede utilizar para crear una calificación de un producto | http://localhost:8080/swagger-ui/index.html#/Rates/createRate | "rate": 5, "date": "25-09-2023","productId": 1, "userId": 1 |
| GET | api/v1/rates  | En este endpoint se puede utilizar para obtener todas las calificaciones | http://localhost:8080/swagger-ui/index.html#/Rates/getAllRates | - |
| GET | api/v1/rates/{ratesId}  | En este endpoint se puede utilizar para obtener una calificación por Id | http://localhost:8080/swagger-ui/index.html#/Rates/getRateById | rateId: 1 |

Capturas de documentación: 

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428390-6e4a1109-2181-4ebf-b796-c0e09d9e535c.png)

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428491-714c12b6-52f1-4438-9d08-bdf4fc289a7d.png)


Registro de una venta:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284428534-edd4a4fd-4945-4099-9bd1-3ceb4c1db7a4.png)


#### 5.2.4.7. Software Deployment Evidence for Sprint Review.
| POST | api/v1/sales  | En este endpoint se puede utilizar para registrar una venta | http://localhost:8080/swagger-ui/index.html#/Sales/createSale |   "name": "Venta de camote", "description": "buena venta", "unitPrice": 24, "quantity": 2, "imageUrl": "string" |
| GET | api/v1/sales  | En este endpoint se puede utilizar para obtener todas las ventas | http://localhost:8080/swagger-ui/index.html#/Sales/getAllSales | - |
| GET | api/v1/sales/{salesId}  | En este endpoint se puede utilizar para obtener una venta por Id | http://localhost:8080/swagger-ui/index.html#/Sales/getSaleById | saleId: 1 |
| GET | api/v1/sales/{salesId}/orders/{orderId}  | En este endpoint se puede utilizar para obtener una venta por Id en especifico vinculado a una orden por Id en especifico | http://localhost:8080/swagger-ui/index.html#/Sales/getOrderBySaleIdAndOrderId | saleId: 1, orderId: 1 |

Capturas de documentación: 
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/dd20e070-e5d9-4e4e-adcb-94844cc0306b)
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/93a12b61-d9e7-4413-a26b-7e208aea0188)

Registro de una venta:
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/a3ecaf14-280f-4dd7-9cb0-98561748f0e9)

Registro de un producto:
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/a6ed3e07-37e0-4e2c-af54-88fc2f1ba8ce)


#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

Para realizar el proceso de despliegue de lo desarrollado en el Sprint 3 con respecto a la neuva versión de Web Applications, a continuación se detallará paso a paso el procedimiento del despliegue:

Ejecutamos el comando “ng build” en la ruta de nuestro projecto en angular, nos muestra lo siguiente:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/270755538-59453bc9-dac5-4ec4-9a75-7e5d6a3bced2.png)

Se genera la carpeta dist:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/270755685-de612d0d-f8dc-4880-a0bf-fde275b96aa8.png)

Se añade el archivo “netlify.toml” para que netlify pueda entender las rutas de nuestro programa en angular con la siguiente configuración:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/270755847-85f73994-0a0a-44f3-ad92-46e12988be51.png)

Por último, vamos a netlify a la sección que nos permite desplegar nuestra aplicación manualmente para evitar errores:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/270755966-0a454407-893f-4f98-87e0-0148f38ccf95.png)

Y pasamos la carpeta que se encuentra dentro de la carpeta dist generada en nuestro proyecto:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/270756120-7b51f439-869e-42b1-89fb-b72966cd289d.png)


De esta manera el avance del Sprint 4 queda desplegado

Link de nueva versión de Landing Page: (https://ayni-landing-page-es.netlify.app)

Link de nueva versión de frontend: (https://ayni-web-app.netlify.app)

Para el despliegue del backend, se usó primero Railway, donde se creó un servicio para el hosting de la base de datos:
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284024893-166c9673-a656-42d9-a15f-a7eaeda60b8f.png)

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284024899-4fa26e5f-2493-44a5-a47b-f1999d2f9b5e.png)


Link de base de datos: (https://railway.app/project/fdae3739-fb24-4303-8569-441190ff133c)

Luego, se usó Zeaburn para el despliegue del backend, primero se crea un espacio de trabajo:
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284024946-31a139f1-37cc-4f38-b28b-ab99cff2b1d0.png)

Posteriormente, se vincula con Github para realizar el deploy y este es el resultado:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284024961-2a2c9a97-5fa1-4cb6-ae81-a9f19dae0edc.png)

De esta manera el avance del Sprint 3 queda desplegado

Link de nueva versión de Landing Page: (https://ayni-landing-page-en.netlify.app/)

Link de nueva versión de frontend: ()

Para el despliegue del backend, se usó primero Railway, donde se creó un servicio para el hosting de la base de datos:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3d0be4c7-c43c-4118-ab22-2a12326cb21c)

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/4118ae25-dd34-42e0-be46-9c81ed28d9b4)

Link de base de datos: (https://railway.app/project/781f3e33-7e5c-4896-9802-32175ce32926/service/a7820df3-55e5-46f5-89b7-053902225105)

Luego, se usó Zeaburn para el despliegue del backend, primero se crea un espacio de trabajo:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/48b2b442-60c2-4faf-8fed-bcf35910e529)


Posteriormente, se vincula con Github para realizar el deploy y este es el resultado:

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/47892f19-bc27-4d30-8f42-60166e22f131)

![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/28dc074c-36d6-439b-9d1e-6c2cc072a6d4)

Como se puede observar, cada vez que se haga un push a la rama master, se realiza un build nuevo para que se apliquen los cambios realizados en el proyecto.

Sin embargo, solo da 7 días de prueba para hacer deploys. Por lo tanto, se buscarán mejores alternativas


El link es el siguiente: (https://ayni-api-test.zeabur.app/swagger-ui/index.html#)

#### 5.2.4.8. Team Collaboration Insights during Sprint.

Las actividades para el presente Sprint se repartieron en base a la priorización de historias de usuario dentro del producto backlog referidas a las funcionalidades principales de la aplicación web y web services, para ello, se realizaron primero branches por features abordados dentro del sprint 4 para que cada integrante trabaje en esas branches y luego realice el push para ver los cambios. De esta manera, el desarrollo del frontend y backend fue organizada y eficiente. A continuación, se mostrarán las evidencias de los commits:



| Alumno | Actividad | 
| - | - | 

| Espejo Macuri, Paolo Andre  | Desarrollo de frontend y backend | 
| Gonzales Carrión, Jorge Enrique  | Desarrollo de frontend y backend | 
| Huaman Catano, Miguel Angel  | Desarrollo de backend | 
| Paucar De La Cruz, Tatiana Medalith  | Desarrollo de frontend y backend | 
| Zarate Castro, Jose Daniel  | Desarrollo de frontend y backend | 



Repositorio Frontend:

![Captura de pantalla 2023-11-22 123908](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/285026016-8e2457b8-9191-4051-beed-0262256ef4ae.png)

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284096132-bc145608-0781-4de9-8ac5-e9c246a1cb17.png)





Repositorio Backend:
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284317990-1927e291-6da9-493b-92ca-479b584cfdf8.png)


![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284318078-846d10cd-172c-4703-b370-f42a6ce325de.png)


Repositorio Landing Page:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/285025766-4314a8ef-24fe-4c71-9e5c-228ac22a99dd.png)




## 5.3. Validation Interviews.

En esta sección, se registra las actividades correspondientes a las entrevistas de validación del proyecto. Estas entrevistas van dirigidas a ambos segmentos objetivos donde se evidencia la interacción con el landing page y con las aplicaciones.

### 5.3.1. Diseño de Entrevistas.

**Segmento Objetivo: Productores que quieren mejorar la calidad de sus ventas**
- **Presentación del entrevistado**
  - ¿Cuál es tu nombre?
  - ¿Qué edad tienes?
  - ¿Hace cuánto se dedica a la agricultura?
- **Explicación de los alcances de la demostración**
  - Landing Page
  - Prinipales tareas en la aplicación
- **Navegación a través de la aplicación web**
  
  **User Flow: Añadir cultivo y plan de cultivo**
  - El usuario ingresa a landing page
  - Busca el botón call to action
  - Se redirige a la sección de registro de usuarios y llena los campos solicitados
  - Selecciona su rol 
  - Se redirige a la sección de Home
  - Ingresa a la sección "Mis Productos"
  - Añade un cultivo
  - Crea un plan de cultivo
  - Ingresa los campos solicitados en el stepper
  - Ingresa sus fechas importantes en el calendario
- **Preguntas principales**
  - ¿Consideras atractiva la manera en la que el producto Ayni está promocionado en la Landing Page?
  - ¿Consideras que el landing page ofrece toda la información necesaria para tener un entendimiento adecuado del funcionamento, propósito y funcionalidades ofrecidas por la apliación?
  - ¿Resulta agradable a la vista la manera en la que la información está presentada?
  - ¿Qué dispositivo utilizaste para acceder al Landing Page? ¿La página presenta  algún tipo de inconveniente de diseño que impida navegar de manera fluida?
  - Del 1 al 10 ¿Cómo calificarías el diseño de la Landing Page?
  - Con respecto a la aplicación, ¿considera que es complicado añadir un cultivo?
  - ¿Los cultivos que son añadidos contienen lo que necesitas saber sobre ellas para su correcto sembrío? ¿Qué otros apartados le gustaría visualizar?
  - ¿Qué opina acerca de la distribución de secciones?
  - ¿Cómo describiría nuestra aplicación web en pocas palabras?
  - ¿Qué características específicas desea usted que agreguemos a la aplicación web?
  - ¿Utiliza actualmente una aplicación web para administrar sus sembríos u obtener información sobre sus plantas? De ser así, ¿Qué características logra diferenciar entra esa aplicación y la nuestra?
  - ¿De todas las características evidenciadas en la aplicación web, cuál cree que debería mejorarse? ¿Por qué?
  - ¿Considera que el diseño es adecuado?



**Segmento Objetivo: Comerciantes que quieren mejorar la calidad de sus ventas**
- **Presentación del entrevistado**
  - ¿Cuál es tu nombre?
  - ¿Qué edad tienes?
  - ¿Hace cuánto se dedica a la venta de productos agrícolas?
- **Explicación de los alcances de la demostración**
  - Landing Page
  - Prinipales tareas en la aplicación
- **Navegación a través de la aplicación web**
  
  **User Flow: Comprar un producto**
  - El usuario ingresa a landing page
  - Busca el botón call to action
  - Se redirige a la sección de registro de usuarios y llena los campos solicitados
  - Selecciona su rol 
  - Se redirige a la sección de Home
  - Ingresa a la sección "Buscar productos"
  - Selecciona un cultivo
  - Hace click en el botón "Comprar"
  - Ingresa los campos solicitados en el stepper
  - Confirma la compra
- **Preguntas principales**
  - ¿Consideras atractiva la manera en la que el producto Ayni está promocionado en la Landing Page?
  - ¿Consideras que el landing page ofrece toda la información necesaria para tener un entendimiento adecuado del funcionamento, propósito y funcionalidades ofrecidas por la apliación?
  - ¿Resulta agradable a la vista la manera en la que la información está presentada?
  - ¿Qué dispositivo utilizaste para acceder al Landing Page? ¿La página presenta  algún tipo de inconveniente de diseño que impida navegar de manera fluida?
  - Del 1 al 10 ¿Cómo calificarías el diseño de la Landing Page?
  - Con respecto a la aplicación, ¿considera que es complicado encontrar un cultivo?
  - ¿Los cultivos que son mostrados contienen lo que necesitas saber sobre ellas para incentivar su compra? ¿Qué otros apartados le gustaría visualizar?
  - ¿Qué opina acerca de la distribución de secciones?
  - ¿Cómo describiría nuestra aplicación web en pocas palabras?
  - ¿Qué características específicas desea usted que agreguemos a la aplicación web?
  - ¿Utiliza actualmente una aplicación web para administrar sus ventas u obtener información sobre los productos agrícolas? De ser así, ¿Qué características logra diferenciar entra esa aplicación y la nuestra?
  - ¿De todas las características evidenciadas en la aplicación web, cuál cree que debería mejorarse? ¿Por qué?
  - ¿Considera que el diseño es adecuado?



### 5.3.2. Registro de Entrevistas.

** Segmento Objetivo: Productores que quieren mejorar la calidad de sus ventas **

Nombre y apellidos: Lissane Mareni

Edad: 19

Distrito: San Juan de Miraflores - Lima

Url: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/Ef_UGsnZQFlCkeu_tTZTGF8B1DlxtM8i4hIh3PbnOAEOFw?e=PUmGMQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Inicio: 0:00

Fin: 11:35

Duración: 11:35

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846433-09e0ddc2-0697-414c-9129-479b27d8701d.png)


Lissane nos brindó su sincera opinión acerca de la landing page y aplicación web, con respecto a la landing page, nos resaltó el diseño atractivo y eficiente de las secciones asimismo con el orden de estas, sin embargo considera que debe tener más relevancia las funcionalidades mostradas incluyendo capturas de pantalla de la aplicación web. Pese a ello, la landing page resultó agradable visualmente para ella, calificándola con un 8 de 10. Por otro lado, con respecto a la aplicación web, no consideró dificil la navegación del flujo de añadir un cultivo, asimismo, está conforme con la distribución de las secciones de la barra de navegación. Sin embargo, cree que se debería mejorar el formulario de añadir un cultivo, donde deberían poner mas datos para el registro. Finalmente, le parecio bueno el diseño de la apliación web, pero sería aún mucho mejor si se mejoraran las observaciones que nos compartió.



Nombre y apellidos: Jesus Orellana

Edad: 31

Distrito: Chincha - Ica

Url: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/Ef_UGsnZQFlCkeu_tTZTGF8B1DlxtM8i4hIh3PbnOAEOFw?e=PUmGMQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Inicio: 11:35

Fin: 23:45

Duración: 12 : 10

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846448-649de3d1-5ffa-4205-98d0-aef514df6e13.png)


Jesús elogia la página web que se le presenta y la considera interesante y beneficiosa para los pequeños productores. Asimismo, él menciona que la aplicación web Ayni es fácil de usar y práctica, especialmente la función para agregar cultivos. Sin embargo, sugiere agregar información adicional, como la especie vegetal y variedad de plantas, y sugiere incorporar imágenes deslizantes para mejorar el diseño. Jesús no utiliza ninguna otra aplicación para administrar sus plantas y no ve ninguna característica específica que deba mejorarse en la aplicación web aparte de lo mencionado anteriormente. En general, está satisfecho con la distribución de las secciones en la aplicación.


Nombre y apellidos: Cristel Flores

Edad: 29

Distrito: Chincha - Ica

Url: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/Ef_UGsnZQFlCkeu_tTZTGF8B1DlxtM8i4hIh3PbnOAEOFw?e=PUmGMQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Inicio: 23:45

Fin: 33:41

Duración: 9 : 56

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846465-ec1bc4ff-97bb-404e-95eb-306ee36a4e5a.png)


En la entrevista, Cristel Flores menciona que el diseño de la página podría mejorar en términos de tonalidades y tamaño de letra, y se señaló la falta de información detallada sobre los planes de pago. Ella también calificó el diseño de la landing page con un 5 sobre 10 y mencionó que se encontró un problema en la sección de inicio de sesión que solo permitía crear una cuenta nueva en lugar de iniciar sesión. Para la aplicación web, Cristel sugirió simplificar la adición de cultivos y personalizar los campos según el tipo de cultivo. Además, propuso incluir información sobre la fecha de siembra y el potencial de cosecha. Asimismo, sugirió mejorar las notificaciones y la interfaz de usuario. Finalmente, mencionó que no utiliza ninguna aplicación de gestión de agricultura.

** Segmento Objetivo: Comerciantes que quieren mejorar la calidad de sus ventas **

Nombre y apellidos: Andre Luna

Edad: 25

Distrito: Lince - Lima

Url: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/Ef_UGsnZQFlCkeu_tTZTGF8B1DlxtM8i4hIh3PbnOAEOFw?e=PUmGMQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Inicio: 33:41

Fin: 45:51

Duración: 12:22

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846481-7eb31de0-e67b-418b-a44c-346ddd6a7cc9.png)


Al analizar la entrevista, Andre nos menciona que las vistas son atracticas y logradas para el propósito de la aplicación que se desea ofrecer, además, le resulta muy facilmente navegar en ella al ser intuitiva y las secciones le parecen bien distribuidas, con respecto a la información brindada acerca de las funcionalidades, considera que es adecuada. No tuvo problemas para abrir la landing page en su dispositivo móvil, debido a ello, calificó la landing page con un 8 de 10. Por otro lado, con respecto a la aplicación web, nos brindó una sugerencia con respecto a la creación de un perfil propio del usuario donde proporcione teléfonos de contacto. De esta manera facilitaria aún más el contacto con el agricultor. De la misma manera, nos dejó sugerencias acerca de la tipografía y de el tamaño de algunos botones. Finalmente, indica que, si bien la aplicación web le parece muy buena, todavia cree que se puede mejorar añadiendo funciones y pulir un poco más las vistas. 

Nombre y apellidos: Favio Onofre

Edad: 21

Distrito: Lince - Lima

Url: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/Ef_UGsnZQFlCkeu_tTZTGF8B1DlxtM8i4hIh3PbnOAEOFw?e=PUmGMQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Inicio: 44:51

Fin: 55:27

Duración: 09:28

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846488-19901ea5-adea-4b6e-913f-1d409ec06763.png)


Favio nos proporcionó su tiempo para que visite la landing page y las web applications de Ayni. Asimismo, nos proprocionó su opiniones acerca del diseño de ambas, lo cual le pareció bueno y adecuado, asimismo con la información brindada acerca delas funcionalidades ofrecidas de la aplicación web dentro de  la landing page, resultadole agradable a la vista. Por otro lado, pudo acceder a la alnding page desde su navegador web sin problema, brindandonos su apreciación con 8 puntos de 10. Sin embargo, mencionó que dentro de la landing page hay algunas cosas para mejorar, como el tamaño de los botones y la cantidad de información brindada siendo un poco excedente. Por otro lado, en la aplicación web, mencionó que desea que la información brindada acerca de los cultivos sea más detallada, con secciones de clima o altura. Finalmente, resaltó que la distribución de las secciones es correcta y de igual manera los colores, pues refleja caracteristicas propias de la agricultura brindando un ambiente ameno. 

Nombre y apellidos: Juli Carrión

Edad: 45

Distrito: Surco - Lima

Url: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/Ef_UGsnZQFlCkeu_tTZTGF8B1DlxtM8i4hIh3PbnOAEOFw?e=PUmGMQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Inicio: 55:27

Fin: 01:03:02

Duración: 11:49

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846496-1428b3de-2338-464b-91bb-9058567bedc3.png)


Juli nos brindó su sincera opinión acerca de la landing page y aplicación web, con respecto a la landing page, nos felicitó por la distribución y promoción del producto dentro de las secciones, tambien considera que ofrece lo necario en cuando información de funcionalidades pero recomendaría reducir un poco del texto y poner las funcionalidades de manera más específica. Sin embargo, le resultó agradable la navegación por las secciones puntuando con un 8 de 10 la landing page. Por otro lado, con respecto a la aplicación web, le resultó nada complicado encontrar y seleccionar un cultivo para comprar, además la distribución de las secciones es buena dado que resume las funcionalidades que ofrecen. Tambien, consdera que no debe añadirse caracteristicas dado que siente que está completa para sus necesidades como comerciante. Sin embargo, cree que la sección de estado de compra debería mostrar más información. Finalmente, resume la aplicación web como muy buena, intuitiva y efectiva, con un diseño adecuado.

### 5.3.3. Evaluaciones según herísticas.

UX Heuristics & Principles Evaluation

En esta sección se realizará el reporte de Heurísticas de usabilidad que se ecnotnraron en la realización de la valdiación con posibles usuarios según su segmento.

**Usability – Inclusive Design – Information Architecture**

**CARRERA : Ingeniería de Software**

**CURSO : Desarrollo de Aplicaciones Open Source**

**SECCIÓN : SW51**

**PROFESORES : Todos**

**AUDITOR : Equipo de desarrollo Greatminds ** 

**CLIENTE(S) : Ayni ** 


- **SITE o APP A EVALUAR:**

Ayni - Aplicación de gestión agrícola. 

- **TAREAS A EVALUAR:**

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Desktop landing page
   1. Información y descripción de la aplicación y sus funcionalidades
   2. Visualización de botón call to action y redirección a web applications
   3. Header y footer apropiado para la landing page
2. Web Applications
   1. Registro de nuevo usuario
   2. Inicio de sesión de usuario existente
   3. Botones interactivos y de uso intuitivo
   4. Creación de cultivos
   5. Navegación y orientación dentro de las secciones
   6. Proceso de compra de cultivo
   7. Visualización de cultivos

- **ESCALA DE SEVERIDAD:**

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

|**Nivel:**|**Descripción**|
| :- | :- |
|**1**|<p>Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco </p><p>frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.</p>|
|**2**|<p>Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de </p><p>superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente </p><p>reléase</p>|
|**3**|<p>Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es </p><p>importante que sean corregidos y se les debe asignar una prioridad alta.</p>|
|**4**|<p>Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de </p><p>la herramienta. Es imperativo que sea corregido antes del lanzamiento</p>|



- **TABLA RESUMEN:**

1. **Web Application**

|*#*|*Problema*|*Escala de severidad*|*Heurística/Principio violada(o)*|
| :-: | :-: | :-: | :-: |
|*1*|*El formato de diseño elegido para los botones es inconsistente*|*1*|*Usabilidad - Consistencia y estándares*|
|*2*|*Al estar en una de las secciones, resulta imposible de diferenciar entre estos debido a que la barra de navegación no indica en qué sección se encuentra el usuario*|*1*|*Usabilidad - Reconocer antes que recordar*|
|*3*|*No existe un apartado de edición de perfil*|*2*|*Usabilidad - Control de usuario y libertad*|
|*4*|*En el inicio de sesión, la card de contenido no resalta diferencia del fondo*|*1*|*Usabilidad - Diseño estético y minimalista*|
|*5*|*Inconsistencia en tamaño de tipografía*|*2*|*Usabilidad - Consistencia y estándares*|

2. **Landing page**

|*#*|*Problema*|*Escala de severidad*|*Heurística/Principio violada(o)*|
| :-: | :-: | :-: | :-: |
|*1*|*El contenido de funcionalidades no se actualiza periódicamente*|*3*|*Information Architecture - Is it credible?*|



- **DESCRIPCIÓN DE PROBLEMAS:**



1. **Web Application**

***PROBLEMA 1:** El formato de diseño elegido para los botones es inconsistente*

***Severidad:** 1*

*Heurística violada: Usabilidad - Consistencia y estándares*

***Problema:***
Botones en sección "Sign In y Sign Up"

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846713-9ed0ca37-09d7-45c7-b111-b614739c209e.png)


Botones en sección "Financial Management"

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846724-a145e2c6-d273-4e4e-9bfc-73b8c11b22f8.png)


*El formato de diseño elegido para los botones “Sign In” es inconsistente a comparación de todas las secciones de la aplicación web. Esto incluye el color y bordes del botón que permite identificarlos. Como consecuencia, esto puede provocar que potencialmente los usuarios se desorienten y no puedan diferenciar el texto de un botón con el cual pueden interactuar.*

***Recomendación:**
Utilizar el mismo estilo de botones para mostrar más información en todas las secciones, de manera que el usuario se familiarice mejor con la aplicación web.*

***PROBLEMA 2:** Al estar en una de las secciones, resulta imposible de diferenciar entre estos debido a que la barra de navegación no indica en qué sección se encuentra el usuario*

***Severidad:** 1*

*Heurística violada: Usabilidad - Reconocer antes que recordar*

***Problema:***

Barra de navegación:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/277204700-cbbfa595-2a68-4619-8a4c-fa66067715cc.png)


*Dentro de las secciones que se ofrecen para ambos roles, no existe ningún indicador resaltante que permita indicar al usuario en qué sección se encuentra, potencialmente provocando que se desubique.*

***Recomendación:**
Resaltar con un cuadro de color resaltante la sección que se seleccione dentro de la barra de navegación, con la finalidad de orientar al usuario.*

***PROBLEMA 3:** No existe un apartado de edición de perfil*

***Severidad:** 2*

*Heurística violada: Usabilidad - Control de usuario y libertad*

***Problema:***

*Dentro de la barra de navegación no hay un apartado de edición de perfil, esto ocasiona que el usuario no brinde y proporcione datos quepeuden llegar a ser relevantes, como teléfono de contacto entre otros campos.*

***Recomendación:**
Implementar un boton o apartado para editar perfil de usuario.*

***PROBLEMA 4:** En el inicio de sesión, la card de contenido no resalta diferencia del fondo*

***Severidad:** 1*

*Heurística violada: Usabilidad - Diseño estético y minimalista*

***Problema:***

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/277204363-409272f0-0261-4092-bccf-3331e5c190c8.png)


*En la pantalla de login, el contenido dento de la card principal de la página, no es notable visualmente ya que no tiene un color que lo diferencie del fondo principal, por lo que el usuario puede forzar la vista y descontrarse para realizar un inicio de sesión exitoso.*

***Recomendación:**
Cambiar el color de la card contenedora de los campos de inicio de sesión*

***PROBLEMA 5:** Inconsistencia en tamaño de tipografía *

***Severidad:** 2*

*Heurística violada: Usabilidad - Consistencia y estándares*

***Problema:***

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/277205109-ba79cecd-1ba0-489c-a18e-f8eeb0a91a3a.png)

*En las pantallas de home para ambos roles, existe una incosistencia en el tamaño de la tipografía, lo que ocasiona insatisfacción visual al usuario al momento de navegar por las pantallas de home*


***Recomendación:**
Corregir la tipografía en todas las secciones de un tamaño equivalente*


1. **Landing Page**

***PROBLEMA 1:**  El contenido de funcionalidades no se actualiza periodicamente*

***Severidad:** 3*

*Heurística violada: Information Architecture - Is it credible?*

***Problema:***

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/277208099-62d39d65-9fa9-4d98-859a-cf2b655faad0.png)

*En la sección de funcionalidades, algunas de estas ya no se están implementando, por lo que el usuario puede ser confundido al querer usar esas caracteristicas*

***Recomendación:**
Corregir las funcionalidades mostradas en las listas de la sección*



## 5.4. Video About-the-Product.

A continuación, se mostrará el Video About the Product, donde se mostrará las carácteristicas de la Landing Page para los segmentos objetivos interesados. De igual manera, la aplicación web será mostrada en su nueva versión del Sprint #3, abarcando muchas más funcionalidades para ser expuestas en este video. Finalmente, también incluye un testimonio de uso realizado en una entrevista de validación:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/278846579-582e24d7-4221-4bb3-a38d-39a876d69ce6.png)


Link: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/Echgms5rbepHnsyhy31ZYW8BSf-ggaZUfXAQpmJLpkg_3w?e=tazdiw&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19) 


Finalmente, se realizó una nueva versión del Video About The Product, donde se mostrará a totalidad las funcionalidades de la aplicación web como resultado del Sprint #4. A continuación el link del video:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284323869-230db99a-26b0-45d5-9f22-39764eb77d27.png)

Link: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EQSk9OOAoklOpWKUBSAHzBgBr3601RYb6MocpL8xReV2WQ?e=NhCrP8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)





# Conclusiones

- En conclusión, en este entregable se ha definidio la idea de negocio para el proyecto, asimismo, la problemática que se busca solucionar y a raiz de ello se utilizaron herramientas y artefactos para los puntos de este entregable, tales como: 5W's y 2H's, Lean Ux, Entrevistas, As-Is y To-Be Scenario Mapping, entre otros. Todos estos artefactos sirvieron para identificar las caracteristicas que deben estar presentes en el futuro del desarrollo de la aplicación web para satisfacer a la problematica planteada.
  
- Por otro lado, se definieron los General Style Guidelines que sirvieron de base para diseños los Wireframes y Mock-ups de la aplicación web y de la landing page, donde se evidenciaran todos los principios que se propusieron para el futuro desarrollo de la aplicación web.

- Se desarrolló la Landing Page en base al Sprint presentado en esta entrega, donde todos los integrantes del equipo desarrollaron secciones que componen la Landing, de esta manera los usuarios pueden visitar la landing page para posteriormente acceder a la aplicación web.

- Se desarrolló una avance del frontend en base al Sprint presentado en esta entrega, donde todos los integrantes del equipo de desarrollaron features priorizados dentro del producto backlog, se puede hacer un desarrollo del frontend sin importar el backend al usar una fake api.

- Se desarrollo una nueva version de Web Applications en base al Sprint presentado en la entrega TB2, corrigiendo y anadiendo features para una mejor experiencia de usuario y para una mejor conexion con los Web Services.

- Se desarrollo la primera version de Web Services, donde como principal base tenemos la logica de negocio orientada al producto solucion, se implementaron operaciones de features de mantenimiento, sin embargo, se planificaron en algunos features incluir logica de negocio. Por otro lado, la implementacion fue un poco complicada, debido a que se tenia que usar dependencias e inyecciones.

- En conclusión, el proyecto de desarrollo de la aplicación web, con un frontend en Angular y un backend en Java, implementado mediante metodologías ágiles, ha demostrado la eficacia de la colaboración dentro de un equipo multidisciplinario de desarrollo de software. La combinación de tecnologías modernas, enfoques ágiles y la diversidad de habilidades en el equipo permitió alcanzar los objetivos establecidos de manera eficiente. La aplicación resultante no solo cumple con los requisitos funcionales, sino que también refleja la adaptabilidad del equipo frente a los cambios y la capacidad para enfrentar desafíos de manera colaborativa. Este proyecto no solo ha mejorado nuestras habilidades técnicas, sino que también ha fortalecido la importancia de la comunicación, la flexibilidad y la iteración continua en el proceso de desarrollo de software. En resumen, la experiencia adquirida a lo largo de este proyecto destaca la efectividad de la combinación de tecnologías de vanguardia y metodologías ágiles en la creación exitosa de aplicaciones web robustas y funcionales.

- A continuación, se mostrará el Video About the Team, donde se relata en voz en off la retrospectiva del grupo con respecto al ciclo de vida del proyecto de software realizado. Además, cada integrante del equipo de desarrollo resume sus tareas realizadas durante el ciclo de vida del proyecto de software. A continuación el link del video:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284324945-04bc9c9f-3eb0-4711-9e49-b79341ce5a4c.png)


Link: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EbkzzmlLil1Mt0T0Xu1XmhkBoba7XcaDEOFrP2nIWuR3fA?e=K4sRnW&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19) 


Finalmente, se realizó una nueva versión del Video About The Team, donde se actualizará la retrospectiva con respecto al Sprint 4 y se adicionará el resumen de tareas del sprint 4. A continuación el link del video:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/104078975/284408492-bbb08973-97a1-4d8b-b39c-167d52eee3d0.png)


Link: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EeTNdVyXTh1Kra1Knyck_tIB7c1uBw6JMdB_sPRG8jF5og?e=yCIwHe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


# Referencias

COMEXPERU (2020). PROBLEMAS DEL SECTOR AGRÍCOLA EXPLICARÍAN LOS MENORES INGRESOS DE LOS PRODUCTORES - Sociedad de Comercio Exterior del Perú. Recuperado de https://www.comexperu.org.pe/articulo/problemas-del-sector-agricola-explicarian-los-menores-ingresos-de-los-productores

INEI (2022). Comportamiento de los indicadores de mercado laboral a Nivel Nacional. Recuperado de https://m.inei.gob.pe/media/MenuRecursivo/boletines/03-informe-tecnico-empleo-nacional-abr-may-jun-2022.pdf 

MINAGRI (s.f). PROBLEMAS TIPO DE LA AGRICULTURA PERUANA. Recuperado de https://www.midagri.gob.pe/portal/22-sector-agrario/vision-general/190-problemas-en-la-agricultura-peruana

COEECI (2022). Problemático del agro en el Perú: Impactos a los agricultores y propuestas de acción. Recuperado de https://coeeci.org.pe/problematica-del-agro-en-el-peru-impactos-a-los-agricultores-y-propuestas-de-accion/

El Comercio (2023). CCL: sector agro perdería hasta S/50,8 millones diarios por lluvias e inundaciones. Recuperado de https://elcomercio.pe/economia/peru/ccl-sector-agro-perderia-hasta-s-508-millones-diarios-por-lluvias-huaicos-e-inundaciones-camara-de-comercio-de-lima-peru-ciclon-yaku-noticia/

Congreso de la Reública (2020). Boletín Social N°30. Gobierno estima pérdidas por S/1,611 millones en el sector agropecuario este año por efecto de cuarentena. Recuperado de https://www.congreso.gob.pe/Docs/Otamdegrl/files/boletinsocial/bs_30_julio_2020.pdf


# Anexos

Video Exposición TB1: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EfGXv140UdJAj5qJjl92k4MBiX5R0c1zXJI3MsotH5xepg?e=qk0X0x)

Video Exposición TP: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EQPFOrKXordClMuFSr95AvYBJKBR76KKGIh9Pg8WC_oJ-A?e=WruxwM&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Video Exposición TB2: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EROzWQRXTARGlUSPcyhqVnEBMrkDVFGmj15QiT0DEUbJIA?e=S2DCNl&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Video Exposición TF: (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EcJ-y2UQysVIhsYV1CXsnZYBiQ8jPbYuK1AYdlaQtPmptw?e=AIzA8g&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Video About the Team (Sprint 4): https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EeTNdVyXTh1Kra1Knyck_tIB7c1uBw6JMdB_sPRG8jF5og?e=Q7MUjz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Video About the product (Sprint 4): https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EQSk9OOAoklOpWKUBSAHzBgBr3601RYb6MocpL8xReV2WQ?e=QysXis&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
