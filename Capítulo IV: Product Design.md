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

En esta sección, se presentan los wireflows de la aplicación guiándose de las historias de usuario en la herramienta LucidChart.

Link de Lucidchar: [Wireflows LucidChart](https://lucid.app/lucidchart/aa72d3cf-f994-4a82-9ad8-044f3b9fc331/edit?viewport_loc=676%2C-2242%2C15341%2C7356%2C0_0&invitationId=inv_0da86b32-9131-4d2a-9317-1d95207a50e7)

**Usar Goal:** Como usuario, quiero poder registrarme en la aplicación para acceder a las funcionalidades disponibles.

**Task Flow:**
- Primero se observará la pantalla de inicio de sesión, en esta se puede o iniciar o registrarse
- Si accede a registrarse, se mostrará la pantalla de registro. Puede regresar a iniciar sesión o continuar
- Finalmente, se accede a la pantalla de selección de roles si es que se registra, para que acceda a la aplicación.

![wirefrlow 1 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/9d53b467-cf0c-4e75-aae8-0206c9668001)

---

**User Goal:** Como agricultor, quiero ingresar los datos correspondientes para la planificación de las actividades agrícolas. 

**Task Flow:**
- Primero se está en la pantalla de “Mis productos”
- Si presiona el botón de “Añadir nuevo producto”, se mostrará la pantalla para rellenar los datos del cultivo 
- Luego, se mostrará un dashboard para la planificación de cultivo, donde se irá introduciendo pasos para la planificación
- Finalmente, se mostrará el calendario de la planificación donde el usuario podrá introducir eventos

![wireflow 2 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/bfce0ee5-bfe7-4f79-b8ab-12d7d1a71a6d)

---

**User Goal:** Como agricultor, quiero registrar los gastos y las ganancias relacionadas con las actividades agrícolas para poder llevar un control financiero.

**Task Flow:**
- Primero se está en la pantalla de “Gestión Financiera”
- Se mostrarán los costos en un label y las ganancias en otro label
- Si el usuario le da click al botón “Ver más”, se mostrarán a detalle los costos o ganancias según haya elegido previamente
- Si el usuario le da click a “Registrar” en la sección que escogió, se mostrará la pantalla de registro.

![wireflow 3 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3ac1f604-0b0e-4ff7-95d6-a74cc3888d63)

---

**User Goal:** Como agricultor, quiero llevar un registro de los insumos agrícolas utilizados para analizarlo y tomar decisiones de acuerdo a ello.

**Task Flow:**
- Primero se tiene que seleccionar un producto
- Luego el usuario da click al botón de “Insumos”
- Le aparecerá la pantalla de los insumos usados ya registrados en el producto

![wireflow 4 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/92807fa0-63cd-4cd3-aff6-173f1af75702)

---

**User Goal:** Como usuario deseo ver los pedidos que tengo de manera rápida y fácil en una pantalla 

**Task Flow:**
- Primero el usuario tiene que estar en la sección del header “Mis pedidos”
- Luego, se mostrará la pantalla de pedidos con las listas de los pedidos pendientes
- Al seleccionar un pedido, el productor puede darle al botón de aceptar o rechazar pedido

![wireflow 5 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/c4ca075b-227c-4063-a9e8-8b3fb43487c7)

---

**User Goal:** Como usuario deseo encontrar los productos de manera rápida para no perder tiempo

**Task Flow:**
- Primero el usuario debe encotnrarse en una de las paginas de inicio o en secciones con paginación
- Luego, el usuario deberá escribir lo que desea en el input y luego darle click al icono de la lupa, en caso de paginación escoger la pagina deseada.

![wireflow 6 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/0e2b2c0c-ff4b-4830-8320-a711f3b29fb9)

---

**Sector: Comerciantes**

**User Goal:** Como comercializador quiero observar los productos disponibles para poder realizar los pedidos

**Task Flow:**

- Primero el usuario tiene que estar en la sección “Buscar Productos” 
- Luego se mostrará la pantalla con los productos disponibles y una descripción

![wireflow 7 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/f78109c8-122d-438a-a1d6-3465570d817a)

---

**Usar Goal:** Como comercializador, quiero poder realizar los pedidos de productos agrícolas para poder realizar las entregas

**Task Flow:**
- Primero el usuario debe estar en la pantalla de buscar productos
- Luego debe seleccionar el producto que desee comprar
- Se debe dar click en comprar y aparecerá la pantalla de dashboard donde debe completar datos para la compra

![wireflow 8 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/cfbc9cdd-f6cc-4307-8b9d-e9a9f5de5c75)

---

**User Goal:** Como comercializador, quiero poder observar el estado de los pedidos y entregas para poder sentirme más tranquilo

**Task Flow:**

- Primero el usuario debe estar en la pestaña de “Mis compras”
- Seleccionar un producto y luego se le mostrará el estado de su compra e información
- Si hace click en el botón “Ver estado” podrá ver detalladamente el estado actual del producto

![wireflow 9 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/a4fd64ee-27c1-4c18-81a8-996b8a2818cc)

---

**User Goal:** Como comercializador, quiero acceder a las calificaciones y reseñas dejadas por los agricultores para saber sobre la valoración de mis servicios

**Task Flow:**
- Primero el usuario debe estar en la sección “Calificaciones” 
- En la siguiente pantalla se mostrará información de los productos que compró y una calificación en estrellas

![wireflow 10 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/8e486e78-ed01-4ede-9846-453b3c3618ca)

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

En esta sección, se presentaran los User Flows, donde se mostrarán las rutas Happy y Unhappy que los usuarios pueden tener al momento de usar la aplicación web. Cabe resaltar que los Happy Paths están represetnadas con flechas en color verde y los Unhappy con flechas de color rojo. Se utilizó la herramienta LucidChart.

Link de Lucidchart:[UserFlow Lucidchart](https://lucid.app/lucidchart/edcb2519-faf5-4a02-8d32-e782a99ffa7f/edit?viewport_loc=-781%2C342%2C12102%2C5535%2C0_0&invitationId=inv_78155e1b-bf61-45ea-9bb8-16f59f2af020)


**User Goal:** Registrar los insumos agrícolas utilizados en un cultivo

**Task Flow:**
- Primero se tiene que seleccionar un producto
- Luego el usuario da click al botón de “Insumos”
- Le aparecerá la pantalla de los insumos usados ya registrados en el producto
- Si el usuario desea editar los insumos puede hacerlo mediante inputs
- Finalmente se le mostrará una pantalla de guardado o una pantalla de eliminación de cultivo si así lo quiere (Unhapy Path)

![userflow1 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/8a65fbfa-9e2b-4f4d-9a15-8a4947ab97cb)

---

**User Goal:** Observar el estado de los pedidos realizados

**Task Flow:**

- Primero el usuario debe estar en la pestaña de “Mis compras”
- Seleccionar un producto y luego se le mostrará el estado de su compra e información
- Si hace click en el botón “Ver estado” podrá ver detalladamente el estado actual del producto
- Si el usuario lo desea puede cancelar su compra (Unhappy Path)

![userflow2 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/bcd167da-4798-4e6a-ba6a-def0127df6b9)


---

**Usar Goal:** Realizar pedidos de productos agrícolas

**Task Flow:**
- Primero el usuario debe estar en la pantalla de buscar productos
- Luego debe seleccionar el producto que desee comprar
- Se debe dar click en comprar y aparecerá la pantalla de dashboard donde debe completar datos para la compra
- Si el usuario lo desea puede cancelar la compra con el botón "Cancelar compra" (Unhappy Path)
  
![userflow3 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/bf758eb8-87d1-41f7-bb8d-39d0b0a10ad7)

---

**User Goal:** Registrar costos y ganancias de mis productos

**Task Flow:**
- Primero se está en la pantalla de “Gestión Financiera”
- Se mostrarán los costos en un label y las ganancias en otro label
- Si el usuario le da click al botón “Ver más”, se mostrarán a detalle los costos o ganancias según haya elegido previamente
- Si el usuario le da click a “Registrar” en la sección que escogió, se mostrará la pantalla de registro.

![userflow 4 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/f306cfc6-4e57-4053-8a73-5801161c8f7f)

---


**User Goal:** Visualizar los pedidos existentes

**Task Flow:**
- Primero el usuario tiene que estar en la sección del header “Mis pedidos”
- Luego, se mostrará la pantalla de pedidos con las listas de los pedidos pendientes
- Al seleccionar un pedido, el productor puede darle al botón de aceptar (Happy Path) o rechazar pedido (Unhappy Path)

![userflow 5 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/904e93d2-9184-40da-838f-c4e635e1915d)

---

**User Goal:** Añadir cultivos y realizar plan de cultivo de este mismo

**Task Flow:**
- Primero se está en la pantalla de “Mis productos”
- Si presiona el botón de “Añadir nuevo producto”, se mostrará la pantalla para rellenar los datos del cultivo 
- Luego, se mostrará un dashboard para la planificación de cultivo, donde se irá introduciendo pasos para la planificación
- Finalmente, se mostrará el calendario de la planificación donde el usuario podrá introducir eventos
- Si el usuario quiere eliminar el cultivo, le debe dar al botón "Elminar cultivo" (Unhappy Path)
  
![userflow 6 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3152792e-b890-435d-9d18-59ed2c68452a)

---


**User Goal:** Calificar los productos que se recibieron

**Task Flow:**
- Primero el usuario debe estar en la sección “Calificaciones” 
- En la siguiente pantalla se mostrará información de los productos que compró y una calificación en estrellas
- Si el usuario no desea dejar califcación simplemente retrocede a la sección de Inicio/Home (Unhappy Path)

![userflow 7 ld](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/42b85ca4-d60b-4ba6-b2d4-748c094cfbfc)

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

Authentication Context:
![authentication context](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/cd4f351e-2ec7-4540-9286-51eb25ac3781)

Planification Context:
![planification context](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/08eab9bb-6305-4076-8434-cce03fdbb389)

Shopping Context:
![Shopping context](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/3327d4cf-c7b1-4f0c-ae42-4c74da4fcfb4)

Finance Context:
![Finance context](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/a3cb977a-e23e-447e-9c29-7c85a3013a43)

Rates Context:
![Rates context](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/2bdd2692-2dd2-4d89-98fb-adf60e1e7e7c)

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

![Ayni-2023-09-20_20-58](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/1b9bc309-9286-4b29-9ef8-cbbc110e1223)

Link para visualizar el diagrama de base de datos: [Vertabelo](https://my.vertabelo.com/doc/lh2wueyLIyZXQviphxQgyZACCtfJVtKs)
