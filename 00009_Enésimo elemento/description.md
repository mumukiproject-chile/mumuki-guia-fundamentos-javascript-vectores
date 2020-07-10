Así como existe una función para averiguar en qué posición está un elemento, también puede ocurrir que queramos saber lo contrario: qué elemento está en una cierta posición. :open_mouth:

Para averiguarlo, podemos usar el **operador de indexación**, escribiendo después de la colección y entre corchetes `[]` la posición que queremos para averiguar:

```javascript
ム mesesDelAnio[0]
"enero"
ム ["ese", "perro", "tiene", "la", "cola", "peluda"][1]
"perro"
```

¡Ojo! El número que ingreses, formalmente llamado **índice**, debe ser menor a la longitud de la lista, o puede pasar algo malo. :astonished:

> Pruébalo tú mismo en la consola: ¿qué pasa si le pides el elemento 0 a una lista vacía? ¿O si le pides el elemento 48 a una lista de 2 elementos?