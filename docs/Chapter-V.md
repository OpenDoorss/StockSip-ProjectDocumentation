# Capítulo 5: Product Implementation, Validation & Deployment #

## _5.1. Software Configuration Management_ ##

### 5.1.1. Software Development Environment Configuration ###

* **Project Management**

  En el aspecto de gestión y desarrollo del ciclo de vida del proyecto se utilizó la aplicación Discord y Google Meet para las reuniones de grupo en las cuales se conversan sobre temas relacionados a avances y corrección de aspectos del proyecto. Luego, para la documentación del proyecto, se utilizó el formato MarkDown

* **Requirements Management**

  Para el manejo de los requisitos (historias de usuario, product backlog, sprint backlog), se utilizó Trello es una herramienta ideal para gestionar proyectos. Usando esta herramienta, se puede organizar un product backlog, ya que permite estructurar tareas visualmente en un tablero. Puedes crear listas que representen etapas del flujo de trabajo, y en cada lista añadir tarjetas que describan las user stories o tareas individuales. Estas tarjetas permiten detallar información clave, como prioridades, etiquetas de color, descripciones y checklists, facilitando así el seguimiento y la colaboración del equipo.

* **Product UX/UI Design**

  Para el desarrollo de plantillas de los User Persona  y del Impact Mapping se utilizó UXPressia. Es una plataforma especializada en la creación de mapas de experiencia del usuario ofreciendo una interfaz enfocada exclusivamente en UX que facilita la estructuración clara y profesional de estos elementos. Destaca por sus plantillas personalizables, la posibilidad de añadir datos reales, imágenes y métricas, y por permitir la colaboración en tiempo real. Para la creación del Lean UX Canvas se utilizó la aplicación canva. Esta aplicación es una herramienta versátil para crear diversos diseños. Canva facilita la colaboración del equipo y la exportación de los proyectos en archivo PNG o PDF, manteniendo el proceso creativo ordenado y atractivo. Para los Journey Mapping, Empathy Mapping, entre otros mapas,  se decidió utilizar Miro. Esta aplicación permite una colaboración en tiempo real entre equipos, ofrece una interfaz visual e intuitiva, y cuenta con plantillas prediseñadas que agilizan el proceso sin perder calidad metodológica.

  Luego, para el desarrollo de wireframes, mockups y prototipos de aplicación, se decidió utilizar Figma. Esta es una herramienta que facilita el diseño de interfaces, permitiéndonos trabajar con colores, imágenes, formas, y otros elementos visuales para crear nuestra aplicación. Nos ofrece la posibilidad de probar diversos modelos de dispositivos. Además, esta plataforma será clave en la creación de nuestro prototipo, ya que brinda una simulación interactiva que permite visualizar y experimentar el proyecto desde la perspectiva del usuario.


* **Software Development**

  Para el desarrollo del Software correspondiente al Landing Page, se utilizarán dos aplicaciones, las cuales son GitHub y JetBrains. La primera ayuda al equipo a gestionar de manera correcta los avances colaborativos del proyecto. Por otro lado, JetBrains ayudará a trabajar el proyecto con lenguajes como HTML5, CSS y JavaScript.
  Para el desarrollo del Frontend Web Application, se utilizaron las aplicaciones de Github y WebStorm. Github nos ayuda a gestionar la documentacion correcta de los avances que realizan los miembros del equipo. Mientras que WebStorm es el programa en el que se codifica nuestra aplicacion Frontend usando los lenguajes HTML5, CSS y Typescript, asi mismo se utilizo el framework de Angular.

* **Software Testing**

  Las pruebas del Landing Page y del Frontend se realizarán mediante uso del navegador web para verificar que el diseño del mismo cumple con aspectos como el diseño responsivo en cualquier dispositivo desde el que se acceda al landing page y al frontend del proyecto. Además, para visualizar que se han implementado correctamente elementos visuales que deben aparecer en las distintas secciones de la página.

  Las pruebas del frontend se realizaron utilizando una fake API mediante JSON Server, que funcionó como una base de datos temporal para validar el correcto funcionamiento de las interfaces y las interacciones con los datos.

* **Software Deployment**

  Para el despliegue del Landing page se uso la el servicio web de github pages, este servicio se especializa en el despliegue de sitios web staticos directamente desde un repositorio.
  Para el despliegue del Frontend se uso beeceptor y firebase. Beeceptor es una herramienta en línea (basada en la web) que nos permite crear endpoints HTTP falsos (mock) para probar APIs, se uso ver qué datos está enviando nuestra aplicación. Firebase es una plataforma desarrollada por Google que permite crear aplicaciones web y móviles más rápido, sin tener que construir un backend completo desde cero, ofrece servicios listos para usar que se pueden usar para conectar facilmente nuestro Frontend.
  

### 5.1.2. Source Code Management ###

En esta sección, se describen los medios y esquemas de organización para gestionar de manera efectiva los archivos de proyecto relacionados a Landing Page, Web Services y Frontend Web Applications. En el caso de los repositorios, se usará GitHub para almacenar los archivos. Además, se implementará GitFlow. Esta función de GitHub ayudará al equipo, gracias a las ramas de características de lanzamiento, a poder trabajar paralelamente en el proyecto y a tomar el control de versiones de avance del proyecto.

#### **5.1.2.1. Repositorios**

A continuación, se adjuntan los enlaces para acceder a los repositorios donde se almacenarán los archivos de proyecto relacionados al Landing Page.

* **Landing Page: [https://github.com/OpenDoorss/StockSip-LandingPage.git](https://github.com/OpenDoorss/StockSip-LandingPage.git)**
* **Frontend Web Applications: [https://github.com/OpenDoorss/stocksip-front-end-application.git](https://github.com/OpenDoorss/stocksip-front-end-application.git)**

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
  Para la codificación del proyecto en Angular, se utilizará el artículo *“Angular coding style guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Angular recomienda para escribir código en sus aplicaciones. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Angular.. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://v17.angular.io/guide/styleguide](https://angular.dev/style-guide)  
  Finalmente, se aplicará el contenido del artículo para el Frontend Applications de StockSip.  
    
* **Nomenclatura en Java:**  
  Para la codificación del proyecto en Java, se utilizará el artículo *“Google Java*   
  *Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Google sigue para escribir código en Java. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Google. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)  
  Finalmente, se aplicará el contenido del artículo para el apartado de Web Services de StockSip.


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

## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

### 5.2.1.1. Sprint Planning 1 ###

### 5.2.1.2. Aspect Leaders and Collaborators ###

### 5.2.1.3. Sprint Backlog 1 ###

### 5.2.1.4. Development Evidence for Sprint Review ###

### 5.2.1.5. Execution Evidence for Sprint Review ###

### 5.2.1.6. Services Documentation Evidence for Sprint Review ###

### 5.2.1.7. Software Deployment Evidence for Sprint Review ###

### 5.2.1.8. Team Collaboration Insights durint Sprint ###
