# HTML Roadmap 🚀  

Welcome to Day 1 of your HTML learning journey! This guide will introduce you to the foundational concepts of web design and development. By the end of the day, you’ll understand HTML basics and its essential role in creating web pages. Let’s dive in! 🌟  

---

## 📖 Overview of Web Design and Development  

Web design and development is all about creating visually appealing and functional websites. A good website is:  
- **User-friendly** 🎯  
- **Responsive** 📱  
- **Accessible** ♿  
- **Well-structured** 🏗️  

Web development is divided into two key areas:  
1. **Frontend Development** (What users see 👀)  
2. **Backend Development** (How it works behind the scenes ⚙️)  

HTML is the backbone of frontend development! 💪  

---

## 🌐 Understanding Web Standards and Technologies  

- **Web Standards**: Guidelines to ensure websites are accessible, responsive, and compatible across all devices and browsers.  
- **Core Technologies**:  
  - **HTML** (Structure 🧱)  
  - **CSS** (Style 🎨)  
  - **JavaScript** (Interactivity 🎮)  

---

## 🛠️ Introduction to the Course Project  

We’ll create a **simple portfolio webpage** by the end of this course! 💼  
- Showcasing your skills, projects, and contact details.  
- Building blocks: **HTML**, **CSS**, and some **JavaScript**.  

---

## ✍️ Introduction to HTML  

HTML stands for **HyperText Markup Language**. It provides the **structure** of a webpage. Think of it as the **skeleton** of a website! 💀  

### Why HTML?  
- It defines headings, paragraphs, links, images, and more.  
- It’s the first step in building a website.  

---

## 🏗️ Basic Structure of an HTML Document  

Here’s the basic structure of an HTML document:  

```html  
<!DOCTYPE html>  
<html>  
<head>  
    <title>My First Web Page</title>  
</head>  
<body>  
    <h1>Welcome to HTML!</h1>  
    <p>This is the start of your web development journey. 🚀</p>  
</body>  
</html>  
```  

---

## 🏷️ Introduction to HTML Tags  

HTML is made up of **tags**, which are used to define elements on a page.  
### Types of Tags:  
1. **Block Elements** 🟦  
   - Occupy the entire width of their container.  
   - Examples: `<div>`, `<p>`, `<h1>` to `<h6>`.  
2. **Inline Elements** ➡️  
   - Occupy only the necessary width.  
   - Examples: `<span>`, `<a>`, `<img>`.


| **Type**       | **Element**           | **Description**                                                                                     | **Example Code**                      |  
|----------------|-----------------------|-----------------------------------------------------------------------------------------------------|---------------------------------------|  
| **Block**      | `<div>`               | A generic container used for grouping content. Takes up the full width of its container.            | `<div>Content</div>`                  |  
| **Block**      | `<p>`                 | Represents a paragraph. Automatically adds spacing before and after the text.                       | `<p>This is a paragraph.</p>`         |  
| **Block**      | `<h1>` to `<h6>`      | Defines headings, with `<h1>` being the largest and `<h6>` the smallest.                            | `<h1>Heading 1</h1>`                  |  
| **Block**      | `<ul>` and `<ol>`     | `<ul>` creates unordered lists; `<ol>` creates ordered lists.                                       | `<ul><li>Item 1</li></ul>`            |  
| **Block**      | `<table>`             | Creates a table to organize data into rows and columns.                                             | `<table><tr><td>Cell</td></tr></table>`|  
| **Inline**     | `<span>`              | A generic inline container used for styling a part of text or grouping small elements.              | `<span>Styled text</span>`            |  
| **Inline**     | `<a>`                 | Creates hyperlinks to other pages, files, or external resources.                                    | `<a href="url">Link</a>`              |  
| **Inline**     | `<img>`               | Embeds images into the webpage.                                                                    | `<img src="image.jpg" alt="Image">`   |  
| **Inline**     | `<strong>`            | Adds semantic importance, typically displayed as bold text.                                         | `<strong>Important</strong>`          |  
| **Inline**     | `<em>`                | Adds semantic emphasis, typically displayed as italic text.                                         | `<em>Emphasized</em>`                 |  

---

### Key Differences  
1. **Block Elements**:  
   - Always start on a new line.  
   - Take up the full width of their container.  
   - Useful for layout and structure.  

2. **Inline Elements**:  
   - Flow inline with text.  
   - Occupy only as much width as necessary.  
   - Used for styling or small content pieces.  



