# Capítulo 5: Product Implementation, Validation & Deployment #

## _5.1. Software Configuration Management_ ##

En esta sección, se detalla la configuración de la tecnología a usar en el ciclo de vida de desarrollo del proyecto del curso.

### 5.1.1. Software Development Environment Configuration ###

En esta sección, se explica los entornos en donde se decidió llevar a cabo el ciclo de vida de desarrollo de los productos de software relacionados al proyecto del curso.

* **Project Management**

  - En el aspecto de gestión y desarrollo del ciclo de vida del proyecto se utilizó la aplicación DISCORD y GOOGLE MEET para las reuniones de grupo en las cuales se conversan sobre temas relacionados a avances y corrección de aspectos del proyecto. Además, para la documentación del proyecto, se utilizó el formato Mark Down en un repositorio de GitHub para el control de versiones del informe.

* **Requirements Management**

  - Para el manejo de los requisitos (historias de usuario, product backlog, sprint backlog) del producto, se utilizó TRELLO la cual es una herramienta ideal para gestionar proyectos. Además, usando esta herramienta, se puede organizar un product backlog, ya que permite estructurar tareas visualmente en un tablero. También puedes crear listas que representen etapas del flujo de trabajo, y en cada lista añadir tarjetas que describan las user stories o tareas individuales. Estas tarjetas permiten detallar información clave, como prioridades, etiquetas de color, descripciones y checklists, facilitando así el seguimiento y la colaboración del equipo.

* **Product UX/UI Design**

  - Para el desarrollo de plantillas de los user persona, de los Impact Maps y los User Journey Maps se utilizó la aplicación UXPRESSIA la cual es una plataforma especializada en la creación de mapas de experiencia del usuario ofreciendo una interfaz enfocada exclusivamente en UX que facilita la estructuración clara y profesional de estos elementos. Destaca por sus plantillas personalizables, la posibilidad de añadir datos reales, imágenes y métricas, y por permitir la colaboración en tiempo real.

  - Para la creación del Lean UX Canvas se utilizó la aplicación de diseño CANVA. Esta aplicación es una herramienta versátil para crear diversos diseños. Canva facilita la colaboración del equipo y la exportación de los proyectos en archivo PNG o PDF, manteniendo el proceso creativo ordenado y atractivo. Para los Journey Mapping, Empathy Mapping, entre otros mapas,  se decidió utilizar Miro. Esta aplicación permite una colaboración en tiempo real entre equipos, ofrece una interfaz visual e intuitiva, y cuenta con plantillas prediseñadas que agilizan el proceso sin perder calidad metodológica.

  - Finalmente, para el desarrollo de interfaces de usuario (wireframes, mockups y prototipos de aplicación) se decidió utilizar FIGMA. Esta es una herramienta que facilita el diseño de interfaces, permitiéndonos trabajar con colores, imágenes, formas, y otros elementos visuales para crear nuestra aplicación. Nos ofrece la posibilidad de probar diversos modelos de dispositivos. Además, esta plataforma será clave en la creación de nuestro prototipo, ya que brinda una simulación interactiva que permite visualizar y experimentar el proyecto desde la perspectiva del usuario.

* **Software Development**

  - Para el desarrollo del producto de software correspondiente al Landing Page, se utilizarán dos aplicaciones, las cuales son GITHUB y JETBRAINS WEBSTORM. La primera ayuda al equipo a gestionar de manera correcta los avances colaborativos del proyecto. Por otro lado, JetBrains WebStorm ayudará a trabajar el proyecto con lenguajes como HTML5, CSS y JavaScript para el desarrollo del landing page.

  - Para el desarrollo de la aplicación Front-End, se utilizaron las aplicaciones de GITHUB y JETBRAINS WEBSTORM. Por un lado, Github nos ayuda a gestionar la documentacion correcta de los avances que realizan los miembros del equipo. Mientras que, por otro lado, JetBrains WebStorm es el programa en el que se codifica nuestra aplicacion Frontend usando los lenguajes HTML5, CSS y JavaScript, asi mismo se utilizo el framework de Angular para los componentes de la aplicación.

  - Para el desarrollo de los Web Services o la Aplicación Back-End, se utilizaron las aplicaciones de GITHUB Y JETBRAINS INTELLIJ IDEA. Por un lado, Github nos ayuda a gestionar la documentacion correcta de los avances que realizan los miembros del equipo y a llever un control de los avances que realiza cada miembro del equipo. Mientras que JetBrains IntelliJ Idea es el programa en el que se codifica nuestra aplicacion BackEnd usando el lenguaje de Java, asi mismo se utilizo el framework de SpringBoot para el desarrollo de los endpoints correspondientes al producto de software.

  - Finalmente, para la creación del esquema de base de datos, se usó MYSQL y el cliente MYSQL WORKBENCH. Gracias a algunas extensiones para ASP.NET Core, se puede generar un esquema relacional en MySql respecto a lo que se implementa en la aplicación Backend. Además, con MySql Workbench, se pueden comprobar las creaciones de datos y los datos almacenados en ella.
  
* **Software Testing**

  - Las pruebas de la Landing Page se realizarán mediante uso del navegador web GOOGLE para verificar que el diseño del mismo cumple con aspectos como el diseño responsivo en cualquier dispositivo desde el que se acceda al landing page del proyecto. Además, para visualizar que se han implementado correctamente elementos visuales que deben aparecer en las distintas secciones de la página.

  -  Las pruebas de la aplicación Front-End se realizaron utilizando una fake API que usa la dependencia JSON SERVER que simula el consumo de datos traidos de una base de datos temporal para validar el correcto funcionamiento de las interfaces y las interacciones con los datos.

  - Finalmente, las pruebas de la Aplicación Back-End se realizaron mediante SWAGGER UI y POSTMAN, herramientas que facilitaron la ejecución de consultas y solicitudes HTTP de manera visual e intuitiva, permitiendo verificar el correcto funcionamiento de los endpoints expuestos por la API. Gracias a estas herramientas, fue posible simular distintos escenarios de uso, validar las respuestas del servidor, analizar los códigos de estado HTTP y garantizar que la lógica del backend respondiera adecuadamente ante entradas válidas y erróneas.

* **Software Deployment**

  - Para los despliegues de la Landing Page se uso el servicio web de GITHUB PAGES, este servicio se especializa en el despliegue de sitios web staticos directamente desde un repositorio creado en GitHub.

  - Para el primer y segundo despliegue de la aplicación Front-End se usaron las aplicaciones BEECEPTOR y FIREBASE. Por un lado, Beeceptor es una herramienta en línea (basada en la web) que nos permite crear endpoints HTTP falsos (mock) para probar APIs, se uso ver qué datos está enviando nuestra aplicación. Por otro lado, Firebase es una plataforma desarrollada por Google que permite crear aplicaciones web y móviles más rápido, sin tener que construir un backend completo desde cero, ofrece servicios listos para usar que se pueden usar para conectar facilmente nuestro Frontend.

  - Para el último despliegue de la aplicación Front-End se usó únicamente FIREBASE ya que desde la propia aplicación, se integró la conexión con el último despliegue de la aplicación Back-End.

  - Para los despliegues de la Aplicación Back-End se utilizó RENDER. Render es una plataforma en la nube que permite desplegar aplicaciones web, APIs, bases de datos, sitios estáticos y más de forma sencilla y automatizada, sin necesidad de gestionar servidores manualmente. Permite que una aplicación backend esté disponible públicamente en internet, funcionando 24/7 con un dominio propio o asignado automáticamente.

  - Finalmente, para los despliegues de la Base de Datos se utilizó FREESQLDATABASE. Esta aplicación web es gratuita y nos ayuda a desplegar fácilmente la base de datos con la que va a interactuar la aplicación Backend para almacenar, obtener y crear datos.

### 5.1.2. Source Code Management ###

En esta sección, se describen los medios y esquemas de organización para gestionar de manera efectiva los archivos de proyecto relacionados a Landing Page, Web Services y Frontend Web Applications. En el caso de los repositorios, se usará GitHub para almacenar los archivos. Además, se implementará GitFlow. Esta función de GitHub ayudará al equipo, gracias a las ramas de características de lanzamiento, a poder trabajar paralelamente en el proyecto y a tomar el control de versiones de avance del proyecto.

#### **5.1.2.1. Repositorios**

A continuación, se adjuntan los enlaces para acceder a los repositorios donde se almacenarán los archivos de proyecto relacionados al Landing Page, Frontend Web Applications y Web Services.

