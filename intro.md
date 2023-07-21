# FDP_java_EIA

Notas y talleres resueltos de la materia de fundamentos de programación

## Taller#1 (Conceptos básicos)

- ¿Qué es una algoritmo?
  Es una conjunto de pasos ordenados y en secuencia, quiere decir, un conjunto de instrucciones
  específicas con la función de cumplir determinada tarea; en el caso de la programación los algoritmos se caracterizan por tener elementos de entrada, un proceso a partir de esos datos y una salida o resultado de los mismos (input, output)
- ¿Para qué sirven los algoritmos?
  Un algoritmo tiene ua nmensa cantidad de usos, algunos de ellos son: La resolución de problemas, automatización de tareas, toma de decisiones y optimización.
- ¿Cuantos algoritmos pueden existir para solucionar un mismo problema?
  Infintos, sin embargo habrán algunos que lo resuelvan de forma mas óptima que otros
- ¿Que es una expresión?
  Representa cualquier línea de código que implemente constantes, variables y comandos para generar un resultado
- ¿Que tipos de expresiones hay?
  Existe variables de asignación (nombran o dan valores), aritméticas (operaciones matemáticas) y lógicas (De caracter booleano)
- ¿Cuales son las diferencias entre cada expresión?
  Cada expresión cumple con una finalidad específica, ya sea para denitar datos , usar datos e indentificar datos con base en la necesidad dada
- ¿En que casos de deben usar variables y en que otros constantes?
  Cómo sus nombres lo indicasn, usarás una variable en el momentos en que los valores asignados puedan o necesiten variar, en cambio las constantes son aquellas que no cambiarán y tendrán un valor fijo dentro del código. Un ejemplo de ambas expresiones se da en un código para calular el área de un circulo, usarás una varibale para asignar el radio, puesto que puede variar según el tamaño del circulo, y usarás una constante para pi, debido a que este número siempre será el mismo para calcular un área independiente del radio
- ¿Qué se debe hacer antes de poder utilizar una variable o constante?
  Se deben de declarar según el tipo de expresión que sean, así mismo cómo el uso que se le dará.

  Ejemplo

  ```{java}
   double GRAVITY = 9.8;
  ```

En este caso particular se declaró una constante (final) de caracter decimal (double) llamada GRAVITY y con un valor de 9.8

- ¿Cómo se llama el estándar que se utiliza para nombrar las variables?
  El estandar que se utiliza para nombrar las variables se llama nomenclaruta. (Nomenclature)
- Explique cómo se deben llamar las variables.
  Hay diferentes formas que se pueden nombrar las variables como por ejemplo se podría nombrar usando CamelCase que consiste en nombrar la variable con las primeras letras en mayúscula

  Ex:

  ```{java}
  String MyName = "Juan";
  ```

  También existe la nomenclatura lowerCamelCase, en donde la primera letra empieza en minúscula y las siguentes en mayúsculas

  Ex: Java code

  ```{java}
  String myName = "Juan";
  ```

  También existe otro tipo de nomenclatura llamado snake_case y consiste en separar las palabras usando el underscore key ( )

  ex: python code

  ```{python}
  my_name = 'Juan'
  ```

  Este tipo de nomenclatura se utiliza en lenguajes como Python y C

- Explique cómo se deben llamar las constantes
  Las constantes se deben de llamar usando siempre mayúscula
  ex:

```{java}
   int PI = 3.14;

   int GRAVITY = 9.8;
```

También se nombrar usando snake_case
ex:

```{java}
int ID_USER = 11111;
```

```{java}
String COLOMBIA_ADDRESS = "CR 18 Sur Guatape";
```
