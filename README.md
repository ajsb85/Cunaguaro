¿Qué es cunaguaro?
==================
Es un paquete derivado de Iceweasel respectivamente. Este es una navegador web de Debian GNU/LINUX, la distribución en que se basa canaima. Es un navegador de Internet, con interfaz gráfica de usuario desarrollado por la Corporación Mozilla y un gran número de voluntarios externos.

Características de Cunaguaro
============================

Añadido el Feed RSS de las noticias del portal Canaima a la barra de marcadores.

Añadido a los favoritos las páginas principales desde las cuales se puede interactuar con la comunidad.

Añadido el Plugin “Download StatusBar“, el cual redirige todas las descargas para que se visualicen en una cómoda y compacta barra de descargas en la parte inferior, permitiendo ver el progreso de las mismas, cancelarlas, reanudarlas, entre otras interesantes funcionalidades.

Agregada funcionalidad de búsqueda en tres ámbitos de la Plataforma Canaima: El portal principal, las listas y la wiki. 

Como instalar Cunaguaro
=======================

Abre el archivo /etc/apt/sources.list con tu editor de textos preferido (con permisos de root) y modifícalo de forma tal que sólo queden las siguientes líneas: deb http://repositorio.canaima.softwarelibre.gob.ve/ pruebas usuarios deb http://universo.canaima.softwarelibre.gob.ve/ squeeze main contrib non-free Luego ejecuta los siguientes comandos para instalar Cuanguaro y sus traducciones al español: aptitude update aptitude install cunaguaro cunaguaro-l10n-es-es 