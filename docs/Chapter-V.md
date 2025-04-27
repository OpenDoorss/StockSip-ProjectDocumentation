# Capítulo 5: Product Implementation, Validation & Deployment #

## _5.1. Software Configuration Management_ ##

### 5.1.1. Software Development Environment Configuration ###

### 5.1.2. Source Code Management ###

### 5.1.3. Source Code Style Guide & Conventions ###

### 5.1.4. Software Deployment Configuration ###

## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

### 5.2.1.1. Sprint Planning 1 ###

| Sprint #                                     | Sprint 1                                               |
|----------------------------------------------|--------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                     |
| Date                                         | 2025/04/20                                             |
| Time                                         | 03:30 PM                                               |
| Location                                     | Reunión mediante llamada virtual en Discord            |
| Prepared By                                  | Huamani Cruz, Camila Victoria                          |
| Attendees                                    | Huamani Cruz, Camila Victoria / Juarez Leon, Nicolas Emilio Walter / Gonzales Castillo, Angel Martin / Diaz Quispe, Matias Sebastian / Coronel Espinoza, Farid Sebastian |
| <b> Sprint Goal & User Stories </b>          | --                                                     |
| Sprint 1 Goal                                | <b> Our focus </b> is on develop and deploy the first version of the landing page <br> <b> We believe it delivers </b> a first view of what our product offers to our target segments <br> <b> This will be confirmed when </b> the target segments are visiting the site and can see and know the benefits on using our product. |
| Sprint 1 Velocity                            | 25                                                     |
| Sum of Story Points                          | 21                                                     |

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