### **1. Formatting Text with Tags**  
HTML provides various tags to format text.  

#### Examples:
```html
<p>This is a paragraph.</p>  
<strong>This text is bold.</strong>  
<em>This text is italicized.</em>  
<mark>This text is highlighted.</mark>
```

#### Output:
- **Paragraph**: Appears as regular text in a block.  
- **Bold**: Text is displayed in bold.  
- **Italic**: Text is italicized.  
- **Highlighted**: Text appears with a background highlight.  

---

### **2. Working with Text Attributes (id, class, style)**  
Attributes add functionality or styles to HTML elements.  

#### Examples:
```html
<p id="intro">This paragraph has an ID.</p>  
<p class="highlight">This paragraph has a class for styling.</p>  
<p style="color: blue; font-size: 18px;">This paragraph has inline styles.</p>
```

#### Output:
- Text can be uniquely identified with an ID.  
- Multiple elements can share the same class for styling.  
- Inline styles can directly style elements.  

---

### **3. Semantic HTML Tags**  
Semantic tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` improve readability and SEO.  

#### Examples:
```html
<header>
  <h1>Welcome to My Website</h1>
</header>
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
  </ul>
</nav>
<main>
  <section>
    <article>
      <h2>Article Title</h2>
      <p>Article content goes here.</p>
    </article>
  </section>
</main>
<footer>
  <p>Copyright © 2024</p>
</footer>
```

#### Benefits:
- Enhances accessibility.  
- Improves SEO by structuring content meaningfully.  

---

### **4. Creating Ordered and Unordered Lists**  
Lists organize content using `<ul>` (unordered) or `<ol>` (ordered).  

#### Examples:
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

#### Output:
- **Unordered List**: Bulleted items.  
- **Ordered List**: Numbered steps.  

---

### **5. Nested Lists and List Attributes**  
Lists can be nested inside each other.  

#### Example:
```html
<ul>
  <li>Item 1
    <ul>
      <li>Subitem 1.1</li>
      <li>Subitem 1.2</li>
    </ul>
  </li>
  <li>Item 2</li>
</ul>
```

#### Output:
- Nested lists display subitems indented under main items.  

---

### **6. Creating Hyperlinks with Anchor Tags**  
Anchor tags `<a>` create links to other pages, sections, or resources.  

#### Examples:
```html
<a href="https://www.example.com" target="_blank" rel="noopener">Visit Example</a>  
<a href="#section1">Jump to Section 1</a>
```

#### Output:
- **Target="_blank"**: Opens the link in a new tab.  
- **Rel="noopener"**: Improves security for external links.  

---

### **7. Inserting Images and Image Attributes**  
The `<img>` tag embeds images and uses attributes for customization.  

#### Examples:
```html
<img src="example.jpg" alt="Example Image" width="300" height="200">
```

#### Output:
- **Src**: Specifies the image file.  
- **Alt**: Describes the image for accessibility.  
- **Width/Height**: Defines dimensions.  

---

### **Summary**  
Here’s a quick recap of the covered topics:  
1. **Formatting Text**: Use tags like `<p>`, `<strong>`, `<em>`, `<mark>` for text styling.  
2. **Text Attributes**: Add attributes like `id`, `class`, and `style` to customize elements.  
3. **Semantic Tags**: Use `<header>`, `<nav>`, `<main>`, etc., for structure and SEO benefits.  
4. **Lists**: Organize data with `<ul>` and `<ol>`; nest lists as needed.  
5. **Hyperlinks**: Create navigation with `<a>` tags.  
6. **Images**: Insert and customize images with `<img>`.  

# **Inserting Images in HTML**  

The `<img>` tag is used to embed images into a webpage. It is a self-closing tag and requires specific attributes to work effectively.

---

### **Key Attributes of the `<img>` Tag**  
1. **`src` (Source)**: Specifies the path to the image file.  
   - It can be an absolute URL (e.g., `https://example.com/image.jpg`) or a relative path (e.g., `images/photo.jpg`).  

2. **`alt` (Alternative Text)**: Provides a text description for the image.  
   - Useful for accessibility (screen readers) and when the image fails to load.  

3. **`width` and `height`**: Define the dimensions of the image.  
   - Can be set in pixels (`px`) or percentages (`%`).  

---

### **Example 1: Basic Image Tag**  
```html
<img src="image.jpg" alt="Beautiful Landscape" width="600" height="400">
```

