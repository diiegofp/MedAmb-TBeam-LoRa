# TBeam LoRaWAN
En este proyecto se realizo el envió de variables ambientales a través de LoRaWAN con TTN para luego desplegarlas en un dashboard en Grafana.

# ¿Qué podemos hacer?

Desplegar información por medio de Grafana a traves de LoRaWAN. Obtener mediciones de temperatura, humedad y presión atmosférica con el sensor BME280, longitud, latitud y altitud con el GNSS L76K. Por último, el QMI8658 que incorpora un giroscopio de 3 ejes y un acelerómetro de 3 ejes. 

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
SDI 3 | SDA 17
SCK 4 |  SCL 18

### IMU Sensor
QMI8658 | GPIO 
--- | --- 
MISO | 37
MOSI | 35
SCK | 36
CS | 34

### LoRa Module
SX1262 | GPIO 
--- | --- 
DIO1 | 1
BUSY | 4
RST | 5
CS | 10
