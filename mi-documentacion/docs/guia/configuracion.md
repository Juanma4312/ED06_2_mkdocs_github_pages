# Configuración del Proyecto

La herramienta MkDocs se configura de manera centralizada a través de un único archivo llamado `mkdocs.yml`, situado en la raíz del proyecto.

## Archivo mkdocs.yml

En este archivo definimos aspectos fundamentales del sitio web, como:

* El nombre del sitio (`site_name`).
* El tema visual elegido (`theme`), que en nuestro caso es **Material for MkDocs**.
* Las extensiones y características adicionales, como la navegación por pestañas y la opción de copiar el código.

### Estructura de navegación

Si deseas personalizar el menú lateral, puedes añadir una sección `nav:` en el archivo de  configuración para forzar un orden específico de las páginas.
