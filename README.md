# Guia  1  NO SE COPIEN VAGOS

### **Alumno:** Juan Baader

### **Año:** 2024

### **Curso:** 4B TIC

### **Profesor/a** Ignacio Pardo

[Link a Github](https://github.com/juanpanpanyz/python)

<br>

## **Primer Ejercicio**

```python

# Teniendo en una variable el nombre de una persona, contar la longitud en caracterres del nombre y mostrarlo en pantalla
contador=0
for i in "Hola 4B":
  contador = contador + 1
print (contador)
```

## **Segundo Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    int num1 = 0; int num2 = 0; // variables de los numeros

    Console.WriteLine("Calculadora en c#"); // Textito xq pinto jaja

    Console.WriteLine("Ingresa un numero y apreta Enter"); // el usuario ingresa un numero
    num1 = Convert.ToInt32(Console.ReadLine()); // el programa guarda ese numero

    Console.WriteLine("Ingresa otro numero y apreta Enter"); // el usuario ingresa un numero
    num2 = Convert.ToInt32(Console.ReadLine()); // el programa guarda ese numero

    Console.WriteLine("Elegí una de las siguientes opciones:"); // el usuario elige
    Console.WriteLine("\ts - Suma"); // suma
    Console.WriteLine("\tr - Resta"); // resta
    Console.WriteLine("\tm - Multiplicacion"); // multiplica
    Console.WriteLine("\td - Division"); // divide
    Console.Write("¿Tu eleccion? "); // el usuario entra una de las iniciales de la operación que quiere hacer

    switch (Console.ReadLine()) // Eze canay nos lo enseño el año pasado jajsjaj
    {
        case "s":
            Console.WriteLine($"Tu resultado: {num1} + {num2} = " + (num1 + num2)); // el programa suma
            break;
        case "r":
            Console.WriteLine($"Tu resultado: {num1} - {num2} = " + (num1 - num2)); // el programa resta
            break;
        case "m":
            Console.WriteLine($"Tu resultado: {num1} * {num2} = " + (num1 * num2));  // el programa multiplica
            break;
        case "d":
            Console.WriteLine($"Tu resultado: {num1} / {num2} = " + (num1 / num2)); // el programa divide
            break;
    }
    Console.Write("Apreta cualquier tecla y tocar enter para detener el programa"); // el usuario cierra el programar
    Console.ReadKey();
  }
}
```

## **Tercer Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingrese su nombre"); // el usuario pone su nombre
    string nombre = Convert.ToString(Console.ReadLine ()); // el programa guarda el nombre del usuario
    Console.WriteLine ("Ingrese su edad"); // el usuario pone su edad
    int edad = Convert.ToInt32(Console.ReadLine ()); // el programa guarda la edad del usuario
    Console.WriteLine ("Hola " + nombre + ", usted tiene " + edad + " años"); // printea nombre y edad que el usuario ingreso
  }
}
```

## **Cuarto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
     Console.WriteLine ("Ingresar la nota de el primer trimestre"); // el usuario anota la nota del 1er trimestre
    int tri1 = Convert.ToInt32(Console.ReadLine()); // el programa guarda la nota del trimestre
    Console.WriteLine ("Ingresar la nota de el segundo trimestre"); // el usuario anota la nota del 2ndo trimestre
    int tri2 = Convert.ToInt32(Console.ReadLine()); // el programa guarda la nota del trimestre
    Console.WriteLine ("Ingresar la nota de el tercer trimestre"); // el usuario anota la nota del 3er trimestre
    int tri3 = Convert.ToInt32(Console.ReadLine()); // el programa guarda la nota del trimestre
    int promedio = (tri1 + tri2 + tri3) / 3; // esta variable permite que el programa de al usuario su promedio
    Console.WriteLine (promedio); // printea un promedio
  }
}
```

## **Quinto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingresar altura"); // el usuario entra la altura del triangulo
    int altura = Convert.ToInt32(Console.ReadLine()); // el programa guarda la altura
    Console.WriteLine ("Ingresar base"); // el usuario entra la base del triangulo
    int basesita = Convert.ToInt32(Console.ReadLine()); // el programa guarda la base del triangulo
    int superficie = basesita * altura / 2; // calcula la suuperficie mediante (base x altura)/2
    Console.WriteLine (superficie); // printea el resultado de la superficie
  }
}
```

## **Sexto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingresar precio del producto para recibir cuanto pagaria de IVA "); // el usuario ingrese el precio
    int precio = Convert.ToInt32(Console.ReadLine()); //el programa guarda el precio del producto
    int ivachoto = precio + precio / 100 * 21; // sabiendo que el iba es 21% al precio realizo esta cuenta
    Console.WriteLine (ivachoto); // printea el resultado del impuesto y el precio
  }
}   
```

## **Septimo Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingresar precio de la nafta"); // el usuario ingresa el precio de la nafta
    int nafta = Convert.ToInt32(Console.ReadLine()); // el programa  guarda el precio de la nafta
    Console.WriteLine ("Ingresar la distancia recorrida"); // el usuario ingresa la distancia recorrida
    int distancia = Convert.ToInt32(Console.ReadLine()); // el programa guarda la distancia recorrida
    int gastos = nafta * distancia / 10; // sabiendo que por cada 10 kilometros recorridos se gasta 1 litro de nafta hacemos esto
    Console.WriteLine (gastos); // printea el resultado de los gastos (en nafta)
  }
}
```
