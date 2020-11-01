<h1>Flask</h1>

Flask es sencillo de aprender, tiene una documentación clara y práctica, es rápido a la hora de renderizar puede ser hasta tres veces más rapido que Django. También es fácil de realizar una API REST, la estructura de un proyecto es flexible y es ideal para aprender desarrollo web con un framework de Python.

<h2>¿Cómo funcionan las aplicaciones web?</h2>

Cuando utilizas una aplicación web puedes interactuar con ella desde una computadora hasta un dispositivo móvil, pero esto no quiere decir que consume el procesamiento de tu dispositivo. Todo lo contrario, se hace en una red de servidores.

Estos servidores unen su poder de procesamiento con el fin transmitir solicitudes a todo el mundo, a su vez utilizar servidores especializados para almacenar los datos con los cuales se está trabajando, así como los datos de los demás usuarios. Como todo esto sucede sin demora alguna, parecerá que la aplicación se está ejecutando de forma nativa en tu dispositivo.

El servidor procesa la información obtenida por el navegador, luego se realizan los procedimientos necesarios de acuerdo a la lógica de negocio de la aplicación para regresar la información solicitada al cliente.

Ejemplo:

Cuando utilizamos Google Drive el cual es una aplicación web y abrimos un documento con Google Docs, el navegador se comunica con los servidores para ver y editar el documento.

A medida que vayas editando el documento, tu navegador trabajará de la mano con los servidores para asegurarse que todos los cambios se estén guardando.

<h2>Hello word flask</h2>

Crear el Entorno Virtual en windows:

Para crear un nuevo virtualenv, necesitas abrir una terminal command prompt y ejecutar

```
python3 -m venv myvenv
```

Se verá así:
```
C:\Users\Name\platzi-flask> python3 -m venv myvenv
```
Donde myvenv es el nombre de tu virtualenv.

Puedes utilizar cualquier otro nombre, pero asegúrate de usar minúsculas y no usar espacios, acentos o caracteres especiales. También es una buena idea mantener el nombre corto. ¡Vas utilizarlo muchas vecesl!

Inicia el entorno virtual ejecutando:

```
C:\Users\Name\platzi-flask> myvenv\Scripts\activate
```
Fuente de texto: https://tutorial.djangogirls.org/es/django_installation/

