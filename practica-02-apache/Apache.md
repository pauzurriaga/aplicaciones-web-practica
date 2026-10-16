# Instalacion, Configuracion y securizacion de apache


### Apartado 1

**Salida de comandos**

```sudo apt update | sudo apt upgrade -y```

**captura**

![Captura de pantalla 1](Imagenes/Imagen2.png)

En esta captura se muestra la version actual de ubuntu despues de actualizarlo.

### Apartado 2

**Pregunta**

¿Qué paquetes adicionales se han instalado como dependencias? 


### Apartado 3

**captura**

![Captura de pantalla 2](Imagenes/Captura2.png)

**Pregunta**

¿Qué diferencia hay entre los perfiles Apache, Apache Full y Apache Secure?


### Apartado 4

**Pregunta**

¿Cuándo conviene usar reload en lugar de restart?

### Apartado 5
| Ruta | Descripción |
|---|---|
|/etc/apache2/apache2.conf |Este es el archivo de configuracion principal de apache2 |
|/etc/apache2/ports.conf|En este archivo están los puertos en los que apache escucha |
|/etc/apache2/sites-available/ |Aquí se guardan los sitios disponibles em el servidor que no están necesariamente activos |
|/etc/apache2/sites-enabled/ |En este archivo se estan los enlaces a los sitios activos |
|/etc/apache2/mods-available/ y mods-enabled/ |En esta carpeta se guardan los módulos activos  y disponibles|
|/etc/apache2/conf-available/ y conf-enabled/ |Donde se guardan fragmentos de configuración tanto disponible como activos |
|/etc/apache2/envvars |Es el archivo que guarda las variables de del entorno de el servidor |
|/var/www/html/ |Es el directorio raiz por defecto |
|/var/log/apache2/access.log|Archivo donde se almacenan los registros de el servidor |
|/var/log/apache2/error.log |Archivo donde se almacenan los Errores de el servidor |

**captura**

![Captura de pantalla 3](Imagenes/Captura3.png)

**Pregunta**

¿Por qué Apache usa enlaces simbólicos entre los directorios *-available y *-enabled?

### Apartado 6

**captura**

![Captura de pantalla 4](Imagenes/Captura4.png)

### Apartado 7

| Modulo | Función |
|---|---|
|mod_rewrite |Reescritura de URL |
|mod_headers |Manipulación de cabeceras HTTP |
|mod_ssl |Soporte HTTPS |
|mod_dir |Gestión de ficheros índice (index.html) |
|mod_alias |Redirecciones y alias de rutas |
|mod_auth_basic |Autenticación básica |
|mod_status  |Página de estado del servidor |
|mod_php / PHP-FPM |Ejecución de PHP (opcional) |

**Pregunta**

¿Qué ocurre si desactivas un módulo del que depende otro?

### Apartado 8

**captura**

![Captura de pantalla 5](Imagenes/Captura5.png)

![Captura de pantalla 5.1](Imagenes/Captura5.1.png)

**Pregunta**

¿Qué diferencia hay entre virtual hosts basados en nombre y basados en IP? ¿Cuál has usado?

### Apartado 9

**captura**

![Captura de pantalla 6](Imagenes/Captura6.png)

### Conclusiones y problemas







