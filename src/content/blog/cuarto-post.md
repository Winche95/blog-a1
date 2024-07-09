---
title: 'ONDAS (ESTACIONARIAS, INCIDENTES Y REFLEJADAS)'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 23 2022'
heroImage: 'onda.jpg'
---

**ONDAS INCIDENTES Y REFLEJADAS**

Una línea de transmisión ordinaria es bidireccional: la energía se puede propagar por igual en ambas direcciones. El voltaje que se propaga desde la fuente hacia la carga se llama voltaje incidente, y el que se propaga de la carga hacia la fuente se llama voltaje reflejado. De igual manera hay corrientes incidente y reflejada.

En consecuencia, la potencia incidente se propaga hacia la carga, y la potencia reflejada se propaga hacia la fuente. El voltaje y la corriente incidentes siempre están en fase cuando la impedancia es de carácter resistivo. En una línea infinitamente larga, toda la potencia incidente se almacena en ella, y no hay potencia reflejada. También, si la línea se termina en una carga puramente resistiva igual a la impedancia característica de la línea, la carga absorbe toda la potencia incidente (suponiendo que la línea no tenga pérdidas).
 
Para contar con una definición más práctica, la potencia reflejada es la parte de la potencia incidente que no absorbió la carga. En consecuencia, la potencia reflejada nunca puede ser mayor que la potencia incidente.

**Líneas de transmisión resonantes y no resonantes** Una línea de transmisión sin potencia reflejada se llama línea plana o no resonante. Una línea de transmisión es no resonante si su longitud es infinita o si termina en una carga resistiva igual al valor óhmico de su impedancia característica. En una línea plana, el voltaje y la corriente son constantes en toda su longitud, si se supone que no tiene pérdidas.

Cuando la carga no es igual a la impedancia característica de la línea, algo de la potencia se refleja y va hacia la fuente. Si la carga es un circuito cerrado o abierto, toda la potencia incidente se refleja hacia la fuente. Si se sustituyera la fuente por una abertura y un corto y la línea fuera sin pérdidas, la energía presente en ella se reflejaría de un lado a otro (oscilaría) entre los extremos de la fuente y la carga, de modo parecido a cuando la energía va y viene entre el capacitor y el inductor de un circuito tanque LC. A esto se le llama línea de transmisión resonante.

En una línea resonante, la energía es transferida en forma alternativa entre los campos magnéticos y eléctricos de la inductancia y la capacitancia distribuida de la línea.

<center> <img src="/fig8-14.jpg" alt="centered image" > </center>

La fig. 8-14 muestra una fuente, una línea de transmisión y una carga, con sus respectivas ondas incidente y reflejada.

**Coeficiente de reflexión** El coeficiente de reflexión es una cantidad vectorial que representa la relación del voltaje reflejado entre el voltaje incidente, o la corriente reflejada entre la corriente incidente. La definición matemática del coeficiente de reflexión, representado por la gamma mayúscula es

<center> <img src="/cr.jpg" alt="centered image" > </center>

**ONDAS ESTACIONARIAS**

Cuando Zo = ZL, toda la potencia incidente es absorbida por la carga. A esto se le llama línea compensada. Cuando Zo = ZL, algo de la potencia incidente queda absorbida en la carga y algo se regresa (se refleja) a la fuente. Es lo que se llama línea no compensada o línea descompensada. En
una línea no compensada hay dos ondas electromagnéticas que viajan en direcciones opuestas, al
mismo tiempo (de hecho, a esas ondas se les llama ondas viajeras). Las dos ondas viajeras establecen un patrón de interferencia llamada onda estacionaria.

<center> <img src="/fig8-15.jpg" alt="centered image" > </center>

Esto se ve en la fig. 8-15. Cuando las ondas incidente y reflejada pasan una por la otra, se producen patrones estacionarios de voltaje y corriente en la línea. Esas ondas se llaman estacionarias porque parecen permanecer en un lugar fijo de la línea, y sólo varían de amplitud. La onda estacionaria tiene mínimos (nodos) separados por una mitad de longitud de onda de las ondas viajeras, y tiene máximos (antinodos) también separados por una mitad de longitud de onda.

**Relación de onda estacionaria** La relación de onda estacionaria (SWR, de standing-wave ratio) se define como la relación del voltaje máximo al voltaje mínimo, o de la corriente máxima entre la corriente mínima de una onda estacionaria en una línea de transmisión. A ello también se le llama relación de voltajes de onda estacionaria (VSWR, por voltage standing-wave ratio). En esencia, la SWR es una medida de la falta de compensación entre la impedancia de carga y la impedancia característica de la línea de transmisión. La ecuación correspondiente es