#### Explanation:
- `src`: The image file is located in the same folder.  
- `alt`: Displays "Beautiful Landscape" if the image doesn’t load.  
- `width` & `height`: Set the size of the image to 600px by 400px.

---

### **Example 2: Using External Image URL**  
```html
<img src="https://via.placeholder.com/300" alt="Placeholder Image" width="300" height="300">
```

#### Output:  
- Displays a placeholder image with 300px width and height.

---

### **Example 3: Responsive Images (Only Width)**  
```html
<img src="responsive.jpg" alt="Responsive Design" width="100%">
```

#### Explanation:
- Setting the width to `100%` makes the image scale to fit its container, ensuring responsiveness.  

---

### **Example 4: Decorative Images**  
For purely decorative images, you can leave the `alt` attribute empty to indicate they do not need a description:  
```html
<img src="decorative.png" alt="" width="200" height="200">
```

---

### **Example 5: Adding Images Inside a Figure**  
To provide a caption for the image:  
```html
<figure>
  <img src="nature.jpg" alt="Nature View" width="500">
  <figcaption>A serene view of nature.</figcaption>
</figure>
```

---

### **Good Practices for Using Images in HTML**  
1. Always include an `alt` attribute for accessibility and SEO.  
2. Optimize image size to reduce page loading time.  
3. Use responsive images (`width: 100%`) for mobile-friendly designs.  
4. Use descriptive file names and organize images in a dedicated folder (e.g., `/images`).  

---

### **Summary**  
The `<img>` tag is a powerful tool for embedding images on a webpage. By leveraging its attributes—`src`, `alt`, `width`, and `height`—you can create accessible, responsive, and visually appealing designs.

# 📋 Tables and Forms in HTML  

Tables and forms are essential for structuring data and collecting user input in a webpage. Let’s explore their key features with examples and explanations! 🚀  

---

## **1. Structuring Data with Tables**  

### 🏗️ **Basic Table Structure**  
Tables are created using the `<table>` tag and contain rows (`<tr>`) and cells (`<th>` for headers, `<td>` for data).  

#### Example:  
```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
  <tr>
    <td>Vijay</td>
    <td>25</td>
    <td>Delhi</td>
  </tr>
  <tr>
    <td>Pratham</td>
    <td>22</td>
    <td>Mumbai</td>
  </tr>
</table>
```

#### Output:  
| **Name**    | **Age** | **City**   |  
|-------------|---------|------------|  
| Vijay       | 25      | Delhi      |  
| Pratham     | 22      | Mumbai     |  

---

### 🖋️ **Table Captions and Attributes**  
- **`<caption>`**: Adds a title to the table.  
- **`colspan`**: Merges multiple columns.  
- **`rowspan`**: Merges multiple rows.  

#### Example:  
```html
<table border="1">
  <caption>Employee Data</caption>
  <tr>
    <th>Name</th>
    <th colspan="2">Contact</th>
  </tr>
  <tr>
    <td>Vijay</td>
    <td>vijay@example.com</td>
    <td>+91 9876543210</td>
  </tr>
  <tr>
    <td>Pratham</td>
    <td colspan="2">pratham@example.com</td>
  </tr>
</table>
```

#### Output:  
**Employee Data**  
| **Name**    | **Contact**           | **Phone**         |  
|-------------|-----------------------|-------------------|  
| Vijay       | vijay@example.com     | +91 9876543210    |  
| Pratham     | pratham@example.com   |                   |  

---

## **2. Creating Forms**  

Forms collect user input with controls like text boxes, checkboxes, dropdowns, and buttons.  

### ✍️ **Basic Form Structure**  
A form is created using the `<form>` tag, and controls like `<input>`, `<textarea>`, `<select>`, and `<button>` are added inside it.  

#### Example:  
```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  
  <label for="password">Password:</label>
  <input type="password" id="password" name="password"><br><br>
  
  <button type="submit">Submit</button>
</form>
```

#### Explanation:  
- **`action`**: URL where form data is sent.  
- **`method`**: HTTP method (`POST` or `GET`).  
- Includes text, email, and password input fields.  

---

### 🔘 **Form Controls**  

1. **Text Input**: Collects short text.  
   ```html
   <input type="text" name="username">
   ```
2. **Textarea**: Collects longer text.  
   ```html
   <textarea name="comments" rows="4" cols="50"></textarea>
   ```
