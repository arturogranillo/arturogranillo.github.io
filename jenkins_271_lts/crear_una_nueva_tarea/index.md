# Crear una nueva tarea

Ir a Pantalla principal &gt; Nueva Tarea

Ingresar un nombre para la tarea.

Seleccionar crear un proyecto de estilo libre, no parece un elemento seleccionable, pero con click se selecciona.

Dar click en “OK”.

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image001.jpg)

Aparece la pantalla para configurar la tarea dividida en cinco secciones.

General.- define la configuración general de la tarea.

Si se desea se agrega una descripción.

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image002.jpg)

Configurar el origen del código fuente.- se define de donde se obtiene el código.

Seleccionamos “Subversion” y configuramos.

Repository URL: es la ruta al repositorio SVN.

Credentials: los datos de acceso al repositorio SVN.

Jenkins almacena las diferentes credenciales que usamos para ingresar a los diferentes sistemas, de tal manera que puedan ser reutilizables.

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image003.jpg)

Disparadores de ejecuciones.- se define que dispara la ejecución de nuestra tarea.

Seleccionamos “Consultar repositorio (SCM)”.

Programador: es el periodo en que se verificara el repositorio por cambios en formato cron. Utilizamos “* * * * *”.

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image004.jpg)

Ejecutar.- Se definen que acciones se van a ejecutar con el código fuente.

Añadimos un nuevo paso “Build a Visual Studio Project or solution using MSBuild”

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image005.jpg)

Configuramos la acción de MSBuild.

MSBuild Version: seleccionamos la instalación de MSBuild que deseemos usar.

MSBuild Build File: es la ruta relativa al archivo MSBuild (csproj, sln o xml) desde la carpeta raíz de nuestro código fuente.

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image006.jpg)

Acciones para ejecutar después.- no se modifica.

Dar click en “Guardar”.

Al guardar la configuración nos aparecerá la página principal de nuestra tarea.

Si la configuración se realizo correctamente en poco tiempo veremos cómo se pone en cola y se ejecuta por primera vez la tarea configurada.

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image007.jpg)

![](/jenkins_271_lts/crear_una_nueva_tarea/images/image008.jpg)

Nota : La carpeta donde Jenkins descarga el código es “workspace” en la carpeta de instalación.