* **Landing Page: [https://github.com/OpenDoorss/StockSip-LandingPage.git](https://github.com/OpenDoorss/StockSip-LandingPage.git)**
* **Frontend Web Applications: [https://github.com/OpenDoorss/stocksip-front-end-application.git](https://github.com/OpenDoorss/stocksip-front-end-application.git)**
* **Web Services: [https://github.com/OpenDoorss/stocksip-back-end-application.git](https://github.com/OpenDoorss/stocksip-back-end-application.git)**

#### **5.1.2.2. GitFlow**

Como se mencionó previamente, GitFlow ayudará al equipo de desarrollo a gestionar de manera efectiva el proyecto en su ciclo de vida. En general, GitHub ayudará a facilitar el desarrollo del proyecto para el equipo ya que es más sencillo desarrollar trabajos en equipo en los repositorios de los archivos de proyecto.

##### **5.1.2.2.1. Main Branches**

* **Main Branch**   
  Llamada también rama principal del proyecto, esta es la rama predeterminada del proyecto creado en el repositorio. Esta rama representa el historial del proyecto lo que ayuda a llevar el control de versiones del mismo.

    
* **Develop Branch**  
  Llamada también rama de desarrollo del proyecto. Esta rama es una bifurcación de código original del proyecto para definir nuevos rumbos respecto del proyecto original que servirá para evaluar variaciones del proyecto para su evolución. Además, ayudan a incorporar nuevas funciones al proyecto.

##### **5.1.2.2.2. Supporting Branches**

* **Feature Branch**  
  También llamada rama de característica del proyecto, es una rama de desarrollo que ayuda a incorporar nuevas funciones al proyecto en desarrollo. Además, permite el aislamiento de la función agregada y que varios colaboradores puedan trabajar simultáneamente en dicha funcionalidad.

* **Release Branch**  
  También llamada rama de lanzamiento del proyecto, es una versión de código del proyecto que se usa para empezar un nuevo ciclo de lanzamiento del producto de software. Además, en esta rama se pueden realizar correcciones de errores de la versión pasada del proyecto. Finalmente, una vez terminada con esta rama, se suma a la rama principal del proyecto y se le asigna un nuevo número de versión de proyecto.

* **Hotfix Branch**  
  También llamada rama de corrección del proyecto, es una rama que permite dar mantenimiento al código del proyecto. Se utiliza principalmente para arreglar errores en alguna sección del producto de software de manera rápida.

#### **5.1.2.3. Release Versioning Conventions**

Para la nomenclatura de los lanzamientos del Landing Page, se utilizará Semantic Versioning que consta de tres partes para describir cambios mayores, cambios menores y parches para corrección de bugs, según la siguiente estructura:

* Número principal: Incrementa cuando se realiza un cambio mayor y significativo al proyecto.  
* Número secundario: Incrementa cuando se realiza un cambio menor al proyecto como arreglo de errores o agregación de características.  
* Número terciario: Incrementa cuando se realiza un parche al proyecto como una corrección de bugs o errores visuales.

#### **5.1.2.3. Commits Conventions**

Para los textos de mensajes en los *‘commits’* del proyecto en Git, se utilizará Conventional Commits. Estos son mensajes de confirmación que son fáciles de entender por los colaboradores del proyecto. Finalmente, estos mensajes siguen la siguiente estructura:  

<!-- Commits-->
<p align="center">
  <img src="https://i.imgur.com/vfirypa.png" alt="Commits">


La sección *‘type’* indica el tipo de mensaje de confirmación que se usará. A continuación, la sección *‘description’* indica la descripción que se le agrega al mensaje de confirmación, por ejemplo, una característica agregada. Además, la sección *‘body’* incluye una descripción más detallada del cambio aplicado al proyecto.  
Luego, se tienen distintos tipos de mensajes de confirmación. Por ejemplo, se tiene el mensaje tipo *‘fix’* que incluye una corrección al proyecto. Utilizar este tipo conlleva aumentar el número terciario de la versión del proyecto (por ejemplo, de 1.0.0. a 1.0.1.). Después, utilizar el mensaje de tipo *‘feat’* conlleva agregar una nueva función a la aplicación, por lo tanto, se debe aumentar el número secundario de la versión (por ejemplo, de 1.0.0. a 1.1.0.). Finalmente, si se agrega una sección de tipo ‘BREAKING CHANGE’ indicaría que las versiones anteriores del proyecto dejarán de ser compatibles entre sí, lo que conlleva un cambio significativo y el aumento del número principal de la versión (por ejemplo, de 1.0.0. a 2.0.0.).

### 5.1.3. Source Code Style Guide & Conventions ###

En esta sección, se definen las referencias que se usaron para adoptar estrategias de nomenclatura de elementos de programación en los lenguajes que se usarán para la solución (HTML, CSS, JavaScript, TypeScript y Java). En general, la nomenclatura de los archivos y secciones en la programación se hará en inglés.

* **Nomenclatura en HTML:**  
  Para la codificación del proyecto en HTML, se utilizará el artículo *“HTML Style Guide and Coding Conventions”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en HTML como si se debe escribir en minúsculas o mayúsculas las secciones del cuerpo del documento. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://www.w3schools.com/html/html5\_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en HTML para el landing page de StockSip a desarrollar.

* **Nomenclatura en CSS:**  
  Para la codificación del proyecto en Cascading Style Sheets (CSS), se utilizará el artículo *“Google HTML/CSS Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en CSS como capitalización en código de colores, referencias a imágenes, etc. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en CSS para el estilo de colores que se quiere agregar al landing page de StockSip a desarrollar.

* **Nomenclatura en TypeScript:**  
  Para la codificación del proyecto en TypeScript, se utilizará el artículo *“Google TypeScript Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que establece las convenciones de codificación que Google sigue para escribir código en TypeScript. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/tsguide.html](https://google.github.io/styleguide/tsguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.  
    
* **Nomenclatura en Angular:**  
  Para la codificación del proyecto en Angular, se utilizará el artículo *“Angular coding style guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Angular recomienda para escribir código en sus aplicaciones. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Angular en su version numero 20. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://angular.dev/style-guide](https://angular.dev/style-guide)  
  Finalmente, se aplicará el contenido del artículo para el Frontend Applications de StockSip.  
    
* **Nomenclatura en Java:**  
  Para la codificación del proyecto en Java, se utilizará el artículo *“Google Java Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Google sigue para escribir código en Java. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Google. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.

* **Nomenclatura en Spring Boot:**  
  Para la codificación del proyecto en Spring Boot, se utilizará el artículo *“Spring Boot Features”.* Este artículo contiene información útil y necesaria para comprender las características fundamentales que ofrece Spring Boot para el desarrollo de aplicaciones en el ecosistema Spring. Su objetivo principal es presentar de forma estructurada los componentes clave del framework, promoviendo un desarrollo eficiente, coherente y escalable, especialmente para proyectos que buscan aprovechar la configuración automática, la modularidad y las mejores prácticas del desarrollo moderno con Java. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://docs.spring.io/spring-boot/reference/features/index.html](https://docs.spring.io/spring-boot/reference/features/index.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.

* **Nomenclatura en ASP.NET:**  
  Para la codificación del proyecto en ASP.NET, se utilizará el artículo *“Microsoft ASP.NET Core Coding Guidelines”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura y el estilo de los diversos aspectos que conforman un proyecto desarrollado con ASP.NET Core. Se trata de la guía de ingeniería oficial del equipo de ASP.NET Core, en la cual se detallan las convenciones recomendadas para escribir código claro, consistente y fácil de mantener. Esta guía organiza sus recomendaciones en distintos apartados que abarcan desde el formato del código, el uso de tipos y palabras clave, la compatibilidad multiplataforma, hasta el control de cambios en versiones del framework. Cada sección tiene como propósito establecer prácticas que favorezcan la legibilidad, el rendimiento, y la calidad del desarrollo colaborativo a gran escala. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#codingguidelines](https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#codingguidelines)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip

* **Nomenclatura para RESTful API:**

  Para la nomenclatura de endpoints a implementar en la aplicación Back-End, se usó el artículo *"REST API URI Naming Conventions and Best Practices".* Este mismo contiene información sobre consejos y buenas prácticas al momento de nombrar correctamente a los endpoints en una aplicación back-end que use el esquema REST. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://restfulapi.net/resource-naming/](https://restfulapi.net/resource-naming/).

* **Nomenclatura en MySQL:**

  Para la nomenclatura de objetos en una base de datos relacional usando MySQL, se usó el artículo *"MYSQL Naming Conventions"* como base para la correcta nomenclatura de tablas y columnas. A continuación, se adjunta el enlace para acceder al artículo de referencia: [(https://medium.com/@centizennationwide/mysql-naming-conventions-e3a6f6219efe)](https://medium.com/@centizennationwide/mysql-naming-conventions-e3a6f6219efe).

### 5.1.4. Software Deployment Configuration ###

En esta sección, se especifica la configuración para realizar el despliegue de la solución en el repositorio. Para realizar esto, se usó GitHub Pages para lanzar el landing page, Web Services y Frontend Web Applications. A continuación, se describen los pasos necesarios para desplegar el Landing Page del proyecto, empezando por la creación del repositorio hasta el lanzamiento del proyecto.

* **Paso 1: Creación del repositorio**  
  Como primer paso, se debe crear el repositorio en GitHub que será el lugar donde se aloja todo lo relacionado al Landing Page.

<p align="center">
  <img src="https://i.imgur.com/lW7iEKk.png">

* **Paso 2: Carga de archivos necesarios**   
  Como segundo paso, se importan todos los archivos necesarios para el desarrollo del landing page como imágenes, archivos HTML, CSS y JavaScript.

<p align="center">
  <img src="https://i.imgur.com/RNjUuSV.png">

* **Paso 3: Preparar el lanzamiento**  
  Como tercer paso, se juntan todas las características del proyecto en una sola para verificar el correcto funcionamiento de cada una. Luego, se envía todo a la rama principal donde se encuentra, por defecto, el proyecto.

<p align="center">
  <img src="https://i.imgur.com/KtKEa2v.png">

* **Paso 4: Lanzar el Landing Page**  
  Como cuarto paso, cuando todo se encuentre en la rama principal, se accede a la sección Configuración del repositorio, luego, se selecciona la opción “GitHub Pages” y se seleccionará la rama principal que es la que se desea desplegar.

<p align="center">
  <img src="https://i.imgur.com/4xT68yG.png">
  
* **Paso 5: Acceder al Landing Page**  
  Como paso final, el entorno otorgará un enlace para poder acceder al proyecto desplegado.

<p align="center">
  <img src="https://i.imgur.com/aeqpcKT.png">

A continuación, se describen los pasos necesarios para desplegar el Frontend del proyecto, empezando por la creación del repositorio hasta el lanzamiento del proyecto.

* **Paso 1: Creación del repositorio**  
  Como primer paso, se debe crear el repositorio en GitHub que será el lugar donde se aloja todo lo relacionado al Frontend.

<p align="center">
  <img src="https://i.imgur.com/X6DvQRn.png">

* **Paso 2: Carga de archivos y carpetas necesarios**   
  Como segundo paso, se importan todos los archivos y carpetas necesarios para el desarrollo del Frontend.

<p align="center">
  <img src="https://i.imgur.com/XUIzxlB.png">

* **Paso 3: Creacion del proyecto en WebStorm**  
  Como tercer paso, se creara el proyecto en WebStorm, importamos nuestros features e instalamos las dependencias necesarias. 

<p align="center">
  <img src="https://i.imgur.com/pDPb0M4.png">

* **Paso 4: Comando ng build**  
  Como cuarto paso, ingresaremos el comando ng build en la consola de nuestro proyecto, este comando creara una carpeta llamada Dist que contiene todo nuestro proyecto traducido a html, css y javascript.

<p align="center">
  <img src="https://i.imgur.com/WUsvhqP.png">
<p align="center">
  <img src="https://i.imgur.com/SuN3YEo.png">
  
* **Paso 5: Probar el funcionamiento del build**  
  Ingresamos a la pagina web Beeceptor e iniciamos sesion con nuestra cuenta, crearemos un nuevo mock server y copiaremos el enlace que nos proporciona. Volvemos al WebStorm, nos dirigimos a la carpeta environments y colocamos el enlace en la parte de apiUrl en los dos archivos

<p align="center">
  <img src="https://i.imgur.com/3W2K0Qm.png">
  
* **Paso 6: Probar el funcionamiento del build con HTTP**  
  Ingresamos a la pagina web npmjs y buscamos HTTP-server, es un servidor para probar que nuestro build funcione en un entorno de desarrollo, copiamos el comando npm i http-server --save-dev. Luego ingresamos el comando http-server ruta/nuestro/dist/browser y elegimos cualquier de los links presentes. Se podra a acceder a nuestra aplicacion.

<p align="center">
  <img src="https://i.imgur.com/OMaUvwE.png"> 
<p align="center">
  <img src="https://i.imgur.com/IRjDrXI.png"> 

* **Paso 7: Probar despliegue con Firebase**  
  Ingresamos a la pagina web Firebase e ingremos con nuestra cuenta de google y vamos a la consola, creamos un nuevo proyecto con el nombre de nuestra aplicacion,
nos ubicamos en el apartado de hosting

<p align="center">
  <img src="https://i.imgur.com/LF7yomG.png">
<p align="center">
  <img src="https://i.imgur.com/IMS9O5Y.png">
<p align="center">
  <img src="https://i.imgur.com/TMeYnnF.png">
  
* **Paso 8: Configurar el despliegue**  
  Regresamos a nuestro WebStorm y en la consola ingresamos el comando firebase login y decimos NO, nos pedira que ingremos con nuestra cuenta de google con la que creamos el proyecto e inicializamos el firebase con el comando firebase init, con las flechitas del teclado nos desplazamos a la opcion Hosting y presionamos la barra espaciadora para seleccionarlo y damos enter. Elejimos 'Use an existing proyect' y elegimos nuestro proyecto, colocamos ruta/nuestro/dist/browser y decimos YES NO NO

<p align="center">
  <img src="https://i.imgur.com/kyQfbBW.png"> 
<p align="center">
  <img src="https://i.imgur.com/K6nvtaP.png">
<p align="center">
  <img src="https://i.imgur.com/lJ5Emix.png"> 
<p align="center">
  <img src="https://i.imgur.com/9phLLJm.png">

* **Paso 9: Desplegar nuestro proyecto**  
  Nos dirigimos al archivo firebase.json y agregamos una seccion "site": "nombre de nuestro site" e ingresamos el comando firebase deploy, pero antes de eso ingresamos el comando ng build para actualizar, ingresamos con el enlace que nos proporciona y nuestro proyecto ya estaria desplegado

<p align="center">
  <img src="https://i.imgur.com/W6r5Iwp.png"> 
<p align="center">
  <img src="https://i.imgur.com/d5iOzXH.png"> 
<p align="center">
  <img src="https://i.imgur.com/7CvKjfw.png"> 

## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

### 5.2.1.1. Sprint Planning 1 ###

A continuación, se detalla, en la tabla siguiente, información sobre el planeamiento del primer sprint. En general, el objetivo de este sprint se centra en el desarrollo y despliegue de la primera versión del sitio web estático de StockSip.

| Sprint #                                     | Sprint 1                                                                                                                                                                                                                                                                                                                          |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                                                                                                                                                                                                                                                                                                |
| Date                                         | 2025/04/20                                                                                                                                                                                                                                                                                                                        |
| Time                                         | 03:30 PM                                                                                                                                                                                                                                                                                                                          |
| Location                                     | Reunión mediante llamada virtual en Discord                                                                                                                                                                                                                                                                                       |
| Prepared By                                  | Huamani Cruz, Camila Victoria                                                                                                                                                                                                                                                                                                     |
| Attendees                                    | Huamani Cruz, Camila Victoria / Juarez Leon, Nicolas Emilio Walter / Gonzales Castillo, Angel Martin / Diaz Quispe, Matias Sebastian / Coronel Espinoza, Farid Sebastian                                                                                                                                                          |
| <b> Sprint Goal & User Stories </b>          | --                                                                                                                                                                                                                                                                                                                                |
| Sprint 1 Goal                                | <b> Our focus </b> is on develop and deploy the first version of the landing page <br> <b> We believe it delivers </b> a first view of what our product offers to our target segments <br> <b> This will be confirmed when </b> the target segments are visiting the site and can see and know the benefits on using our product. |
| Sprint 1 Velocity                            | 16                                                                                                                                                                                                                                                                                                                                |
| Sum of Story Points                          | 16                                                                                                                                                                                                                                                                                                                                |

### 5.2.1.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este primer sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada sección y el estilo que debe contener este mismo: inicio, funcionamiento de la aplicación, beneficios para cada segmento, testimonios, exploración de la aplicación, planes y contacto.

| Team Member                        | GitHub Username | Sección Inicio | Funcionamiento de la aplicación | Beneficios | Testimonios | Planes | Contacto | 
|------------------------------------|-----------------|----------------|---------------------------------|------------|-------------|--------|----------|
| Huamani Cruz, Camila Victoria      | victiila06      | L              | C                               |            |             |        | L        |
| Gonzales Castillo, Angel Martin    | XdiabloX426     |                | L                               |            |             |        |          |
| Coronel Espinoza, Farid Sebastian  | Far14z          |                |                                 | L          |             |        |          |
| Juarez Leon, Nicolas Emilio Walter | JuarezLn10      |                |                                 |            | L           |        |          |
| Diaz Quispe, Matias Sebastian      | equinox-1092    |                |                                 |            |             | L      |          |

### 5.2.1.3. Sprint Backlog 1 ###

Como se mencionó previamente en el planeamiento del sprint número 1, el objetivo del mismo es el desarrollar y desplegar una primera versión del landing page del producto. Esto conlleva implementar las diversas secciones que presenta un landing page que puedan ayudar a los visitantes del sitio a conocer mejor el producto en desarrollo.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 
[https://trello.com/invite/b/68254069b45285c273087923/ATTI2507d3d76e72207b9b855c678811f82d3CF68D96/stocksip-sprint-backlog-1](https://trello.com/invite/b/68254069b45285c273087923/ATTI2507d3d76e72207b9b855c678811f82d3CF68D96/stocksip-sprint-backlog-1)

<p align="center">
  <img src="../img/Chapter V/sprint_backlog.png" 
  alt="sprint_backlog_1"/>

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este primer sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 1     | Sprint Backlog 1                                              |     |                                         |                                                                                                            |                    |                |            |
|--------------|---------------------------------------------------------------|-----|-----------------------------------------|------------------------------------------------------------------------------------------------------------|--------------------|----------------|------------|
| User Stories |                                                               | Work Item/Task                                |                                                                                                            |                    |                |            |
| Id           | Title                                                         | Id  | Title                                   | Description                                                                                                | Estimation (Hours) | Assigned to    | Status     |
| US001        | Ver propuesta de valor clara                                  | 001 | Diseñar sección inicio                  | Diseñar el encabezado con logo, menú de navegación y sección principal.                                    | 0.5                | Camila Huamani | Done       |
|              |                                                               | 002 | Crear estructura principal del Landing Page  | Crear la estructura principal de la página en HTML y los estilos iniciales en CSS.                         | 0.5                | Camila Huamani | Done       |
|              |                                                               | 003 | Diseñar sección contacto                | Diseñar el pie de página con información de contacto y enlaces a otras secciones                           | 0.5                | Camila Huamani | Done       |
|              |                                                               | 004 | Describir visión y misión del startup   | Agregar espacios que detallen la misión y visión de la empresa.                                            | 0.5                | Camila Huamani | Done       |
|              |                                                               | 005 | Añadir estilos a la sección Inicio      | Estilizar las secciones de contacto e inicio para que sean visiblemente agradables y llamativas.           | 0.5                | Camila Huamani | Done       |
| US002        | Acceder a explicación detallada sobre el uso de la aplicación | 001 | Añadir sección sobre funcionamiento de la aplicación | Separar una sección de la estructura general para agregar el contenido de explicación de cómo funciona la aplicación. | 0.3     | Martin Gonzales | Done       |
|              |                                                               | 002 | Describir las funcionalidades           | Resumir cada funcionalidad que podrá utilizar cada segmento objetivo.                                      | 0.4                | Martin Gonzales | Done       |
|              |                                                               | 003 | Añadir imágenes referenciales sobre funcionalidades | Para cada funcionalidad detallada, agregar una imágen referencial.                                         | 0.5                | Martin Gonzales | Done       |
|              |                                                               | 004 | Ordenar las imagenes y las descripciones de funcionalidades | Ordenar y organizar cada funcionalidad descrita con su imagen.                                             | 0.4                | Martin Gonzales | Done       |
|              |                                                               | 005 | Añadir estilos a la sección de funcionamiento | Usando CSS, añadir estilos a esta sección para que sea visiblemente llamativa.                             | 0.6                | Martin Gonzales | Done      |
| US003        | Ver beneficios para licorerías	                               | 001 | Implementar sección beneficios para licorerías         | Diseñar la subsección de beneficios para dueños de licorerías agregando tarjetas con listas de beneficios. | 0.6                | Farid Coronel  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes a la sección beneficios para licorerías | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | Done      |
|              |                                                               | 003 | Añadir estilos a la sección de beneficios para licorerías | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | Done      |
| US004        | Ver beneficios para proveedores                               | 001 | Implementar sección beneficios para proveedores | Diseñar la subsección de beneficios para proveedores agregando tarjetas con listas de beneficios.          | 0.6                | Farid Coronel  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes a la sección beneficios para proveedores | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | Done      |
|              |                                                               | 003 | Añadir estilos a la sección de beneficios para proveedores | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | Done      |    
| US006        | Leer testimonios de clientes		                               | 001 | Añadir sección para testimonios         | Usando HTML, separar una sección para colocar todo el contenido de esta sección.                           | 0.5                | Nicolas Juarez | Done      |
|              |                                                               | 002 | Redactar testimonios de personas sobre la aplicación  | Redactar uno o varios testimonios para cada segmento objetivo que den su opinión sobre la aplicación.     | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 003 | Añadir tarjetas para cada testimonio    | Crear tarjetas en la estructura. Estas tarjetas contendrán el texto del testimonio.                        | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 004 | Añadir imágenes de personas para testimonios  | Agregar al lado del texto, una imagen referencial de la persona que está dando su testimonio.              | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 005 | Añadir estilos a la sección de testimonios | Agregar estilos a la sección usando CSS.                                                                   | 0.6                | Nicolas Juarez | Done      |
| US007        | Comparar planes gratis y premium	                             | 001 | Añadir sección de planes de suscripción | Diseñar la sección de planes con tarjetas que detallen las características de cada plan.                   | 0.5                | Matias Diaz | Done      |
|              |                                                               | 002 | Añadir información para segmentos de dueños de licorería y proveedores | Añadir texto diferenciando funcionalidades que incluye el plan para cada segmento objetivo.                | 0.6                | Matias Diaz | Done      |
|              |                                                               | 003 | Agregar comparación entre planes  | Añadir texto en las tarjetas que pueda ser utilizado para saber qué contiene el plan premium.              | 0.6                | Matias Diaz | Done      |
|              |                                                               | 004 | Añadir íconos relacionados a planes | Añadir íconos relacionados a lo que ofrece cada plan para cada segmento objetivo.                          | 0.6                | Matias Diaz | Done      |  
|              |                                                               | 005 | Añadir estilos a la sección planes | Estilizar la sección usando CSS.                                                                           | 0.5                | Matias Diaz | Done      |
| US008        | Conocer el precio y condiciones	                             | 001 | Añadir espacio para precios en las tarjetas de planes | En la sección de planes, agregar un recuadro que indique el precio para cada plan                          | 0.3                | Matias Diaz | Done      |
|              |                                                               | 002 | Añadir estilos a los precios | Estilizar los recuadros para precios usando CSS.                                                           | 0.3                | Matias Diaz | Done      |


### 5.2.1.4. Development Evidence for Sprint Review ###

En esta sección, se describen los principales avances de implementación realizados en este primer sprint. Se tiene como principal avance la implementación de cada sección del landing page en su primera versión.
Cada miembro del equipo avanzó progresivamente con cada sección del landing page. Finalmente, se añadieron estilos a las secciones usando CSS.

A continuación, se muestra una tabla que contiene la información sobre los _commits_ hechos que contienen partes de las funcionalidades que debemos implementar para completar el primer sprint.

| Repository                             | Branch                           | Commit Id | Commit Message                                                   | Commited On |
|----------------------------------------|----------------------------------|-----------|------------------------------------------------------------------|-------------|
| OpenDoors/StockSip-LandingPage         | master                           | f35ecc2   | chore: add home section                                          | 23/04/2025  |
| OpenDoors/StockSip-LandingPage         | master                           | df4416f   | feat(home): add home section and styles                          | 23/04/2025  |
| OpenDoors/StockSip-LandingPage         | master                           | fead8af   | chore: add images in home section                                | 23/04/2025  |
| OpenDoors/StockSip-LandingPage         | master                           | 85a32a0   | feat(footer): add footer section and style                       | 23/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/how-it-works             | b35b8a1   | chore: add image file.                                           | 24/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/how-it-works             | f730632   | feat(how-it-works): add how it works html                        | 24/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/how-it-works             | ece8b35   | feat(how-it-works): add how it works style css                   | 24/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/premium-plans            | c11a1db   | feat(section-premium-plans): add premium plans section and styles| 24/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/premium-plans            | a441e10   | feat(section-premium-plans): add premium plans section and styles| 24/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/benefits                 | 1985575   | feat(benefits): add benefits section                             | 25/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/benefits                 | 4ac613f   | feat(benefits): add css styles                                   | 25/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/how-it-works             | bc1c0ae   | fix(how-it-works): fix styles.                                   | 25/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/how-it-works             | 34bbff6   | fix(how-it-works): fix index html.                               | 25/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/testimonials             | 5274230   | feat(testimonials): add html structure for testimonials section. | 26/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/testimonials             | 2f4f14a   | feat(testimonials): add css styles for testimonials section.     | 26/04/2025  |
| OpenDoors/StockSip-LandingPage         | feature/testimonials             | d2ca22d   | docs: add testimonials images.                                   | 26/04/2025  |


### 5.2.1.5. Execution Evidence for Sprint Review ###
El objetivo de este sprint fue realizar, en collaboration con todo el equipo, la creación de la landing page. A continuación, se explica a detalle la evidencia del proceso de ejecución del sitio web estático.

Se implementó la sección de inicio que contiene información general sobre el producto y sobre la startup detrás del producto. Además, se incluye la visión general de la startup relacionada con el producto y los valores del equipo de desarrollo. Esto tiene un motivo de implementación y es el de llamar la atención de los visitantes del sitio web estático.
<p align="center">
  <img src="https://i.imgur.com/RM5QuV9.png"/>
</p>

También, se implementó una sección con un resumen de las funcionalidades que ofrece la aplicación web a los visitantes que decidan convertirse en usuarios de la aplicación.
<p align="center">
  <img src="https://i.imgur.com/l6XxVmI.png"/>
</p>

También, se implementó la sección que informa de los potenciales beneficios que ofrece el uso de la aplicación web a los visitantes interesados en usar el producto para el desarrollo de sus actividades.
<p align="center">
  <img src="https://i.imgur.com/Rdp57BN.png"/>
</p>

Además, se implementó una sección que contiene algunos testimonios de usuarios que usaron previamente la aplicación web y deciden dar una opinión respecto a su experiencia con el uso de la misma y como les ha ayudado en su situación.
<p align="center">
  <img src="https://i.imgur.com/FsUQGMa.png"/>
</p>

También, se implementó la sección con información acerca de los planes de suscripción para los visitantes. Esta sección incluye las restricciones que aplica cada plan a los usuarios que decidan crear una cuenta nueva.
<p align="center">
  <img src="https://i.imgur.com/wR7L77j.png"/>
</p>

### 5.2.1.6. Software Deployment Evidence for Sprint Review ###
La organization de nuestro code se realizó en un repositorio en GitHub y para el despliegue de la landing page se utilizó GitHub Pages. Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue del sitio web estático.

Se adjunta el enlace para acceder al sitio web estático desplegado: 

  


#### 5.2.1.7. Team Collaboration Insights during Sprint
En esta sección, se explica la colaboración aportada por cada miembro del equipo durante este sprint. Este proyecto se realizo mediante repositorio en GitHub con los siguientes integrantes participantes:
<p align="center">
  <img src="https://i.imgur.com/7mo7SJU.png"/>
</p>

Respecto del avance realizado por cada integrante en este sprint, se detallan las secciones realizadas por cada integrante:
A continuacion, se detallara el trabajo que realizo cada integrante del equipo:
- El integrante Martín Gonzales fue responsable de implementar la sección de como funciona la aplicacion en el Landing page.
- La integrante Camila Huamani implementó las seccion de inicio y contacto en el Landing page.
- El integrante Farid Coronel fue responsable de implementar la seccion beneficios en el landing page.
- El integrante Matias Diaz implementó la seccion de planes en el Landing page.
- El integrante Nicolas Juarez implementó la seccion de testiminos en el Landing page.

A continuación, se adjunta el gráfico con la cantidad de commits realizados por cada integrante del equipo durante este sprint para el desarrollo de la primera versión del sitio web estático:
<p align="center">
  <img src="https://i.imgur.com/xaO8mjo.png"/>
</p>

Finalmente, se muestra el gráfico los avances realizados por los integrantes en las ramas creadas para cada característica que se implementó al sitio web estático en este sprint:
<p align="center">
  <img src="https://i.imgur.com/vBY3Ne2.png"/>
</p>

### 5.2.2. Sprint 2 ###

### 5.2.2.1. Sprint Planning 2 ###

A continuación, se detalla, en la tabla siguiente, información sobre el planeamiento del segundo sprint. Además, para este sprint se definieron dos objetivos para cubrir los aspectos de sitio web estático y aplicación front-end. El primer objetivo se centra en desarrollar una mejora visual para el sitio web estático y añadir secciones para Call-To-Action para los visitantes del sitio web. Por otro lado, el segundo objetivo se centra en el desarrollo y despliegue de la primera versión de la aplicación front-end de StockSip.

| Sprint #                                     | Sprint 2                                               |
|----------------------------------------------|--------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                     |
| Date                                         | 2025/04/29                                             |
| Time                                         | 11:15 AM                                               |
| Location                                     | Reunión presencial en el aula VH107 del curso en la sede Villa |
| Prepared By                                  | Gonzales Castillo, Angel Martin                        |
| Attendees                                    | Huamani Cruz, Camila Victoria / Juarez Leon, Nicolas Emilio Walter / Gonzales Castillo, Angel Martin / Diaz Quispe, Matias Sebastian / Coronel Espinoza, Farid Sebastian |
| Sprint 1 Review Summary                      | In the previous sprint, the team completed a first view of the Landing Page implementing the basic sections and styles it will need like Benefits, Plans, Information about the Startup. |
| Sprint 1 Retrospective Summary               | The principal area the team has to improve is having more communication between the members to let each others know how is the progress is going for each member. Now, the plan for next sprint is to work more organized so each member know what to do.  |
| <b> Sprint Goal & User Stories </b>          | --                                                     |
| Sprint 2 Goals                               | <b> Our focus </b> is to offer a more detailed visualization and a greater adaptability of the current StockSip Landing Page and implement and deploy the first functional version of the Front-End application with key features like digital warehouses, the dashboard, registration of products, warnings, care guides and basic navigation between sections. <br> <b> We believe it delivers </b> different forms of accessing the Landing Page from different sizes of screens and languages to target segments and visitors and a complete first vision of functionalities the aplication offers to the target segments. <br> <b> This will be confirmed when </b> our target segments and visitors access the Landing through different devices and when our target segments register to the application and use the principal funcionalities like warehouses and care guides. | 
| Sprint 2 Velocity                            | 100                                                    |
| Sum of Story Points                          | 99                                                     |

### 5.2.2.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este segundo sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada las principales secciones que presenta el Front-End Web Application. Para esto, hemos definido las siguientes secciones: Inventarios y Zonas, Productos, Cuenta de Usuario, Reportes (Guía de cuidados y Reprote de pérdidas) y Alertas.

| Team Member                        | GitHub Username | Inventarios y Zonas | Productos | Cuenta de Usuario | Reportes (Guía de cuidados y Reprote de pérdidas) | Alertas | 
|------------------------------------|-----------------|---------------------|-----------|-------------------|---------------------------------------------------|---------|
| Huamani Cruz, Camila Victoria      | victiila06      |                     |           | L                 |                                                   |         |
| Gonzales Castillo, Angel Martin    | XdiabloX426     |                     |           |                   |                                                   | L       |
| Coronel Espinoza, Farid Sebastian  | Far14z          | L                   |           |                   |                                                   |         |
| Juarez Leon, Nicolas Emilio Walter | JuarezLn10      |                     | L         |                   |                                                   |         |
| Diaz Quispe, Matias Sebastian      | equinox-1092    |                     |           |                   | L                                                 |         |

### 5.2.2.3. Sprint Backlog 2 ###

Como se mencionó previamente en el planeamiento del sprint número 2, el objetivo del mismo es implementar secciones para que los usuarios puedan ser redirigidos a la aplicación web desde el sitio web estático e implementar secciones importantes como inventarios, almacenes, productos, alertas y guías en la aplicación front end del proyecto.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 
[https://trello.com/b/UjadbQbv/stocksip-sprint-backlog-2?filter=label:Desarrollo%20de%20Aplicaciones%20Open%20Source](https://trello.com/b/UjadbQbv/stocksip-sprint-backlog-2?filter=label:Desarrollo%20de%20Aplicaciones%20Open%20Source)

<p align="center">
  <img src="../img/Chapter V/sprint-2/sprint-backlog-2_1.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

  <p align="center">
  <img src="../img/Chapter V/sprint-2/sprint-backlog-2_2.png" 
  alt="Sprint Backlog 2 en desarrollo"/>

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este segundo sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 2     | Sprint Backlog 2                                              |             |                                                                                    |                                                                                                                                                                     |                    |                 |             |
|--------------|---------------------------------------------------------------|-------------|------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|-----------------|-------------|
| User Stories |                                                               | Work Item/Task                                                                                   |                                                                                                                                                                     |                    |                 |             |
| Id           | Title                                                         | Id          | Title                                                                              | Description                                                                                                                                                         | Estimation (Hours) | Assigned to     | Status      |
| US017        | Visualizar lista completa de productos en stock               | US017T001   | Crear una sección para visualizar los productos de un inventario                   | Crear un componente que muestre en una tabla los productos que posee un almacén.                                                                                    | 8                  | Nicolas Juarez  | Done        |
|              |                                                               | US017T002   | Crear una sección para el almacén seleccionado                                     | Crear una nueva sección que muestre toda la información relacionada al inventario como productos, capacidad, etc.                                                   | 8                  | Nicolas Juarez  | Done        |
|              |                                                               | US017T003   | Incluir un paginador para mostrar cierta cantidad de productos por página          | Implementar un paginador en la sección que ayude a organizar la información del inventario.                                                                         | 6                  | Nicolas Juarez  | Done        | 
|              |                                                               | US017T004   | Incluir un fake-api para simulación de datos de backend                            | Implementar un fake-api que ayude a probar los componentes usados que requieran mostrar, modificar o crear datos.                                                   | 5                  | Nicolas Juarez  | Done        |
| US016        | Registrar nuevo producto al inventario                        | US016T001   | Integrar un API para carga de imagenes de productos a la aplicación                | Utilizar Cloudinary para carga de URL de la imagen del producto subido.                                                                                             | 5                  | Nicolas Juarez  | In-Progress |
|              |                                                               | US016T002   | Crear un botón que permita cargar imagenes de productos al usuario                 | Programar un botón que abra el explorador de archivos del usuario para que pueda subir la foto de su producto.                                                      | 4                  | Nicolas Juarez  | Done        |
|              |                                                               | US016T003   | Crear un formulario base para edición y creación de cualquier entidad              | Añadir un componente que sirva de base para otros formularios que sirvan para crear y editar cualquier entidad.                                                     | 4                  | Nicolas Juarez  | Done        |
|              |                                                               | US016T004   | Crear un formulario para crear un producto en el inventario                        | Crear un componente usando como base el componente genérico de formularios para crear un formulario de creación de productos.                                       | 6                  | Nicolas Juarez  | Done        |
| US025        | Crear guía de conservación por tipo de licor                  | US025T001   | Crear un botón que permita crear una nueva guía de conservación                    | Programar un botón que muestre el formulario para crear una nueva guía de conservación.                                                                             | 4                  | Matias Diaz     | Done        |
|              |                                                               | US025T002   | Crear un formulario para crear una nueva guía de conservación                      | Crear un componente formulario usando como base el formulario base implementado.                                                                                    | 6                  | Matias Diaz     | Done        |
| US026        | Consultar guía de conservación desde el inventario            | US026T001   | Implementar un método para asignar una guía a un producto                          | Crear un método para asignar una guía de conservación a su respectivo producto.                                                                                     | 5                  | Matias Diaz     | Done        |
|              |                                                               | US026T002   | Implementar botón para visualizar guía de conservación de un producto              | Crear un botón en la sección de información de un producto en especifíco que muestre la guía de conservación de dicho producto.                                     | 7                  | Matias Diaz     | Done        |
| US024        | Visualizar productos en riesgo de vencimiento o merma         | US024T001   | Crear una sección que muestre los productos a cercanos a su vencimiento            | Crear un componente en el panel de control que muestre la lista de productos cuya fecha de vencimiento esté cerca a la fecha actual.                                | 5                  | Nicolas Juarez  | In-Progress |      
|              |                                                               | US024T002   | Crear un botón que redirija al usuario al producto cerca a su vencimiento          | Crear un botón que redirija al usuario a la información de producto del producto que ha seleccionado.                                                               | 6                  | Nicolas Juarez  | In-Progress | 
| US033        | Crear zonas de almacenamiento dentro del local                | US033T001   | Integrar un API para carga de imagenes referenciales a las zonas de inventario     | Integrar Cloudinary y utilizarlo para carga de URL de la imagen referencial de la zona de inventario creada.                                                        | 5                  | Farid Coronel   | Done        |
|              |                                                               | US033T002   | Crear un botón que permita cargar imagenes de zona de almacenamiento al usuario    | Programar un botón que abra el explorador de archivos del usuario para que pueda subir la foto referencial de su zona de inventario creada.                         | 4                  | Farid Coronel   | Done        |
|              |                                                               | US016T004   | Crear un formulario para crear un producto en el inventario                        | Crear un componente usando como base el componente genérico de formularios para crear un formulario de creación de zonas de inventario.                             | 6                  | Farid Coronel   | Done        |
| US027        | Generar reporte de pérdidas por tipo de baja                  | US027T001   | Crear un formulario para generar reporte de pérdidas                               | Crear un componente tomando de base el formulario genérico para crear un formulario para generar un reporte de pérdidas.                                            | 7                  | Matias Diaz     | Done        |                                                              
| US028        | Visualizar resumen económico de pérdidas                      | US028T001   | Crear un método que calcule el total de pérdidas                                   | Crear un método que calcule las pérdidas de los reportes generados para obtener un total.                                                                           | 4                  | Matias Diaz     | Done        |
|              |                                                               | US028T002   | Crear una sección que muestre el resumen económico de pérdidas                     | Crear un componente que muestre cada valor de pérdida y su total en el panel de control.                                                                            | 8                  | Matias Diaz     | Done        |
| US020        | Detallar el estado de salida de productos del inventario      | US020T001   | Crear una nueva sección para mostrar los movimientos de salida de productos        | Crear una nueva sección donde se mostrará todo lo relacionado a movimientos de salida de los productos.                                                             | 4                  | Nicolas Juarez  | Done        |
|              |                                                               | US020T002   | Crear una sección de historial de movimientos de salida de productos               | Crear una sección dentro de la principal donde se muestre la lista de movimientos de salida realizados por un mismo usuario.                                        | 6                  | Nicolas Juarez  | Done        |
|              |                                                               | US020T003   | Crear un formulario para registrar la salida de un producto                        | Crear un nuevo componente formulario sobre la salida de uno o varios productos del inventario del usuario.                                                          | 5                  | Nicolas Juarez  | Done        |
|              |                                                               | US020T004   | Implementar un método que actualice el stock del producto                          | Crear un método que actualice el stock de un producto que haya sido usado para realizar un movimiento de salida.                                                    | 7                  | Nicolas Juarez  | Done        |
| US036        | Visualizar el mapa general de zonas y productos               | US036T001   | Crear una nueva sección para mostrar los inventarios del usuario                   | Crear una nueva sección en donde únicamente se mostrará las zonas de inventario del usuario.                                                                        | 4                  | Farid Coronel   | Done        |
|              |                                                               | US036T002   | Crear una sección que enliste los inventarios del usuario                          | Crear un componente que enliste todas las zonas de inventario que el usuario posee.                                                                                 | 5                  | Farid Coronel   | Done        |
| US022        | Alertas por próximo vencimiento                               | US022T001   | Designar sección para el panel de alertas                                          | Crear una nueva sección solamente para la visualización de alertas.                                                                                                 | 4                  | Martin Gonzales | Done        |
|              |                                                               | US022T002   | Implementar un método que verifique las fechas de vencimiento de los productos     | Crear un método que verifique las fechas de vencimiento y emita una alerta si la fecha de vencimiento es cercana a la fecha actual.                                 | 8                  | Martin Gonzales | Done        |
|              |                                                               | US022T003   | Implementar método para que la alerta se muestre en el panel de alertas            | Crear un método que cree la alerta y la almacene en el panel de alertas en cualquier momento.                                                                       | 6                  | Martin Gonzales | Done        |
| US038        | Ver alertas destacadas en el panel de control                 | US038T001   | Implementar método para agregar alertas importantes al panel de control            | Crear un método que coloque las alertas importantes en una sección del panel de control del usuario.                                                                | 4                  | Martin Gonzales | Done        |
|              |                                                               | US038T002   | Crear una sección para las alertas destacadas en el panel de control               | Crear un componente dentro de la sección de panel de control que muestre la lista de alertas destacadas.                                                            | 5                  | Martin Gonzales | Done        |
| US043        | Consultar historial de guías emitidas                         | US043T001   | Crear una sección para Guías de conservación                                       | Crear una sección nueva para que se muestre todo lo relacionado a guías de conservación como creación, edición o historial.                                         | 4                  | Matias Diaz     | Done        |
|              |                                                               | US043T002   | Implementar una sección para el historial de guías                                 | Crear un componente que muestra la lista de guías de conservación creadas.                                                                                          | 6                  | Matias Diaz     | Done        |
| US034        | Asignar productos a una zona específica                       | US034T001   | Crear un método para mover un producto a otro inventario                           | Crear un método colocado en un botón que permita al usuario cambiar el inventario del producto seleccionado.                                                        | 6                  | Nicolas Juarez  | to-Fix      |                                               
|              |                                                               | US034T002   | Implementar un diálogo de confirmación sobre la transferencia de producto a otro inventario| Crear un diálogo para que el usuario confirme que desea transferir el producto seleccionado a otro inventario.                                              | 4                  | Nicolas Juarez  | To-Fix      |  
| US021        | Configurar alertas de reposición de productos                 | US021T001   | Implementar una sección para configurar alertas                                    | Crear una sección nueva dentro de la sección de Alertas para la configuración de las mismas.                                                                        | 4                  | Martin Gonzales | Done        |
|              |                                                               | US021T002   | Implementar un método para alterar el stock mínimo que pueda tener un producto     | Crear un método que permita al usuario alterar el número mínimo de productos que puede presentar en su inventario.                                                  | 6                  | Martin Gonzales | Done        |
| US037        | Visualizar resumen general en el panel de control             | US037T001   | Designar sección para el panel de datos                                            | Crear una nueva sección solamente para información del panel de datos o dashboard.                                                                                  | 4                  | Camila Huamani  | Done        |
|              |                                                               | US037T002   | Usar gráficos estadísticos para la visualización de información clave              | Implementar gráficos estadísticos que utilicen la información de productos e inventarios del usuario.                                                               | 8                  | Camila Huamani  | Done        |
|              |                                                               | US037T003   | Implementar las alertas en la sección del panel de datos                           | Implementar las alertas generadas sobre diversos aspectos en el panel de datos.                                                                                     | 7                  | Martin Gonzales | Done        |
| US044        | Cambiar estado de una guía a entregado                        | US044T001   | Implementar un método para asociar una guía de cuidado a un producto               | Desde la vista de proveedor, puede asociar una guía creada con un producto que al ser entregado al dueño de licorería, también podrá visualizar la guía.            | 8                  | Matias Diaz     | Done        |
|              |                                                               | US044T002   | Implementar acceso a la guía asociada al producto desde la información del mismo   | En el apartado de información del producto, dejar un espacio para acceder a la guía de cuidados del producto (si es que tiene una).                                 | 6                  | Nicolas Juarez  | Done        |
| US019        | Eliminar un producto del inventario                           | US019T001   | Implementar un botón que permita eliminar un producto registrado                   | Agregar un botón que permita al usuario eliminar un producto de su inventario.                                                                                      | 4                  | Nicolas Juarez  | Done        |
|              |                                                               | US019T002   | Implementar un diálogo de confirmación antes de eliminar un producto               | Programar un diálogo para que se muestre al presionar el botón de eliminar para que el usuario confirme su acción y no hayan equivocaciones.                        | 4.5                | Nicolas Juarez  | To-Fix      |
|              |                                                               | US019T003   | Implementar un botón para disminuir stock del producto                             | Programar un botón que ayude al usuario a disminuir el contador del stock del producto.                                                                             | 5                  | Nicolas Juarez  | To-Fix      |
| US018        | Editar un producto registrado                                 | US018T001   | Implementar un botón que permita editar un producto registrado                     | Agregar un botón que permita al usuario editar un producto existente en alguno de sus inventarios en la aplicación.                                                 | 4                  | Nicolas Juarez  | Done        |
|              |                                                               | US018T002   | Implementar un formulario para editar un producto registrado                       | Usar como base el formulario genérico para crear un componente formulario para la edición de información del producto seleccionado.                                 | 6                  | Nicolas Juarez  | Done        |
| US035        | Editar o eliminar una zona de almacenamiento                  | US035T001   | Implementar un botón que permita eliminar una zona de almacenamiento               | Agregar un botón que permita al usuario eliminar una zona de almacenamiento.                                                                                        | 4                  | Farid Coronel   | Done        |
|              |                                                               | US035T002   | Implementar un diálogo de confirmación antes de eliminar una zona de almacenamiento| Programar un diálogo para que se muestre al presionar el botón de eliminar para que el usuario confirme su acción y no hayan equivocaciones.                        | 4.5                | Farid Coronel   | Done        |
|              |                                                               | US035T003   | Implementar un botón que permita editar una zona de almacenamiento                 | Agregar un botón que permita al usuario editar una zona de almacenamiento existente en la aplicación.                                                               | 4.5                | Farid Coronel   | Done        |
|              |                                                               | US035T004   | Implementar un formulario para editar una zona de almacenamiento                   | Usar como base el formulario genérico para crear un componente formulario para la edición de información de la zona de almacenamiento seleccionada.                 | 6.5                | Farid Coronel   | Done        |
| US005        | Sección sobre la aplicación para el visitante                 | US005T001   | Agregar sección con imágenes de la aplicación                                      | En el Landing Page, se debe agregar una nueva sección que muestra imágenes de algunas pantallas principales de la aplicación.                                       | 4                  | Camila Huamani  | Done        |
|              |                                                               | US005T002   | Añadir imágenes a la sección sobre la aplicación                                   | En la sección sobre la aplicación del Landing Page, agregar imágenes de las principales secciones de la aplicación.                                                 | 4                  | Camila Huamani  | Done        |
|              |                                                               | US005T003   | Dar estilo a la sección sobre la aplicación                                        | Usar CSS para darle una mejor vista a la sección sobre la aplicación.                                                                                               | 4                  | Camila Huamani  | Done        |
|              |                                                               | US005T004   | Agregar un botón para cambiar de idiomas en el Landing Page                        | En el header del Landing Page, agregar un botón que sea programado para que cambie el idioma de la página.                                                          | 5.5                | Camila Huamani  | Done        |
| US045        | Editar datos personales del perfil                            | US045T001   | Crear una sección para editar información del usuario                              | Crear un componente dentro de la sección Perfil que permita al usuario editar información personal en la aplicación.                                                | 5                  | Camila Huamani  | Done        |
| US048        | Ver tipo de cuenta y plan actual                              | US048T001   | Crear un pequeño apartado para mostrar información de la cuenta del usuario        | Crear un pequeño componente dentro de la sección Perfil que muestra información sobre la cuenta de usuario como el tipo de cuenta.                                  | 4                  | Camila Huamani  | Done        |
| US046        | Subir y actualizar foto de perfil                             | US046T001   | Integrar un API para carga de imagenes de perfil a la aplicación                   | Utilizar Cloudinary para facilitar la carga de imágenes de perfil de los usuarios.                                                                                  | 4                  | Camila Huamani  | Done        |
|              |                                                               | US046T002   | Crear un pequeño apartado para mostrar la foto de perfil del usuario               | Crear un pequeño componente dentro de la sección Perfil que muestre la imagen del usuario.                                                                          | 4                  | Camila Huamani  | Done        |
|              |                                                               | US046T003   | Crear un botón que permita cargar archivos al usuario                              | Programar un botón que abra el explorador de archivos del usuario para que pueda subir su foto de perfil.                                                           | 4                  | Camila Huamani  | Done        |
| US050        | Ver fecha de vencimiento del Plan Premium                     | US050T001   | Crear un apartado para visualizar el tiempo restante del plan premium              | Crear un componente que contenta el tiempo restante que le queda a la suscripción del usuario registrado.                                                           | 4                  | Camila Huamani  | Done        | 
| US049        | Visualizar beneficios del Plan Premium                        | US049T001   | Crear un apartado para beneficios del plan premium                                 | Crear un componente que contenga información sobre beneficios que brinda el plan premium a los usuarios.                                                            | 4                  | Camila Huamani  | Done        | 
| US011        | Inicio de sesión de usuario registrado                        | US011T001   | Crear una sección para inicio de sesión de usuarios                                | Crear un componente para inicio de sesión de usuarios usando como requisitos el usuario y la contraseña.                                                            | 4                  | Camila Huamani  | Done        | 
|              |                                                               | US011T002   | Añadir estilos a la sección de inicio de sesión de usuario                         | Usar estilos con CSS para darle mejor vista a la pantalla de inicio de sesión.                                                                                      | 4                  | Camila Huamani  | Done        |
| US009        | Registro de usuario                                           | US009T001   | Crear una sección para registro de usuario                                         | Crear un componente para registro de usuarios usando espacios para completar como nombre, correo, contraseña y dirección.                                           | 4                  | Camila Huamani  | Done        |
|              |                                                               | US009T002   | Añadir estilos a la sección de registro de usuario                                 | Usar estilos con CSS para darle mejor vista a la pantalla de registro.                                                                                              | 4                  | Camila Huamani  | Done        |
|              |                                                               | US009T003   | Integrar un API para selección de dirección del usuario                            | Para el apartado de la dirección de usuario se debe usar un API que muestre un mapa con el que el usuario puede interactuar para marcar su ubicación                | 4.5                | Camila huamani  | Done        |
| US010        | Selección de rol durante registro                             | US010T001   | Crear un botón para seleccionar rol de usuario                                     | Usando Angular Material, usar el componente del botón "select" para que el usuario pueda elegir su rol al registrarse.                                              | 4                  | Camila Huamani  | Done        |

### 5.3.1.4. Development Evidence for Sprint Review ###

En esta sección, se describen los principales avances de implementación realizados en este segundo sprint.

A continuación, se muestra una tabla que contiene la información sobre los _commits_ hechos que contienen partes de las funcionalidades que debemos implementar para completar el primer sprint.

| Repository                          | Branch                      | Commit Id   | Commit Message                                                               | Commited On |
| ----------------------------------- | --------------------------- | ----------- | ---------------------------------------------------------------------------- | ----------- |
| Opendorss/StockSip-Front-End-App | develop                     | 758bdf2     | chore: add domain-driven file structure.                                     | 11/05/2025  |
| Opendorss/StockSip-Front-End-App | develop                     | 80feb21     | chore: add dependencies.                                                     | 11/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/inventory           | 2b62152     | feat(warehouse): add json-server data.                                       | 13/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/profile             | bac777a     | feat(profile): add profile page and components                               | 13/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/i18n                | c36fa88     | feat(i18n): add language switcher component.                                 | 13/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/inventory           | ce55380     | feat(warehouse): add inventory component.                                    | 13/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/inventory           | 66d0aa9     | feat(warehouse): add product component.                                      | 13/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/inventory           | f88e7bc     | feat(warehouse): add warehouse environment endpoints.                        | 13/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/profile             | bac777a     | feat(profile): add profile page and components                               | 14/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/authentication      | e19d7c2     | feat(authentication): add login page and components                          | 14/05/2025  |
| Opendorss/StockSip-Front-End-App | develop                     | 9bfc008     | feat(public): add side navigation bar routing                                | 14/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/dashboard           | 44a318c<br> | feat(analytics-and-reporting): update side navigation bar sections           | 16/05/2025  |
| Opendorss/StockSip-Front-End-App | feature/alerts              | a45f12e     | feat(alerts): add alerts component.                                          | 16/05/2025  |
| Opendorss/StockSip-LandingPage   | feature/i18n                | ddf0f82     | feat(i18n): Add data-i18n attributes to FAQ and statistics sections          | 15/05/2025  |
| Opendorss/StockSip-LandingPage   | develop                     | ac735e5     | chore: add page icon                                                         | 15/05/2025  |
| Opendorss/StockSip-LandingPage   | feature/faq                 | f63ab33c    | feat(faq): add faq section and styles.                                       | 15/05/2025  |
| Opendorss/StockSip-LandingPage   | feature/exploration-off-app | 78e7985     | feat(exploration-of-the-app): add exploration of the application section<br> | 15/05/2025  |

### 5.3.1.5. Execution Evidence for Sprint Review ###

En esta sección, se explica lo logrado en este sprint con pruebas de lo implementado.
Primero, los logros de este sprint incluyen la mejora de aspectos visuales y funcionales del sitio web estático, entre ellos, la implementación de secciones de Call-To-Action para los visitantes del sitio web, así como la implementación de secciones relacionadas a almacenes, productos, inventarios, alertas y guías de cuidado en la aplicación front-end de StockSip.

A continuación, se muestran las capturas de pantalla de las secciones implementadas en el Landing Page y la aplicación Front End. Estas imágenes reflejan el progreso realizado en el sprint y sirven como evidencia del trabajo completado.

Se adjunta el enlace al vídeo de ejecución de los productos para este sprint 2:
- Vídeo de ejecución: [https://youtu.be/ooFjKZ4uB3g](https://youtu.be/ooFjKZ4uB3g)

#### **Landing Page**

**Inicio Actualizado**
<p align="center">
  <img src="https://i.imgur.com/u1TwQ7f.png"/>
</p>

<br>

**Estadísticas**
<p align="center">
  <img src="https://i.imgur.com/8rUyLIU.png"/>
</p>
<br>

**Propuesta de valor**
<p align="center">
  <img src="https://i.imgur.com/Nuns8GD.png"/>
</p>
<br>

**Exploración de la Aplicación**
<p align="center">
  <img src="https://i.imgur.com/1FRWrt0.png"/>
</p>
<br>

**Preguntas frecuentes**
<p align="center">
  <img src="https://i.imgur.com/AIv2pf0.png"/>
</p>
<br>

#### **Front End Application**

**Inicio de sesión**
<p align="center">
  <img src="https://i.imgur.com/J5cbi5p.png"/>
</p>
<br>

**Perfil de usuario**

<p align="center">
  <img src="https://i.imgur.com/jYYG1aD.png"/>
</p>
<br>

**Reportes**

<p align="center">
  <img src="https://i.imgur.com/MKUCfFa.png"/>
</p>
<br>

**Guías de Conservación**
<p align="center">
  <img src="https://i.imgur.com/BVaQjr1.png"/>
</p>
<br>

**Alertas**
<p align="center">
  <img src="https://i.imgur.com/Hx43AXx.png"/>
</p>
<br>

### 5.3.1.6. Software Deployment Evidence for Sprint Review ###
Para asegurar un desarrollo estructurado y un despliegue eficiente, se organizaron los componentes del proyecto en dos partes principales: la Landing Page y el Frontend funcional. Cada uno fue alojado en su propio repositorio de GitHub, con procesos de desarrollo independientes y métodos de despliegue distintos. A continuación, se detalla el flujo de trabajo seguido en cada caso, junto con evidencia visual del resultado final.
Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue del sitio web estático.

#### Despliegue del Landing Page
Para el despliegue del sitio web estático, usamos GitHub Pages, una herramienta que permite alojar sitios web estáticos directamente desde un repositorio de GitHub. A continuación, se detalla el proceso seguido para el despliegue del sitio web estático:

- Link al landing page: [https://opendoorss.github.io/StockSip-LandingPage/](https://opendoorss.github.io/StockSip-LandingPage/)

* Partimos de la rama develop del repositorio del sitio web estático con todos los cambios realizados para el sprint actual.

* Luego, enviamos todos los cambios realizados en este segundo sprint desde la rama de desarrollo a una nueva rama de tipo release "release/landing-page-v2.0". Desde esa rama, se realizará un nuevo despliegue del sitio web estático.
<p align="center">
  <img src="https://i.imgur.com/keIfkaH.png"/>
</p>

* A continuación, nos dirigimos a la sección de Configuración del repositorio (Settings). Luego, accedemos a la opción de páginas (Pages) dentro del bloque de secciones de código y automatización (Code and automation).
<p align="center">
  <img src="https://i.imgur.com/0TJGzpU.png"/>
</p>

* Después, elegimos el tipo de origen para que despliegue desde una rama que escojamos. Luego, buscamos la rama de lanzamiento que hemos creado para realizar el despliegue de esta versión y guardamos la configuración.
<p align="center">
  <img src="https://i.imgur.com/E8TLSWz.png"/>
</p>

* A continuación, aparecerá el enlace público generado para poder acceder al sitio web estático desplegado.
<p align="center">
  <img src="https://i.imgur.com/iWq4Sm3.png"/>
</p>

* Finalmente, se accede el sitio web desplegado gracias a GitHub Pages y se adjunta la siguiente evidencia.
<p align="center">
  <img src="https://i.imgur.com/RM5QuV9.png"/>
</p>

#### Despliegue del Frontend
Para el despliegue de esta aplicación, se utilizó Firebase Hosting, una plataforma que permite alojar aplicaciones web de manera sencilla y eficiente.
Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue de la aplicación Frontend:

Link a la aplicación: [https://stocksip-od-app.web.app/](https://stocksip-od-app.web.app/)

* Partimos de la rama develop del repositorio de la aplicación frontend con todos los cambios realizados para el sprint actual.

* Luego, enviamos todos los cambios realizados en este segundo sprint desde la rama de desarrollo a una nueva rama de tipo release "release/front-end-app-v1.0". Desde esa rama, se realizará el primer despliegue de la aplicación front-end.

* A continuación, se instaló Firebase CLI, lo que permite gestionar y desplegar aplicaciones en Firebase. Luego, se inicializó el proyecto de Firebase en la carpeta del Frontend. Inmediatamente, ejecutamos en la consola el comando "firebase --version" para verificar que se haya instalado correctamente.
<p align="center">
  <img src="https://i.imgur.com/wrgcd4o.jpeg"/>
</p>

* Luego, ejecutamos el comando npm run build en la consola de nuestro proyecto, este comando creara una carpeta llamada Dist que contiene todo nuestro proyecto.

<p align="center">
  <img src="https://i.imgur.com/kuCErf7.png" alt="Execution of npm run build command">

<p align="center">
  <img src="https://i.imgur.com/qwP3yJb.png" alt="Creation of the dist folder">

* Luego, ingresamos a la página web Firebase e ingresamos con nuestra cuenta de Google y vamos a la consola, creamos un nuevo proyecto con el nombre de nuestra aplicación.

<p align="center">
  <img src="https://i.imgur.com/LF7yomG.png">

* Después, nos ubicamos en el apartado de hosting.
<p align="center">
  <img src="https://i.imgur.com/IMS9O5Y.png">

* Y se procede a agregar un nuevo sitio web, colocamos el nombre de nuestro sitio y damos clic en Agregar sitio.
<p align="center">
  <img src="https://i.imgur.com/7Fb9T6a.png">

* Regresamos a WebStorm y en la consola ingresamos el comando "firebase login" y decimos NO. Luego, nos solicitará que ingresemos con nuestra cuenta de Google con la que creamos el proyecto.
<p align="center">
  <img src="https://i.imgur.com/kyQfbBW.png"> 

* A continuación, se nos muestra una pantalla de inicio de sesión exitoso, lo que significa que hemos realizado correcto el anterior paso.
<p align="center">
  <img src="https://i.imgur.com/K6nvtaP.png">

* Inmediatamente, inicializamos Firebase con el comando "firebase init".
<p align="center">
  <img src="https://i.imgur.com/lJ5Emix.png"> 

* Con las teclas direccionales del teclado nos desplazamos a la opción Hosting y presionamos la barra espaciadora para seleccionarlo y damos enter. Elejimos 'Use an existing proyect' y elegimos nuestro proyecto, colocamos solo dist y respondemos con el siguiente orden a las preguntas que realiza FireBase: YES, NO, NO.
<p align="center">
  <img src="https://i.imgur.com/9phLLJm.png">

* Nos dirigimos al archivo firebase.json creado en nuestro proyecto y agregamos una sección "site": "nombre de nuestro site".

* A continuación, ingresamos el comando firebase deploy, pero antes de eso ingresamos el comando npm run build para construir una nueva versión del proyecto con todos los últimos cambios.
<p align="center">
  <img src="https://i.imgur.com/d5iOzXH.png"> 

* Finalmente, tras la ejecución del despliegue del Frontend a través de Firebase, se muestra la evidencia del despliegue:
<p align="center">
  <img src="https://i.imgur.com/J5cbi5p.png"/>
</p>

### 5.3.1.7. Team Collaboration Insights during Sprint ###

En esta sección se detalla cómo se llevaron a cabo las actividades de implementación durante el sprint, así como la participación de cada miembro del equipo. Para este sprint, el equipo se organizó en torno a los dos principales productos: Landing Page y Web Application (Frontend). Cada integrante asumió responsabilidades específicas en uno o más de estos componentes, trabajando mediante ramas individuales y siguiendo una estrategia de integración continua.

El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:

<p align="center">
  <img src="https://i.imgur.com/7mo7SJU.png"/>
</p>

A continuacion de detallara el trabajo que realizo cada integrante del equipo:
- El integrante Martín Gonzales fue responsable de implementar la sección de alertas en el Frontend, asegurando su correcto funcionamiento e integración con el resto de la aplicación.
- La integrante Camila Huamani implementó correcciones en el landing page, asi mismo agrego las secciones de exploracion de la aplicacion y preguntas frecuentes. En el Frontend se encargo de realizar la autenticacion, en ella creo los formularios de registro e inicio de sesion, tambien se encargo de implementar el perfil del usuario y el dashboard.
- El integrante Farid Coronel fue responsable de implementar la seccion de inventarios en el Frontend, se aseguro el correcto funcionamiento.
- El integrante Matias Diaz implementó la seccion de reportes en el Frontend, dentro de esta seccion agrego las guias de conservacion.
- El integrante Nicolas Juarez implementó la seccion de productos en el Frontend, asegurandose su correcto funcionamiento.

Commits de los integrantes en el Landing Page:
<p align="center">
  <img src="https://i.imgur.com/xaO8mjo.png"/>
</p>

Grafico de los push y merge realizados por el equipo en el landing page:
<p align="center">
  <img src="https://i.imgur.com/vBY3Ne2.png"/>
</p>

Commits de los integrantes en el Frontend:
<p align="center">
  <img src="https://i.imgur.com/pfifLqs.png"/>
</p>

Grafico de los push y merge realizados por el equipo en el Frontend: 

<p align="center">
  <img src="https://i.imgur.com/3Y3G0cw.png"/>
</p>


### 5.2.3. Sprint 3 ###

### 5.2.3.1. Sprint Planning 3 ###

A continuación, se detalla, en la tabla siguiente, información sobre el planeameanto del tercer sprint del proyecto. Además, para este sprint se definio un objetivo para cubrir los aspectos de sitio web estático, aplicación front-end y aplicación back-end. Una seccion del objetivo se centra en desarrollar una mejora visual para el sitio web estático y añadir secciones para Call-To-Action para los visitantes del sitio web. Por otro lado, el segundo objetivo se centra en el desarrollo y despliegue de la primera versión de la aplicación front-end de StockSip.

| Sprint #                                     | Sprint 3                                               |
|----------------------------------------------|--------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                     |
| Date                                         | 2025/05/27                                             |
| Time                                         | 11:15 AM                                               |
| Location                                     | Reunión presencial en el aula VH107 del curso en la sede Villa |
| Prepared By                                  | Gonzales Castillo, Angel Martin                        |
| Attendees                                    | Huamani Cruz, Camila Victoria / Juarez Leon, Nicolas Emilio Walter / Gonzales Castillo, Angel Martin / Diaz Quispe, Matias Sebastian / Coronel Espinoza, Farid Sebastian |
| Sprint 2 Review Summary                      | In the previous sprint, the team completed a first view of the Landing Page implementing the basic sections and styles it will need like Benefits, Plans, Information about the Startup. |
| Sprint 2 Retrospective Summary               | The principal area the team has to improve is having more communication between the members to let each others know how is the progress is going for each member. Now, the plan for next sprint is to work more organized so each member know what to do.  |
| <b> Sprint Goal & User Stories </b>          | --                                                     |
| Sprint 3 Goal                                | <b> Our focus </b> is to offer information, content and a video about the product and an introduction video about the team behind. <br> <b> We believe it delivers </b> different forms of accessing the Landing Page from different sizes of screens and languages to target segments and visitors. <br> <b> This will be confirmed when </b> our target segments and visitors access the Landing through different devices. <br><br> <b> Our focus </b> is on implement and deploy the first functional version of the Front-End application with key features like digital warehouses, the dashboard, registration of products, warnings, care guides and basic navigation between sections. <br> <b> We believe it delivers </b> a complete first vision of functionalities the aplication offers to the target segments. <br> <b> This will be confirmed when </b> our target segments register to  the application and use the principal funcionalities like warehouses and care guides. |
| Sprint 3 Velocity                            | 100                                                    |
| Sum of Story Points                          | 156                                                    |

### 5.2.3.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este tercer sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada las principales secciones que presenta el Front-End Web Application y en su contraparte para el Back-End Application. Para esto, hemos definido las siguientes secciones: Inventarios y Zonas, Productos, Cuenta de Usuario, Reportes, Ordenes de compra y Alertas.

| Team Member                        | GitHub Username | Alerts and Notifications | Analytics and Reporting | Authentication | Inventory Management  | Order Operation and Monitoring | Payment and Subscriptions | Profile Management |
|------------------------------------|-----------------|--------------------------|-------------------------|----------------|-----------------------|--------------------------------|---------------------------|--------------------|
| Huamani Cruz, Camila Victoria      | victiila06      |                          |                         | L              |                       |                                |                           | L                  |
| Gonzales Castillo, Angel Martin    | XdiabloX426     | L                        |                         |                |                       |                                |                           |                    |
| Coronel Espinoza, Farid Sebastian  | Far14z          |                          |                         |                | L                     |                                | L                         |                    |
| Juarez Leon, Nicolas Emilio Walter | JuarezLn10      |                          |                         |                |                       | L                              |                           |                    |
| Diaz Quispe, Matias Sebastian      | equinox-1092    |                          | L                       |                |                       |                                |                           |                    |

### 5.2.3.3. Sprint Backlog 3 ###

Como se mencionó previamente en el planeamiento del sprint número 3, el objetivo del mismo es concluir con el sitio web estatico integrando secciones que informen a los visitantes sobre los desarrolladores del producto y sobre el producto en si; implementar caracteristicas relacionadas con la realizacion de ordenes de compra en la aplicacion web e implementar endpoints en la aplicacion backend necesarios para la implementacion de caracteristicas fundamentales en la aplicacion web.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 
[https://trello.com/b/UjadbQbv/stocksip-sprint-backlog-2?filter=label:Desarrollo%20de%20Aplicaciones%20Open%20Source](https://trello.com/b/UjadbQbv/stocksip-sprint-backlog-2?filter=label:Desarrollo%20de%20Aplicaciones%20Open%20Source)

<p align="center">
  <img src="../img/Chapter V/sprint-3/sprint-backlog-3_1.png" 
  alt="Sprint goal y Stories del Sprint #3"/>

  <p align="center">
  <img src="../img/Chapter V/sprint-3/sprint-backlog-3_2.png" 
  alt="Sprint Backlog 3 en desarrollo"/>

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este segundo sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 3     | Sprint Backlog 3                                         |                |                                                                               |                                                                                                                                                              |                    |                 |        |
| ------------ | -------------------------------------------------------- | -------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ | --------------- | ------ |
| User Stories |                                                          | Work Item/Task |                                                                               |                                                                                                                                                              |                    |                 |        |
| Id           | Title                                                    | Id             | Title                                                                         | Description                                                                                                                                                  | Estimation (Hours) | Assigned to     | Status |
| US059        | Generar orden de compra                                  | US059T001      | Crear formulario de nueva orden de compra                                     | Diseño e implementación del formulario para crear manualmente una orden de compra.                                                                           | 4                  | Nicolas Juarez  | Done   |
|              |                                                          | US059T002      | Validar productos en orden                                                    | Validación para evitar el envío de órdenes vacías.                                                                                                           | 3                  | Nicolas Juarez  | Done   |
|              |                                                          | US059T003      | Implementar un snackbar para las notificaciones                               | Diseño e implementación de un componente snackbar para las notificaciones de órdenes creadas.                                                                | 3                  | Nicolas Juarez  | Done   |
|              |                                                          | US059T004      | Conexión con proveedor                                                        | Implementar la lógica para enviar la orden generada al proveedor correspondiente.                                                                            | 3                  | Nicolas Juarez  | Done   |
| US060        | Visualizar estado de la orden de compra                  | US060T001      | Crear vista de seguimiento de órdenes                                         | Vista para mostrar las órdenes realizadas por el usuario.                                                                                                    | 4                  | Nicolas Juarez  | Done   |
| US061        | Notificaciones sobre el estado de una orden              | US061T001      | Configurar notificación inicial                                               | Enviar notificación cuando se crea una orden de compra.                                                                                                      | 3                  | Nicolas Juarez  | Done   |
|              |                                                          | US061T003      | Crear notificaciones de orden aceptada o rechazada                            | Crear funcionalidad para enviar y mostrar notificación al dueño cuando la orden sea aceptada.                                                                | 4                  | Nicolas Juarez  | Done   |
| US062        | Coordinar fecha de entrega                               | US062T001      | Implementar función de propuesta de horario de entrega                        | Funcionalidad para que el proveedor proponga un horario al cliente.                                                                                          | 4                  | Nicolas Juarez  | Done   |
|              |                                                          | US062T002      | Crear función para aceptar/rechazar propuesta de horario                      | Implementar funcionalidad para que el cliente pueda aceptar o rechazar la propuesta del proveedor.                                                           | 3                  | Nicolas Juarez  | Done   |
|              |                                                          | US062T003      | Guardar fecha acordada en orden                                               | Persistencia de la fecha y hora confirmada entre ambas partes en la orden correspondiente.                                                                   | 3                  | Nicolas Juarez  | Done   |
| US056        | Creación de catálogo                                     | US056T001      | Crear formulario de catálogo                                                  | Diseño e implementación del formulario para crear un catálogo manualmente.                                                                                   | 4                  | Camila Huamani  | Done   |
|              |                                                          | US056T002      | Validar no publicación de catálogo vacío\|                                    | Implementar validación para impedir publicar catálogo sin productos.                                                                                         | 2                  | Camila Huamani  | Done   |
|              |                                                          | US056T003      | Implementar funcionalidad para publicar catálogo con productos                | Implementación de funcionalidad para publicar catálogo con productos visibles para clientes.                                                                 | 3                  | Camila Huamani  | Done   |
| US057        | Agregar producto al catálogo                             | US057T001      | Implementar funcionalidad para añadir producto con información completa       | Crear formulario y funcionalidad para agregar producto con datos completos al catálogo.                                                                      | 3                  | Camila Huamani  | Done   |
|              |                                                          | US057T002      | Implementar validación para campos obligatorios                               | Implementar validación para impedir añadir producto con campos incompletos o vacíos.                                                                         | 3                  | Camila Huamani  | Done   |
|              |                                                          | US057T003      | Crear función para agregar producto desde inventario                          | Crear funcionalidad para agregar productos ya existentes en inventario directamente al catálogo                                                              | 3                  | Camila Huamani  | Done   |
| US058        | Eliminacion de producto del catalogo                     | US058T001      | Crear funcionalidad para detectar productos sin stock y marcar en catálogo    | Agregar una funcionalidad que permita identificar productos sin stock y marcarlos como no disponibles en catálogo.                                           | 5                  | Camila Huamani  | Done   |
|              |                                                          | US058T002      | Crear funcionalidad para eliminar producto manualmente del catálogo           | Funcionalidad para que proveedor elimine manualmente un producto del catálogo sin eliminarlo del inventario.                                                 | 5                  | Camila Huamani  | Done   |
| US063        | Actualizar estado de la orden de venta                   | US063T001      | Implementar funcionalidad para actualizar el estado de una orden de venta.    | Crear una funcionalidad que permita al usuario cambiar el estado de una orden de venta a "Aceptado", "En preparación", "Enviando", "Entregado" o "Cancelado" | 2                  | Nicolas Juarez  | Done   |
|              |                                                          | US063T002      | Agregar funcionalidad para enviar notificaciones por orden cancelada          | Implementar una funcionalidad que envíe una notificación al dueño de licorería si su orden de compra se canceló por el proveedor.                            | 3                  | Nicolas Juarez  | Done   |
| US064        | Contabilizar productos en el inventario                  | US064T001      | Actualizar stock automáticamente al recibir pedido                            | Agregar método para incrementar stock en almacén digital al confirmar entrega.                                                                               | 4                  | Nicolas Juarez  | Done   |
|              |                                                          | US064T002      | Crear producto nuevo en inventario                                            | Implementar método para agregar nuevos productos recibidos y no existentes en almacén digital.                                                               | 4                  | Nicolas Juarez  | Done   |
| US020        | Detallar el estado de salida de productos                | US020T001      | Crear métodos para registrar el motivo de salida de productos                 | Crear un método para permitir al dueño de licorería registrar una salida de producto como venta                                                              | 3                  | Nicolás Juarez  | Done   |
| US021        | Configurar alertas de reposición                         | US021T001      | Crear función para definir umbral de stock mínimo                             | Crear un método para permitir que el dueño establezca un nivel mínimo por producto                                                                           | 3                  | Martin Gonzales | Done   |
|              |                                                          | US021T002      | Crear una función para generar alerta cuando stock esté por debajo del mínimo | Automatizar alerta al alcanzar o pasar el umbral definido                                                                                                    | 3                  | Martin Gonzales | Done   |
| US022        | Alertas por próximo vencimiento                          | US022T001      | Configurar margen de vencimiento                                              | Implementar opción para definir días previos al vencimiento para generar alerta                                                                              | 3                  | Martin Gonzales | Done   |
|              |                                                          | US022T002      | Crear un componente para visualizar productos próximos a vencer               | Mostrar claramente los productos en riesgo de vencimiento próximo en un componente "card"                                                                    | 3                  | Martin Gonzales | Done   |
| US039        | Crear un plan de reabastecimiento                        | US039T001      | Implementar una opción para crear plan de reabastecimiento para licorería     | Crear un formulario para ingresar datos de plan (cliente, productos, frecuencia)                                                                             | 4                  | Matias Diaz     | Done   |
|              |                                                          | US039T002      | Implementar un método para validar campos obligatorios                        | Añadir validaciones para asegurar datos completos antes de guardar                                                                                           | 2                  | Matias Diaz     | Done   |
| US040        | Editar plan de reabastecimiento existente                | US040T001      | Crear una opción para editar un plan existente                                | Permitir edición de datos en planes ya creados                                                                                                               | 3                  | Matias Diaz     | Done   |
|              |                                                          | US040T002      | Crear botón para cancelar edición sin guardar                                 | Implementar botón de cancelación que preserve los datos originales                                                                                           | 2                  | Matias Diaz     | Done   |
| US028        | Visualizar resumen económico de pérdidas                 | US028T001      | Crear una función para mostrar valor total de pérdidas                        | Calcular y mostrar el total monetario de pérdidas según precio de compra                                                                                     | 4                  | Martin Gonzales | Done   |
|              |                                                          | US030T002      | Aplicar desglose por tipo de pérdida                                          | Mostrar subtotales por tipo: merma, consumo interno, donación                                                                                                | 3                  | Martin Gonzales | Done   |
| US030        | Asociar productos comprados a inventario                 | US028T001      | Asociar productos de factura al inventario                                    | Registrar productos de una factura directamente en el stock                                                                                                  | 4                  | Farid Coronel   | Done   |
|              |                                                          | US030T002      | Agregar validaciones para evitar duplicados al ingresar productos             | Verificar existencia de producto y sumar unidades en lugar de duplicar                                                                                       | 3                  | Farid Coronel   | Done   |
| US031        | Registro de pedidos a proveedores                        | US031T001      | Crear una vista del historial de compras por proveedor                        | Mostrar pedidos pasados al seleccionar un proveedor                                                                                                          | 3                  | Farid Coronel   | Done   |
|              |                                                          | US031T002      | Filtrar historial por producto                                                | Implementar filtro de búsqueda por nombre de producto en historial                                                                                           | 3                  | Farid Coronel   | Done   |
| US065        | Visualización y elección del plan gratuito               | US065T001      | Definir estructura de datos para los planes                                   | Crear entidad o configuración para almacenar beneficios de los planes                                                                                        | 3                  | Farid Coronel   | Done   |
|              |                                                          | US065T002      | Implementar lógica para activar plan gratuito                                 | Asociar beneficios del plan gratuito al usuario                                                                                                              | 3                  | Farid Coronel   | Done   |
|              |                                                          | US065T003      | Crear vista/interfaz para mostrar plan gratuito                               | Mostrar los beneficios del plan de manera clara en la interfaz                                                                                               | 2                  | Farid Coronel   | Done   |
| US066        | Visualización y elección del plan premium                | US066T001      | Crear vista/interfaz para mostrar plan premium                                | Mostrar beneficios y comparativa con el plan gratuito                                                                                                        | 4                  | Farid Coronel   | Done   |
|              |                                                          | US066T002      | Implementar lógica para seleccionar plan premium                              | Activar plan premium en el sistema al usuario luego del pago                                                                                                 | 4                  | Farid Coronel   | Done   |
|              |                                                          | US066T003      | Integrar visualización con flujo de pago PayPal                               | Asegurar coherencia entre información mostrada y el proceso de pago                                                                                          | 3                  | Farid Coronel   | Done   |
| TS006        | Registrar productos en el inventario                     | TS006T001      | Crear modelo de producto                                                      | Definir esquema del producto: nombre, cantidad, tipo, fecha de vencimiento                                                                                   | 2                  | Nicolas Juarez  | Done   |
|              |                                                          | TS006T002      | Implementar POST para registrar productos en el inventario                    | Crear endpoint para registrar productos en inventario                                                                                                        | 3                  | Nicolas Juarez  | Done   |
|              |                                                          | TS006T003      | Validar duplicados y datos incompletos                                        | Controlar duplicación y campos requeridos                                                                                                                    | 2                  | Nicolas Juarez  | Done   |
| TS007        | Consultar inventario                                     | TS007T001      | Implementar GET para devolver un inventario                                   | Crear endpoint para devolver lista de productos del inventario                                                                                               | 2                  | Farid Coronel   | Done   |
|              |                                                          | TS007T002      | Crear función para manejar inventario vacío                                   | Crear una funcionalidad para devolver lista vacía con código 200 si no hay productos                                                                         | 1                  | Farid Coronel   | Done   |
| TS008        | Configurar alertas de reposición                         | TS008T001      | Crear modelo de alerta                                                        | Definir esquema para alertas (producto, umbral)                                                                                                              | 2                  | Martin Gonzales | Done   |
|              |                                                          | TS008T002      | Implementar consulta POST para alertas                                        | Crear endpoint para guardar configuraciones de alerta                                                                                                        | 2                  | Martin Gonzales | Done   |
| TS011        | Registrar guía de conservación                           | TS011T001      | Crear modelo de guía de conservación                                          | Definir estructura de guía (producto, condiciones de conservación, etc.)                                                                                     | 2                  | Matias Diaz     | Done   |
|              |                                                          | TS011T002      | Implementar consulta POST para registrar guías                                | Crear endpoint para registrar una nueva guía de conservación.                                                                                                | 2                  | Matias Diaz     | Done   |
|              |                                                          | TS011T003      | Validar campos obligatorios en las guías                                      | Manejar errores por datos incompletos                                                                                                                        | 1                  | Matias Diaz     | Done   |
| TS001        | Endpoint para registrar nuevo usuario                    | TS001T001      | Crear modelo y validaciones de usuario                                        | Definir esquema del usuario (nombre, correo, contraseña, rol) y validar campos requeridos                                                                    | 3                  | Camila Huamani  | Done   |
|              |                                                          | TS001T002      | Implementar consulta POST para registro de usuarios                           | Crear endpoint para registrar nuevos usuarios en la plataforma, creando su respectivo perfil                                                                 | 3                  | Camila Huamani  | Done   |
|              |                                                          | TS001T003      | Manejar errores por datos incompletos y duplicados                            | Incluir manejo de errores 400 (campos faltantes) y 409 (correo existente)                                                                                    | 2                  | Camila Huamani  | Done   |
| TS002        | Endpoint para iniciar sesión                             | TS002T001      | Implementar lógica de autenticación                                           | Verificar correo y contraseña del usuario                                                                                                                    | 2                  | Camila Huamani  | Done   |
|              |                                                          | TS002T002      | Implementar método para generar y devolver token JWT                          | Configurar JWT y retornarlo con datos del usuario                                                                                                            | 2                  | Camila Huamani  | Done   |
|              |                                                          | TS002T003      | Crear métodos para validar cuenta activa del usuario                          | Verificar si el usuario está activo antes de permitir acceso                                                                                                 | 1                  | Camila Huamani  | Done   |
| TS012        | Generar reporte de pérdidas                              | TS012T001      | Implementar lógica para detectar pérdidas                                     | Detectar productos vencidos, merma u otros criterios de pérdida                                                                                              | 3                  | Martin Gonzales | Done   |
|              |                                                          | TS012T002      | Implementar consulta GET para obtener perdidas                                | Crear endpoint que devuelva las pérdidas encontradas                                                                                                         | 2                  | Martin Gonzales | Done   |
| TS014        | Endpoint para registrar una nueva zona de almacenamiento | TS014T001      | Crear modelo y migración para zona de almacenamiento                          | Definir estructura de datos para zonas (nombre, descripción) y crear migración en base de datos                                                              | 3                  | Farid Coronel   | Done   |
|              |                                                          | TS014T002      | Implementar endpoint POST para registrar zonas                                | Crear lógica de controlador para registrar nueva zona de almacenamiento                                                                                      | 4                  | Farid Coronel   | Done   |
|              |                                                          | TS014T003      | Validar datos de entrada y verificar duplicados                               | Verificar que no falten campos obligatorios y que la zona no exista ya en BD                                                                                 | 2                  | Farid Coronel   | Done   |
| TS015        | Endpoint para obtener resumen del panel del usuario      | TS015T001      | Diseñar DTO/respuesta para panel del usuario                                  | Definir estructura de respuesta del panel (alertas, inventario, movimientos)                                                                                 | 2                  | Camila Huamani  | Done   |
|              |                                                          | TS015T002      | Implementar endpoint para obtener panel de usuario                            | Consultar datos relevantes y retornarlos en el formato definido y por tipo de rol de usuario (dueño de licorería o proveedor)                                | 4                  | Camila Huamani  | Done   |
|              |                                                          | TS015T003      | Añadir middleware de autenticación                                            | Asegurar que solo usuarios autenticados accedan al panel                                                                                                     | 1                  | Camila Huamani  | Done   |
| TS021        | Endpoint para generar una orden de compra                | TS021T001      | Diseñar estructura de orden de compra                                         | Definir modelo con sus relaciones (productos, cantidades, usuario)                                                                                           | 3                  | Nicolas Juarez  | Done   |
|              |                                                          | TS021T002      | Implementar endpoint POST para pedidos                                        | Crear lógica para registrar orden de compra y manejar errores                                                                                                | 4                  | Nicolas Juarez  | Done   |
|              |                                                          | TS021T003      | Validar productos en orden                                                    | Verificar que la orden no esté vacía                                                                                                                         | 1                  | Nicolas Juarez  | Done   |
| TS023        | Endpoint para actualizar estados de los pedidos          | TS023T001      | Definir lógica de transición de estados                                       | Permitir solo cambios válidos de estado (p. ej., pendiente → enviado)                                                                                        | 2                  | Nicolas Juarez  | Done   |
|              |                                                          | TS023T002      | Implementar endpoint PUT para pedidos                                         | Crear lógica de actualización de estado y respuesta adecuada                                                                                                 | 3                  | Nicolas Juarez  | Done   |
|              |                                                          | TS023T003      | Agregar validaciones de negocio (estado entregado)                            | Bloquear cambios a pedidos entregados                                                                                                                        | 1                  | Nicolas Juarez  | Done   |
| TS025        | Endpoint para validar un pago                            | TS025T001      | Configurar integración con API de PayPal                                      | Establecer conexión segura para validar pagos desde cliente                                                                                                  | 3                  | Farid Coronel   | Done   |
|              |                                                          | TS025T002      | Implementar endpoint POST /api/paypal                                         | Crear lógica para procesar y validar respuesta del pago                                                                                                      | 4                  | Farid Coronel   | Done   |
|              |                                                          | TS025T003      | Manejar errores de PayPal (fondos insuficientes)                              | Procesar código INSUFFICIENT\_FUNDS y retornar error 402                                                                                                     | 2                  | Farid Coronel   | Done   |


### 5.2.3.4. Development Evidence for Sprint Review ###

En esta sección, se describen los principales avances de implementación realizados en este tercer sprint.

A continuación, se muestra una tabla que contiene la información sobre los _commits_ hechos que contienen partes de las funcionalidades que debemos implementar para completar el tercer sprint.

| Repository                      | Branch                   | Commit Id | Commit Message                                                                        | Commited On  |
| ------------------------------- | ------------------------ | --------- | ------------------------------------------------------------------------------------- | ------------ |
| OpenDoors/StockSip-Back-End-App | inventories              | a996184   | feat(inventory-management): add account warehouses inbound service.                   | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | inventories              | 8475722   | feat(inventories): add resources and assemblers.                                      | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | products                 | 79d402e   | feat(products): add command for updating only the minimum stock level.                | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | inventories              | b7a66ad   | feat(inventories): add queries.                                                       | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | care-guides              | 3a892b5   | feat(care-guides): add repository implementation.                                     | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | care-guides              | 344f781   | feat(care-guides): add care guide command service contract.                           | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | care-guides              | e77812c   | feat(care-guides): add commands.                                                      | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | release                  | 0f86516   | chore: add dockerfile.                                                                | Jun 22, 2025 |
| OpenDoors/StockSip-Back-End-App | alerts                   | 9384e3a   | feat(alerts-and-notifications): add external service in inventory management context. | Jun 20, 2025 |
| OpenDoors/StockSip-Back-End-App | alerts                   | 2caef51   | feat(alerts-and-notifications): add anti-corruption layer implementation.             | Jun 20, 2025 |
| OpenDoors/StockSip-Back-End-App | alerts                   | 92d34d    | feat(alerts): add alert commands.                                                     | Jun 20, 2025 |

### 5.2.3.5. Execution Evidence for Sprint Review ###
El objetivo de este sprint fue, mediante un trabajo colaborativo entre todos los integrantes del equipo, realizar la actualización del landing page, del frontend y la primera version del backend. Esta tarea incluyó la mejora de aspectos visuales y funcionales, así como la integración de los cambios en los repositorios correspondientes para su posterior despliegue.


#### **Landing Page**

**Video about the team**
<p align="center">
  <img src="https://i.imgur.com/YqXuFYh.png"/>
</p>
<br>

**Video about the product**
<p align="center">
  <img src="https://i.imgur.com/uRPVNuH.png"/>
</p>
<br>

#### **Front End Application**

**Ordenes dueño**
<p align="center">
  <img src="https://i.imgur.com/jYVMgI8.png"/>
</p>
<br>

**Ordesnes proveedor**
<p align="center">
  <img src="https://i.imgur.com/cNl9e1d.png"/>
</p>
<br>

**Nueva orden**
<p align="center">
  <img src="https://i.imgur.com/B2pc4k7.png"/>
</p>
<br>

**Catalogos**
<p align="center">
  <img src="https://i.imgur.com/vK4W9dB.png"/>
</p>
<br>

**Nuevo catalogos**
<p align="center">
  <img src="https://i.imgur.com/1syLV04.png"/>
</p>
<br>

#### **Back End Application**
**Guias de conservacion**

<p align="center">
  <img src="https://i.imgur.com/Sr9FFNB.png"/>
</p>
<br>


**Products**

<p align="center">
  <img src="https://i.imgur.com/HwA3oIl.png"/>
</p>
<br>


**Warehouses**

<p align="center">
  <img src="https://i.imgur.com/mkfc0RK.png"/>
</p>
<br>


**Alertas**

<p align="center">
  <img src="https://i.imgur.com/JSViuuy.png"/>
</p>
<br>


**Cuentas de usuario**

<p align="center">
  <img src="https://i.imgur.com/9EUTotn.png"/>
</p>
<br>




### 5.2.3.6. Services Documentation Evidence for Sprint Review ###

| Módulo      | Endpoint                                                                                            | Acción                                    | Verbo HTTP | Sintaxis                                       | Parámetros principales                                        | Enlace a Swagger                                              |
| ----------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------- | ---------- | ---------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- |
| Care Guides | `/api/v1/care-guides/{careGuideId}`                                                                 | Obtener guía por ID                       | GET        | `/api/v1/care-guides/123`                      | `careGuideId`, `accountId`                                    | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}`                                                                 | Actualizar guía                           | PUT        | `/api/v1/care-guides/123`                      | Body con nuevos campos                                        | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}`                                                                 | Eliminar guía                             | DELETE     | `/api/v1/care-guides/123`                      | `careGuideId`                                                 | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}/deallocations`                                                   | Desasignar guía                           | PUT        | `/api/v1/care-guides/123/deallocations`        | `careGuideId`                                                 | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}/allocations/{productId}`                                         | Asignar guía a producto                   | PUT        | `/api/v1/care-guides/123/allocations/45`       | `careGuideId`, `productId`                                    | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Products    | `/api/v1/products/{productId}/care-guide`                                                           | Obtener guía por producto                 | GET        | `/api/v1/products/45/care-guide`               | `productId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Products    | `/api/v1/products/{productId}/exits`                                                                | Obtener salidas por producto              | GET        | `/api/v1/products/45/exits`                    | `productId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Products    | `/api/v1/products/{productId}`                                                                      | Obtener producto por ID                   | GET        | `/api/v1/products/45`                          | `productId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Products    | `/api/v1/products/{productId}`                                                                      | Actualizar producto                       | PUT        | `/api/v1/products/45`                          | Body con valores actualizados                                 | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Products    | `/api/v1/products`                                                                                  | Crear producto                            | POST       | `/api/v1/products`                             | Body con nuevos campos                                        | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Products    | `/api/v1/products`                                                                                  | Obtener productos por perfil              | GET        | `/api/v1/products?profileId=10`                | `profileId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses`                                                                                | Obtener todos los almacenes               | GET        | `/api/v1/warehouses`                           | —                                                             | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses`                                                                                | Crear un almacén                          | POST       | `/api/v1/warehouses`                           | Body con datos del almacén                                    | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}`                                                                  | Obtener almacén por ID                    | GET        | `/api/v1/warehouses/123`                       | `warehouseId`                                                 | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}`                                                                  | Actualizar almacén                        | PUT        | `/api/v1/warehouses/123`                       | Body actualizado + `warehouseId`                              | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}`                                                                  | Eliminar almacén                          | DELETE     | `/api/v1/warehouses/123`                       | `warehouseId`                                                 | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/inventories/product/{productId}`                                  | Agregar stock a producto                  | POST       | `/warehouses/123/inventories/product/456`      | `expirationDate`, `quantity`                                  | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/inventories/product/{productId}/additions`                        | Añadir stock                              | PUT        | `.../additions`                                | `addedQuantity`, `stockExpirationDate`                        | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/inventories/{productId}/substractions`                            | Quitar stock                              | PUT        | `.../substractions`                            | `removedQuantity`, `expirationDate`                           | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/inventories/product/{productId}/moves`                            | Mover stock entre almacenes               | PUT        | `.../moves`                                    | `newWarehouseId`, `movedQuantity`, `movedStockExpirationDate` | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/inventories/product/{productId}/expiration-date/{expirationDate}` | Obtener inventario por fecha              | GET        | `/.../expiration-date/2025-06-22`              | `warehouseId`, `productId`, `expirationDate`                  | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/inventories/product/{productId}`                                  | Eliminar stock con fecha                  | DELETE     | `/.../product/456` (en body: `expirationDate`) | `warehouseId`, `productId`                                    | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/product-exits/{productId}`                                        | Registrar salida de producto              | POST       | `.../product-exits/456`                        | `expirationDate`, `quantityExited`, `exitReason`              | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/product-exits/{productId}`                                        | Obtener salidas por producto              | GET        | `.../product-exits/456`                        | `warehouseId`, `productId`                                    | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/product-exits`                                                    | Obtener salidas por almacén               | GET        | `/.../product-exits`                           | `warehouseId`                                                 | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/products`                                                         | Obtener productos por almacén             | GET        | `/.../products`                                | `warehouseId`                                                 | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Warehouses  | `/api/v1/warehouses/{warehouseId}/products/provider/{providerId}`                                   | Obtener productos por proveedor y almacén | GET        | `/.../products/provider/789`                   | `warehouseId`, `providerId`                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Alerts      | `/api/v1/alerts/{alertId}`                                                                          | Obtener alerta por ID                     | GET        | `/api/v1/alerts/123`                           | `alertId`                                                     | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides/{careGuideId}`                                            | Obtener Care Guide por ID                 | GET        | `/accounts/1/care-guides/10`                   | `accountId`, `careGuideId`                                    | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides`                                                          | Obtener todos los Care Guides             | GET        | `/accounts/1/care-guides`                      | `accountId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides`                                                          | Crear Care Guide sin producto             | POST       | `/accounts/1/care-guides`                      | `accountId`, Body                                             | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides/product/{productId}`                                      | Crear Care Guide con producto             | POST       | `/accounts/1/care-guides/product/99`           | `accountId`, `productId`, Body                                | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/products`                                                             | Obtener productos por cuenta              | GET        | `/accounts/1/products`                         | `accountId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/warehouses`                                                           | Obtener almacenes por cuenta              | GET        | `/accounts/1/warehouses`                       | `accountId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/alerts`                                                               | Obtener alertas por cuenta                | GET        | `/accounts/1/alerts`                           | `accountId`                                                   | [Ver Link](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html) |

## **Ejemplos Detallados**


### Care Guides

#### Endpoint: Endpoint: `/api/v1/care-guides/{careGuideId}` – `GET`

- **Descripción:** Crea una nueva guía de cuidado sin asociarla inicialmente a un producto.
    
- **Parámetros:**
    
    - `careGuideId` (path)
    - `accountId` (path)
        
- **Ejemplo de llamada:**

	- GET /api/v1/care-guides/123
    
- **Respuesta (`200 Ok`):**
    
	{
	  "id": "123",
	  "accountId": "456",
	  "productId": "789",
	  "title": "Guía de Almacenamiento",
	  "summary": "Instrucciones para conservar el producto",
	  "minTemp": 5,
	  "maxTemp": 15,
	  "placeStorage": "Ambiente fresco",
	  "recommendation": "Evitar exposición solar directa"
	}


### Products

### Endpoint: `/api/v1/products` – `POST`

- **Descripción:** Crea un nuevo producto asociado a un proveedor.
    
- **Body:**

	{
	  "additionalName": "Whisky Etiqueta Azul",
	  "liquorType": "Whisky",
	  "brandName": "Blue Label",
	  "unitPriceAmount": 250,
	  "minimumStock": 10,
	  "imageUrl": "http://example.com/image.png",
	  "providerId": "sup123"
	}
	
- **Respuesta exitosa (`201 Created`):**

	{
	  "id": "prod678",
	  "imageUrl": "http://example.com/image.png",
	  "name": "Whisky Etiqueta Azul",
	  "brandName": "Blue Label",
	  "liquorType": "Whisky",
	  "unitPriceAmount": 250,
	  "minimumStock": 10,
	  "providerId": "sup123"
	}
	
- **Respuesta de error (`400`):**  
    `"Product could not be created..."`


### Warehouses

### Endpoint: `/api/v1/warehouses/{warehouseId}/inventories/product/{productId}` – `POST`

- **Descripción:** Añade stock a un producto en un almacén determinado, registrando su fecha de expiración.
    
- **Parámetros:**
    
    - `warehouseId`: ID del almacén
        
    - `productId`: ID del producto
        
 - Body:
        
	 {
	  "expirationDate": "2025-12-01T00:00:00",
	  "quantity": 100
	 }
        
- **Respuesta exitosa (`201 Created`):**

	{
	  "id": "inv123",
	  "productId": "prod456",
	  "warehouseId": "wh789",
	  "bestBeforeDate": "2025-12-01T00:00:00",
	  "stock": 100,
	  "productState": "FRESH"
	}



### Alerts

### Endpoint: `/api/v1/alerts/{alertId}` – `GET`

- **Descripción:** Recupera una alerta del sistema según su identificador único.
    
- **Parámetros:**
    
    - `alertId` (path): ID de la alerta.
        
- **Ejemplo de llamada:**
    
    `GET /api/v1/alerts/a123`
    
- **Ejemplo de respuesta (`200 OK`):**
    
    {
	  "id": "a123",
	  "title": "Alerta de Temperatura",
	  "message": "La temperatura ha superado el límite permitido.",
	  "severity": "HIGH",
	  "type": "STORAGE_CONDITION",
	  "productId": "p456",
	  "warehouseId": "w789"
	  }
    
- **Respuesta de error (`404 Not Found`):**
    
    `Alert not found...`


### Account

### Endpoint: `/api/v1/accounts/{accountId}/care-guides` – `POST`

- **Descripción:** Crea una nueva guía de cuidado sin asociarla inicialmente a un producto.
    
- **Parámetros:**
    
    - `accountId` (path): ID de la cuenta.
        
- **Body:**
    
	{
	  "title": "Guía de temperatura baja",
	  "summary": "Almacenar bajo 8 °C",
	  "minTemp": 2,
	  "maxTemp": 8,
	  "placeStorage": "Refrigerado",
	  "recommendation": "Evitar exposición al calor."
	}
    
- **Respuesta (`201 Created`):**
    
	{
	  "id": "cg01",
	  "accountId": "acc01",
	  "productId": null,
	  "title": "Guía de temperatura baja",
	  "summary": "Almacenar bajo 8 °C",
	  "minTemp": 2,
	  "maxTemp": 8,
	  "placeStorage": "Refrigerado",
	  "recommendation": "Evitar exposición al calor."
	}

### 5.2.3.7. Software Deployment Evidence for Sprint Review ###

#### Despliegue del Back End
* Primero, se creó un repositorio en GitHub para alojar el código fuente del Backend, permitiendo así una gestión centralizada y control de versiones
* Segundo, cada miembro del equipo creó una rama individual para desarrollar una función específica del BackEnd, lo que permitió trabajar en paralelo de manera organizada.
<p align="center">
  <img src="https://i.imgur.com/e31bJ1F.png"/>
</p>

* Tercero, se creó un proyecto en Rider y se conectó al repositorio remoto, facilitando la integración del código con el control de versiones desde el entorno de desarrollo.
* Cuarto, se implementaron las diferentes funcionalidades asignadas y se realizaron los commits respectivos, siguiendo buenas prácticas para mantener un historial de cambios claro.
* Quinto, una vez completado el desarrollo, se hizo merge de las ramas individuales a develop, donde se resolvieron conflictos y se corrigieron errores detectados en la integración.
* Sexto, tras verificar el correcto funcionamiento en develop, se realizó el merge final hacia la rama release, consolidando una versión estable del proyecto.
* Septimo, se configuró el archivo dockerfile y appsettings.production para poder utilizar la web render para su despliegue exitoso.
* Octavo, se configuro la pagina FreeSQLDatabase para poder desplegar nuestra base de datos en la nube.
* Noveno, se realizó el despliegue del Backend a través de Render. A continuación, se muestra la evidencia del despliegue:
<p align="center">
  <img src="https://i.imgur.com/Aw9gYTV.png"/>
</p>

* Link publico: [Web_Services_StockSip](https://stocksip-back-end-application.onrender.com/swagger-ui/index.html)

### 5.2.3.8. Team Collaboration Insights durint Sprint ###
En esta sección se detalla cómo se llevaron a cabo las actividades de implementación durante el sprint, así como la participación de cada miembro del equipo. Para este sprint, el equipo se organizó en torno a los tres principales productos: Landing Page, Web Application (Frontend) y Web Services(BackEnd). Cada integrante asumió responsabilidades específicas en uno o más de estos componentes, trabajando mediante ramas individuales y siguiendo una estrategia de integración continua.

El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:

<p align="center">
  <img src="https://i.imgur.com/7mo7SJU.png"/>
</p>

A continuacion de detallara el trabajo que realizo cada integrante del equipo:
- El integrante Martín Gonzales fue responsable de implementar la sección de alertas en el Frontend y creacion del bounded context alerts and notifications
- La integrante Camila Huamani agrego los videos about the team y about the product. En el Frontend se encargo de realizar las secciones de catalogo y órdenes de compra y creacion del bounded context authentication, y profile management
- El integrante Farid Coronel fue responsable de implementar el bounded context de inventory management y payments and subscriptions.
- El integrante Matias Diaz implementó la seccion de planes de reabastecimiento en el Frontend y creacion del bounded context analytics and reporting
- El integrante Nicolas Juarez implementó la creacion del bounded context inventory management

Commits de los integrantes en el Landing Page:
<p align="center">
  <img src="https://i.imgur.com/xaO8mjo.png"/>
</p>

Grafico de los push y merge realizados por el equipo en el landing page:
<p align="center">
  <img src="https://i.imgur.com/vBY3Ne2.png"/>
</p>

Commits de los integrantes en el Frontend:
<p align="center">
  <img src="https://i.imgur.com/pfifLqs.png"/>
</p>

Grafico de los push y merge realizados por el equipo en el Frontend: 

<p align="center">
  <img src="https://i.imgur.com/3Y3G0cw.png"/>
</p>

Commits de los integrantes en el BackEnd:
<p align="center">
  <img src="https://i.imgur.com/oDFYrHx.png"/>
</p>

Grafico de los push y merge realizados por el equipo en el BackEnd 

<p align="center">
  <img src="https://i.imgur.com/09vttpb.png"/>
</p>

### 5.2.4. Sprint 4 ###

#### 5.2.4.1. Sprint Planning 4

A continuación, se detalla, en la tabla siguiente, información sobre el planeamiento del último sprint del proyecto. Además, para este sprint se definió un objetivo para cubrir los aspectos de sitio web estático, aplicación front-end y aplicación back-end. Una sección del objetivo se centra en desarrollar una mejora visual para el sitio web estático y añadir mejoras para secciones para los videos acerca del producto y del equipo de desarrollo para los visitantes del sitio web. Por otro lado, el segundo objetivo se centra en la implementación de consumo de servicios de la aplicación backend para la aplicación front-end de StockSip. Finalmente, el último objetivo del sprint se centra en la implementación de endpoints relacionados con órdenes de compra y autenticación de usuarios.

| Sprint #                            | Sprint 4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <b> Sprint planning Background </b> | --                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Date                                | 2025/06/24                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Time                                | 11:00 AM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Location                            | Reunión presencial en el aula VH107 del curso en la sede Villa                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Prepared By                         | Gonzales Castillo, Angel Martin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Attendees                           | Huamani Cruz, Camila Victoria / Juarez Leon, Nicolas Emilio Walter / Gonzales Castillo, Angel Martin / Coronel Espinoza, Farid Sebastian / Julca Minaya, Sergio Gino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Sprint 3 Review Summary             | In the previous sprint, the team finished to implement the videos about the team and about the product in the Landing Page. Also, completed most of the sections of the front-end application and making sure it works with the fake API server. Finaly, the principal endpoints for the back-end application like warehouses, products, inventories, alerts and care guides were implemented.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Sprint 3 Retrospective Summary      | In this sprint, the team improved the internal communication between all the members and achieve another level in trust and communication. This will help the team to finish all the remaining tasks left for the final sprint and complete the develop of the product.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| <b> Sprint Goal & User Stories </b> | --                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Sprint 4 Goal                       | Our goal is to offer the complete information and a detailed video about all benefits and features related to the product and the final video with complete details of the team behind the platform in the life cycle of the product development, implement web service consumption for endpoints related to products, warehouses, inventories, alerts, care guides, orders, accounts, users, profiles and authentication in the front end application and increment the possibilities to implement features related to profile preferences; creating an account with a subscription and making orders. We believe it delivers the complete knowledge of the potential benefits of using the application and trust of usage to the visitors; consumption, manipulation and creation of real-time data regarding products, warehouses, inventories, alerts, orders, care guides, accounts, profiles, users and authentication to the liquor store owners and providers and opportunities to implement features related to profile preferences; creating an account with a subscription and making orders to the developers. This will be confirmed when the user registration numbers increment, the liquor store owners use the application to help them to do the inventory control of their stores; the providers use the application to do the inventory control and do the reception and check of the orders to deliver to its clients and the web developers implement features related to profile preferences; creating an account with a subscription and making orders. |
| Sprint 4 Velocity                   | 91                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Sum of Story Points                 | 90                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

#### 5.2.4.2. Aspect Leaders and Collaborators

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este último sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada las principales secciones que presenta el Front-End Web Application y en su contraparte para el Back-End Application. Para esto, hemos definido las siguientes secciones: Inventarios y Zonas, Productos, Cuenta de Usuario, Reportes, Órdenes de compra y Alertas.

| Team Member                        | GitHub Username | Alerts and Notifications | Analytics and Reporting | Authentication | Inventory Management  | Order Operation and Monitoring | Payment and Subscriptions | Profile Management |
|------------------------------------|-----------------|--------------------------|-------------------------|----------------|-----------------------|--------------------------------|---------------------------|--------------------|
| Huamani Cruz, Camila Victoria      | victiila06      |                          |                         | L              |                       | L                              |                           | L                  |
| Gonzales Castillo, Angel Martin    | XdiabloX426     | L                        |           L             |                |                       |                                |                           |                    |
| Coronel Espinoza, Farid Sebastian  | Far14z          |                          |                         | C              | C                     |                                | L                         |                    |
| Julca Minaya, Sergio Gino          | sergioMJ05      |                          |                         |                | C                     |                                |                           |                    |
| Juarez Leon, Nicolas Emilio Walter | JuarezLn10      | C                        |                         | C              | L                     |                                |                           |                    |

#### 5.2.4.3. Sprint Backlog 4

Como se mencionó previamente en el planeamiento de este sprint, el objetivo del mismo es concluir definitivamente con el sitio web estático integrando una mejora en las secciones que informen a los visitantes sobre los desarrolladores del producto y sobre el producto en sí; implementarle a la aplicación frontend la capacidad de consumir los servicios web que ofrece la aplicación backend e implementar endpoints en la aplicación backend necesarios para la implementación de características relacionadas a órdenes de compra y autenticación de usuarios.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint.
[https://trello.com/invite/b/68656a625110370ffdc6aad5/ATTIc7cfb2ae142da72c21ec87c8b1b3e6ad2FABEAB6/stocksip-sprint-backlog-4](https://trello.com/invite/b/68656a625110370ffdc6aad5/ATTIc7cfb2ae142da72c21ec87c8b1b3e6ad2FABEAB6/stocksip-sprint-backlog-4)

<p align="center">
  <img src="https://i.imgur.com/MoCTfWf.png" 
  alt="Sprint goal and Stories of Sprint #4"/>
</p>


A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este último sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 4     | Sprint Backlog 4                                  |                |                                                                               |                                                                                                                                                              |                    |                 |        |
|--------------|---------------------------------------------------|----------------|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|-----------------|--------|
| User Stories |                                                   | Work Item/Task |                                                                               |                                                                                                                                                              |                    |                 |        |
| Id           | Title                                             | Id             | Title                                                                         | Description                                                                                                                                                  | Estimation (Hours) | Assigned to     | Status |
| US052        | Consultar historial de facturación                | US052T001      | Desarrollar sección que muestre historial de ordenes                          | Desarrollar una sección en el front end que muestre todas las órdenes realizadas.                                                                            | 6                  | Camila Huamani  | Done   |
|              |                                                   | US052T002      | Implementar endpoint para obtener todas las ordenes de un usuario             | Desarrollar un endpoint que permita obtener todas las ordenes de un determinado usuario.                                                                     | 6                  | Camila Huamani  | Done   |
| US066        | Acceder al plan premium                           | US066T001      | Desarrollar una sección que permita a los usuarios elegir su plan             | Desarrollar una sección que muestre información del plan premium y el precio del mismo.                                                                      | 6                  | Farid Coronel   | Done   |
|              |                                                   | US066T002      | Implementar el API de PayPal para realizar pagos                              | Implementar el API de PayPal para validar los pagos.                                                                                                         | 8                  | Farid Coronel   | Done   |
| US065        | Acceder al plan gratuito                          | US065T001      | Desarrollar una sección que muestre información del plan gratuito             | Desarrollar una sección que muestre información del plan gratuito.                                                                                           | 4                  | Farid Coronel   | Done   | 
| TS002        | Endpoint para iniciar sesión                      | TS002T001      | Desarrollar un endpoint para inicio de sesión                                 | Desarrollar un endpoint que autentique usuarios para el inicio de sesión.                                                                                    | 5                  | Nicolas Juarez  | Done   |
|              |                                                   | TS002T002      | Implementar JWT para la generación de Tokens                                  | Implementar JSON Web Tokens para la generación de Tokens con Bearer para la validación.                                                                      | 4                  | Nicolas Juarez  | Done   |
| TS001        | Endpoint para registrar nuevo usuario             | TS001T001      | Desarrollar un endpoint para el registro de usuarios                          | Desarrollar un endpoint que registre nuevos usuarios.                                                                                                        | 6                  | Nicolas Juarez  | Done   |
| US042        | Crear guía de remisión interna                    | US042T001      | Desarrollar lógica para trasladar producto a otro inventario                  | Desarrollar lógica de negocio relacionada con traslado de mercadería internamente.                                                                           | 6                  | Nicolas Juarez  | Done   |
| TS017        | Endpoint para registrar guía de remisión          | TS017T001      | Desarrollar un endpoint para trasladar productos a otro inventario            | Desarrollar un endpoint para poder trasladar productos a otro inventario.                                                                                    | 6                  | Nicolas Juarez  | Done   |
| TS009        | Endpoint para configurar alertas de vencimiento   | TS009T001      | Desarrollar un endpoint que permita configurar alertas                        | Desarrollar un endpoint para poder modificar la configuración de las alertas.                                                                                | 6                  | Martin Gonzales | Done   |
| TS022        | Endpoint para visualizar el estado de los pedidos | TS022T001      | Desarrollar un endpoint para obtener las ordenes realizadas                   | Desarrollar un endpoint que permita obtener las ordenes de un usuario específico.                                                                            | 8                  | Camila Huamani  | Done   |
| TS016        | Endpoint para generar plan de reabastecimiento    | TS016T001      | Desarrollar un botón para trasladar productos a otro inventario               | Desarrollar un botón que permita utilizar el endpoint para trasladar productos de un inventario a otro.                                                      | 6                  | Sergio Julca    | Done   |
| US032        | Visualizar historial de facturación de compras    | US032T001      | Desarrollar un endpoint para obtener todos las ordenes de una cuenta          | Desarrollar el endpoint que permita obtener las ordenes hechas por una cuenta específica.                                                                    | 8                  | Camila Huamani  | Done   |
|              |                                                   | US032T002      | Desarrollar un endpoint para obtener todos las ordenes de un proveedor        | Desarrollar el endpoint que permita obtener las ordenes enviadas hacia un proveedor específico.                                                              | 6                  | Camila Huamani  | Done   |
| TS018        | Endpoint para actualizar perfil del usuario       | TS018T001      | Desarrollar un endpoint para creación de perfiles                             | Desarrollar un endpoint que permita crear perfiles para un usuario.                                                                                          | 6                  | Farid Coronel   | Done   |
|              |                                                   | TS018T002      | Desarrollar un endpoint para actualizar perfiles                              | Desarrollar un endpoint que permita actualizar el perfil para un usuario.                                                                                    | 6                  | Farid Coronel   | Done   |
| TS004        | Endpoint para recuperar contraseña                | TS004T001      | Implementar lógica para validar códigos generados para restablecer contraseña | Implementar lógica que permita validar el código enviado al correo electrónico del usuario que desea restablecer su contraseña.                              | 6                  | Camila Huamani  | To-Do  |
|              |                                                   | TS004T002      | Implementar un endpoint para actualizar contraseña                            | Desarrollar un endpoint que permita la actualización de contraseñas de los usuarios.                                                                         | 5                  | Camila Huamani  | Done   |
| US014        | Cambiar contraseña desde configuración            | US014T001      |                                                                               | En la aplicación frontend, se debe implementar un botón que redirija al usuario a una sección donde pueda realizar el proceso de recuperación de contraseña. | 4                  | Camila Huamani  | Done   |
| US047        | Cambiar contraseña desde el perfil                | US047T001      |                                                                               | En la aplicación frontend, se debe implementar un botón que redirija al usuario a una sección donde pueda realizar el proceso de recuperación de contraseña. | 4                  | Camila Huamani  | Done   |
| US012        | Recuperar contraseña mediante correo electrónico  | US012T001      | Implementar botón para acceder a la sección de recuperación de contraseña     | En la aplicación frontend, se debe implementar un botón que redirija al usuario a una sección donde pueda realizar el proceso de recuperación de contraseña. | 4                  | Camila Huamani  | Done   |
|              |                                                   | US012T002      | Implementar un servicio de email para enviar correos electrónicos             | Implementar un servicio de terceros con el que se pueda enviar correos electrónicos para recuperación de contraseñas.                                        | 6                  | Camila Huamani  | To-Do  |
|              |                                                   | US012T003      | Implementar lógica para validar códigos generados                             | Implementar lógica que permita validar el código enviado al correo electrónico del usuario que desea recuperar su contraseña.                                | 8                  | Camila Huamani  | To-Do  |
| US015        | Cerrar sesión manualmente                         | US015T001      | Implementar botón para cerrar sesión                                          | En la aplicación frontend, se debe implementar un botón para que el usuario pueda cerrar sesión de su cuenta                                                 | 4                  | Camila Huamani  | Done   |
|              |                                                   | US015T002      | Implementar la lógica necesaria para cerrar la sesión del usuario             | Implementar la funcionalidad que permita borrar la información que permite al usuario realizar actividades en la aplicación.                                 | 4                  | Camila Huamani  | Done   |
| US013        | Elegir una contraseña segura                      | US013T001      | Implementar un método que valide la contraseña                                | Implementar un método que revise la contraseña y valide el nivel de seguridad que posea.                                                                     | 4                  | Camila Huamani  | Done   |
|              |                                                   | US013T002      | Probar el método de validación de la contraseña                               | Probar que el método funcione para verificar su funcionamiento esperado.                                                                                     | 4                  | Camila Huamani  | Done   |

#### 5.2.4.4. Development Evidence for Sprint Review
En esta sección, se describen los principales avances de implementación realizados en este último sprint.

A continuación, se muestra una tabla que contiene la información sobre los commits hechos que contienen partes de las funcionalidades que debemos implementar para completar este sprint.

Repositorio del sitio web estático: [https://github.com/OpenDoorss/StockSip-LandingPage](https://github.com/OpenDoorss/StockSip-LandingPage)
Repositorio de la aplicación Frontend: [https://github.com/OpenDoorss/stocksip-front-end-application](https://github.com/OpenDoorss/stocksip-front-end-application)
Repositorio de la aplicación Backend: [https://github.com/OpenDoorss/stocksip-back-end-application](https://github.com/OpenDoorss/stocksip-back-end-application)

| Repository                        | Branch                    | Commit Id | Commit Message                                                            | Commited On |
|-----------------------------------|---------------------------|-----------|---------------------------------------------------------------------------|-------------|
| EXPDesigners/StockSip-LandingPage | feature/testimonials      | d2d8cdd   | fix: change files and folders naming.                                     | 05/07/2025  |
| EXPDesigners/StockSip-FrontEndApp | feature/warehouse-logic   | 8344243   | feat(inventory): add warehouse logic.                                     | 05/07/2025  |
| EXPDesigners/StockSip-FrontEndApp | feature/accounts          | eef6170   | feat(accounts): add authentication service.                               | 05/07/2025  |
| EXPDesigners/StockSip-FrontEndApp | feature/subscription-view | 0082b32   | feat(SAP): add subscription view with responsive design.                  | 05/07/2025  |
| EXPDesigners/StockSip-FrontEndApp | feature/alerts            | 57b1c92   | feat(alerts): add alert integration in the dashboard                      | 06/07/2025  |
| EXPDesigners/StockSip-BackEndApp  | feature/orders            | 3e095c7   | feat(orders): add orders controller.                                      | 02/07/2025  |
| EXPDesigners/StockSip-BackEndApp  | feature/catalogs          | 3e095c7   | feat(catalogs): add clients and dto.                                      | 02/07/2025  |
| EXPDesigners/StockSip-BackEndApp  | feature/alerts            | 3e095c7   | feat(alerts): add events.                                                 | 05/07/2025  |
| EXPDesigners/StockSip-BackEndApp  | feature/accounts          | 6a667c1   | feat(authentication): add acl to get account id for the sign in resource. | 05/07/2025  |


#### 5.2.4.5. Execution Evidence for Sprint Review
En esta sección, se explica lo logrado en este sprint con pruebas de lo implementado.
Primero, los logros de este sprint incluyen la implementación de una mejora en las secciones con dos videos para los visitantes del sitio web: uno que incluye información relacionada a las características y beneficios que ofrece la aplicación web, y otro que detalla información del equipo de desarrollo de la aplicación a lo largo del ciclo de vida del proyecto.
También, los logros incluyen la implementación en la aplicación frontend de poder consumir servicios web de parte de la aplicación backend en todas las secciones implementadas previamente. Finalmente, también, se logró implementar unos cuantos endpoints en la aplicación backend relacionados con órdenes de compra, alertas, autenticación, perfiles, cuentas y suscripciones.

A continuación, se muestran las capturas de pantalla de las secciones implementadas en la Landing Page, aplicación Front End y aplicación Backend. Estas imágenes reflejan el progreso realizado en el sprint y sirven como evidencia del trabajo completado.

- Vídeo de ejecución de los tres productos para este sprint: https://youtu.be/32aIog7QiWQ

## **Landing Page**

Se adjuntan los enlaces para acceder al sitio web desplegado y al vídeo de ejecución del sitio web estático. El vídeo muestra el funcionamiento de cada sección del sitio web y cómo se ve en un navegador web.

Video sobre exploracion de la aplicacion
<p align="center">
  <img src="https://i.imgur.com/R7IKPNX.png" 
  alt="Exploration of the app section in landing page"/>
</p>


## **Front End Application**

Se adjuntan los enlaces para acceder a la aplicación frontend desplegada y al vídeo de ejecución de la misma. El vídeo muestra el funcionamiento de cada sección implementada y cómo se ve en un navegador web.

Seccion de almacenes
<p align="center">
  <img src="https://i.imgur.com/JKOTI6O.png" 
  alt="Warehouses in frontend"/>
</p>

Seccion de ordenes
<p align="center">
  <img src="https://i.imgur.com/eRTeEX5.png" 
  alt="Orders in frontend"/>
</p>

### **Back End Application**
Se adjuntan los enlaces para acceder a la aplicación backend desplegada y al vídeo de ejecución de la misma. El vídeo muestra el funcionamiento de cada sección implementada y cómo fueron nombradas las rutas de los endpoints implementados.

Endpoints para catalogos en el backend
<p align="center">
  <img src="https://i.imgur.com/IJZMiKb.png" 
  alt="Catalogs in backend"/>
</p>

Endpoints para cuentas en el backend
<p align="center">
  <img src="https://i.imgur.com/Vnvk58B.png" 
  alt="Accounts in backend"/>
</p>

#### 5.2.4.6. Services Documentation Evidence for Sprint Review
En esta sección, se describe la evidencia de documentación de los endpoints que se han implementado en la aplicación backend de nuestro proyecto para este sprint. A continuación, se muestra la tabla que contiene una breve descripción de las acciones y requisitos de cada endpoint implementado.

| Módulo      | Endpoint                                                                                            | Acción                                    | Verbo HTTP | Sintaxis                                       | Parámetros principales                                        | Enlace a Swagger                                              |
| ----------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------- | ---------- | ---------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- |
| Care Guides | `/api/v1/care-guides/{careGuideId}`                                                                 | Obtener guía por ID                       | GET        | `/api/v1/care-guides/123`                      | `careGuideId`, `accountId`                                    | [Ver Link](https://stocksip-backendapplication.onrender.com/) |

#### 5.2.4.7. Software Deployment Evidence for Sprint Review
Para asegurar un desarrollo estructurado y un despliegue eficiente, se organizaron los componentes del proyecto en tres partes principales: la Landing Page, el Frontend y Backend funcional. Cada uno fue alojado en su propio repositorio de GitHub, con procesos de desarrollo independientes y métodos de despliegue distintos. A continuación, se detalla el flujo de trabajo seguido en cada caso, junto con evidencia visual del resultado final.
Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue del sitio web estático.

### Despliegue del Landing Page
Para el despliegue del sitio web estático, usamos GitHub Pages por última vez. Esta es una herramienta que permite alojar sitios web estáticos directamente desde un repositorio de GitHub. A continuación, se detalla el proceso seguido para el despliegue del sitio web estático:

Se adjunta el enlace para acceder al sitio web estático desplegado:

* Partimos de la rama develop del repositorio del sitio web estático con todos los cambios realizados para este sprint.
<p align="center">
  <img src="https://i.imgur.com/T7oPQGS.png"/>
</p>

* Luego, enviamos todos los cambios realizados en este segundo sprint desde la rama de desarrollo a una nueva rama de tipo release "release/landing-page-v4.0". Desde esa rama, se realizará el último despliegue del sitio web estático.
<p align="center">
  <img src="https://i.imgur.com/fwPFFrn.png"/>
</p>

* A continuación, nos dirigimos a la sección de Configuración del repositorio (Settings). Luego, accedemos a la opción de páginas (Pages) dentro del bloque de secciones de código y automatización (Code and automation).
<p align="center">
  <img src="https://i.imgur.com/0TJGzpU.png"/>
</p>

* Después, elegimos el tipo de origen para que despliegue desde una rama que escojamos. Luego, buscamos la rama de lanzamiento que hemos creado para realizar el despliegue de esta versión y guardamos la configuración.
<p align="center">
  <img src="https://i.imgur.com/kiVhLH4.png"/>
</p>

* A continuación, aparecerá el enlace público generado para poder acceder al sitio web estático desplegado.
<p align="center">
  <img src="https://i.imgur.com/iWq4Sm3.png"/>
</p>

* Finalmente, se accede el sitio web desplegado gracias a GitHub Pages y se adjunta la siguiente evidencia.
<p align="center">
  <img src="https://i.imgur.com/TWaTaot.png"/>
</p>

### Despliegue de la Aplicación Frontend
Para el despliegue de esta aplicación, se utilizó Firebase Hosting, una plataforma que permite alojar aplicaciones web de manera sencilla y eficiente.
Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue de la aplicación Frontend:

Se adjunta el enlace a la aplicación frontend desplegada: https://stocksip-od-app.web.app/sign-in

* Partimos de la rama develop del repositorio de la aplicación frontend con todos los cambios realizados para el sprint actual.
<p align="center">
  <img src="https://i.imgur.com/ZVkeCUj.png"/>
</p>

* Luego, enviamos todos los cambios realizados en este último sprint desde la rama de desarrollo a una nueva rama de tipo release. Desde esa rama, se realizará el tercer y último despliegue de la aplicación front-end.
<p align="center">
  <img src="https://i.imgur.com/foaO8rj.png"/>
</p>

* Luego, ejecutamos el comando npm run build en la consola de nuestro proyecto. Este comando actualizará la carpeta Dist que había sido creada para el despliegue anterior.
<p align="center">
  <img src="https://i.imgur.com/kuCErf7.png" alt="Execution of npm run build command">

<p align="center">
  <img src="https://i.imgur.com/qwP3yJb.png" alt="Creation of the dist folder">

* Luego, en la consola ingresamos el comando "firebase login" y decimos NO. Luego, nos solicitará que ingresemos con nuestra cuenta de Google con la que creamos el proyecto.
<p align="center">
  <img src="https://i.imgur.com/kyQfbBW.png"> 

* A continuación, se nos muestra una pantalla de inicio de sesión exitoso, lo que significa que hemos realizado correcto el anterior paso.
<p align="center">
  <img src="https://i.imgur.com/K6nvtaP.png">

* A continuación, ingresamos el comando firebase deploy, pero antes de eso ingresamos el comando npm run build para construir una nueva versión del proyecto con todos los últimos cambios.
<p align="center">
  <img src="https://i.imgur.com/i44OUm2.png"> 

* Luego, ingresamos con el enlace que nos proporciona y podremos visualizar el proyecto desplegado
<p align="center">
  <img src="https://i.imgur.com/Zk0LuFl.png">

#### Despliegue del Back End
Para el despliegue de esta aplicación, se utilizó Render, una plataforma que permite desplegar aplicaciones web de manera sencilla y eficiente que ayuda con el despliegue cada que se realizan cambios al repositorio.
Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue de la aplicación Backend:

Se adjunta el enlace a la aplicación backend desplegada: https://stocksip-back-end-application.onrender.com/swagger-ui/index.html

* Partimos de la rama develop del repositorio de la aplicación backend con todos los cambios realizados para el sprint actual.
<p align="center">
  <img src="https://i.imgur.com/Gyi4ybF.png"/>
</p>

* A continuación, creamos la rama release para realizar el despliegue.
<p align="center">
  <img src="https://i.imgur.com/rl0uFir.png" 
  alt="Release branch created"/>
</p>

* A continuación, nos dirigimos a la página de freesqldatabase para poder desplegar nuestra base de datos 
<p align="center">
  <img src="https://i.imgur.com/QOpwA6D.png">

* Luego, nos dirigimos a iniciar el proceso de despliegue de la aplicación backend. En la siguiente imagen, se visualiza la consola de RENDER donde realizamos el despliegue.
<p align="center">
  <img src="https://i.imgur.com/VnMrlTd.png">

* Se visualiza un despliegue exitoso de nuestra aplicación.
<p align="center">
  <img src="https://i.imgur.com/8lZx9pb.png"/>
</p>

<p align="center">
  <img src="https://i.imgur.com/PxjwQee.png"/>
</p>

* Ingresaremos a la página web de Render, ingresamos con nuestra cuenta, importamos nuestro repositorio, asignamos la rama en la que se realizara el deploy y confirmamos el despliegue, esperamos a que la propia página verifique el deploy y nos entregue una URL publica.
<p align="center">
  <img src="https://i.imgur.com/02heKNc.png"> 
<p align="center">
  <img src="https://i.imgur.com/3QF2uQu.png">
<p align="center">
  <img src="https://i.imgur.com/wowQCCl.png"> 

* Finalmente, ingresamos a la URL pública que nos proporcionó Render y podemos verificar que se logró el despliegue de nuestra aplicación Backend.
<p align="center">
  <img src="https://i.imgur.com/eAzqAkd.png"> 


#### 5.2.4.8. Team Collaboration Insights during Sprint
En esta sección se detalla cómo se llevaron a cabo las actividades de implementación durante el sprint, así como un resumen de las labores realizadas por cada miembro del equipo para el cumplimiento completo de la entrega relacionada a este sprint.

A continuation, se detallará el trabajo que realizo cada integrante del equipo para cada producto avanzado en este sprint:

### Landing Page ###

- El integrante Martín Gonzales formó parte de la grabación del último vídeo sobre el equipo.
- La integrante Camila Huamani mejoró las secciones about the product y about the team en la landing page y formó parte de la grabación del vídeo sobre el equipo.
- El integrante Farid Coronel formó parte de la última grabación del vídeo sobre el equipo.
- El integrante Nicolas Juarez formó parte de la grabación definitiva del vídeo sobre el equipo y reorganizó la estructura de los archivos del sitio web de negocio.

A continuación, se adjunta el gráfico con la cantidad de commits realizados por cada integrante del equipo durante este sprint para el desarrollo de la última versión del sitio web de negocio. Cada barra indica la cantidad de commits realizados en cada rama, reflejando el progreso del equipo en el desarrollo de las actualizaciones de las secciones del sitio web.
<p align="center">
  <img src="https://i.imgur.com/3B3zlvd.png"/>
</p>

También, se adjunta el gráfico del avance realizado por cada rama de funcionalidades por el equipo en la Landing Page. En este gráfico se puede observar el flujo de desarrollo del sitio web estático, donde las ramas que se desarrollaron fueron las relacionadas a las secciones que contienen los vídeos acerca del equipo de desarrollo y del producto.
<p align="center">
  <img src="https://i.imgur.com/qF08116.png"/>
</p>

### Aplicación Frontend ###

- El integrante Martín Gonzales fue responsable de implementar el consumo de servicios web para las guías de conservación, alertas y salidas de productos.
- La integrante Camila Huamani implementó el consumo de servicios web para las secciones de órdenes de compra, catálogos, autenticación y perfiles.
- El integrante Farid Coronel fue responsable de implementar el consumo de servicios web para las secciones de productos y almacenes.
- El integrante Sergio Julca fue responsable de implementar las secciones de inventarios y productos.
- El integrante Nicolas Juarez fue responsable de implementar el consumo de servicios web para los productos de la aplicación.

También, se adjunta el gráfico del avance realizado por cada rama de funcionalidades por el equipo en la aplicación front end. Este gráfico indica el flujo de desarrollo de la aplicación, donde cada rama representa una funcionalidad específica que se implementó durante el sprint para la aplicación frontend principalmente la implementación del consumo de servicios web y autenticación de usuarios.
<p align="center">
  <img src="https://i.imgur.com/A73aRUf.png" width=500/>
</p>

### Aplicación Backend ###

- El integrante Martín Gonzalez realizó correcciones en los respectivos endpoints para las alertas en el bounded context "Alertas Y Notifications."
- La integrante Camila Huamani se encargó de completar los endpoints para órdenes de compra y catálogos.
- El integrante Farid Coronel se encargó de realizar correcciones en los respectivos endpoints para esta sección en la aplicación Backend. Además, implementó los endpoints para la creación de cuentas y suscripciones para la aplicación.
- El integrante Nicolas Juarez completó los endpoints de perfiles y usuarios teniendo en cuenta el contexto de autenticación y creación de usuarios para la aplicación.

A continuación, se muestra el siguiente gráfico que detalla la cantidad de commits realizados por cada miembro durante este sprint. El gráfico detalla el aporte realizado por cada integrante del equipo para el avance de la última versión de la aplicación backend.
<p align="center">
  <img src="https://i.imgur.com/nnu434v.png"/>
</p>

También, se adjunta el gráfico del avance realizado por cada rama de funcionalidades por el equipo en la aplicación backend. Este gráfico indica el flujo de desarrollo de la aplicación, donde cada rama representa una funcionalidad específica que se implementó durante el sprint para la aplicación backend, entre ellas se incluye endpoints para características como órdenes de compra, catálogos, perfiles, usuarios y suscripciones.
<p align="center">
  <img src="https://i.imgur.com/A73aRUf.png" width=500/>
</p>

### Reflexión del equipo ###
Finalmente, se realizó una reflexión del equipo sobre el sprint, donde se destacó la importancia de la colaboración y la comunicación constante entre los miembros. Se identificaron áreas de mejora en la planificación y ejecución de tareas, así como la necesidad de realizar pruebas más exhaustivas antes de cada entrega. El equipo también valoró positivamente el uso de herramientas como GitHub para el control de versiones y la gestión de tareas, lo que facilitó el seguimiento del progreso y la resolución de conflictos.
El equipo valora este avance final como un determinante para la finalización del proyecto, destacando la importancia de la integración de todas las funcionalidades desarrolladas hasta el momento. Se reconoce que aún se pueden implementar funcionalidades más útiles, pero se siente confianza en que el proyecto ha cumplido con su propósito al cumplir con los objetivos establecidos.



## 5.3. Validation Interviews

### 5.3.1. Diseño de entrevistas

En las entrevistas de validación se incluirá:

- **Exploración de la Landing Page:**
    
    - ¿Comprendieron el propósito de la aplicación?
        
    - ¿Fue clara la propuesta de valor?
        
- **Validación de la Aplicación Web:**
    
    - Se validarán las funcionalidades clave según el flujo de cada user goal.
        
    - Se observarán comportamientos, puntos de confusión, y reacciones espontáneas.
        
- **Registro de métricas cualitativas y cuantitativas:**
        
    - Nivel de comprensión (autoevaluación del usuario).
        
    - Comentarios de usabilidad y experiencia.
        
    - Satisfacción con el flujo (escala del 1 al 5).
	
- **Flujos a Desarrollar:**

| **User Goal** | **Descripción del Flujo**                                                                                                 | **Objetivo de Validación**                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| **UG 1**      | El usuario accede al Landing Page, se registra con sus datos, y se le asigna un plan gratuito.                            | Validar claridad del formulario de registro y comprensión del plan gratuito. |
| **UG 2**      | El usuario inicia sesión con su cuenta y selecciona plan premium si aplica.                                               | Validar facilidad de login y claridad en elección de plan.                   |
| **UG 4**      | Desde el dashboard, el licorero accede fácilmente a la sección de inventario.                                             | Confirmar acceso intuitivo al inventario desde cualquier punto.              |
| **UG 5**      | El licorero accede al inventario, agrega un nuevo producto llenando el formulario, y el producto se asocia correctamente. | Validar comprensión y facilidad del formulario de producto.                  |
| **UG 8**      | El licorero navega desde cualquier parte a la sección Reportes utilizando el icono correspondiente.                       | Verificar navegación clara y sin fricción hacia reportes.                    |
| **UG 9**      | Desde la sección Reportes, el licorero crea un nuevo reporte llenando los datos solicitados.                              | Validar flujo lógico y claridad de campos al generar reportes.               |
| **UG 11**     | El licorero crea una nueva orden de compra: elige productos, cantidad y proveedor. Luego la envía.                        | Verificar fluidez del proceso y facilidad para seleccionar y enviar pedidos. |
| **UG 12**     | El proveedor accede a la sección de Conservación, genera una nueva guía completando datos, y la visualiza.                | Validar comprensión del proceso de creación de guías de conservación.        |

### 5.3.2. Registro de entrevistas

**Entrevista 1**

| Entrevista                                                         | Registro                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p align="center"><img src="https://i.imgur.com/fJEnnVU.png"/></p> | **Distrito:** Villa el Salvador<br>**Entrevistado:** Erick Coronel                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Link](https://acortar.link/8Nl8Ms)                                | **Entrevistador:** Farid Sebastian Coronel Espinoza                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Timing: Minuto 00:06-15:30                                         | **Resumen:** La entrevista se realizo a Erick Coronel, de 59 años, con el fin de validar dos productos de software enfocados en empresas de licores. La evaluación se centró en la landing page, el flujo de navegación, claridad de contenido y funcionalidad de las secciones clave (planes, testimonios, dashboard, almacenes, alertas, perfil y reportes). Erick valoró positivamente la estructura general del sitio, destacando la claridad de los testimonios, los beneficios de los planes y el seguimiento en tiempo real de inventario. Mencionó que sería conveniente aumentar ligeramente el tamaño de la fuente para una mejor legibilidad. También sugirió que la opción multilingüe (español-inglés) debería estar disponible en todas las secciones, ya que el contenido en inglés no siempre resulta accesible. Apreció los iconos y accesos rápidos del dashboard, considerándolos intuitivos. Opinó que la sección de almacenes es clara, aunque recomendó incluir más visibilidad de ciertos datos como precio y cantidad por botella. Consideró que las alertas de productos próximos a vencer y de bajo stock son funcionales y útiles para la toma de decisiones. Respecto al registro y perfil, destacó que el diseño es amigable y los colores ayudan a guiar el proceso. También le pareció útil incluir redes sociales en el perfil. Finalmente, evaluó como clara y precisa la sección de reportes, indicando que no requiere mejoras importantes en su diseño o ubicación. Satisfaccion de flujo: 4.5/5|

**Entrevista 2**

| Entrevista                                                         | Registro                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p align="center"><img src="https://i.imgur.com/B0hSLHp.png"/></p> | **Distrito:** Chorrillos<br>**Entrevistado:** Luis Alfonzo Jimenez                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [Link](https://acortar.link/8Nl8Ms)                                | **Entrevistador:** Camila Victoria Huamani Cruz                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Timing: Minuto 15:40-28:04                                         | **Resumen:** La entrevista se realizo a Luis Alfonzo Jimenez, de 55 años, participó en la validación de la aplicación Stock, diseñada para la gestión de inventario en licorerías. Durante la prueba, creó una cuenta, seleccionó su rol como dueño de licorería, y accedió sin problemas al dashboard, el cual le permitió visualizar ventas, productos en stock y alertas relevantes. Exploró la sección de almacenamiento, donde creó un producto nuevo ingresando datos como tipo de licor, marca, precio e imagen. También navegó por la sección de reportes y generó una guía de conservación, configurando temperatura, duración del producto abierto y comentarios útiles para sus trabajadores. Luis continuó creando una orden de compra desde la sección correspondiente, seleccionando productos del catálogo y asignando un proveedor. Finalmente, accedió al perfil para modificar su información personal, revisar su rol y consultar los beneficios del plan premium. En su opinión, la aplicación es muy amigable, clara y sencilla de manejar. Destacó como funcionalidad clave la gestión del stock mínimo y la emisión de alertas, que considera fundamentales para tomar decisiones de reposición, sobre todo en fechas críticas como fines de semana. Valoró positivamente la estructura general de la app, aunque aclaró que un mayor uso permitiría familiarizarse aún más con ella. Satisfaccion de flujo: 4.8/5| 
**Entrevista 3**

| Entrevista                                                         | Registro                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p align="center"><img src="https://i.imgur.com/AshFnYN.png"/></p> | **Distrito:** Villa el Salvador<br>**Entrevistado:** Brayner Coronel                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [Link](https://acortar.link/8Nl8Ms)                                | **Entrevistador:** Farid Sebastian Coronel Espinoza                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Timing: Minuto 28:06-41:29                                         | **Resumen:** La entrevista se realizo a Brayner Coronel, de 28 años, participó en la entrevista de validación de nuestra aplicacion. Se evaluó principalmente el flujo de navegación y la experiencia visual en la landing page y distintas secciones del sistema. Brayner destacó positivamente la estructura de la landing page, valorando la inclusión de testimonios, preguntas frecuentes, soporte bilingüe (español e inglés) y planes diferenciados (gratuito y premium). Considera que estos elementos ayudan al visitante a orientarse, confiar en el servicio y tomar decisiones. Sugirió que los nombres en los almacenes podrían omitir palabras redundantes como "vino" si ya están en el contexto de un almacén de vinos, para mejorar la visualización. Respecto al diseño, valoró los colores y la organización visual de las secciones. Le pareció comprensible la navegación mediante iconos en la barra lateral, considerando que estos son suficientemente descriptivos. También resaltó como útil la funcionalidad de selección de roles al registrarse, el perfil de usuario editable, y la posibilidad de cambiar idioma fácilmente. En cuanto al inventario, consideró clara la visualización de productos, imágenes, precio, stock y capacidad de edición o creación de nuevos ítems. En la sección de reportes, entendió correctamente las distintas funciones: pérdidas, transportes, reposiciones y conservación. Opinó que los reportes son fáciles de navegar y bien segmentados. Finalmente, destacó la utilidad de las alertas por productos próximos a vencer o con stock crítico, y sugirió que algunos accesos clave, como los catálogos y pedidos, deberían estar disponibles desde accesos rápidos para agilizar la interacción. Satisfaccion de flujo: 4.7/5|


### 5.3.3. Evaluación según heurísticas

##### APP A EVALUAR: **StockSip**
---

##### TAREAS A EVALUAR:

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Registro de un usuario nuevo  
2. Inicio de sesión de un usuario
3. Creación de un almacén
4. Visualización de las alertas de la aplicación
5. Visualización de almacenes creados
6. Insertar una imagen a un almacén
7. Carga de alertas en la aplicación
8. Realización de una orden de compra

**No están incluidas en esta versión de la evaluación las siguientes tareas:**

1. Asignar un producto a un inventario
2. Registrar salidas de productos
3. Proceso de adquisición de una membresía
4. Registrar reportes de pérdidas

---

##### ESCALA DE SEVERIDAD:

| Nivel | Descripción                                                                                                                                                                                     |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.                    |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante que sea corregido y se le debe asignar una prioridad alta.                                     |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                               |

---

##### TABLA RESUMEN

| #   | Problema                                                                                                | Escala de severidad | Heurística/Principio violado                                                        |
| --- | ------------------------------------------------------------------------------------------------------- | ------------------- | ----------------------------------------------------------------------------------- |
| 1   | Faltan validaciones visibles para los campos (ej: email inválido) en el formulario de inicio de sesión. | 3                   | Usability: Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores |
| 2   | Faltan validaciones para no permitir contraseñas inseguras.                                             | 2                   | Usability: Prevención de errores                                                    |
| 3   | No se muestra mensaje de error al usuario si la carga de una imagen falla al crear un almacén.          | 3                   | Usability: Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores |
| 4   | No hay paginación ni scroll controlado para muchos almacenes                                            | 1                   | Information Architecture: Is it scalable?                                           |
| 5   | No hay búsqueda ni filtros para listas largas                                                           | 1                   | Information Architecture: Is it findable?                                           |
| 6   | Texto de error poco informativo y no contextualizado cuando fallan en cargar las alertas                | 2                   | Usability: Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores |
| 7   | La jerarquía visual no destaca adecuadamente alertas críticas                                           | 1                   | Usability: Estética y diseño minimalista                                            |

---

##### DESCRIPCIÓN DE PROBLEMAS

###### PROBLEMA #1: Faltan validaciones para asegurar que un usuario agregue un correo electronico correctamente.

**Severidad:** 3  
**Heurística violada:** Usability - Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores

**Descripción:**  
Si el usuario pone un correo inválido con cualquier palabras después del símbolo (@), no hay mensajes visuales de error.

<p align="center">
  <img src="https://i.imgur.com/h2gIADr.png">
</p>

**Recomendación:**  
Agregar validaciones básicas con mensajes claros, donde se validan correos reales con las palabras "gmail, hotmail, etc."

###### PROBLEMA #2: No hay una validación para contraseñas seguras.

**Severidad:** 2  
**Heurística violada:** Usability - Prevención de errores

**Descripción:**  
Un usuario se puede registrar con contraseñas cuya longitud sea menor de 8 caracteres, sin símbolos o números, lo que no previene errores de seguridad.

<p align="center">
  <img src="https://i.imgur.com/e7dY6mI.png">
</p>

**Recomendación:**  
Agregar validaciones básicas para que los usuarios creen contraseñas con más de 8 caracteres, letras mayúsculas y símbolos.

###### PROBLEMA #3: No hay comunicación visible del error al crear un nuevo almacén

**Severidad:** 3  
**Heurística violada:** Usability - Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores.

**Descripción:**  
Aunque se asigna un error cuando no se puede crear un nuevo almacén, este error **no se muestra en el la pantalla del usuario**. El usuario no sabe qué ocurrió.

<p align="center">
  <img src="https://i.imgur.com/qUhkUh9.png">
</p>

**Recomendación:**  
Agregar un componente que muestre el error cuando no se pudo crear un nuevo almacén.

###### PROBLEMA #4: No hay un control que permita regresar a la tienda durante el trámite de compra  

**Severidad:** 1  
**Heurística violada:** Information Architecture: Is it scalable?

**Descripción:**  
Si hay muchos almacenes, no hay mecanismos para manejar la cantidad de elementos (paginación, scroll infinito, scroll virtual).

<p align="center">
  <img src="https://i.imgur.com/Ky4KlN4.png">
</p>

**Recomendación:**  
Agregar soporte para paginación o carga por lotes, o bien un scroll con carga perezosa.

###### PROBLEMA #5: No hay opción de búsqueda o filtrado de almacenes

**Severidad:** 1  
**Heurística violada:** Information Architecture: Is it findable?

**Descripción:**  
Si la lista de almacenes crece, el usuario no tiene cómo buscar por nombre de almacén.

<p align="center">
  <img src="https://i.imgur.com/z2fRhTV.png">
</p>

**Recomendación:**  
Agregar un buscador o filtro en la parte superior de la sección de almacenes.

###### PROBLEMA #6: Texto de error poco informativo y no contextualizado

**Severidad:** 2  
**Heurística violada:** Usability: Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores

**Descripción:**  
los mensajes presentes no brindan detalles útiles ni opciones para volver a intentar.

<p align="center">
  <img src="https://i.imgur.com/qVwEGzl.png">
</p>

**Recomendación:**  
Mostrar mensaje más útil e interactivo: "No se pudieron cargar las alertas. Verifica tu conexión e intenta nuevamente."

###### PROBLEMA #7: Falta jerarquía visual en alertas críticas

**Severidad:** 1  
**Heurística violada:** Usability: Estética y diseño minimalista

**Descripción:**  
Las alertas críticas como “Urgent Repositioning” no destacan visualmente frente a otras.

<p align="center">
  <img src="https://i.imgur.com/KT1j1y0.png">
</p>

**Recomendación:**  
Usar color de fondo, bordes o íconos para distinguir prioridades.

## 5.4. Video About The Product
En esta sección, se adjunta el enlace al video sobre el producto de software desarrollado. En este video, se detallan funcionalidades principales y beneficios que ofrece la aplicacion a los usuarios finales que usaran la aplicacion web para sus negocios.

Enlace al video acerca del producto: [https://acortar.link/dnNGV5](https://acortar.link/dnNGV5)

<p align="center">
  <img src="https://i.imgur.com/eM34Itk.png">
</p>

## 5.5. Video About The Team

En esta sección, se adjunta el enlace al video que presenta al equipo de trabajo que desarrolló el producto de software. En este video, cada miembro del equipo comparte su rol y contribuciones al proyecto, destacando la colaboración y el esfuerzo conjunto para crear una solución efectiva.

Enlace al video acerca del equipo de trabajo que desarrollo el producto de software: [https://acortar.link/omYKFj](https://acortar.link/omYKFj)

<p align="center">
  <img src="https://i.imgur.com/x1CrLdb.png">
</p>

