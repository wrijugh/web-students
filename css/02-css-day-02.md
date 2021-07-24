# CSS Basics - Day 2

Borders - you can have fun with borders. Below sample

![CSS Borders](css-assignments/border-sample.png)

## Borders

```html
<h1>Heading 1</h2>

<h2>Heading 2</h2>

<h3>Heading 3</h3>

<h1 id="multicolor">Multi Color Heading 1 </h3>

```

```css
<style>

    h1 { border-style: dotted;}

    h2 {
        border-style: solid;  
        border-color: tomato;
    }

    h3 { 
        border-bottom-style: solid; 
        border-color: green; 
    }

    #multicolor { 
        border-style: solid;
        border-bottom-color: red;
        border-right-color: green;
        border-top-color: blue ;
        border-left-color: tomato ;        
    }
</style>
```

You can also group all the border properties in one line. They follow the clockwise pattern `top` -> `right` -> `botton` -> `left`.

```css
border-color: orange red green blue;
```

Is equivalent to,

```css
border-top-color: orange;
border-right-color: red;
border-bottom-color: green;
border-left-color: blue;
```

This can be taken for any property which has side specific option like `margin`, `padding` etc.

## CSS Assignment #2

Please comeup with your own idea to design a page with some html tags. Be creative. Creativity has no limit.

---

[Home Page](../README.md)

[Next: CSS Day 3 >>](03-css-day-03.md)
