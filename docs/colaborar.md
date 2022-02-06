
## Requirements

MkDocs requires a recent version of Python and the Python package manager, pip, to be installed on your system.

You can check if you already have these installed from the command line:

```
$ python --version
Python 3.8.2 
```
```
$ pip --version
pip 20.0.2 from /usr/local/lib/python3.8/site-packages/pip (python 3.8)
```
## Installation


#### Installing pip
If you're using a recent version of Python, the Python package manager, pip, is most likely installed by default. However, you may need to upgrade pip to the lasted version:

`$ pip install --upgrade pip`<br>
If you need to install pip for the first time, download `get-pip.py` . Then run the following command to install it:

`$ python get-pip.py`

### Installing MkDocs
Install the mkdocs package using pip. To install MkDocs, run the following command from the command line:

`$ pip install mkdocs`

You should now have the mkdocs command installed on your system.
Run `mkdocs --version` to check that everything worked okay.

```
$ mkdocs --version
mkdocs, version 1.2.0 from /usr/local/lib/python3.8/site-packages/mkdocs (Python 3.8)
```


## ¿Cómo colaborar?

1. Clonate el repo:

    SSH: 

        git@github.com:sergio-gonzalez-sainz/apuntes-kodemia.git

2. Crea una carpeta en tu equipo. Entra a la carpeta en tu terminal.
    
    2.2  Posicionado en la carpeta que creaste (en tu terminal), copia lo siguiente: 

        git clone git@github.com:sergio-gonzalez-sainz/apuntes-kodemia.git

3. Crea una rama: 

         git branch nombreDeTuRama

4. Cambiate a tu rama: 

        git switch nombreDeTuRama
    Puede que si tienes una versión de git menor a **2.25.0** (para revisar la versión utiliza `git --version` ) no reconozca el `switch`, para ese caso puedes usar:

         git checkout nombreDeTuRama

5. Para visualizar el sitio debes levantar un pequeño servicio con el siguiente comando:
       
        mkdocs serve

    Te debe levantar el sitio en `http://127.0.0.1:8000/`.

    Para este punto ya puedes empezar a editar la documentación en tu editor de texto favorito. Estaría chido que ingresaras a los siguientes sitios:
        
    * Acá aprenderás la sintáxis básica para escibir: [Markdown](https://www.markdownguide.org/basic-syntax/)
    * Aqui un contéxto de que es [MKdocs](https://www.mkdocs.org/user-guide/writing-your-docs/), que es con lo que esta hecha esta documentación

6. Cuando termines se hacer tu aportación, guarda tus cambios y en terminal realiza un **push**: 
            
            git push --set-upstream origin nombreDeTuRama

7. Ve a [GitHub](https://github.com/sergio-gonzalez-sainz/apuntes-kodemia/pulls) y crea un Pullrequest  