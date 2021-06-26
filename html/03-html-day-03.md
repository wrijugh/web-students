# HTML Basics - Day 3

List and table

## List and Tables  

| Tag |   Purpose |
|-----|:----------|
| `<ul>` | list unordered - no serial number |
| `<ol>` | serial numbered list, you can also use few attribues to control the sequence (reverse), starting using `start` number etc. |
| `<li>` | list item to be used inside `<ul>` or `<ol>`|
| `<table>` | create row column like class routine |
| `<th>` | header of a `<table>` |
| `<tr>` | row of the `<table>` |
| `<td>` | cell of a `<tr>` |
| `<span>` | section like inside `<p>` |
| `<div>` | more magic here |
| `<header>` | for header |
| `<footer>` | for footer |

## List

```html
<p>No Serial</p>
<ul>
    <li>India</li>
    <li>Nepal</li>
    <li>Sri Lanka</li>
    <li>Bhutan</li>
</ul>

<p>Numbered</p>
<ol>
    <li>India</li>
    <li>Nepal</li>
    <li>Sri Lanka</li>
    <li>Bhutan</li>
</ol>
```

## Table

```html
<table border="1">
    <th>
        <td>Monday</td>
        <td>Tuesday</td>
        <td>Sunday</td>
    </th>
    <tr>
        <td></td>
        <td>Maths</td>
        <td>Science</td>
        <td>Literature</td>
    </tr>
</table>
```

> **Note:** Explore `<div>` tag. Div is a modern approach to table.

## Assignment #3

- Build your class routine in HTML Table.
- Make a list of favourite people as List.
- Make a serial list of grocery items to buy.
- Explore few additional tags about table like `<caption>`, `<colgroup>`, `<thead>`, `<tfoot>` and `<tbody>`

---

[Home Page](../README.md)

[Next: HTML Day 4 >>](04-html-day-04.md)
