# Week #1 Day # 1

## What is HTML

HTML stands for Hyper Text Markup Language. It is a standard markup language used to create web pages and web applications. HTML uses a system of markup tags and attributes to structure content on the web, such as headings, paragraphs, images, links, lists, and more.

HTML documents consist of a series of elements, which are enclosed within tags. Tags are written using angle brackets (<>) and usually come in pairs, with an opening tag (<tag>) and a closing tag (</tag>) that surround the content. Attributes provide additional information about an element and are typically used within the opening tag. Together, HTML tags and attributes define the structure and appearance of web pages.

Web browsers interpret HTML code and render it into a visual representation, which users can view in their web browsers. HTML is a fundamental technology combined with other technologies like CSS (Cascading Style Sheets) and JavaScript to build websites and web applications.

## What is CSS

CSS stands for Cascading Style Sheets. It is a style-sheet language used for describing the presentation and visual appearance of HTML or XML documents on the web. CSS provides a way to separate the content and structure of a web page from its presentation, allowing web developers to define the layout, colors, fonts, and other visual styles of web pages.

With CSS, web developers can apply styles to HTML elements using selectors, which target specific elements or groups of elements, and declare properties and values to define how those elements should be displayed. CSS rules can be defined inline within HTML documents, included in the **`<style>`** element within an HTML document, or externally in separate CSS files that are linked to HTML documents.

CSS uses a cascading model, meaning multiple CSS rules can apply to the same HTML element, and their styles can be combined in a specific order to determine the final appearance of the element. This allows for flexibility and control over the visual presentation of web pages.

CSS is a powerful tool that enables web developers to create visually appealing and responsive web designs, and it is an essential technology used in combination with HTML and JavaScript to build modern websites and web applications.

## What is JavaScript

JavaScript is a widely-used programming language that allows for dynamic and interactive functionality on web pages. It is a client-side scripting language, which means that it is executed by web browsers on the client's computer, allowing for real-time interactivity and responsiveness in web applications.

JavaScript enables web developers to add interactivity, manipulate content, and dynamically update the behavior and appearance of web pages. It can be used to perform various tasks such as form validation, DOM (Document Object Model) manipulation, handling events, making asynchronous requests to servers, and creating interactive user interfaces.

JavaScript is typically embedded directly in HTML documents using **`<script>`** tags, or it can be included as separate external JavaScript files that are linked to HTML documents. Web browsers execute JavaScript code in a top-down, procedural manner, and it can interact with the DOM to dynamically modify the content and structure of web pages.

JavaScript is a versatile and powerful language that is widely used in web development, both on the client side and server side (using frameworks such as Node.js). It is a core technology of the web and is commonly used in combination with HTML and CSS to build modern, interactive, and dynamic web applications.

## What is their relationship?

HTML is the bone structure of a web page whereas CSS provides skin to the bone structure and JavaScript works as a brain for the body we just have created.

## Set up your Environment!

First of all setup your computer for developing web pages for that

