---
title: 'IMPEDANCIA DE ENTRADA DE UNA LÍNEA DE TRANSMISIÓN'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 08 2023'
heroImage: '/imp.jpg'
---

Cuando se termina una línea de transmisión en un cortocircuito o en un circuito abierto, hay una inversión de impedancia cada cuarto de onda. Para una línea sin pérdidas, la impedancia varía de infinito a cero. Sin embargo, en un caso más práctico donde sí hay pérdidas de energía, la amplitud de la onda reflejada siempre es menor que la de la onda incidente, excepto en la terminación.

Por consiguiente, la impedancia varía desde cierto valor máximo hasta cierto valor mínimo, o viceversa, dependiendo de si la línea termina en corto o en circuito abierto. La impedancia de entrada de una línea sin pérdida, vista hacia una línea de transmisión que termina en un corto o en circuito abierto, puede ser resistiva, inductiva o capacitiva, dependiendo de la distancia a la terminación

**Análisis fasorial de la impedancia de entrada: línea abierta**

Se usan en general los diagramas fasoriales para analizar la impedancia de entrada de una
línea de transmisión, por ser relativamente sencillos y dar una representación gráfica de las
relaciones de fase de corriente y voltaje. Estas relaciones se refieren a variaciones en el
tiempo. 

**Línea de transmisión de un cuarto de longitud de onda.** La fig. 8-19a muestra el diagrama fasorial del voltaje, y la fig. 8-19b el diagrama fasorial de la corriente en la entrada de un tramo de un cuarto de onda, de una línea de transmisión terminada en un circuito abierto. Las formas de onda de la corriente y del voltaje incidentes son Ii y Vi , respectivamente, en el extremo de la entrada (de la fuente) de la línea en determinado instante. 

<center> <img src="/fig8-19.jpg" alt="centered image" > </center>

Todo voltaje reflejado, Er, en la entrada de la línea ha viajado la mitad de una longitud de onda, de la fuente a la abertura y de regreso y en consecuencia está 180° retrasado al voltaje incidente. Por consiguiente, el voltaje total Et en el extremo de entrada es la suma de Ei y Er. Es decir,
Et = Ei + Er / -180°, y, suponiendo una pérdida pequeña en la línea, Et = Ei - Er. La corriente reflejada se demora 90° al propagarse de la fuente a la carga, y otros 90° en el regreso de la carga a la fuente.

También, la corriente reflejada sufre una inversión de 180° en el extremo abierto. La corriente reflejada se ha demorado en realidad 360°. Por consiguiente, cuando la corriente reflejada llega al extremo de la fuente, está en fase con la corriente incidente y la corriente total es It = Ii + Ir.

Se puede ver, al examinar la fig. 8-19, que Et e It están en fase. Por consiguiente, la impedancia de entrada viendo hacia una línea de transmisión de un cuarto de longitud de onda de largo terminada en un circuito abierto es Z(ent) = Et / 0° /It/ 0° = Z(ent) / 0° . Zent tiene ángulo de fase 0° y en consecuencia es resistiva y es mínima. Así, una línea de transmisión terminada en un circuito abierto equivale a un circuito LC resonante en serie.

<center> <img src="/fig8-20.jpg" alt="centered image" > </center>

La fig. 8-20 muestra varios fasores de voltaje para las ondas incidente y reflejada en una
línea de transmisión terminada en circuito abierto, y la forma en que producen una onda de
voltaje estacionaria.

**Línea de transmisión de longitud menor que un cuarto de longitud de onda.** La fig. 8-21a muestra el diagrama fasorial de voltaje, y la fig. 8-21b muestra el diagrama fasorial de corriente de una línea de transmisión más corta que un cuarto de longitud de onda (/4), terminada en circuito  abierto.

<center> <img src="/fig8-21.jpg" alt="centered image" > </center>

