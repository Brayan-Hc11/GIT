<div align="center">
  <img src="https://github.com/Brayan-Hc11/devicon/blob/master/icons/git/git-original-wordmark.svg" height="80"/>
  
  # Lista de comandos usados en git  
</div>

***

<details>
  <summary>
   <h2>Comandos de asignación</h2>
  </summary>
  Este comando nos permite asignar un nombre de usuario al interior de la terminal de Git.

~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ Git config --global user.name "nombre de usuario"
~~~

***
Este comando nos permitirá asignar un correo electronico al interior de la terminal
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ gir config --global user.email correoelectronico@gmial.com
~~~

***
Este otro comando nos permitirá asignar un IDE para trabajar en nuestros proyectos y repositorios
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ git config --global core.editor "code --wait"
~~~
***

Este otro comando nos permitirá ver el archivo de configuración global en Vs code donde podremos visualizar la configuración
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$git config --global -e
~~~
***

 Este comando nos permitira cambiar la propiedad de scritura en distintos sistemas operativos, el comando nos permitira que la escritura sea compatible entre varios sistemas opertarivos.para estotendremos que usar una varible especifica para cada sistema operativo

 _Variables_

   - para Windows (true)
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$git config --global core.autocrlf true
~~~
 
   - para Linux/Mac (input)

~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$git config --global core.autocrlf input
~~~
***

El siguiente comando nos permite abrir la barra de configuraciones disponibles en GIT
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ git config -h
~~~
***

</details>

***
<details>
  <summary>
   <h2>Comandos de utilidad</h2>
  </summary>
Para limpiar la terminal despues de haberce llenado ocuparemos el comando de limpieza general
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ clear
~~~
***

para saber la ubicación en la que nos encontramos usaremos un comando que nos permitirá saber el directorio en el que nos encontramos ubicados
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ pwd
~~~
***

ahora que sabemos en que directorio nos encontramos, queremos ver el contendido de este dirextorio para eso usaremos el siguiente comando
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ ls
~~~
***
</details>

***
<details>
  <summary>
   <h2>Comando de movimiento dentro de la terminal</h2>
  </summary>

Para poder movilizarnos entre las distintas estancias y carpetas que tenemos disponibles usaremos una serie de comando de movimiento:

_comando para poder movernos entre carpetas_

**especificaciónes:** Para este comando incicaremos el nombre de la carpeta a la que queremos ir.
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$ cd nombre/
~~~

_Ejemplo:_

~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~
$cd Documents/
~~~

**Salida emergente de la terminal (en caso de estar en Windows)**
~~~
Usuario@DESKTOP-LDCDO8M MINGW64 ~/Documents
$ |
~~~
***

para salir de la carperta actual usaremos el comado de retroceso de navegación
~~~
$cd ..
~~~

_Nota:_ Importante tener en cuenta el espacio que se encuentra entre los puntos y el camndo.

**Salida emergente de la terminal (en caso de estar en Windows)**
~~~
Usuario@DESKTOP-LDCDO8M MINGW64 ~
$ |
~~~
***
</details>

***
<details>
  <summary>
    <h2>Creación y manipulación de directorios o carpetas</h2>
  </summary>


Para poder crear una carpeta nueva es necesario conocer la ubicación actual en la que nos escontramos con ayude del comando (pwd) podemos hacerlo, ya conociendo la ubicación en la que estamos usaremos el comando de (mkdir) seguido del nombre que queremos darle a nuestra nueva carpeta.

_Ejemplo:_
~~~
Usuario@DESKTOP-LDCDO8M MINGW64 ~/Downloads
$mkdir miweb
~~~
</details>

***
<details>
  <summary>
     <h2>Inicialización de un repositorio</h2>
  </summary>

inicializaremos un repositorio desde GIT, para esto estaremos ubicados en la ruta en donde queremos que se inicialice el repositorio

~~~
Usuario@DESKTOP-LDCDO8M MINGW64 ~/Downloads/miweb
$git init
~~~

**salida emergente de la terminal**
~~~
Usuario@DESKTOP-LDCDO8M MINGW64 -/Downloads/miweb
$git init
Initialized empty Git repository in C:/Users/Usuario/Dowloads/miweb/.git/

Usario@DESKTOP-LCDDO8M MINGW64 ~/Downloads/miweb (master)
$|
~~~
***

como nuestro repositorio tiene la extencion (/miweb/.git/) quiere decir que es un directorio oculto y que no lo podremos ver, a no ser de que ejecutemos el diguiente comando que nos permitira el contenido oculto que no podemos ver con los comando de (pwd) y (ls)

~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~/Downloads/miweb (master)
$ls -a
~~~

**salida emergente de la terminal**
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~/Downloads/miweb (master)
$ls -a
. / ../ .git/
~~~
***
</details>

***
<details>
  <summary>
    <h2> Detalle de implementación </h2>
  </summary>

Ahora que nos encontramos en el repositorio nos moveremos al contenido del archivo de la siguiente forma, esto para lograr ver el detalle de implementación que git nos ofrece en la creación de repositorios.
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~/Downloads/miweb (master)
$cd .git/
~~~

como salida emergente tendremos el siguiente resultado:
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~/Downloads/miweb (GIT_DIR!)
$|
~~~

ahora queremos ver las herramientas que GIT nos ofrece para la creación de repositorios para esto usaremos el comando de (ls -a)

_Ejecución_
~~~
Usario@DESKTOP-LCDDO8M MINGW64 ~/Downloads/miweb (GIT_DIR!)
$ls -a
. / ../ HEAD config description hooks/ info/ objects/ refs/
~~~
</details>

***








































