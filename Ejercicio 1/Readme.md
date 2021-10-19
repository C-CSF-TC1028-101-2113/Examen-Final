# Examen Parte Practica

Modifica el siguiente código:

```python
def main():
  #escribe tu código abajo de esta línea

if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario, el programa la va a ignorar al ejecutarse.

Diseña e implementa un programa que primero lea la cantidad de elementos que el usuario va a ingresar, después acepté cada uno de los elementos que ingrese el usuario. Estos elementos representaran las calificaciones obtenidas por un alumno (Numeros enteros comprendidos entre 0 y 10). 

A continuación el programa debe mostrar todas las calificaciones, el promedio final del alumno, la calificacion más alta que ha sacado y la mas baja.

Las calificaciones las introduce el usuario una por una y se iran almacenando en una lista. Posteriormente se analizará la lista para determinar lo que el programa solicita.

## Entrada
Un número entero que representa la cantidad de valores que tiene la lista, asi como cada uno de los valores de la lista.

## Salida
Se despliega la lista completa de calificaciones.
Se muestra el promedio final obtenido por el alumno en un renglon aparte.
Se muestra la calificacion maxima y minima obtenida por el alumno en un renglon aparte, usando el siguiente formato:
```
Calificación mayor: XX Calificación menor: XX
```

## Ejemplo de ejecución del programa
### Entrada
```
>>> 5
>>> 8
>>> 9
>>> 10
>>> 6
>>> 7
```
### Salida
```
[8, 9, 10, 6, 7]
Promedio: 8
Calificación mayor: 10 Calificación menor: 6
```
### Entrada
```
>>> 0
```
### Salida
```
[]
Promedio: 0
Calificación mayor: 0 Calificación menor: 0
````
