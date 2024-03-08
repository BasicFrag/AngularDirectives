# Types of Directives

In Angular, we have two types of Directives.

* **Attribute Directives**:
It has this name because these types of Directives rest within an element in the view of document;   
Usually these don't change much, if any, of the DOM (*Document Object Model*);  
Used mainly for adding and/or changing the element that contains the directive.

* Examples:
  * ngClass (adds a class to the element)
  * ngStyle (adds a inline-style to the element)


* **Structural Directives**:
Like the name implies, it changes the whole structure of the Document by inserting and/or removing
elements from the DOM.  
Usually, they are preceded by a asterisk and also sits within a element.

* Examples:

  * ngIf (inserts or removes an element with the value that is being assigned to it is a boolean *or* an expression that return a boolean)

  * ngFor (iterates an array and inserts the elements based on the number of values that are being iterated).
