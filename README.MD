# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de énfasis
- formato *italica* de la primera forma
- formato _italica_ de la primera forma
- formato **bold** o __strong__.
- formato ~~tachado~~
- ~~***italico***~~

# Listas
1. Esto es un item ordenado
2. Esto es un item ordenado
3. Esto es un item ordenado
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://www.google.es">Esto es un link</a>
- [Esto es un link en MD](http://www.google.es)
- [Esto es un link al index.html](index.html)

# Imágenes
 ![Logo Github]()

 # Snippets
 Código JSON [https://highlightjs.org/static/demo/]
 ```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
 ```

Código JavaScript
 ```Javascript
 function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
 ```

 # Tablas
 | Nombre | Apellido | Documento |
 | ------ | -------- | --------- |
 | Maxi | Burgos | 12345567P | 
 | Tomas | Pepe | 123654L |
 
 # Citas
 Esto es un texto referente a una cita que pondremos debajo:
 > Esto es una cita

 Esto es otro texto:
 > Esto es otra cita

 # Líneas divisoras
 Esto es un texto que será dividido
 
 ---

 Esto es otro texto dividido

***

Esto es otro mas
___

# Saltos de línea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.