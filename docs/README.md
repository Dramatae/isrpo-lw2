# Общее описание

В файлах сожержаться функции для вычисления <ins>площадей</ins> и <ins>периметров</ins> геометрических фигур.

- [Круг](https://github.com/Dramatae/isrpo-lw2/blob/main/circle.py) - S = πr<sup>2</sup>, P = 2πr
- [Квадрат](https://github.com/Dramatae/isrpo-lw2/blob/main/square.py) - S = a<sup>2</sup>, P = 4a
- [Треугольник](https://github.com/Dramatae/isrpo-lw2/blob/main/triangle.py) - S = ah/2, P = a+b+c

# Описание каждой функции с примерами вызова

## Circle.py

import math

def area(r):
    ```
    Возвращает площадь окружности по её радиусу.

    	Параметры:
        	r (int/float): радиус окружности

    	Возвращаемое значение:
        	area (float): площадь окружности (π * r²)

    	Пример вызова:
        	area(12) = 452.3893421169302
    ```
    return math.pi * r * r

def perimeter(r):
    ```
    Возвращает длину окружности по её радиусу.

	Параметры:
        	r (int/float): радиус окружности

    	Возвращаемое значение:
        	perimeter (float): длина окружности (2 * π * r)

    	Пример вызова:
        	perimeter(12) = 75.39822368615503
    ```
    return 2 * math.pi * r
