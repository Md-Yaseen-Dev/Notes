# HTML Javascript

Javascript makes HTML pages more dynamic and interactive

__Example__

```javascript
<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

```

## The HTML `<script>` Tag

The HTML `<script>` tag is used to define a client-side script (JavaScript).

The `<script>` element either contains script statements, or it points to an external script file through the src attribute.

Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content.

To select an HTML element, JavaScript most often uses the document.getElementById() method.

This JavaScript example writes "Hello JavaScript!" into an HTML element with id="demo":

__Example__

```javascript
<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>

```

## A Taste of JavaScript

Here are some examples of what JavaScript can do:

__Example__

JavaScript can change content:

```javascript
<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>

<p>JavaScript can change the content of an HTML element:</p>

<button type="button" onclick="myFunction()">Click Me!</button>

<p id="demo">This is a demonstration.</p>

<script>
function myFunction() { 
  document.getElementById("demo").innerHTML = "Hello JavaScript!";
}
</script>

</body>
</html>

```

## The HTML `<noscript>` Tag

The HTML `<noscript>` tag defines an alternate content to be displayed to users that have disabled scripts in their browser or have a browser that doesn't support scripts:

__Example__

```javascript
<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>
<noscript>Sorry, your browser does not support JavaScript!</noscript>

```
