# Capítulo 4: Product Design #

## _4.1. Style Guidelines_ ##

### 4.1.1. General Style Guidelines ###

La propuesta visual de **StockSip** se basa en transmitir profesionalismo, accesibilidad y tecnología confiable para negocios que requieren control eficiente de su inventario, especialmente licorerías y proveedores. Las decisiones tomadas en cuanto a branding, tipografía, colores y espaciado buscan crear una experiencia clara, funcional y moderna, adecuada tanto para nuevos usuarios como para usuarios frecuentes del sistema.

**Branding**

-   "StockSip" se presenta como una marca moderna y profesional, enfocada en la gestión inteligente de licores.
    
-   El logotipo de StockSip combina elementos gráficos relacionados con licorería (como una copa estilizada o una botella minimalista) con una tipografía limpia, para reflejar sofisticación y control.
    
-   El uso de tonos cálidos oscuros (burdeos, dorado suave, marrones profundos) proyecta calidad, tradición y elegancia, en línea con el mundo de bebidas selectas.
    
-   La frase clave “stock management” debajo del logo refuerza el propósito de la herramienta y su enfoque en la eficiencia operativa.

<p align="center">
  <img src="https://i.imgur.com/AwKOYXI.png" 
  alt="logo-stocksip"/>

  > <p align="center">Logo de StockSip</p>
</p>
<br>

**Tipografía**

-   **Títulos**: “Poppins” — serif elegante, ideal para transmitir distinción y modernidad.
    
-   **Cuerpo de texto**: “Inter” — sans-serif moderna, clara y altamente legible.
    
-   **Botones y microtextos**: “Roboto Medium” — neutral y funcional, facilita la interacción en interfaces digitales.
    
-   **Elementos destacados** usan una variante "bold" o "semi-bold", asegurando énfasis sin sobrecargar visualmente.

<p align="center">
  <img src="https://i.imgur.com/M4bj10w.png" 
  alt="tipografias"/>

  > <p align="center">Tipografías elegidas</p>
</p>
<br>

**Colores**
<br>
Paleta principal:

<p align="center">
  <img src="https://i.imgur.com/q09Pywz.jpeg" 
  alt="logo-stocksip"/>

  > <p align="center">Paleta de colores de StockSip</p>
</p>

- Los tonos oscuros como el gris medio transmiten sofisticación y solidez, ideales para generar confianza.

- Los acentos vibrantes como el morado, el rojo y el magenta profundo aportan energía, personalidad y un toque moderno que destaca sin saturar.

- El tono claro equilibra la composición, proporcionando aire y claridad visual, lo cual mejora la legibilidad y la elegancia general del diseño.

- La armonía entre los neutros oscuros y los acentos cálidos crea una experiencia visual impactante, sofisticada y contemporánea.

**Espaciado**

-   Diseño moderno y minimalista, con énfasis en claridad visual.
    
-   Márgenes y “padding” van de 12px a 48px, adaptándose al dispositivo.
    
-   El contenido se organiza en secciones bien separadas, para facilitar el escaneo visual y la navegación intuitiva.
    
-   Se prioriza la jerarquía visual con suficiente espacio entre los elementos clave.
<br>

**Tono de la comunicación**
    
- **Serio pero accesible**: transmitimos confianza y precisión sin ser excesivamente técnicos.
    
- **Formal/Casual equilibrado**: nos dirigimos a usuarios emprendedores o gerentes de negocios, con un tono que mezcla profesionalismo y cercanía.
    
- **Respetuoso**: mantenemos un lenguaje claro y respetuoso, enfocado en resolver problemas del usuario.
    
- **Sereno con un toque entusiasta**: buscamos reflejar eficiencia con mensajes motivadores que inviten a la acción sin ser invasivos.
<br>

**Botones**

-   Formato rectangular con bordes ligeramente redondeados (8px).
    
-   Los botones tienen tamaños grandes y están bien espaciados, en pantallas de escritorio, su diseño y posicionamiento optimizan la interacción con el ratón.  

 <p align="center">
  <img src="https://i.imgur.com/93LE3LW.png" 
  alt="botones"/>

  > <p align="center">Botones elegidos</p>
</p>
<br>

**Patrón de diseño web:** 

