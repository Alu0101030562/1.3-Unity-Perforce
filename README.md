# 1.3-Unity-Perforce

Objetivo: experimentar el control de versiones con Perforce

## 1. Crear una conexión al depósito FDV2425 en la ULL

Lo primero que tendremos que hacer será descargar la aplicacion de Perforce **(Perforce Helix P4V)** y una vez descargada tendremos que hacer la conexión con el servidor.

Tendremos que utilizar la siguente ruta como Server y como usuario nuestro identificativo universitario.

 - Server: ssl:mudv-vcs.iaas.ull.es:1666
 - User: aluXXXXXXXXXX

Una vez conectado, crearemos un *workspace* para poder hacer la conexión con el depósito *FDV2425*

![conexiondepot](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3Perforce/Workspace.PNG)

## 2. Clonar el repositorio

Una vez hecha la conexión debemos clonar el repositorio para obtener todo el contenido. Para ello pulsaremos el botón de *Get Latest* de parte superior de la interfaz

![workspace](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3Perforce/Actualizardepot.PNG)

Carpeta local una vez clonado el repositorio

![CarpetaLocal](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3Perforce/repositorio.PNG)

## 3. Modificar el fichero presentacion.txt, agregando una frase que indique tu nombre y resuma tu experiencia en el programación de videojuegos 2D y 3D.

Para modificar un fichero ya creado debemos seleccionar el fichero y una vez seleccionado, pulsaremos el botón **checkout** para poder modificarlo

Tras modificarlo, debemos darle al botón de **submit** y añadir el commit de referencia.

## 4. Crear un fichero nuevo, tu_nombre.txt y añádelo al proyecto.

Para esto debemos crear el fichero en local y una vez creado, debemos ir a la pestaña de *workspaces* y seleccionar el fichero en local, ahí debemos seleccionar el botón de **Add** para hacer que Perforce haga un seguimiento. Por ultimo, pulsamos en el botón de **Submit** para añadirlo al proyecto.

## 5. Crear un proyecto Unity 3D básico y agregarlo al depot de la asignatura. Tu nombre debe ser prefijo.

Crearemos un proyecto 3D básico en unity y, tras haberlo añadido a la carpeta en local, pulsaremos el botón de **Add** para que perforce le haga un seguimiento.

![unity](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3Perforce/proyectoUnity.PNG)

Tras eso, pulsamos el botón de **submit** para añadirlo al depósito y añadimos el mensaje para guardar los cambios

![changelist](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3Perforce/commit%20proyecto.PNG)

![proyectoSubido](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3Perforce/depot%20subido.PNG)
