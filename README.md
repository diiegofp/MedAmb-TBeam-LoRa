# TBeam-LoRa
En este proyecto se realizo el envió de variables ambientales a través de LoRaWAN con TTN para luego desplegarlas en un dashboard en Grafana.

# ¿Qué podemos hacer?

Desplegar información por medio de un web server o dashboard MQTT por medio de conexión WiFi. Obtener mediciones de temperatura, humedad y presión atmosférica a través del sensor BME280,  controlar cargas AC por medio del relé y una tira led de tipo NeoPixel por medio de la programación y un Buzzer para emitir algún sonido.

# Pinout


### GPS
L76K | GPIO 
--- | --- 
TX | 8
TX | 9
VDD | 3V3
VSS | GND

### Sensor de temperatura, humedad y presión
BME280 | ESP32S3
--- | ---
SDI 3 | SDA 21
SCK 4 |  SCL 22 

### LoRa Module
SX1262 | GPIO 
--- | --- 
DIO1 | 1
BUSY | 4
RST | 5
CS | 10
