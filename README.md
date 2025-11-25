# SISTEMAS_G6
La solución consiste en un software funcional desarrollado en Python (PyQt5) que se conecta a una base de datos MySQL.
El sistema permite:
# Visualizar productos, stock y alertas de reposición.
# Consultar proveedores, ventas y conteos de inventario.
# Registrar nuevas categorías desde la interfaz.
# Eliminar productos desde la vista correspondiente.
# Mostrar tablas relacionales directamente desde la BD.
La interfaz se diseñó en Qt Designer y se integra mediante loadUi().

# 1. Requisitos del Sistema
Software
a) Python 3.10 o superior
b) MySQL Server 8.x
c) Qt Designer / PyQt5
d) Anaconda o entorno virtual recomendado
Librerías necesarias
pip install PyQt5
pip install pymysql

# 2. Configuración Inicial
Paso 1: Configurar la Base de Datos:
Paso 2: Abrir MySQL Workbench.
Paso 3: Crear la base de datos ejecutando:
# SOURCE BBDD.sql;

# 3. Ejecución del Sistema

Abrir Anaconda Prompt o terminal.
Navegar a la carpeta del proyecto: cd ruta/del/proyecto
Ejecutar: python main.py
En la ventana de login ingresar:
Host: localhost
Usuario: root (o el definido en MySQL)
Contraseña: tu contraseña MySQL
Al presionar Validar usuario, se abrirá la ventana principal.

# 4. Secuencia de Uso del Sistema
1) Usuario ingresa sus credenciales → login exitoso.
2) Selecciona una consulta en el combo.
3) Presiona Visualizar → la tabla se actualiza.
4) (Opcional) Inserta categorías mediante el formulario.
5) (Opcional) Elimina productos seleccionando una fila.
6) Cierra la aplicación, lo que cierra también la conexión a MySQL.
