# Examen Parte Practica

Modifica el siguiente código:

```python
def main():
  #escribe tu código abajo de esta línea

if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario, el programa la va a ignorar al ejecutarse.

Diseña e implementa un programa que lea por teclado las calificaciones obtenidas por un alumno (comprendidas entre 0 y 10). A continuación el programa debe mostrar todas las calificaciones, el promedio final del alumno, la calificacion más alta que ha sacado y la mas baja.

Los valores los introduce el usuario uno por uno, se van almacenando en una lista y posteriormente se analizará la lista para determinar lo que el programa solicita.

## Entrada
Cero o más valores enteros, uno en cada renglón. Finaliza la captura con un *.

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
>>> 8
>>> 9
>>> 10
>>> 6
>>> 7
>>> *
```
### Salida
```
[8, 9, 10, 6, 7]
Promedio: 8
Calificación mayor: 10 Calificación menor: 6
```
### Entrada
```
>>> *
```
### Salida
```
[]
Promedio: 0
Calificación mayor: 0 Calificación menor: 0
````
