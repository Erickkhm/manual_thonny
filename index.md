---
title: Thonny
description: Manual de Instalación y configuración
author: Miguel Ángel Robles R.
email: "miguel.robles@atmosfera.unam.mx"
layout: default
---

## Introducción
Thonny es un software de programación principalmente utilizado para conectar dispositivos con micropython.

## Instalación
1. Acceder a <https://thonny.org>

2. En la sección *Download* (descargas), hacer click en la versión correspondiente a su sistema operativo.
![download](/assets/img/download.png)

3. Ejecutar el archivo descargado, se iniciará un asistente de instalación que le guiará paso a paso. 


## Descarga de driver para Windows 

1. Acceder a <https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads>

2. Descargar el driver *CP210x Universal Windows Driver*
![driver](/assets/img/driver.png)

3. Guardarlo y descomprimirlo en una ubicación conocida y de fácil acceso.

4. Conectar la ESP32.

5. Abrir el *Administrador de dispositivos* y buscar el dispositivo que aparezca como desconocido o en la sección *otros*.

6. Dar doble click en este

7. Dar click en la opción *Actualizar controlador*
![controlador](/assets/img/controlador.png)

8. Dentro de la opción de controladores, seleccionar la opción de *Buscar controladores en mi equipo*
![controladores](/assets/img/controladores.png)

9. Dar click en "examinar"

10. Seleccionar la carpeta donde previamente se descomprimió el *CP210x Universal Windows Driver*
![driver2](/assets/img/driver2.png)

11. Una vez que termine el proceso de instalación, el controlador ya está instalado y el dispositivo listo para usarse.
![listo](/assets/img/listo.png)

## Instalar o Actualizar el firmware de Micropython

** en desarrollo

## Configuración para conectar a la ESP32
1. Abrir Thonny

2. En el menú *Run*, seleccionar *Configure Interpreter...*
![config](/assets/img/config.png)

3. En la pestaña *Interpreter*, seleccionar *Micropython (ESP32)* y el puerto correspondiente (en Windows aparece como *Silicon Labs CP210x USB to UART Bridge* o *Dispositivo serie USB (COM##)*.

4. Desactivar todas las opciones de la última sección, excepto *restart interpreter before running a script*

5. Click en OK
![interpreter](/assets/img/interpreter.png)

#### Estás listo para utilizar Tony
![tony](/assets/img/tony.png)
