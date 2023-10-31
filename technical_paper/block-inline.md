# Inline versus Block Elements.

In HTML we mainlty divide all the elements in two category i.e `block element` and `inline element`.

## Block-Level Elements:

Block-level elements are those that typically create a "block" or "box" in the layout. They start on a new line and extend the full width of their parent container. Some common block-level elements include:

* **< div >  :** A generic container element used for grouping and structuring content.

* **< p >  :** Represents a paragraph of text.

* **< h1 >, ... , < h6 >  :** Headings of various levels.

* **< ul >  :** Represents an unordered (bulleted) list.

* **< ol >  :** Represents an ordered (numbered) list.

* **< li >  :** List items within < ul > or < ol > elements.

* **< table >  :** Used to create tables.

* **< form >  :** Represents a form element for user input.

EXAMPLE
```HTML
<div>
  <h1>This is a heading</h1>
  <p>This is a paragraph of text.</p>
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
  </ul>
</div>
```

## Inline Elements:

Inline elements, on the other hand, do not create a new block in the layout. They flow within the content, allowing multiple inline elements to appear side by side on the same line. Some common inline elements include:

* **< span >  :** A generic inline container for styling and scripting purposes.

* **< a >  :** Represents a hyperlink.

* **< strong > and < em >  :** Used for text emphasis (bold and italic).

* **< img >  :** Represents an image.

* **< br >  :** Inserts a line break within text.

* **< i > and < b >  :** Used for italic and bold styling, though it's generally recommended to use < em > and < strong > for semantics.

```HTML
<p>This is a <a href="#">link</a> to a website. <strong>Important</strong> information here.</p>
```