## CBDapp

#### Aplicación de prueba sobre CouchDB para la asignatura CBD de Ingeniería del Software

Vamos a explicar paso a paso como utilizar la aplicación en nuestro equipo (preferiblemente bajo Windows, por facilidad con las instrucciones previas de instalación del entorno).

### Descarga

Puedes descargar la aplicación en tu equipo desde [aquí](https://github.com/roberjc/CBDapp).

### Instalación

Para instalar la aplicación debemos estar corriendo previamente nuestro servidor local CouchDB.

* Nos dirigimos a la intefaz web FUTON en nuestro navegador mediante:
> http://localhost:5984/_utils

* Damos en *"Create database..."* en la esquina superior izquierda para crear una nueva base de datos, y elegimos *"item"* como nombre para ella.

* En la nueva base de datos, vamos a *"New document"* en la esquina superior izquierda. 
Cambiamos el id del documento por *"webpage"*. Guardamos el documento dando en *"Save document"* en la esquina superior izquierda.

* Dentro del documento, damos en *"Upload attachement..."*.
Seleccionamos los archivos descargados en el primer paso de esta guía, el archivo **index.html** y **style.css** y damos en *"Upload"* y *"Save document"* respectivamente para cada archivo.

### Acceso a la aplicación

Ahora, podemos acceder a los archivos subidos anteriormente por medio de su URL. Tan solo hay que abrir nuestro navegador e ir a la dirección:

> http://localhost:5984/items/webpage/index.html

