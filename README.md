# HandGestureControl con Python y Arduino

Este repositorio presenta un proyecto que combina la detección de gestos de manos mediante Python y la manipulación de una mano robótica controlada por Arduino. La aplicación utiliza una cámara para identificar la posición de los dedos levantados y bajados, y esta información se envía a un Arduino para controlar los motores de la mano robótica, replicando así los gestos en tiempo real.

## Cómo Funciona

1. **Detección de Gestos:**
   - Utiliza la biblioteca OpenCV en Python para analizar el flujo de video de una cámara.
   - Identifica la posición de los dedos levantados y bajados en tiempo real.

2. **Comunicación con Arduino:**
   - Transmite la información de gestos al Arduino a través de la comunicación serial.

3. **Control de Mano Robótica:**
   - El Arduino interpreta los datos y controla los motores (uno por cada dedo) de la mano robótica para replicar los gestos detectados.

