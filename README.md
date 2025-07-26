# TBeam-LoRa
En este proyecto se realizo el envió de variables ambientales a través de LoRaWAN con TTN para luego desplegarlas en un dashboard en Grafana.

# ¿Qué podemos hacer?

Desplegar información por medio de un web server o dashboard MQTT por medio de conexión WiFi. Obtener mediciones de temperatura, humedad y presión atmosférica a través del sensor BME280,  controlar cargas AC por medio del relé y una tira led de tipo NeoPixel por medio de la programación y un Buzzer para emitir algún sonido.

# Pinout


### B
Nombre | GPIO 
--- | --- 
DATA | 12
VDD | 3V3
VSS | GND

### Relé
Nombre | GPIO 
--- | --- 
DATA | 13
VDD | 5V
VSS | GND

### Tira led - WS2812B
Nombre | GPIO 
--- | --- 
DATA | 14
VDD | 5V
VSS | GND

### Sensor de temperatura, humedad y presión - Comunicación I2C
BME280 | ESP32
--- | ---
SDI 3 | SDA 21
SCK 4 |  SCL 22 
