# Práctica 1_Introduccion a GitHub

- Descripción

La práctica nos ha enseñado como se conecta un repositorio local *(con git y el enclace url)* para que se pueda hacer un repositorio en **github**. Esto incluyen los comandos *(add, commit, push)*  que es el procedimiento el cual nos ha de servir para hacer la subida de los documentos de manera correcta para que todos lo podamos ver y saber que añadidos se tienen en cada subida, así como los commit que ponen comentarios de cada subida que se hace.


- Ejcución del programa HolaMundo.py

    1. Se abre una terminal en la carpeta en donde esta guardado el archivo HolaMundo, en este caso seria **https://github.com/Xenki/ProyectoEjemploGit.git**
    2. Se  pone en dicha terminal el comando **python HolaMundo.py**

    3. Mostrará el mensaje *Hola Git*


- Listado de comandos utilizados
    
    - git init
    - git remote add origin https://github.com/Xenki/ProyectoEjemploGit.git
    - git add -A
    - git commit -m  *"Mensaje deseado"*
    - git push origin master
    - git remote -v
    - git status
    - touch .gitignore

- Sobre el archivo *gitignore*


    - Se creo para que al momento de hacer *(add, commit y push)*, ignorara los archivos deseados *(que estan en el archivo .gitignore)* en este caso son todos los archivos que tienen la terminación .deb.

    - Usando el comando git status El programa debe mostrar **On branch master nothing to commit, working tree clean** eso quiere decir que no hay archivos en un término en el cual no se hayan subido. El siguiente paso es verificar el repositorio directamente para revisar que el archvio debug.log no esté.