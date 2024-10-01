# Web Development Tutorial Series

## Table of Contents
1. [HTML Basics](#html-basics)
   - [1.1 Introduction to HTML](#11-introduction-to-html)
   - [1.2 HTML Document Structure](#12-html-document-structure)
   - [1.3 HTML Elements and Tags](#13-html-elements-and-tags)
   - [1.4 Common HTML Tags](#14-common-html-tags)
   - [1.5 Attributes in HTML](#15-attributes-in-html)
   - [1.6 Forms in HTML](#16-forms-in-html)
   - [1.7 Semantic HTML](#17-semantic-html)
   - [1.8 Div and Span](#18-div-and-span)
   - [1.9 HTML Best Practices](#19-html-best-practices)
   - [1.10 Conclusion](#20-conclusion)

---

## HTML Basics

### 1.1 Introduction to HTML
- **HTML** ka full form hai **HyperText Markup Language**. Yeh web pages banane ke liye use hoti hai.
- HTML ek markup language hai jo content ko structure aur format karne ke liye tags ka use karti hai.
- HTML ka basic purpose hai web content ko define karna, jaise headings, paragraphs, images, links, etc.

### 1.2 HTML Document Structure
- Har HTML document ka basic structure kuch is tarah hota hai:

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <h1>Hello World!</h1>
    <p>This is my first HTML page.</p>
</body>
</html>
```
<!DOCTYPE html>: Document type declaration.<html>: HTML document ka root element.<head>: Document ka metadata (title, character set, etc.).<body>: Document ka visible content.1.3 HTML Elements and TagsHTML elements ko tags se define kiya jata hai. Tags ka syntax kuch is tarah hota hai:<tagname>Content goes here</tagname>Example: <p>This is a paragraph.</p>1.4 Common HTML TagsHeadings: <h1> se <h6> tak headings.Paragraphs: <p> tag paragraphs ke liye.Links: <a href="url">Link text</a> se hyperlinks banate hain.Images: <img src="image-url" alt="description"> se images include karte hain.Lists:Unordered lists: <ul><li>Item</li></ul>Ordered lists: <ol><li>Item</li></ol>1.5 Attributes in HTMLHTML tags mein additional information provide karne ke liye attributes ka use hota hai. Attributes ka syntax kuch is tarah hota hai:<tagname attribute="value">Content</tagname>Example: <a href="https://www.example.com" target="_blank">Visit Example</a>1.6 Forms in HTMLHTML forms user input collect karne ke liye use hoti hain. Form ka basic structure kuch is tarah hota hai:<form action="submit-url" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    <input type="submit" value="Submit">
</form><input>: Various types of input fields (text, password, email, etc.).<label>: Labels for input fields.<textarea>: Multi-line text input.1.7 Semantic HTMLSemantic HTML ka use karke aap elements ko unke meaning ke hisaab se define karte hain. Yeh accessibility aur SEO mein help karta hai.Examples of semantic elements:<header>: Page ka header.<nav>: Navigation links.<article>: Independent content.<footer>: Page ka footer.1.8 Div and Span<div>:<div> block-level element hai jo content ko grouping aur layout ke liye use hota hai.Iska use styling aur scripting ke liye bhi kiya jata hai.Example:<div style="background-color: lightblue; padding: 10px;">
    <h2>This is a Div</h2>
    <p>Divs are used to group block-level content.</p>
</div><span>:<span> inline element hai jo text ya content ke chhote portions ko group karne ke liye use hota hai.Iska use styling aur scripting ke liye bhi kiya jata hai.Example:<p>This is a <span style="color: red;">red</span> word in a sentence.</p>Difference:<div> block-level element hai aur naya line shuru karta hai, jabki <span> inline element hai aur same line mein content ko group karta hai.1.9 HTML Best PracticesCode ko clean aur organized rakhna zaroori hai.Indentation aur comments ka use karein:<!-- This is a comment -->
<p>This is a paragraph.</p>Har element ka correct structure aur closing tag ka use karein.1.10 ConclusionHTML web development ka foundational language hai. Isse sikhne se aap web pages ka structure aur layout achhe se samajh sakte hain.
---
