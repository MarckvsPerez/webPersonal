=============================================
=            Estructura de carpetas          =
=============================================

Controllers - Contiene los controladores, que son las funciones que se ejecutan
cuando se llama a una petición HTTP.

Middlewares - Contiene las funciones que se van a ejecutar en mitad de una petición para 
validar si una petición es autenticada.

Models - Contiene los archivos de definición de modelos.

Router - Contiene los archivos de enrutamiento de la App

Upload - Donde se van a subir los ficheros que añadamos desde la App

Utils - Contiene archivos con funciones comunes y de uso general para toda la aplicación. 
Estos archivos pueden ser importados y utilizados en otras partes del proyecto para evitar 
la repetición de código y facilitar su mantenimiento.

node_modules - La carpeta "node_modules" es una carpeta que se crea en un proyecto de 
Node.js cuando se utiliza el administrador de paquetes npm (Node Package Manager) para 
instalar módulos de Node.js. Esta carpeta contiene todos los paquetes de dependencias 
que se instalan en el proyecto, y cada paquete se instala en su propia carpeta dentro de 
la carpeta "node_modules".

=====  End of Estructura de carpetas  ======


=============================================
=          Documentación del codigo         =
=============================================

La Documentación del código se encuentra detallada por secciones dentro de los archivos.
De este modo se consigue una mejor comprensión, pero aumentan el número de líneas
totales. Para mejorar la legibilidad, recomiendo usar los siguientes atajos de teclado:

Ctrl+k Ctrl+0 - Colapsar todas las secciones.
Ctrl+k Ctrl+j - Desplegar todas las secciones.
Ctrl+k Ctrl+ç - Colapsar todas las secciones de comentarios

Estos son los atajos de teclado predeterminados de VisualStudio, si se han modificado
anteriormente o se usa otro editor de texto, los comandos corresponden a:

Ctrl+k Ctrl+0 - Fold all
Ctrl+k Ctrl+j - Unfold all
Ctrl+k Ctrl+ç - Fold all block comments.

=====  End of Documentación del codigo ======