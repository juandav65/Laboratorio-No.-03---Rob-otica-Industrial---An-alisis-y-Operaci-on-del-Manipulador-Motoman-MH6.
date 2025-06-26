## Comparacion Tecnica Motoman MH6 y el IRB140: 

![Captura de pantalla 2025-06-23 215524](https://github.com/user-attachments/assets/daf2a859-8648-4e5e-8b8d-cba44ccc976d)
Configuraciones iniciales:

## Posiciones de home
El manipulador cuenta con dos posiciones de Home.
   
**Home 1** hace referencia al manipulador recogido con el fin de minimizar el torque al que se ven sometidos los componentes, esta posicion se usa cuando el robot va a entrar en reposo. 
![WhatsApp Image 2025-06-25 at 10 09 28 AM](https://github.com/user-attachments/assets/cbfc94c2-6d8d-4781-af37-4295fa090a90)

**Home 2** hace referencia a los servomotores en 0, y este se utiliza pra tener el robot preparado para trabajar, hacer cambios de herramienta etc.
![WhatsApp Image 2025-06-25 at 10 09 28 AM (1)](https://github.com/user-attachments/assets/940366f3-aa5b-427a-ade2-73687e013b71)

## Cómo hacer movimientos manuales?
1. Antes de mover el robot manualmente:
   - Se debe encender el controlador.
   - Luego se activa el teach pendant con la llave en modo "TEACH".
2. Entrar en modo de movimiento manual:
   - Se presiona la tecla `SELECT` del teach pendant.
   - Luego se presiona en el menú principal `JOGGING`.
3. Depende del modo de operación: (Luego de presionar `COORD`)
   - Si se elige el modo cartesiano, el cual permite movimientos en las coordenadas X, Y, Z: (Seleccionando `JOINT`)
      - Se mantiene presionado el hombre muerto y se presiona el botón que indique el movimiento o rotación deseada.
   - Si se elige el modo por articulaciones

| Eje | Nombre                        | Movimiento (Teclas típicas) |
|-----|-------------------------------|------------------------------|
| S   | Base (Shoulder)               | `+X` / `-X`                  |
| L   | Brazo inferior (Lower Arm)    | `+Y` / `-Y`                  |
| U   | Brazo superior (Upper Arm)    | `+Z` / `-Z`                  |
| R   | Rotación de muñeca (Roll)     | `+Rx` / `-Rx`                |
| B   | Balanceo de muñeca (Pitch)    | `+Ry` / `-Ry`                |
| T   | Giro de muñeca (Yaw/Twist)    | `+Rz` / `-Rz`                |

## Acerca de las velocidades en los movimientos manuales
El Manipulador tiene 3 botones para el control de la velocidad en el teach pendant, los cuales son "High Speed", "Fast" y "Slow" ademas de esto dentro de las configuraciones se pueden selecionar  cuatro modos, "inching", "Low speed", "Medium speed" y "High speed".


7) Se Realizo una Trayectoria Polar, en la que se describe una espiral  enmarcada por un circulo, el codigo de esta se encuentra en, ScriptPY_Uzumaki asi como videos de la simulacion y de la trayectoria fisica en los videos Uzumaki.mp4 y ...... respectivamente.


[![Watch the video](https://img.youtube.com/vi/Urdk39AMFZ4/maxresdefault.jpg)](https://youtu.be/Urdk39AMFZ4)

### [Cambio de Home](https://youtu.be/Urdk39AMFZ4)
