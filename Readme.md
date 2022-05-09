En primer lugar creamos la carpeta destino en la cual copiaremos los documentos de código que queremos usar para crear el repositorio.

Seguidamente ejecutamos Git Bash en nuestro pc.

A continuación escribimos el comando cd ' ' y entre las comillas ponemos el directorio de la carpeta en la cual tenemos el codigo,json, etc.

Una vez dentro que hayamos accedido y estemos en el directorio (el cual se nos muestra en la línea de información de usuario) y ejecutamos el comando GIT INIT.
Esto nos convierte a la carpeta en la que estamos en la master/main , seguidamente usamos el comando git status para comprobarlo.

Ahora queremos subir nuestro proyecto a git, asi que vamos a la página de git hub y creamos un repositorio con el nombre que queramos asignarle. Aqui tenemos la opción de generarle un 
README.MD en la carpeta del mismo o simplemente lo creamos nosotros en la carpeta que tengamos los documentos de codigo.

Ahora tenemos que usar el comando git add + el nombre del fichero que queramos subir para que nos detecte los cambios que se han hecho en la carpeta del proyecto, volvemos a usar el 
status para comprobar que nos los ha detectado y deberían aparecer en rojo(que significa que no están en el stage y verde que los hemos añadido).

Después usamos git status otra vez para comprobar que todos los ficheros que queremos subir están en verde dentro de la carpeta para poder proceder con el comando
git commit - n"mensaje descriptivo del upload" para confirmar todos los ficheros que incluimos con el git add.

Finalmente volvemos a hacer git status para comprobar que todo está ok y usamos comando git push para subirlo todo al repositorio en la web de git hub.

Después de crear el .txt de .gitignore e introducirle los valors .reto_2 para la carpeta y *.png para que ignore tanto la carpeta como todas las imagenes png

Seguimos el processo de git add .gitignore, después el git commit -n y finalmente el git push + direccion de repostiorio + la rama en la que estoy y por fin lo subimos a nuestro repositorio quedando accesible
desde nuestro github.


