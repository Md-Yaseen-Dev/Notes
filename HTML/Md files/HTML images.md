# HTML Image

Images can improve the design and the appearance of a web page.

![Quotes](../Images/Quotefancy-82341-3840x2160.jpg)

__for example:-__

```html
<img>src ="../Images/Quotefancy-82341-3840x2160.jpg">
```

## HTML Images Syntax

Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image.

The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.

The `<img>` tag has two required attributes:

* src - Specifes the path to the image

* alt - specifes an alternate text for the image

__Syntax__

```html
<img src="url" alt="alternatetext">

```

## The src Attribute

The required src attribute specifies the path (URL) to the image.

**Note**: When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

__Example__

```html
<img src="img_chania.jpg" alt="Flowers in Chania">

```

## The alt Attribute

The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

__Example__

```html
<img src="img_chania.jpg" alt="Flowers in Chania">

```

## Image Size - Width and Height

You can use the style attribute to specify the width and height of an image.

__Example__

```html
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

```
Alternatively, you can use the width and height attributes


**Note**: Always specify the width and height of an image. If width and height are not specified, the web page might flicker while the image loads.

## Animated Images
 
 HTML allows animated GIFs:

__Example__

```html
<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">

```

## Image Floating

Use the CSS float property to let the image float to the right or to the left of a text:

__Example__

```html
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>

<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>

```