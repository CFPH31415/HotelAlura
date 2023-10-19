# Challenge ONE | Java | Back-end | Hotel Alura

<p align="center" >
     <img width="300" heigth="300" src="https://user-images.githubusercontent.com/91544872/189419040-c093db78-c970-4960-8aca-ffcc11f7ffaf.png">
</p>

## Descripción del Proyecto 
El Hotel Alura conocido por su espectaculares instalaciones y paquetes promocionales para Desarrolladores de Software está teniendo problemas para llevar el control de las reservaciones hechas por sus clientes, por eso solicitan nuestra ayuda para desarrollar un sistema de reserva que contenga:

1) Sistema de autenticación de usuario para que solo usuarios pertenecientes al hotel consigan acceder al sistema;
2) Permitir crear, editar y eliminar una reserva para los clientes;
3) Buscar en la base de datos todas las informaciones tanto de los clientes como de las reservas;
4) Registrar, editar y eliminar datos de los huéspedes;
5) Calcular el valor de la reserva en base a la cantidades de días de la reserva y a una tasa diaria que puede ser asignada por ti y en la moneda local de tu país, por ejemplo si tenemos una reserva de 3 dias y el valor de nuestra diaria son 20$ debemos multiplicar esos 3 dias por el valor de la diaria, lo que serian 60$, todo esto deberá ser hecho automaticamente y mostrado al usuario antes de guardar la reserva;
6)Base de datos para almacenar todos los datos pedidos anteriormente.

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

## ⬇️ Download

### Cómo descargar:

#### 🔹 Fork

1 - Haz el <strong>fork</strong> del proyecto. En la parte superior derecha, al hacer clic en el icono se creará un repositorio del proyecto en tu cuenta personal de GitHub. </br>

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/169404781-7df6355b-3a15-472a-8d8e-fdb84d91a7bd.png">
</p>

2 - Una vez que tengas el repositorio "forkado" en tu cuenta, comprueba si la URL de la página es la del repositorio de tu cuenta.

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/173256272-6dd3eaba-b52e-42ec-b307-17ed785f9110.png">
</p>

3 - Haz clic en la opción <strong>Code</strong>. Se mostrarán tres formas de instalar el repositorio en su máquina, y destacamos dos:

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/173166461-e62d9704-98d5-4773-a60e-57d5729575ae.png">
</p></br>

#### 🔹 Clonar o descargar el ZIP

1 - Para clonar, simplemente copia el <em>url</em> resaltado en la imagen y ubicado justo debajo del HTTPS, crea una carpeta en tu computadora, abre el <em>cmd</em> o el <em>git bash</em> dentro de esa carpeta y luego ingresa el comando <strong>git clone</strong> y con el botón derecho del mouse dentro del terminal haz click en la opcion <strong>Paste</strong> para pegar el <em>url</em> y presiona <em>Enter</em>. 

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/173256523-79d38ee2-8668-435c-b31a-ac6ba78bb813.png">
</p>

2 - La segunda opción es descargar el código en un paquete <strong>"zipado"</strong> y extraer la carpeta a tu computadora.
</br></br>

## 📝 Eclipse

### ¿Cómo importar mi proyecto a Eclipse?

1 - Una vez dentro del Editor al lado izquierdo, haz clic en el <em>Files</em> que está en el menú en la parte superior, elige la opción <em>Open Projects from File System</em>.

<p align="center" >
     <img width="400" heigth="400" src="https://user-images.githubusercontent.com/101413385/173164237-1db32d79-2b35-433f-817c-ec3fa30899fc.png">
</p>

Luego haz click en <em>Directory</em> y ubica el directorio del proyecto "clonado" o "extraído" en tu computadora. Haz click en <em>Finish</em> para completar la importación.

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/173110215-f9451a5e-a9eb-4056-aec8-6eb3e3601e53.png">
</p>

2 - La segunda forma de importar es en <em>File</em> en la opción <em>Import</em>. O a través del <strong>Project Explorer</strong> haz clic en el campo vacío con el botón derecho del mouse y elijas la opción <strong>Import</strong>.

