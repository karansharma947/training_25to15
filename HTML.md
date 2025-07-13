# 📘 Module 3: Introduction to HTML & Web Basics

## 🔹 Section 1: What is HTML and How Browsers Render It  
---

### ✅ What is HTML?

**HTML** stands for **HyperText Markup Language**. It is the **standard language** used to create the **structure** of web pages.

- **HyperText**: Refers to the use of hyperlinks that connect documents and web pages to each other.
- **Markup Language**: Uses tags to annotate or mark up elements within the text to define their structure and appearance.

HTML is **not a programming language**. It does not contain logic or loops like JavaScript or Python. Instead, it structures and labels content for the browser to interpret and render visually.

---

### ✅ How Browsers Render HTML

When you open a webpage in a browser (like Chrome, Firefox, Safari):

1. The browser **downloads the HTML file** from the server.
2. It **reads the HTML code line by line** from top to bottom.
3. It **parses the HTML** to create a structure called the **DOM** (Document Object Model).
4. The DOM is used by the browser to **render** the content (text, headings, images, links, etc.) on the screen.

#### 🧠 Example:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, Karan!</h1>
    <p>This is your first webpage.</p>
  </body>
</html>
#  HTML Tags: Headings, Paragraphs, Lists, Links, Images

This markdown file explains the most commonly used HTML tags.

---

## 🟢 1. Headings (`<h1>` to `<h6>`)

Headings are used to define titles and sub-titles. There are 6 levels from `<h1>` (most important) to `<h6>` (least important).

### 📌 Syntax:
```html
<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6</h6>
```

- Use only one `<h1>` per page for SEO.
- Helps organize content in a hierarchical structure.

---

## 🟢 2. Paragraphs (`<p>`)

The `<p>` tag defines a paragraph. Paragraphs are block-level elements and automatically add space above and below the content.

### 📌 Syntax:
```html
<p>This is a simple paragraph in HTML.</p>
<p>This is another paragraph below the first one.</p>
```

- Each paragraph starts on a new line.
- Avoid placing block elements like `<div>`, `<ul>`, etc., inside `<p>`.

---

## 🟢 3. Lists (`<ul>`, `<ol>`, `<li>`)

Lists are used to display items in a structured way. There are two main types: unordered (bulleted) and ordered (numbered).

### 🔹 Unordered List:
```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

- Displays items with bullets.
- Use when the order of items doesn't matter.

### 🔹 Ordered List:
```html
<ol>
  <li>Wake up</li>
  <li>Brush teeth</li>
  <li>Start coding</li>
</ol>
```

- Displays items with numbers.
- Use when the order of items matters.

### 🔹 Nested List:
```html
<ul>
  <li>Frontend
    <ul>
      <li>HTML</li>
      <li>CSS</li>
    </ul>
  </li>
  <li>Backend</li>
</ul>
```

- You can nest one list inside another.
- Use indentation for better readability.

---

## 🟢 4. Links (`<a>`)

The `<a>` tag is used to create hyperlinks. These can point to other websites, files, or locations on the same page.

### 📌 Syntax:
```html
<a href="https://www.google.com">Visit Google</a>
<a href="about.html" target="_blank" title="Open About Page">About</a>
```

- `href` defines the URL or file path.
- `target="_blank"` opens the link in a new tab.
- `title` shows a tooltip when hovered.

---

## 🟢 5. Images (`<img>`)

The `<img>` tag is used to embed images into a webpage. It is a self-closing tag.

### 📌 Syntax:
```html
<img src="profile.jpg" alt="My Photo" width="200" height="150">
```

- `src` is the source (path) to the image file.
- `alt` is the text shown if the image fails to load.
- `width` and `height` control the size of the image in px or %.

## 📋 Summary Table

| Tag         | Description                                  |
|-------------|----------------------------------------------|
| `<h1>`–`<h6>` | Headings, from largest to smallest           |
| `<p>`       | Paragraph text                               |
| `<ul>`      | Unordered list (bulleted)                    |
| `<ol>`      | Ordered list (numbered)                      |
| `<li>`      | List item (used inside `<ul>` or `<ol>`)     |
| `<a>`       | Hyperlink (anchor tag)                       |
| `<img>`     | Image embed tag                              |

# HTML Tags: Forms and Semantic HTML

This section explains how to use HTML forms, input types, and semantic HTML tags to structure web content properly.

---

## 🟢 1. Forms and Input Types (`<form>`, `<input>`, etc.)

The `<form>` tag is used to collect user input. Input fields are added using `<input>`, `<textarea>`, `<select>`, and other form elements.

### 📌 Basic Form Syntax:
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <label for="password">Password:</label>
  <input type="password" id="password" name="password">

  <input type="submit" value="Submit">
</form>
```

- `<form>` is the container for form elements.
- `action` defines where the form data will be sent.
- `method="post"` or `"get"` defines how the data will be sent.

---

### 🧩 Common `<input>` Types:
```html
<input type="text">       <!-- Single-line text field -->
<input type="email">      <!-- Email validation -->
<input type="password">   <!-- Password field (masked input) -->
<input type="number">     <!-- Numeric input -->
<input type="date">       <!-- Date picker -->
<input type="radio">      <!-- Radio button -->
<input type="checkbox">   <!-- Checkbox -->
<input type="submit">     <!-- Submit button -->
<input type="reset">      <!-- Reset form values -->
```

---

### 📋 Other Form Elements:
```html
<textarea></textarea>     <!-- Multi-line input -->
<select>                  <!-- Dropdown menu -->
  <option value="html">HTML</option>
  <option value="css">CSS</option>
</select>

<button type="button">Click Me</button>  <!-- Custom button -->
```

- `label` tags improve accessibility.
- Always use `name` attributes to send form data.

---

