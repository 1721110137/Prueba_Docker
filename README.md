# Prueba_Docker

Repositorio de prueba para utilizarlo con Docker | Este repositorio tiene una página web sencilla desarrollada con web.py

# 1. Instalar paquetes
Para instalar 1 paquete en python3 se ejecuta el siguiente comando:

$ pip3 install web.py
#-----------------------------------------------------------------------------------

# 2. Visualizar lista de paqutes
Para visualizar la lista de paquete instalados se ejecuta el siguiente comando:

$ pip3 freeze
#-----------------------------------------------------------------------------------

# 3. Crear el archivo requirements.txt

$ pip3 freeze > requirements.txt
#-----------------------------------------------------------------------------------

# 4. Instalar todos los paquetes necesarios
Para instalar todos los paquetes necesarios se crear una lista en el archivo requirements.txt y se ejecuta el siguiente comando:

$ pip3 install -r requirements.txt
#-----------------------------------------------------------------------------------

# 5. Generar el archivo requirements.txt
Para generar el archivo requirements.txt se redirecciona la salida del comando freeze al archivo.

$ pip3 freeze > requirements.txt
#-----------------------------------------------------------------------------------

# 6. Ejecutar la aplicación web
En este ejemplo se instala web.py, se utiliza el código de ejemplo y se ejecuta.

$ python3 app.py
#-----------------------------------------------------------------------------------