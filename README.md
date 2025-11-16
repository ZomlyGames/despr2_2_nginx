# despr2_2_nginx

## Descripción del proyecto

El objetivo de esta práctica es instalar y configurar Nginx en una máquina virtual (Ubuntu 22.04) y desplegar sitio web estático sencillo con navegación entre páginas, imágenes y estilos.

## Pasos seguidos para la instalación y despliegue

1. Creación de la VM
2. Preparación del entorno
3. Comprobación básica
4. Desplegar el sitio de ejemplo
5. Configurar un bloque de servidor (server block)
6. Verificación

## Capturas de pantalla del proceso

1. Creación de la VM:
![Creación VM como clon enlazado de la VM base](./Screenshots/Screenshot%20from%202025-10-30%2010-36-13.png)
![Configuración red: Adaptador 1 en NAT + Port-Forward](./Screenshots/Screenshot%20from%202025-10-30%2010-38-39.png)
![Iniciar VM](./Screenshots/Screenshot%20from%202025-10-30%2010-39-42.png)
![Acceder por SSH desde host](./Screenshots/Screenshot%20from%202025-10-30%2010-40-33.png)
2. Preparación del entorno:
![Actualizar paquetes](./Screenshots/Screenshot%20from%202025-10-30%2011-38-15.png)
![Instalar nginx](./Screenshots/Screenshot%20from%202025-10-30%2011-47-05.png)
![Configurar firewall para permitir tráfico HTTP y HTTPS](./Screenshots/Screenshot%20from%202025-10-30%2011-48-48.png)
3. Comprobación básica:
![Comprobación servicio activo](./Screenshots/Screenshot%20from%202025-10-30%2011-48-06.png)
![Acceso a http://localhost:8082/ y ver página por defecto de Nginx](./Screenshots/Screenshot%20from%202025-11-06%2011-22-47.png)
4. Desplegar el sitio de ejemplo:
![Copiar archivos a MV](./Screenshots/Screenshot%20from%202025-11-06%2011-33-37.png)
![Copiar archivos a /var/www/sitio_ejemplo/](./Screenshots/Screenshot%20from%202025-11-06%2011-36-10.png)
5. Configurar un bloque de servidor:
![Crear archivo de configuración](./Screenshots/Screenshot%20from%202025-11-06%2011-40-05.png)
![Desactivar sitio por defecto y activar configuración](./Screenshots/Screenshot%20from%202025-11-06%2011-48-56.png)
![Desactivar sitio por defecto y activar configuración](./Screenshots/Screenshot%20from%202025-11-06%2011-49-44.png)
6. Verificación:
![Acceder desde el host a http://localhost:8082](./Screenshots/Screenshot%20from%202025-11-06%2011-50-16.png)

## Problemas encontrados durante la configuración y despliegue, y cómo los solucionaste

No encontré ningún problema en esta práctica.
