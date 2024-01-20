
# Enlaces

Para crear un link simplemente cerramos entre corchetes el texto que queramos que nos direccione a otro lugar seguido de la URL entre paréntesis.

Aquí te muestro un ejemplo de como crear un link:

```
[Mi perfil en GitHub](https://github.com/alexdevrep)
```

La salida que se nos mostrará será la siguiente:

[Mi perfil en GitHub](https://github.com/alexdevrep)

---

## Añdiendo título al enlace

Si queremos que al pasar el ratón por el link aparezca una pequela descripción sobre el sitio al que va a dirigirse simplemente añadimos entre comillas la descripción del texto justo despues de la URL

Aquí te enseño a crear un link con una descripción

```
[Mi perfil en GitHub](https://github.com/alexdevrep "GitHub de alexdevrep")
```

La salida que se nos muestrará es la siguiente:

[Mi perfil en GitHub](https://github.com/alexdevrep "GitHub de alexdevrep")

---

## URL's y direcciones de email

Para convetir una URL o una dirección de email en un link debemos de escribirlos entre comillas angulares `<>`

Aquí te muestro un ejemplo de como hacerlos

```
<https://www.youtube.com/>
```

La salida que se nos muestra es la siguiente:

<https://www.youtube.com/>

---

 Formateo de enlaces

Podemos hacer que nuestro enlaces se vean en negrilla para ello incluimos
asteríscos antes y después de los corchetes y paréntesis.

Aquí te muestro un ejemplo de como hacer que los enlaces se vean en negrilla:

ˋˋˋ
**[Mi perfil de GitHub](https://github.com/alexdevrep)**
ˋˋˋ

La salida que se nos muestra por pantalla es la siguiente:


 Enlaces de referencias estilados

Estos enlaces son un tipo de enlace especial que hacen a las URL más fáciles
de leer y desplegar en Markdown.

Estos enlaces se construyen en dos partes (la parte que deseas mantener visible en el
documento y la parte que vas a guardar en otra parte del archivo para mantener el texto 
fácil de leer)

   Creando la primera parte del enlace 

La primera parte del enlace se crea con dos pares de corchetes ˋ[]ˋ en el primer par
aparece el texto que debe de ir linkado y en el segundo par de corchetes una etiqueta que servirá para referenciar al enlace que estamos guardando en otra parte del archivo.

    Creando la segunda parte del enlace 

La segunda parte del enlace se crea siguiendo los siguientes pasos:

1. La etiqueta entre corchetes, seguido por dos puntos ˋ:ˋ y al menos un espacio
2. La URL del enlace, la cual opcionalmente la podemos encerrar entre comillas angulares ˋ<>ˋ
3. Un título opcional para el enlace, encerrado entre comillas simples, dobles o paréntesis

(completar este archivo con ejemplos)


 Buenas prácticas con los enlaces 

Por compatibilidad con ciertos procesadores de Markdown si el enlace tiene espacios en blanco
es mejor sustituir estos espacios por ˋ%20ˋ

Aquí te muestro un ejemplo de como actuar ante enlaces con espacios:

[link](https://ejemplo.com/my%20pagina%20web)


