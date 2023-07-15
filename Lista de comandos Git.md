<div align="center">
  
  # Lista de comandos usados en git  
</div>

***

## Comandos de asignación

Este comando nos permite asignar un nombre de usuario al interior de la terminal de Git.
~~~
$ Git config --global user.name "nombre de usuario"
~~~

Este comando nos permitirá asignar un correo electronico al interior de la terminal
~~~
$ gir config --global user.email correoelectronico@gmial.com
~~~

Este otro comando nos permitirá asignar un IDE para trabajar en nuestros proyectos y repositorios
~~~
$ git config --global core.editor "code --wait"
~~~

Este otro comando nos permitirá ver el archivo de configuración global en Vs code donde podremos visualizar la configuración
~~~
$git config --global -e
~~~

 Este comando nos permitira cambiar la propiedad de scritura en distintos sistemas operativos, el comando nos permitira que la escritura sea compatible entre varios sistemas opertarivos.para estotendremos que usar una varible especifica para cada sistema operativo

 _Variables_

   - para Windows (true)
~~~
$git config --global core.autocrlf true
~~~
 
   - para Linux/Mac (input)

~~~
$git config --global core.autocrlf input
~~~


