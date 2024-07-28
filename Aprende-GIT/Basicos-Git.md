# Comandos en Git

Para ejecutar los siguientes comandos es necesario abrir la terminal de comandos que se incluye en la instalación de Git, la terminal que usaremos para ejecutar los comandos desde ahora será la terminal de Git Bash.

---
## Sintaxis de comandos

|comando|acción|sintaxis|
|-------|------|--------|
|ls |Nos permite listar todas las instancias que se encuentren en ese directorio.|~$ Ls|
|pwd|Nos muestra la ubicación actual de nuestra navegación.|~$ pwd|
|cd|Este comando nos permite movernos entre las distintas instancias que se encuentran en nuestro equipo local|~$ cd|
|cd ..|Nos permite salir o retroceder del directorio en el que nos encontremos ubicados|~$ cd ..|
|mkdir| Nos permite la creación de directorios|~$ mkdir "nombre de directorio"|
|git init|Nos permite inicializar un repositorio o proyecto web|~$ git init|
|ls -a|Nos muestra todos los directorios o carpetas que se encuentran ocultas|~$ls -a|
|Git status|Este comando nos permite saber el estado actual de nuestro repositorio|~$ Git status|
|Git add|Nos permite confirmar y agregar todos los cambios o commits que queremos ver reflejados en el nuestro repositorio|~$ Git add + (nombre del archivo)|
|Git restore|Nos permite regresar o restaurar un archivo|~$ git restore + "nombre del archivo"|
|Git commit|Este comando tiene la función de comprometer todos los cambios que se encuentren confirmados o lo mismo que decir hacer un commit de los archivos alojados en un repositorio|~ $ Git commit -m "Descripción detallada del commit"|
|rm|Nos permite eliminar el archivo o elemento que deseemos |~$ rm + "Nombre del archivo"|
|mv|Nos permite cambiar el nombre de un archivo|~$ mv + "nombre actual" + "nombre a cambiar"|
|git diff| Nos muestra una breve diferencia entre los cambios actuales y los cambios anteriores en el documento|~$ git diff|
|Git diff --staged| Nos muestra los cambios que se encuentran en staged o cambios sin comprometer|~$ Git diff --staged|
|Git log --oneline|Nos muestra el historial de cambios realizados en el repositorio actual|~$ Git log --oneline|
|Git branch|Nos permite saber en que rama de nuestro proyecto nos encontramos actualmente.|~$ Git branch|
|Git checkout -b|Nos permite crear una nueva rama además de la principal.|~$ Git checkout -b + "nombre de la rama"|
|cat |Nos permite acceder al contenido que encuentre el ese documento especifico.|~$ cat + "Nombre del documento"|
|Git Checkout|Nos permite movernos entre las ramas disponibles en el repositiorio|~$ Git checkout + "Nombre de la rama"|
|Git remote add | Nos permite subir nuestros cambios a la nube en este caso será un repositorio en GitHub|~$ Git remote add "URL de repositorio en la nube"|
|Git push -u origin main|Nos permite subir los cambios mas recientes de nuestro repositorio|~$ Git push -u origin main|
