**Instrucciones**

Para ejecutar el proyecto base solo debes ejecutar el comando `docker-compose up -d` dentro de la carpeta raiz y colocar tus modulos de odoo17 dentro de la carpeta `addons`

`odoo.conf`: Este archivo contiene la configuración de Odoo, incluyendo la ubicación de los módulos (addons_path) y la carpeta de datos (data_dir).
`.env`: Aquí se definen las variables de entorno para PostgreSQL y Odoo. Estas variables se utilizan en el archivo docker-compose.yml.
`docker-compose.yml`: Este archivo define los servicios de Odoo y PostgreSQL, sus imágenes, variables de entorno y volúmenes.
Carpeta addons: Aquí debes colocar tus módulos personalizados de Odoo.