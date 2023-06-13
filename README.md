# Challenge ONE | Java | Back-end | Hotel Alura

<p align="center" >
     <img width="300" heigth="300" src="https://user-images.githubusercontent.com/91544872/189419040-c093db78-c970-4960-8aca-ffcc11f7ffaf.png">
</p>

---
##  Primeros Pasos:


#### 🔹 Marca este proyecto con una ⭐
</br>

## 🖥️ Tecnologías Utilizadas:

- Java
- Eclipse
- Biblioteca JCalendar
- MySql
- Plugin WindowBuilder </br>

---
## ⚠️ Importante! ⚠️

☕ Use Java versión 8 o superior para compatibilidad. </br></br>
📝 Recomendamos usar el editor de Eclipse para compatibilidad con la Interfaz Gráfica. </br></br>
🎨 La interfaz contiene dos métodos importantes:
- setResizable(false): determina el tamaño de la ventana, y a través del parámetro <strong>false</strong>, la pantalla no se puede maximizar;
- setLocationRelativeTo(null): determina la ubicación de la ventana, y a través del parámetro <strong>null</strong> la mantiene centrada en la pantalla.

#### Para este desafío, concéntrate en la parte lógica y la conexión con la base de datos, después de completar el desafío, siéntete libre de agregar nuevas funciones y modificar la interfaz gráfica.
---

## 🔍 ¡Analizando nuestro repositorio!

### Este es el repositorio base de nuestro proyecto, en el encontrarás:
#### 🔹 src/views: carpeta con toda la interfaz gráfica de las pantallas necesarias para desarrollar el programa;
#### 🔹 src/imagenes: carpeta con imágenes que puedes usar en tu proyecto. Siéntete libre de usar otros, si lo deseas;
</br>


## 🚧 Proyecto

#### Al clonar o descargar el proyecto base y tener instalado el JCalendar, tendrás esta presentación al ejecutar el proyecto en Eclipse:

<p align="center" >
     <img width="700" heigth="700" src="https://user-images.githubusercontent.com/91544872/189419249-06b539da-7cf2-4d40-a711-618a5c872096.png">
</p>

### ⚠️ Descargué el proyecto pero los caracteres especiales no funcionan:

Si tu proyecto tiene errores como los de la imagen, siga los pasos a continuación:

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/91544872/189419556-20b67f67-003c-47ac-a0ae-02cf814a6ccb.png">
</p>

Ve a <em>Window</em> y haz clic en <em>Preferences</em>.

<p align="center" >
     <img width="200" heigth="200" src="https://user-images.githubusercontent.com/101413385/173693126-8e2fec8b-91b1-4007-bbc5-010bb454f440.png">
</p>

Luego haz clic en <em>General</em> y en <em>Workspace</em>. Si tu <em>Text File Enconding</em> no está con el <strong>Default (UTF-8)</strong>, haz clic en <em>Other</em>, y eliges la opción <strong>UTF-8</strong>, y finaliza haciendo clic <em>Apply and Close</em>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173691963-1e3d966e-5162-4393-9232-d5d395d5440f.png">
</p>

## 📊 Base de Dados

### ¿Cómo importar MySqlConnector al proyecto?

Es la misma ruta descrita para importar el <strong>JCalendar</strong>, haga clic con el botón derecho en el proyecto, <em>Build Path</em>, <em>Configure Build Path</em>, <em>Libraries</em>, <em>Add External JARs</em>. Para encontrar la ruta de este archivo <strong>.jar</strong>, ve al disco duro de tu computadora e ingresa a la carpeta  <em>Archivos de Programas (x86)</em>.

- Archivos de Programas (x86):
<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173169394-a67b528a-c8b7-4f7a-b374-a1da81b1cc5d.png">
</p>

- MySQL
<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173169551-b32a9978-3a05-4b6e-b077-f586d0c41e31.png">
</p>

- Connector J 8.0:

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173169584-48e21a03-e70f-4a65-9197-448a3645f526.png">
</p>

- My SQL Connector Java:
<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173169737-5f93868e-df8f-4177-90ba-faf9570758ac.png">
</p>

### Modelado de tablas:

Para este reto te proponemos dos tablas: <strong>Reservas</strong> y <strong>Huéspedes</strong>. La tabla de huéspedes debe contener la clave externa <em>(foreign key)</em> <strong>idReserva</strong>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/169529338-09a4d4c2-1b5a-41dc-b305-38498ebc29a8.png">
</p>


## 🗔 Plugin WindowBuilder

En el menú de <strong>Eclipse</strong>, ir a la pestaña <em>Help</em> y seleccione la opción <em>Eclipse Marketplace</em>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173254683-a4d27b04-3994-4c7b-bf70-6e1b665a5452.png">
</p>

En la barra de búsqueda, ingresa <strong>window builder</strong> y haz click en <em>Go</em>. Después de la búsqueda, selecciona la primera opción y haz click en <em>Install</em>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173254936-b1ed41ba-af1b-47ae-bf75-00de4a22ff19.png">
</p>

En la siguiente ventana, selecciona el botón <em>Confirm</em>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173255237-94789460-0544-4dd3-b00d-2738b83bd575.png">
</p>

Haz click en la opción para aceptar los Términos de Uso, y para finalizar haz clic en <em>Finish</em>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173255298-05ac80f1-3e93-4097-90af-7fc8a4fa1611.png">
</p>

Después de la instalación, será necesario reiniciar el <strong>Eclipse</strong>.

### ¿Cómo abrir cada ventana de diseño?

Una vez que completes el desafío, si quieres explorar el <em>Window Builder</em> y agregar nuevas ventanas, o cambiar el diseño de las existentes, haz clic en el archivo <strong>.java</strong>, y luego en <em>Open With</em> y finalmente en <em>Window Builder Editor</em>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173681973-5699a164-b66d-49f5-87c1-5436dd425457.png">
</p>

La pestaña de <em>Design</em> se abrirá por encima de la zona del <em>Console</em>. ¡Aquí puedes liberar al artista que llevas dentro de ti!

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173682648-4c371224-fe4b-4e57-a3ee-9298a4d44554.png">
</p>
