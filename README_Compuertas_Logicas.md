# Informe sobre las compuertas lógicas

## Introducción

La lógica booleana es un sistema que trabaja principalmente con dos valores: **0 y 1**. Estos valores pueden representar diferentes estados, como falso y verdadero, apagado y encendido o desactivado y activado. Las compuertas lógicas son elementos fundamentales de la electrónica digital, ya que reciben una o varias entradas y, de acuerdo con una operación lógica, producen una salida.

El objetivo de este trabajo es comprender el funcionamiento de las principales compuertas lógicas, conocer sus operaciones y entender cómo funcionan sus tablas de verdad. Estas compuertas son importantes porque hacen posible el funcionamiento de muchos dispositivos electrónicos y sistemas digitales que utilizamos diariamente.

## Compuerta AND

La compuerta **AND** realiza una multiplicación lógica. Su característica principal es que la salida solamente es **1 cuando todas sus entradas son 1**. Si alguna de las entradas es 0, el resultado será 0. Su expresión lógica es **F = A · B**. Por ejemplo, si A = 1 y B = 1, entonces F = 1. En cambio, si A = 1 y B = 0, la salida será 0. Una situación cotidiana que puede representar esta compuerta es una máquina que solamente funciona cuando se cumplen dos condiciones al mismo tiempo.

## Compuerta NAND

La compuerta **NAND** es la combinación de una compuerta AND con una negación. Esto significa que hace lo contrario de AND. Su salida es **0 solamente cuando todas las entradas son 1** y es 1 en los demás casos. Su expresión es **F = ¬(A · B)**. Por ejemplo, cuando A = 1 y B = 1, la salida es 0; pero cuando A = 1 y B = 0, la salida es 1.

## Compuerta OR

La compuerta **OR** realiza una suma lógica. Su salida es **1 cuando al menos una de sus entradas es 1**. Solamente produce 0 cuando todas las entradas son 0. Su expresión lógica es **F = A + B**. Por ejemplo, si A = 1 y B = 0, la salida será 1. También será 1 si ambas entradas son 1. Un ejemplo de su uso podría ser un sistema de alarma que se activa cuando se presenta cualquiera de dos condiciones.

## Compuerta NOR

La compuerta **NOR** es la negación de la compuerta OR. Por esta razón, su salida es **1 únicamente cuando todas sus entradas son 0**. Si alguna de las entradas es 1, la salida será 0. Su expresión lógica es **F = ¬(A + B)**. Por ejemplo, si A = 0 y B = 0, la salida es 1; pero si A = 0 y B = 1, la salida será 0.

## Compuerta XOR

La compuerta **XOR**, también llamada OR exclusiva, produce una salida de **1 cuando sus entradas son diferentes**. Cuando las dos entradas tienen el mismo valor, la salida es 0. Su expresión es **F = A ⊕ B**. Por ejemplo, si A = 0 y B = 1, el resultado es 1. Si A = 1 y B = 1, el resultado es 0. Esta compuerta es útil en sistemas digitales donde se necesita detectar si dos señales tienen valores diferentes.

## Compuerta NOT

La compuerta **NOT** tiene una sola entrada y se encarga de invertir su valor. Si recibe un 0, produce un 1, y si recibe un 1, produce un 0. Por esta razón también se conoce como **inversor**. Su expresión es **F = ¬A**. Por ejemplo, si A = 0, entonces F = 1; y si A = 1, entonces F = 0.

## Tablas de verdad

Las tablas de verdad permiten representar todas las posibles combinaciones de las entradas y observar cuál será la salida de una compuerta. Para las compuertas de dos entradas, existen cuatro combinaciones posibles: 00, 01, 10 y 11.

- **AND:** 0, 0, 0, 1
- **NAND:** 1, 1, 1, 0
- **OR:** 0, 1, 1, 1
- **NOR:** 1, 0, 0, 0
- **XOR:** 0, 1, 1, 0
- **NOT:** si la entrada es 0, la salida es 1; si la entrada es 1, la salida es 0.

## Aplicaciones de las compuertas lógicas

Las compuertas lógicas se utilizan en muchos dispositivos electrónicos, como computadores, celulares, calculadoras, relojes digitales, sistemas de seguridad, robots y sistemas de control. Al combinar diferentes compuertas se pueden construir circuitos más complejos capaces de realizar operaciones matemáticas, tomar decisiones y controlar diferentes procesos automáticamente.

## Conclusión

En conclusión, las compuertas lógicas son fundamentales para el funcionamiento de la electrónica digital porque permiten procesar información utilizando los valores 0 y 1. Cada compuerta tiene una función diferente: **AND** necesita que todas sus entradas sean verdaderas, **OR** necesita que al menos una sea verdadera, **NOT** invierte el valor, mientras que **NAND, NOR y XOR** realizan operaciones derivadas que permiten crear circuitos más complejos. Comprender las tablas de verdad y las operaciones de estas compuertas ayuda a entender cómo funcionan muchos de los dispositivos tecnológicos que utilizamos en nuestra vida diaria.
