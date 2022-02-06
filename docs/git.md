# Taller de Git y GitHub 

Git nos va a ayudar a darle un seguimiento específico a archivos. 
Nos permite administrar los cambios por archivo. Responde a:
* ¿Quien hizo el cambio?
* ¿Cuando hizo el cambio?

Al final Git es un sistema de control de versiones sobre un archivo o un conjunto de archivos a lo largo del tiempo. 

***VCS - Version Control System***

Git es para registral los cambios de manera atómica. 

## Versionamiento

### ¿Que es Git?

SCV distribuido. 
Pensando en la eficienciaa y confiabilidad del mantenimiento de las versiones del proyecto con muchos archivos. 
Optimizado para guardad todos los cambios de manera atómica e incremiental. 
Mas eficiente con archivos de texto plano, que con binarios.Quiere decir que no puede trabajar de manera optima con pdf o archivos codificados.

## Conceptos Base

### Directorio Git
Directorio ``.git ``.
Repositorio local donde se almacenan los metadatos y la base de datos. Este directorio es el que se clona entre computadoras.
### Stagin area
Archivo que define el staging AREA. Antesala donde van a esperar mis cambios. 
Almacena información acerca de lo que ca a ir en la próxima confirmacion. (commit).

PWD - present working directory 

``Git init`` - nos permite inicializar un repositorio. 

``Git add - ``  es para darle seguimiento al un archivo en especifico. 

``git add`` sirve para pasarlo al staging area 

Si quiere eliminarlos del staging area 
se utiliza 

    ``git rm --cached``

``git config --local ``

``git commit -m "version 1"``

envía los últimos cambios registrados a la base del sistema de versionamineto. 
La opción -m permite colocar un ""nombre" a este registro. 

``git status``: nos revela los últimos cambios.

``git rm --cached miArchivo``: nos quita los archivos.

``git show``:nos va a mostrar el cambio que se ha commiteado.

``git show miArchivo``: me va a mostrar la comparación de ``git diff id-1 id-2``

``git log``: Nos va a mostrar el historico completo de cambios.

Descargamos [Starship](https://starship.rs/guide/#%F0%9F%9A%80-installation) 

1. Primero se descargan las fuentes 
2. Luego se ejecuta un comando sh -c "$(curl -fsSL https://starship.rs/install.sh)"
3. Luego se intala el archivo de HomeBrew brew install starship

``git checkout``: Sirve para cambiarme a un commit en un momento en el tiempo. Para commit especificos 

``git switch``: se hace sobre una rama. y siempre nos va a llevar al presente de la rama.

``gitignore``: el git ignore, ayuda a que cuando se suba al reporsitorio ignore especificos archivos o Lo que hacemos es que creamos un archivo llamado .gitignore y en ese archivo ponemos todo lo que deseamos ignorar, archivos y carpetas. 

## Trabajo colaborativo
Repositorio remoto, para trabajar en un proyecto remoto le damos clic

        git clone URL

Cuando se hace un git clone, ya no es necesario hacer un ``git init`` ya que ya tenemos una carpeta .git 

``git push``:  Es lo que voy a utilizar para subir lo que tengo commiteado al repositorio remoto


## Claves de encriptacion
La comunicación con GitHub y mi computadora se tieen que hacer de manera cifrada, para eso se utiliza una llave pública
y una privada.

Esto se hace cada que se cambia de equipo. Se genera una llave, para ello abrimos terminal y 
    ssh-keygen -t ed255119 -C "miCorreo"

``eval "$(ssh-agent -s)"``

Cuando se le da enter se les tiene qu aparecer el Pid agent 

se tiene que crear un archivo de .config 
para eso se hace con nano y "config"
    
## Reporitio en GitHub

Se copia el ssh y se va a la terminal 

         git remote add origin URL 

El "origin" se llama Alias.
para confirmar que esta todo bien se hace ``git remote`` o ``git remote -v``
Ya que se configuro, se puede hacer push.
Cuando ya tenemos un repositorio para hacer push se hace lo siguinte:

        git push --set-upstream origin master

Para sabes si esta actualiza pongo 

        git fetch

y luego hacemos 

        git status

y si la queremos actulizar hacemos un ``git pull``

## Trabajo colaborativo en GitHub

1. ``git clone <ssh link>``

2. ``git branch <rama>``

3. ``git switch <rama>``

4. Editar archivo

5. ``$git add .``

6. ``git commit -m "texto"``

7. ``git push --set-upstream origin < nombre de mi rama>``

8. Ir a GitHub y crear pull request

### Si hay conflictos

1. Cambiar a main/master

        git switch main

2. ``git pull``
3. ``git marge main``
4. Hacemos los cambios 
5. git push --set-upstream origin <nombre de rama>
6. Ir a github y crear pull request 



    
    
















