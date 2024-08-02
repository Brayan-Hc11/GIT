![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?style=flat-square&logo=markdown&logoColor=white)

# Comandos en Git

Para ejecutar los comandos a continuación, es necesario utilizar la terminal de comandos incluida con la instalación de Git. A partir de ahora, utilizaremos la terminal de Git Bash para ejecutar estos comandos.

## Sintaxis de comandos

# Comandos en Git

Git es un sistema de control de versiones distribuido, diseñado para manejar todo tipo de proyectos con rapidez y eficiencia. Permite a los equipos de desarrollo colaborar en el mismo proyecto, manteniendo un historial de todos los cambios realizados.

Para ejecutar los comandos a continuación, es necesario utilizar la terminal de comandos incluida con la instalación de Git. A partir de ahora, utilizaremos la terminal de Git Bash para ejecutar estos comandos.

## Sintaxis de comandos

|   Comando             |   Acción                                                                                         |   Sintaxis                                       | Ejemplo |
|:----------------------|:-------------------------------------------------------------------------------------------------|:-------------------------------------------------|:--------|
| `ls`                  | Nos permite listar todas las instancias que se encuentren en ese directorio.                     | `$ ls`                                           | `$ ls`  |
| `pwd`                 | Nos muestra la ubicación actual de nuestra navegación.                                           | `$ pwd`                                          | `$ pwd` |
| `cd`                  | Nos permite movernos entre las distintas instancias que se encuentran en nuestro equipo local.   | `$ cd <directorio>`                              | `$ cd proyecto/` |
| `cd ..`               | Nos permite salir o retroceder del directorio en el que nos encontremos ubicados.                | `$ cd ..`                                        | `$ cd ..` |
| `mkdir`               | Nos permite la creación de directorios.                                                          | `$ mkdir <nombre del directorio>`                | `$ mkdir nuevo_directorio` |
| `git init`            | Nos permite inicializar un repositorio de Git.                                                   | `$ git init`                                     | `$ git init` |
| `ls -a`               | Nos muestra todos los archivos, incluidos los ocultos.                                           | `$ ls -a`                                        | `$ ls -a` |
| `git status`          | Nos permite saber el estado actual de nuestro repositorio.                                       | `$ git status`                                   | `$ git status` |
| `git add`             | Agrega archivos al área de preparación (staging area).                                           | `$ git add <nombre del archivo>`                 | `$ git add index.html`<br>`$ git add .` |
| `git restore`         | Nos permite restaurar cambios en el directorio de trabajo.                                       | `$ git restore <nombre del archivo>`             | `$ git restore index.html` |
| `git commit`          | Crea un commit con los cambios confirmados.                                                      | `$ git commit -m "Descripción del commit"`       | `$ git commit -m "Añadir la estructura inicial del proyecto"` |
| `rm`                  | Nos permite eliminar un archivo.                                                                 | `$ rm <nombre del archivo>`                      | `$ rm archivo.txt` |
| `mv`                  | Nos permite mover o renombrar un archivo.                                                        | `$ mv <nombre actual> <nuevo nombre o ubicación>`| `$ mv archivo.txt archivo_renombrado.txt`<br>`$ mv archivo.txt ../nuevo_directorio/` |
| `git diff`            | Nos muestra las diferencias entre los cambios actuales y los anteriores.                         | `$ git diff`                                     | `$ git diff` |
| `git diff --staged`   | Nos muestra las diferencias entre los cambios en staging y los anteriores.                       | `$ git diff --staged`                            | `$ git diff --staged` |
| `git log --oneline`   | Nos muestra el historial de cambios realizados en el repositorio en un formato simplificado.     | `$ git log --oneline`                            | `$ git log --oneline` |
| `git branch`          | Nos permite saber en qué rama de nuestro proyecto nos encontramos.                               | `$ git branch`                                   | `$ git branch` |
| `git checkout -b`     | Nos permite crear una nueva rama y movernos a ella.                                              | `$ git checkout -b <nombre de la rama>`          | `$ git checkout -b feature/nueva-funcionalidad` |
| `cat`                 | Nos permite ver el contenido de un archivo.                                                      | `$ cat <nombre del archivo>`                     | `$ cat archivo.txt` |
| `git checkout`        | Nos permite movernos entre las ramas disponibles en el repositorio.                              | `$ git checkout <nombre de la rama>`             | `$ git checkout main` |
| `git remote add`      | Nos permite agregar un repositorio remoto (e.g., GitHub).                                        | `$ git remote add <nombre> <URL del repositorio>`| `$ git remote add origin https://github.com/usuario/repositorio.git` |
| `git push -u origin main` | Sube los cambios recientes al repositorio remoto en la rama principal.                      | `$ git push -u origin main`                      | `$ git push -u origin main` |
| `git branch -M main`  | Nos permite cambiar la rama predeterminada de `master` a `main`.                                 | `$ git branch -M main`                           | `$ git branch -M main` |

## Referencias

- [Documentación oficial de Git](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Learning Lab](https://lab.github.com/)


![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?style=flat-square&logo=markdown&logoColor=white)
