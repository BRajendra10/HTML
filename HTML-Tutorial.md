# HTML

## HTML intro

HTML is the standard markup language for creating Web pages.

### What is HTML?

- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

### Questions

1. What is a html tag?
   An HTML tag is a special keyword enclosed in angle brackets (< >) that tells the browser how to display content on a web page.

2. What is a html eliment?
   An HTML element is the building block of a webpage. It defines the structure and content on a website using opening and closing tags.

```
    // html tag & eliment

    <p>Hello, world!</p>

    // <p> is the opening tag
    // Hello, world! is the content
    // </p> is the closing tag
```

3. Basic structure of html page.

```
    <!DOCTYPE html>
    // The <!DOCTYPE html>, It tells the browser what version of HTML the page is written in, so the browser can render it correctly.
    <html>
    // The root element of an HTML document. It wraps everything in your HTML file
        <head>
        // Contains metadata (data about the page) like the title, CSS links, meta tags, scripts, etc. It’s not visible on the web page.
            <title>My Page</title> // Sets the page title shown in the browser tab.
        </head>
        <body>
        // Holds everything you see on the page: text, images, buttons, links, etc.
            <p>Hello, world!</p>
        </body>
    </html>
```
