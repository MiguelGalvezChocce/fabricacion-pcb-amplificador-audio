# fabricacion-pcb-amplificador-audio

Este proyecto es un sistema de amplificación de audio estéreo de 15W + 15W que diseñé de forma modular. El circuito está dividido en 3 placas principales para evitar ruidos y facilitar el armado:

##  Las 3 Placas del Proyecto

1. **Placa de la Fuente:** Recibe los 220V AC de la pared y los transforma en voltajes DC estables: una salida de 12V (para darle potencia al amplificador) y tres salidas independientes de 5V (para los módulos de audio).
2. **Placa de Selección:** Controla las entradas de audio mediante un switch mecánico ON-ON-ON. Te permite cambiar fácilmente entre tres fuentes: **Bluetooth**, **Jack 3.5mm** y tarjeta **Micro SD**.
3. **Placa del Amplificador:** Es el núcleo del audio. Utiliza un integrado de la serie TDA en configuración Clase AB, entregando un máximo de 15W por canal (izquierdo y derecho).

---

##  Detalles Técnicos y Herramientas
* **Software:** Diseñado y ruteado en EasyEda.
* **Habilidades aplicadas:** Ruteado de pistas de potencia (para los 12V y salidas de parlantes), planos de masa para evitar interferencias en el audio, y exportación de archivos Gerber listos para mandar a fabricar.

---

##  Carpetas del Repositorio
* `Planos/` -> Diagramas esquemáticos en PDF.
* `Gerber/` -> Archivos listos para fabricación.
* `Fotos/` -> Capturas en 3D del software.
