# Practica Git y GitHub
El programa `HolaMundo.py`, simplemente imprime el mensaje "Hola Git"; el principal objetivo de la práctica es aplicar los primeros conocimientos del uso de Git y GitHub, con la creación de un pequeño codigo,
su modificación e implementación primeramente en un repositorio local, asi como la creación de un archivo .gitignore, para ignorar cierto tipo de archivos (Que en este caso, fue el archivo .log)
El programa `Hola Mundo.py` se podría ejecutar desde la computadora, con el uso del IDE desde que se creó este, o clonando el repositorio en otra computadora que no sea la principal.

Los principales comandos de Git que utilicé en el proceso fueron:
+ `cd **Ruta de acceso**`, para seleccionar la carpeta del proyecto
+ `git init`, para inicializar el codigo como un repositorio local
+ `git add -A`, para enviar al área de preparación
+ `git commit -m "Algún mensaje"`, para realizar los commits incluyendo los mensajes necesarios
y finalmente, cuando se vinculó al repositorio remoto, el uso de `git push origin master`, para subir los archivos al repositorio
## Arhivo GitIgnore
Cabe mencionar que yo creé el archivo .gitignore desde mi IDE, sin embargo, se puede usar el comando `touch .gitignore`, para crear el archivo desde la consola
Este archivo se crea para que se "ignoren" ciertos tipos de documentos, codigos, etc. por razones diversas hacia el programador, y no se suban al repositorio.

El documento de texto debe de contener el tipo de archivos que quieren que se ignore, en este caso, tiene escrito `*.git`, que hace que se ignoren todos los archivos con extensión .git, usando el "*" 
como comodín, otra forma de ignorar algun archivo, seria con el uso de /archivo.log, que ignoraría específicamente un archivo con ese nombre.
Se puede verificar al ingresar `git estatus` en el bash de git, para verificar que archivos están por falta en commit, y en este caso, no debería de aparecer los archivos que se especificaron dentro del documento ".gitignore", solamente los demás:)
