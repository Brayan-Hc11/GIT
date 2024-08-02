<img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" width="120" height="120"/>

# Introducción a Git

# ¿Qué es GIT?

Git es un sistema de control de versiones distribuido que te ayuda a llevar un seguimiento de los cambios en tu código y colaborar con otros 
desarrolladores. Es una herramienta esencial para el desarrollo de software, ya que te permite gestionar y coordinar el trabajo en proyectos de manera eficiente.

*fuente de información: [Wikipedia](https://es.wikipedia.org/wiki/Git)*

***
## Usos de GIT 

- Git nos permite mantener y mantener un historial de versiones de nuestros proyectos.

- Git nos permite almacenar nuestros códigos tanto de forma local como el la nube.

- Git nos permite trabajar con equipos de desarrolladores de forma Online.

- Git nos permite manipular las versiones que han sido creadas para saber el momento en el que un error se introdujo a producción.

---
## Aplicaciones o herramientas adicionales

- **Git Bash:**  es una aplicación para entornos de Microsoft Windows que ofrece una capa de emulación para una experiencia de líneas de comandos de Git.

---
## Manual de instalación de GIT

### Paso 1: Descarga del ejecutable

Para utilizar la herramienta de GIT en nuestro ordenador es necesario descargarla desde el navegador de nuestra preferencia, para eso podemos dirigirnos a su sitio web dando clic en el siguiente enlace [Downloads-GIT](https://git-scm.com).

Ya que nos encontramos en el sitio web del fabricante, podemos encontrar una ventana de bienvenida al usuario, como la que se muestra a continuación:

_Imagen 1: Origen autor_

![sitio web del fabricante de GIT](/img/image.png)

Al indagar en el sitio web encontraremos un apartado con forma de monitor, en el cuál estará descrita la versión actual del Aplicativo, seguido de esto el botón de instalar. El sitio web del fabricante detecta el sistema operativo (SO) que estemos utilizando, en este caso estamos utilizando Windows.

_Imagen 2: Origen autor_

![Sitio web del fabricante](/img/image-1.png)


Procederemos a descargar la herramienta ejecutable dando clic en el botón de descarga que se nos muestra en pantalla **"Dowload for Windows"**, este botón nos redirige a un apartado en donde seleccionaremos la arquitectura y el método de alojamiento para de nuestra maquina. para este caso seleccionaremos el instalador local(**Standalone Installer**) para la arquitectura **64-bit Git for Windows setup.**

_Imagen 3: Origen autor_

![selección de descarga](/img/image-2.png)

Después de haber seleccionado nuestra arquitectura y que tipo de instalador, será necesario seleccionar el sitio el donde estará alojado el aplicativo.

_Imagen 4: Origen Autor_

![Sitio de alojamiento local](/img/image-3.png)

Después de  seleccionar el alojamiento en nuestra maquina, nos dirigimos al navegador el cual en la parte superior se nos estará mostrando un apartado de descargas, el cual indicara el estado y porcentaje de descarga de nuestro archivo, al finalizar la descarga se cambiara el estado a "hecho" o "Descarga terminaba" dependiendo del navegador que usemos.

_Imagen 5: Origen autor_

![texto alternativo](/img/image-4.png)

---
### Instalación

Después de descargar el aplicativo en nuestro ordenador procedemos a realizar la instalación de esté. La instalación del aplicativo es bastante sencilla, ya que es una instalación tipita de oprimir "**next**"y "**finish**".

---
### Paso 3: Verificación

Ahora debemos de verificar que nuestro aplicativo este instalado correctamente en nuestro equipo. para hacer esto usaremos la consola de comandos de Windows o el símbolo de sistemas, para poder ejecutarla oprimimos la combinación de teclas "**Win + R**", en donde nos mostrara la barra de búsqueda del aplicativo "**Ejecutar**", en esta barra escribimos "**CMD**", para abrir la consola de comandos oprimiremos la tecla enter o el daremos clic al botón de "Aceptar" que se muestra en la parte de inferior de la ventana emergente.


_figura 6: Origen autor_

![image](https://github.com/Brayan-Hc11/GIT/assets/118775234/cb60e16d-f5f8-4c37-9950-d9e647ef7c59)

Para verificar que la instalación ha sido un éxito ejecutaremos el siguiente comando,el cual le dice a nuestro equipo que nos muestre la versión actual que este posee del instalador

~~~
C:\Users\Usuario>Git --version
~~~

de tal forma que se nos mostrará la una línea de comandos en donde se especifica la instancia de alojamiento, el directorio principal y la versión del aplicativo

_Figura 7: Origen autor_

![alt text](/img/image-5.png)

para salir de la consola de comandos ejecutaremos el comando "**Exit**", al insertar este comando se nos cerrará la ventanilla de CMD.

~~~
C:\Users\Usuario>exit
~~~

_Nota:_ 

*En la consola de comandos(CMD) la dirección del directorio principal "**C:\Users\Usario>**" puede variar al igual que la instancia de alojamiento del aplicativo dependiendo del equipo o usuario de sesión en el que estemos trabajando.*
