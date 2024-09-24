# CSS
1. Hoja de estilos en cascada
```html
<link rel="stylesheet" href="./styles.css">
```
2. Usando la etiqueta "style"
```html
<style> 
    h1{
        color:red;
    }
</style>
```
3. De manera inline en el elemento con el atributo style
```html
<h1 style="color: red">CSS</h1>
```
## SINTAXIS CSS

- Lenguage for web styles (1996) 

# SINTAXIS

- How is  CSS code defined?


```css
    h1{
        color: red;
    }
```

- h1 : selector
- color: propiery
- red: value

## IMPORTANT CSS CONCEPTS -- CONCEPTOS IMPORTANTES EN CSS

- 4 CSS IMPORTANT CONCEPTS

## SELECTORS -- SELECTORES

- Indica a que elemento se le aplicara los estilos

```css
    /*TAG SELECTOR */
    h1{
        color: red;

    /*DESCENDANT SELECTOR */
    nav ul li a {
        color: red;
    }
```

## INHERITANCE -- HERENCIA
- Elementos ancestro heedan algunas propuedad a sus descendientes 
```html
    <p>Hi world <a href="">this is a link</a></p>
```

```css
    h1 {
        color: red;
    }

    p{
        color: green;
    }

    a{
        color: inherit;
    }
```

## CASCADE -- CASCADA

- Significa que los ultimos archivos sobreescriben a los previos.
- La especificidad vence a la cascada

```css
    h1{
        color: red;
    }

    h1{
        color: blue;
    }
```

## SPECIFICITY -- ESPECIFICIDAD

- Es un valor numerico que se establece en los selectores y aplica ante conflictos.

```html
    <!-- Selector de Etiqueta (1) -->

    <!-- Selector de Clase (10)-->

    <!-- Selector de ID (100)-->

    <!-- INLINE (1000)-->

    <!-- IMPORTANT (1000000)-->

```
## STYLES TEXTS

### PROPERTIES

- color
- font-size (em,rem,px)
- font-family (google fonts - fontface)
- font-weight (peso de tipografia)
- estilo entre navegadores (normalize.css)
- text-transform: uppercase | lowercase | capitalize
- text-align : left | center | right
- text-decoration : none | underline

