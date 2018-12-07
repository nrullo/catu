# Clase 02: Estructura condicional `if ... else`
 
Es un tipo de estructura condicional. `if` significa "si" (condicional) en español.

Su funcionamiento es simple: se evalúa una condición, si es verdadera ejecuta un código, si es falsa, ejecuta otro código (o continúa con la ejecución del programa).

Supongamos que queremos saber si nuestro jugador ha completado el nivel actual, si lo completó entonces deberíamos pasar al siguiente nivel, podríamos hacer:

```
if (nivel_completado === true) {
  console.log('El jugador ' + jugador1.nombre + ' pasó al siguiente nivel');
  jugador1.nivel_actual = jugador1.nivel_actual + 1;
} else {
  console.log('El jugador ' + jugador1.nombre + ' aún no pasó de nivel');
}
```
