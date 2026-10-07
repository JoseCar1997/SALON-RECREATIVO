\# Decisión del CMS e imagen Docker



\## CMS elegido



Para este bloque vamos a utilizar WordPress como gestor de contenidos.



WordPress necesita PHP, una base de datos MySQL o MariaDB y un servidor web. En nuestro proyecto utilizaremos Nginx como servidor web y MariaDB como base de datos.



\## Imagen elegida



La imagen que vamos a utilizar es:



`wordpress:7.1-php8.3-fpm`



He elegido la variante `fpm` porque utilizaremos Nginx como servidor web separado.



`php8.3` indica que la imagen utiliza PHP 8.3.



No utilizamos `latest` porque puede cambiar de versión con el tiempo y provocar que el proyecto deje de ser reproducible.



\## Comprobaciones realizadas



Se ha descargado la imagen correctamente y se ha comprobado que incluye:



\- PHP 8.3

\- mysqli

\- gd

\- zip

\- intl

\- imagick



Con estas comprobaciones la imagen cumple los requisitos necesarios para utilizar WordPress en el proyecto.

