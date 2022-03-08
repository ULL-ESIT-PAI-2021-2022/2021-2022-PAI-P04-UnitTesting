# Práctica 4. Unit Testing en Javascript con Jest
### Factor de ponderación: 5

### Objetivos
Los objetivos de esta práctica son:
* Ser capaz de desarrollar tests unitarios en Jest para sus programas Javascript
* Ser capaz de desarrollar programas simples en JavaScript en el entorno Linux de la VM de la asignatura usando
  Node.js

### Rúbrica de evaluacion del ejercicio
Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva)
que se tendrán en cuenta a la hora de evaluar esta práctica:
* Se valorará la realización de las diferentes tareas que se proponen
* El alumnado ha de ser capaz de desarrollar tests unitarios para sus programas utilizando Jest.
* El alumnado debe ser capaz de resolver problemas de la plataforma Exercism, subiendo sus soluciones a la misma.
* El alumnado ha de acreditar que es capaz de desarrollar y ejecutar programas simples de la plataforma Jutge
* Se comprobará que el código que el alumnado escribe se adhiere a las reglas de la Guía de Estilo de Google
  para Javascript
* El alumnado ha de acreditar que es capaz de editar ficheros de forma remota en su VM usando Visual Studio
  Code (VSC)

### Unit Testing con Jest
Para cada uno de los siguientes problemas de 
[Jutge](https://jutge.org/)
haga que la entrada de los programas se tome por línea de comandos.

Desarrolle tests unitarios en Jest para probar la corrección de cada una de las soluciones.
Aparte de los tests públicos de Jutge, incluya algunos tests adicionales para comprobar situaciones que
considere relevantes.

1. [P48107](https://jutge.org/problems/P48107) Integer division and remainder of two natural numbers
2. [P29973](https://jutge.org/problems/P29973) Triangle
3. [P90615](https://jutge.org/problems/P90615) Maximum of three integer numbers
4. [P70955](https://jutge.org/problems/P70955) How many seconds are they?
5. [P34279](https://jutge.org/problems/P34279) Add one Second.
6. [P51352](https://jutge.org/problems/P51352) Elementos.
7. [P51126](https://jutge.org/problems/P51126) Intervals (I)
8. [P33839](https://jutge.org/problems/P33839) Sum of Digits 
9. [P97969](https://jutge.org/problems/P97969) Counting a's (I)
10. [P80660](https://jutge.org/problems/P80660) The sequence of Collatz

1. [P11916](https://jutge.org/problems/P11916_en) Approximation of e
2. [P67268](https://jutge.org/problems/P67268_en) Reverse of sequences
3. [P50497](https://jutge.org/problems/P50497_en) Is Palindrome
4. [P76024](https://jutge.org/problems/P76024_en) Sum of fractions
5. [P17179](https://jutge.org/problems/P17179_en) Statistical measures




### Ejercicios de Exercism
Siga a continuación con el conocido problema
[Two Fer](https://exercism.org/tracks/javascript/exercises/two-fer)
(*Two for one*).
En este caso la función que hay que codificar es una
[arrow function](https://javascript.info/arrow-functions-basics):
```js
export const twoFer = () => {
  throw new Error('Remove this statement and implement this function');
};
```

La plantilla que proporciona Exercism para esta función, lanza un error utilizando el operador
[Throw](https://javascript.info/try-catch#throw-operator).
Esta primera versión puede ser útil para aprender cómo lanzar una excepción en un programa Javascript, que
sería la forma más adecuada de abortar su ejecución ante una situación de error.

[Collatz Conjecture](https://exercism.org/tracks/javascript/exercises/collatz-conjecture)
es otro ejercicio que no debiera costarle resolver puesto que ya lo ha resuelto en Jutge.

[Esta página](https://exercism.org/tracks/javascript/concepts) 
de Exercism muestra un posible itinerario de aprendizaje que podría Ud. seguir para ganar experiencia con
Javascript.
Los diferentes programas de la plataforma se van desbloqueando conforme va Ud. resolviendo problemas cada vez
más complejos.

Para cubrir los objetivos de esta práctica, resuelva al menos **5 problemas de la plataforma** aparte de los
anteriores y a partir de ese punto, desarrolle todos los ejercicios de Exercism que sea capaz.

## Ejercicios de Jutge
Desarrolle programas que solucionen los siguientes problemas:

1. [P11916](https://jutge.org/problems/P11916_en) Approximation of e
2. [P67268](https://jutge.org/problems/P67268_en) Reverse of sequences
3. [P50497](https://jutge.org/problems/P50497_en) Is Palindrome
4. [P76024](https://jutge.org/problems/P76024_en) Sum of fractions
5. [P17179](https://jutge.org/problems/P17179_en) Statistical measures

## Referencias
* [Exercism](https://exercism.io/)
* [JavaScript Fundamentals](https://javascript.info/first-steps)
* [PAI Code Examples](https://github.com/ULL-ESIT-PAI-2021-2022/PAI-class-code-examples/tree/master/src)
* [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
* [Jutge web site](https://jutge.org/)


### Prime Factors
Localice en el track de JavaScript de Exercism el problema 
[*Prime Factors*](https://exercism.io/my/solutions/fce10654772240b3b22955cd5aeb855a)
y descárguelo en su máquina virtual. 
Resuelva ese problema. 

La función que ha de escribir es una *arrow function* que tendría la siguiente *signature*:

```js
export const primeFactors = () => {
};
```
que tendrá como parámetro un número entero y ha de devolver un array que contenga todos los factores primos del número pasado como parámetro.

Estudie
[este tutorial](https://javascript.info/array)
para conocer los fundamentos necesarios para trabajar con arrays en JavaScript. 

Ejecute los tests que acompañan al problema para comprobar que todos pasan correctamente y cuando lo consiga, suba su solución a Exercism.

Una vez que suba su solución a la plataforma, revise la solución que hayan subido otros usuarios y compárelas
con la suya.

Una vez que su programa funcione en consola, consiga que funcione en una página web similar a la que se ha usado para el cálculo de Pi. 

### Strain
Localice en el track de JavaScript de Exercism el problema 
[*Strain*](https://exercism.io/my/solutions/03d029e7331642fd8a15501eb1ae64bf)
y descárguelo en su máquina virtual. 
Resuelva ese problema. 

Las funciones que ha de programar, *keep()* y *discard()* toman ambas dos parámetros, un array 
y una función booleana (un predicado) y devuelven un array que contiene (keep) o no (discard) 
los elementos del array de entrada para los que el predicado es cierto.

### Yacht
Localice en el track de JavaScript de Exercism el problema 
[*Yacht*](https://exercism.io/my/solutions/5f2e1e4332fd419abf2ea365b05b4e3b)
y descárguelo en su máquina virtual. Resuelva ese problema. 

Si analiza el programa que realiza los tests (`yacht.spec.js`) observará que la función *score()* ha de tener dos parámetros: 
un array con las puntuaciones de los lanzamientos de 5 dados y una cadena (string) con el nombre de la jugada y ha de devolver 
la puntuación correspondiente a esa jugada.
