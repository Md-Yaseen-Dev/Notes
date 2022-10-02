# HTML  CSS

CSS stands for Cascading Style Sheets.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

## What is CSS?

Cascading Style sheets is used to format the layout of a webpage.

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are postioned and laid out, what background images or background colors are to be used, different displays for different devices and screens sizes, and much more!

---
**Tip:** The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!

---

## Using CSS

CSS can be added to HTML documents in 3 ways:

*  **Inline -** by using the style attribute inside HTML elements
*  **Internal -** by using a `<style>` element in the  `<head>` section

* **External -** by using a `<link` element to link to an external CSS file.

The most common way to add CSS, is to keep the styles in external CSS files. However, in this tutorial we will use inline and internal styles, because this is easier to demonstrate, and easier for you to try it yourself.

## Inline CSS

An inline CSS is used to apply a unique style to a single HTML element.

An inline CSS uses the style attribute of an HTML element.

The following example sets the text color of the `<h1>` element to blue, and the text color of the `<p> `element to red:

__for Example:-__

```html
<h1 style="color:blue;">A Blue Heading</h1>

<p style="color:red;">A red paragraph.</p>

```

## Internal CSS

An internal CSS is used to define a style for a single HTML Page.

An internal CSS is defined in the `<head>` section of an HTML page, within a `<style>` element.


The following example sets the text color of ALL the `<h1>` elements (on that page) to blue, and the text color of ALL the `<p>` elements to red. In addition, the page will be displayed with a "powderblue" background color: 

__for Example:-__

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

```

## CSS Colors, font and sizes

Here, we will demonstrate some commonly used CSS properties. You will learn more about them later.


The CSS color property defines the text color to be used.

The CSS font-family property defines the font to be used.

The CSS font-size property defines the text size to be used.

__for Example:-__

Use of CSS color,font-family and font-size properties:

```html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

```

## CSS Border

The CSS border property defines a border around an HTML element.

Tip: You can define a border for nearly all HTML elements.

__for Example:-__

Use of CSS border property:

```html
p {
  border: 2px solid powderblue;
}

```
## CSS padding

The Css  padding property defines a padding(spaces) between the text and the border.

__for Example:-__

Use of css border and padding properties:

```html
<Style>
p {
  border: 2px solid powderblue;
  padding: 30px;
}
</style>

```

## CSS Margin

The CSS margin property defines a margin (spaces) outisde the border.

__for Example:-__

Use of CSS border and margin properties:

```html
<style>
p {
  border: 2px solid powderblue;
  margin: 50px;
}
</style>

```
## link to External CSS

External style sheets can be referenced with a full URL or with a path relative to the current web page.

__for example:-__

This example uses a full URL to link to a style sheet:

```html
<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">

```

## Chapter Summary

* Use the HTML style attribute for  inline styling
* Use the HTML `<style>`element to define internal CSS
* Use the HTML `<link>` element to refer to an external CSS file

* Use the HTML`<head>` element to store `<style>` and `<link>` elements

* Use the CSS color property for text colors

* Use the CSS font-family property for text fonts

* Use the CSS font-size property for text sizes

* Use the CSS border property for borders

* Use the CSS padding property for space inside the border

* Use the CSS margin property for space outside the border