3. **Dropdown (Select)**: Provides a dropdown menu.  
   ```html
   <select name="gender">
     <option value="male">Male</option>
     <option value="female">Female</option>
   </select>
   ```
4. **Checkbox**: Allows multiple selections.  
   ```html
   <input type="checkbox" name="subscribe" value="newsletter"> Subscribe
   ```
5. **Radio Button**: Allows single selection.  
   ```html
   <input type="radio" name="gender" value="male"> Male
   <input type="radio" name="gender" value="female"> Female
   ```
6. **Submit Button**: Submits the form.  
   ```html
   <button type="submit">Submit</button>
   ```

---

### **3. Example: Complete Form with Various Controls**  
```html
<form action="/register" method="POST">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username"><br><br>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  
  <label>Gender:</label>
  <input type="radio" name="gender" value="male"> Male
  <input type="radio" name="gender" value="female"> Female<br><br>
  
  <label for="city">City:</label>
  <select id="city" name="city">
    <option value="delhi">Delhi</option>
    <option value="mumbai">Mumbai</option>
  </select><br><br>
  
  <label for="comments">Comments:</label><br>
  <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br><br>
  
  <input type="checkbox" name="agree" value="yes"> I agree to the terms<br><br>
  
  <button type="submit">Register</button>
</form>
```

---

### **Summary of Tables and Forms**  
| **Feature**            | **Tags/Attributes**                                                                                     | **Description**                                                                                                                                       |  
|-------------------------|--------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|  
| **Tables**              | `<table>, <tr>, <th>, <td>`                                                                            | Structure tabular data.                                                                                                                               |  
| **Table Attributes**    | `colspan`, `rowspan`, `<caption>`                                                                      | Merge cells or add a table title.                                                                                                                     |  
| **Forms**               | `<form>, <input>, <textarea>, <select>, <button>`                                                      | Collect user inputs.                                                                                                                                  |  
| **Form Input Types**    | `text`, `email`, `password`, `checkbox`, `radio`, `submit`                                             | Define input controls for specific types of data.                                                                                                     |  

Tables and forms are key components of HTML, helping to display data and gather user information efficiently. 🚀

# HTML Best Practices & Embedding Media

This repository provides a collection of HTML examples and best practices, including how to embed video, audio, and other content, as well as tips for responsive design, accessibility, and SEO optimization.

