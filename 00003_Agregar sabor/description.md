Las listas son muy útiles para contener múltiples elementos. ¡Pero hay más! También podemos agregarle elementos en cualquier momento utilizando la función `agregar`, que recibe dos parámetros: la lista y el elemento. Por ejemplo:

```javascript
let pertenencias = ["espada", "escudo", "antorcha"];
//longitud(pertenencias) devuelve 3;

agregar(pertenencias, "amuleto mágico");
//ahora longitud(pertenencias) devuelve 4
```

Como vemos, `agregar` suma un elemento a la lista, lo cual hace que su tamaño aumente. ¿Pero en qué parte de la lista lo agrega? ¿Al principio? ¿Al final? ¿En el medio?

> Averígualo tú mismo: inspecciona en la consola qué elementos contiene `pertenencias`, agrégale una `"ballesta"` y vuelve a inspeccionar `pertenencias`.
> 
> Además, hay un procedimiento `remover` que sólo recibe la lista por parámetro. Investiga en la consola qué hace. :thought_balloon:
