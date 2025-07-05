Recopilacion de ejemplos para el uso con ESP32 de una pantalla 2.4" TFT SPI 

Esta pantalla tiene 16M de colores y tiene capacidades touch.

En el archivo .txt hay varios ejemplos de el uso de la pantalla con la libreria
TFT_eSPI

Se debe incluir en el directorio del script el archivo User_Setup.h y hacer mencion
a este como sigue:

#include <User_Setup.h>

Para las conexiones seguir la imagen adjunta.

La libreria incluye varios ejemplos de uso

( https://github.com/Bodmer/TFT_eSPI )

*******************************************************************************************************

Un desarrollo interesante es una GUI para diseñar las pantallas y su libreria

https://github.com/ImpulseAdventure/GUIslice/wiki

Un ejemplo del uso de GUISlicer esta en:

https://github.com/jtoobe/FSUIPC_to_Mqtt/tree/main/ESP32

Una buena explicacion del uso de GUISlicer:

https://blog.csdn.net/zgj_online/article/details/104992395    (Esta en chino traducir a español ;-) )