## Table of Contents
- [Introduction](#introduction)
- [Embedding Video & Audio](#embedding-video--audio)
- [Embedding Content from Other Sources](#embedding-content-from-other-sources)
- [Responsive Design & Accessibility](#responsive-design--accessibility)
- [SEO Basics & Meta Tags](#seo-basics--meta-tags)
- [HTML Validation](#html-validation)
- [Best Practices for Clean, Maintainable Code](#best-practices-for-clean-maintainable-code)

## Introduction
This guide demonstrates the correct usage of HTML5 elements, including embedding media like video and audio, as well as ensuring your code is responsive, accessible, and SEO-friendly. Follow the practices outlined in this document to build clean and maintainable HTML code.

## Embedding Video & Audio

### Video
To embed a video, use the `<video>` element with the `controls` attribute for playback controls. Supported formats include `.mp4`, `.webm`, and `.ogg`.

```html
<video width="600" controls autoplay loop>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.webm" type="video/webm">
  Your browser does not support the video tag.
</video>


### Audio
To embed audio, use the `<audio>` element with the `controls` attribute. Supported formats include `.mp3`, `.ogg`, and `.wav`.

```html
<audio controls autoplay loop>
  <source src="audio.mp3" type="audio/mp3">
  <source src="audio.ogg" type="audio/ogg">
  Your browser does not support the audio element.
</audio>
```

## Embedding Content from Other Sources

### iFrames
To embed external content such as YouTube videos, Google Maps, or other web applications, use the `<iframe>` element.

```html
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" width="560" height="315" frameborder="0" allowfullscreen></iframe>
```

### Embed and Object Tags
The `<embed>` and `<object>` elements can also be used for embedding various media types or interactive content.

```html
<embed src="flashmovie.swf" width="600" height="400">
```

```html
<object data="movie.swf" type="application/x-shockwave-flash" width="600" height="400"></object>
```

## Responsive Design & Accessibility
To ensure your web pages are responsive and accessible across various devices and for all users, follow these best practices:

1. **Viewport Meta Tag**: Include the viewport meta tag to make your website responsive on mobile devices.
   
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```

2. **Use Semantic HTML**: Use appropriate HTML elements (e.g., `<header>`, `<footer>`, `<article>`) for better accessibility and SEO.
3. **Alt Text for Images**: Always provide descriptive alt text for images using the `alt` attribute.
   
   ```html
   <img src="image.jpg" alt="Description of the image">
   ```

4. **Keyboard Navigation**: Ensure your site is navigable using the keyboard by adding proper tabindex and ensuring form controls are properly labeled.

## SEO Basics & Meta Tags

Use meta tags to improve search engine indexing and provide metadata about your website.

```html
<head>
  <meta charset="UTF-8">
  <meta name="description" content="A description of your webpage for better SEO.">
  <meta name="keywords" content="HTML, SEO, web design">
  <meta name="author" content="Your Name">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Web Page Title</title>
</head>
```

## HTML Validation
To ensure your HTML code is clean and error-free, use the [W3C HTML Validator](https://validator.w3.org/). This tool will help you identify and fix issues with your HTML structure, syntax, and accessibility.

## Best Practices for Clean, Maintainable Code

1. **Indentation**: Use consistent indentation (2 or 4 spaces) for better readability.
2. **Commenting**: Add comments to explain complex code sections.
3. **Consistent Naming Conventions**: Use meaningful class and id names to make your code more understandable.

Example:

```html
<!-- Main Navigation -->
<nav class="main-nav">
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
  </ul>
</nav>
```

# HTML Interview Questions 🤖

This repository contains a list of 50 HTML interview questions, with collapsible answers for easy navigation. Click the **Answer** button to view the responses!

## General HTML Questions

<details>
<summary>1. What is HTML and why is it important in web development? 🌐</summary>
<button>Answer</button><br>
HTML (HyperText Markup Language) is the standard language for creating and structuring web pages. It defines the content and layout of a webpage. It is important because it is the backbone of any webpage, allowing for the display of text, images, forms, and other elements.
</details>

<details>
<summary>2. What are the basic components of an HTML document? 🏗️</summary>
<button>Answer</button><br>
The basic components of an HTML document include:
- `<!DOCTYPE html>` declaration (defines document type).
- `<html>` (the root element).
- `<head>` (contains metadata like title, links to CSS, etc.).
- `<body>` (contains the visible content of the page).
</details>

<details>
<summary>3. What is the purpose of the `<!DOCTYPE html>` declaration? 📜</summary>
<button>Answer</button><br>
The `<!DOCTYPE html>` declaration defines the document type and version of HTML. It helps the browser render the page correctly by telling it to interpret the page as an HTML5 document.
</details>

<details>
<summary>4. Explain the difference between an HTML tag and an HTML element. 🏷️</summary>
<button>Answer</button><br>
- An HTML tag is the markup used to define elements, such as `<p>`, `<h1>`, and `<div>`.
- An HTML element is the combination of the start tag, content, and the end tag, such as `<p>This is a paragraph.</p>`.
</details>

<details>
<summary>5. What is the difference between inline and block-level elements? 🏗️</summary>
<button>Answer</button><br>
- Block-level elements occupy the full width available, starting on a new line. Examples: `<div>`, `<h1>`, `<p>`.
- Inline elements take up only as much space as needed and do not start on a new line. Examples: `<span>`, `<a>`, `<img>`.
</details>

<details>
<summary>6. What are semantic HTML tags and why are they important? 📚</summary>
<button>Answer</button><br>
Semantic HTML tags give meaning to the content inside them, improving accessibility and SEO. Examples include `<header>`, `<footer>`, `<section>`, and `<article>`.
</details>

## Forms and Input Elements

<details>
<summary>7. What is the purpose of the `<head>` tag in HTML? 💡</summary>
<button>Answer</button><br>
The `<head>` tag contains meta-information about the document, such as the document's title (`<title>`), links to external files (CSS, JavaScript), and other metadata like keywords and author.
</details>

<details>
<summary>8. What are the different types of lists in HTML? 📜</summary>
<button>Answer</button><br>
There are three types of lists in HTML:
- `<ul>`: Unordered list (bulleted list).
- `<ol>`: Ordered list (numbered list).
- `<dl>`: Description list (used for terms and descriptions).
</details>

<details>
<summary>9. What is the `<a>` tag used for in HTML? 🔗</summary>
<button>Answer</button><br>
The `<a>` (anchor) tag is used to create hyperlinks that link to other webpages or resources. It typically uses the `href` attribute to specify the target URL: `<a href="https://example.com">Visit Example</a>`.
</details>

<details>
<summary>10. How do you add an image in HTML? 🖼️</summary>
<button>Answer</button><br>
You can add an image using the `<img>` tag, specifying the `src` (source) attribute to point to the image file and `alt` (alternative text) for accessibility:
```html
<img src="image.jpg" alt="Description of image">
```
</details>

<details>
<summary>11. What is the difference between the `<div>` and `<span>` elements? 🖥️</summary>
<button>Answer</button><br>
- `<div>` is a block-level element used for grouping content and creating sections.
- `<span>` is an inline element used to style a part of the content without affecting the layout.
</details>

<details>
<summary>12. What are attributes in HTML? Can you give some examples? 🏷️</summary>
<button>Answer</button><br>
Attributes provide additional information about HTML elements. Examples include:
- `src`: Specifies the source for images or media.
- `href`: Defines the destination URL for anchor tags.
- `alt`: Provides alternative text for images.
- `class` and `id`: Used for styling and identification purposes.
</details>

<details>
<summary>13. What is the role of the `alt` attribute in images? 🌅</summary>
<button>Answer</button><br>
The `alt` attribute provides alternative text for an image, which is displayed if the image cannot be loaded. It is also essential for accessibility, as screen readers use it to describe images for visually impaired users.
</details>

<details>
<summary>14. What does the `href` attribute do in anchor tags (`<a>`) in HTML? 🌍</summary>
<button>Answer</button><br>
The `href` (Hypertext Reference) attribute specifies the destination URL for the link. When the link is clicked, the browser navigates to the URL defined in the `href` attribute.
</details>

<details>
<summary>15. What is the purpose of the `target` attribute in anchor tags? 🎯</summary>
<button>Answer</button><br>
The `target` attribute specifies where to open the linked document. Common values include:
- `_blank`: Opens in a new tab or window.
- `_self`: Opens in the same frame (default).
- `_parent`: Opens in the parent frame.
- `_top`: Opens in the full body of the window.
</details>

<details>
<summary>16. What are the different ways to create hyperlinks in HTML? 🔗</summary>
<button>Answer</button><br>
You can create hyperlinks using the `<a>` tag with the `href` attribute. The `href` can link to:
- A relative URL: `<a href="/about.html">About Us</a>`
- An absolute URL: `<a href="https://www.example.com">Visit Example</a>`
- An anchor within the same page: `<a href="#section1">Go to Section 1</a>`
</details>

## Table and Forms

<details>
<summary>17. What is the `<iframe>` tag used for in HTML? 🖥️</summary>
<button>Answer</button><br>
The `<iframe>` tag is used to embed another HTML document within the current page. It is commonly used for embedding external content like videos, maps, and other web pages.
```html
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" width="560" height="315" frameborder="0" allowfullscreen></iframe>
```
</details>

<details>
<summary>18. Explain the use of the `<meta>` tag in HTML. 🧠</summary>
<button>Answer</button><br>
The `<meta>` tag provides metadata about the HTML document, such as the character set, author, description, and viewport settings. It helps with SEO and defining how the content is displayed.
</details>

<details>
<summary>19. What are the different types of input fields in HTML forms? 📝</summary>
<button>Answer</button><br>
HTML forms can have different types of input fields:
- `text`: Single-line input.
- `password`: Hides input for password fields.
- `radio`: For selecting one option from a group.
- `checkbox`: For selecting multiple options.
- `email`: For validating an email address.
- `date`: For date input.
- `submit`: For form submission button.
</details>

<details>
<summary>20. What is the difference between the `readonly` and `disabled` attributes in HTML? 🚫</summary>
<button>Answer</button><br>
- `readonly`: The user cannot modify the field, but the data can be submitted.
- `disabled`: The user cannot modify or interact with the field, and it is not submitted with the form.
</details>

<details>
<summary>21. How do you create a table in HTML? 🧮</summary>
<button>Answer</button><br>
You can create a table using the `<table>`, `<tr>`, `<td>`, and `<th>` elements:
```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
</table>
```
</details>

<details>
<summary>22. What is the use of the `colspan` and `rowspan` attributes in HTML tables? 🏛️</summary>
<button>Answer</button><br>
- `colspan`: Specifies how many columns a cell should span.
- `rowspan`: Specifies how many rows a cell should span.
```html
<td colspan="2">Spans 2 columns</td>
<td rowspan="2">Spans 2 rows</td>
```
</details>

<details>
<summary>23. How do you create a dropdown menu in HTML? 📜</summary>
<button>Answer</button><br>
A dropdown menu can be created using the `<select>` element with `<option>` elements inside:
```html
<select>
  <option value="option1">Option 1</option>
  <option value="option2">Option 2</option>
</select>
```
</details>

<details>
<summary>24. What is the purpose of the `action` and `method` attributes in a form? 🧳</summary>
<button>Answer</button><br>
- `action`: Specifies the URL to which the form data will be sent.
- `method`: Specifies how the form data will be sent. Common methods are `GET` (data in the URL) and `POST` (data in the request body).
</details>

<details>
<summary>25. How do you add a comment in HTML? 💬</summary>
<button>Answer</button><br>
You can add a comment using the following syntax:
```html
<!-- This is a comment -->
```
Comments are not displayed in the browser and are used for documentation or notes within the code.
</details>

## Advanced HTML Features

<details>
<summary>26. What is the difference between the `<ul>` and `<ol>` tags in HTML? 📜</summary>
<button>Answer</button><br>
- `<ul>`: Unordered list (bulleted).
- `<ol>`: Ordered list (numbered).
</details>

<details>
<summary>27. What is the purpose of the `<label>` tag in HTML? 🏷️</summary>
<button>Answer</button><br>
The `<label>` tag is used to define a label for form elements. It improves accessibility by associating text with an input field, which can be clicked to focus on the input.
</details>

<details>
<summary>28. How do you create a checkbox in HTML? ☑️</summary>
<button>Answer</button><br>
A checkbox is created using the `<input>` element with the `type="checkbox"` attribute:
```html
<input type="checkbox" id="agree" name="agree">
<label for="agree">I agree to the terms and conditions</label>
```
</details>

<details>
<summary>29

. What is the `required` attribute in HTML forms used for? ✅</summary>
<button>Answer</button><br>
The `required` attribute specifies that a form field must be filled out before submitting the form. It is often used for input fields like email, text, and password.
</details>

<details>
<summary>30. How do you create a radio button in HTML? 🔘</summary>
<button>Answer</button><br>
A radio button is created using the `<input>` element with the `type="radio"` attribute:
```html
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
```
</details>

<details>
<summary>31. What is the difference between the `id` and `class` attributes in HTML? 🏷️</summary>
<button>Answer</button><br>
- `id`: Uniquely identifies an element on the page (should only be used once per page).
- `class`: Can be used to group multiple elements and apply styles to them.
</details>

<details>
<summary>32. What is the `style` attribute in HTML and how is it used? 🎨</summary>
<button>Answer</button><br>
The `style` attribute is used to apply inline CSS styles to an HTML element:
```html
<p style="color: red; font-size: 20px;">This is a styled paragraph.</p>
```
</details>
```
Here’s how you can structure the remaining HTML interview questions and answers in the same GitHub README format using `details`, `summary`, and interactive buttons with emoji. 

```markdown
## Forms and Input Elements (Continued)

<details>
<summary>33. What is the purpose of the `<form>` tag in HTML? 📝</summary>
<button>Answer</button><br>
The `<form>` tag is used to create an HTML form for user input. It contains various input elements such as text fields, radio buttons, and submit buttons. The data collected from the form can be sent to a server for processing.
</details>

<details>
<summary>34. Explain the difference between the `<input>` and `<textarea>` elements in HTML. 🖊️</summary>
<button>Answer</button><br>
- `<input>` is used to create single-line input fields like text boxes, checkboxes, and buttons.
- `<textarea>` is used to create multi-line input fields for longer text input, like comments or messages.
</details>

<details>
<summary>35. What is the purpose of the `<button>` tag in HTML? 🔘</summary>
<button>Answer</button><br>
The `<button>` tag is used to create clickable buttons. These buttons can trigger actions such as form submissions, opening a dialog, or running a JavaScript function.
```html
<button type="submit">Submit</button>
```
</details>

<details>
<summary>36. What is the purpose of the `<fieldset>` and `<legend>` tags in HTML? 🔒</summary>
<button>Answer</button><br>
- `<fieldset>` is used to group related elements in a form, typically visually enclosing them within a border.
- `<legend>` defines a caption for the `<fieldset>`, usually appearing at the top of the fieldset box.
```html
<fieldset>
  <legend>Personal Information</legend>
  Name: <input type="text">
</fieldset>
```
</details>

<details>
<summary>37. What is the difference between the `<b>` and `<strong>` tags in HTML? 🔤</summary>
<button>Answer</button><br>
- `<b>` is used to make text bold without implying any added importance or emphasis.
- `<strong>` is used to make text bold while indicating that the content has strong emphasis, typically rendering with a bold style by default.
</details>

## HTML5 and Advanced Features

<details>
<summary>38. What is the `contenteditable` attribute in HTML? ✏️</summary>
<button>Answer</button><br>
The `contenteditable` attribute is used to make an HTML element editable by the user. When applied, users can modify the content directly in the browser.
```html
<div contenteditable="true">Edit this text.</div>
```
</details>

<details>
<summary>39. What is the difference between the `<em>` and `<i>` tags in HTML? 🔠</summary>
<button>Answer</button><br>
- `<em>` is used to emphasize text, typically displayed in italics by default and indicates semantic importance.
- `<i>` is used to display text in italics without implying any emphasis or importance.
</details>

<details>
<summary>40. What is the `<link>` tag used for in HTML? 🔗</summary>
<button>Answer</button><br>
The `<link>` tag is used to link an external resource to the HTML document, typically used to link external CSS stylesheets.
```html
<link rel="stylesheet" href="styles.css">
```
</details>

<details>
<summary>41. What is the purpose of the `rel` attribute in the `<link>` tag? 🪢</summary>
<button>Answer</button><br>
The `rel` attribute specifies the relationship between the current document and the linked resource. For example, `rel="stylesheet"` specifies that the linked file is a stylesheet.
</details>

<details>
<summary>42. How do you add external CSS and JavaScript to an HTML document? 🌐</summary>
<button>Answer</button><br>
To add external CSS:
```html
<link rel="stylesheet" href="styles.css">
```
To add external JavaScript:
```html
<script src="script.js"></script>
```
Both links should be placed within the `<head>` or just before the closing `</body>` tag for better performance.
</details>

<details>
<summary>43. How do you include a font in an HTML document? 🔤</summary>
<button>Answer</button><br>
You can include a font using the `<link>` tag or `@font-face` in CSS. One common way is by linking to Google Fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
```
</details>

<details>
<summary>44. What are the different types of HTML forms? 📝</summary>
<button>Answer</button><br>
HTML forms can include various elements such as:
- `text`: Single-line input fields.
- `password`: For sensitive text.
- `email`: For email addresses.
- `radio`: For single-choice options.
- `checkbox`: For multiple selections.
- `submit`: To submit the form.
</details>

<details>
<summary>45. What is the role of the `<header>` tag in HTML? 🏠</summary>
<button>Answer</button><br>
The `<header>` tag represents the introductory content or navigational links of a document. It typically contains elements such as the site title, logo, or main navigation menu.
</details>

<details>
<summary>46. What is the purpose of the `<footer>` tag in HTML? 🦶</summary>
<button>Answer</button><br>
The `<footer>` tag represents the footer section of a document or section. It typically contains copyright information, links to privacy policies, or contact information.
</details>

## Mobile Optimization and SEO

<details>
<summary>47. What is the `viewport` meta tag, and why is it important? 📱</summary>
<button>Answer</button><br>
The `viewport` meta tag is used to control the layout on mobile devices. It allows the page to scale appropriately, making it responsive to different screen sizes:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
</details>

<details>
<summary>48. How does HTML5 improve web development compared to previous versions? ⚙️</summary>
<button>Answer</button><br>
HTML5 introduces new semantic elements like `<header>`, `<footer>`, `<section>`, and `<article>`, better support for multimedia (audio, video), offline storage with `localStorage`, and improved APIs like the Geolocation API.
</details>

<details>
<summary>49. How do you create an embedded video in HTML? 🎥</summary>
<button>Answer</button><br>
You can embed a video using the `<video>` tag. For example:
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```
</details>

<details>
<summary>50. What is the role of the `<canvas>` element in HTML? 🎨</summary>
<button>Answer</button><br>
The `<canvas>` element is used to draw graphics via JavaScript. It is commonly used for creating game graphics, data visualizations, and other interactive content.
```html
<canvas id="myCanvas" width="200" height="100"></canvas>
<script>
  var ctx = document.getElementById("myCanvas").getContext("2d");
  ctx.fillStyle = "blue";
  ctx.fillRect(10, 10, 150, 75);
</script>
```
</details>
```

