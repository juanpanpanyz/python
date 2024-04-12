# Guia  de Programación de Python  NO SE COPIEN VAGOS

### **Alumno:** Juan Baader

### **Año:** 2024

### **Curso:** 4B TIC

### **Profesor/a** Ignacio Pardo

[Link a Github](https://github.com/juanpanpanyz/python)

<br>

## **Tarea**

```python
# A) Dada una lista lis=[1,2,3,4,5] crea una nueva lista por cada elemento x de lis tenga x*x en la lista nueva
from typing import List
lis1: List[List[int]]=[[1,2,3,4,5]]
b: List[List[int]] = lis1
for j in range(len(b)):
  if j % 2 == 0:
    print(j)
```

## **Primer Ejercicio**

```python

# Escribir una función que reciba una lista de números y devuelva una lista con los números pares.
from typing import List

lista_original = [1, 2, 3, 4, 5]
pares = []
for num in lista_original:
    if num % 2 == 0:
        pares.append(num)
print("Números pares:", pares)
```

## **Segundo Ejercicio**

```python
# Escribir una función que tome una lista de números y devuelva el numero mas grande. Si la lista está vacía, devolver 0.
from typing import List

lista_original = [1, 2, 3, 4, 5]
if not lista_original:
    mas_grande = 0
else:
    mas_grande = max(lista_original)
print("El número más grande es:", mas_grande)
```

## **Tercer Ejercicio**

```python
# Escribir una función que tome una lista de números y devuelva el numero mas chico. Si la lista está vacía, devolver 0.
from typing import List

lista_original = [1, 2, 3, 4, 5]
if not lista_original:
    mas_chico = 0
else:
    mas_chico = min(lista_original)
print("El número más chico es:", mas_chico)
```

## **Cuarto Ejercicio**

```python
# Escribir una función que tome una lista de números y devuelva el promedio de los números. Si la lista está vacía, devolver 0.
import numpy as np

from typing import List

lista_original = [1, 2, 3, 4, 5]
if not lista_original:
    promedio = 0
else:
    promedio = np.mean(lista_original)
print("El número más chico es:", promedio)
```

## **Quinto Ejercicio**

```python
# Escribir una función que tome una lista de números y devuelva el mayor número que no sea divisible por ningún otro número de la lista. Si la lista está vacía, devolver 0.
```

## **Sexto Ejercicio**

```python
# Escribir una función que tome una lista de listas de la forma [[1, 2, 3], [4, 5, 6], [7, 8, 9]] y devuelva una lista con los números de todas las listas: [1, 2, 3, 4, 5, 6, 7, 8, 9]. Si la lista está vacía, devolver una lista vacía. Bonus: Resolver con una comprensión de listas.
```

## **Septimo Ejercicio**

```python
# Escribir una función que tome una lista de listas de la forma [[1, 2, 3], [4, 5, 6], [7, 8, 9]] y devuelva una lista con el mayor numero de cada sublista: [3, 6, 9]. Bonus: Resolver con una comprensión de listas.
```