- [ ]  Download VS-Code from here [**Download VS-Code](https://code.visualstudio.com/download).**
- [ ]  Install Prettier Extension from VS-Code Marketplace and turn it one like this [**Install Prettier**](https://youtu.be/J-JRwDkDJHc).
- [ ]  Also, Install Live Server to the VS-Code like this [**Live Server.**](https://www.youtube.com/watch?v=9kEOkw_LvGU)

and you are good to go.

[Create your first HTML page!](https://www.notion.so/Create-your-first-HTML-page-57223cf1a99043b6944545168e844a2b?pvs=21)

here is a **[link](https://www.youtube.com/watch?v=MDLn5-zSQQI)** you can watch to learn for how to build your first HTML page 

## What is an HTML Tag?

HTML tags are used to define the content and structure of a web page. They are enclosed in angle brackets, and usually come in pairs: an opening tag and a closing tag. The content to which the tag applies is placed between the opening and closing tags.
For example, the `<p>` tag is used to indicate a paragraph of text, and the opening and closing tags look like this: `<p>Here is some text.</p>`.
HTML tags can also have attributes that provide additional information about the tag or modify its behavior. For example, the `<a>` tag is used to create links, and it has an attribute called `href` that specifies the URL of the page to which the link should go. A link created with the `<a>` tag might look like this: `<a href="<https://www.example.com>">Click here to go to Example.com</a>`.

## What is the attribute of HTML Tag?

An attribute of an HTML tag provides additional information about the tag or modifies its behavior. Attributes are added to the opening tag of an element and consist of a name and a value, separated by an equals sign. For example, the `href` attribute of the `<a>` tag specifies the URL of the page to which the link should go. An example of an anchor tag with an href attribute is `<a href="<https://www.example.com>">Click here to go to Example.com</a>`.

HTML attributes can modify the behavior of an element or provide additional information about the element. There are many HTML attributes available, some of the commonly used ones are:

- `class`: specifies one or more class names for an element (used to refer to CSS styles)
- `id`: specifies a unique id for an element
- `src`: specifies the URL of the image to be displayed (used with `<img>` tag)
- `alt`: specifies an alternate text for an image (used with `<img>` tag)
- `style`: specifies inline CSS styles for an element
- `title`: specifies extra information about an element (displayed as a tooltip)

For example, the following code uses the `class` and `id` attributes to style an `<div>` element:

```html
<div class="content" id="main-content">
  <p>This is the main content area.</p>
</div>

```

In this example, the `class` attribute specifies the class name `content`, which can be used to style the element using CSS. The `id` attribute specifies the unique id `main content`, which can be used to refer to the element in JavaScript.

## Before your assignment dive a little deeper.

to understand from an instructor you can go here on this [**link**](https://youtu.be/vNOyRZIkC7o?t=290) or explore you on complete 10 attributes.

## Now you are ready for your second assignment!

[Add tags and attributes to your Html Page (1)](https://www.notion.so/Add-tags-and-attributes-to-your-Html-Page-1-6b72f66fd6614294adfd4bc32a49cccf?pvs=21)

## HTML Tags!

Tags are used to define different parts of an HTML page and to create interactive elements like forms, input fields, and buttons.

Here are some popular HTML tags and their purposes:

- `<html>`: Represents the root of an HTML document
- `<head>`: Contains metadata such as the title and links to stylesheets
- `<body>`: Contains the content of the document that is displayed in the browser
- `<div>`: Groups together HTML elements and applies styles to them
- `<p>`: Defines a paragraph of text
- `<a>`: Creates hyperlinks to other web pages, email addresses, or files
- `<img>`: Displays an image
- `<ul>`: Creates an unordered list with bullet points
- `<ol>`: Creates an ordered list with numbers
- `<li>`: Defines a list item within a `<ul>` or `<ol>`
- `<h1>` to `<h6>`: Create headings of different sizes, with `<h1>` being the largest and `<h6>` being the smallest
- `<table>`: Creates a table
- `<tr>`: Defines a table row
- `<th>`: Defines a header cell in a table
- `<td>`: Defines a data cell in a table
- `<form>`: Creates a form that users can fill out
- `<input>`: Defines an input field that accepts user input
- `<label>`: Associates an input field with a label
- `<button>`: Defines a clickable button
- `<textarea>`: Defines a multi-line text input field
- `<select>`: Defines a drop-down list
- `<option>`: Defines an option in a drop-down list

## Want to get more out of it?

go to this [**link**](https://www.youtube.com/watch?v=ZhULGD5hNQs) and get a comprehensive view of all the tags needed to learn and also extra ones. 

## Ready for the next assignment!

[Assignment](https://www.notion.so/Assignment-f50c2153a1744cf9aab2ef8dd1d2803c?pvs=21)

## What is Table Tag in HTML?

The HTML `<table>` tag is used to create tables in web pages. Tables consist of rows and columns, which are defined using the `<tr>` (table row) and `<td>` (table data/cell) tags, respectively. The `<th>` (table header) tag is used to define the header cells of a table. Tables can also be styled using CSS.

In HTML, the `<table>` tag is one of the most commonly used tags for creating tables on web pages. It allows you to structure data into rows and columns, which makes it easier to read and understand.

To create a table, you first need to define the `<table>` element, followed by one or more `<tr>` elements to define the rows, and one or more `<td>` or `<th>` elements to define the columns. The `<td>` element represents a standard data cell, while the `<th>` element represents a header cell.

For example, the following code creates a table with two rows and two columns:

```html
<table>
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
  </tr>
  <tr>
    <td>Row 1, Column 1</td>
    <td>Row 1, Column 2</td>
  </tr>
  <tr>
    <td>Row 2, Column 1</td>
    <td>Row 2, Column 2</td>
  </tr>
</table>

```

You can also add attributes to the table and its elements to customize its appearance and behavior. For example, you can use the `border` attribute to add a border around the table, or the `colspan` and `rowspan` attributes to span a cell across multiple columns or rows.

The `colspan` attribute can be used to span a cell across multiple columns. For example, the following code creates a table where the first cell spans two columns:

```html
<table>
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
    <th>Column 3</th>
  </tr>
  <tr>
    <td colspan="2">Row 1, Column 1 and 2</td>
    <td>Row 1, Column 3</td>
  </tr>
  <tr>
    <td>Row 2, Column 1</td>
    <td>Row 2, Column 2</td>
    <td>Row 2, Column 3</td>
  </tr>
</table>

```

This will produce:

| Column 1 | Column 2 | Column 3 |
| --- | --- | --- |
| Row 1, Column 1 and 2 | Row 1, Column 3 |  |
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3 |

The `rowspan` attribute can be used to span a cell across multiple rows. For example, the following code creates a table where the first cell spans two rows:

```html
<table>
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
    <th>Column 3</th>
  </tr>
  <tr>
    <td rowspan="2">Row 1 and 2, Column 1</td>
    <td>Row 1, Column 2</td>
    <td>Row 1, Column 3</td>
  </tr>
  <tr>
    <td>Row 2, Column 2</td>
    <td>Row 2, Column 3</td>
  </tr>
</table>

```

This will produce:

| Column 1 | Column 2 | Column 3 |
| --- | --- | --- |
| Row 1 and 2, Column 1 | Row 1, Column 2 | Row 1, Column 3 |
|  | Row 2, Column 2 | Row 2, Column 3 |

## Want to get a practical guide?

Go to this [**link**](https://www.youtube.com/watch?v=w2inJrRGC9c) and you can get a good grip on how to develop a table in HTML.

## What is Form in HTML?

In HTML, a form is a section that allows users to enter data and send it to a server for processing. Forms typically contain input fields, check boxes, radio buttons, submit buttons, and more. These elements are used to create web forms that users can fill out and submit to a server.

Here is a basic example of HTML form code:

```html
<form action="submit.html" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <label for="password">Password:</label>
  <input type="password" id="password" name="password">

  <input type="submit" value="Submit">
</form>

```

In this example, the form has three input fields (name, email, and password) and a submit button. When the user clicks the submit button, the form data is sent to a server-side script specified in the `action` attribute of the `form` tag. The `method` attribute specifies which HTTP method to use when submitting the form (either `"post"` or `"get"`).

## Want to get a practical guide?

you can go to this [**link**](https://www.youtube.com/watch?v=HTf-gPLWuUA) and check how to write a form in HTML.