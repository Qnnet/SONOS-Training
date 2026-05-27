 SONOS

 * Sonos devices do not support Double NAT. To avoid issues, use only one NAT device or set the second router to bridge mode.(Same SSID)
 * The DHCP reservation feature must be disabled for Sonos to work properly.
* Sonos se conecta a red local no se puede conectar red celular
* Los speakers funcinan con Multicast
 * The Wi‑Fi WPA security setting must be WPA2 for Sonos to work properly.
* Sonos devices do not support WPA Enterprise authentication 
* SONOS devices require SSID Broadcast to be enabled and do not support hidden (non‑broadcast) Wi‑Fi networks.
* SONOS do not support Guest Network
* Multiple Wi‑Fi networks can share the same name (SSID) but use different IP addresses. If your Sonos devices aren’t on the same network, expect connectivity problems.
* Do not support public IP address
* Sonos devices cannot be set up for the first time using tethering or mobile hotspots as the internet connection.
* Use a regular home Wi‑Fi network for the initial setup.
* For most Sonos devices to work, the router must support both 2.4 GHz and 5 GHz.  Routers with only 5 GHz are not supported.
* 2.4GHz non overlapping 
* There is a Wi‑Fi feature that makes a router act like a directional antenna.  
* It’s called Beamforming, and it should be turned off when using Sonos devices.
* Sonos devices do not support connections through wireless extenders.

Network Hardware not supported
https://support.sonos.com/en-us/article/incompatible-network-hardware

Important settings to check for 2.4 GHz and 5 GHz
 

If both bands (5GHz and 2.4GHz) share the same Wi‑Fi name (SSID), rename them and separate the bands. Disable Band Steering and Smart Steering if available.

Make sure the wireless mode is set to b/g/n (supports multiple Wi‑Fi standards).

Set the channel width to 20 MHz.

Not all Sonos devices support Wi‑Fi 5 (802.11ac).

# DAY 1/1

Local Area Network (LAN)

Wide Area Network (WAN)

Metropolitan Area Network (MAN)

Controller Area Network (CAN)

Personal Area Network (PAN)

Wireless Local Area Network (WLAN)

Physical Topologies physically connected

Logical Topologies  describes configuration


PAN Personal Area Network hay dispositivos que no se conectan (MAC)
Los speakers funcuinan con Multicast

EMI (Electromagnetic Interference) noise or disruption in an network caused by external electromagnetic fields

RFI (Radio Frequency Interference)Radio Frequency Interference  (RFI) is a subset of EMI specifically dealing with high-frequency disturbances in the radio frequency spectrum

 

# DAY 1/2
SWITCH 

1.MAC-address learning 
El switch aprende los MAC que le ingresan 

2.Flooding
El switch manda el paquete excepto por la interface de donde ingreso 

3.MAC address Table

show mac-address-table 

4.ipconfig /all
Muestra el MAC de la PC 

Personal Authentication usar SSID and password WAP WAP2 WAP3

Enterprise Authentication un server revisa en la lista usuario y password para dar accesso 

 

# DAY 1/3

 DHCP

 DNS

 # DAY 1/4

 NAT 

 UDP/TCP

 # DAY 1/5

 DOS Denial Service Attacks 
 Satura los servidores para que los verdaderos usuarios no tengan acceso (Ejemplo de UBER)           

 ROGUE ACCESS POINT 

 An unauthorized or fake access point that mimics a legitimate one, tricking users into connecting and exposing their data.

MAN-IN THE-MIDDLE MITM

 An attacker intercepts communication between a user and the network, allowing data to be monitored or altered without detection.
 
## Tipos de verification 
* NFC
* CHIRP PASSCODE
* PIN
* BUTTON 

Do not spect the old ones to do another method rather than button. 

<!-- * If customer already have a system needs to hit the option add existing system1. -->

- We can give a hint if necessary


### Sonos Cloud

Is where the information will be storaged such as customer information, devices added and accounts. 
Guardan el path a libery

## Local Direct Control
Permite controlar desde la app nativa

## Airplay
Allow to control devices remotely for Apple devices

* Only Ace and portable works with bluetooth * 

If the device is connected to Sonos Cloud, we can use the voice assistant

>> Reminder of what DNS is 

- It translates a domain name into an IP address 

>>a Domain Name Vs Hostname
- Hostnames are a way for DNS to find those different sites even they are part of the same domain

Example: hostname.domainname.com

>> Sonos Cloud: 

The Sonos cloudl will allow the devices from SONOS to the Music services CDN. 

Example: Spotify.com

>> Sonos Software Update: 

Improvements 
Fixing 
Any necessary fixing process

" Player needs to be authenticated in the cloud" 


# SONOS CONCEPTOS 
---

# 1. ORGANIZACIÓN / AGRUPACIÓN DEL SISTEMA

## Zone (Zona en Sonos)

Una zona es un grupo de uno o varios altavoces que funcionan como un sistema único.

