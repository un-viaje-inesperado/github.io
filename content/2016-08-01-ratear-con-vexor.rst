:title: Cómo ratear con la Vexor Navy Issue
:date: 2016-08-01 10:00
:category: tutorial
:tags: drones, VNI
:author: Piloto X
:excerpt: como ratear con la vexor navy issue
:disqus_identifier: como ratear con la vexor navy issue 

En este artículo comento los puntos que me parecen importantes para ratear,
mucho de lo cual aprendí de mis compañeros de corp. También incluyo cosas que
encontré por la web y otras que descubrí por mi mismo.

La nave recomendable para empezar a ratear en soledad es la `Vexor Navy Issue`_
(**VNI**), que vale unos 65m de isk (más unos 30 o 40m para sus módulos).
También se puede ratear con la `Vexor`_ común, pero un piloto novato no tiene
suficientes skills para que la experiencia sea agradable y redituable en las
anomalías de null-sec. La VNI no sólo tiene un low slot más, sino que la
diferencia más importante es su ancho de banda de 125 Mbit/sec que permite sacar
5 drones pesados simultaneamente (cada uno ocupa 25 Mbit/sec), mientras que la
Vexor sólo cuenta con 75 Mbit/sec que permiten sólo 3 berserkers en el espacio
en simultaneo (o un grupo con 2 pesados, 2 medianos y 1 liviano).

Secuencia de ataque
-------------------

Una vez elegida la anomalía (en la web encontré que las mejores en términos de
isk/hora son las forsaken hub, ya que tienen pocas fragatas y muchas
battleships, y resultan más relajadas que las havens que tienen fragatas en casi
todas sus oleadas) la secuencia es la siguiente:

1. warpear a 20 km.
2. orbitar a unos 15 km de algún elemento que esté cercano al centro de la
   anomalía.
3. encender el afterburner (AB), no olvidarlo porque es vital para tanquear a
   velocidad (esquivar el daño).
4. encender el escudo activo si está disponible (depende de los módulos
   instalados).
5. sacar los berserkers (que atacarán inmediatamente después de que nuestra nave
   tenga el *aggro*). Esperar a que los drones ataquen solos al primer objetivo,
   salvo que los hayamos sacado muy tarde y se queden inmóviles mientras nuestra
   nos atacan la nave. En este caso iniciar el primer ataque manualmente hasta
   completar el punto 6.
6. targetear las naves pequeñas y atacarlas manualmente.
7. dejar a los drones atacar a las naves grandes en el orden que les plazca.

En algún momento, mis drones sufrían el ataque de las ratas y debía hacerlos
retornar porque pierden escudo y armadura muy rápido. Para evitar este problema
nuestra nave tiene que empezar a recibir daño (tener el *aggro*) antes de enviar
los drones al ataque. Pero para que ataquen por sí solos, ya deben estar en el
espacio (y en modo agresivo) cuando empezamos a recibir daño. De esta manera los
drones hacen su trabajo tranquilos, sin ser atacados ni una sola vez.

Al sacar los berserkers lo que he visto es que atacan inicialmente la nave más
pequeña que encuentran, sea una fragata, un cruiser, un battlecruiser, lo cual
está muy bien. Pero el segundo blanco lo eligen incorrectamente y se van directo
a atacar una battleship. Por eso el punto 5 es sacar los drones (que deben estar
en modo agresivo y con focus fire) sin hacer nada más, sólo esperar a que
ataquen por sí solos, ya que atacan la nave correcta aún sin que tengamos un
target lock (un objetivo fijado). Mientras los drones hacen trizas la primera
nave tenemos tiempo de fijar nuestros objetivos primarios, y al hacerlo
descubriremos cuál nave están atacando. Continuamos con el punto 6 enviando
manualmente a nuestros pequeños a atacar las naves restantes, hasta que sólo
quedan battleships. Recién ahí dejamos a los drones decidir por sí solos y nos
dedicamos a ver Netflix. ;)

