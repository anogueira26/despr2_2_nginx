# Descripción del proyecto:

El objetivo de esta práctica es instalar y congurar Nginx en una máquina virtual (Ubuntu 22.04) y desplegar
sitio web estático sencillo con navegación entre páginas, imágenes y estilos.

# Pasos seguidos para la instalación y despliegue. 

Actualizar paquete de la maquina web
![updatemachine](/despr2_2_nginx/img/update.png)

Instalar nginx
![installnginx](/despr2_2_nginx/img/installnginx.png)

# Capturas de pantalla del proceso: configuración, comprobaciones, estructura de archivos, página cargada y navegación.

ccede desde el host a http://localhost:8082
![webdef](/despr2_2_nginx/img/webantesdemodificar.png)

Configura de red:
![configred](/despr2_2_nginx/img/config%20de%20red.png)

Configura el firewall para permitir tráfico HTTP y HTTPS:
![confifirewall](/despr2_2_nginx/img/configfirewall.png)

Comprueba que el servicio está activo:
![status](/despr2_2_nginx/img/statusnginx.png)

Copia los archivos del sitio de ejemplo
![scp](/despr2_2_nginx/img/scpdelosarchivos.png)

Desactiva el sitio por defecto y activa tu configuración
![config](/despr2_2_nginx/img/desactivardefyactisonfig.png)

Accede desde el host a http://localhost:8082 y comprueba navegación, imágenes y estilo.
![webmod](/despr2_2_nginx/img/wendepuesmod.png)

Estructura de archivos
![estruct](/despr2_2_nginx/img/estructuradearchivo.png)

# Problemas encontrados durante la conguración y despliegue, y cómo los solucionaste.

Problema:

No cambiar la ruta al copiar el archivo de configuración en /etc/nginx/sites-available/sitio_ejemplo (root /var/www/sitio_ejemplo;)

Solución:

Cambiar las rutas y corregir el archivo
