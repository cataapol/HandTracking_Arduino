# Sistema de Seguimiento de Manos con Arduino y Python

> Este proyecto es un sistema de seguimiento de manos que utiliza un Arduino y un sistema de visión por computadora en Python para controlar LEDs basados en la posición de los dedos. Se utiliza un módulo de detección de manos que detecta cuántos dedos están levantados y, en función de esto, controla un conjunto de LEDs conectados a un Arduino.

# Tabla de Contenidos

- [Requisitos](#requisitos)
  
- [Descripción del Proyecto - Documentacion - Configuración ](#descripción-del-proyecto-y-configuracion-del-hw)
  


----------------------------------------------------


## Requisitos

### Hardware:
- Arduino Uno (o compatible)
- 5 LEDs
- Resistencias (220Ω o similares)
- Cables de conexión
- Cámara web (para el seguimiento de manos)

<img width="949" alt="Screenshot 2024-09-10 at 03 54 45" src="https://github.com/user-attachments/assets/8698a2df-385d-4340-8474-63dd52c7ed5f">


### Software:
- Python 3.x
- Librerías de Python:
  > pyfirmata (para la comunicación con Arduino)
  > cv2 (OpenCV para la captura de video)
  > cvzone (para la detección de manos)
- Arduino IDE

### Descripción del Proyecto y Configuración del HW

[handRecognizingDocs.pdf](https://github.com/user-attachments/files/16940753/handRecognizingDocs.pdf)





