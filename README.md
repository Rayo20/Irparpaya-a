...............................
#Nombre del script: Irparpayaña
...............................
#Significado: Acompañar a uno hasta ponerlo en camino 
#Lengua: Aymara - Perú
..............................
.........................
#NAME SCRIPT: Irparpayaña
.........................
#Irparpayaña meaning = Accompany one to put it on the road.
#Language: Aymara - Perú 
.........................

#Domingo 09/12/2018
#Martes 15/01/2019
#by: real strategy / rwam

#Script diseñado para la extracción de url de páginas web, Mostrar los estatus que arrojan cada uno de dichos host y analizar los servicios que brinda con un scan usando nmap 

PASO N°1

#Instalar paquetes para el buen inicio del script

apt update && apt upgrade -y

pkg install nmap

pkg install wget

pkg install curl

pkg install git


PASO N°2

#Instalar el script host-extractor-v2

git clone https://github.com/HackeRStrategy/Irparpaya-a.git

cd Irparpaya-a

chmod +x real-host-v2.sh

bash real-host-v2.sh


