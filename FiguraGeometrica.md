Descripción


Clases:

    FiguraGeométrica: Clase padre que define las funciones abstractas calcular_area y calcular_perimetro.
    Rectángulo: Hereda de FiguraGeométrica e implementa las funciones para calcular el área y perímetro de un rectángulo.
    Triángulo: Hereda de FiguraGeométrica e implementa las funciones para calcular el área y perímetro de un triángulo rectángulo.
    Círculo: Hereda de FiguraGeométrica e implementa las funciones para calcular el área y perímetro de un círculo.


Documentación de las clases
FiguraGeométrica

    Métodos:
        calcular_area(self): Función abstracta que debe ser implementada por las clases hijas para calcular el área de la figura geométrica.
        calcular_perimetro(self): Función abstracta que debe ser implementada por las clases hijas para calcular el perímetro de la figura geométrica.

Rectángulo

    Atributos:
        base: La base del rectángulo.
        altura: La altura del rectángulo.
    Métodos:
        calcular_area(self): Calcula el área del rectángulo como base * altura.
        calcular_perimetro(self): Calcula el perímetro del rectángulo como 2 * (base + altura).


Triángulo

    Atributos:
        base: La base del triángulo.
        altura: La altura del triángulo.
    Métodos:
        calcular_area(self): Calcula el área del triángulo como 0.5 * base * altura.
        calcular_perimetro(self): Calcula el perímetro del triángulo rectángulo como base + altura + lado, donde lado es la hipotenusa calculada con la fórmula de Pitágoras.


Círculo

    Atributos:
        radio: El radio del círculo.
    Métodos:
        calcular_area(self): Calcula el área del círculo como pi * radio ** 2.
        calcular_perimetro(self): Calcula el perímetro del círculo como 2 * pi * radio.

Importaciones

El código importa las siguientes librerías:

    math: Librería que proporciona funciones matemáticas como la raíz cuadrada y el valor de pi.



# Nota
Con toda esta documentacion podras crear un un primer ejercicio.

* reto # 1: Hacer este ejercicio con programacion orientada a objetos
* reto # 2: Hacer este ejercicios con variables introducidas por consola
* reto # 3: hacer una clase tipada para cada variable y esta darle el valor


Guía 1: 

POO
#
=> from archivoPadre import funcion o Clase 

Guía 2:
#
base = input("Introduce la base del rectángulo: ") 

altura = input("Introduce la altura del rectángulo: ")

Guía 3:

class Valore:
    
    base:int

    altura:int
