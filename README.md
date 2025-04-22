# Taller Integrador Grupo 1

- David Obando Pereira
- Daniel Quesada Camacho
- Federico Rivera Moya

# APRS

### ¿Qué es?
APRS (Automatic Packet Reporting System) es un sistema de comunicación basado en radioaficionados que permite la transmisión en tiempo real de datos, como ubicación GPS, mensajes de texto, información meteorológica y telemetría. Se utiliza en sistemas de radiofrecuencia (usualmente radios) que operan en VHF o UHF.
### ¿Para Qué sirve? (Aplicaciones)
El APRS tiene múltiples aplicaciones, entre ellas:
- Rastreo de vehículos y personas: Utilizando GPS para reportar posiciones de vehículos en emergencias o carreras y de personas en actividades como expediciones, senderismo, ciclismo, etc.
- Mensajes de texto: Envío y recepción de mensajes entre estaciones utilizando este sistema ya sea para comunicaciones interpersonales o de emergencia.
- Alertas meteorológicas: Difusión de información meteorológica y datos ambientales en tiempo real entre estaciones meteorológicas.
- Telemetría: Monitoreo y reporte de datos obtenidos por sensores, lo que conlleva a un excelente control sobre estaciones o nodos de sensado.
- Apoyo en emergencias y desastres: Se utiliza en situaciones de desastre o emergencia para coordinar operaciones y rastrear vehículos y equipos de rescate.
### ¿Qué protocolos de comunicación utiliza?
APRS utiliza principalmente el protocolo de comunicación AX.25 (Amateur X.25) en modo de datagrama (UI-frames), que es un protocolo de radiopaquetes utilizado en redes de radioaficionados. También admite la utilización de repetidores digitales (nodos UI) y permite la operación sobre otros medios como TCP/IP, UDP, PSK y otros modos digitales en HF.
### ¿En cuales bandas de frecuencia opera?
l APRS opera principalmente en las bandas VHF y UHF, y en algunos casos HF dedicadas para radioaficionados, esta varía dependiendo del país, pero usualmente en las bandas 144.390 MHz (2 metros) para USA y 144.800 MHz (2 metros) para Europa y otras regiones.

![Screenshot](https://github.com/DOPALTEC/Taller-Integrador/blob/main/mapa%20aprs.png)
 
### Componentes clave (dispositivos que componen) una red APRS
- Transceptor de radio VHF/UHF – Para transmitir y recibir paquetes de datos APRS.
- TNC (Terminal Node Controller) – Convierte los datos en paquetes AX.25 para su transmisión. Puede ser hardware dedicado o emulación por software.
Computadora o microcontrolador – Procesa los datos y puede ejecutar software APRS como UI-View, Xastir o APRSdroid.
- Digipeaters – Repetidores que amplían la cobertura retransmitiendo paquetes APRS.
- iGates (Internet Gateways) – Conectan la red APRS de radio con Internet a través de APRS-IS.
- Servidores APRS-IS – Infraestructura en línea que recopila y distribuye datos APRS en Internet.

# Evidencia en base de datos APRS-IS

![Screenshot](https://github.com/DOPALTEC/Taller-Integrador/blob/main/iGATE%20en%20APRS%20-%20Grupo%201%20-%20Taller%20integrador.png)

# CA2RXU LoRa APRS iGate/Digipeater

This firmware is for using ESP32 based boards with LoRa Modules and GPS to live in the APRS world.

![Screenshot](https://github.com/DOPALTEC/Taller-Integrador/blob/main/lora.jpg)

# Bill of Materials (BOM)
Considerar horas. Presentar horas de trabajo y con el presupuesto. 


