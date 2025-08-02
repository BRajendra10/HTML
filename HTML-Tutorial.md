Sure Rajendra! Here's a **detailed explanation** of each of your HTML interview questions:

---

### 1. **What is HTML?**

**HTML (HyperText Markup Language)** is the standard language used to create and structure web pages. It tells the browser **what content to display** and **how it's organized**. It uses elements (tags) to define parts of the page like headings, paragraphs, images, links, etc.

* **"HyperText"** refers to the ability to link to other pages.
* **"Markup Language"** means it uses tags to annotate text, images, and other content.

---

### 2. **What are tags in HTML?**

**Tags** are the basic building blocks of HTML. They define how elements on a web page behave or are displayed. Tags are enclosed in angle brackets:

```html
<p>This is a paragraph.</p>
```

* `<p>` is the **opening tag**
* `</p>` is the **closing tag**
* `This is a paragraph.` is the **content**

Some tags are **self-closing**, like `<img />` or `<br />`.

---

### 3. **What is the difference between HTML and HTML5?**

| Feature             | HTML                          | HTML5                                      |
| ------------------- | ----------------------------- | ------------------------------------------ |
| Version             | Older versions (HTML4, XHTML) | Latest version                             |
| Doctype Declaration | Long and complex              | Simple: `<!DOCTYPE html>`                  |
| Multimedia Support  | No built-in audio/video       | `<audio>` and `<video>` supported          |
| Semantic Tags       | Lacking                       | Has tags like `<article>`, `<nav>`         |
| Form Controls       | Limited types                 | New types: `date`, `range`, `email`        |
| Browser Storage     | Not supported                 | Supports `localStorage` & `sessionStorage` |

---

### 4. **What are semantic tags? Can you name a few?**

**Semantic tags** clearly define the **meaning of the content** inside them. They help screen readers, SEO tools, and developers understand the structure of the page.

Examples:

* `<header>` – for the top section or intro
* `<footer>` – for the bottom section
* `<article>` – for a self-contained block of content
* `<section>` – for grouping related content
* `<nav>` – for navigation links
* `<aside>` – for side content

**Non-semantic example:** `<div>` or `<span>` (they say nothing about their content)

---

### 5. **What is the purpose of `<!DOCTYPE html>`?**

The `<!DOCTYPE html>` declaration **informs the browser** about the HTML version used in the document. In HTML5, it’s written simply as:

```html
<!DOCTYPE html>
```

It helps browsers render the page **in standards-compliant mode** instead of quirks mode (which tries to mimic older behavior).

---

### 6. **What is the difference between `<div>` and `<span>`?**

| Feature    | `<div>`                           | `<span>`                        |
| ---------- | --------------------------------- | ------------------------------- |
| Type       | Block-level element               | Inline-level element            |
| Purpose    | Groups larger sections of content | Styles small chunks inside text |
| Line break | Starts on a new line              | Doesn’t break the line          |

Example:

```html
<div>This is a block element.</div>
<span>This is inline.</span>
```

---

### 7. **What is the use of `<meta>` tag?**

The `<meta>` tag provides **metadata** about the HTML document. Metadata is not displayed on the page but helps browsers and search engines understand it.

Examples:

```html
<meta charset="UTF-8"> <!-- Character encoding -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Rajendra's front-end portfolio">
```

---

### 8. **How do you add an image in HTML?**

You use the `<img>` tag, which is self-closing:

```html
<img src="image.jpg" alt="A description of the image" width="300" height="200" />
```

* `src` – path to the image
* `alt` – alternative text for screen readers or if the image fails to load
* `width` and `height` – optional for sizing

---

### 9. **What is the difference between id and class attributes?**

| Attribute | Use Case                             | Uniqueness     | Selector in CSS |
| --------- | ------------------------------------ | -------------- | --------------- |
| `id`      | Identify **a single unique** element | Must be unique | `#elementId`    |
| `class`   | Group **multiple elements**          | Can be reused  | `.className`    |

Example:

```html
<div id="header">Header</div>
<div class="box">Box 1</div>
<div class="box">Box 2</div>
```