## 🟢 2. Semantic HTML Tags

Semantic tags clearly describe the meaning of the content inside them. They make the structure more meaningful to browsers, developers, and screen readers.

---

### 🔹 `<header>`
Defines the top section of a page or a section, usually containing logos or navigation.

```html
<header>
  <h1>My Website</h1>
  <p>Welcome to my portfolio</p>
</header>
```

---

### 🔹 `<footer>`
Defines the bottom section of a page, usually containing copyright, contact, or links.

```html
<footer>
  <p>&copy; 2025 MyWebsite. All rights reserved.</p>
</footer>
```

---

### 🔹 `<nav>`
Defines the navigation links for the website.

```html
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
```

---

### 🔹 `<section>`
Defines a thematic grouping of content, often with a heading.

```html
<section>
  <h2>Skills</h2>
  <p>I know HTML, CSS, JavaScript, and more.</p>
</section>
```

---

### 🔹 `<article>`
Defines self-contained content that can be independently reused or distributed.

```html
<article>
  <h2>Blog Post Title</h2>
  <p>This is the content of a blog post.</p>
</article>
```

---

## 📋 Summary Table
| Tag           | Description                                  |
|---------------|----------------------------------------------|
| `<form>`      | Defines a form to collect user input         |
| `<input>`     | Input field inside a form                    |
| `<textarea>`  | Multi-line text field                        |
| `<select>`    | Dropdown select menu                         |
| `<button>`    | Clickable button                             |
| `<header>`    | Top section of a page or content block       |
| `<footer>`    | Bottom section of a page                     |
| `<nav>`       | Contains site navigation links               |
| `<section>`   | Defines a content section                    |
| `<article>`   | Self-contained, reusable content             |

#  HTML Styling: Inline & Internal CSS + Multi-page Portfolio Website

This section covers how to style HTML elements using **inline** and **internal CSS**, and how to build a simple **multi-page personal portfolio website**.

---

## 🟢 1. Basic Styling using Inline and Internal CSS

CSS (Cascading Style Sheets) is used to style and design HTML pages.

---

### 🔹 Inline CSS

Inline CSS is written inside an HTML tag using the `style` attribute. It applies styles directly to that specific element.

#### 📌 Syntax:
```html
<p style="color: blue; font-size: 18px;">This is styled text using inline CSS.</p>
```

- Quick and easy for small changes.
- Not reusable — applies only to one element.
- Avoid using for larger projects.

---

### 🔹 Internal CSS

Internal CSS is written inside a `<style>` tag in the `<head>` section of an HTML document. It applies styles to multiple elements using selectors.

#### 📌 Syntax:
```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background-color: #f5f5f5;
    }
    h1 {
      color: darkgreen;
      text-align: center;
    }
    p {
      font-size: 16px;
      color: #333;
    }
  </style>
</head>
<body>
  <h1>Welcome to My Styled Page</h1>
  <p>This paragraph is styled using internal CSS.</p>
</body>
</html>
```

- More reusable than inline CSS.
- Good for small websites.
- Styles can be grouped and reused across elements.

---

## 📋 Summary Table

```md
| Type         | Description                                              | Where It Is Written              |
|--------------|----------------------------------------------------------|----------------------------------|
| Inline CSS   | CSS inside the `style` attribute of a tag                | Inside HTML tag (e.g., `<p>`)    |
| Internal CSS | CSS written in a `<style>` tag inside the `<head>` tag   | Head section of HTML document    |
```

---

## 🟢 2. Create a Personal Portfolio Website (Multi-Page)

A multi-page portfolio site includes **separate HTML files** for each section like Home, About, Projects, and Contact.

### 📂 Folder Structure:
```plaintext
/portfolio/
│
├── index.html        (Home page)
├── about.html        (About Me)
├── projects.html     (My Projects)
├── contact.html      (Contact Form)
└── images/
    └── profile.jpg
```

---

### 🔹 index.html (Home Page)
```html
<!DOCTYPE html>
<html>
<head>
  <title>Karan's Portfolio</title>
  <style>
    body { font-family: Arial; background-color: #fff0f5; }
    nav a { margin: 0 15px; text-decoration: none; color: #333; }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Portfolio</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="projects.html">Projects</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <p>Hello! I'm Karan, an aspiring web developer.</p>
</body>
</html>
```

---

### 🔹 about.html
```html
<!DOCTYPE html>
<html>
<head>
  <title>About Me</title>
</head>
<body>
  <h1>About Me</h1>
  <p>I love coding and creating meaningful websites using HTML, CSS, and JavaScript.</p>
  <a href="index.html">Back to Home</a>
</body>
</html>
```

---

### 🔹 projects.html
```html
<!DOCTYPE html>
<html>
<head>
  <title>Projects</title>
</head>
<body>
  <h1>My Projects</h1>
  <ul>
    <li>Food Delivery App (HTML + CSS)</li>
    <li>Personal Blog Website</li>
  </ul>
  <a href="index.html">Back to Home</a>
</body>
</html>
```

---

### 🔹 contact.html
```html
<!DOCTYPE html>
<html>
<head>
  <title>Contact Me</title>
</head>
<body>
  <h1>Contact Me</h1>
  <form action="/submit" method="post">
    <label>Name:</label>
    <input type="text" name="name"><br><br>
    <label>Email:</label>
    <input type="email" name="email"><br><br>
    <input type="submit" value="Send">
  </form>
  <a href="index.html">Back to Home</a>
</body>
</html>
```

---

## ✅ Tips to Improve Your Portfolio

- Use `<header>`, `<footer>`, `<nav>` for semantic layout.
- Use consistent navigation across all pages.
- Add a profile image using `<img src="images/profile.jpg">`
- Make links between pages using `<a href="about.html">About</a>`

---



