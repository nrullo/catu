# Clase 01: Variables `var` y comentarios `// me gusta programar`

## Variables

Una variable es un espacio de memoria que se utiliza para guardar información: `var mi_perro = "Firulais"`.

El valor que guardamos en una variable puede tener diferentes tipos de datos que veremos a continuación.

### Numérico (integer, float)

Por ejemplo, si estamos programando un video juego y queremos guardar el actual `nivel` del jugador, podemos a guardarlo de la siguiente manera:

`var nivel = 10; // la variable "nivel" va a tener un valor numérico (integer) igual 10`

Ahora si queremos guardar el actual `puntaje` del jugador, podemos hacerlo escribiendo:

`var puntaje = 425.2; // la variable "puntaje" va a tener un valor numérico (float) igual 425.2`

### Cadena de texto (string)

En cambio si queremos guardar el nombre del jugador podemos hacerlo escribiendo:

`var nombre_jugador = "Juanita"; // la variable "nombre_jugador" va a guardar una cadena de caracteres (string) con el valor "Juanita"`

### Objecto (object)

Un objeto es una variable con esteroides, ya que no sólo puede tener un valor, sino varias propiedades. Por ejemplo, imaginemos que queremos guardar varias caraterísticas de nuestro jugador, podemos hacerlo de la siguiente manera:

```
var jugador = {
  "nombre": "Juanita",
  "nivel_actual": 10
  "puntaje_actual": 425.2
};
```

Luego podemos acceder a cada propiedad utilizando un `.`. Ejemplo:

```
jugador.nivel_actual = jugador.nivel_actual + 1;
console.log(usuario.nivel_actual); // el jugador subió un nivel, por lo tanto, esto imprimirá 11
```

### Arreglos (arrays)

Un array es un tipo de variable donde se pueden guardar múltiples valores. Como ejemplo, si queremos guardar nuestra lista de jugadores bastaría con definir los jugadores y luego "empujarlos" (`push`) a nuestra lista:

```
var jugador1 = {
  "nombre": "Juanita",
  "nivel_actual": 11
  "puntaje_actual": 425.2
};

var jugador2 = {
  "nombre": "Simón",
  "nivel_actual": 5
  "puntaje_actual": 400
};

var jugadores = []; // definición del array

jugadores.push(jugador1); // jugadores[0] contiene el valor de jugador1
jugadores.push(jugador2); // jugadores[1] contiene el valor de jugador2
```

### Booleano (boolean)

Un booleano es una tipo de variables que puede tener 2 valores posibles: `true` (verdadero, 1) o `false` (falso, 0). Ejemplo:

`var nivel_completado = false; // nos indicará que el no ha sido completado`

## Comentarios

En las líneas de código de arriba aparecen unas marcas `//`, eso es un comentario. Un comentario es una parte del código que no se ejecuta, que utilizamos para hacer anotaciones alrededor del código. Ejemplo:

```javascript
// este es un comentario de una sola línea

/*
este es otro comentario,
pero de múltiples líneas
*/
```