- Se decidió utilizar el patrón de diseño web de tipo Z para el sitio web de la aplicación. Esta técnica mejora la experiencia del usuario al guiar su atención hacia los elementos claves más importantes que presenta la aplicación y maximizar la efectividad del contenido.


### 4.1.2. Web Style Guidelines ###

Esta sección define las pautas visuales y de interfaz para el desarrollo de la aplicación en Angular, utilizando **Angular Material** como librería principal de componentes. El enfoque está centrado en garantizar una experiencia consistente, accesible y optimizada para todos los usuarios, independientemente del dispositivo que utilicen.
<br>

**Responsive Design**

La interfaz de StockSip se adapta automáticamente gracias a **Angular Flex Layout** y el uso de breakpoints estándar para diseño responsive:

- `xs` ≤ 576px (móvil)  
- `sm` 577–768px (tablet)  
- `md` 769–1024px (laptop)  
- `lg` > 1024px (escritorio)

Las directivas `fxLayout`, `fxFlex`, `fxHide`, `fxShow` y sus variantes permiten estructurar la interfaz de forma fluida y adaptativa.
<br>

**Componentes y patrones compatibles**

- **Navbar/Menu:**  `<mat-toolbar>` junto con `<mat-menu>` o `mat-sidenav` para la navegación principal. Se integran con rutas usando `routerLink`.

- **Cards:** `<mat-card>` para contenedores de información como productos, alertas o resúmenes.

- **Botones:** `<button mat-button>`, `<button mat-icon-button>`, `<button mat-raised-button>` según el contexto, con íconos usando `<mat-icon>`.

- **Notificaciones y Diálogos:** `MatSnackBar` para mensajes de éxito, error o alerta; `MatDialog` para mostrar detalles o acciones contextuales. Todo esto se gestiona mediante inyección de servicios.
<br>

**Accesibilidad**

Todos los componentes siguen prácticas de accesibilidad:

- Angular Material incluye soporte integrado para `aria-*` en componentes relevantes.

- Navegación por teclado compatible (Tab, Enter, Space, Escape, etc.).

- Contraste visual conforme a la norma **WCAG 2.1 AA**.

- Tipografías y layouts adaptables mediante unidades relativas (`rem/em`), favoreciendo la escalabilidad en distintos dispositivos.

## _4.2. Information Architecture_ ##

### 4.2.1. Organization Systems ###

La organización jerárquica del Landing Page de "StockSip" ha sido diseñada con el propósito de guiar al usuario de manera lógica y efectiva desde su primer contacto con la solución hasta su conversión en cliente. Esta estructura responde a principios de arquitectura de la información que priorizan la claridad, la relevancia y la progresión natural del contenido, permitiendo que los usuarios comprendan de inmediato el valor del producto, cómo funciona, sus beneficios, y los pasos para adquirirlo.

**Inicio**

- **Propósito**: Captar la atención del visitante con un mensaje claro y directo.
    
- **Contenido**: Nombre del producto, propuesta de valor destacada y llamado a la acción (CTA).


**Información explicativa**

- **¿Cómo funciona?:** Descripción paso a paso del funcionamiento del sistema.
    
- **Beneficios:** Listado de ventajas competitivas de la solución para los usuarios.
    
- **Testimonios:** Opiniones de usuarios actuales que validan la experiencia con StockSip.


**Conversión**

- **Planes:** Detalle de los distintos planes de suscripción disponibles.

<p align="center">
  <img src="https://i.imgur.com/FmDNTCb.png">

  > <p align="center">Organización en el landing page</p>


Además la arquitectura jerárquica en la interfaz de la aplicación web de "StockSip" ha sido diseñada para facilitar el acceso y gestión eficiente de las múltiples funcionalidades del sistema. Esta estructura permite una distribución lógica del contenido, reduciendo la carga cognitiva del usuario y mejorando su capacidad para encontrar rápidamente las herramientas que necesita.


<p align="center">
  <img src="https://i.imgur.com/AGeCflJ.png">

  > <p align="center">Organización en la aplicación</p>

**Pantalla de inicio**

Una vista general tipo dashboard que presenta:

- Tarjetas resumen del stock actual, productos por vencer, y alertas activas.
    
