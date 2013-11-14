Proyecto: sistema de control de una placa solar fotovoltaica.

Objetivo: seguimiento de la posición del sol, de manera que cuando la posición del sol varíe, los motores hagan que la placa se posicione de nuevo para el máximo aprovechamiento de la radiación solar. El código fuente es para programar la aplicación en un microcontrolador Stellaris LM3S8962 del fabricante Texas Instruments.

Versión: 0.1
Fecha: 11 Noviembre de 2013
Estado del proyecto: en esta versión se ha implementado:
* Un planificador ejecutivo cíclico (véase "scheduler").
* Un patrón de diseño Facade, para separar diferentes niveles el software de la aplicación (véase los ficheros "display", "displayGeneric" y "displayRIT").
* Un patrón de diseño doble buffer, para evitar parpadeo de la imagen (véase "framebuffer").
Descripción: se mueve un cuadrado a través de los botones: arriba, abajo, izquierda y derecha.
