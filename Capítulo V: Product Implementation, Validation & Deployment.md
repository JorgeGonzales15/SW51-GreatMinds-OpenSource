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

Como mencionamos anteriormente, se utilizará GitHub para llevar un control de las versiones de desarrollo y poder trabajar de forma colaborativa. Para ello, se creó una organización llamada: [Github Organización](https://github.com/upc-pre-202302-GreatMinds-SW51) 

Repositorio del landing page: [Repositorio Landing Page](https://github.com/upc-pre-202302-GreatMinds-SW51/Ayni_LandingPageOfficial/tree/Release/1.0) 

Repositorio pruebas de aceptación: [Github](https://github.com/upc-pre-202302-GreatMinds-SW51/acceptance-test-opensource) 

Repositorio Frontend: [Github](https://github.com/upc-pre-202302-GreatMinds-SW51/AyniFrontend) 

Repositorio de uso para usar el servicio de JSONPlaceholder: [Github](https://github.com/JorgeGonzales15/AyniDBPrueba) 


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

Link del video: [Video Evidencia](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EboHBmisglROmEJioyVBF5YBZ_Pr7cydTYr8pFi8njPn8A?e=SJBY3T) 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

No se utilizó ningún servicio adicional, pues este primer Sprint solo consta de la implementación del landing page.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Como se mencionó, se utilizó Netlify para el despliegue automático del landing page con todos los cambios realizados por el equipo. Netlify se integra con nuestra organización en GitHub y luego con el repositorio, siendo la rama main la que utilizamos para el despliegue. El enlace es el siguiente: 
[Ayni Landin Page](https://aynilandingpage.netlify.app/)

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
<tr><td rowspan="3" valign="top">HU-08</td><td rowspan="3" valign="top">Planificar actividades agrícolas</td><td valign="top">08\.1</td><td valign="top">Implementar fake-api</td><td valign="top">Implementar fake api para posts o gets de entidades</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.2</td><td valign="top">Implementar estilos </td><td valign="top">Diseñar la página con los Styles Guidelines definidos</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.3</td><td valign="top">Implementar stepper </td><td valign="top">El stepper consta de 3 pasos y cada uno es de un componente</td><td valign="top">4</td><td valign="top">Miguel Huaman</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">HU-04</td><td rowspan="3" valign="top">Realizar pedidos de productos</td><td valign="top">08\.1</td><td valign="top">Implementar fake-api</td><td valign="top">Implementar fake api para posts o gets de entidades</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.2</td><td valign="top">Implementar estilos </td><td valign="top">Diseñar la página con los Styles Guidelines definidos</td><td valign="top">4</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td valign="top">08\.3</td><td valign="top">Implementar stepper </td><td valign="top">El stepper consta de 3 pasos y cada uno es de un componente</td><td valign="top">5</td><td valign="top">Paolo Espejo</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">HU-03</td><td rowspan="3" valign="top">Explorar productos agrícolas</td><td valign="top">03\.1</td><td valign="top">Implementar estilos</td><td valign="top">Diseñar los estilos para las páginas</td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">03\.2</td><td valign="top">Implementar formularios</td><td valign="top">Implementar formularios para añadir cultivos</td><td valign="top">5</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td valign="top">03\.3</td><td valign="top">Implementar página de productos</td><td valign="top">Implementar cars para explorar los productos agrícolas</td><td valign="top">4</td><td valign="top">Tatiana Paucar</td><td valign="top">Done</td></tr>
<tr><td rowspan="3" valign="top">HU-09</td><td rowspan="3" valign="top">Registro de gastos y ganancias</td><td valign="top">09\.1</td><td valign="top">Implementar estilos </td><td valign="top">Diseñar los estilos para las páginas</td><td valign="top">4</td><td valign="top">Jorge Gonzales Carrión</td><td valign="top">Done</td></tr>
<tr><td valign="top">09\.2</td><td valign="top">Implementar las listas de costos y ganancias</td><td valign="top">Implementar con las listbox con el framework requerido</td><td valign="top">5</td><td valign="top">Jorge Gonzales Carrión</td><td valign="top">Done</td></tr>
<tr><td valign="top">09\.3</td><td valign="top">Cards con información de costos y gastos</td><td valign="top">Implementar cards con la información de costos y gatos</td><td valign="top">5</td><td valign="top">Jorge Gonzales Carrión</td><td valign="top">Done</td></tr>
<tr><td valign="top">HU-21</td><td valign="top">Sección principal (“Home”)</td><td valign="top">21\.1</td><td valign="top">Paginas de “Home”</td><td valign="top">Implementar páginas de “Home”</td><td valign="top">4</td><td valign="top">Jose Zarate</td><td valign="top">Done</td></tr>
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

Link del video: [Video Evidencia](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EaDY_7OrBVNGsjAXORTlPisBfycb7Bn6bKcMeajAVDzhJw?e=Dcavps) 

#### 5.2.2.6. Services Documentation Evidence for Sprint Review.

| Endpoint | Detalles |
| - | - | 
| /signin| Como ruta default tenemos esta, que a la vez es la pantalla de inicio de sesión | 
| /signup | En esta ruta se muestra la pantalla de registro de usuario | 
| /select-rol  | En este endpoint se muestra la pantalla relacionada a la selección de roles | 
| /finance  | En este endpoint se muestra la pantalla relacionada la vista previa de costos y ganancias del tipo usuario agricultor | 
| /costs  | En este endpoint se muestra la pantalla relacionada la vista a detalle de los costos generados del tipo usuario agricultor | 
| /bills  | En este endpoint se muestra la pantalla relacionada la vista a detalle de las ganancias generados del tipo usuario agricultor | 
| /products  | En este endpoint se muestra la pantalla relacionada la vista previa de los productos del del tipo usuario agricultor | 
| /product-details  | En este endpoint se muestra la pantalla relacionada la vista a detalle de un producto seleccionado del tipo usuario agricultor | 
| /farmer-home  | En este endpoint se muestra lo correspondiente a funcionalidades para el rol de agricultor | 
| /merchant-home  | En este endpoint se muestra lo correspondiente a funcionalidades para el rol de comerciante | 
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

Link del JSONPlaceholder: [JSONPlaceholder](https://my-json-server.typicode.com/JorgeGonzales15/AyniDBPrueba) 

Finalmente, se logró desplegar con exito todo el desarrollo trabajado en el Sprint2. A continuación el link:

Link del frontend desplegado: [Netlify](https://ayni-frontend.netlify.app/signin) 


#### 5.2.2.8. Team Collaboration Insights during Sprint.
Las actividades para el presente Sprint se repartieron en base a la priorización de historias de usuario dentro del producto backlog referidas a las funcionalidades principales de la aplicación web, para ello, se realizaron primero branches por features abordados dentro del sprint para que cada integrante trabaje en esas branches y luego realice el push para ver los cambios. De esta manera, el desarrollo del frontend fue organizada y eficiente. A continuación, se mostrarán las evidencias de los commits:

![Pulse sprint2](https://user-images.githubusercontent.com/104078975/270454769-9d9e3b8f-20c0-494f-82e9-6894ed4acd68.png) 
![image](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/18806c49-8062-49bf-a64f-5011509b9cee)


Network:

![network sprint2](https://user-images.githubusercontent.com/104078975/270454953-c1cbf6c8-dfbc-4afa-809f-f26872b563df.png)
![Network2 srpint2](https://user-images.githubusercontent.com/104078975/270455044-3c869d76-e568-4568-981b-f46ff2f0b0e0.png)

### 5.2.3. Sprint 3
#### 5.2.3.1. Sprint Planning 3.

| Sprint # | 3 | 
| - | - | 
| **Sprint Planning Background** | - |
| Date | 2023 - 10 - 20 |
| Time | 19:00 PM |
| Location | Virtual via Google Meet |
| Prepared By | Gonzales Carrión, Jorge Enrique |
| Attendees (to planning meeting) | Gonzales Carrión, Jorge Enrique / Espejo Macuri, Paolo Andre / Paucar De La Cruz, Tatiana Medalith / Huaman Cataño, Miguel Ángel / Zarate Castro, Jose Daniel |
| Sprint 2 - Review Summary | Se realizó un avance de Web Applications |
| Sprint 2 - Retrospective Summary  | Añadir el enlace a Web Applications mediante el botón Call To Action de la Landing Page. <br> Mejorar el diseño de Web Applications. <br> Corregir la documentación |
| **Sprint Goal & User Stories** | - |
| Sprint 3 Goal| Desarrollar la primera versión de Web Services y mejorar Web Applications |
| Sprint 3 - Velocity | El equipo puede aceptar XX Story Points|
| Sprint 3 - Story Points | La suma de los Story Points de los User Sotires que se atenderá es (XX)|

#### 5.2.2.2. Sprint Backlog 3.



#### 5.2.3.3. Development Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| AyniFrontend |  | | | - |   |
| AyniFrontend |  | | | - |   |
| AyniFrontend |  | | | - |   |
| AyniFrontend |  | | | - |   |
| AyniFrontend |  | | | - |   |
| AyniFrontend |  | | | - |   |

#### 5.2.3.4. Testing Suite Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| acceptance-test-opensource | main |  | | - | |
| acceptance-test-opensource | main |  | | - | |
| acceptance-test-opensource | main |  | | - | |
| acceptance-test-opensource | main |  | | - | |
| acceptance-test-opensource | main |  | | - | |
| acceptance-test-opensource | main |  | | - | |
| acceptance-test-opensource | main |  | | - | |
| acceptance-test-opensource | main |  | | - | |

#### 5.2.3.5. Execution Evidence for Sprint Review.

El producto del desarrollo del presente sprint, está reflejado en el siguiente video, donde se muestra todo lo logrado en este sprint. A continuación el link del video:



Link del video: [Video Evidencia]() 

#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

| Endpoint | Detalles |
| - | - | 
| | | 



#### 5.2.3.7. Software Deployment Evidence for Sprint Review.




#### 5.2.3.8. Team Collaboration Insights during Sprint.


## 5.3. Validation Interviews.

En esta sección, se registra las actividades correspondientes a las entrevistas de validación del proyecto. Estas entrevistas van dirigidas a ambos segmentos objetivos donde se evidencia la interacción con el landing page y con las aplicaciones.

### 5.3.1. Diseño de Entrevistas.



### 5.3.2. Registro de Entrevistas.




### 5.3.3. Evaluaciones según herísticas.

**UX Heuristics & Principles Evaluation**
--- 

**Usability – Inclusive Design – Information Architecture**

**CARRERA : Ingeniería de Software**

**CURSO : Desarrollo de Aplicaciones Open Source**

**SECCIÓN : SW51**

**PROFESORES : Todos**

**AUDITOR :** 

**CLIENTE(S) :** 


- **SITE o APP A EVALUAR:**

sdasd

- **TAREAS A EVALUAR:**

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Desktop landing page
   1. Información y descripción de la aplicación y sus funcionalidades
   1. Visualización de planes de pago y precio de la aplicación
   1. Visualización de botón de descarga de la aplicación
   1. Header y footer apropiado para la landing page
   1. Etc.
1. Mobile App Wireframes
   1. Registro de nuevo usuario
   1. Inicio de sesión de usuario existente
   1. Pestañas de navegación dentro de la aplicación
   1. Botones interactivos y de uso intuitivo
   1. Búsqueda de temas académicos
   1. Navegación y orientación dentro de la realidad virtual
   1. Apertura y visualización de libros académicos
   1. Visualización de perfil de usuario
   1. Creación y navegación dentro de aula
   1. Opción de cargar material educativo dentro de la aplicación
   1. Mensajes que orienten al usuario sobre el estado del sistema

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Desktop landing page
   1. Formulario para crear cuenta o iniciar sesión
   1. Redes sociales asociadas a la startup
   1. Política de privacidad y condiciones de uso
1. Mobile App Wireframes
   1. Ventanas emergentes
   1. Notificaciones de la aplicación
   1. Opción de cambio de idioma
   1. Política de privacidad y condiciones de uso

- **ESCALA DE SEVERIDAD:**

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:



- **TABLA RESUMEN:**





- **DESCRIPCIÓN DE PROBLEMAS:**



1. **Desktop Landing Page**

***PROBLEMA #1:** El formato de diseño elegido para los botones “Ver más” es inconsistente*

***Severidad:** 1*

*Heurística violada: Usabilidad - Consistencia y estándares*

***Problema:***

*El formato de diseño elegido para los botones “Ver más” es inconsistente dentro de todas las secciones de la landing page. Esto incluye el tamaño de la letra, color, bordes del botón e iconografía que permite identificarlos. Como consecuencia, esto puede provocar que potencialmente los usuarios se desorienten y no puedan diferenciar el texto de un botón con el cual pueden interactuar.*

***Recomendación:**
Utilizar el mismo estilo de botones para mostrar más información en todas las secciones, de manera que el usuario se familiarice mejor con el Landing Page.*



## 5.4. Video About-the-Product.





# Conclusiones

- En conclusión, en este entregable se ha definidio la idea de negocio para el proyecto, asimismo, la problemática que se busca solucionar y a raiz de ello se utilizaron herramientas y artefactos para los puntos de este entregable, tales como: 5W's y 2H's, Lean Ux, Entrevistas, As-Is y To-Be Scenario Mapping, entre otros. Todos estos artefactos sirvieron para identificar las caracteristicas que deben estar presentes en el futuro del desarrollo de la aplicación web para satisfacer a la problematica planteada.
  
- Por otro lado, se definieron los General Style Guidelines que sirvieron de base para diseños los Wireframes y Mock-ups de la aplicación web y de la landing page, donde se evidenciaran todos los principios que se propusieron para el futuro desarrollo de la aplicación web.

- Se desarrolló la Landing Page en base al Sprint presentado en esta entrega, donde todos los integrantes del equipo desarrollaron secciones que componen la Landing, de esta manera los usuarios pueden visitar la landing page para posteriormente acceder a la aplicación web.

- Se desarrolló una avance del frontend en base al Sprint presentado en esta entrega, donde todos los integrantes del equipo de desarrollaron features priorizados dentro del producto backlog, se puede hacer un desarrollo del frontend sin importar el backend al usar una fake api.

# Referencias

COMEXPERU (2020). PROBLEMAS DEL SECTOR AGRÍCOLA EXPLICARÍAN LOS MENORES INGRESOS DE LOS PRODUCTORES - Sociedad de Comercio Exterior del Perú. Recuperado de https://www.comexperu.org.pe/articulo/problemas-del-sector-agricola-explicarian-los-menores-ingresos-de-los-productores

INEI (2022). Comportamiento de los indicadores de mercado laboral a Nivel Nacional. Recuperado de https://m.inei.gob.pe/media/MenuRecursivo/boletines/03-informe-tecnico-empleo-nacional-abr-may-jun-2022.pdf 

MINAGRI (s.f). PROBLEMAS TIPO DE LA AGRICULTURA PERUANA. Recuperado de https://www.midagri.gob.pe/portal/22-sector-agrario/vision-general/190-problemas-en-la-agricultura-peruana

COEECI (2022). Problemático del agro en el Perú: Impactos a los agricultores y propuestas de acción. Recuperado de https://coeeci.org.pe/problematica-del-agro-en-el-peru-impactos-a-los-agricultores-y-propuestas-de-accion/

El Comercio (2023). CCL: sector agro perdería hasta S/50,8 millones diarios por lluvias e inundaciones. Recuperado de https://elcomercio.pe/economia/peru/ccl-sector-agro-perderia-hasta-s-508-millones-diarios-por-lluvias-huaicos-e-inundaciones-camara-de-comercio-de-lima-peru-ciclon-yaku-noticia/

Congreso de la Reública (2020). Boletín Social N°30. Gobierno estima pérdidas por S/1,611 millones en el sector agropecuario este año por efecto de cuarentena. Recuperado de https://www.congreso.gob.pe/Docs/Otamdegrl/files/boletinsocial/bs_30_julio_2020.pdf


# Anexos

Video Exposición TB1: [Microsoft Streams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EfGXv140UdJAj5qJjl92k4MBiX5R0c1zXJI3MsotH5xepg?e=qk0X0x)

Video Exposición TP: [Microsoft Streams](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EQPFOrKXordClMuFSr95AvYBJKBR76KKGIh9Pg8WC_oJ-A?e=WruxwM&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Video Exposición TB2: [Microsoft Streams]()
