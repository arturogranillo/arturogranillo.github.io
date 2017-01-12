# Instalación

De la página [http:\/\/www.collab.net\/downloads\/subversion]

(http://www.collab.net/downloads/subversion) descargar el instalador para Windows.

La página solicita que te registres para poder realizar la descarga.

![](/subversion_edge_513/instalacion/images/image001.jpg)

El proceso de instalación es similar a cualquier aplicación de Windows, se muestran las pantallas solo por referencia.

![](/subversion_edge_513/instalacion/images/image002.jpg)

![](/subversion_edge_513/instalacion/images/image003.jpg)

![](/subversion_edge_513/instalacion/images/image004.jpg)

![](/subversion_edge_513/instalacion/images/image005.jpg)

![](/subversion_edge_513/instalacion/images/image006.jpg)

Al finalizar la instalación se abre el archivo readme, leerlo detenidamente.

El instalador cambia y agrega algunas variables de sistema, debemos verificar que no causen problemas.

Además se abre un navegador con la dirección “file:\/\/\/C:\/csvn\/launch.html” con algunas instrucciones iniciales.

![](/subversion_edge_513/instalacion/images/image007.jpg)

Cuando la página muestre “Console Status: Ready” podemos acceder a la aplicación de administración en “[http:\/\/localhost:3343\/csvn”](http://localhost:3343/csvn”).

Usuario: admin

Contraseña: admin

![](/subversion_edge_513/instalacion/images/image008.jpg)

Muestra la página principal de la aplicación de administración.

![](/subversion_edge_513/instalacion/images/image009.jpg)

Cambiar contraseña de administrador.

Ir a Página principal &gt; admin &gt; User Profile

![](/subversion_edge_513/instalacion/images/image010.jpg)

Indicar la nueva contraseña y dar click en “Actualizar”.

![](/subversion_edge_513/instalacion/images/image011.jpg)

Después de cambiar la contraseña de administrador, un asistente nos guiara por la configuración básica del servidor SVN.

Servidor: nombre del servidor con dominio incluido.
Servidor SVN debería servir vía HTTPS: No.
Puerto: 8080.
Directorio raíz del repositorio: C:\scvn\data\repositories.

Dar click en “Save & Continue”.

![](/subversion_edge_513/instalacion/images/image012.jpg)

Al terminar la configuración básica se nos redirige a la página principal.

Dar click en “Empezar” para iniciar el servidor SVN.

![](/subversion_edge_513/instalacion/images/image013.jpg)

Una vez que el servidor SVN está corriendo \(Andando\) podemos comenzar a administrarlo.

![](/subversion_edge_513/instalacion/images/image014.jpg)