De nuevo, la corriente incidente Ii y el voltaje incidente Ei están en fase. La onda reflejada de voltaje se demora 45° al ir de la fuente a la carga (distancia que equivale a un octavo de longitud de onda) y otros 45° al regresar de la carga a la fuente (otro octavo de longitud de onda más). Por consiguiente, cuando la onda reflejada llega al extremo de la fuente, está retrasada 90° respecto a la onda incidente. El voltaje total en el extremo de la fuente es la suma vectorial de las ondas incidente y reflejada. Así <img src="/Et.jpg">

La onda reflejada de corriente se demora 45° al ir de la fuente a la carga y otros 45° al regresar de la carga a la fuente (una distancia total de un cuarto de longitud de onda). Además, la onda reflejada de corriente ha sufrido una inversión de fase de 180° en el extremo abierto antes de ser reflejada. Así, la onda reflejada de corriente tiene una demora total de 270°. Por lo anterior, la onda reflejada de hecho antecede 90° a la onda incidente.

La corriente total en el extremo de la fuente es la suma vectorial de las ondas incidente y reflejada. Es decir,<img src="/It.jpg"> Al examinar la fig. 8-21 se puede ver que Et está retrasado 90° respecto a It. Entonces <img src="/zent.jpg">

 La impedancia Zent tiene ángulo de fase de -90° y por consiguiente es
capacitiva. Toda línea de transmisión más corta que un cuarto de longitud de onda que esté terminada en un circuito abierto equivale a un capacitor. La cantidad de capacitancia depende de
la longitud eléctrica exacta de la línea.

**Línea de transmisión mayor que un cuarto de longitud de onda.** La fig. 8-22a muestra el diagrama fasorial de voltaje y la fig. 8-22b el diagrama fasorial de corriente para una línea de transmisión más larga que un cuarto de longitud de onda, terminada en circuito abierto. 

<center> <img src="/fig8-22.jpg" alt="centered image" > </center>

Para este ejemplo se usa una línea de transmisión de tres octavos de longitud de onda. El voltaje reflejado está demorado tres cuartos de longitud de onda, o 270°. Por consiguiente, de hecho el voltaje se adelanta 90° al voltaje incidente. Entonces, el voltaje total es <img src="/Et2.jpg">

La onda reflejada de corriente está demorada 270° y ha sufrido una inversión de fase de 180° en el extremo abierto. Por ello, de hecho la corriente reflejada está retrasada 90° respecto a la corriente incidente. Entonces, la corriente total es <img src="/It2.jpg"> Así, <img src="/zent2.jpg">

La impedancia Zent tiene un ángulo de fase de +90° y en consecuencia es inductiva. La magnitud de la impedancia de entrada es igual a la impedancia característica en los puntos a un octavo de longitud de onda. Una línea de transmisión entre un cuarto y media longitud de onda que termina en un circuito abierto equivale a un inductor. La cantidad de inductancia depende de la longitud eléctrica exacta de la línea.

**Línea de transmisión abierta como elemento de circuito.** Es obvio que una línea de transmisión abierta se puede comportar como un resistor, un inductor o un capacitor, dependiendo de su longitud eléctrica. Como las pautas de onda estacionaria en una línea abierta se repiten cada intervalo de media longitud de onda, la impedancia de entrada también se repite.

<center> <img src="/fig8-23.jpg" alt="centered image" > </center>

La fig. 8-23 muestra las variaciones en la impedancia de entrada para una línea de transmisión abierta de varias longitudes eléctricas. Se ve que la impedancia de una línea abierta es resistiva y máxima en el extremo abierto y a cada intervalo sucesivo de media longitud de onda, y resistiva y mínima a un cuarto de longitud de onda del extremo abierto y a cada intervalo sucesivo de media longitud de onda.

Para longitudes eléctricas menores que un cuarto de longitud de onda, la impedancia de entrada es capacitiva y disminuye con la longitud. Para longitudes eléctricas entre un cuarto y media longitud de onda, la impedancia de entrada es inductiva y aumenta con la longitud. Los patrones de capacitancia y de inductancia también se repiten cada media longitud de onda.

