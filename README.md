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

```

## **Cuarto Ejercicio**

```python

```

## **Quinto Ejercicio**

```python

```

## **Sexto Ejercicio**

```python
 
```

## **Septimo Ejercicio**

```python

```
