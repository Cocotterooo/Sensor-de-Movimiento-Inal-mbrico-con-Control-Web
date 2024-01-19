# PortaSense:
##  ¿Qué es PortaSense?:
**PortaSense** es un proyecto inspirado por las personas que comienzan con una persona dependiente con demencia en su casa pero es totalmente válido para el ámbito de seguridad.

Creado para la **notificación de movimiento** o también otros valores a analizar de cierta  área del hogar, como por ejemplo la temperatura, humedad...

## Descripción y Dispositivos:

 - **HUB:**
   > **Centralita:** Un dispositivo fijo dedicado a recibir todos los datos de los sensores conectados además de poder controlar de manera general mediante botones en el propio dispositivo o individualmente desde un apartado WEB donde está dispuesta la información de todos los sensores además de sus controles específicos.
 - **Sensor:**
   > **Dispositivo Portátil:** Un dispositivo "portátil" dedicado a detectar movimiento en un área, analizar otros valores como temperatura y humedad, este puede ser controlado mediante un botón local o desde la conexión al HUB. 
   > - **Función Principal:** Detección de movimiento. (La notificación se podrá evitar mediante el modo "Pausa" que se puede habilitar localmente o desde el HUB)
   

**Funciones Comunes:** Ambos dispositivos cuentan con funciones comunes como la iluminación mediante la conexión a tiras LED, la notificación de ciertos eventos como el movimiento con un zumbador o señales luminosas.

## HUB:

## Sensor:

### Requisitos para subir el código a los dispositivos ESP32:
 - Tener intalado el firmware de micropython en los dispositivos ESP32.
   > - Descarga el firmware para tu microcontrolador. Este proyecto utilizará este: [Firmware ESP32 Genérico 1.22.1](https://www.micropython.org/download/ESP32_GENERIC/)
   > - Instala el firmware descargado [esptool](https://github.com/espressif/esptool/) al puerto COM de asignado a tu dispositivo.
   > \n*Instrucciones: En la misma página donde descargaste el firmware se encuentra una guía de como instalarlo.* 
