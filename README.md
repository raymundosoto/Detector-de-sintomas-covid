# detector-de-sintomas-COVID

# Resumen

Este repositorio contiene la información necesaria para crear un prototipo que detecta los sintomas de COVID, el prototipo consta de un detector de oxigenación y ritmo cardíaco MAX30102 y un sensor de temperatura LMX90614. El sistema de adquisición de datos está compuesto por los sensores conectados a un microcontrolador ESP32CAM (programado en arduino) que se conecta a internet vía WIFI, los datos recolectados se almacenan en una base de datos local MySQL y enviados a un flow de node-red mediante el protocolo MQTT.  

# Material necesario

# Software necesario
- Ubuntu 22 (https://ubuntu.com/download/desktop)
- Arduino IDE (https://www.arduino.cc/en/software) corriendo en Ubuntu
- Mosquitto (https://mosquitto.org/download/) corriendo en Ubuntu
- Node-red (https://nodered.org/docs/getting-started/local)
- Programa para conectar sensor MAX30102 y LMX90614 al ESP32 y enviar datos al broker local
- MySQL para crear la base de datos local
- Flow de node-red para adquisición, envío y visualización de datos en el broker local y de la base de datos 
- Biblioteca DHT11 de adafruit en arduino [DHT11](https://github.com/adafruit/DHT-sensor-library)
- Biblioteca [PubSubClient](https://pubsubclient.knolleary.net/) en arduino

# Instruccciones
![imagen](https://user-images.githubusercontent.com/72757419/187573107-653a4561-568b-4068-9646-10dc60edecbc.png)

# Funcionamiento

# Resultados
Creación y uso de la base de datos en MySQL
![imagen](https://user-images.githubusercontent.com/72757419/187574025-9b3504ee-6e6f-4a58-b1dd-9f1a8c45ee52.png)

Se muestra resultado parcial de la conexión del sensor de ritmo cardíaco y saturación de oxígeno y la publicación de los datos obtenidos en el broker local

![imagen](https://user-images.githubusercontent.com/72757419/187573521-e76cece2-9470-4769-b323-be9b27def10d.png)

![imagen](https://user-images.githubusercontent.com/72757419/187573484-3e68f795-2336-47c3-8e7b-0e598da07c00.png)


# Evidencia

# Conclusiones

# Bibliografía

