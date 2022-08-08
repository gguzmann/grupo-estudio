# Introduccion Javascript 

## Es un lenguaje multiproposito utilizado principalmente en la web.
.
# Variables

Una variable es un espacio para almacenar, recuperar o modificar datos, en la memoria de un ordenador. En Javascript, una variable se define con la sintaxis:

    nombre_de_la_variable = valor_de_la_variable


 **Valores primitivos:**

    Boolean — verdadero o falso

    Null — sin valor

    Undefined — una variable declarada pero que no se le ha dado un valor
    
    Number — enteros, flotantes, etc.

    String — una matriz de caracteres, es decir, palabras

    Symbol — un valor único que no es igual a ningún otro valor(+ - * /)

# Funciones 

Una funcion es un conjunto de instrucciones para realizar una tarea y tiene como objetivo reutilizar codigo. Puede tomar alguna entrada y devolver una salida. Una funcion se declara con la palabra clave ***function***, de la siguiente manera:

    function(param1, param2) {}

- El nombre de la función.
- Una lista de parámetros de la función, entre paréntesis y separados por comas.
- Las declaraciones de JavaScript que definen la función, encerradas entre llaves,    { ... }.
- Puede retornar algo con *return*.

Ejemplo de una funcion:

    function sumar(num1, num2) {
        let resultado = num1 + num2;
        return resultado;
    }

    console.log(sumar(1,3)) // 4

# Condicionales

Evalua la expresion logica entre parentesis y ejecuta el primer bloque de código si es verdadero(True); En caso contrario(False), ejecuta el bloque de codigo despues de else:

    let edad = 25 
    if(edad > 18){
        console.log('eres mayor de edad');
    }else{
        console.log('eres menor de edad');
    }

Pueden agregarse else if en caso de tener mas opciones:

    let edad = 25 
    if(edad > 18){
        console.log('eres mayor de edad');
    }else if (edad == 18){
        console.log('Tienes 18 años');
    }else{
        console.log('eres menor de edad');
    }


## Operadores Logicos

    && : and
    || : or 

## Operadores de comparacion:

    == : es igual a
    != : es distinto a
    < : es menor a
    > : es mayor a
    >= : mayor o igual que
    <= : menor o igual que


# Ejercicios 

> Funcion que sume dos numeros

> Funcion que pregunte tu edad y se imprima en consola.

> Funcion que haga convencion del dolar(850). ingresar una cantidad de dolar y imprimir la convencion a peso chileno.
 
> Funcion que reciba un numero. si es par imprimir 'par', si es impar imprimir 'impar' y si es 0 imprimir 'es 0'.

> Funcion que pregunte el 'nombre' del usuario y 'edad' en la consola, después de que el usuario lo introduzca muestre por pantalla la cadena 
 
    ¡Hola 'nombre'!, tu edad es 'edad'

> Funcion que pida una cantidad de segundos y luego que escriba cuántos minutos y segundos son. Como en el siguiente ejemplo:

    >>>Escriba una cantidad de segundos: 120
    120 segundos son 2 minutos y 0 segundos

> Escriba un programa que pida dos números y que conteste cuál es el menor y cuál el mayor o que escriba que son iguales.. Como en el siguiente ejemplo:

    >>>Escriba un numero: 2
    >>>Escriba otro numero: 9
    el numero 2 es menor que 9

    >>>Escriba un numero: 5
    >>>Escriba otro numero: 5
    Los numeros son iguales