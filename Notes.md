
# HTML & HTML5 Notes

## Basic Structure of HTML
- **`<html>`**: Root element of an HTML document.
- **`<head>`**: Contains metadata, links to scripts and styles.
- **`<title>`**: Sets the title of the webpage (shown in the browser tab).
- **`<body>`**: Contains the main content of the webpage.

---

## Block Element Tags
- **Headings**: 
  - **`<h1>` to `<h6>`**: Define headings of different levels; `<h1>` is the highest.
- **Paragraph**: 
  - **`<p>`**: Represents a paragraph of text.
- **Horizontal Rule**: 
  - **`<hr/>`**: Creates a thematic break (horizontal line).
- **Line Break**: 
  - **`<br/>`**: Inserts a line break.
- **Lists**:
  - **Unordered List**: 
    - **`<ul>`**: Creates a bulleted list.
    - **`<li>`**: Defines a list item.
  - **Ordered List**: 
    - **`<ol>`**: Creates a numbered list.
    - **`<li>`**: Defines a list item.
  - **Definition List**: 
    - **`<dl>`**: Creates a list of terms and definitions.
    - **`<dt>`**: Defines a term.
    - **`<dd>`**: Defines the description of the term.

---

## Tag Attributes for Block Elements
- **Type**: Specifies the type of element (e.g., list type).
- **Start**: Specifies the start value of the first list item in an ordered list.
- **Align**: Specifies the alignment of the element.

---

## Inline Element Tags
- **Text Formatting**:
  - **`<i>`**: Italic text.
  - **`<em>`**: Emphasized text (usually italic).
  - **`<b>`**: Bold text.
  - **`<strong>`**: Strong importance (usually bold).
  - **`<big>`**: Larger text.
  - **`<small>`**: Smaller text.
  - **`<sub>`**: Subscript text.
  - **`<sup>`**: Superscript text.
  - **`<u>`**: Underlined text.
  - **`<ins>`**: Inserted text (underlined).
  - **`<del>`**: Deleted text (strikethrough).
  - **`<s>`**: Strikethrough text.
  - **`<mark>`**: Highlighted text.

---

## Image, Marquee & Anchor Tags
- **Image**: 
  - **`<img/>`**: Embeds an image.
  - **Attributes**:
    - **`src`**: Source of the image.
    - **`title`**: Tooltip text when hovering over the image.
    - **`alt`**: Alternative text for accessibility.
    - **`width`** & **`height`**: Dimensions of the image.
  
- **Marquee**: 
  - **`<marquee>`**: Creates scrolling text.
  - **Attributes**:
    - **`direction`**: Specifies scroll direction.
    - **`behavior`**: Specifies how the text scrolls.
    - **`scrollamount`**: Specifies the speed of scrolling.
  
- **Anchor**: 
  - **`<a>`**: Creates hyperlinks.
  - **Attributes**:
    - **`href`**: URL of the link.
    - **`target`**: Specifies how to open the link (e.g., in a new tab).
  - **Link Types**:
    - **Bookmark Link**: Links to a specific part of a page using an ID.
    - **Internal Link**: Links to another section of the same page.
    - **External Link**: Links to a different webpage.

---

## Form & Table Tags
- **Form**: 
  - **`<form>`**: Defines a form for user input.
  - **Input Types**: 
    - **`<input type="text">`**: Single-line text input.
    - **`<input type="email">`**: Email input.
    - **`<input type="password">`**: Password input.
    - **`<input type="file">`**: File upload input.
    - **`<input type="checkbox">`**: Checkbox input.
    - **`<input type="radio">`**: Radio button input.
  - **Attributes**:
    - **`required`**: Specifies that an input field must be filled out.
    - **`selected`**: Preselects an option in a dropdown.

- **Table**:
  - **`<table>`**: Defines a table.
  - **Row and Cell Tags**:
    - **`<tr>`**: Table row.
    - **`<th>`**: Table header cell.
    - **`<td>`**: Table data cell.
  - **Attributes**:
    - **`cellspacing`**: Space between cells.
    - **`cellpadding`**: Space within cells.
    - **`border`**: Border width.
    - **`width`** & **`height`**: Table dimensions.
    - **`bgcolor`**: Background color of the table.

---

## HTML5 Introduction
### Differences Between HTML and HTML5
- HTML5 introduces new semantic elements and multimedia support.

### New HTML5 Tags
- **Semantic Tags**:
  - **`<header>`**: Defines a header for a document or section.
  - **`<nav>`**: Defines a navigation section.
  - **`<section>`**: Defines a section in a document.
  - **`<article>`**: Represents a self-contained composition.
  - **`<aside>`**: Defines content aside from the main content.
  - **`<footer>`**: Defines a footer for a document or section.
  
- **Multimedia Tags**:
  - **`<audio>`**: Embeds audio content.
    - **Attributes**: `controls`, `muted`, `loop`.
  - **`<video>`**: Embeds video content.
    - **Attributes**: `controls`, `muted`, `loop`.
  - **`<iframe>`**: Embeds another document within the current document.

## Summary
These notes provide a comprehensive overview of HTML and HTML5 tags, their attributes, and practical uses. By mastering these elements, students can effectively structure and style web content.

