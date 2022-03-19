-Comandos Git-

INICIO DE GIT
- git init : crea un repositorio en el directorio que se encuentra, esto se ejecuta solo la primera vez, crea una carpeta ".git"

COMANDOS GIT
- git status : muestra el estado de los archivos, si se hicieron commit o branch
- git status -s : esto muestra el estado de los archivos, es información minimizada

- git add . : Escanea y registra los nuevos cambios de los archivos, colocando el punto, significa que se agregan todos los archivos del directorio
- git add archivo.html : agrega solo un archivo específico

- git commit -m "mensaje descriptivo" : crea un commit (como una foto) del proyecto actual, el -m "..." permite agregar directamente el mensaje de descripción al crear el commit

CONEXION A REPOSITORIO REMOTO EN GITHUB
- git config user.name "miguelgh16" : con esto se registra el usuario de git, por lo general se usa el mismo usuario que github
- git config user.email "miguelgh16@gmail.com" : con esto se registra el correo del 
usuario, tiene que ser el mismo que en github donde va a estar el repositorio
- git config user.password token : el token(no va la palabra token, solo va la clave que genera github) es el password que pide github, se consigue en github>perfil>settings>developer settigns>personal Access token.
- git remote add origin "url del repositorio" : con eso se conecta al repositorio remoto en github

ENVÍO Y RECIBO DE ARCHIVOS AL REPO REMOTO
- git push -u origin master : con este comando se envían los archivos que fueron commit al repositorio remoto
- git clone url : con este comando se clona lo que está en el repositorio remoto al directorio local
- git pull origin master : busca en el repo remoto y trae los cambios al local

RAMAS
- git branch : nos dice en que rama estamos
- git branch rama1 : crea una nueva rama, en este caso "rama1"
- git branch -m rama1 ramaB : cambia el nombre de "rama1" a "ramaB"
- git checkout rama1 : con esto se cambia de una rama a otra, en este caso iría de master hacia rama1
- git branch -d rama1 : elimina una rama

COMANDOS AYUDA
- git version : muestra la versión de git
- git help : muestra todos los comandos
- git log : muestra el historial de cambios, dependiendo de la configuración de la terminal se tiene que salir con la tecla "q"
-git log --online : muestra el historial minimizado, más facil de seguir
- clear : limpia la terminal
- .gitignore : si se crea un archivo con en nombre ".gitignore", dentro se puede escribir el nobre de uno o varios archivos para que no les haga seguimiento, por ejemplo claves, para agregar un archivo hay que escribir el nombre en una linea y si se quiere agregar otro sería en otra linea

MOVIMIENTO EN DIRECTORIOS y CREACIÓN
- cd C:\documentos : con CD nos movemos a una carpeta específica (change directory)
- cd.. : retrocedemos un directorio
- touch "texto1.txt" : crea un archivo en el directorio actual

