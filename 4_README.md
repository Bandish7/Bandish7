### Learn
# HTML Structure
HTML is organized as a collection of family tree relationships.  When an element is contained inside another element, it is considered the child of that element. The child element is said to be nested inside of the parent element.
```
<body>
  <p>This paragraph is a child of the body</p>
</body>
```
In the example above, the `<p>` element is nested inside the `<body>` element. The `<p>` element is considered a child of the `<body>` element, and the `<body>` element is considered the parent. You can also see that we’ve added two spaces of indentation (using the space bar) for better readability.

Since there can be multiple levels of nesting, this analogy can be extended to grandchildren, great-grandchildren, and beyond. The relationship between elements and their ancestor and descendent elements is known as hierarchy.

Let’s consider a more complicated example that uses some new tags:
```
<body>
  <div>
    <h1>Sibling to p, but also grandchild of body</h1>
    <p>Sibling to h1, but also grandchild of body</p>
  </div>
</body>
```
In this example, the `<body>` element is the parent of the `<div>` element. Both the `<h1>` and `<p>` elements are children of the `<div>` element. Because the `<h1>` and `<p>` elements are at the same level, they are considered siblings and are both grandchildren of the `<body>` element.

Understanding HTML hierarchy is important because child elements can inherit behavior and styling from their parent element. 


### Instructions
* Add the paragraph below as a child of the div element.
```
<p>This paragraph is a child of the div element and a grandchild of the body element</p>
```


### Questions
* Is it correct to say that the `<body>` element is nested within the `<html>` element?
* What sorts of things can child elements inherit from their parents?
* What is the point of nesting the `<p>` element in a `<div>` element?