Comandos utilizados en el ejercicio3
Paso1-Crea un repositorio de Git vacío con el comando: git init
Paso2-Crea un archivo llamado index.html: touch index.html
Paso3-Agrega el archivo index.html al área de preparación con el comando y haces commit en esa rama con su respectivo mensaje: git add index.html luego git commit -m 'Agrega contenido a index.html'
Paso4-Crea una nueva rama llamada develop: git branch develop
Paso5-Cambia a la rama develop: git checkout develop
Paso6-Crea un archivo llamado .env: touch .env
Paso7-Crea un archivo llamado .gitignore en la raíz del repositorio: mkdir /.gitignore
Paso8-Agrega una línea que indique que Git debe ignorar el archivo .env
Paso9-Agrega el archivo .gitignore al área de preparación: git add .gitignore
Paso10-Edita el archivo index.html y agrega esos cambios al área de preparación: git add index.html
Paso11-Haz un commit con los cambios en la rama develop: git commit -m 'Cambios en la rama develop'
Paso12-Cambia de vuelta a la rama master: git checkout master
Paso13-Muestra el contenido del archivo index.html para comprobar que los cambios hechos en la rama develop no están presentes: cat index.html
Paso14-Fusiona la rama develop en la rama master: git merge develop
Paso15-Muestra el contenido del archivo index.html de nuevo para comprobar que los cambios realizados en la rama develop ahora están presentes en la rama master: cat index.html
Paso16-Verifica que el archivo .env no está incluido en el repositorio: git ls-files --other --ignored --exclude-standard
Paso17-Publicar a Github en un repositorio llamado aspirantes-mir-ejercicioi-3.