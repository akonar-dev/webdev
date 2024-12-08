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

 Examples - <h1></h1>  <p></p>  <hr/>  <br/>

### 6. What is an HTMl element?
**Ans.** An <opening tag> + content + </closing tag> form an html element. It is the basic building block of an html document.

Example - <h1>Content</h1>

### HTML tag tree
![HTML Document Tree](htmlTagTree.png)

### 7. Define meta, link and title tags in HTML.
**Ans.**
 1. <meta>: Defines metadata for the webpage (SEO, responsiveness, character set).
 2. <link>: Links external resources like CSS files and favicons.
 3. <title>: Sets the webpage title shown in browser tabs and improves SEO.

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