<p align="center">
  <img src="../img/Chapter V/sprint_backlog.png" 
  alt="sprint_backlog_1"/>

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este primer sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 1     | Sprint Backlog 1                                              |     |                                         |                                                                                                            |                    |                |            |
|--------------|---------------------------------------------------------------|-----|-----------------------------------------|------------------------------------------------------------------------------------------------------------|--------------------|----------------|------------|
| User Stories |                                                               | Work Item/Task                                |                                                                                                            |                    |                |            |
| Id           | Title                                                         | Id  | Title                                   | Description                                                                                                | Estimation (Hours) | Assigned to    | Status     |
| US001        | Ver propuesta de valor clara                                  | 001 | Diseñar sección inicio                  | Diseñar el encabezado con logo, menú de navegación y sección principal.                                    | 0.5                | Camila Huamani | Done       |
|              |                                                               | 002 | Estructura principal de la página       | Crear la estructura principal de la página en HTML y los estilos iniciales en CSS.                         | 0.5                | Camila Huamani | Done       |
|              |                                                               | 003 | Diseñar sección contacto                | Diseñar el pie de página con información de contacto y enlaces a otras secciones                           | 0.5                | Camila Huamani | Done       |
|              |                                                               | 004 | Describir visión y misión               | Agregar espacios que detallen la misión y visión de la empresa.                                            | 0.5                | Camila Huamani | Done       |
|              |                                                               | 005 | Añadir estilos                          | Estilizar las secciones de contacto e inicio para que sean visiblemente agradables y llamativas.           | 0.5                | Camila Huamani | Done       |
| US002        | Acceder a explicación detallada sobre el uso de la aplicación | 001 | Añadir sección de cómo funciona         | Separar una sección de la estructura general para agregar el contenido de explicación de cómo funciona la aplicación. | 0.3     | Martin Gonzales| Done      |
|              |                                                               | 002 | Descripción de funcionalidades          | Resumir cada funcionalidad que podrá utilizar cada segmento objetivo.                                      | 0.4                | Martin Gonzales| Done      |
|              |                                                               | 003 | Añadir imágenes referenciales           | Para cada funcionalidad detallada, agregar una imágen referencial.                                         | 0.5                | Martin Gonzales| Done      |
|              |                                                               | 004 | Agrupar y ordenar imagenes y descripcion| Ordenar y organizar cada funcionalidad descrita con su imagen.                                             | 0.4                | Martin Gonzales| Done      |
|              |                                                               | 005 | Añadir estilos                          | Usando CSS, añadir estilos a esta sección para que sea visiblemente llamativa.                             | 0.6                | Martin Gonzales| Done      |
| US003        | Ver beneficios para licorerías	                               | 001 | Implementar sección beneficios          | Diseñar la subsección de beneficios para dueños de licorerías agregando tarjetas con listas de beneficios. | 0.6                | Farid Coronel  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes               | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | Done      |
|              |                                                               | 003 | Añadir estilos                          | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | Done      |
| US004        | Ver beneficios para proveedores                               | 001 | Implementar sección beneficios          | Diseñar la subsección de beneficios para proveedores agregando tarjetas con listas de beneficios.          | 0.6                | Farid Coronel  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes               | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Farid Coronel  | Done      |
|              |                                                               | 003 | Añadir estilos                          | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Farid Coronel  | Done      |    
| US006        | Leer testimonios de clientes		                               | 001 | Añadir sección para testimonios         | Usando HTML, separar una sección para colocar todo el contenido de esta sección.                           | 0.5                | Nicolas Juarez | Done      |
|              |                                                               | 002 | Redactar testimonios ideales            | Redacatar uno o varios testimonios para cada segmento objetivo que den su opinión sobre la aplicación.     | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 003 | Añadir espacios para cada testimonio    | Crear tarjetas en la estructura. Estas tarjetas contendrán el texto del testimonio.                        | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 004 | Añadir imágenes referenciales           | Agregar al lado del texto, una imagen referencial de la persona que está dando su testimonio.              | 0.4                | Nicolas Juarez | Done      |
|              |                                                               | 005 | Añadir estilos                          | Agregar estilos a la sección usando CSS.                                                                   | 0.6                | Nicolas Juarez | Done      |
| US007        | Comparar planes gratis y premium	                             | 001 | Añadir sección de planes                | Diseñar la sección de planes con tarjetas que detallen las características de cada plan.                   | 0.5                | Matias Diaz    | Done      |
|              |                                                               | 002 | Añadir información para ambos segmentos | Añadir texto diferenciando funcionalidades que incluye el plan para cada segmento objetivo.                | 0.6                | Matias Diaz    | Done      |
|              |                                                               | 003 | Agregar texto comparativo               | Añadir texto en las tarjetas que pueda ser utilizado para saber qué contiene el plan premium.              | 0.6                | Matias Diaz    | Done      |
|              |                                                               | 004 | Añadir íconos                           | Añadir íconos relacionados a lo que ofrece cada plan para cada segmento objetivo.                          | 0.6                | Matias Diaz    | Done      |  
|              |                                                               | 005 | Añadir estilos                          | Estilizar la sección usando CSS.                                                                           | 0.5                | Matias Diaz    | Done      |
| US008        | Conocer el precio y condiciones	                             | 001 | Añadir espacio para precios             | En la sección de planes, agregar un recuadro que indique el precio para cada plan                          | 0.3                | Matias Diaz    | Done      |
|              |                                                               | 002 | Añadir estilos                          | Estilizar los recuadros para precios usando CSS.                                                           | 0.3                | Matias Diaz    | Done      |


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
El objetivo de este sprint fue realizar, en colaboracion con todo el equipo, la creacion del landing page.

<p align="center">
  <img src="https://i.imgur.com/RM5QuV9.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/l6XxVmI.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/Rdp57BN.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/FsUQGMa.png"/>
</p>
<p align="center">
  <img src="https://i.imgur.com/wR7L77j.png"/>
</p>

### 5.2.1.7. Software Deployment Evidence for Sprint Review ###
La organizacion de nuestro codigo se realizo en un repositorio en GitHub. Para el despliegue del landing page se utilizo GitHub Pages
* Primero se creo un repositorio para alojar el codigo del landing page
* Segundo, cada integrante del equipo creo una rama de cada funcion del landing page
<p align="center">
  <img src="https://i.imgur.com/WLeViFN.png"/>
</p>

* Tercero, se realizo el merge a develop para corregir errores
* Cuarto, cuando se corrigieron los errores, se realizo merge al master
* Quinto, se desplego el landing page mediante GitHub Pages, evidencia:
<p align="center">
  <img src="https://i.imgur.com/RM5QuV9.png"/>
</p>

### 5.2.1.8. Team Collaboration Insights durint Sprint ###
El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:
<p align="center">
  <img src="https://i.imgur.com/7mo7SJU.png"/>
</p>

Commits de los integrantes en el Landing Page:
<p align="center">
  <img src="https://i.imgur.com/xaO8mjo.png"/>
</p>

Grafico de los push y merge realizados por el equipo:
<p align="center">
  <img src="https://i.imgur.com/vBY3Ne2.png"/>
</p>
