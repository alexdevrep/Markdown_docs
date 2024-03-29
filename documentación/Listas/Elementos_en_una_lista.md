
# Elementos que se pueden añadir en una lista

En este apartado veremos los elementos que podemos añadir a una lista 
sin importar que sea ordenada o desordenada.

 ## Párrafos

Para añadir un párrafo a una lista simplemente identamos con el tabulador 
y escribimos lo que deseemos.

Aquí te muestro un ejemplo de como añadir un párrafo a una lista:

ˋˋˋ
* Primer elemento de la lista
* Segundo elemento de la lista

    Párrafo a añadir en la lista

* Tercer elemento de la lista
ˋˋˋ

La salida que se nos muestra por pantalla es la siguiente:

* Primer elemento de la lista
* Segundo elemento de la lista

    Párrafo a añadir en la lista

* Tercer elemento de la lista


## Citas en bloque 

Podemos añadir citas en bloque a una lista de la siguiente manera:

```
* Primer elemento de la lista
* Segundo elemento de la lista

    > En un lugar de la mancha cuyo nombre no quiero acordarme...

* Tercer elemento de la lista
```


La salida que se nos muestra por pantalla es la siguiente:

* Primer elemento de la lista
* Segundo elemento de la lista

    > En un lugar de la mancha cuyo nombre no quiero acordarme...

* Tercer elemento de la lista

## Bloques de código 

Los bloques de código pueden añadirse a una lista simplemente identando todo
el bloque dos veces (es decir dándole 2 veces al tabulador):

Aquí te muestro un ejemplo de cómo incluir un bloque de código en una lista:

```
1. Primer elemento de la lista
2. Segundo elemento de la lista

        let mi_variable = "Hola, JavaScript"
        console.log(mi_variable)

3. Tercer elemento de la lista 
```

La salida que se nos muestra por pantalla es la siguiente:

1. Primer elemento de la lista
2. Segundo elemento de la lista

        let mi_variable = "Hola, JavaScript"
        console.log(mi_variable)

3. Tercer elemento de la lista 

## Imágenes 

 En las listas también pueden añadirse imágenes de la siguiente manera:

```
1. Primer elemento de la lista
2. Segundo elemento de la lista 

    ![Una imagen de OctoCat, la mascota de GitHub](/imágenes/OctoCat.png)

3. Tercer elemento de la lista
```
La salida que se nos muestra por pantalla es la siguiente:

1. Primer elemento de la lista
2. Segundo elemento de la lista 

    ![Una imagen de OctoCat, la mascota de GitHub](/documentación//imágenes/OctoCat.png)

3. Tercer elemento de la lista

## Listas 

También es posible añadir listas dentro de otras listas.

```
1. Primer elemento de la lista
2. Segundo elemento de la lista
    * Primer elemento de la lista identada
    * Segundo elemento de la lista identada
3. Tercer elemento de la lista

```

La salida que se nos muestra por pantalla es la siguiente:

1. Primer elemento de la lista
2. Segundo elemento de la lista
    * Primer elemento de la lista identada
    * Segundo elemento de la lista identada
3. Tercer elemento de la lista
