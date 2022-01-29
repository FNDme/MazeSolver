# Maze Solver
Solucionador recursivo de laberintos

## Formato de entrada
Para ejecutar el solucionador estableceremos en un fichero el laberinto a resolver siguiendo el siguiente formato.

```
12 12
1 8 1 1 1 1 1 1 1 1 1 1
1 0 0 0 0 0 1 1 0 0 0 1
1 1 0 0 0 0 0 1 0 1 0 1
1 1 1 0 1 0 0 0 1 1 0 1
1 0 1 0 0 0 1 0 0 1 0 1
1 1 1 1 0 1 1 1 0 1 0 1
1 0 1 0 0 0 1 1 0 0 1 1
1 1 1 1 1 0 1 1 0 1 0 1
1 1 0 0 0 0 0 0 0 1 1 1
1 0 0 0 0 0 1 1 0 0 0 1
1 1 1 0 1 1 0 0 1 1 0 9
1 1 1 1 1 1 1 1 1 1 1 1
```
En la primera línea se establecen las dimensiones del laberinto.  
A partir de ahí, estableceremos el laberinto.  
  
1 - Muro  
2 - Camino  
8 - Entrada  
9 - Salida  

## Compilación
La compilación del programa se realiza a través de la herramienta 'make'
```
make
```

## Ejecución
La ejecución se realiza pasandole al programa el fichero con los datos del laberinto
```
./Maze < data_maze_1.txt
```

