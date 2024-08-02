# Comandos de Git

## Comandos Básicos
- `git init`: Inicializa un nuevo repositorio Git.
- `git clone <url>`: Clona un repositorio remoto.
- `git add <archivo>`: Añade archivos al área de preparación (staging area).
- `git commit -m "<mensaje>"`: Realiza un commit de los cambios añadidos.
- `git status`: Muestra el estado de los archivos en el repositorio.
- `git push`: Sube los commits locales a un repositorio remoto.
- `git pull`: Trae y fusiona los cambios de un repositorio remoto.
- `git fetch`: Descarga los cambios del repositorio remoto sin fusionarlos.

## Ramas y Fusionado
- `git branch`: Lista, crea o elimina ramas.
- `git branch <nombre>`: Crea una nueva rama.
- `git checkout <rama>`: Cambia a una rama existente.
- `git checkout -b <rama>`: Crea y cambia a una nueva rama.
- `git merge <rama>`: Fusiona una rama en la rama actual.
- `git rebase <rama>`: Reaplica commits en la base de otra rama.
- `git stash`: Guarda temporalmente los cambios sin hacer commit.
- `git stash pop`: Recupera los cambios guardados por `git stash`.

## Inspección y Comparación
- `git log`: Muestra el historial de commits.
- `git diff`: Muestra las diferencias entre archivos o commits.
- `git show <commit>`: Muestra información sobre un commit específico.
- `git blame <archivo>`: Muestra quién modificó cada línea de un archivo.
- `git log --graph`: Muestra un gráfico del historial de commits.

## Manipulación de Commits
- `git reset <commit>`: Deshace los commits y mueve la rama actual a un commit específico.
- `git revert <commit>`: Crea un nuevo commit que revierte los cambios de un commit específico.
- `git cherry-pick <commit>`: Aplica los cambios de un commit específico a la rama actual.
- `git rebase -i <commit>`: Realiza una rebase interactiva para reordenar, combinar o modificar commits.

## Configuración y Ayuda
- `git config`: Configura opciones de Git (usuario, editor, etc.).
- `git config --global user.name "<nombre>"`: Establece el nombre del usuario.
- `git config --global user.email "<email>"`: Establece el correo electrónico del usuario.
- `git help <comando>`: Muestra la ayuda para un comando específico.

## Remotos
- `git remote -v`: Muestra las URL de los repositorios remotos.
- `git remote add <nombre> <url>`: Añade un nuevo repositorio remoto.
- `git remote remove <nombre>`: Elimina un repositorio remoto.
- `git remote rename <antiguo_nombre> <nuevo_nombre>`: Renombra un repositorio remoto.
- `git remote set-url <nombre> <url>`: Cambia la URL de un repositorio remoto.

## Etiquetas
- `git tag`: Lista las etiquetas.
- `git tag <nombre>`: Crea una nueva etiqueta.
- `git tag -d <nombre>`: Elimina una etiqueta.
- `git push origin <etiqueta>`: Envía una etiqueta a un reposit