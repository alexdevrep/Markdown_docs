
# Citas en  bloque

Para crear una cita en bloque añadimos un `>` al principio de un párrafo.

Aquí tienes un ejemplo famosísimo de cita en bloque:

>En un lugar de la Mancha, de cuyo nombre no quiero acordarme, no ha mucho tiempo que vivía un hidalgo de los de lanza en astillero, adarga antigua, rocín flaco y galgo corredor...

## Citas en bloque con varios párrafos

Si deseamos añadir citas en bloque que contengan varios párrafos debemos hacer lo 
siguiente:

```
>Aquí añadimos el primer párrafo de la cita en bloque
>
>Aquí añadimos el párrafo número n de la cita en bloque
>
```

Lo que veríamos en la salida sería lo siguiente:

>En un lugar de la Mancha, de cuyo nombre no quiero acordarme, no ha mucho tiempo que vivía un hidalgo de los de lanza en astillero, adarga antigua, rocín flaco y galgo corredor...
>
> Con diez cañones por banda,
viento en popa a toda vela,
no corta el mar, sino vuela,
un velero bergantín;
bajel pirata que llaman
por su bravura el Temido
en todo el mar conocido
del uno al otro confín. 

---

## Citas en bloque anidadas 

También es posible anidar citas en bloque solo tienes que añadir lo siguiente:

```
>Aquí iría un párrafo de la cita en bloque 
>
>> Y aquí iría el párrafo anidado (identado)
```

Lo que veríamos en la salida sería lo siguiente:

>En un lugar de la Mancha, de cuyo nombre no quiero acordarme, no ha mucho tiempo que vivía un hidalgo de los de lanza en astillero, adarga antigua, rocín flaco y galgo corredor...
>
>>Con diez cañones por banda,
viento en popa a toda vela,
no corta el mar, sino vuela,
un velero bergantín;
bajel pirata que llaman
por su bravura el Temido
en todo el mar conocido
del uno al otro confín. 

---

### Citas en bloques con otros elementos 

Este elemento permite utilizar otros elementos dentro de él como pueden ser encabezados letras en negrilla o listas.

**Ojo no todos los elementos son compatibles por lo que deberás comprobar cual si**

Un ejemplo de esto sería:

```
> # Aquí añado un encabezado a mi cita 
>
> -Elemento 1 
> -Elemento 2
>
>Así **pongo letras en negrilla**
```

La salida que nos mostraría sería:

> # Aquí añado un encabezado a mi cita 
>
> -Elemento 1 
> -Elemento 2
>
>Así **pongo letras en negrilla**

---

## Buenas prácticas con citas en bloques

Si vamos a añadir párrafos antes y despues de una cita en bloque
por compatibilidad mejor dejar líneas en blanco entre los párrafos y la cita en bloque.







