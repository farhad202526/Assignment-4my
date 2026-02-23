



<!-- ## Answers to Questions -->

 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Auswer =  when we want to get id in DOM than use getElementById('id')    and when we want to get class in Dom than use    getElementByClassName('class name ') 

when need single element than use    querySelector('.$$')
       when need multiful element than use    querySelectorAll('  ')





 2. How do you create and insert a new element into the DOM?

    Aunswer 
     const new = doumdocument.createElement("div");






 3. What is Event Bubbling? And how does it work?

 Aunswer  event bubblig is DOM event .it's event happane in all child  to parent element . 

 it's work like moving forward from the stump of a tree .

 4. What is Event Delegation in JavaScript? Why is it useful?
 Aunswer   Event delegation is a technique where a single event listener is added to a parent element to manage events for all its current and future child elements by leveraging event bubbling.


 it useful
It improves performance by reducing memory usage and ensures that dynamically added elements automatically have event functionality without needing new listeners.


### 5. What is the difference between preventDefault() and stopPropagation() methods?
 Aunswer preventDefault() stops the browser's default action.

 stopPropagation() stops the event from bubbling up