**Análisis fasorial de la impedancia de entrada: línea en cortocircuito**

Las siguientes explicaciones usarán diagramas fasoriales para el análisis de líneas de transmisión puestas en corto de la misma forma que con las líneas abiertas. La diferencia es que en
las líneas de transmisión en corto, la forma de onda de voltaje se regresa con una inversión de
fase de 180°, mientras que la onda de corriente se refleja como si no hubiera corto.

**Línea de transmisión de un cuarto de longitud de onda.** Los diagramas fasoriales de voltaje y corriente, para una línea de transmisión de un cuarto de longitud de onda terminada en un cortocircuito son idénticos a los de la fig. 8-19, pero invertidas. Los voltajes incidente y reflejado están en fase y en consecuencia Et = Ei + Er y es máximo. Las corrientes incidente y
reflejada están desfasadas 180° y, en consecuencia, It = Ii + Ir y es mínima. Entonces <img src="/zent2.jpg"> y es máxima. La impedancia Zent tiene ángulo de fase de 0°, es resistiva y
es máxima. Por consiguiente, una línea de transmisión terminada en un cortocircuito equivale a
un circuito LC en paralelo.

**Línea de transmisión menor que un cuarto de longitud de onda.** Los diagramas fasoriales de voltaje y corriente para una línea de transmisión menor que un cuarto de longitud de onda y terminadas en cortocircuito son idénticos a los de la fig. 8-21, pero invertidos. El voltaje se invierte 180° en el corto y la corriente se refleja con la misma fase que tendría si hubiera continuado. Por consiguiente, el voltaje total en el extremo de la fuente de la línea se adelanta 90° a la corriente y la línea se ve inductiva.

**Línea de transmisión mayor que un cuarto de longitud de onda.** Los diagramas fasoriales de voltaje y corriente para una línea de transmisión mayor que un cuarto de longitud de onda, terminada en cortocircuito, son idénticos a los de la fig. 8-22, pero invertidos. El voltaje total en el extremo de la línea que da a la fuente se retrasa 90° a la corriente, y la línea se ve capacitiva.

**Línea de transmisión en cortocircuito como elemento de circuito.** De acuerdo con la descripción anterior es obvio que una línea de transmisión puesta en corto se puede comportar como si fuera un resistor, un inductor o un capacitor, dependiendo de su longitud eléctrica. En una línea de transmisión en corto, las ondas estacionarias se repiten cada media longitud de onda, y en consecuencia también se repite la impedancia de entrada. 

<center> <img src="/fig8-24.jpg" alt="centered image" > </center>

La fig. 8-24 muestra las variaciones de impedancia de entrada de una línea de transmisión en corto, para diversas longitudes eléctricas. Se ve que una línea en corto tiene impedancia resistiva y mínima en el corto y en cada intervalo sucesivo de media longitud de onda, y resistiva y máxima a un cuarto de longitud de onda del corto, y en cada intervalo sucesivo de media longitud de onda.

**Resumen de impedancia de entrada a una línea de transmisión.** La fig. 8-25 es un resumen de las configuraciones de línea de transmisión que se describieron en las secciones anteriores, sus características de impedancia de entrada y sus circuitos LC equivalentes. Se ve que los tramos en corto y abiertos de las líneas de transmisión se pueden comportar como resistores, inductores o capacitores, dependiendo de su longitud eléctrica.

<center> <img src="/fig8-25.jpg" alt="centered image" > </center>

**Acoplamiento de impedancias en líneas de transmisión**

La potencia se transfiere a una carga cuando no hay ondas reflejadas, esto es, cuando la carga es puramente resistiva e igual a Zo. Siempre que la impedancia característica de una línea de transmisión con su carga no estén balanceadas (sean iguales), habrá ondas estacionarias en la línea,
y no se transfiere la potencia máxima a la carga. Las ondas estacionarias causan pérdida de potencia, falla del dieléctrico, ruido, radiación y señales fantasma.

