# Class-02 Readings
## 1. HTML 
### Headings
  ``` 
  Headings are defined with the <h1> to <h6> tags.
  <h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

```

### Paragraph
```
The HTML <p> element defines a paragraph,
The HTML <br> element defines a line break.
<!DOCTYPE html>
<html>
<body>

<p>This is a paragraph.</p>
<br>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
</html>

```
### Formating Elements

```
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Small text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```

### Quotations
```
The HTML <q> element defines a short quotation.

Browsers usually insert quotation marks around the <q> element.

<p>Browsers usually insert quotation marks around the q element.</p>

<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

```

## 2. CSS
CSS is a language that describes the style of an HTML document.

CSS describes how HTML elements should be displayed.

This tutorial will teach you CSS from basic to advanced.

### Syntax

![syntax](https://www.w3schools.com/css/selector.gif)

Example
```
p {
  color: red;
  text-align: center;
} 
```

### Selectors
All CSS Simple Selectors
|Selector	|Example	|Example description |
|---|:---|:---|
|.class	|.intro	|Selects all elements with class="intro" |
|#id	|#firstname	|Selects the element with id="firstname"|
|*	|*	|Selects all elements|
|element	|p	|Selects all <p> elements|
|element,element,..	|div, p	|Selects all <div> elements and all <p> elements|

### Three Ways to Insert CSS
There are three ways of inserting a style sheet:

- External CSS
```
<link rel="stylesheet" type="text/css" href="mystyle.css">
```
- Internal CSS
```
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
} 
</style>
```
- Inline CSS
```
<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```

## 3.JavaScript
