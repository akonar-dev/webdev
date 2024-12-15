#### Date: 07/12/2024

Written by: Arijeet Konar

### 1. What is VS Code?
**Ans.** **Visual Studio Code (VS Code)** is a lightweight, free, open-source code editor developed by Microsoft. It's designed for a wide range of programming and development tasks and supports many programming languages like C,C++, Java, JavaScript, Python etc.

Download VS Code here:
[VS Code](https://code.visualstudio.com/)

### 2. What is an .html in index.html?
**Ans.** In **index.html**, the **.html** is the file extension that indicates the file is an HTML document.
    Other examples of file extension are -
    .txt - for writing text files,
    .css - for writing css files,
    .js - for writing javascript files

### 3. What are the different parts of a website?
**Ans.** A website is composed of -
    1. HTML
    2. CSS and
    3. JavaScript.
    In order to understand this let us take the analogy of the human body
        The skeleton of the website - HTML
        The skin, hair and other external attributes - CSS
        The brain and the central nervous system - JavaScript

![WebSite Analogy](webAnalogy.jpg)

**Tips** - Use the autosave option in VS Code

Extensions to use in VS Code -  1.Live Server  2.Prettier

### 4.What is meant by boilerplate code?
**Ans.** Boilerplate code refers to sections of code that are repeated in multiple places with little or no modification. It's typically required for setting up the foundational structure of an application, project, or specific functionality, but doesn't necessarily relate to the core logic of the program.

Example:
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```
 ### 5. What are tags in html?
 **Ans.** In HTML, tags are the building blocks used to define and structure elements on a webpage. Tags are written using angle brackets (< >) and typically come in pairs: an opening tag (e.g., <tagname>) and a closing tag (e.g., </tagname>), though some tags are self-closing.

 Examples - `<p> <h1></h1>  <  <hr/>  <br/> </p>`

### 6. What is an HTMl element?
**Ans.** An <openingTag> + content + </closingTag> form an html element. It is the basic building block of an html document.

Example - `<p><h1>Content</h1></p>`

### HTML tag tree
![HTML Document Tree](htmlTagTree.png)

### 7. Define meta, link and title tags in HTML.
**Ans.**
 1. `<p><meta></p>`: Defines metadata for the webpage (SEO, responsiveness, character set).
 2. `<p><link></p>`: Links external resources like CSS files and favicons.
 3. `<p><title></p>`: Sets the webpage title shown in browser tabs and improves SEO.

Example -

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Learn about meta, link, and title tags in HTML.">
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <title>Understanding Meta, Link, and Title Tags</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
</body>
</html>
```

### Heading Tags in HTML
HTML heading tags are used to define headings in a document. These tags range from **h1** to **h6**, with **h1** being the most important or prominent and **h6** being the least.

```html
<h1>This is a main heading</h1>
<h2>This is a subheading</h2>
<h3>This is a sub-subheading</h3>
<h4>This is a smaller heading</h4>
<h5>This is an even smaller heading</h5>
<h6>This is the smallest heading</h6>
```
### VSCode Shortcuts
[VS Code Shorcut Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
[VS Code Shorcut MacOs](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)

### Lorem

In the context of HTML and Visual Studio Code (VS Code), "lorem" refers to placeholder text commonly used in web development and design. It originates from "Lorem Ipsum," a scrambled version of Latin text used to fill spaces in design templates or mock-ups.

Usage in VS Code:
1.Open an HTML file in VS Code.
2.Type lorem and press Tab or Enter.
3.VS Code automatically generates a paragraph of Lorem Ipsum text.

Typing lorem5 generates 5 words
Typing lorem10 generates 10 words.

### `<b>` tag
The `<b>` tag in HTML is used to bolden text without implying any added importance or emphasis. It is typically used for styling purposes when you want to draw attention to text visually, but without conveying extra meaning.

```html
<b>Your Text Here</b>
```

### `<i>` tag
The `<i>` tag in HTML is used to display text in italic style. It is often used for stylistic purposes or to indicate a particular type of content, such as titles, foreign words, or technical terms, without adding any semantic meaning.

```html
<i>Your Text Here</i>
```
### br tag hr tag(auto closing  tag)


| Tag | Purpose | Visual Effect |
|------------------|------------------|------------------|
| `<br>`   | Adds a line break in the text   | Moves content to a new line   |
| `<hr>` | Adds a horizontal rule for separation   | Displays a horizontal line   |

They are self-closing tags (do not require a closing tag)

Example of `<br>`tag -
```html
Address: 123 Main St.<br>City, State, ZIP.
```
Example of `<hr>`tag -
```html
<h2>End of Chapter 1</h2>
<hr>
<h2>Start of Chapter 2</h2>
```



### sub sup tag
### ol ul li tag
### anchor tag and target attribute
### input tag label tag
### when not to use cdn
### img tag
### video tag
### audio tag
### semantic html tags
###