- Notificaciones destacadas (por vencimiento o bajo stock).
    
- Gráficos breves sobre tendencias de entradas/salidas recientes.

**Navegación principal**

Sistema jerárquico accesible desde un menú lateral con iconografía clara. Incluye las siguientes pestañas:

- Dashboard
    
- Inventario
    
- Zonas de almacenamiento
    
- Alertas
    
- Facturación
    
- Guías
    
- Perfil

**Filtrado y organización avanzada**

**a. Para Dueños de Licorerías**

- **Filtros por:** Tipo de producto y nivel de stock y vencimiento.
    
- **Funcionalidades destacadas:** Visualización de productos críticos, registro de nuevas entradas y salidas y gestión de zonas de almacenamiento.

**b. Para Proveedores de Licores**

- **Filtros por:** Temporalidad de pedidos (última semana, mes).
    
- **Funcionalidades destacadas:** Emisión y consulta de guías, gestión de facturación y seguimiento de entregas.


**Segmentación por audiencia**

**a. Dueños de licorerías**

- Enfoque en gestión de stock, reducción de pérdidas por caducidad, registro de movimientos y planificación de compras.
    
- Visualización clara de productos prioritarios y herramientas para reorganizar zonas de almacenamiento.

**b. Proveedores de licores**

- Acceso a historial de pedidos y entregas.
    
- Visualización de demanda por producto y licorería.

- Herramientas de seguimiento y emisión de guías y facturas desde la plataforma.
<br>

### 4.2.2. Labeling Systems ###

El sistema de etiquetado de "StockSip" ha sido diseñado para ser claro, directo y fácil de entender, usando palabras clave con un número mínimo de términos sin perder precisión. Las etiquetas evitan tecnicismos innecesarios y buscan reducir la carga cognitiva del usuario.

**Principios:**

- **Consistencia**: Se usan las mismas etiquetas en botones, menús y mensajes relacionados (por ejemplo: “Nuevo Producto”, “Registrar Salida”, “Ver Detalles”).

- **Simplicidad**: Se evita el uso de jergas técnicas o frases largas. Ejemplos: “Stock mínimo”, “Fecha de caducidad”, “Alerta activa”.

**Etiquetado en el Landing Page:**

- **Inicio**: Es la primera sección que el usuario ve al entrar. Resume qué es StockSip y capta la atención con un mensaje claro y directo.
    
- **Cómo Funciona**: Explica paso a paso el funcionamiento de la plataforma, mostrando lo fácil que es empezar y gestionar el inventario.
    
- **Beneficios**: Resalta las ventajas clave de usar StockSip, como ahorro de tiempo, reducción de pérdidas y toma de decisiones inteligentes.
    
- **Testimonios**: Incluye opiniones reales de usuarios que ya usan la plataforma, lo que genera confianza en nuevos visitantes.
    
- **Planes**: Presenta los diferentes planes de suscripción disponibles, con precios, características y comparaciones para facilitar la elección.

**Etiquetado en la Aplicación Web:**

- **Inventario**: Sección principal donde se visualiza y gestiona el stock de productos disponibles.

- **Nuevo Producto**: Permite registrar un nuevo artículo en el sistema, ingresando sus datos básicos.

- **Alertas de Vencimientos**: Muestra los productos próximos a caducar para tomar decisiones rápidas.

- **Zonas de almacenamiento**: Permite al usuario crear una zona de almacenamiento o gestionar zonas donde guardar o exponer sus productos.

- **Reportes**: Área donde se pueden consultar y descargar informes de movimiento y estado del inventario.

- **Configuración**: Sección para ajustar preferencias del sistema, notificaciones y datos de la cuenta.

- **Perfil Usuario**: Acceso a los datos personales del usuario, con opción para editar información o cerrar sesión.
<br>

### 4.2.3. SEO Tags and Meta Tags ###

Con el objetivo de mejorar la visibilidad de "StockSip" en los motores de búsqueda y facilitar su descubrimiento tanto por licorerías como por proveedores interesados en optimizar la gestión de sus productos, se ha establecido una estrategia SEO que incluye el uso adecuado de etiquetas HTML para los principales elementos informativos del sitio y la aplicación web.

