# WIMUMO

## Instaladores de la aplicación de escritorio

<p align=center>
[Windows](https://github.com/wimumo/wimumo-desktop-app/releases/download/v1.0/wimumo-desktop-app-1.0.0-Setup_win64.exe)
</p>
<p align=center>
[MacOS](#)
</p>
<p align=center>
[Linux](#)
</p>
## Ejemplos rápidos

Sketches de Processing y Patches de PureData para comenzar a usar WIMUMO

 - [ejemplo-basico-cuadrados.pd](https://github.com/wimumo/ejemplos/tree/main/Processing/ejemploBasicoCuadrados): Un Sketch que recibe mensajes de dos canales y controla el tamaño de dos redondeles a partir del esfuerzo realizado.
 - [muestra-valores.pd](https://github.com/wimumo/ejemplos/blob/main/Puredata/muestra-valores.pd): Un Patch que recibe mensajes e imprime los valores.
 
Exiten más ejemplos en el siguiente repositorio.

## Proyecto WIMUMO

WIMUMO (de "plataforma de adquisición WIreless MUltiMOdal") es un dispositivo capaz de adquirir señales biopotenciales del cuerpo y transmitirlas a través de WiFi.

Específicamente, mide señales electromiográficas y electrocardiográficas (de los músculos y el corazón respectivamente). Está diseñado como una plataforma de bajo costo, fácil de construir y fácil de usar.

Nació como un dispositivo para performances artísticas, midiendo las señales producidas por el cuerpo de un intérprete y transmitiéndolas mediante el protocolo OSC para producir imágenes y sonido.

El proyecto consiste en:

 - Una plataforma de hardware construida con componentes electrónicos de bajo costo como ESP32 y el ahora casi antiguo amplificador LM324, carcasa impresa en 3D y suministros textiles comunes (aún no se ha publicado).
 - Firmware programado en el IDE de Arduino utilizando bibliotecas ESP32 de alto y bajo nivel para proporcionar una conexión a Internet simplificada, medición de señal, procesamiento y entrega a cualquier IP local y dirección de puerto utilizando el protocolo OSC. [Repositorio del Firmware de Arduino](https://github.com/wimumo/wimumo-esp15-V2/)
- Software programado en Electron para contar con una aplicación de escritorio opcional que permite observar las señales medidas, y utilizar algunas características básicas de WIMUMO. [Repositorio de la app de escritorio](https://github.com/wimumo/wimumo-desktop-app/).
 


 
 
