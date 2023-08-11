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
- ¿Qué es un tipo de dato?
  son aquellos tipos de valores que puede tomar las varibales, así mismo que determinan la cantidad de memoria que usan dentro del       
  codigo. Dichos datos se dividen en dos categorías : Primitivos y de referencia.

  Primitivos: Representan valores individuales y están diseñados para ser eficientes. son:
    bytes: (8bits) almacena valores enteros
    short: (16 bits) valores enteros mayores
    int: (32 bits) almacena valores enteros
    long: 64 bits, almacena valores enteros más grandes que el int.
    float: 32 bits, almacena valores de punto flotante (números decimales) con aproximación.
    double: 64 bits, almacena valores de punto flotante con mayor precisión que el float.
    char: 16 bits, almacena un único carácter (Unicode)
    boolean: representa un valor booleano, que puede ser verdadero (true) o falso (false)
  
  Valores de referencia: Estos tipos de datos se utilizan para almacenar referencias a objetos en memoria, en lugar de almacenar         
  directamente los valores. Los tipos de datos de referencia incluyen:

  Clases: Las clases son definiciones de objetos y sus propiedades/métodos. Por ejemplo, 'String', 'ArrayList', etc.
    Interfaces: Las interfaces definen contratos para métodos que las clases deben implementar.
    Arrays: Los arrays permiten almacenar múltiples valores del mismo tipo en una estructura indexada.
    Enumeraciones (Enums): Los enums son tipos especiales que representan un conjunto de constantes con nombre.
    Tipos de datos personalizados: Puedes definir tus propios tipos de datos utilizando clases y estructuras personalizadas
  
- ¿Por qué hay diferentes tipos de dato que almacenan el mismo tipo de valor?
  Como se mencionó anteriormente, hay ciertos tipos de códigos que implementan mas memoria que otros, al momento de declarar variable es   importante saber que cantidad de memoria puede o debe usar la variable, esto con motivos de optimizar el código en cuestión y evitar   
  el uso de recrusos inncesarios de la máquina
- ¿Qué es inicializar una variable o constante?:
  Inicializar una variable en programación significa asignarle un valor inicial en el momento de su creación. Cuando declaras una   
  variable, estás reservando un espacio en la memoria para almacenar algún tipo de dato. Sin embargo, hasta que le asignas un valor, el 
  contenido de ese espacio en memoria puede ser cualquier cosa. ej:

   ``` {java}
   int numero; //declara la variable
    numero=10; //inicializa la variable
   ```
- ¿Qué pasa si no inicializamos una variable?
     tu PC  explota

- Declare las siguientes variables:
  "nombre" para almacenar un nombre
  ````{java}
  import java.util.Scanner;
  {
  String nombre;
  system.out.println("Ingrese nombre");
  nombre = scanner.nextLine();
  scanner.close();
  }
  
    





    