**Landing Page**

- **Title:**  
`<title>StockSip – Optimiza tu inventario de forma inteligente</title>`

Una frase concisa que refleja la propuesta de valor de la herramienta y contiene palabras clave como "optimiza", "inventario" e "inteligente", términos que los usuarios suelen emplear al buscar soluciones de este tipo.

- **Meta Description:**  
`<meta name="description" content="StockSip es una plataforma digital diseñada para ayudar a licorerías y proveedores a gestionar sus inventarios de forma eficiente. Recibe alertas de vencimiento, mejora tus decisiones de compra y evita pérdidas gracias a recomendaciones inteligentes basadas en tu historial de productos.">`  

Esta descripción amplía la explicación del producto, destacando sus beneficios clave y diferenciadores, a la vez que integra términos como “plataforma digital”, “alertas”, “decisiones de compra” y “recomendaciones inteligentes”.

- **Meta Keywords:**  
`<meta name="keywords" content="gestión de inventarios, licorerías, proveedores, plataforma de stock, control de vencimiento, optimización de productos, sugerencias de compra, StockSip">`  

Un conjunto seleccionado de palabras y frases clave que abarca tanto el público objetivo (licorerías, proveedores) como funcionalidades (control, stock, sugerencias).

- **Meta Author:**  
`<meta name="author" content="Equipo StockSip – Diseño UX/UI y Desarrollo Web">`  

Incluye una referencia al equipo responsable del diseño y desarrollo del producto, lo cual puede apoyar en términos de confianza y atribución de contenido.

---

**Web Application – Dashboard Principal**

- **Title:**  
`<title>Panel de Control – StockSip | Visualiza, gestiona y optimiza tu inventario</title>`  

Este título complementa el nombre de la aplicación con un llamado a la acción claro y directo, enfocado en los principales objetivos que el usuario puede lograr desde el dashboard.

- **Meta Description:**  
`<meta name="description" content="Explora tu panel de control personalizado en StockSip. Administra tu inventario, accede a reportes detallados, recibe sugerencias de compra y controla tus productos a punto de vencer. Toda la información que necesitas, en un solo lugar.">`  

Redactado con una estructura clara y centrada en la funcionalidad. Refuerza el valor del dashboard como núcleo operativo de la aplicación, destacando acciones prácticas que el usuario puede realizar.

- **Meta Keywords:**  
`<meta name="keywords" content="dashboard de inventario, stock inteligente, gestión operativa, productos por vencer, reportes automáticos, control de licorerías, sugerencias de compra, plataforma StockSip">`  

En esta lista se incluyen palabras clave enfocadas en la experiencia dentro del entorno de aplicación, usando términos que reflejan una intención de uso concreta (ej. “dashboard de inventario”, “reportes automáticos”).

- **Meta Author:**  
`<meta name="author" content="Equipo de Desarrollo Web – StockSip, 2025">`  

Agrega también el año del lanzamiento del producto para reforzar la actualidad del sistema y su vigencia.
<br>
<br>
### 4.2.4. Searching Systems ###

Dentro de la sección Inventario, el sistema de búsqueda está integrado de forma simple pero efectiva para que el usuario pueda localizar productos rápidamente. Se utiliza un campo de búsqueda principal centrado en la parte superior de la tabla, acompañado de botones de acción. Este campo permite buscar por nombre de producto o tipo (por ejemplo: “Whiskey”, “Vino”).


<p align="center">
  <img src="https://i.imgur.com/Ut4hET5.png">

  > <p align="center">Búsqueda en el inventario</p>


**Filtros de Búsqueda**

Al realizar una búsqueda, los usuarios pueden refinar los resultados mediante una variedad de criterios clave que les permiten adaptar la visualización a sus necesidades específicas:


- **Categoría:** Posibilidad de filtrar por tipo de licor o bebida, tales como destilados, vinos, cervezas, espumantes, etc.
- **Disponibilidad por zona:** Permite verificar si un producto está disponible en alguna zona creada por el usuario.

**Resultados de Búsqueda**

Los resultados se presentan en un formato visual tipo tabla, diseñado para proporcionar información clave de forma rápida. Cada fila en la tabla incluye:

