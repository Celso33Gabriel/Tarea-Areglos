# Tarea: Configuración de Entorno Java/Maven y Arreglos en Java

## 1. Configuración del entorno
Se instalaron los requisitos necesarios para el desarrollo en Java:
* **JDK 11**
* **Maven**
* **IDE Eclipse**

## 2. Capturas obligatorias del entorno
Las evidencias de la instalación se encuentran en la carpeta `/docs`:
* **Java Version**: ![Java](./docs/)
* **Maven Version**:

## 3. Ejercicio Java con Maven
Se implementó un programa básico con una multiplicación:
* **Código**: Se utilizó `System.out.println` y variables tipo `int`.
* **Ejecución**: ![Ejecución](./docs/ejecucion.png)

## 4. Investigación: Arreglos en Java
### 4.1 Declaración e inicialización
* `int[] numeros = new int[5];`
* `int[] valores = {1, 2, 3, 4, 5};`

### 4.2 Métodos de java.util.Arrays
1. `sort()`: Ordena el arreglo.
2. `binarySearch()`: Busca un elemento.
3. `equals()`: Compara arreglos.
4. `fill()`: Llena el arreglo.
5. `toString()`: Convierte a texto.

### 4.3 Diferencias: Arreglo vs ArrayList
* **Arreglo**: Tamaño fijo y más rápido.
* **ArrayList**: Tamaño dinámico y solo objetos.


# Tarea: Configuración de Entorno Java/Maven y Arreglos en Java
## 1. Configuración del entorno (Requisitos)
Se realizó la instalación y configuración de las siguientes herramientas:

### JDK 11

### Maven

### IDE Eclipse

### Cuenta de GitHub

## 2. Evidencias de Configuración

### Resultado de java -version: Ver captura en /docs

### Resultado de mvn -v: Ver captura en /docs

## 3. Ejercicio Java con Maven
Se creó un proyecto Maven ejecutando un programa simple que imprime un saludo y realiza una operación matemática.

# Código implementado:

Java
System.out.println("Hola mundo desde Java");
int a = 6;
int b = 7;
int resultado = a * b;
System.out.println("Resultado: " + resultado);
### Ejecución del programa: Ver captura de Eclipse en /docs

## 4. Investigación: Arreglos en Java
## 4.1 Declaración e inicialización
Se muestran las dos formas principales de manejar arreglos:

int[] numeros = new int[5];

int[] valores = {1, 2, 3, 4, 5};

## 4.2 Métodos de java.util.Arrays
Arrays.sort: Ordena el arreglo.
Arrays.binarySearch: Busca un elemento.
Arrays.copyOf: Copia el arreglo.
Arrays.fill: Llena el arreglo con un valor.
Arrays.equals: Compara dos arreglos.

## 4.3 Formas de recorrer arreglos
For tradicional: Usando índices.
For-each: Recorrido simplificado.
Streams: Usando Arrays.stream(...).forEach(...).

## 4.4 Diferencias: Arreglo vs ArrayList
Tamaño: El Arreglo es fijo; el ArrayList es dinámico.
Tipos: El Arreglo usa primitivos; el ArrayList usa clases envolventes.
Rendimiento: El Arreglo es más rápido.