---

### 10. **How do you create a hyperlink in HTML?**

You use the `<a>` (anchor) tag:

```html
<a href="https://example.com" target="_blank">Visit Website</a>
```

* `href` – the URL
* `target="_blank"` – opens the link in a new tab (optional)

---

### 11. **What is the use of the `alt` attribute in images?**

The `alt` attribute is used to:

* Show **descriptive text** when the image fails to load
* Help **screen readers** describe the image to visually impaired users
* Improve **SEO**

Example:

```html
<img src="logo.png" alt="Company Logo" />
```

If the image can’t load, the alt text appears in its place.

---

### 12. **What is a block-level vs inline-level element?**

| Type         | Block-level            | Inline-level                |
| ------------ | ---------------------- | --------------------------- |
| Layout       | Starts on a new line   | Flows with the text         |
| Width        | Takes full width       | Only as wide as its content |
| Example Tags | `<div>`, `<p>`, `<h1>` | `<span>`, `<a>`, `<strong>` |

---

### 13. **How do you embed a video or audio file in HTML?**

**For video:**

```html
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

**For audio:**

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

The `controls` attribute shows play/pause buttons.

---

### 14. **What is the purpose of the `<title>` tag?**

The `<title>` tag sets the **title of the web page** that appears in:

* The browser **tab**
* **Search engine results**
* **Bookmarks**

Example:

```html
<title>Rajendra's Portfolio</title>
```

It must be placed inside the `<head>` tag.

---

### 15. **What is the use of `<br>`, `<hr>`, and `<wbr>`?**

* **`<br>`** – Inserts a **line break**.

  ```html
  Hello<br>World
  ```

* **`<hr>`** – Adds a **horizontal line** (thematic break).

  ```html
  <hr>
  ```

* **`<wbr>`** – Suggests a **possible line break** point inside long words.

  ```html
  <p>Supercalifragilistic<wbr>expialidocious</p>
  ```

---
Absolutely Rajendra! Here’s a **detailed explanation** of all your intermediate-level HTML interview questions with real-world clarity:

---

### 1. **What are the differences between `<section>`, `<article>`, `<aside>`, and `<nav>`?**

All of these are **semantic tags** introduced in HTML5. Here's how they differ:

| Tag         | Purpose                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `<section>` | A logical **grouping of related content** under a theme or heading. Often used for page structure.                           |
| `<article>` | Represents **independent, self-contained content**, like blog posts or news articles. Can be shared/reused outside the page. |
| `<aside>`   | Represents **side content** like ads, tips, or related links—not core to the main content.                                   |
| `<nav>`     | Used for **navigation links**, menus, or tables of contents that help users navigate the site.                               |

Example:

```html
<article>
  <h2>Blog Post Title</h2>
  <p>Post content...</p>
</article>

<aside>
  <p>Related articles</p>
</aside>
```

---

### 2. **How do you make a table in HTML?**

A simple table includes rows (`<tr>`) and columns (`<td>`). Use `<th>` for header cells.

```html
<table border="1">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Rajendra</td>
      <td>22</td>
    </tr>
  </tbody>
</table>
```

---

### 3. **How can you create a form in HTML?**

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="username" required>

  <input type="submit" value="Submit">
</form>
```

* Use `<form>` to group form fields
* Inputs like `<input>`, `<textarea>`, `<select>`, `<button>` go inside

---

### 4. **Explain the purpose of `action` and `method` attributes in forms.**

* **`action`**: URL where the form data will be sent (e.g., `/register`, `api.php`)
* **`method`**: HTTP method:

  * `GET` – data goes in URL (used for search)
  * `POST` – data goes in the body (used for login, signup)

Example:

```html
<form action="/register" method="POST">
```

---

### 5. **What are `data-*` attributes in HTML5?**

`data-*` are custom attributes used to **store extra info** on elements without affecting layout or behavior.

Example:

```html
<button data-user-id="123" data-role="admin">Edit</button>
```

You can access them via JavaScript:

```js
button.dataset.userId // "123"
```

