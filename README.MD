# Cabeceras

# Cabecera H1

## Cabecera H2

### Cabecera H3

#### Cabecera H4

##### Cabecera H5

###### Cabecera H6

# Underlines

## Underline 1

`-------------`

# Underline 2

`============`

# Formatos de enfasis

- letra `*`_italica_`*` de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato `__`**bold o strong**`__` de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar _formato italico_, pero tambien **bold** y ~~tachado~~

# Listas

1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

1.  Esto es una lista ordenada combinado

- con una desordenada.

# Links

- <a href="https://www.google.com">Esto es un link HTML</a>
- [Esto es un link Markdown](https://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes

![Logo GitHub](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png)

# Code Snippets

Codigo en JSON

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

Codigo en Javascript

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

Codigo en Java

```Java
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract strictfp class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
}
```

Codigo en Markdown

```Markdown
# hello world

you can write text [with links](http://example.com) inline or [link references][1].

* one _thing_ has *em*phasis
* two __things__ are **bold**

[1]: http://example.com

---

hello world
===========

<this_is inline="xml"></this_is>

> markdown is so cool

    so are code segments

1. one thing (yeah!)
2. two thing `i can write code`, and `more` wipee!
```

# Tablas

| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Juan   | Martinez | 11271999  |
| Miguel | Toledo   | 24121999  |
| Itzel  | Ruiz     | 18111999  |

# Citas

Esto es un texto referente a una cita que pondremos debajo:

> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:

> Esto es otra cita

# Lineas Divisoras

Esto es un texto que sera dividido.

---

Esto es otro texto dividido.

---

`***`
Esto es otro texto dividido por guiones bajos

---

`___`