A pesar de que en el `artículo sobre drones`_ escribí que éstos se eligen de
acuerdo a la envergadura de las naves enemigas (fragatas, battleships, etc), en
las anomalías sólo uso berserkers incluso para deshacerme de las fragatas. Si
tuviese que llamarlos de vuelta cada vez que aparece una nueva oleada, esperar a
que lentamente retornen (sobre todo si están lejos), lanzar los livianos y
finalmente hacer el proceso inverso, todo esto llevaría una eternidad, con lo
cual se pierde la ventaja de usar warriors para atacar las fragatas. Además, los
berserkers son los drones pesados más rápidos de todos los raciales, y tienen
una eficiencia más que aceptable para destruir fragatas y deshacernos de sus
warp scramblers y target painters.

Fiteo
-----

Una configuración para tener como objetivo inicial para ratear con suficiencia
es::

    [Vexor Navy Issue, T2]

    Capacitor Power Relay II
    Capacitor Power Relay II
    Capacitor Power Relay II
    Drone Damage Amplifier II
    Drone Damage Amplifier II
    Drone Damage Amplifier II

    Large Shield Extender II
    Large Shield Extender II
    100MN Monopropellant Enduring Afterburner
    Adaptive Invulnerability Field II

    Drone Link Augmentor II
    [Empty High slot]
    [Empty High slot]
    [Empty High slot]

    Medium Core Defense Field Extender I
    Medium Core Defense Field Extender I
    Medium Core Defense Field Extender I


    Berserker II x5

Por supuesto que un piloto nuevo tardará en poder equiparse con todos estos
módulos T2, así que comenzará con varios (o todos) T1. Por otra parte, hay que
tener en cuenta que si bien es recomendable llegar a una nave estable (aquella
en la que todos los módulos pueden permanecer prendidos todo el tiempo) igual se
puede ratear pulsando algunos módulos activos, es decir prendiéndolos sólo por
algunos ciclos. Por ejemplo esto se puede hacer con el *Adaptive Invulnerability
Field*, de modo que esté encendido sólo durante el tiempo en que estamos
recibiendo más daño (generalmente cuando están presentes las fragatas enemigas
que nos enlentecen o aplican el target painter).

Los berserker pueden ser los T1, pero hay disponible una variante más poderosa y
no tan cara que se pueden usar desde el principio: son los *Integrated
Berserker* que cuestan unos 500k. Y si disponen de suficiente isk para arriesgar
(porque a veces los drones se pierden al huir rápidamente) pueden tratar de
conseguirse los *Republic Fleet Berserker* que son casi tan buenos como los
Berserker II, a unos 3 o 4 millones cada uno.

Un fiteo más experimental que busca optimizar el dps (en detrimento del escudo y
que requiere buenas skills para no quedarnos sin capacitor) es::

    [Vexor Navy Issue, Max VNI]

    Capacitor Power Relay II
    Capacitor Power Relay II
    Drone Damage Amplifier II
    Drone Damage Amplifier II
    Drone Damage Amplifier II
    Drone Damage Amplifier II

    Large Shield Extender II
    Large Shield Extender II
    100MN Monopropellant Enduring Afterburner
    Omnidirectional Tracking Link II, Optimal Range Script

    Drone Link Augmentor II
    [Empty High slot]
    [Empty High slot]
    [Empty High slot]

    Medium Drone Speed Augmentor II
    Medium Core Defense Field Purger I
    Medium Core Defense Field Purger I


    Berserker II x5

Skills
------

Un piloto muy nuevo tendrá que decidir qué skills subir primero, porque todas
tienen mucha importancia. Al principio es mejor subir varias a lvl 3 y 4 (lo
cual no ocupa tanto tiempo) en vez de concentrarse en subir cada una de ellas
al 5. Son muy importantes las siguientes para el dps: *Gallente Cruiser* (por el
bonus de la VNI) y *Drone Interfacing*. Además, creo que conviene subir
directamente la skill de drones pesados (*Heavy Drone Operation*) antes de subir
las de drones livianos y medianos, ya que sólo estarán usando Berserkers.

Si sufren mucho del daño de las ratas del Angel Cartel será bueno subirse las
skills que disminuyan el daño explosivo y cinético.

