# Geometic lib
This project is a set of functions to calculate area and perimeter of simple shapes

(Written on python 3.11) 

**Table of contents**
- [Geometic lib](#geometic-lib)
  - [сircle.py](#сirclepy)
  - [rectangle.py](#rectanglepy)
  - [square.py](#squarepy)
  - [triangle.py](#trianglepy)
  - [History of changes](#history-of-changes)
  
## сircle.py
```
area(r):
    Returns area of a circle with radius r
    Arguments:
        r (int or float) - radius of a circle

perimeter(r):
    Returns perimeter of a circle with radius r
    Arguments:
        r (int or float) - radius of a circle
```

**Formulas**
- Circle area: πR²
- Circle perimeter: 2πR

**Usage examples**
```python
area(23) # 1661.9025137490005
area(1) # 3.141592653589793
area(4.5) # 63.61725123519331
perimeter(12) # 75.39822368615503
perimeter(2.7) # 16.964600329384883
perimeter(1024) # 6433.981754551896
```

## rectangle.py
```
area(a, b):
    Returns area of a rectangle with sides a and b
    Arguments:
        a (int) - length of side
        b (int) - length of side adjacent to a
    
perimeter(a, b):
    Returns perimetr of a rectangle with sides a and b
    Arguments:
        a (int) - length of side
        b (int) - length of side adjacent to a
```

**Formulas**
- Rectangle area: a * b
- Rectangle perimeter: 2a + 2b

**Usage examples**
```python
area(12, 2) # 24
area(123, 4) # 492
area(1.2, 2.5) # 3.0
perimeter(34, 12) # 92
perimeter(22, 2.1) # 48.2
perimeter(45, 6.0) # 102.0
```


## square.py
```
area(a):
    Returns area of a square with side a
    Arguments:
        a (int or float) - length of side
    
perimeter(a):
    Returns perimeter of a square with side a
    Arguments:
        a (int or float) - length of side
```

**Formulas**
- square area: a * a
- square perimeter: 4a

**Usage examples**
```python
area(3.0) # 9
area(1.5) # 2.25
area(11.0) # 121
perimeter(1) # 4
perimeter(50) # 200
perimeter(11.5) # 46
```


## triangle.py
```
area(a, h):
    Returns area of a triangle from its side and height to this side
    Arguments:
        a (int or float) - length of side
        h (int or float) - length of a height to this side

perimeter(a, b, c): 
    Returns perimeter of a triangle from its sides
    Arguments:
        a (int or float) - length of side 1
        b (int or float) - length of side 2
        c (int or float) - length of side 3
```

**Formulas**
- triangle area: a * h
- triangle perimeter: a + b + c

**Usage examples**
```python
area(1, 4) # 2
area(12, 4.21) # 25.26
area(3.14, 2.7) # 4.239
perimeter(1, 12, 3) # 16
perimeter(11, 12, 4.5) # 27.5
perimeter(12, 13, 15) # 40
```

## History of changes

8ba9aeb : Circle and square added

d078c8d : Docs folder added

4b48c44 : Add(rectangle.py)

dd73444 : Add(triangle.py) and fixed rectangle perimeter func

bbcc121 : Docs(rectangle.py, circle.py, square.py, triangle.py): documented all functions