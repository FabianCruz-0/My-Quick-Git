# Instructions and tricks that I use for git.
<hr>

## **Para clonar un repo en una carpeta "non empty":** <br>
git init. <br>
git remote add origin PATH/TO/REPO. <br>
git fetch. <br>
git reset origin/master  # Required when the versioned files existed in path before "git init" of this repo. <br>
git checkout -t origin/master. <br>

<hr>

1. clonar el repo de github y ponerlo en nuestra pc. <br>
2. dentro de éste agregamos los archivos que queremos subir. <br>
3. en la carpeta raíz damos click derecho y "git bash here". <br>
4. git add "Archivo a subir". <br>
5. git status verás todos los archivos seleccionados. <br>
*Si añadieron un archivo que no querian con "git add <archivo>" y se olvidaron*
*de colocarlo en  ".gitignore" (Antes de hacer un commit) utilizar "git reset -archivo-"* <br>
6. git commit -m "initial commit". <br>
7. git push.

<hr>

* git init.
* git add <file> Pasa los docs a staging area.
* git add . Pasa todos los archivo.
* git commit Pasa los docs de staging area a repository (Después de esto se te va a abrir el editor de código VIN en donde tendrás que escribir un comentario, si se quiere evitar abrir VIN entonces utilizar:)
* git commit -m "comentario" Lo mismo que el commit regular, pero ahora no necesitas entrar a VIN.
* git status Ver en que status (wd, sa, r) están los docs.
* git push Subir los docs a un server (Github).
* git pull  Traer los docs de un server, traer los cambios de tus compañeros.
* git clone Hacerte una copia de lo que está en el server a tu PC.
* git checkout -- <file> Para revertir los cambios de los archivos.
* git diff <file> Para ver las diferencias hechas en los archivos.
* git branch Ver las ramas que hay ("master" es la rama default).
* git branch "nombre" Crear una nueva rama.
* git checkout "nombre" Ir a una rama en especifico.
<hr>
*  git config -- global user.email "email" Para configurar email del usuario. <br>
*  git config -- global user.name "nombre" Para configurar nombre del usuario.

