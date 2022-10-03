# HTML-The Head Element

The HTML `<head>` element is a container for the following elements: `<title`, `<style`, `<meta>`, `<link>`, `<script>`, and `<base>`.

## The HTML `<head>` Element

The `<head` element is a container for metadata and is placed between the `<html>` tag and the `<body>` tag.

HTML metadata is data about the HTML document. Metadata is not displayed.

Metadata typically define the document title, character set, styles, scripts, and other meta information.

## The HTML `<title>` Element

The `<title>` element defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.

The `<title>` element is required in HTML documents!

The content of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search results.

The `<title>` element:

* defines a title in the browser toolbar
 
* provides a title for the page when it is added to favorites

* displays a title for the page in search engine-results

__Example__

```html
<!DOCTYPE html>
<html>
<head>
  <title>A Meaningful Page Title</title>
</head>
<body>

The content of the document......

</body>
</html>
```

## The HTML `<style>` Element

The `<style>` element is used to define style information for a single HTML page:

__Example__

```html
<style>
  body {background-color: powderblue;}
  h1 {color: red;}
  p {color: blue;}
</style>

```

## The HTML `<link>` Element

The `<link>` element defines the relationship between the current document and an external resource.

The `<link>` tag is most often used to link to external style sheets:

__Example__

```html
<link rel="stylesheet" href="mystyle.css">

```

## The HTML `<meta>` Element

The `<meta>` element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.

The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.


__Examples__

```html
<meta charset="UTF-8">

```

## The HTML `<script>` Element

The `<script>` element is used to define client-side JavaScripts.

The following JavaScript writes "Hello JavaScript!" into an HTML element with id="demo":


__Example__

```html
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello JavaScript!";
}
</script>

```

## The HTML <base> Element

The `<base>` element specifies the base URL and/or target for all relative URLs in a page.

The `<base>` tag must have either an href or a target attribute present, or both.

There can only be one single `<base>` element in a document!

__Example__

```html
<head>
<base href="https://www.w3schools.com/" target="_blank">
</head>

<body>
<img src="images/stickman.gif" width="24" height="39" alt="Stickman">
<a href="tags/tag_base.asp">HTML base Tag</a>
</body>

```
