# CSS Basics - Day 7

CSS can and should be added in a seperate file from the working Html file. That way the html would look clean.

**style.css**

```css
p {
    margin: 20%;
    border: 1px solid blue;
    border-radius: 50%;
    height: 200px;
    width: 200px;
}    

```

**home.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>    
    <title>CSS in Seperate file</title>
    <link rel="stylesheet" href="./styles/styles.css" >
</head>
<body>
    <div>
        <p>WW</p>
    </div>
</body>
</html>
```

## CSS Assignment #7

- Get back to you previous work on css and move all the css in seperate file in the same folder as `styles.css`. Then add a reference.

---

[Home Page](../README.md)

[Next: JavaScript Day 1 >>](./../javascript/01-js-day-01.md)
