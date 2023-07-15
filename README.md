<div align="center">
<img src="https://github.com/Brayan-Hc11/devicon/blob/master/icons/git/git-original-wordmark.svg" height="80"/>

Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.
</div>

***
## Instalación de GIT

### Paso 1: Descarga
Para poder instalar git en un ordenador deberas dirigirte al sitio web oficial de [GIT](https://git-scm.com), en esta pagina descargaremos el ejecutable para GIT que nuestro equipo requiere, afortunadamente el aplicativo web identifica el SO de nuestro equipo por ende oprimimos el boton de "Dowloand for Windows" en caso de tener un sistema operativo de Windows, sino es el caso procedemos a selecionar el sistema operativo que estemos usando.

_figura 1_
![image](https://github.com/Brayan-Hc11/GIT/assets/118775234/398fd2cd-75ee-469a-8136-2fa7d7f82a12)

### Paso 2: Instalación
Despues de descargar el aplicativo en nuestro ordenador procedemos a realizar la instalación de esté. La instalación del applicativo es bastante sencilla, ya que es una instalación tipita de oprimir "next"y "finish"

### Paso 3: Verificación
Ahora debemos de verificar que nuestro aplicativo este instalado correctamente en nuestro equipo. para hacer esto usaremos la consola de comandos de Windows o el simbolo de sistemam, para poder ejecutarla oprimimos la combinación de teclas "Win + r", en donde nos mostrara la barra de busqueba del aplicativo "Ejecutar" donde digitaremos "CMD", para abir la consola de comandos oprimiremos la tecla enter o el boton de "Aceptar" que se muestra en la parte de abajo.  

_figure 2_

![image](https://github.com/Brayan-Hc11/GIT/assets/118775234/cb60e16d-f5f8-4c37-9950-d9e647ef7c59)

Para verificar que la instalación ha sido un exito ejecutaremos el siguiente comando,el cual le dice a nuestro equipo que nos muestre la versión actual que nuestro equipo posee
~~~
C:\Users\Usuario>Git --version
~~~

de tal forma que se nos mostrará la una línea de comandos en donde se nos especifica la instancia de alojamiento, el direcitorio principal y la versión del aplicativo

_Figura 3_

![image](https://github.com/Brayan-Hc11/GIT/assets/118775234/76e85202-b608-4e23-b62c-b8c0038a30e3)

para salir de la consola de comandos ejecutaremos un comando de salida, al insertar este comando se nos cerrará la ventanilla en donde vemos las CMD.
~~~
C:\Users\Usuario>exit
~~~

_Nota:_ En la consola de comandos la dirección del directorio principal "C:\Users\Usario>" puede variar al igual que la instancia de alojamiento del aplicativo dependiendo del equipo en donde estemos trabajando.

## Paso 4: Configuración de Git
Para poder donfigurar GIT usaremos dos comandos. uno nos permite asignar un nombre de usuario dentro de la terminal y el otro nos dejara asignar un correo electronico. Estos comandos deben de ser ejecutados en la terminal de git, la cuál lleva el nombre de (GitBash).

_Primer comando de asignación de nombre de usuario_

_figura 3_

![image](https://github.com/Brayan-Hc11/GIT/assets/118775234/55941c93-87a6-460c-9ab9-765ce7f1dfea)

_El segundo comando nos permnitira asignar un correo electronico_

_Figura 4_

![image](https://github.com/Brayan-Hc11/GIT/assets/118775234/739a55e4-7b20-438c-9032-4c1eb777a334)

## Paso 5: Configuración de  IDE(Vs Code)
En nuestro caso estaremos usando el editor de texto Vs Code, para configurar [Vs Code](https://code.visualstudio.com) desde nuestra terminal de GIT debemos de habeelo instalado previamente, a continuacion le indicaremos a GIT que usaremos Vs Code como nuestro editor de texto por medio de un comando.

_Figura 5_

![image](https://github.com/Brayan-Hc11/GIT/assets/118775234/75d6102e-9710-4a0f-b3f6-e3317bc939f8)

Para poder visualizar la configuración global usaremos un comando que nos mostrará las configuraciones que hemos hecho.

~~~
git config --global -e
~~~
_Nota:_ Despues de ejecutar este comando se nos abrira la una ventana de Vs code donde se nos mostrará la lista de configuraciones que estaremos realizando.

## Paso 6: Configuración de escritura
Para poder definir un método de escritura en GIT es necesario el siguiente comando, ya que cada sistema operativo usa un metodo de escritura distinto para Git es dificl llegar a convertir este tipo de caracteres a caracteres legibles para los programadores.

_Nota:_ Este comando posee dos valores muy importantes, que dependiendo del sistema operativo este va a cambiar:

 - Para Windows
   
~~~
$ git config --global core.autocrlf true
~~~

  - Para Mac/Linux

~~~
$ git config --global core.autocrlf input
~~~










































































