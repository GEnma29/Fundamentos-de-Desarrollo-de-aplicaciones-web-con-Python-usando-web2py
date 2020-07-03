# Resumen del capitulo 3(Overview)
## Puesta en Marcha (Startup)
Primero tenemos que empezar a correr nuestro programa existen diversas maneras de hacerlo dependiendo del sistema operativo que se emplee 
en nuestro caso es windows 

   `web2py.exe`
   
al ejecutar la aplicación mostrará la siguiente ventana:
[![Esta es una imagen de ejemplo](http://www.web2py.com/books/default/image/29/en400.png)](https://ejemplo.com)
Nos pedira que escojamos una contraseña para administrador, Por defecto, web2py ejecuta su servidor web en 127.0.0.1:8000 (puerto 8000 en localhost), pero puede ejecutarlo en cualquier dirección IP y puerto disponibles. Puede consultar la dirección IP de su interfaz de red abriendo CMD o PowerSheel y escribiendo ipconfig en Windows o ifconfig en OS X y Linux. 
mostrará la siguiente ventana:

[![Esta es una imagen de ejemplo](http://www.web2py.com/books/default/image/29/en500.png)](https://ejemplo.com)


Le damos click a administrative interface nos pedira la contraseña que elegimos 

[![Esta es una imagen de ejemplo](http://www.web2py.com/books/default/image/29/en600.png)](https://ejemplo.com)


 Nos Mostrará un pantalla que habrá una serie de carpetas:
1. **admin**: la aplicación que está en uso. en esta carpeta podras realizar las siguientes acciones:

    - **Install**: instale una aplicación completando el formulario en la parte inferior derecha de la página. Dé un nombre a la aplicación, seleccione el archivo que contiene una aplicación empaquetada o la URL donde se encuentra la aplicación, y haga clic en "enviar".
    
    - **Unistal**: se da click en el boton correspondiente.
    
    - **Create**: Cree una nueva aplicación escogiendo un nombre y dando click en crear.
   
    - **package**: Una aplicación descargada es un archivo tar que contiene todo, incluida la base de datos. No debe descomprimir este archivo; web2py lo desempaqueta automáticamente cuando se instala con admin.
    
    - **clean up**: los archivos temporales de una aplicación, como sesiones, errores y archivos de caché.
    
    - **enable/disable**: Cuando una aplicación está deshabilitada, no se puede llamar de forma remota, pero no está deshabilitada desde localhost. Esto significa que aún se puede acceder a las aplicaciones deshabilitadas detrás de un proxy. Una aplicación se deshabilita creando un archivo llamado "DESHABILITADO" en la carpeta de la aplicación. Los usuarios que intenten acceder a una aplicación deshabilitada recibirán un error HTTP 503. Puede usar routes_onerror para personalizar la página de error.
    
    
2. **examples**:  contiene documentación interactiva on line y una réplica del sitio oficial de web2py

3. **Welcome**: Esta es la plantilla básica para cualquier otra aplicación web2py

[![Esta es una imagen de ejemplo](http://www.web2py.com/books/default/image/29/en700.png)](https://ejemplo.com)

## Ejemplo (Simple examples)
Crearemos una pequeña App Para el  nombre de Nuestra App pensamos en un gestor de tiempo que le permita al usuario administrar sus actividades diarias. en nuestro caso KalenderApp
luego de introducir el nombre se nos presentara esta pequeña pantalla

![Screenshot](miAPP.png)

