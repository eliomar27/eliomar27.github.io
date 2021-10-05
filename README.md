# eliomar27.github.io

Configuracion local de Git 

$ git config --global user.name "eliomar"
$ git config --global user.email "eliomar.leon@gmail.com"

clave SSH 
ls -al ~/.ssh      para ver si hay clves SSH presentes:

$ ls -al ~/.ssh 
# Lists the files in your .ssh directory, if they exist

Generar una Nueva Clave SSH
$ ssh-keygen -t ed25519 -C "eliomar.leon@gmail.com"
o 
$ ssh-keygen -t rsa -b 4096 -C "eliomar.leon@gmail.com"
