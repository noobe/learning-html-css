# Basic HTML File

- A basic HTML file consists of the following content:
```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>
  Hello HTML
</body>
</html>
```
## DOCTYPE
The file starts with the doctype declaration that specifies the doctype version to which the content corresponds to. The latest doctype is HTML5 and it can be specified using `<!DOCTYPE html>`

## TAGS
- This is followed by the a bunch of HTML tags. HTML tags are pre-defined strings that comes enclosed in angular brackets `<` & `>`.

- An html tag usually comes as a self closing tag or as a pair of opening and closing tag that can enclose content between them. Eg:
  1. Self closing: `<br />`
  2. Opening and closing pairs: `<head></head>`
  3. Opening and closing pairs with content enclosed: `<html> ... </html>`

- In the above example, the structure of a basic HTML document is shown:
  1. `Doctype` declaration
  2. `HTML` tag to encapsulate the whole page content
  3. `HEAD` tag to encapsulate specifications about the page (which does not appear on the actual page in the browser).
  4. `BODY` tag that contains content that finally gets rendered on the page.