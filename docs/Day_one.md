##PREPARACION DEL ENTORNO
-Instalar python
-Instalar git
-Instalar Vs code
*descargamos e instalamos el .deb con "sudo apt  install./ nombre del archivo.deb" y reiniciamos el archivo con ctrl+shift+p dentro de vscode

#Creacion de carpetas
-mkdir - crear carpetas
-mkdir ~/ - crear una carpeta desde home
rmdir + nombre de la carpeta - para eliminar

#Iniciamos git
git init 
#Revisamos la version
git --version
#Creamos un entorno virtual
python3 -m venv venv
#Activar el entorno virtual
source venv/bin/activate 
#Por si quieres desactivar
deactivate
#Creamos un gitignore
touch.gitignore
#configuramos git
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
#Agregamos los archivos al stagin
-git status  verificamos el estado
-git add .  agregamos
-git status  verificamos nuevamente

#Primer commit
git commit -m "Initial project structure"

##CREAMOS EL REPOSITORIO EN GITHUB
debemoos crear el repositorio en la web y obtener una URL https
git remote add origin https://github.com/TUUSUARIO/python-dev-journey.git
git branch -M main
git push -u origin main

posterior a ingresar te solicitara un usuario y contrasena los cuales con  1. tu usuario en github y 2. un personal Token que debes generar en configuraciones 

