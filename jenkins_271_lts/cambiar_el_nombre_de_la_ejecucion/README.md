# Cambiar el nombre de la ejecución

Cada vez que se ejecuta la tarea, Jenkins asigna un número consecutivo como nombre a la ejecución.

![](/jenkins_271_lts/cambiar_el_nombre_de_la_ejecucion/images/image001.jpg)

Configuraremos Jenkins para mostrar el número de versión de SVN.

Instalar el complemento “Build Name Setter Plugin”.

Este complemento agregara una nueva sección a la configuración de las tareas “Entorno de ejecución”.

Activar la opción “Set Build Name”.

Build Name: #${ENV,var="svn_revision"}

![](/jenkins_271_lts/cambiar_el_nombre_de_la_ejecucion/images/image002.jpg)

Ahora al ejecutar la tarea mostrara el numero de versión SVN.

![](/jenkins_271_lts/cambiar_el_nombre_de_la_ejecucion/images/image003.jpg)
