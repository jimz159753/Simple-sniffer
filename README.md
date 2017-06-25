# <p align="center"> Simple sniffer hecho en python </p> 
<br>
Esto es un simple sniffer que puede ser usado con wireshark para analizar los paquetes de toda la red, simplemente ejecutar las instrucciones de la herramienta dependiendo si se quiere sniffear toda la red o solamente un equipo.

## Prerequisito
1. Python 2.7
2. Libreria scapy

## Ejemplo:
<br>
En caso de querer sniffear solamente una ip:

```
C:User>python sniffer.py 192.168.1.1 192.168.1.15 wlan0

```

En caso de querer sniffear toda la red:

```
C:User>python sniffer.py 192.168.1.1 192.168.1.0/24 wlan0

```
