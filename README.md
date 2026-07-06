# fabricacion-pcb-amplificador-audio

Este proyecto consiste en el diseño, ruteado y manufactura modular de un sistema de amplificación de audio estéreo de 15W + 15W. 

Fue desarrollado de forma colaborativa como **proyecto grupal por un equipo de 5 estudiantes de Ingeniería Electrónica de la Pontificia Universidad Católica del Perú (PUCP)** para el curso de Fabricación de Equipos Electrónicos.

Para optimizar el rendimiento térmico, mitigar el ruido electromagnético (EMI) y facilitar el ensamblaje en el laboratorio, el sistema se dividió en 3 bloques de hardware independientes distribuidos en este repositorio:

##  Las 3 Placas del Proyecto

1. **Placa de la Fuente:** Recibe los 220V AC de la pared y los transforma en voltajes DC estables: una salida de 12V (para darle potencia al amplificador) y tres salidas independientes de 5V (para los módulos de audio).
2. **Placa de Selección:** Controla las entradas de audio mediante un switch mecánico ON-ON-ON. Te permite cambiar fácilmente entre tres fuentes: **Bluetooth**, **Jack 3.5mm** y tarjeta **Micro SD**.
3. **Placa del Amplificador:** Es el núcleo del audio. Utiliza un integrado de la serie TDA en configuración Clase AB, entregando un máximo de 15W por canal (izquierdo y derecho).

---

##  Detalles Técnicos y Herramientas
* **Software:** Diseñado y ruteado en EasyEda.
* **Habilidades aplicadas:** Ruteado de pistas de potencia (para los 12V y salidas de parlantes), planos de masa para evitar interferencias en el audio, y exportación de archivos Gerber listos para mandar a fabricar.

---

## Estructura de Archivos del Repositorio

El proyecto incluye la documentación técnica completa para la fabricación de las placas y la integración final del sistema:

* **[1_Placa_Fuente](./1_Placa_Fuente):** Diagramas, archivos de diseño y Gerber de la etapa de alimentación.
* **[2_Placa_Seleccion](./2_Placa_Seleccion):** Archivos fuente y Gerber del conmutador de entradas (Bluetooth/Jack/MicroSD).
* **[3_Placa_Amplificador](./3_Placa_Amplificador):** Planos y Gerber del módulo amplificador Clase AB.
* ** Planos_Fabricacion_y_Ensamblaje:** Carpeta que contiene la planimetría de ingeniería del equipo:
  * **Plano de Conexiones:** Diagrama general de interconexión y cableado entre los 3 módulos de hardware.
  * **Plano de Ensamblaje:** Guía visual con la ubicación exacta (Silkscreen/Top Overlay) de cada componente en las placas para el proceso de soldadura.
  * **Plano Explosivo:** Vista despiezada del hardware que detalla el montaje físico, acoplamiento de las placas y fijación mecánica del sistema.
