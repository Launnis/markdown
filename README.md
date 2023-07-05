MARKDOWN
# CABECERAS
version 1.0.0 
# CABECERA H1
## CABECERA H2
### CABECERA H3
#### CABECERA H4
##### CABECERA H5
###### CABECERA H6

# UNDERLINES
Underline1
----------
Underline2
==========

# FORMATOS DE ÉNFASIS
- formato *italic* de la primera forma
- formato _italic_ de la segunda forma
- formato **bold** de la primera forma
- formato __bold__ de la segunda forma
- formato ~~tachado~~ , formato normal
- aqui podemos usar formato *italic* pero tambien **bold** o ~~tachado~~

# LISTAS
1. esto es un item de lista ordenada ol
2. esto es un item de lista ordenada ol
- esto es un item de lista desordenada ul
- esto es un item de lista desordenada ul

# LINKS 

- <a href= "http://google.com"> Esto es un link HTML </a>
- [Esto es un link en markdown](http://google.com)
- [Esto es un link al index](index.html)
- [Con este editamos todo esto en vez de escribirlo aquí - editormd]()
- [Con este vemos diferentes estilos/highlights con diferentes códigos - hightlightjs.org](https://highlightjs.org/static/demo/)

# IMÁGENES
![logo github](https://logoeps.com/wp-content/uploads/2014/05/37318-github-logo-icon-vector-icon-vector-eps.png)

# CODE SNIPPETS
Código en JSON
``` JSON
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
Código en JavaScript
``` JavaScript
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

# TABLAS
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Laura  | Burgos | 34234243J
| Pepe | Madrid | 23542342H

# CITAS 
Esto es un texto referente a una cita que pondremos debajo:
>Esto es una cita.

Esto es otro texto bien separado para que no se junte con la otra.
>Esto es otra cita

# LÍNEAS DIVISORAS
Esto es un texto que será dividido por guiones medios.

-------------

Esto es otro texto dividido por astericos

******

Esto es otro texto dividido por guiones bajos

_________

--------

# SALTOS DE LÍNEA

Esto es nuestro primer párrafo separado por enter.

Esto es nuestro segundo párrafo separado por enter.

Esto es nuestro tercer párrafo separado por enter.



