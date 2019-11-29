## 1. Ejercicios con parámetros

1. 
Crear una función llamada mostrarNombreCompleto. 

Esta función recibe 2 parámetros: nombre y apellido. 

La función debe mostrar en consola el nombre completo de la persona, concatenando nombre y apellido

Por ejemplo: si los parámetros son 'Ada' y 'Lovelace', mostrar en consola 'Ada Lovelace'

2. 
Crear una funcion llamada sonIguales() que reciba dos parametros. 

La funcion debe mostrar en consola "true" si los parametros son iguales, y "false" si son diferentes. 

3. 
Crear una funcion llamada agregarNumero() que reciba dos parametros: un array y un numero.

La funcion debe agregar el numero recibido al array, y mostrar el array resultante en consola. 

4. 
Crear una funcion llamada comprobarPosicion() que reciba dos parametros: un array de strings y un string

La funcion debe revisar si el string esta incluido dentro del array, y mostrar en consola "true" o "false". 

5. 
Crear una función llamada calcularPromedio()

La función recibe un único parámetro, del tipo array, con números enteros

La funcion debe mostrar en consola el promedio entre todos los números que pertenecen al array 

## 2. Ejercicios con return 

1. 
Crear una función que se llame obtenerNombre y retorne tu nombre como string

Probarlo con la siguiente linea de codigo

```
console.log("Mi nombre es " + obtenerNombre());
```

2. 
En el mismo código, crear una función llamada obtenerSaludo, que retorne un valor string

Dentro de esta función obtener tu nombre utilizando la función obtenerNombre(), y guardarlo en una variable. 

Retornar un texto de la forma: ¡Hola, ${nombre}!, donde nombre tiene que ser el valor guardado en la variable de arriba.

Ejecutar la función obtenerSaludo y mostrar el resultado por consola.

```
console.log(obtenerSaludo());
```

3. 
Crear la funcion obtenerResto(a, b) que retorne el resto de dividir a y b. 

4. 
Crear la funcion esPar(num) que retorne true si el numero es par, y false si es impar. 

Dentro de esa funcion debe utilizarse lo retornado por la funcion obtenerResto creada en 2.3. 

5. 
Declarar la siguiente variable:
```
const listaDeNumeros = [ 43, 11, 18, 46, 44, 37, 42, 29, 9, 3, 37, 0, 40, 10, 38, 34, 25, 40, 4, 32 ];
```
Crear una funcion llamada encontrarPares() que recorre el array recibido por parametros

y retorna un nuevo array compuesto solo por los numeros impares. 

Para saber si un número es par debe utilizarse la funcion esPar() creada en 2.4. 

6. 
Crear la funcion exclamar() que recibe un parametro string y retorna ese mismo string con signos 

de exclamacion al principio y al final. 

7. 
Crear la funcion unirNombre() que recibe dos parametros (nombre y apellido), y debe retornarlos 

en un solo string, separados por un espacio

  // ('Ada', 'Lovelace') => 'Ada Lovelace'

8. 
Crear la funcion saludar() que reciba un nombre y un apellido. 

La funcion saludar() debe concatenar ambos parametros usando la funcion unirNombre()

Luego debe darle signos de exclamacion usando la funcion exclamar()

Y finalmente retornar el resultado. 

