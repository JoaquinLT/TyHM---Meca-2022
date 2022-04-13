# Consignas del proyecto:

## Resumen:
El proyecto busca poder enviar un comando hacia un receptor mediante rediofrecuencia y que este responda utilizando el internet

## Receptor:
Debe poder acceder a la información de sensores y debe poder controlar distintos actuadores. La comunicacion con este debe ser mediante radiofrecuencia, es decir debe contar con una antena y decodificador adecuados.
### Sensores y actuadores propuestos:
* Sensor presion  atmosferica
* Sensor temperatura
* Sensor composicion de gases
* Sensor nivel de luz
* Sensor voltaje de la bateria
* Estabilizador giroscopico
### Dispositivos de comunicación propuestos:
* SDR
* Radio a cristal
* Placa Wi-Fi/ Ethernet (Comunicación de respaldo o de respuesta)
### Placa base/ Microcontrolador propuesto:
* Arduino Mega/UNO
* Raspberry Pi 3B+

## Emisor:
Debe ser como una terminal donde pueda enviar comandos y recibir su respuesta. La forma de envio es por radiofrecuencia utilizando Onda Corta.
### Dispositivos de comunicación propuestos:
* uSDX Radio
* Radio a cristal

## Consignas adicionales:
Realizar un diagrama de funcionamiento del receptor utilizando la forma normal de Backus.

## Enlaces de interes:
* [WebSDR Radio Online](http://websdr.org/)
* [Guía del activador SOTA](http://www.sota-argentina.com.ar/2018/04/guia-del-activador-summits-on-air-sota.html)
* [Arduino uSDX](https://antrak.org.tr/blog/usdx-a-compact-sota-ssb-sdr-transceiver-with-arduino/)