They’re helpful in JavaScript-heavy UIs (React, Vanilla JS, etc.).

---

### 6. **How do you disable autocomplete in a form field?**

Use the `autocomplete="off"` attribute:

```html
<input type="text" name="username" autocomplete="off">
```

It stops the browser from suggesting saved values.

---

### 7. **What is the `required` attribute in HTML forms?**

It makes a form input **mandatory** before submission. The browser will prevent submission if the field is empty.

Example:

```html
<input type="email" required>
```

You’ll see a browser validation popup if it’s empty.

---

### 8. **What are `localStorage`, `sessionStorage`, and cookies?**

These are used to **store data in the browser**:

| Feature           | `localStorage`         | `sessionStorage`          | `Cookies`                |
| ----------------- | ---------------------- | ------------------------- | ------------------------ |
| Lifespan          | Until manually cleared | Until tab/browser closed  | Set via expiration       |
| Size              | \~5MB                  | \~5MB                     | \~4KB                    |
| Sent with request | ❌ No                   | ❌ No                      | ✅ Yes, sent with HTTP    |
| Use case          | Save theme, token      | Tab-specific session data | Login sessions, tracking |

Example:

```js
localStorage.setItem("user", "Rajendra");
```

---

### 9. **How do you create a drop-down list in HTML?**

Use the `<select>` element with `<option>`s:

```html
<select name="country">
  <option value="india">India</option>
  <option value="usa">USA</option>
</select>
```

To select by default:

```html
<option selected>India</option>
```

---

### 10. **What’s the difference between `<button>` and `<input type="button">`?**

| Feature           | `<button>`                        | `<input type="button">`         |
| ----------------- | --------------------------------- | ------------------------------- |
| Flexibility       | Can have inner HTML, icons, spans | Only text via `value` attribute |
| Types             | `submit`, `reset`, `button`       | `button` only                   |
| Style and Control | More customizable                 | Limited styling                 |

Example:

```html
<button type="submit"><strong>Submit</strong></button>
<input type="button" value="Click Me">
```

---

### 11. **What is the difference between `<label for>` and wrapping `<label>` around input?**

Both associate a label with a form input, but the method differs:

✅ **With `for`**:

```html
<label for="email">Email:</label>
<input id="email" type="email">
```

✅ **Wrapping**:

```html
<label>Email: <input type="email"></label>
```

Both are valid and support accessibility. Using `for` is clearer for screen readers.

---

### 12. **Can a form have multiple submit buttons? How do you handle them?**

Yes, a form can have **multiple submit buttons**:

```html
<button type="submit" name="action" value="save">Save</button>
<button type="submit" name="action" value="delete">Delete</button>
```

In your backend (or JS), check the `action` value to know which button was clicked.

---

### 13. **What is the `<fieldset>` and `<legend>` tag used for?**

They’re used to **group related fields** in a form and provide a heading:

```html
<fieldset>
  <legend>Personal Info</legend>
  <label>Name: <input type="text"></label>
</fieldset>
```

* `<fieldset>`: groups the inputs visually and semantically
* `<legend>`: adds a title

This improves **form accessibility** and structure.

---

### 14. **What is placeholder? Can screen readers detect it?**

The `placeholder` attribute shows **temporary hint text** inside input fields:

```html
<input type="text" placeholder="Enter your name">
```

⚠️ Screen readers often **do not read** placeholder text. That’s why using `<label>` is essential for accessibility.

---

### 15. **How to create an accessible form?**

✅ Key practices:

* Always use **`<label>`** for each input
* Associate labels using `for` or wrapping
* Use **semantic tags** like `<fieldset>` and `<legend>`
* Provide clear **error messages**
* Use **`aria-*` attributes** where needed for assistive technologies
* Ensure good **contrast**, focus styles, and keyboard navigation
* Use `required`, `aria-required`, and proper `type` attributes

Example:

```html
<label for="email">Email:</label>
<input id="email" type="email" aria-required="true" required>
```

---

Let me know if you want to move on to **advanced HTML questions** next!

