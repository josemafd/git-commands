# git-commands
basic commands for uploading, modifying and deleting files in git

# English

git local

- git init - create a repository locally
- git status - look at the status of our git repository
- git add <folder> - add folder and subfiles to repository
- git commit -m "comment" - validate changes to the repository

- git rm -r <folder> - delete folder from local repository

Whenever a change is made to the local repository it should always be commented with git commit, to validate the changes in our git repository.

To finish uploading it to our git server, we will do the following steps.

git remote

- git remote add origin <url of the repository> - add remote directory to the local repository, this will only be done once.

- git push origin master - upload files to our remote repository to the master root.

# Español

git local

- git init - crear un repositorio de manera local
- git status - mirar estado de nuestro repositorio git
- git add <carpeta> - añadir carpeta y sub archivos al repositorio
- git commit -m "comentario" - validar cambios en el repositorio

- git rm -r <carpeta> - borrar carpeta del repositorio local

Siempre que se haga algún cambio en el repositorio local, siempre habrá que comentarlo con git commit, para validar los cambios en nuestro repositorio git.

Para acabar de subirlo a nuestro servidor git, haremos los siguientes pasos.

git remoto

- git remote add origin <url del repositorio> - añadir directorio remoto al repositorio local, esto únicamente se hará una vez.

- git push origin master - subir archivos a nuestro repositorio remoto a la raíz máster.
