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
En esta sección se presentarán los mockups de la aplicación web, los cuales son bosquejos de media o alta fidelidad sobre las funcionalidades principales de nuestra solución. Para el diseño de los mockups, se partió de los wireframes realizados previamente.

### Inicio de Sesion/Registro ###
<p align="center">
  <img src="https://i.imgur.com/cIC7cS5.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/KT269QZ.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/mh0dTbk.png">
</p>

### Inventario ###
<p align="center">
  <img src="https://i.imgur.com/Rs5UuQj.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/COJ0sm4.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/ecZ3s1A.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/yN8FEOs.png">
</p>

### Alertas ###
<p align="center">
  <img src="https://i.imgur.com/gqflAB8.png">
</p>

### DashBoard ###
<p align="center">
  <img src="https://i.imgur.com/YshuwWl.png">
</p>

### Facturacion ###
<p align="center">
  <img src="https://i.imgur.com/8gePhYX.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/FlkNcHb.png">
</p>

### Descuentos ###
<p align="center">
  <img src="https://i.imgur.com/oIiZ6ls.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/VTqmcoE.png">
</p>

### Planes de reabastecimiento ###
<p align="center">
  <img src="https://i.imgur.com/0VUjZjM.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/tSUYAub.png">
</p>

### Guias de conservacion ###
<p align="center">
  <img src="https://i.imgur.com/LmDPGXj.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/IskgNzG.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/4iaC6e9.png">
</p>

### Ordenes de compra ###
<p align="center">
  <img src="https://i.imgur.com/iocU5wd.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/6IVUctF.png">
</p>

### Reportes ###
<p align="center">
  <img src="https://i.imgur.com/N2kxBpQ.png">
</p>

### Zonas de almacenamiento ###
<p align="center">
  <img src="https://i.imgur.com/XQlT1qr.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/2ZcCs5J.png">
</p>

### Perfil ###
<p align="center">
  <img src="https://i.imgur.com/NWCRoKP.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/VWZ6niB.png">
</p>

### Catalogo ###
<p align="center">
  <img src="https://i.imgur.com/R7V4dDW.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/qkj7s5k.png">
</p>
<p align="center">
  <img src="https://i.imgur.com/J8KLgq7.png">
</p>

### 4.4.4. Web Applications Userflow Diagrams ###
Un user flow o trayectoria del usuario es un diagrama que consiste en mostrar el trayecto del usuario representado por un diagrama de flujo e indica el camino que debe seguir el usuario para cumplir con un objetivo en específico en la aplicación. Además, el user flow debe determinar estos pasos para completar una experiencia digital satisfactoria para el usuario.

- **User Goal 1:** Usuario desea registrarse en la aplicación

**Happy Path**

En esta ruta esperada, el flujo concentra un proceso de registro de cuenta en la aplicación. Asimismo, el usuario es recibido por la pantalla principal y debe registrarse en la aplicación usando información que solicite el registro. Finalmente, al crease la cuenta, el usuario puede continuar con el uso de la aplicación. Cabe recalcar, que este flujo no toma en cuenta la elección de plan ya que los usuarios que se registran, automáticamente poseen un plan de uso gratuito que limita sus funciones.

<p align="center">
  <img src=""
    alt="userflow_1_happypath"/>

**Unhappy Paths**

Estas rutas alternas toman en cuenta que el usuario ha colocado alguna información errónea que no pasó la verificación o que no completó uno o varios espacios requeridos para proceder con el registro.

<p align="center">
  <img src=""
    alt="userflow_1_unhappypath"/>

- **User Goal 2:** Usuario desea iniciar sesión con su cuenta en la aplicación

**Happy Path**

En esta ruta esperada, el flujo representa el proceso de inicio de sesión del usuario para acceder a la aplicación. Cabe recalcar, que desde este flujo sí toma en cuenta la elección de plan. Asimismo, de ahora en adelante, se trabaja con usuarios que poseen el plan premium.

<p align="center">
  <img src=""
    alt="userflow_2_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el usuario ha colocado alguna información de su cuenta erróneamente, lo que prohibe, en ese instante, poder acceder a su cuenta.

<p align="center">
  <img src=""
    alt="userflow_2_unhappypath"/>

- **User Goal 3:** Usuario desea cambiar su contraseña

**Happy Path**

En esta ruta esperada, el usuario inicia en un estado en el que no recuerda su contraseña para acceder a la aplicación. Para ello, deberá seguir el proceso para recuperación de contraseñas mediante el uso de su correo electrónico. Luego, recibirá un código de verificación que deberá introducir en la aplicación para poder crear una nueva contraseña.

<p align="center">
  <img src=""
    alt="userflow_3_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el usuario ha indicado un correo no registrado en la aplicación (si introduces un correo registrado, enviará un código de verificación a dicho correo aunque no sea tuyo). Por lo tanto, no recibirá ningún código de verificación y no podrá restaurar su contraseña.

<p align="center">
  <img src=""
    alt="userflow_3_unhappypath"/>

- **User Goal 4:** Dueño de licorería desea visualizar su inventario

**Happy Path**

En esta ruta esperada, el dueño de licorería inicia sesión en su cuenta para, de esta manera, pueda acceder a la pantalla principal (dashboard). Finalmente, el usuario, mediante un clic, accede al inventario digital y puede visualizar sus productos.

<p align="center">
  <img src=""
    alt="userflow_4_happypath"/>

