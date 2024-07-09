---
title: 'LÍNEAS DE TRANSMISIÓN DE MICROCINTA Y DE CINTA'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 10 2023'
heroImage: '/mic.jpg'
---

A frecuencias menores que unos 300 MHz, las características de las líneas de transmisión abiertas y en corto, como las que se describieron antes en este capítulo tienen poca importancia. Así, a bajas frecuencias, las líneas de transmisión normales serían demasiado largas para tener aplicación práctica como componentes reactivos o circuitos sintonizados.

Sin embargo, para aplicaciones de alta frecuencia, de 300 a 3000 MHz, se han desarrollado líneas especiales de transmisión hechas con patrones de cobre en una tarjeta de circuito impreso (PC, por printed circuit, o PCB, por printed circuit board), llamadas microcintas y línea de cinta, para interconectar componentes en las tarjetas PC. También, cuando la distancia entre los extremos de fuente y de carga en una línea de transmisión es de unas pocas pulgadas o menor, es impráctico usar líneas de transmisión de cable coaxial normal, simplemente porque los conectores, las terminaciones y los cables mismos son demasiado grandes.

Tanto las microcintas como las líneas de cinta usan las pistas (o trazas) de cobre sobre la misma tarjeta de circuito impreso. Las trazas se pueden grabar con los mismos procesos que se usan en la fabricación de circuitos impresos, y, por consiguiente, ya no requieren más procesos de manufactura.

Si las líneas se graban sólo en la superficie de la tarjeta PC, se llaman líneas de microcinta. Cuando se graban en la capa intermedia de una tarjeta PC de varias capas se llaman líneas de cinta. Las microcintas y las líneas de cinta se pueden usar como líneas de transmisión, inductores, capacitores, circuitos sintonizados, filtros, desplazadores de fase y dispositivos de acoplamiento de impedancia.


**Microcinta**

Una microcinta no es más que un conductor plano separado de un plano de tierra con un material dieléctrico aislante.

<center> <img src="/fig8-29.jpg" alt="centered image" > </center>

En la fig. 8-29a se ve una línea de microcinta de una pista. El plano de tierra sirve como punto común del circuito, y debe ser cuando menos 10 veces más ancho que el conductor superior, y debe conectarse a tierra. 

En general, la microcinta es de un cuarto o media longitud de onda, a la frecuencia de operación, y equivale a una línea de transmisión desbalanceada. Se prefieren las líneas en corto sobre las líneas abiertas, porque éstas tienen mayor tendencia a irradiar. La fig. 8-29b muestra una línea de transmisión balanceada de dos hilos.

Como en cualquier línea de transmisión, la impedancia característica de una línea de microcinta depende de sus características físicas. Así, cualquier impedancia característica de 50 a 200 ohms puede obtenerse en las líneas de microcinta sólo con cambiar sus dimensiones. Lo mismo sucede con la cinta. Desafortunadamente, toda configuración de microcinta tiene su propia y exclusiva fórmula. La ecuación para calcular la impedancia característica de una línea desbalanceada de microcinta, como la de la fig. 8-29c, es

<center> <img src="/Z02.jpg" alt="centered image" > </center>

**Línea de cinta**

La línea de cinta no es más que un conductor plano emparedado entre dos planos de tierra, como
se ve en la fig. 8-30.

<center> <img src="/fig8-30.jpg" alt="centered image" > </center>

Aunque es más difícil de fabricar que la microcinta, es menos propensa a irradiar y así sus pérdidas son menores que las de la microcinta. De nuevo, la longitud de una línea de cinta puede ser de un cuarto o media longitud de onda, y se usan con más frecuencia las líneas en corto que las abiertas. La impedancia característica de una línea de cinta, configurada como se ve en la fig. 8-30 es

<center> <img src="/Z03.jpg" alt="centered image" > </center>