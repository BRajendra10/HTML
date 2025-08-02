## ✅ Full HTML Interview Questions with Detailed Answers

### 🔰 BASIC HTML INTERVIEW QUESTIONS

---

### 1. **What is HTML?**

HTML (HyperText Markup Language) is the standard markup language used to create the structure of web pages. It describes the layout of a web document using tags and elements. HTML works alongside CSS (for design) and JavaScript (for interactivity) to build complete websites.

**Key Features:**

* Uses elements/tags to wrap content
* Represents text, images, links, forms, etc.
* Platform-independent and browser-supported

**Example:**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
  </body>
</html>
```

---

### 2. **What are tags in HTML?**

HTML tags are predefined keywords enclosed in angle brackets that tell the browser how to render content. Tags usually come in pairs — an opening tag (e.g., `<p>`) and a closing tag (e.g., `</p>`), with the content between them. Some tags like `<img>` or `<br>` are self-closing.

**Example:**

```html
<p>This is a paragraph</p>
<img src="image.jpg" alt="A sample image">
```

---

### 3. **What is the difference between HTML and HTML5?**

HTML5 is the latest version of HTML with new features, simplified syntax, and better support for multimedia and mobile devices.

**HTML vs HTML5:**

* **HTML:** No native support for video/audio, older structure
* **HTML5:** Introduced semantic tags (`<header>`, `<footer>`), native multimedia (`<audio>`, `<video>`), better form elements, and `localStorage`

**Example HTML5 declaration:**

```html
<!DOCTYPE html>
```

---

### 4. **What are semantic tags?**

Semantic HTML tags describe the meaning of the content inside them. These tags improve code readability, SEO, and accessibility.

**Examples:**

* `<article>`: Self-contained content
* `<section>`: A standalone section
* `<nav>`: Navigation links
* `<footer>`: Footer content

**Non-semantic vs Semantic:**

* Non-semantic: `<div>`, `<span>`
* Semantic: `<main>`, `<aside>`, `<header>`

---

### 5. **What is the purpose of `<!DOCTYPE html>`?**

The `<!DOCTYPE html>` declaration tells the browser that the document uses HTML5. It helps ensure the page is rendered in standards-compliant mode.

**Why important?**

* Prevents browsers from switching to quirks mode
* Ensures consistency across browsers

**Example:**

```html
<!DOCTYPE html>
```

---

### 6. **What is the difference between `<div>` and `<span>`?**

Both are container elements but differ in display and usage:

* `<div>`: Block-level, used for larger layout structures
* `<span>`: Inline-level, used for wrapping inline content like text

**Example:**

```html
<div class="card">Content block</div>
<p>This is <span class="highlight">important</span> text.</p>
```

---

### 7. **What is the use of the `<meta>` tag?**

The `<meta>` tag provides metadata about an HTML document such as character encoding, author, keywords, and viewport settings. It is placed inside the `<head>` section.

**Common usages:**

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="HTML Interview Questions">
```

---

### 8. **How do you add an image in HTML?**

Use the `<img>` tag to embed an image. It’s a self-closing tag that requires at least a `src` and `alt` attribute.

**Example:**

```html
<img src="logo.png" alt="Company Logo" width="200" height="100">
```

* `src`: path to the image
* `alt`: alternative description
* `width/height`: optional dimensions

---

### 9. **What is the difference between `id` and `class` in HTML?**

Both are used to target elements for CSS or JavaScript, but they differ in scope and usage:

* `id`: Unique identifier, used for one element only
* `class`: Reusable, can be applied to multiple elements

**Example:**

```html
<div id="header"></div>
<div class="card"></div>
```

---

### 10. **How do you create a hyperlink in HTML?**

Use the `<a>` (anchor) tag to create links.

**Example:**

```html
<a href="https://example.com" target="_blank">Visit Example</a>
```

* `href`: target URL
* `target="_blank"`: opens in a new tab
* `rel="noopener noreferrer"`: improves security when opening new tabs

---

---

### 11. **What is the use of the `alt` attribute in images?**

The `alt` attribute (alternative text) is used in the `<img>` tag to provide a textual description of the image. This text is displayed when the image cannot be loaded, and it's used by screen readers to help visually impaired users understand what the image represents.

**Benefits:**

* Improves accessibility (screen readers read the alt text)
* Helps with SEO (search engines index alt text)
* Provides fallback content

Example:

```html
<img src="cat.jpg" alt="A cute orange cat sitting on a sofa">
```

---

### 12. **What is a block-level vs inline-level element?**

Block-level and inline-level elements behave differently in layout.

**Block-level elements:**

* Start on a new line
* Take up full width available
* Can contain inline or other block elements
* Examples: `<div>`, `<p>`, `<section>`, `<article>`

**Inline-level elements:**

* Do not start on a new line
* Take up only as much width as necessary
* Cannot contain block elements
* Examples: `<span>`, `<a>`, `<strong>`, `<em>`

Understanding this difference helps when structuring layout and styling with CSS.

---

### 13. **How do you embed a video or audio file in HTML?**

HTML5 provides built-in tags to embed media:

**Video:**

```html
<video width="400" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

**Audio:**

```html
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```

Attributes like `controls`, `autoplay`, `loop`, and `muted` enhance behavior.

---

### 14. **What is the purpose of the `<title>` tag?**

The `<title>` tag defines the title of the HTML document, which appears in the browser tab and is used by search engines when indexing.

**Example:**

```html
<title>Portfolio - Rajendra Behera</title>
```

**Purpose:**

* Displayed in browser title bar or tab
* Used by search engines in SERPs (search engine results pages)
* Crucial for accessibility and SEO

---

### 15. **What is the use of `<br>`, `<hr>`, and `<wbr>`?**

These are void (self-closing) elements that control text flow:

* `<br>`: Inserts a line break, similar to pressing Enter.

  ```html
  Hello<br>World
  ```
* `<hr>`: Inserts a horizontal rule (line), usually used to separate content.

  ```html
  <hr>
  ```
* `<wbr>`: Suggests a possible line break point inside a word (especially useful for long URLs or strings).

  ```html
  verylongword<wbr>breakingpoint
  ```

---

(Next: Intermediate HTML Questions with detailed answers...)