Puede ser una habitación o varias juntas.
Puedes reproducir música diferente en cada zona.

En simple: un grupo de speakers que controlas como uno solo.

---

## Grouping (Agrupación)

Es cuando unes varias zonas o altavoces para que reproduzcan lo mismo al mismo tiempo.

Puedes agrupar:

* habitaciones
* zonas completas
* speakers individuales

En simple: hacer que varios sistemas suenen al mismo tiempo.

---

## Stereo Pair

Dos altavoces configurados juntos como un sistema estéreo.

Uno es canal izquierdo.
El otro es canal derecho.
Se configuran desde la app.

En simple: dos speakers trabajando como un solo sistema estéreo.

---

## Bluetooth Grouping

Conexión de audio por Bluetooth (en dispositivos compatibles).

Permite:

* enviar audio desde un teléfono
* conectar sin Wi-Fi
* reproducir en un speaker o grupo (según modelo)

En simple: conectar audio sin red usando Bluetooth.

---

# 2. MODOS DE AUDIO (CÓMO SE ESCUCHA EL SONIDO)

## Mono

Todo el sonido es igual en todos los canales.

No hay izquierda ni derecha.
El sonido viene del centro.

En simple: un solo punto de sonido.

---

## Stereo

Sonido dividido en izquierda y derecha.

Crea dirección y espacio.

En simple: sonido con dos lados.

---

## Spatial Audio

Sonido con posición en el espacio.

Los sonidos parecen venir de distintas direcciones.

En simple: sonido en 3D alrededor de ti.

---

# 3. PROCESAMIENTO DE SONIDO

## Trueplay

Función de Sonos que ajusta el sonido según la habitación.

Usa el micrófono para medir el espacio.
Ajusta graves, agudos y balance.

En simple: optimiza el sonido según tu cuarto.

---

## Dolby Atmos

Formato de sonido envolvente en 3D.

Incluye altura (sonido desde arriba).
Requiere hardware compatible.

En simple: sonido que te rodea completamente.

---

# 4. CONEXIONES DE AUDIO

## RCA

Conectores rojo y blanco analógicos.

Usado en equipos antiguos.
Señal básica de audio.

En simple: cable clásico de audio.

---

## Optical (TOSLINK)

Cable digital que usa luz para transmitir audio.

Sin interferencias eléctricas.
Muy usado en televisores.

En simple: cable digital limpio para TV.

---

## Banana Plug

Conector para cables de altavoces.

Se conecta fácilmente a amplificadores.
Usado en sistemas Hi-Fi.

En simple: conector fácil para bocinas.

---

# 5. RED / CONECTIVIDAD

## SonosNet

Red privada del sistema de Sonos.

Se crea cuando un speaker está conectado por Ethernet.
Los demás speakers se conectan entre sí.
Reduce dependencia del Wi-Fi.

En simple: red interna de Sonos para estabilidad.

---

# RESUMEN RÁPIDO

## Organización / agrupación

* Zone → sistema o habitación
* Grouping → unir zonas
* Stereo Pair → 2 speakers como uno
* Bluetooth Grouping → conexión sin Wi-Fi

## Modos de audio

* Mono → un solo punto
* Stereo → izquierda + derecha
* Spatial Audio → sonido 3D

## Procesamiento

* Trueplay → ajuste a la habitación
* Dolby Atmos → sonido 3D avanzado

## Conexiones

* RCA → analógico
* Optical → digital por luz
* Banana Plug → conexión de bocinas

## Red

* SonosNet → red privada de Sonos

## Dynimic Range:
* Es el rango de sonido, picos mas altos mas amplio y mas detalles se escuchan. 

## ARC
Audio return channel. Allows to go back and forward


## Pairing/ Stereopair:
Pairing is the stereo pair feature for the same model 

## Bonding:
Used for home teather, it allows to connect same moding of devices as 
surround

## Grouping:
It does not matter the model of the device it can be use for grouping

## Bluetooth grouping:
Sonos play y move 2, up to 4

## Station mode:

All connected to WI fi

## Sonos MAC address for internet net:
Cuando muchos estan conectados via ethernet cable, el que tengo el menor MAC es el que hace el bridge 
El menor MAC se determina por los numeros y las letras 

## CDN 
Content delivery network 

## agregator

Add links to find a location by country - Artits - Podcast ETC. 


## Sonos On/Off

Smart connect - OFF
Public IP's - NOT SUPPORTED
10.0.0.0
172.16.0.0
192.168.0.0
Enterprise - OFF
Hidden SSID - OFF
UPnP - ON
Airtime frames 
Guest Net- OFF
IGMP Proxy - OFF
VPN - OFF
IGMP Snooping - ON
Beamforming - OFF
QoS - OFF
Bridge Mode - ON
MAC Filtering - OFF


Sonosnet wired
sonos station wirless 

https://drive.google.com/drive/folders/1Kgvq8JYHD1URDkkABqsMnrNKKgtipLIu




