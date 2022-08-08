# Arrays

Conjunto de datos, ordenados segun ingreso y separados por (,). 
Pueden contener cualquier tipo de datos = numero, string, array, boolean, object
Parte desde la posicion 0

    //index =           0      1   2   3...
    const matriz = [[6, 2, 3], 76, 56, 1, 4, 'a', 'b', 'c', true, false];


const arr = [1,2,3]

Para acceder a un elemento del array:

    arr[0] // devuelve 1

Para modificar elemento del array:

    arr[2] = 5 // [1,2,5]

-- PUSH

Agrega un nuevo elemento al final del array

    arr.push(4); // [1, 2, 3 ,4];

-- POP

Elimina y retorna el ultimo elemento del array

    let delete = arr.pop(); // delete=3 // arr=[1,2]

-- SHIFT

Elimina y retorna primer elemento del array

    let delete = arr.shift() // delete = 1 // arr = [1, 2, 3]

-- UNSHIFT

Agrega un nuevo elemento al principio del array

    arr.unshift(0) //[0, 1, 2, 3 ,4];


# Ciclos

Los bucles ofrecen una forma rápida y sencilla de hacer algo repetidamente. Hay muchos diferentes tipos de bucles, pero esencialmente, todos hacen lo mismo: repiten una acción varias veces.

## FOR

Ejemplo 1:

    for (let index = 0; index < 10; index++) {
        console.log(index)
    }
    // 0,1,2,3,4,5,6,7,8,9

Ejemplo 2:

    cost arr = ['oso', 'gato', 'conejo']
     for (let index = 0; index < arr.length; index++) {
        console.log(arr[index])
    }
    // 'oso'; 'gato'; 'conejo';
    
## WHILE

La condición puede ser cualquier valor o expresión booleana. El cuerpo del ciclo se va a ejecutar mientras que la condición se cumpla. 

    while (<condicion>) {
        ...
    }

ejemplo:

    i = 0
    while(i < 10) {
        console.log(i)
        i++
    } 
    // 0,1,2,3,4,5,6,7,8,9

# EJERCICIOS

Ciclos

    1. Con ciclo for imprimir en console los numeros del 0 al 9.
    2. Con ciclo for imprimir en console los numeros del 3 al 15.
    3. Con ciclo for imprimir en console los numeros del 9 al 0.
    4. Con ciclo for imprimir numeros pares de los numeros del 1 al 99

Array + Ciclos

    1. Con ciclo for imprimir la suma del siguiente array [2, 4, 1, 7]
    2. Con ciclo for copiar var arr = [2, 3, 5] a var arr2 = [] 
    3. Escribe una función que devuelve una matriz con todos los números del 1 al 255
    4. Buscar el numero más pequeño de un array
    5. Escribe una función que entregue la suma de todos los números pares del 1 al 1000 - Puedes usar un operador de módulo para este ejercicio.
    6. Escribe una función que devuelva la suma de todos los números impares entre 1 y 4000

Desafios:

    1. Escribe una funcion que realice lo mismo que push sin ocupar push. Es decir que pida como parametro un array y un nuevo elemento. Debe retorar un nuevo array con el elemento incluido. ejemplo:

    >>> array inicial = [1,2,3,4]
    >>> nuevo elemento = 6
    >>> nuevo array = [1,2,3,4,6]

    1. Funcion que pida un array y el numero de indice. Debe devolver un nuevo array sin el elemento en la posición del indice indicado. Ejemplo:

    >>> array inicial = [1,2,3,4]
    >>> nuevo elemento = 2
    >>> nuevo array = [1,2,4,6]


    2. Una funcion que pida como parametro un array y un elemento que contenga el array. Debe devolver cuantas veces se repite el elemento en el array. Sin ocupar .filter. Ejemplo:

    >>> array inicial = [6, 3, 1, 7 , 1, 6, 8, 2, 1]
    >>> numero = 1
    >>> el elemento 1 se repite 3 veces

    1. Funcion que pida como parametro un array numerico y un numero. Debe devolver un nuevo array igual al ingresado pero con cada elemento multiplicado por el numero indicado. No ocupar .map. Ejemplo:

    >> array inicial = [2,5,7,3,8]
    >> numero = 2
    >> nuevo array = [4, 10, 14, 6, 16]
   