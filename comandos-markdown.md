# Guía de markdown

## ENCABEZADOS O TÍTULOS
Se utiliza el símbolo `#` "n" veces donde n es la profundidad de encabezado deseado como si fuese la etiqueta `hn` en html
# h1
``` 
# h1
```
## h2
```
## h2
```
### h3
```
### h3
```
---

## Listas
Para crear *listas ordenadas* se utilizan los `números`, para añadir una sub lista se utilizan `tab + numero + .`
1. Item 1
2. Item 2
    1. subItem 1
    2. subItem 2
```
1. Item 1
2. Item 2
    1 subItem 1
    2 subItem 2
```
Para crear *listas desordenadas* se utiliza el `*`, para añadir una sub lista se utilizan el `tab + *`.
* Item 1
* Item 2
    * Item 1
    * Item 2
```
* Item 1
* Item 2
    * Item 1
    * Item 2
```
---

## Links
Para usar *links* se utilizan de la siguiente forma:
entre `[]` se agrega el nombre y entre `()` se agrega el link de la página:
[GitHub](http://github.com)
```
[NAME_PAGE](LINK)
[GitHub](http://github.com)
```
---

## Salto de linea
Se utilizan `---`
```
---
```
---

### Imagenes
Para utilizar imágenes se utiliza básicamente el mismo concepto de los links, pero se agrega el símbolo `!` al principio:
![GitHub Logo](https://github.githubassets.com/favicons/favicon-dark.svg)
```
![PAGE_NAME_ALT](LINK_IMAGE)
```
---

## Énfasis
* Italic
    
    Para utilizarlo se agregan `*` o `_` en lo que se desee remarcar con italic

    Texto en *italic*
    Texto en _italic_
```
Texto en *italic*
Texto en _italic_
```

* Bold -> negrita

    Para utilizarlo se agregan `**` o `__` en lo que se desee remarcar con bold

Texto en **bold**
Texto en __bold__
```
Texto en **bold**
Texto en __bold__
```
---

## Código
Se utilizan ` ``` ` seguido del lenguaje (puede no incluirse), se pulsa la tecla `enter` y después se agrega el `código a remarcar`, por último nuevamente se presiona la tecla `enter` y se agregan otra vez las  ` ``` `

` ``` javascript`

function test() {

 console.log("text");

}

` ``` `
```javascript
function test() {
 console.log("text");
}
```
---

## Tablas
Los títulos se señalan primero.
Después para marcar que es una columna se agrega un `|`.
Pueden utilizar el salto de línea para marcar que es otra fila, por último se utilizan los `-` para marcar de mejor manera las columnas

First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2
.
```
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2
```
---

## Citas
Se utiliza el `>` seguido del texto, por ejemplo:

Ben Parker dijo:
> "Cuando el grajo vuela bajo hace un frío del carajo."

### CRÉDITOS
Contenido basado en un documento de [BattlerHaru](https://gist.github.com/BattlerHaru) - [comandos-markdown](https://gist.github.com/BattlerHaru/80c0bb5f873deae0589046d4d1b8f963)