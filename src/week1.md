## Week challenges (Tuesday 19 of july 22) 💻

1. Base on [this reading](https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/) and [this video](https://www.youtube.com/watch?v=I1f45REi3k4), create an explanation about `Interpreted And Compiled Programming Languages` in your README


    <p> R= Lo que pude comprender es que existen diferentes tipos de lenguajes en la programación, busqué información adicional aparte del que han enviado, para poder ayudarme a guíar y de ese modo sacar una conclusión con respecto al tema del día de hoy. </p>
    <p> Por lo que cabe destacar las diferencias entre el "Interpreted And Compiled Programming Languages" ya que un <strong>lenguaje compilado</strong>, genera un file binario no modificable. y el <strong>lenguaje interpretado</strong> es escrito en un lenguaje de programación definido y modificable en cada momento. </p>

2. Is Java compiled or interpreted, or both?, check the sources and answer the question in your README

    <p> R= Es ambas, ya que según los creadores de Java querían un lenguaje compilado pero a su vez que fuese ejectuado en diferentes tipos de sistemas operativos, por lo que buscando información adicional pude encontrar que <em>es un lenguaje particular porque es compilado, pero es compilado a un lenguaje intermedio llamado bytecode, que después es interpretado</em>
    Dando como fin que al ser creado como un <strong>lenguaje compilado</strong> debe compilarse con el código fuente de Java hasta el código de bytes . Luego el código de bytes es ejecutado por una máquina virtual Java (JVM). Para luego ser <strong>interpretado</strong>  por una máquina virtual Java (JVM).

3. [Pseudocode Currency Converter](./exercises/e00/desc) exercise

    Available Instructions


    Starting point: START

    Input: READ, GET

    Output: PRINT

    Math: +, -, *, /

    Assignation: <--

    Initialize: SET, INIT

    Add one: INCREMENT

    End point: END


     ## Pseucode Currency Converter

    Answer:

    1. START
    2. USDMont: READ
    3. BTC Cost: READ FROM (https://es.investing.com/currencies/usd-btc-converter)
    4. Total USD TO BTC: *
    5.  PRINT: COST USD TO BTC
    6. END

4. Learn about [High and Low level languages](https://www.youtube.com/watch?v=bUWCD45qniA)

Answer:
Primero hay que tomar en cuenta la definición del Lenguaje Máquina, la cual como sabemos es una sistema de Códigos interpretable directamente por un circuito microprogramable, como el microprocesador de una computadora.
Por lo que es importante saber eso para poder desarrollar los siguientes terminos del "High and Lowe level Languages"
1. Low Level Languages: Su definición es que dicho lenguaje proporciona o ninguna abstracción (o sea la conceptualización) del micropocesador de una computadora. Por lo que el traslado de dicho lenguaje a una maquina es sencilla.
Otro ejemplo sería el ensamblador "assembler", que es un tipo de programa informático encargado de traducir un archivo fuente, escrito en el lenguaje ensamblador, a un archivo fuente.
Por lo que entiendo es que se requiere un alto grado de expecialización por parte de los programadores, ya que dicho lenguaje es exclusivo de un ordenador o plataforma donde se ejecuten.

2. High Level Languages:
 Según la definición que encontré se caracterizan porque la estructura semántica es muy similar a la forma como escribimos los humanos, por lo que es más sencillo codificar los algoritmos de manera mas natural, a mi entender es que en lugar de codificarlos en el lenguaje binario de las máquinas, es mucho más natural.
 Por lo que es independiente del hardware en el que se ejecutan, de ese modo facilita al programado  centrarse en los problemas a resolverse.

    Ejemplo de lenguajes de alto nivel:
    - a) C++
    - B) Fortran
    - c) Java

## Week challenges (Wednesday 20 of July of 2022) 💻

1. [Your date of birth in the matrix?](./exercises/e01/desc) exercise

<br>

04-07-1997 convert to binary

First 04   

| 32 | 16| 8| 4|2 | 1|
|:-------------------:|---|---|---|---|---|
| 0 | 0 | 0| 1 | 0| 0

## 04 = 000100 <br>

Second 07
 
 | 8 | 4| 2| 1|
|:-------------------:|---|---|---|
| 0 | 1 | 1| 1| 

## 07 = 0111

Third 1997

| 2048 | 1024| 512| 256| 128 |64 | 32 | 16| 8 | 4 | 2 | 1|
|:-------------------:|---|---|---|---|---|---|---|---|---|---|---|
| 0 | 1 | 1| 1 | 1 | 1 | 0 | 0 | 1| 1 | 0| 1|

## 1997 = 011111001101
<br>

**Solution**

<br>

## 04= 0100

## 07= 0111

## 1997= 011111001101

<br>

## Recurso adicional
Al no comprender mucho sobre el tema, tuve que buscar información adicional y encontré este video en youtube que me ayudó mucho.
**[Conversión de números entre Sistemas Numéricos - Técnica RÁPIDA y FÁCIL
](https://www.youtube.com/watch?v=QrULhy0P_uU)**


2. [MIPS](./exercises/e02/desc) exercise

    ##  Descripción

    Basado en la [ guía ](#guía) y los [ ejemplos ](#ejemplos) del lenguaje de bajo nivel, crea lo siguiente

    <p>1. Cree un programa que sume dos números proporcionados por el usuario</p>

      .data
        message: .asciiz "\nMy name is: Farik Ayarza!\n"
  .text
        main:
              li $v0, 4
              la $a0, message
              syscall
    2. Crea un programa que muestre tu nombre

## Week challenges (Thursday 21 of july 2022) 💻

1. [Print special numbers](./exercises/e03/desc) exercise
## Description

In this exercise you must use an iterative flow control to be able to print all the even numbers in the range of numbers from 0 to 100. Remember that you should not print each number, you should use a flow control structure to perform the exercise

### Answer

*   [For](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)

		for (let i = 0; i <= 100; i++) {
 			if((i % 2) == 0 ){
			 console.log(i);
 			} 


2. [Bad Code](./exercises/e04/desc) exercise
## Description

The code shown below is not working in the right way, as a task you must find the error made by the developer who programmed this code and correct it, for this exercise you must explain what the error is and place the correct code

### Answer

    var cond = false;

    if (cond == true) {
    console.log('The cond variable is true');
    } else {
    console.log('The cond variable is false');
    }

3. [Bad Code 2](./exercises/e05/desc) exercise

    var n = 100;

    if (n == 100) {
    console.log('This is a special number!');
    }

    if (n <= 1000) {
    console.log('This number is almost special');
    
    } else {
    console.log('Just a regular number');
    
    }
    if (n % 10 == 0) {
    console.log('This number is multiple of 10');
    }

4. [Follow Git Course](https://www.udacity.com/course/version-control-with-git--ud123)
