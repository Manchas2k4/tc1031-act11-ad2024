# Saltadores alegres

Una secuencia de n > 0 enteros se denomina saltador alegre si los valores absolutos de la diferencia entre elementos sucesivos toman todos los valores de 1 a n − 1. Por ejemplo,
```
1 4 2 3
```
es un saltador alegre, porque las diferencias absolutas son 3, 2 y 1 respectivamente. La definición implica que cualquier secuencia de un solo entero es un saltador alegre. Debe escribir un programa para determinar si cada una de varias secuencias es o no un saltador alegre.

## Entrada
Cada línea de entrada contiene un entero n ≤ 3000 seguido de n enteros que representan la secuencia.

## Salida
Para cada línea de entrada, genere una línea de salida que diga ```Jolly``` o ```Not jolly```.

## Entrada de muestra
```
4 1 4 2 3
5 1 4 2 -1 6
```

## Salida de muestra
```
Jolly
Not jolly
```

[Fuente](https://onlinejudge.org/external/100/10038.pdf)