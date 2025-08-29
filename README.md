# PH-Assignment-05
 
 1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll

Solution:
getElementById("id"): Finds one element by its ID (only one result).

getElementsByClassName("class"): Finds all elements with the given class (returns a list).

querySelector("selector"): Finds the first element matching a CSS selector (like classes or IDs).

querySelectorAll("selector"): Finds all elements matching a CSS selector (returns a list).

2. How to create and insert a new element into the DOM?

Solution:
Create an element:

let newDiv = document.createElement("div");


Add content or attributes:

newDiv.textContent = "Hello!";


Insert into the DOM:

document.body.appendChild(newDiv);

3. What is Event Bubbling and how does it work?

Solution:
Event Bubbling means an event triggered on a child element also affects its parent elements.
Example: Clicking a button inside a div will also trigger the div’s event.

4. What is Event Delegation in JavaScript? Why is it useful?

Solution:
Event Delegation is adding one event listener on a parent element to handle events for all child elements.
Useful because it saves memory and works for new child elements added later.

5. Difference between preventDefault() and stopPropagation()

Solution:
preventDefault(): Stops the default action (like following a link or submitting a form).

stopPropagation(): Stops the event from bubbling up to parent elements.