- Nombre del producto
- Tipo
- Precio
- Fecha de caducidad
- Stock actual
- Stock mínimo

Se implementa una codificación por colores para facilitar la interpretación visual de las tendencias:

- **Verde:** Indica un stock aceptable
- **Rojo:** Indica un riesgo en el stock

**Búsqueda Avanzada (Proveedores)**

StockSip incluye una función de búsqueda avanzada especialmente diseñada para proveedores de licores:

- **Guías de conservación por tipo de producto:** Acceso exclusivo a documentos y recomendaciones técnicas que detallan las mejores prácticas para la conservación de diferentes tipos de licores (temperatura, humedad, tiempo de almacenamiento recomendado, etc.).
- **Planes de reabastecimiento:** Herramienta que permite proyectar necesidades de reposición de stock basándose en históricos de venta, frecuencia y patrones de consumo.
<br>

### 4.2.5. Navigation Systems ###

La navegación en **StockSip** está diseñada para facilitar el recorrido del usuario de manera clara y rápida. En el landing page se implementa una barra de navegación fija con las secciones clave para el visitante. Estas son:

- Inicio
- ¿Cómo funciona?
- Beneficios
- Contacto
- Empezar


<p align="center">
  <img src="https://i.imgur.com/Xs1UCzf.png">

  > <p align="center">Barra de navegación fija</p>

<br>
En la aplicación web, se implementa una barra lateral fija con íconos**, la cual permite el acceso directo a las funcionalidades clave como:  

- Inicio
- Inventario
- Alertas
- Reportes
- Compras
- Zonas
- Configuración
- Perfil de usuario

Cada sección está representada con un ícono claro y una etiqueta visible al pasar el cursor o expandir el menú, asegurando una navegación fluida.

<p align="center">
  <img src="https://i.imgur.com/NRXVoUd.png">

  > <p align="center">Barra de navegación desplegable</p>

<br>

## _4.3. Landing Page UI Design_ ##

### 4.3.1. Landing Page Wireframe ###
Para el desarrollo del Landing Page de StockSip, se realizaron diversos bosquejos de baja fidelidad en la aplicación de diseño de interfaz Figma para crear la estructura de las pantallas del Landing Page de la solución.

<p align="center">
  <img src="https://i.imgur.com/iwIbHR9.png"/>
</p>

### 4.3.2. Landing Page Mock-up ###
Para el desarrollo del Landing Page de StockSip, se realizaron bosquejos de alta fidelidad en la aplicación Figma. Para el desarrollo de estas pantallas, se tomó como base los Wireframes previamente diseñados, sin embargo, estas pantallas poseen colores adecuados y la tipografía definida para las distintas secciones del Landing Page.

<p align="center">
  <img src="https://i.imgur.com/kGRg31c.png"/>
</p>

## _4.4. Web Applications UX/UI Design_ ##

### 4.4.1. Web Applications Wireframes ###

### 4.4.2. Web Applications Wireflow Diagrams ###

### 4.4.3. Web Applications Mock-ups ###

### 4.4.4. Web Applications Userflow Diagrams ###

## _4.5. Web Applications Prototyping_ ##

## _4.6. Strategic Domain-Driven Design_ ##

## 4.6.1. Event Storming ##

## 4.6.2. Domain Message Flow Modeling ##

## 4.6.3. Bounded Context ##

## 4.6.4. Bounded Context Canvas ##

## _4.7. Domain-Driven Software Architecture_ ##

### 4.7.1. Software Architecture Context Diagram ###

### 4.7.2. Software Architecture Container Diagrams ###

### 4.7.3. Software Architecture Components Diagrams ###

## _4.8. Software Object-Oriented Design_ ##

### 4.8.1. Class Diagram ###

### 4.8.2. Class Dictionary ###

## _4.9. Database Design_ ##

### 4.9.1. Database Diagram ###

A continuación, se adjunta el link de acceso a la vista del diagrama de base de datos diseñado en Vertabelo.
[Link de acceso al Diagrama de Base de Datos](https://my.vertabelo.com/doc/4fUjzmQ2srbVzhRC8cE7TcMHqw8az7R0)

<p align="center">
  <img src="../img/Chapter IV/database_diagram.png" 
  alt="database_diagram"/>
