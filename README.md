### Proyecto1 
###### ## Es un proyecto para el curso de git y git hub

- git init -> crea el repositorio.


- git add . -> subes los cambio de tus archivos.


- git log [archivo] -> ves los .


- git show


- git status

- git branch [nombre de la nueva rama] -> Sirve para crear una nueva rama al proyecto

- git checkout [rama] -> Sirve para moverse entre las ramas


- Generar una nueva llave SSH: (Cualquier sistema operativo)

- ssh-keygen -t rsa -b 4096 -C "youremail@example.com"

*Comprobar proceso y agregarlo (Windows)*

    eval $(ssh-agent - s)
    ssh-add ~/.ssh/id_rsa

*Comprobar proceso y agregarlo (Mac)*

    eval "$(ssh-agent -s)"

    git reset --soft HashDelHEAD te mantiene lo que tengas en staging ahí.
    git reset --hard HashDelHEAD resetea absolutamente todo incluyendo lo que tengas en staging.

git reset es una mala práctica, no deberías usarlo en ningún momento; debe ser nuestro último recurso.
