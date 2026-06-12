# Tema 1 - Variables y tipos de datos

## ¿Qué es una variable?

Una variable es un espacio de memoria que permite almacenar información para utilizarla posteriormente en el programa.

En JavaScript se crean normalmente utilizando la palabra reservada `let`.

```javascript
let nombre = "Omar";
let edad = 39;
```

---

## La instrucción console.log()

La función `console.log()` permite mostrar información por la consola.

```javascript
console.log("Hola mundo");
```

También puede mostrar el valor de variables:

```javascript
let nombre = "Omar";

console.log(nombre);
```

Resultado:

```text
Omar
```

---

## Tipos de datos básicos

### String

Representa texto.

```javascript
let nombre = "Omar";
let ciudad = "Alicante";
```

Tipo:

```javascript
typeof nombre;
```

Resultado:

```text
string
```

---

### Number

Representa números enteros o decimales.

```javascript
let edad = 39;
let altura = 1.75;
```

Tipo:

```javascript
typeof edad;
```

Resultado:

```text
number
```

---

### Boolean

Representa valores lógicos.

```javascript
let esProgramador = true;
let aprobado = false;
```

Tipo:

```javascript
typeof esProgramador;
```

Resultado:

```text
boolean
```

---

## Operador typeof

Permite conocer el tipo de dato almacenado en una variable.

```javascript
let nombre = "Omar";
let edad = 39;
let esProgramador = true;

console.log(typeof nombre);
console.log(typeof edad);
console.log(typeof esProgramador);
```

Resultado:

```text
string
number
boolean
```

---

## Template Literals

Los Template Literals permiten insertar variables dentro de cadenas de texto.

Se utilizan con comillas invertidas (backticks):

```javascript
`
```

Sintaxis:

```javascript
let nombre = "Omar";

console.log(`Me llamo ${nombre}`);
```

Resultado:

```text
Me llamo Omar
```

---

## Expresiones dentro de ${}

Dentro de `${}` pueden utilizarse variables y operaciones.

```javascript
let edad = 39;

console.log(`El año que viene tendré ${edad + 1} años`);
```

Resultado:

```text
El año que viene tendré 40 años
```

---

## Diferencias con Java

### Java

```java
String nombre = "Omar";
int edad = 39;
boolean esProgramador = true;
```

### JavaScript

```javascript
let nombre = "Omar";
let edad = 39;
let esProgramador = true;
```

JavaScript determina automáticamente el tipo de dato almacenado en la variable.

---

## Conceptos aprendidos

- Variables (`let`)
- Tipos de datos (`string`, `number`, `boolean`)
- `console.log()`
- `typeof`
- Template Literals
- Interpolación de variables mediante `${}`

```

```
