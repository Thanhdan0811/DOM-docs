# DOM Hierarchy.
- DOM will map our HTML into a hierachical structure.
- Each tab has its own Window instance.

- console.log() => prints an array , object and message to the console, most times as a string.
- console.dir() => takes an object as its input, and prints it out as a JSON-like tree.
- document is one of the properties of Window.
- window.document => document
- document also have many properties.
- window => document => html => head || body

## Acess Dom
- form object is uniquely created for every single form on your page by the browser, automatically.

```
document.forms => HTMLCollection [form, form]

```

## What is BOM.
- Window is supplied by the Browser Object Model (BOM).
- BOM allow JS to talk to the browser about things other than the content of the page.
- Like navigator, screen, location, history
- The whole HTML document is a property of the Window object.
- window.console
- DOM is not HTML file. DOM can correct error html tag.

## Pseudo Element
- A css Pseudo-element is a keyword added to a selector that lets you style a specific part of an elements
- Ex : ::first-letter, ::before ::after, ::first-line.


## what is DOM
- THe DOM is built from our source HTML file.
- The DOM is always built from valid HTML.
- the DOM looks at our document object within our hierarchical stucture.
- every website has a DOM.
- this moel allows JS and other languages to access elements and text.
- Th DOM is alive - change it with js at any time.
- The DOM is not the same as our HTML code.
- Not the same as the render tree, not always what we see in DevTools.