Así, de ser posible, una línea de transmisión se debe adaptar a su carga. Para adaptar una línea de transmisión a una carga que tenga una impedancia distinta de Zo se usan dos técnicas comunes. Son la compensación con transformador de un cuarto de longitud de onda mediante línea de acoplamiento.

**Adaptación con transformador de un cuarto de longitud de onda.** Los transformadores de un cuarto de longitud de onda se usan para compensar las líneas de transmisión con cargas puramente resistivas cuya resistencia no sea igual a la impedancia característica de la línea. Téngase en cuenta que un transformador de un cuarto de longitud de onda en realidad no es un transformador, sino más bien una sección de línea de transmisión de un cuarto de longitud de onda que funciona como si fuera un transformador.

La impedancia de entrada a una línea de transmisión varía desde un valor máximo hasta uno mínimo o viceversa, cada cuarto de longitud de onda. Así, una línea de transmisión de un cuarto de longitud de onda de largo funciona como un transformador elevador o un transformador reductor, dependiendo de si ZL es mayor o menor que Zo.

Un transformador de un cuarto de longitud de onda no es un dispositivo de acoplamiento de impedancia de banda ancha; es de cuarto de longitud de onda en una sola frecuencia. Las transformaciones de impedancia para una línea de transmisión de un cuarto de longitud de onda son las siguientes:
1. RL = Zo: la línea de un cuarto de longitud de onda funciona como un transformador
con relación de vueltas 1:1.
2. RL > Zo: la línea de un cuarto de longitud de onda funciona como un transformador
reductor.
3. RL < Zo: la línea de un cuarto de longitud de onda funciona como un transformador
elevador.

Como en los transformadores, uno de un cuarto de longitud de onda se pone entre una línea de transmisión y su carga. El transformador de un cuarto de longitud de onda no es más que un tramo de línea de transmisión de un cuarto de longitud de onda de largo.

<center> <img src="/fig8-25.jpg" alt="centered image" > </center>

La fig. 8-26 muestra cómo se usa ese transformador para adaptar una línea de transmisión a una carga puramente resistiva. La impedancia característica de la parte de un cuarto de longitud de onda se calcula con la fórmula

<center> <img src="/Z0.jpg" alt="centered image" > </center>

**Adaptación con línea de acoplamiento.** Cuando una carga es puramente inductiva o puramente capacitiva no absorbe energía. El coeficiente de reflexión es 1, y la relación de onda estacionaria (SWR) es infinita. Cuando la carga es una impedancia compleja, y este suele ser el caso, es necesario eliminar la componente reactiva para adaptar la línea de transmisión a la carga. Para este objeto se utilizan líneas de acoplamiento.

Una línea de acoplamiento a una línea de transmisión no es más que un tramo adicional de línea de transmisión que se conecta entre los hilos de la línea primaria, tan cerca como sea posible de la carga. La susceptancia de la línea se usa para sintonizar la susceptancia de la carga. Para la adaptación con línea de acoplamiento se colocan líneas en corto o abiertas. Sin embargo, se prefieren las líneas en corto, porque las líneas abiertas tienen la tendencia a irradiar, en especial a frecuencias más elevadas

<center> <img src="/fig8-27.jpg" alt="centered image" > </center>

La fig. 8-27 muestra cómo se conecta una línea en corto para anular la susceptancia de la carga y balancear la resistencia de carga con la impedancia característica de la línea de transmisión. Se ha demostrado cómo un tramo de línea de transmisión puesto en corto puede verse resistivo, inductivo o capacitivo, dependiendo de su longitud eléctrica. Una línea de transmisión de media longitud de onda o menor se puede usar para sintonizar y eliminar el componente resistivo de una carga.

<center> <img src="/aco.jpg" alt="centered image" > </center>