Vamos a ver una manera de recorrer los elementos de una lista con un nuevo amigo: el  `for`. :muscle:

Imaginémonos que tenemos una lista con los precios de los productos que compramos en el supermercado y queremos restar cada uno de ellos a `plataEnBilletera` :money_with_wings:. Usando `for` podemos hacerlo así:

```javascript
for(let precio of [10, 100, 87 ]) {
  plataEnBilletera  = plataEnBilletera - precio
}

```
donde `plataEnBilletera` es una variable que se va modificando a medida que recorremos los `precio`s.

Si teníamos $5.000 en nuestra billetera, después del `for` nos van a quedar $3.030 porque:

* Al principio `plataEnBilletera` era 5.000 y el primer `precio` de la lista es 100. Luego de hacer 5.000 - 100, `plataEnBilletera` es 4.900.
* A los 4.900 que quedaron en nuestra billetera, le restamos el segundo precio de la lista: 1.000. Ahora `plataEnBilletera` es 3.900.
* El último precio a restar es 870, por lo que, al hacer 3.900 - 870, la variable `plataEnBilletera` terminará siendo 3.030.

> Completa la función `saludar` que reciba una lista de personas e imprima un saludo para cada una de ellas.
> 
> ``` javascript ム saludar(["Don Pepito", "Don Jose"]) hola Don Pepito hola Don Jose
> 
> ム saludar(["Elena", "Hector", "Tita"]) hola Elena hola Hector hola Tita ```
