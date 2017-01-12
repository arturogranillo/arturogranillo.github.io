# Cargar un repositorio

Suponer que se tiene una carpeta para nuestra solución de Visual Studio y que esa carpeta contiene el archivo sln y la(s) carpeta(s) individual(es) de los proyectos.

Además debemos tener instalado TortoiseSVN (Cliente de SVN).

![](/subversion_edge_513/cargar_un_repositorio/images/image001.jpg)

En cualquier lugar libre de la carpeta dar click derecho > SVN Checkout.

![](/subversion_edge_513/cargar_un_repositorio/images/image002.jpg)

Indicamos la ruta del repositorio usando la dirección IP.

Dar click en “OK”.

![](/subversion_edge_513/cargar_un_repositorio/images/image003.jpg)

Aparece una advertencia de que el directorio no está vacío.

Dar click a “Si”.

![](/subversion_edge_513/cargar_un_repositorio/images/image004.jpg)

Aparece la bitácora del checkout.

Al terminar muestra el mensaje “Completed”.

Dar click en “OK”.

![](/subversion_edge_513/cargar_un_repositorio/images/image005.jpg)

En la carpeta de nuestra solución aparecerá una carpeta “.svn”.

![](/subversion_edge_513/cargar_un_repositorio/images/image006.jpg)

Seleccionar todos los elementos de la carpeta, excepto la carpeta “.svn”.

Dar click derecho > TortoiseSVN > Add.

![](/subversion_edge_513/cargar_un_repositorio/images/image007.jpg)

Aparece una ventana con todos los archivos que vamos a agregar.

Deben aparecer todos los archivos y carpetas seleccionados incluyendo los archivos y carpetas que están dentro de las carpetas seleccionadas.

Dar click en “OK”.

![](/subversion_edge_513/cargar_un_repositorio/images/image008.jpg)

Aparece la bitácora del agregado de los archivos.

Al terminar muestra el mensaje “Completed”.

Dar click en “OK”.

![](/subversion_edge_513/cargar_un_repositorio/images/image009.jpg)

Una vez que los archivos están agregados debemos seleccionar cuales se van a ignorar.

En este caso debemos ignorar la carpeta .vs y dentro de la carpeta del proyecto(s) las carpetas bin y obj.

Para excluir una carpeta (o archivo) se debe dar click derecho > TortoiseSVN > Unversion and add to ignore list > nombreCarpeta(recursively)

Seleccionamos “recursively” para ignorar la carpeta y todos los archivos que contiene.

Se muestra el proceso para la carpeta “.vs”.

![](/subversion_edge_513/cargar_un_repositorio/images/image010.jpg)

Después de seleccionar se muestra el mensaje de confirmación.

![](/subversion_edge_513/cargar_un_repositorio/images/image011.jpg)

Aplicar el mismo proceso a las carpetas bin y obj.

En la carpeta de la solución dar click derecho > SVN Commit.

![](/subversion_edge_513/cargar_un_repositorio/images/image012.jpg)

Aparece una ventana mostrando los archivos que se van a subir al servidor.

No deben aparecer los archivos que ignoramos en el paso anterior.

Colocamos un mensaje descriptivo para el commit.

Dar click en “OK”.

![](/subversion_edge_513/cargar_un_repositorio/images/image013.jpg)

Aparece la ventana de bitácora para el commit.

Al terminar muestra el mensaje “Completed”.

Dar click en “OK”.

![](/subversion_edge_513/cargar_un_repositorio/images/image014.jpg)

Listo
