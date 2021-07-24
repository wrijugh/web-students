# CSS Basics - Day 4

CSS is very powerful. Below example demonstrates how simple list element can be converted to a professional looking menu.

## Evolution of `<ul>` to Navigation Menu

```html
<ul>
    <li><a href="https://www.bbc.com/news">BBC</a></li>
    <li><a href="https://edition.cnn.com/">CNN</a></li>
    <li><a href="https://news.yahoo.com/">Yahoo</a></li>
    <li><a href="https://www.msn.com/en-us/news">MSN</a></li>
</ul>
```

```css
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 200px;
  background-color: #f1f1f1;
}

li a {
  display: block;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
}

/* Change the link color on hover */
li a:hover {
  background-color: #555;
  color: white;
}
```

## CSS Assignment #4

- Using the above CSS build a menu with 10 items. Open some of your favourite websites.
  
---

[Home Page](../README.md)

[Next: CSS Day 5 >>](05-css-day-04.md)
