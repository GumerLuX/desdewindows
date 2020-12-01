# desdewindows

'-> Actualizar la primera vez' https://github.com/SinLuX90/arch.git

# Para clonar un repositorio con git bash 'windows'

$ git clone
git clone https://github.com/SinLuX90/arch.git  
.................................................................

Actualizar repositorio " subir archivos"

# 1- Ver los archivos que se van a agregar al repositorio

$ git status

# 2- Para subir archivos al repositorio 'agregar'

$ git add -A ->
$ git add. ->

#Descargar los cambios que se hayan hecho en nuestro repositorio
git pull '-> Actualiza los cambios que hayamos hecho en el repositorio de github'

    	# Ver los commit que se han hecho recientemente
    	$ git log

# Generar un commit de lo subido '-> genera los cambios que se han hecho en repositorio'

$ git commit -m 'version 0.0'

# Para subir los archivos

$ git push origin master '-> subir los cambios al repositorio. pide contraseña'

    ## Resumen

git status
git add .
git pull
git log
git commit -m ''
git push origin master

.................................................................

..............................................................

# para subir archivos desde linux

git add archivo.txt

#Comprovamos el git
git status ->
En la rama master
Cambios a ser confirmados:
(usa "git restore --staged <archivo>..." para sacar del área de stage)
modificado: README.md
modificado: install_arch.sh

Cambios no rastreados para el commit:
(usa "git add/rm <archivo>..." para actualizar a lo que se le va a hacer commit)
(usa "git restore <archivo>..." para descartar los cambios en el directorio de trabajo)

# Actualizamos el commit o version

$ git commit -m "Commit inicial"

#####################################################################

Repositorio arch

https://github.com/SinLuX90/arch.git

…or create a new repository on the command line

echo "# arch" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/SinLuX90/arch.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/SinLuX90/arch.git
git branch -M master
git push -u origin master

…or import code from another repository
