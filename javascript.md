# JavaScript

## Historia
JavaScript se creo en 1995, como una forma de agregar una mayor interactividad y dinamismo a las páginas web en el navegador Netscape Navigator. Uno de los objetivos principales era prevenir el envio de peticiones innecesarias al servidor.

El nombre original era LiveScript, pero decidieron cambiarlo a JavaScript ya que en esa fecha era un lenguaje muy popular y de moda.

El creador de JavaScript es Brendan Eich. 

En la actualidad, ECMA (European Computer Manufacturers Association / Asociación Europea de Fabricantes de Computadoras) tiene un comité llamada TC39 o ECMASCript, que estandariza el lenguaje script.

La version actual de ECMAScript es la 12, lanzada en Junio del 2021.

## Variables en JavaScript
Una variable es un contenedor que apunta a un lugar en memoria. Este espacio contiene información conocida o desconocida.

En Javascript se pueden definir una variable con la palabra reservada `let` o `var` (no recomendado).

Existe una serie de variables básicas:
- Contador
    - Variable cuyo valor se incrementa o decrementa en una cantidad constante cada que se produce un determinado suceso o acción
    - Inicializacion: `let contador = 0`
    - Incremento: `contador = contador + 1` ó `contador++`
    - DecrementoL `contador = contador - 1` ó `contador--`
- Acumulador
    - Variable cuyo valor se incrementa o decrementa en una cantidad variable cada que se produce un determinado suceso o acción
    - Inicialización: `let acumulador = 0`
    - Acumulación: `acumulador = acumulador + 5`
- Bandera o centinela
    - Valor asignado a una variable que hace que se ejecute un bloque de instrucciones. Tiene un valor verdadero `1` o falso `0`
    - Inicializacion: `let bandera = false`
    - Punto de cambio: `bandera = true`

## Constantes en JavaScript
Una constante es un contenedor que apunta a un lugar en memoria y NO es mutable.

Este espacio alberga información conocida que no cambiará a lo largo de la ejecución del programa.

Para definir una constante se usa la palabra reservada `const`. Ejemplo: `const creadorDeJavascript = 'Brendan Uich'`

## Operadores comunes
- `+` Usado para sumas/concatenación
- `-` Usado para restas
- `*` Usado para multiplicaciones
- `/` Usado para divisiones
- `%` Usado para remanentes

## Tipos de datos
- Simples ó primitivos
    - Números enteros
    - Caracteres
    - Booleanos
- Compuestos ó estructurados
    - Arreglos
    - Cadenas de caracteres
    - Registros

 ## Estructuras de control


## Métodos

## Objetos

## JSON



## POO
(Programación orientada a objetos)
Paradigma de programación que usa objetos en iteraciones para diseñar aplicaciones. Es el modelo de programación más cercano a la expresión de elementos en la vida real. 


#### Lenguajes que usan POO:
- Java
- C
- C#
- JavaScript


### Conceptos básicos de POO

#### Qué es un objeto?
en Programación orientada a objetos, un objeto representa un elemento del mundo real llevado a un programa. 

Un objeto es una entidad que contiene atributos que describen su estado en el mundo real y las acciones que tienen. Se designa con un nombre o identificador. todos los objetos tienen **atributos** y **métodos**.

**Atributo**: Datos que caracterizan el estado de un objeto

**Métodos**: Procedimientos o funciones que puede realizar el objeto.

**Clase**: Descripcion de un conjunto de objetos que consta de métodos y datos que resumen las caracteristicas comunes del mismo.

Para representar una clase se utiliza UML (Unified Model Language / Lenguaje unificado de modelado) es un estándar para la representación visual de objetos, estados y procesos dentro de un sistema.


| Clase |
----------
| Atributos |
| Métodos |

**Instancia**: Representa un elemento particular que especifica sus características esenciales. **Un objeto es la instancia de una clase**.

**Constructor**: Una operación que crea un objeto y/o incializa su estado.
Cosas a tocar en cuenta al crear un constructor:
- Declarar con la palabra reservada `constructor`
- Este método se considera como procedimiento, puesto que no nos regresa el objeto creado

Es buena practica que los archivos de clase se inicien con mayúscula ej: `Clase.js`

Para declarar una clase:

```js
class ClaseUno {

}
```

para exportar una clase se usa la siguiente estructura:

```js
export default class ClaseUno {

}
```






