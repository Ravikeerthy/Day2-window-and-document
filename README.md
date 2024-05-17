# Day2-window-and-document


Difference between Document and Window Objects

The Browser Object Model(BOM)
Some objects in the Browser Object Model stand in for the tab or window currently open in the browser. Window objects, which can represent tabs, iframes, or just windows, are always located at the very top of the BOM. A window object can store information such as the current page, the user's location, and the contents of the browser. Although a window object in a multi-tab browser only represents a single tab, its resizeTo() method and innerHeight and innerWidth properties have an effect on the entire browser window.

Document Object Model
The browser builds a Document Object Model (DOM) of the page as soon as it loads. The document object is a hierarchical representation of all HTML elements, including HTML, HEAD, BODY, and others. It stands in for the entire HTML document as its foundational element.

Window Vs Document

A window object represents a tab or window that loads DOM documents, and a document object is a property of the window object that references the loaded content.

Since window is a global object, you can access its document object directly or through the window. document property.

There is also an important difference in the fact that window objects and document objects both have methods and properties. Although the two objects behave differently, they share a handful of method names. 

Screen is a window property that stores information about the browser's screen. It refers to the screen object linked with that window object. This is where you may see the dimensions of the screen, including its height, colour depth, pixel depth, and breadth.

Both window.screen and the screen object directly access the screen, just like in a document. There are no methods available to the screen object, unlike the window and document objects.
