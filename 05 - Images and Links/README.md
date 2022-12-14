# Images and Links

## Images
`<img>` tag used to embed images to HTML document.
The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.
The `<img>` tag has two required attributes:
  `src` - Specifies the path to the image
  `alt` - Specifies an alternate text for the image
The `src` path could be complete or relative.
When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.
The required `alt` attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).
If a browser cannot find an image, it will display the value of the `alt` attribute.
Screen readers also reads the content of the `alt` attribure when it reaches that part of the page.

## Links
- HTML links are hyperlinks.
- You can click on a link and jump to a different section of the document OR to another document.
- When you move the mouse over a link, the mouse arrow will turn into a little hand.
- The HTML <a> tag defines a hyperlink. It has the following syntax:
`<a href="url">link text</a>`
- By default, links will appear as follows in all browsers:
  1. An unvisited link is underlined and blue
  2. A visited link is underlined and purple
  3. An active link is underlined and red

- The `target` attribute specifies where to open the linked document and can have the following values:
  1. _self - Default. Opens the document in the same window/tab as it was clicked
  2. _blank - Opens the document in a new window or tab
  3. _parent - Opens the document in the parent frame
  4. _top - Opens the document in the full body of the window
Eg: `<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>`

