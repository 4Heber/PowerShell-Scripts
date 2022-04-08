# PowerShell-Scripts

### Analizar y documentar los siguientes scripts de Powershell

> ![image](https://user-images.githubusercontent.com/77643882/162392664-6d403fd0-8d4f-4b43-9962-4affd328d094.png)
>
> Se declara la variable `$number` y se inicializa a 1. 
> Mediante el cmdlet `Write-Host` se imprime por pantalla el String indicado entre comillas dobles concatenando la variable con su valor actual en 1.
> Se cambia el valor de la varaible incrementando en 1 y se repite el proceso para imprimir la información por pantalla de forma consecutiva.

> ![image](https://user-images.githubusercontent.com/77643882/162420693-120d5f4f-f9b0-4499-979d-0275ecee7b42.png)
>
> El script cuenta con una série de bucles, el primero es un bucle for:\
> Se declara previamente una variable `$repeat` de tipo `integer` y se inicializa a 5.\
> En la estructura del bucle está la variable `$counter` inicializada a 0 (contador), las variables a evualuar (condición) `$counter -lt $repeat` mientras `$counter` sea menor que `$repeat` ejecutará las instrucciones del bucle y al finalizar una iteración del bucle se incrementa la variable `$counter` en 1 (incremento).\
> Por cada ejecución de las instrucciones del bucle, 5 en este caso, se imprimirá por pantalla el mensaje "hello".
>  
> El segundo bucle while:
> Solo cuenta en su estructura con las variables a evualuar (condición), se definen previamente el límite en la variable `$repeat` en 5 y el contador en la variable `$counter` a 0, el incremento del contador se realiza dentro de la ejecución del bloque de código del bucle.
>
> El tercer bucle do while:
> Siendo una variante del bucle while, este ejecuta primero el bloque de código comprendido en las llaves de `do{}` y después evalua la comparación para iterar o no el bloque de código, se definen previamente el límite en la variable `$repeat` en 5 y el contador en la variable `$counter` a 0, el incremento del contador se realiza dentro de la ejecución del bloque de código del `do{}`.
>
> El cuarto bucle foreach:
> Declara y almacena en la variable `$stringOfCharacters` un String.\
> En la estructura del bucle se declara la variable `$character` que contendrá cada elemento de `$stringOfCharacters.ToCharArray()` un listado de cada carácter que contiene el string almacenado en la variable `$stringOfCharacter`, imprimiendo así la variable `$character` que contendrá cada carácter individual del string en cada iteración.

> ![image](https://user-images.githubusercontent.com/77643882/162433411-9cd869c8-ea79-4833-9966-a80aa6b07d7d.png)
>  
> El primer condicional evalua mediante el operador `-eq` igualdad, si los dos valore numéricos son iguales true o diferentes false.\
> Si la condición es true, se ejecuta el codigo dentro de las llaves.
>
> El segundo condicionar if sigue el mismo patrón, donde los valores a evaluar son Strings, si ambos Strings son iguales `-eq` se imprimirá por consola el texto `Both strings are equal to each other`.
>
> ![image](https://user-images.githubusercontent.com/77643882/162497999-92aad69d-663a-4b07-8d49-c7051e27694e.png)
>
> El primer condicional cuenta con dos variables previamente declaradas `$x` con valor 10 y `$y` con valor 10, como el operador es de igualdad `-eq` el código dentro de las llaves del `if` se ejecutará, imprimiendo por consola el mensaje `the x and y variables are equal to each other` y no se ejecutará el bloque del `else{}`.
>
> El segundo condicional tiene en su condición una variable previamente declarada `$yourName` con el valor de un string "Ian" y el mismo string que fue almacenado en la varible "Ian" al contar con el operador de igualdad `-eq` se ejecutará el código dentro del if imprimiendo por consola el mensaje `Hey my name is Ian too!` ignorando el bloque `else{}` que contenia el mensaje `Hi $yourName, nice to meet you!` concatenando la variable en el texto.






































