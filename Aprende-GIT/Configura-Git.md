# Configuración de global de Git

Para configurar Git será necesario el uso de la terminal de comandos que nuestro equipo de computo tenga, en caso de ser Windows usaremos la terminal de CMD.

A continuación abriremos la terminal de comandos usando el aplicativo de **Ejecutar** de nuestro equipo, para abrirlo usaremos la combinación de teclas "**WIn + R**" y en el buscador emergente escribiremos "**CMD**" y daremos clic al botón de aceptar.

_Imagen: Origen autor_

![alt text](/Aprende-GIT/imagenes/uno.png)

---
Ya que estamos en la terminal de comandos verificaremos la versión actual de Git con el siguiente comando 

~~~
Git --version
~~~
obtendremos un resultado similar al siguiente

_Imagen:Origen autor_

![alt text](/Aprende-GIT/imagenes/dos.png)

---
Ahora que ya sabemos que sea instalado correctamente y tenemos la ultima versión actual configuraremos el usuario que usara Git mediante el siguiente comando,al igual que en la programación para ingresar una cadena de texto tendremos que hacerlo mediante comillas dobles:

_Comando de configuración de usuario_
~~~
Git config --global user.name "Nombre apellido"
~~~

ya que tenemos un nombre de usuario asignado también tendremos que asignarle un correo electrónico mediante, el siguiente comando nos permitirá hacerlo, para indicar una dirección de correo electrónico no será necesario el uso de comillas dobles. 

_Comando de configuración de correo electrónico_

~~~
Git config --global user.email correo electronico
~~~

como siguiente paso configuraremos el IDE de nuestra preferencia, en este caso usaremos [Vs Code](https://code.visualstudio.com), para hacer esta configuración también usaremos la terminal de comandos y lo haremos con el siguiente comando

_Comando de configuración de IDE_

~~~
Git config --global core.editor "code --wait"
~~~

Para verificar que nuestras configuraciones están quedando guardadas usaremos el siguiente comando que nos mostrara el archivo de configuraciones globales de Git y al haber seleccionado a VS code como IDE predeterminado el archivo se ejecutara en una pestaña de este IDE

_Comando de verificación global_

~~~
Git config --global -e 
~~~

Si queremos trabajar o estamos trabajando con desarrolladores que utilicen un sistema operativo(SO) distinto a Windows como por ejemplo Linux tendremos que configurar los saltos de líneas de nuestro IDE para no tener inconvenientes a la hora de ejecutar códigos de Linux o viceversa 

_Configuración de saltos de líneas para Windows (CRLF)_

~~~
Git config --global core.autocrlf true
~~~

_Configuración de saltos de líneas para Linux (LF)_

~~~
Git config --global core.autocrlf input
~~~

---
Para poder indagar un poco más y saber para que sirve cada una de las configuraciones que acabamos de hacer usaremos un último comando que nos permite ver todos los comandos que se pueden usar en Git.

_Lista Global de comandos de Git_

~~~
Git config -h
~~~




