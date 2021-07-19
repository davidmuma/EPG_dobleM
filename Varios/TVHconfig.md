# <b>Configuración común de TVheadend </B>
- Reiniciar TVheadend y activar el grabber:
```
Configuración - Canal/EPG - Módulos para Obtención de Guía - Interno: XMLTV: tv_grab_EPG_dobleM
```
![alt text](https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/Images/Tvheadend1.jpg)
- Programar el cron de TVheadend para que se ejecute todos los días a las 8:15.
```
Configuración - Canal/EPG - Obtener Guía - Internal Grabber Settings - Cronología multi-línea:
```
```
# Todos los días a las 8:04, 14:04 y 20:04
4 8 * * *
4 14 * * *
4 20 * * *
```
- Forzar una actualización de la guía de programación</i>
```
Pulsar el botón "Volver a ejecutar los capturadores de EPG internos"
```
![alt text](https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/Images/Tvheadend2.jpg)
- Configurar guía para Live Channels/TVHClient o para KODI</i>
```
Configuración - General - EPG_Settings - Idioma(s) por defecto:
```
```
Spanish - Guía con etiquetas de colores
French - Guía sin etiquetas de colores
German - Guía con etiquetas de colores, título en una sola linea
English - Guía sin etiquetas de colores, título en una sola linea y sin caracteres especiales
```
![alt text](https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/Images/Tvheadend4.jpg)