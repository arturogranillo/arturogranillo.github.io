# Cambiar puerto

Jenkins se ejecuta por defecto en el puerto 8080 y como el servicio de SVN se ejecuta en el mismo puerto debemos cambiarlo.

Debemos cerrar la sesión dando click en “Desconectar” en la esquina superior derecha.

Jenkins se instala como servicio de Windows, debemos detenerlo.

En la carpeta de instalación está un archivo Jenkins.xml.

El archivo lo debemos abrir con permisos de administrador.

En el nodo “arguments” debemos cambiar el valor del parámetro “–httpPort” de “8080” a “8081”.

Reiniciamos el servicio de Jenkins y accedemos con “localhost:8081”

