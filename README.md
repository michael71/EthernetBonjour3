EthernetBonjour3
================

## to be used with Ethernet3 Lib

Bonjour (ZeroConf) Library for Arduino & EthernetShield v2 

mDNS (registering services) and DNS-SD (service discovery) has been tested and works on:
- Arduino Mega 2560 with EthernetShield v2

Ported (only changes in some includes) from 
   https://github.com/TrippyLighting/EthernetBonjour
use together with 
   https://github.com/sstaub/Ethernet3
(the Adafruit Ethernet2 library has no support for multicast UDP)

## Changelog
 - 06-Aug-2017 to be used with EthernetShield V2

 - 22-Dec-2015 Updated to provide compatibility with Arduino 1.6.6. Since 1.6.6. the Ethernet library provides support for multicast a pre-requisite for Bonjour to work.

 - 29-06-2019 Fixed string zero termination which breaks everything - Marcel Benning / deltacore
