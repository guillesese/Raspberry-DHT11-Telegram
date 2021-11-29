# Obtener datos de DHT11 en Raspberry y comunicación vía Telegram
Proyecto que recupera los datos de un DHT11 utilizando la librería de Adafruit, tratar los datos y posteriormente enviar estos datos a un bot de Telegram. 

Por otro lado almacena los datos que recibe en una BD de SQLite3. 

Para un correcto funcionamiento es necesario instalar:
 - Librerías del SO. 
 
```sudo apt-get install python3-dev```

 - Librería de Adafruit. 
 
```sudo pip3 install adafruit-circuitpython-dht```

 - Librería de SQLite3.

 ```sudo apt-get install sqlite3 ```
   
## Base de Datos ##
Por defecto, la Base de Datos es en SQLite3. La estructura es sencilla y se compone de 4 campos. 
- ID. Clave primaria autoincremental. 
- Temperatura. Float 
- Humedad. Float
- Fecha. Datetime. 

El nombre de la Base de Datos es "datostemperatura.db" y está ubicada en el directorio /home/pi/


## Bot de Telegram ##
Será necesario rellenar los valores del bot_token y del bot_chatID para el correcto funcionamiento.
