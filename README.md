<h1 align="center">
Lab 1: Lógica de Programación (RA 1) <br />
 </h1>
 <p align="center">
Alexander López-Parrado, PhD. <br />
Programación, II-2024 <br />
GDSPROC <br />
Uniquindío <br />
</p>

Esta práctica de laboratorio busca poner en práctica todos los elementos básicos del lenguaje de programación Python. Para tal fin, se propone un reto que está relacionado directamente con el proyecto final y que pondrá en práctica estructuras de programación tales como: declaración de variables, sentencias condicionales, sentencias para ciclos, arreglos y funciones.

## Descripción del Reto

El reto de esta práctica de laboratorio consiste en implementar una **versión minimalista para terminal del juego Preguntados** **(*Trivia Crack*)**. En ese sentido, se espera que el juego soporte las siguientes características:

* Un único jugador.
* Tres categorías de preguntas.
* 10 preguntas por categoría.

Una vez se inicie el programa, se le debe solicitar al usuario su nombre, el cual deberá ser usado durante el progreso en el juego. Posteriormente, el usuario deberá iniciar la selección aleatoria de la categoría de la pregunta, el programa debe mostrar la categoría seleccionada y a continuación desplegar la pregunta junto con las opciones de respuesta.

El mecanismo de puntuación y penalización del usuario es de libre elección por parte del equipo de trabajo, en todo caso el usuario debe poder finalizar el juego en cualquier momento. Si el usuario ha respondido correctamente todas las preguntas de las tres categorías, el programa debe finalizar con un mensaje de felicitación para el usuario.

## Requisitos técnicos

 * Se debe garantizar que no se repitan preguntas que el usuario ha respondido correctamente.
 * El programa debe usar únicamente listas, funciones y las demás estructuras de programación vistas en clase.
 * 


En esta sección repasará y pondrá en práctica de nuevo las sentencias condicionales del lenguaje de programación C y además conocerá las sentencias equivalentes en el lenguaje de programación Python. Para lo anterior, considere el programa en el archivo [bmi.c](bmi.c) que realiza el cálculo del índice de masa corporal (BMI) para una persona a partir de su peso y de la estatura. 

1. Compile y ejecute el programa, y realice pruebas con diferentes valores de peso y estatura.

2. Cree un programa a partir de [bmi.c](bmi.c) que le informe al usuario si se encuentra en alguna de las siguientes condiciones: bajo peso, peso normal, sobrepeso u obesidad.

3. Mediante la herramienta de Inteligencia Artificial (IA) Generativa ChatGPT, genere el equivalente en Python (bmi.py) del programa [bmi.c](bmi.c). Identifique las similitudes y diferencias entre ambas implementaciones.

4. Re-implemente el programa del punto 2 en Python, **esta vez sin usar ChatGPT**.

## Ciclos y Arreglos

En esta sección se considerarán las sentencias para ciclos y el uso de arreglos en los lenguajes de programación C y Python. Para lo anterior, considere los programas [bmi.c](bmi.c) y bmi.py de la sección anterior.

1. Cree un programa a partir de [bmi.c](bmi.c) que solicite al usuario un número de personas y que posteriormente solicite la estatura y peso para cada una de ellas, calcular, almacenar e imprimir el BMI para cada una de las personas.

2. Modifique el programa del punto 1 para que se calcule e imprima el porcentaje de personas que se encuentra en alguna de las siguientes condiciones: bajo peso, peso normal, sobrepeso u obesidad.

3. Re-implemente los programas de los puntos 1 y 2 en Python **sin usar ChatGPT**.


## Funciones

Para terminar, en esta sección pondrá en práctica la creación de funciones en los lenguajes de programación C y Python. Recuerde que las funciones son construcciones que permiten crear código modular, escalable y de mayor legibilidad.

Para lo anterior, considere los programas que construyó en los puntos 2 y 4 de la sección [Sentencias Condicionales](#sentencias-condicionales).

1. Realice una modificación a ambos programas para que se le informe al usuario el peso ideal para lograr la condición de peso normal, esto solo en el caso de que el usuario se encuentre en algunas de las siguientes condiciones: bajo peso, sobrepeso u obesidad. Para lo anterior cree una función que realice el cálculo del peso ideal.

# Entrega del laboratorio

El laboratorio debe ser presentado mediante:

1. Repositorio en GitHub.
2. Informe de laboratorio.

El informe de laboratorio y el enlace al repositorio de GitHub deben ser compartidos en el enlace dispuesto para tal fin en la plataforma Google Classroom.
