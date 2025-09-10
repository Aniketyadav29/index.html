Web Development Basics: HTML
This document provides an overview of fundamental web development concepts, focusing on HTML (HyperText Markup Language). HTML is the backbone of any webpage, providing the structure and content, while CSS handles the styling and JavaScript provides the logic.

💻 HTML: The Building Blocks of the Web
HTML stands for HyperText Markup Language. It's the code used to structure a web page and its content. The components used to design the structure of websites are called HTML tags.

The default filename for a website's homepage is typically index.html.

An HTML tag is a container for some content or other HTML tags. For example, a paragraph is an element with an opening <p> tag and a closing </p> tag, with the content in between. Most HTML elements have both an opening and a closing tag with content in between. Some tags, like <br> for a line break, don't have content and are self-closing.

HTML is not case-sensitive. For example, <p> is the same as <P>.

🛠️ Basic HTML Page Structure
A basic HTML document has a specific structure:

<!DOCTYPE html>: This declaration tells the browser that you're using HTML5.

<html>: This is the root of an HTML document. It is the parent of the <head> and <body> tags.

<head>: This is a container for metadata, which is information about the document that isn't displayed on the page.

<title>: Sets the title of the page, which appears in the browser tab.

<body>: This tag contains all the data rendered and displayed by the browser.

📝 Common HTML Tags and Attributes
HTML Attributes
Attributes are used to add more information to a tag. For example, <html lang="en"> specifies the language of the document as English.

Heading Tags (<h1> to <h6>)
Used to display headings in HTML. <h1> is the most important heading, and <h6> is the least important.

Paragraph Tag (<p>)
Used to add paragraphs in HTML.

Anchor Tag (<a>)
Used to add links to your page. For example: <a href="https://www.google.com">Google</a>. To open a link in a new tab, use the attribute target="_main". You can also make an image a clickable link by wrapping the <img> tag inside an <a> tag.

Image Tag (<img>)
Used to add images to your page. The src attribute specifies the image source, which can be a relative URL. You can set the height and width of an image using attributes, like height="100" or width="100".

Line Break Tag (<br>)
Used to add a line break to your page.

Text Formatting Tags
<b> for bold text.

<i> for italic text.

<u> for <u>underline</u> text.

<big> for bigger text.

<small> for smaller text.

<sub> for subscript text (e.g., H₂O).

<sup> for superscript text (e.g., Aⁿ+B).

Horizontal Ruler (<hr>)
Used to display a horizontal line to separate content.

Preformatted Text (<pre>)
Used to display text exactly as it is, without ignoring spaces and next lines.

📦 Block vs. Inline Elements
Elements can be categorized as block-level or inline-level.

Block-Level Elements: These elements take up the full width available and start on a new line. The <div> tag is a common block-level container for other HTML elements.

Inline-Level Elements: These elements only take up as much width as their content needs and do not start on a new line. The <span> tag is also a container for other HTML elements and is an inline element.

📄 HTML Layout and Structure
Using semantic tags for layout helps with page structure. Examples include <header>, <main>, and <footer>.

Inside the <main> tag, you can use:

<section>: For a section on your page.

<article>: For an article.

<aside>: For content that is "aside" from the main content, like ads.

📂 Lists and Tables
Lists
Lists are used to represent real-life list data.

Unordered List (<ul>): Displays a bulleted list. Each item is an <li> tag.

Ordered List (<ol>): Displays a numbered list. Each item is also an <li> tag.

Tables
Tables are used to represent real-life table data.

<table>: Defines a table.

<caption>: Adds a caption to the table.

<tr>: Used to display a table row.

<td>: Used for table data.

<th>: Used for a table header.

<thead> and <tbody>: Used to wrap the table head and body, respectively.

colspan attribute: Used to create cells that span over multiple columns.

📝 Forms and User Input
Forms (<form>) are used to collect data from the user. The action attribute is used to define what action is performed when the form is submitted.

Input (<input>): A common form element for user input. The type attribute specifies the type of input, such as "text" or "radio". The placeholder attribute provides a hint to the user.

Label (<label>): Used to associate a label with a form control.

Checkbox (<input type="checkbox">): Allows users to select one or more options.

Textarea (<textarea>): Creates a multi-line text input area.

Select (<select>): Creates a dropdown list with multiple <option> tags.

🎬 Multimedia and Embedding
Iframe (<iframe>): Used to embed one website inside another.

Video (<video>): Used to embed a video. It has several attributes:

controls: Adds video controls.

height and width: Sets the dimensions of the video.

loop: Makes the video repeat.

autoplay: Automatically plays the video.







