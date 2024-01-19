
# Tablas 

>Atención: Este archivo pertenece a la sintaxis avanzada del lenguaje por lo que 
>no todas las variantes de Markdown ni los procesadores soportan esta sintaxis para más información clica [aquí](https://github.com/alexdevrep/Markdown_docs/blob/main/Disponibilidad/Disponibilidad.md)

Para crear una tabla añadimos tres o más guiones `---` para crear el encabezado de las columnas y barras verticales `|` para separar cada columna.

Aquí te muestro como crear una tabla:

```
|Encabezado1 | Encabezado 2 | Encabezado n |
|----------- |------------- | ------------ |
|Elemento 1  |Elemento 1    |Elemento 1    |
|Elemento 2  |Elemento 2    |Elemento 3    |
|Elemento 3  |Elemento 2    |Elemento 3    |
```

La salida que se nos muestra es la siguiente:

|Encabezado1 | Encabezado 2 | Encabezado n |
|----------- |------------- | ------------ |
|Elemento 1  |Elemento 1    |Elemento 1    |
|Elemento 2  |Elemento 2    |Elemento 3    |
|Elemento 3  |Elemento 2    |Elemento 3    |

(El tamaño de las celdas puede variar pero no se verá afectada la salida)

## Alineamiento de las tablas 

Podemos alinear el texto de las columnas a la izquierda, a la derecha o en el centro añadiendo dos puntos `:` a los lados de los guiones que separan los encabezados.

Aquí te muestro como hacerlo:

```
|Encabezado1 | Encabezado 2 | Encabezado n |
|:---------- |:-----------: | -----------: |
|Elemento 1  |Elemento 1    |Elemento 1    |
|Elemento 2  |Elemento 2    |Elemento 3    |
|Elemento 3  |Elemento 2    |Elemento 3    |
```

la salida será la siguiente:

|Encabezado1 | Encabezado 2 | Encabezado n |
|:---------- |:-----------: | -----------: |
|Elemento 1  |Elemento 1    |Elemento 1    |
|Elemento 2  |Elemento 2    |Elemento 3    |
|Elemento 3  |Elemento 2    |Elemento 3    |

## Formateando texto en las tablas

En una tabla podemos añadir los siguientes elementos

* Enlaces
* Código entre comillas invertidas (bloques de código no)
* Tachado
* Negrilla
* Cursiva

## Recurso adicional

Si crear una tabla te parece algo tedioso de hacer aquí te dejo un enlace 
que va a ahorrarte mucho tiempo.

* [Generador de tablas Markdown](https://www.tablesgenerator.com/markdown_tables)

