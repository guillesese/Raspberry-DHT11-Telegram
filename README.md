# Obtener datos de DHT11 en Raspberry y comunicación vía Telegram
Proyecto que recupera los datos de un DHT11 utilizando la librería de Adafruit, tratar los datos y posteriormente enviar estos datos a un bot de Telegram. 

Por otro lado almacena los datos que recibe en una BD de SQLite3. 

Para un correcto funcionamiento es necesario instalar:
 - Librerías del SO. 
   sudo apt-get install python3-dev 
 - Librería de Adafruit
   sudo pip3 install adafruit-circuitpython-dht
 - Librería de SQLite3
   sudo apt-get install sqlite3
   
