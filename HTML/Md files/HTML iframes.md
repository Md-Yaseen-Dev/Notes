# HTML IFrames

An HTML iframe is used to display a web page within a web page.

![iframe](https://github.githubassets.com/pinned-octocat.svg)


## HTML Iframe Syntax

The HTML `<iframe>` tag specifies an inline frame.

An inline frame is used to embed another document within the current HTML document.

__Syntax__

```html
<iframe src="url" title="description"></iframe>

```
**Note:** It is a good practice to always include a title attribute for the `<iframe>`. This is used by screen readers to read out what the content of the iframe is.


## Iframe - Set Height and Width

Use the height and width attributes to specify the size of the iframe.

The height and width are specified in pixels by default:
__Example__

```html
<iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"></iframe>
```

## Iframe - Remove the Border

By default, an iframe has a border around it.

To remove the border, add the style attribute and use the CSS border property:

__Example__

```html
<iframe src="demo_iframe.htm" style="border:none;" title="Iframe Example"></iframe>

```

## Iframe - Target for a Link


An iframe can be used as the target frame for a link.

The target attribute of the link must refer to the name attribute of the iframe:


__Example__

```html

<iframe src="demo_iframe.htm" name="iframe_a" title="Iframe Example"></iframe>

<p><a href="https://www.w3schools.com" target="iframe_a">W3Schools.com</a></p>
```

## To know more about iframes click the link below

[Iframe Target](http://127.0.0.1:5500/HTML%20TUTORIAL/HTML%20Iframes/Iframe-Target%20a%20link.html)


## TO know more about iframe coding click the link below
[github-iframes](https://github.com/mohammedyaseen2211/--Markdown-Course/tree/master/HTML%20TUTORIAL/HTML%20Iframes)