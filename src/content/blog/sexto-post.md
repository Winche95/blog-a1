---
title: 'REFLECTOMETRÍA EN EL DOMINIO DEL TIEMPO'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 09 2023'
heroImage: '/ref.jpg'
---

Una técnica que se usa para ubicar un defecto en un cable metálico se llama reflectometría en el dominio del tiempo (TDR, por time-domain reflectometry). Con ella, se pueden localizar los defectos de las líneas de transmisión con precisión de algunos pies en distancias de 10 millas. La TDR usa la bien demostrada teoría de que los defectos en las líneas de transmisión, como cortos o aberturas, hacen que una parte de la señal incidente regrese a la fuente. 

La cantidad de retorno de la señal transmitida depende de la clase y la magnitud del defecto. El punto en la línea donde está el defecto representa una discontinuidad para la señal. Esa discontinuidad hace que una parte de la señal transmitida se refleje, en vez de continuar por el cable.

Si no regresa energía alguna, es decir, si la línea de transmisión y la carga están perfectamente balanceadas, la línea tiene longitud infinita o termina en una carga resistiva con impedancia igual a la impedancia característica de la línea.

La TDR funciona en forma similar al radar. Un pulso de corta duración con corto tiempo de subida se propaga por un cable; a continuación se mide el tiempo en que regresa una parte de la señal a la fuente. Esta señal de regreso se llama eco, a veces. Al conocer la velocidad de propagación por el cable, se puede calcular la distancia exacta entre el defecto y la fuente, con la siguiente ecuación:

<center> <img src="/dist.jpg" alt="centered image" > </center>

El tiempo transcurrido se mide desde la parte delantera del pulso transmitido hasta la recepción de la señal reflejada, como se indica en la fig. 8-28a. Es importante que el pulso transmitido sea tan corto como sea posible. De no ser así, cuando el defecto está cerca de la fuente, la señal reflejada podría regresar mientras todavía se estuviera transmitiendo el pulso (fig. 8-28b), dificultando la detección. Para las señales que viajan a la velocidad de la luz (c), la velocidad de propagación es 3 x 10^8 m/s, que aproximadamente es 1 ns/pie.

<center> <img src="/fig8-28.jpg" alt="centered image" > </center>

En consecuencia, un pulso de varios microsegundos de ancho limitaría la utilidad de la TDR sólo para defectos de cable que estuvieran a varios miles de pies o más de distancia. La producción de pulsos extremadamente angostos fue uno de los factores limitantes en el desarrollo de la TDR para localizar fallas o cortos en cables.