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

# HTML Interview Questions


## General HTML Questions

<details>
<summary>1. What is HTML?</summary>
HTML (HyperText Markup Language) is the standard language used to create web pages. It defines the structure of a webpage using markup. HTML uses tags to describe the structure and elements of the content on the page.
</details>

<details>
<summary>2. What are HTML elements?</summary>
HTML elements consist of a start tag, content, and an end tag. For example, `<p>This is a paragraph.</p>` is an HTML element. The start tag is `<p>`, the content is "This is a paragraph.", and the end tag is `</p>`.
</details>

<details>
<summary>3. What is the difference between an HTML tag and an HTML element?</summary>
- An HTML tag refers to the markup code used to define elements, like `<div>` or `<h1>`.
- An HTML element consists of the tag along with the content inside it, such as `<div>Content</div>`.
</details>

<details>
<summary>4. What is the purpose of the `<!DOCTYPE html>` declaration?</summary>
The `<!DOCTYPE html>` declaration specifies the HTML version and helps the browser render the page correctly. It ensures the document is treated as HTML5, which is the latest version of HTML.
</details>

<details>
<summary>5. What is the difference between inline and block-level elements in HTML? Can you give examples of each?</summary>
- Block-level elements take up the full width of their parent container and start on a new line, like `<div>`, `<h1>`, and `<p>`.
- Inline elements only take up as much width as their content, and do not break onto a new line, such as `<span>`, `<a>`, and `<img>`.
</details>

## HTML Tags & Attributes

<details>
<summary>6. What is the difference between the `<div>` and `<span>` tags in HTML?</summary>
- `<div>` is a block-level element used to group content together.
- `<span>` is an inline element used to apply styles or group inline content without breaking the flow of the document.
</details>

<details>
<summary>7. What are semantic HTML tags? Can you list a few examples?</summary>
Semantic HTML tags give meaning to the content inside them, improving accessibility and SEO. Examples include `<header>`, `<footer>`, `<article>`, `<section>`, and `<nav>`.
</details>

<details>
<summary>8. Explain the `alt` attribute for images. Why is it important for accessibility and SEO?</summary>
The `alt` attribute provides alternative text for an image. It is important for accessibility because screen readers use it to describe images to visually impaired users. It also helps search engines understand the image content, improving SEO.
</details>

<details>
<summary>9. What is the `href` attribute used for in anchor tags (`<a>`) in HTML?</summary>
The `href` (Hypertext Reference) attribute specifies the URL of the page the link goes to. Example: `<a href="https://example.com">Visit Example</a>`.
</details>

<details>
<summary>10. What is the role of the `meta` tag in the HTML `<head>` section?</summary>
The `meta` tag provides metadata about the HTML document, such as character encoding (`<meta charset="UTF-8">`), author information, and viewport settings. It is crucial for SEO and improving the user experience.
</details>

## Forms and Input Elements

<details>
<summary>11. What are the different types of input elements in HTML?</summary>
HTML provides various input types to collect different types of user data:
- `text`: Single-line text input.
- `email`: Validates an email address.
- `password`: Hides input for passwords.
- `radio`: Select one option from a set.
- `checkbox`: Select multiple options.
- `date`: Date picker.
- `number`: Numeric input.
</details>

<details>
<summary>12. What is the purpose of the `required` attribute in form elements?</summary>
The `required` attribute ensures the user cannot submit the form without filling out the field. It is used for validation on the client side.
</details>

<details>
<summary>13. Explain the difference between the `readonly` and `disabled` attributes in form elements.</summary>
- `readonly`: Prevents the user from editing the field but still allows the value to be submitted with the form.
- `disabled`: Prevents the user from editing or interacting with the field. Disabled fields are not submitted with the form.
</details>

## Advanced HTML Features

<details>
<summary>14. What are the `draggable` and `drop` attributes used for in HTML?</summary>
- The `draggable` attribute makes an element draggable, enabling users to drag and drop items.
- The `drop` attribute is used in conjunction with `dragover` to specify the target for dropped items.
</details>

<details>
<summary>15. What is the `contenteditable` attribute and how does it work?</summary>
The `contenteditable` attribute allows users to edit the content of an element directly in the browser. It is often used for rich text editors or to create editable sections in web pages.
</details>

<details>
<summary>16. Explain the `autofocus` attribute in HTML. What elements can it be used with?</summary>
The `autofocus` attribute automatically focuses on an element when the page loads. It is commonly used with form input fields like textboxes or buttons.
</details>

<details>
<summary>17. What is the `hidden` attribute in HTML? Can you explain when you would use it?</summary>
The `hidden` attribute hides an element from view, while keeping it in the DOM. It is useful when you need to hide content temporarily or dynamically.
</details>

<details>
<summary>18. What are the common ways to embed multimedia content (like audio and video) into an HTML page?</summary>
You can use the `<audio>` and `<video>` tags to embed media content. Example for video:

```html
<video controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

