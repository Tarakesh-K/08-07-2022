1st Question

What is a Document Object?
The document object is your html, aspx, php, or other document that will be loaded into the browser. The document actually gets loaded inside the window object and has properties available to it like title, URL, cookie, etc. What does this really mean? That means if you want to access a property for the window it is window.property, if it is document it is window.document.property which is also available in short as document.property.

What is a Window Object?
The window is the first thing that gets loaded into the browser. This window object has the majority of the properties like length, innerWidth, innerHeight, name, if it has been closed, its parents, and more.

Window Vs Document
Window object : It is the top most object and outermost element of the object hierarchy.

Document object : Each HTML document that gets loaded into a window becomes a document object. The document contains the contents of the page. Using document object, JavaScript can modify, add and delete the HTML elements, attributes CSS styles in the page

The window object represents a window/tab containing a DOM document where as document object is property of window object that points to the DOM document loaded in that window.