<p align="center" >
     <img width="400" heigth="400" src="https://user-images.githubusercontent.com/101413385/173111357-2ec928ac-5a3d-4f7c-ba84-8906d84bfd08.png">
</p>

<p align="center" >
     <img width="400" heigth="400" src="https://user-images.githubusercontent.com/101413385/169431325-23a2e3cb-85a3-4298-8e60-64dfa58e2e6f.png">
</p>

Si te decides por el <strong>Import</strong>, se abrirá la ventana correspondiente. Haz clic en la opción <em>Existing Projects Into Workspace</em> y en el botón <em>Next</em>.

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/169431890-27f40955-27d8-4b4d-82df-d3507f85de6c.png">
</p>

Luego haz clic en el botón <em>Browse</em> y busca el proyecto en el directorio local.

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/169432246-a769555c-daf9-490e-a0c7-908f7e5de967.png">
</p>

## 📅 JCalendar

Tras realizar la importación a tu editor, es necesario instalar la librería <strong>JCalendar</strong>, de lo contrário, el proyecto presentará un error y no será posible abrir la ventana de <strong>Reservas</strong>. </br>

Para instalar, se necesita descargar el paquete a través de ese enlace: 
🔹 [Link para el JCalendar](https://toedter.com/jcalendar/)

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/169592420-7ea798d4-b7d2-4fd6-a03c-75f0fbc2e4bc.png">
</p>

El siguiente paso es extraer los archivos a una carpeta e importar los archivos desde la carpeta <strong>lib</strong> a una carpeta local e importar los archivos a Eclipse.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173167366-664a8876-a5c9-45d1-880d-650fbd6f8b07.png">     
</p>

Archivos de carpeta <strong>lib</strong>:

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173699122-00cc4055-2098-4bba-8d3b-3bd252013116.png">
</p>

Haz click con el botón derecho encima del proyecto ubicado en el <strong>Package Explorer</strong>, elijas la opción <em>Build Path</em> y <em>Configure Build Path</em>.

<p align="center" >
     <img width="500" heigth="500" src="https://user-images.githubusercontent.com/101413385/173167991-44b111ca-c2d6-4d83-b225-33eb2657448f.png">
</p>

El proyecto tendrá un mensaje de error que indica que la ruta de la biblioteca no existe en tu computadora. Haz click en <em>Libraries</em>, luego en <em>Classpath</em> seleccione el archivo JCalendar, elije la opción <em>Remove</em> y <em>Apply and Close</em>.

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/173167817-ddbdedc5-c4a6-4f6d-bd86-f86a153d6b88.png">
</p>

Para importar el <strong>Jcalendar</strong> desde tu computadora, después de haber "extraído" los archivos de la descarga, pulsa en <em>ClassPath</em> y luego en <em>Add External JARS</em> agrega uno por uno  o selecciona todos de una vez y haz click en <em>Apply and Close</em>.

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/169596029-a9fa21ef-8d90-45a6-8aa2-be2d911d4074.png">
</p>

Por lo tanto, el proyecto debe contener los siguientes archivos después de las importaciones:

<p align="center" >
     <img width="600" heigth="600" src="[https://user-images.githubusercontent.com/101413385/173695620-7a4893e9-b9a1-44d6-8b70-c94a85ea891e.png](https://github.com/CFPH31415/HotelAlura/blob/main/AluraHotel-Esp-Base/src/imagenes/hotel.png)">
</p>


## 🚧 Proyecto

<p align="center" >
     <img width="700" heigth="700" src="[ttps://github.com/CFPH31415/HotelAlura/blob/main/imagenes/hotel.png?raw=true](https://raw.githubusercontent.com/CFPH31415/HotelAlura/main/AluraHotel-Esp-Base/src/imagenes/hotel.png)">
</p>




🧡 <strong>Oracle</strong></br>
<a href="https://www.linkedin.com/company/oracle/" target="_blank">
<img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

💙 <strong>Alura Latam</strong></br>
<a href="https://www.linkedin.com/company/alura-latam/mycompany/" target="_blank">
<img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
