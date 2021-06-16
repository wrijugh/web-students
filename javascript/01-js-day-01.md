# JavaScript - Day 1

Invented by Brendan Eich in 1995. JavaScript can

- Change text, style, visibility of an HTML element.
- JavaScript can do a lot more for Web.

## Change the HTML Element

Let's see how we can change an HTML element through JavaScript. In a HTML page there are many elements available. We need to catch the element we want to modify then change the property of that. Let's say that we have an element `<p>`. Now there are a many ways to get the element. One of the most popular ways is to find it by `id` attribute.

```html
<p id="1">Here is some text</p>

<script>
    document.getElementById("1").innerHTML = "Hello From JavaScript"
</script>
```

This will change as soon as you open the page. JavaScript is event driven. That means when something happens you can change something. So imagine if you wish to move the mouse over the text and then change it.

JavaScript can be written as function and it is very convenient to call it whenever you feel like. If we change the above,

```html
<p id="1" onmouseover="changeText()">Here is some text</p>

<script>
    function changeText(){
        document.getElementById("1").innerHTML = "Hello From JavaScript"
    }
</script>
```

Once you load your HTML page then move the mouse over the text it would change to the `Hello From JavaScript`. Refresh the browser to reset it.

## JavaScript Assignment #1

- Change the text of a `<h1>` tag when mouse cursor enters.
- When a button is clicked then show a some text in `<p>`.

---

[Home](../README.md)

[Next: JavaScript Day 2 >>](02-js-day-02.md)
