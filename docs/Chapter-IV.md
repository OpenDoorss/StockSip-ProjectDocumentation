# Capítulo 4: Product Design #

## _4.1. Style Guidelines_ ##

### 4.1.1. General Style Guidelines ###

### 4.1.2. Web Style Guidelines ###

## _4.2. Information Architecture_ ##

### 4.2.1. Organization Systems ###

### 4.2.2. Labeling Systems ###

### 4.2.3. SEO Tags and Meta Tags ###

### 4.2.4. Searching Systems ###

### 4.2.5. Navigation Systems ###

## _4.3. Landing Page UI Design_ ##

### 4.3.1. Landing Page Wireframe ###

### 4.3.2. Landing Page Mock-up ###

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

A continuación, se adjunta el link de acceso a la vista del diagrama de clases diseñado en LucidChart:
[Link de acceso al Diagrama de Clases en LucidChart](https://lucid.app/lucidchart/f96ef385-17d9-4c55-b002-b959d622d9d3/edit?viewport_loc=3318%2C172%2C3216%2C1202%2CHWEp-vi-RSFO&invitationId=inv_95b21289-cf5f-45a7-85fe-9164e3f49e26)

<p align="center">
  <img src="../img/Chapter IV/class_diagram.png" 
  alt="class_diagram"/>

### 4.8.2. Class Dictionary ###

En esta sección, se detallará el diccionario de las principales clases que se muestran en el diagrama de clases previamente mostrado.

- **Profile:** Es la clase que contiene la información personal y de contacto del usuario que se registra en la aplicación. Esta clase es la que interactúa con las otras clases de la aplicación.
- **User:** Es la clase que contiene información de cuenta de la persona que se registra en la aplicación.
- **Role:** Es un _value object_ que indica si el usuario es proveedor de productos o dueño de una licorería. 
- **Membership:** Es la clase que contiene la información de la membresía que adquiere un usuario en la aplicación.
- **Address:** Es un _value object_ que contiene la información sobre la dirección geográfica de un usuario (lugar del local de venta).
- **ProfileId:** Es un _value object_ que contiene al identificador único de cada perfil de usuario. Se usa en otras clases para evitar referenciar la clase Profile completa.
- **ProviderId:** Es un _value object_ que contiene al identificador único de cada proveedor. Se usa en las órdenes de pedido para evitar referenciar la clase Provider completa.
- **Money:** Es un _value object_ que sirve para crear valores de moneda válidos en la aplicación. Contiene un valor que puede ser decimal y una divisa.
- **Report:** Es una clase que contiene información de cada reporte que genere el usuario sobre el inventario o productos que posea.
- **Invoice:** Es una clase que contiene la información relacionada a la factura generada tras una compra al proveedor.
- **SalesOrder:** Es una clase que contiene un objeto PurchaseOrder. Es la clase que manipula el **proveedor** y posee estados para indicar cuándo será entregado.
- **PurchaseOrder:** Es una clase que contiene la lista de productos que va a solicitar el **dueño de licorería** al **proveedor**. Posee un método para calcular el precio total del pedido a ordenar.
- **PurchaseOrderItem:** Es una clase que contiene el detalle del producto que necesita el **dueño de licorería** y su cantidad deseada. Posee un método para calcular el subtotal del ítem.
- **ReplenishmentPlan:** Es una clase que contiene la información detallada del plan de reabastecimiento que posee un **proveedor** para enviar los pedidos de sus clientes. Posee un atributo "frequencyDays" que es una métrica de aproximación para saber cuánto tiempo le toma a un **dueño de licorería** a solicitar un pedido para abastecerse.
- **ConservationGuide:** Es una clase que contiene información sobre los cuidados que debe tener el **dueño de licorería** al tratar con los productos que adquiere
- **Inventory:** Es la clase principal de la aplicación. Contiene productos y el stock de cada uno. Además, genera alertas dependiendo del estado actual del almacén. Posee métodos para actualizar el stock de productos y actualizar el almacén en general (eliminar, agregar productos).
- **Zone:** Es una clase que contiene información sobre la zona en la que se encuentra el almacén. Por ejemplo: La zona de muestra de productos, el almacén general de productos, entre otros.
- **Product:** Es una clase que contiene todo el detalle de los productos tanto del proveedor como del dueño de licorería. Posee métodos para actualizar la información del producto, para colocar un stock mínimo que, si el número de stock es más bajo que el colocado, podrá generar notificaciones sobre bajo stock al usuario.
- **ProductType:** Es un _value object_ que contiene el tipo de producto que posee tanto proveedor como dueño de licorería. Ejemplo: cerveza, vino, vodka, etc.
- **ProductInfo:** Es un _value object_ que contiene la información más importante del producto como el nombre, cantidad de líquido, precio unitario y fecha de vencimiento.
- **Provider:** Es una clase que contiene información sobre un proveedor de productos.
- **Alert:** Es una clase que se usa para estructurar un mensaje de alerta o notificación que recibirá el usuario.

## _4.9. Database Design_ ##

### 4.9.1. Database Diagram ###
