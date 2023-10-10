# Обшая информация
Данный репозиторий содержит 4 файла на языке Python. В каждом файле содержатся 2 функции для 4 геометрических фигур - круг, прямоугольник, квадрат и треугольник

***
# Файл circle.py
```
def area(r):\
    return math.pi * r * r

def perimeter(r):\
    return 2 * math.pi * r  
```    
В функцию area(r) мы передаем значение r - радиус круга -> получаем его площадь  
В функцию perimetr(r) мы передаем значение r - радиус круга -> получаем длину его окружности

Пример использования:
```
def area(r):\
    return math.pi * r * r

def perimeter(r):\
    return 2 * math.pi * r

r = 2
s = area(r) = pi * r * r
p = perimetr(r) = 2 * pi * r
```
***
# Файл rectangle.py
```
def area(a, b):
    return a * b

def perimetr(a, b):
    return (a + b) * 2
```    
В функцию area(a, b) мы передаем значение первой стороны a и второй стороны b -> получаем площадь прямоугольника
В функцию perimetr(a, b) мы передаем значение первой стороны a и второй стороны b -> получаем периметр прямоугольника

Пример использования:
```
def area(a, b):
    return a * b

def perimeter(a, b):
    return (a + b) * 2

a = 2
b = 3
s = area(a, b) = a * b = 6
p = perimetr(a, b) = (a + b) * 2 = 10
```
# Файл square.py
```
def area(a):
    return a * a

def perimetr(a):
    return 4 * a
```    
В функцию area(a) мы передаем значение стороны a -> получаем площадь квадрата
В функцию perimetr(a) мы передаем значение стороны a -> получаем периметр квадрата

Пример использования:
```
def area(a):
    return a * a

def perimeter(a, b):
    return 4 * a

a = 2
s = area(a) = a * a = 4
p = perimetr(a) = 4 * a = 8
```
# Файл triangle.py
```
def area(a, h):
    return a * h / 2

def perimetr(a, b, c):
    return a + b + c
```    
В функцию area(a, h) мы передаем значение стороны a и высоты h, которую опустили на сторону a -> получаем площадь треугольника
В функцию perimetr(a, b, c) мы передаем значение стороны a, стороны b и стороны c -> получаем периметр треугольника

Пример использования:
```
def area(a, h):
    return (a * h) / 2

def perimetr(a, b, c):
    return a + b + c

a = 2
b = 3
c = 4
h = 5
s = area(a, h) = (a * h) / 2 = (2 * 5) / 2 = 5
p = perimetr(a, b, c) = a + b + c = 9
```
|хэш|дата|содержание|автор|
|---|---|---|---|
|792767c|10.10.2023, 17:33|Add comment to circle.py|Sergey|
|792767c|10.10.2023, 17:35|Add comment to rectangle.py|Sergey|
|792767c|10.10.2023, 17:37|Add comment to square.py|Sergey|
|792767c|10.10.2023, 17:41|Add comment to triangle.py|Sergey|
