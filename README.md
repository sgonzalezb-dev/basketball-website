Tarea operadores

Operadores de asignación: Son símbolos usados en programación para asignar valores a una variable o modificar su valor actual.
Operador básico de asignación: =, asigna un valor a una variable.
Operador de asignación compuestos: Estos operadores combinan una operación matemática+asignación:

1.+=, suma y asigna. Ej: x+= 5
Si x=10, entonces: x+=5, x= 10+5 = 15

2.-=, resta y asigna. Ej: x-=3
Si x=10, entonces: x-=3, x= 10-3 = 7

3. *=, multiplica y asigna. Ej: x*= 2
Si x=10, entonces x*= 2, x= 10*2 = 20

4. /=, divide y asigna. Ej: x/=2
Si x=10, entonces x/=2, x=10/2 = 5

5. %=, móduo y asigna. Ej: x%=2
Si x= 10, entonces x%= 2, x= 10%2 = 0

6. **=, potencia y asigna. Ej: x**=3
Si x=10, entonces x**=3, x= 10**3 = 30

2. Los operadores de comparación (o relacionales) se usan para comparar dos valores y siempre devuelven un resultado booleano:

true (verdadero)
false (falso)

| Operador | Significado                   | Ejemplo     | Resultado |
| -------- | ----------------------------- | ----------- | --------- |
| `==`     | Igual (solo valor)            | `5 == "5"`  | `true`    |
| `===`    | Igual estricto (valor y tipo) | `5 === "5"` | `false`   |
| `!=`     | Diferente                     | `5 != 3`    | `true`    |
| `!==`    | Diferente estricto            | `5 !== "5"` | `true`    |
| `>`      | Mayor que                     | `10 > 3`    | `true`    |
| `<`      | Menor que                     | `4 < 2`     | `false`   |
| `>=`     | Mayor o igual                 | `5 >= 5`    | `true`    |
| `<=`     | Menor o igual                 | `3 <= 7`    | `true`    |

3.Los operadores lógicos se usan para combinar condiciones o invertir resultados en programación.
Siempre trabajan con valores verdadero (true) o falso (false).

| Operador | Nombre   | Significado                                |        |                                           |
| -------- | -------- | ------------------------------------------ | ------ | ----------------------------------------- |
| `&&`     | AND (Y)  | Todas las condiciones deben ser verdaderas |        |                                           |
| `||`     |  OR (O)   | OR (O) | Al menos una condición debe ser verdadera |
| `!`      | NOT (NO) | Invierte el resultado                      |        |                                           |


4. Los operadores de string (cadenas de texto) se usan para unir o trabajar con textos.
1. Operador de concatenación (+)

Sirve para unir textos.
let nombre = "Juan";
let saludo = "Hola " + nombre;

console.log(saludo);
Hola Juan

2. Operador de asignación con concatenación (+=)

Une texto y además lo guarda en la misma variable.

let mensaje = "Hola";
mensaje += " mundo";

console.log(mensaje);
Hola mundo

3. Concatenar texto con números

JavaScript convierte el número en texto automáticamente.

let edad = 18;
let texto = "Tengo " + edad + " años";
Tengo 18 años


5. El operador ternario es una forma corta de escribir un if...else en una sola línea.
Se llama ternario porque tiene tres partes.

condicion ? valor_si_es_true : valor_si_es_false;
Cómo se lee

 Si la condición se cumple, usa el primer valor.
 Si no se cumple, usa el segundo.
 let edad = 18;

let mensaje = edad >= 18 ? "Mayor de edad" : "Menor de edad";

