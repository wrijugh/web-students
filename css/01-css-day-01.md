# CSS Basics - Day 1

**CSS** stands for *Cascading Style Sheet*. This is to make HTML look beautiful in an inteligent way.  

## How Style Works

If we need to format `<p>` with color brown we may use something like this,

```html
<p style="color: brown;">Paragraph 1</p>
```

## How CSS Can be defined

Now if there are more than one `<p>` tags then you have to write this again and again. To avoid this we use CSS. CSS styles are defined within `<style>` tag.

```html
<style>
    p {color: blue;}
</style>
```

The above will apply styles to all the `<p>` tags which does not have `style` attribute defined inside.

## Selectors

CSS Selectors are key here. In above example it used the tag type `p` here to identify all the `<p>` tags. But in case we want not to modify generic all tags. You can apply to one element or set of elements. Selectors are key here,

## Apply to all Elements

```css
p {color: blue;}
```

## By Id

This will only apply to the element with id `p2`

```html
<p id="p2">Paragraph 2</p>

<style>
    #p2 {color: blue;}
</style>
```

## By Class

```html
<p id="p2">Paragraph 2</p>

<p id="p3" class="blueclass">Paragraph 3</p>

<p id="p4" class="blueclass">Paragraph 4</p>

<style>
    .blueclass {color: blue;}
</style>
```

The above will apply to pnly *paragraph 3* and *paragraph 4*

## By Class and element

But if you have same class in two different types of elements say `<p>` and `<h1>` then just by using the class selector it will be implemented in all the elements with that class name. To avoid in the CSS definition you can add the `element.classname' format as below,

```html
<p id="p2">This is the paragraph 2</p>

<p id="p3" class="blueclass">This is the paragraph 3</p>

<p id="p4" class="blueclass">This is the paragraph 4</p>

<h1 class="blueclass">This is the paragraph 4</h1>

<style>
    p.blueclass {color: blue;}
    h1.blueclass {color:blueviolet;}
</style>
```

If the above did not have `p.` or `h1.` then it would applied to both `<p>` and `<h1>`. Now there will be two different colors even if they have the same class name i.e., `blueclass`

## Commenting

Commenting in CSS is done via 

```css
/* commment here  */
```

## External file

CSS styles can come from an external file. 

## CSS Assignment #1

- Create six different color styles for six differnet header i.e., `<h1>` to `<h6>`
- Use class attibute of `<p>` to color differently.

---

[Home Page](../README.md)

[Next: CSS Day 2 >>](02-css-day-02.md)