# odoo-argentina-ce-dockerfiles
Todo para armar tus imagenes de Odoo Argentina Adhoc

Este Dockerfile soluciona un problema en la imagen oficial de Odoo18 que usa Ubuntu 22.04 e impedía hacer pip install (PEP668). Se solcuiona agregando --break-system-packages en cada linea.
Tambien usamos una herramienta espectacular de @Alitux llamada OdooGCI (https://gitlab.com/alitux/odoogci) para hacer mas fácil la instalacion de los modulos necesarios para la localizacion de Adhoc y sus requerimientos.
Ademas suamamos odooconf para usarla opcionalmente si se quiere optimizar el archivo conf automaticamente.
