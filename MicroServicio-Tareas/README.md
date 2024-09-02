

## Manual de instalación
Se requiere de [python](https://www.python.org/ftp/python/3.12.5/python-3.12.5-amd64.exe) instalado en nuestra máquina y añadido al PATH (tener el check de añadir Python al PATH para poder ejecutarlo correctamente en la cmd), una vez con python instalado en la razi del proyecto ejecutamos 

```console
python -m venv env
```

Con este comando creamos una carpeta de entorno la cual almacena las dependencias que se usarán para el proyecto de Python, activamos el entorno con:

Windows

```console
.\env\Scripts\activate
```

Linux

```console
source env/bin/activate
```

Se nos iniciará el entorno e instalaremos las dependencias ejecutando:

```console
pip install -r dependencies.txt
```