<center> <img src="/RdOE.jpg" alt="centered image" > </center>

Las desventajas de no tener una línea de transmisión equilibrada (plana) se pueden resumir como sigue:
1. A la carga no le llega el cien por ciento de la potencia incidente desde la fuente.
2. El dieléctrico que separa los dos conductores puede fallar y causar un efecto corona
como resultado de la alta relación de voltajes de onda estacionaria.
3. Las reflexiones y las reflexiones repetidas causan más pérdida de potencia.
4. Las reflexiones causan imágenes fantasma.
5. Los desajustes causan interferencia de ruido.

**Ondas estacionarias en una línea abierta** Cuando las ondas incidentes de voltaje y corriente llegan a una terminación abierta, nada de energía se absorbe; se refleja por todo el trayecto hacia la fuente. La onda de voltaje incidente se refleja en la forma exacta como si fuera a continuar por una línea infinitamente larga. Sin embargo, la corriente incidente se refleja invertida 180 respecto a como hubiera continuado si la línea no estuviera abierta. Al pasar las ondas incidente y reflejada, se producen en la línea ondas estacionarias.

<center> <img src="/fig8-16.jpg" alt="centered image" > </center>

La fig. 8-16 muestra las ondas estacionarias de voltaje y corriente en una línea de transmisión terminada en circuito abierto. Se ve que la onda estacionaria de voltaje tiene un valor máximo en el extremo abierto, y uno mínimo a un cuarto de longitud de onda de la abertura. La onda estacionaria de corriente tiene un valor mínimo en el extremo abierto, y un valor máximo a un cuarto de longitud de onda de la abertura. Es razonable que el máximo voltaje esté en la abertura, y que allí haya corriente mínima.

Se pueden resumir como sigue las características de una línea de transmisión terminada
en una abertura:
1. La onda incidente de voltaje se refleja y regresa exactamente como si hubiera de continuar, es decir, sin inversión de fase.
2. La onda incidente de corriente se refleja y regresa a 180° respecto a como hubiera continuado.
3. La suma de las formas de onda de corriente incidente y reflejada es mínima en la
abertura.
4. La suma de las formas de onda de voltaje incidente y reflejado es máxima en la abertura.

También se ve en la fig. 8-16 que las ondas estacionarias de voltaje y corriente se repiten
cada mitad de longitud de onda. La impedancia en el extremo abierto es Z = V(máx)/I(mín) y es
máxima allí. La impedancia a un cuarto de longitud de onda de la abertura es Z = V(mín)/I(máx) y
es mínima allí. En consecuencia, a un cuarto de longitud de onda se presenta una inversión de
impedancia, y hay otras inversiones de impedancia a cada cuarto de longitud de onda.

**Ondas estacionarias en una línea en corto** Como en el caso de la línea abierta, la carga no absorbe potencia alguna cuando la línea de transmisión se termina en un cortocircuito. Sin embargo, si la línea está en corto, el voltaje y la corriente incidentes se reflejan y regresan en la forma contraria. La onda de voltaje se refleja con su fase invertida 180° respecto a la que tendría si continuara por una línea infinitamente larga, y la onda de corriente se refleja exactamente de la misma manera que si no hubiera corto.

<center> <img src="/fig8-18.jpg" alt="centered image" > </center>

La fig. 8-18 representa las ondas estacionarias de corriente y de voltaje en una línea de
transmisión que termina en un cortocircuito. Se ve que la onda estacionaria de voltaje tiene un
valor mínimo en el extremo puesto en corto, y un valor máximo a un cuarto de longitud de onda
del corto. La onda estacionaria de corriente tiene un valor máximo en el corto y un valor mínimo un cuarto de longitud de onda más atrás. Las ondas estacionarias de voltaje y de corriente
se repiten cada cuarto de longitud de onda.

Así, hay una inversión de impedancia cada intervalo
de cuarto de longitud de onda. La impedancia en el corto es Z = Vmín/Imáx = mínima, y un
cuarto de longitud de onda atrás es Z = Vmáx/Imín = máxima. De nuevo, es razonable que un mínimo de voltaje se presente en un corto, y que allí haya corriente máxima.

Las características de una línea de transmisión terminada en corto se pueden resumir
como sigue:
1. La onda estacionaria de voltaje se refleja y se invierte 180° respecto a la forma en que
continuaría.
2. La onda estacionaria de corriente se refleja del mismo modo que si hubiera continuado.
3. La suma de las formas de onda incidente y reflejada de corriente es máxima en el corto.
4. La suma de las formas de onda incidente y reflejada de voltaje es cero en el corto.