Cuando se animen a experimentar y hayan avanzado con el entrenamiento (yo creo
que con un mes enfocados en esto es más que suficiente) pueden jugar con el
equilibrio entre dps y tanqueo / capacitor. Por ejemplo, sustituyan en los lows
un *Capacitor Power Relay* por un *Drone Damage Amplifier*. Los fiteos avanzados
siempre tienen 4 de estos últimos, que son los únicos módulos que afectan el dps
de los drones (el dps efectivo en realidad también estará modulado por skills
que afecten la velocidad, tracking y rango de los drones). O coloquen un módulo
para mejorar el rango o el tracking de sus Berserkers (*Omnidirectional Tracking
Link*) a expensas de un *Shield Extender*.

Secuencia de huida
------------------

Cuando tengo que huir porque apareció un neutral en el sistema, la secuencia que
utilizo es la siguiente:

- terminar de matar las fragatas, puesto que son las únicas que pueden impedir
  el warpeo, lo cual es una condena a muerte.
- llamar los drones.
- apagar el afterburner (de lo contrario pueden tardar más en llegar los drones
  porque nos podríamos estar alejando de ellos a muy alta velocidad, y además se
  dificulta el warpeo).
- alinear a la POS (mejor) o a la estación/citadel (peor, porque pueden haber
  puesto una burbuja muy rápidamente).
- esperar los drones, escanear con el escaner direccional (dscan) buscando naves
  enemigas.
- si aparecen naves enemigas en el dscan, warpear aunque los drones no hayan
  llegado. Más vale perder 20 millones en 5 Republic Fleet Berserker que la nave
  completa con drones incluidos. Tema pendiente: cómo setear el dscan.
- si no aparecen naves enemigas, esperar los drones y warpear.

Justo cuando aparecen los neutrales uno se da cuenta de la importancia de las
skills y los módulos de velocidad de los drones (Drone Navigation,
Omnidirectional Tracking, Drone Navigation Computer). También es conveniente
haber usado una órbita pequeña (15km) alrededor de una zona central de la
anomalía, así los drones tendrán que recorrer menos distancia para volver.

Isk/hora
--------

Una anomalía como la Forsaken Hub da como recompensa total unos 25 a 27m de isk.
El tiempo que se tarda en limpiarla depende mucho de las skills del piloto (y si
tuvo que interrumpir la tarea por algún motivo). Yo me puse contento cuando
llegué a obtener 8m por tick (es decir cada 20 minutos, y tardando una hora
aproximadamente para completarla). Creo que no llegaba a los 380 dps.
Actualmente, que aún no maximicé las skills de drones todo lo posible y hago
unos 470 dps, estoy sacando unos 10-13m por tick. Con skills al máximo la VNI
llega a 648 dps y unos 18-20m por tick. Aunque estos números vienen del
simulador `pyfa`_ y no los verifiqué demasiado, sirven como referencia para
estimar qué tan lejos están de la cumbre del poder de destrucción.

Tengan en cuenta que el aumento de dps no es lineal, es decir que no necesitan
duplicar el dps para hacer la anomalía en la mitad del tiempo. Esto es así
porque una parte del dps se neutraliza por la capacidad de las ratas de
restablecer su escudo o armadura. Entonces, si las ratas se curan a 100 unidades
por segundo y les infligimos 100 unidades de daño, nunca las vencemos. Pero si
les infligimos 120 dps, tardaremos la mitad que asestándoles 110 dps. No se qué
tan claro es esto, pero por favor, no se desanimen. Entrenando las habilidades
correctas estarán ganando isk en un corto tiempo.

Progresión
----------

La nave que aparece en el horizonte después de tocar el techo del dps con
la VNI es la Ishtar (y con skills distintos la Gila y la Rattlesnake). Pero por
el momento, hay mucho isk por farmear con la querida Vexor Navy Issue.

.. _Vexor Navy Issue: http://wiki.eveuniversity.org/Vexor_Navy_Issue
.. _Vexor: http://wiki.eveuniversity.org/Vexor
.. _artículo sobre drones: |filename|/2016-07-11-drones.rst
.. _pyfa: https://github.com/pyfa-org/Pyfa