- **User Goal 5:** Dueño de licorería desea agregar un producto a su inventario

**Happy Path**

En esta ruta esperada, el dueño de licorería accede al inventario digital y utiliza la función de agregación de productos. En la siguiente pantalla, rellena cada espacio requerido correctamente y guarda la información. A continuación, la aplicación asociará dicho producto a su almacén y se mostrará.

<p align="center">
  <img src=""
    alt="userflow_5_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta registrar un producto con información errónea o nula, lo cual no es posible y recibe un mensaje de error.

<p align="center">
  <img src=""
    alt="userflow_5_unhappypath"/>

- **User Goal 6:** Dueño de licorería desea registrar la salida de un producto

**Happy Path**

En esta ruta esperada, el dueño de licorería desea registrar la razón por la cual uno o varios productos salieron de su negocio. Para ello, posee dos secciones que debe completar: el producto y la razón. No hay manera de provocar errores en esta pantalla.

<p align="center">
  <img src=""
    alt="userflow_6_happypath"/>

- **User Goal 7:** Dueño de licorería desea conocer el estado de la salud de su inventario

**Happy Path**

En esta ruta esperada, el dueño de licorería desea visualizar el dashboard alternativo que muestra la salud de su inventario. Es por ello que realiza un scroll en la pantalla de su inventario y accede al lugar que desea visualizar.

<p align="center">
  <img src=""
    alt="userflow_7_happypath"/>

- **User Goal 8:** Dueño de licorería desea visualizar la sección Reportes

**Happy Path**

En esta ruta esperada, el dueño de licorería accede a la sección Reportes desde la pantalla principal (puede acceder a la sección Reportes desde cualquier otra sección). Para ello, utiliza el ícono que representa a dicha sección y la aplicación lo redirigirá.

<p align="center">
  <img src=""
    alt="userflow_8_happypath"/>

- **User Goal 9:** Dueño de licorería desea generar un nuevo reporte

**Happy Path**

En esta ruta, el dueño de licorería accede a la sección Reportes y selecciona el botón para registrar un nuevo reporte. Luego, rellena la inforamción que le solicita la aplicación correctamente. Finalmente, se procesa el registro y se muestra en la sección.

<p align="center">
  <img src=""
    alt="userflow_9_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta registrar un reporte con información errónea o incompleta, lo que no es posible. Por lo tanto, se le muestra un aviso de que su acción no ha sido procesada.

<p align="center">
  <img src=""
    alt="userflow_9_unhappypath"/>

- **User Goal 10:** Dueño de licorería desea saber si un producto se encuentra en una zona de almacenamiento determinada

**Happy Path**

En esta ruta esperada, el dueño de licorería accede a la sección Zonas. Luego, utiliza la barra de navegación al colocar el nombre del producto que desea buscar. Finalmente, la aplicación encuentra el producto y las zonas en las que se encuentra y las muestra al usuario.

<p align="center">
  <img src="."
    alt="userflow_10_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta buscar el nombre de un producto no registrado en su almacén o que no ha sido colocado en alguna zona. Por lo tanto, la aplicación mostrará una sección vacía.

<p align="center">
  <img src=""
    alt="userflow_10_unhappypath"/>

- **User Goal 11:** Dueño de licorería desea generar una nueva orden de compra

**Happy Path**

En esta ruta esperada, el dueño de licorería accede a la sección para realizar pedidos a los proveedores. Luego, selecciona el botón para generar una nueva orden. A continuación, el dueño de licorería completa la información requerida como productos a pedir y cantidad por cada uno. Finalmente, coloca el correo del proveedor al que desea hacer un pedido y envía.

<p align="center">
  <img src=""
    alt="userflow_11_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el dueño de licorería intenta registrar una orden de compra con información incompleta, lo cual, no es posible. Por lo tanto, recibe un mensaje de error,

<p align="center">
  <img src=""
    alt="userflow_11_unhappypath"/>

- **User Goal 12:** Proveedor desea generar una nueva guía de conservación

**Happy Path**

En esta ruta esperada, el proveedor accede a la sección Reportes y hace clic en el botón de Conservación. A continuación, es dirigido a la sección donde puede visualizar sus guías creadas y botones para modificar y crear nuevas guías. Luego, el proveedor se dispone a generar una nueva guía. Para ello, completa la información requerida correctamente y guarda. Finalmente, se muestra toda la información que ha registrado el proveedor.

<p align="center">
  <img src=""
    alt="userflow_12_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el proveedor, por error o equivocación, intenta crear una guía de conservación con información faltante o errónea. Por lo tanto, no se crea su guía de conservación.

<p align="center">
  <img src=""
    alt="userflow_12_unhappypath"/>

- **User Goal 13:** Usuario desea generar una nueva factura

**Happy Path**

En esta ruta esperada, el usuario accede a la sección Facturación donde puede visualizar sus facturas y botones para generar una nueva factura manualmente. A continuación, presiona el botón para registrar una nueva factura. Luego, completa los espacios requeridos correctamente y guarda la información.

<p align="center">
  <img src="."
    alt="userflow_13_happypath"/>

**Unhappy Paths**

En esta ruta alterna, el usuario intenta registrar una factura con información errónea o faltante. Por lo tanto, no será posible registrar la factura.

<p align="center">
  <img src=""
    alt="userflow_13_unhappypath"/>

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
