Otra cosa que queremos hacer con las listas es saber en qué posición se encuentra un elemento. Para ello, utilizamos la función `posicion` de la siguiente manera:

```javascript
posicion(["a", "la", "grande", "le", "puse", "cuca"], "grande"); //devuelve 2

let diasLaborales = ["lunes", "martes", "miercoles", "jueves", "viernes"]
posicion(diasLaborales, "lunes"); //devuelve 0
```

Como ves, lo curioso de esta función es que pareciera devolver siempre uno menos de lo esperado. Por ejemplo, la palabra `"grande"` aparece tercera, no segunda; y `"lunes"` es el primer día laboral, no el cero. ¿Será que los creadores de JavaScript se equivocaron? :confused:

¡No! Es que en JavaScript, al igual que en muchos lenguajes, las posiciones de las listas parten en 0: el primer elemento está en la posición 0, el segundo en la 1, el tercero en la 2, y así.

> ¿Y qué sucede si ingresas como parámetro en `posicion` un elemento que no tiene? ¡Averígualo tú mismo!
> 
> Prueba lo siguiente:
> 
> ```javascript
posicion(diasLaborales, "osvaldo")
```