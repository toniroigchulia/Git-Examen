# Git-Examen


PRIMERA PRACTICA

1. Usamos los comandos "git init" para iniciar un repositorio en una carpeta de nuestro equipo.
![](./git%20init%201.png)

2. Usamos "git clone" o "git remote" para vincularlo con el repositorio online de git.
![](./git%20clone%202.png)

3. Usamos el "git add" para añadir los archivos al siguiente commit si ponemos " . " despues del add se añadiran todos los archivos si queremos solo un archivo en lugar de " . " ponemos el nombre del archivo.
![](./git%20commit%204.png)

4. Con "git commit" para guardar los cambios que se subiran con el siguiente push.
![](./git%20commit%204.png)

5. Usamos "git push" para subir los cambios al repositrio online en este punto como no habia hecho cambios al readme me salia un error porque no habia nada que subir.
![](./git%20push%205.png)

6. Si despues vamos a otro equipo podemos usar "git pull" para descargar a nuestro equipo los nuevos archivos del repositorio online o usar otra vez "git clone" para vinuclar automaticamente con repositorio online.
![](./git%20pull%206.png)

SEGUNDA PRACTICA

7. Podemos usar los comandos "git log --oneline --all" para ver todos los comits que hemos hecho y ver sus identificadores(hash)
![](./git%20oneline%207.png)

8. Usando el comando "git checkout (hash)" nos podemos mover a un commit anterior y hacer modificaciones a este asi podemos recuperar algun archivo perdido
![](./git%20checkout%208.png)

9. Si ahora usamos el "git log --oneline --all" nos deberia salir el HEAD en otro commit en mi caso como solo he hecho un commit sale en el mismo
![](./git%20chekout%209.png)

10. Una vez queremos volver a la rama principal podemos usar "git checkout master" para volver a trabajar en la rama principal del proyecto.
![](./git%20checkout%20master%2010.png)


TERCERA PRACTICA

1. Directorio de trabajo (Working directory)

El directorio de trabajo es donde nosotros podemos editar los archivos y no afecta de niguna forma nuestro repositorio de trabajo hasta que hagamos un git add, git commit y git push para guardar y subir los cambios que hemos hecho al repositorio correspondiente que queramos.


2. Área de preparación (Staging area)

La area de preparacion es donde una vez hemos hecho git add los archivos que hemos indicado se van a añadir en esta area de preparacion donde esos archivos ya no van a ser editados y solo estan esperando a que se confirmen los cambios para ser guardados de forma oficial con un git commit


3. Repositorio local (Directorio .git)

El repositorio loacl es donde git crea una carpeta oculta llamada .git donde se guardan todos los cambios que se vayan haciendo a nuestro proyecto y es lo que nos permite volver a versiones anteriores de nuestro programa usando el git checkout porque todos esos archivos tienen una copia guardad dentro de esa carpeta.