# Boilerplate Template
A full HTML page template would look like:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  Hello HTML
</body>
</html>
```

`lang="en"` on the HTML tag is a global attribute that helps define the language of an element: the language that non-editable elements are written in, or the language that the editable elements should be written in by the user.

`<meta>` tag represents metadata that cannot be represented by other HTML meta-related elements, like <base>, <link>, <script>, <style> or <title>.

`<meta charset="UTF-8">` defines the character encoding format followed. An encoding defines a mapping between bytes and text. A sequence of bytes allows for different textual interpretations. By specifying a particular encoding (such as UTF-8), we specify how the sequence of bytes is to be interpreted. This ensures that you can use characters from just about any human language in your HTML document, and they will display reliably.

`<meta http-equiv="X-UA-Compatible" content="IE=edge">` meta tag allows web authors to choose what version of Internet Explorer the page should be rendered as.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">` This gives the browser instructions on how to control the page's dimensions and scaling. The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device). The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser. 

`<title>Document</title>` Specifies the page title that appears on the browser tab.
