# Prueba_Docker

Repositorio de prueba para utilizarlo con Docker | Este repositorio tiene una página web sencilla desarrollada con web.py

# 1. Instalar paquetes
Para instalar 1 paquete en python3 se ejecuta el siguiente comando:

````bash
pip3 install web.py
````

# 2. Visualizar lista de paqutes
Para visualizar la lista de paquete instalados se ejecuta el siguiente comando:

````bash
pip freeze
````

# 3. Crear el archivo requirements.txt
Crear el archivo requirements.txt con todas las librerias a utilizar.

````bash
pip3 freeze > requirements.txt
````

# 4. Instalar todos los paquetes necesarios
Para instalar todos los paquetes necesarios se crear una lista en el archivo requirements.txt y se ejecuta el siguiente comando:

````bash
pip3 install -r requirements.txt
````

# 5. Ejecutar la aplicación web
En este ejemplo se instala web.py, se utiliza el código de ejemplo y se ejecuta.

````bash
python3 app.py
````

## 6. Actualizar el repositorio

Después de verificar que funciona la aplicación web se generá un commit y se actualiza el repositorio en la rama main.

````bash
git add .
git commit -m "CREATED hola mundo"
git push -u origin main
`````
