# FundamentosDeProgramacion
Repositorio inicial de fundamentos de programación para el equipo FIRST FTC Avengears #31793
## Actividad: Pseudocódigo para calificar exámenes
 
Programa basico para calificar examenes
 
### Objetivo
 
Crear la lógica de un programa que permita revisar los exámenes de un grupo, calcular la calificación de cada alumno y determinar si cada alumno pasó o no pasó.
 
El alumno pasa si su calificación es mayor a 60.
 
### Instrucciones
 
1. Hacer el pseudocódigo del programa.
2. Hacer una lista de las variables necesarias.
3. Indicar el tipo de dato de cada variable.
4. Hacer una lista de las funciones que se podrían crear.
5. Opcional: implementar la solución en cualquier lenguaje de programación.
6. Pseudo código

INICIO

    Leer cantidad de alumnos

    PARA cada alumno
        Leer nombre del alumno
        Leer cantidad de exámenes

        PARA cada examen
            Leer calificación
            suma + calificación

        promedio suma / cantidad de exámenes

        SI promedio > 60 ENTONCES
            resultado “APROBADO"
        SI NO
            resultado "NO APROBADO"

        Mostrar nombre, promedio y resultado

FIN


VARIABLES 
Variable	Tipo de dato 
cantidadAlumnos	Entero
nombre	String
cantidadExamenes	Entero
calificacion	Decimal 
suma	Decimal
promedio	Decimal
resultado	String

#FUNCIONES

calcularPromedio 

* Entrada: calificaciones y cantidad de exámenes
* Proceso: sumar las calificaciones y dividir entre la cantidad de exámenes
* Salida: promedio final

determinarResultado

* Entrada: promedio final
* Proceso: comprobar si el promedio es mayor a 60
* Salida: “Aprobado” o “No aprovado"
* mostrarResultado

* Entrada: nombre, promedio y resultado
* Proceso: datos del alumno
* Salida: nombre, promedio y si aprobó o no
