# HTML Revision Notes

## Table of Contents

1. [Structure of an HTML document](#structure-of-an-html-document)
2. [HTML tags and elements](#html-tags-and-elements)
3. [HTML attributes](#html-attributes)
4. [HTML doctype declaration](#html-doctype-declaration)
5. [HTML comments](#html-comments)
6. [Headings (h1 - h6)](#headings-h1---h6)
7. [Paragraphs (p)](#paragraphs-p)
8. [Line breaks (br)](#line-breaks-br)
9. [Text formatting](#text-formatting)
10. [Lists](#lists)
11. [Hyperlinks (a)](#hyperlinks-a)
12. [Form structure and elements](#form-structure-and-elements)
13. [Form attributes](#form-attributes)
14. [Form validation and error handling](#form-validation-and-error-handling)
15. [Form submission and handling](#form-submission-and-handling)
16. [Inserting images (img)](#inserting-images-img)
17. [Image attributes](#image-attributes)
18. [Adding audio and video](#adding-audio-and-video)
19. [Media attributes and controls](#media-attributes-and-controls)
20. [Creating tables](#creating-tables)
21. [Table headers and captions](#table-headers-and-captions)
22. [Table formatting and styling](#table-formatting-and-styling)
23. [Semantic Tags](#semantic-tags)

---

## Structure of an HTML document

Every HTML document follows a basic structure with doctype, head, and body tags.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```

## HTML tags and elements

HTML tags define elements and they usually come in pairs like `<tag></tag>`.

```html
<p>This is a paragraph.</p>
```

## HTML attributes

Attributes provide additional information about an element. They are always specified in the opening tag.

```html
<a href="https://www.example.com">Visit Example.com</a>
```

## HTML doctype declaration

It specifies the document type and version of HTML.

```html
<!DOCTYPE html>
```

## HTML comments

Comments are ignored by browsers but can help make the code more readable.

```html
<!-- This is a comment -->
```

## Headings (h1 - h6)

Headings are defined with the `<h1>` to `<h6>` tags.

```html
<h1>Main Title</h1>
<h2>Sub Title</h2>
```

## Paragraphs (p)

Paragraphs are defined with the `<p>` tag.

```html
<p>This is a paragraph.</p>
```

## Line breaks (br)

For line breaks without a new paragraph, use `<br>`.

```html
<p>Line 1<br />Line 2</p>
```

## Text formatting

For bold (`<strong>`), italic (`<em>`), underline (`<u>`).

```html
<strong>Bold Text</strong>
<em>Italic Text</em>
<u>Underlined Text</u>
```

## Lists

Unordered (`<ul>`) and ordered (`<ol>`) lists.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<ol>
  <li>First</li>
  <li>Second</li>
</ol>
```

## Hyperlinks (a)

Used for linking to other pages.

```html
<a href="https://www.example.com">Visit Example</a>
```

## Form structure and elements

Elements like `<input>`, `<textarea>`, `<select>` inside a `<form>` tag.

```html
<form>
  <input type="text" name="username" />
  <textarea name="message"></textarea>
  <select name="gender">
    <option value="male">Male</option>
    <option value="female">Female</option>
  </select>
</form>
```

## Form attributes

Attributes like `action`, `method`, `enctype` define form behavior.

```html
<form action="/submit" method="post" enctype="multipart/form-data"></form>
```

## Form validation and error handling

Use attributes like `required`, `min`, `max` for basic HTML validation.

```html
<input type="text" required />
```

## Form submission and handling

Submit a form using a `<button>` or `<input type="submit">`.

```html
<button type="submit">Submit</button>
```

## Inserting images (img)

Images are included using the `<img>` tag.

```html
<img src="image.jpg" alt="An example image" />
```

## Image attributes

Attributes like `src`, `alt`, `width`, `height`.

```html
<img src="image.jpg" alt="Description" width="300" height="200" />
```

## Adding audio and video

For audio (`<audio>`) and video (`<video>`).

```html
<audio controls>
  <source src="audio.mp3" />
</audio>
<video controls>
  <source src="video.mp4" />
</video>
```

## Media attributes and controls

Attributes like `controls`, `autoplay`.

```html
<video controls autoplay>
  <source src="video.mp4" />
</video>
```

## Creating tables

Tables use `<table>`, `<tr>`, `<td>`, `<th>`.

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1 Col 1</td>
    <td>Row 1 Col 2</td>
  </tr>
</table>
```

## Table headers and captions

Headers (`<th>`) and captions (`<caption>`).

```html
<table>
  <caption>
    Table Title
  </caption>
  <tr>
    <th>Header</th>
  </tr>
</table>
```

## Table formatting and styling

Spanning rows and columns using `rowspan

`, `colspan`.

```html
<td rowspan="2">Spans two rows</td>
<td colspan="2">Spans two columns</td>
```

## Semantic Tags

Header (`<header>`), Navigation (`<nav>`), Main content (`<main>`), Sections (`<section>`), Footer (`<footer>`).

```html
<header>Header Content</header>
<nav>Navigation Links</nav>
<main>Main Content</main>
<section>Section Content</section>
<footer>Footer Content</footer>
```

---
