# Readings : Forms and JS Events

## HTML 

* Chapter 7: Forms

1. forms cant be sent using 1 of two methods.
    - get: the values from the form are added to the end of the URL specified in
      the action attribute.
    - post: With the post method the values are sent in what are
      known as HTTP headers.
2. You can use the maxlength attribute to limit the numberof characters a user may enter
   into the text field. 
3. The "textarea" element is used to create a mutli-line
   text input.
4. The "select" element is used to create a drop down list box.
5. You can group related form controls together inside the "fieldset" element. This is
   particularly helpful for longer forms.


* Chapter 14: Lists, Tables & Forms

1. Went over the many lists you can do in HTML and the styling of them. 



## JavaScript

* Chapter 6: Events

1. When an event has occurred, it is often described as having fired or been raised.
2. How events trigger javascript code. 
    - select the element mdpes tpi wamt the script to respond to. 
    - indicate which event on the selected nodes will trigger the reponse.
    - state the code you want to run the event. 
3. There are 3 ways to bind and event to and element
    - HTML event handlers
    - Traditional DOM event handlers
    - DOME level 2 even listeners.
        * The syntax is quite different and, unlike traditional event handlers, these newer event listeners allow
          one event to trigger multiple functions. As a result, there are less likely to be conflicts
          between different scripts that run on the same page. 
4. When the interpreter sees the parentheses after a function call, it runs the code straight away.
   In an event handler, you want it to wait until the event triggers it.
5. if you need to pass arguments to a function that is called by an event handler or listener, you wrap the function
   call in an anonymous function. 
6. The flow of event really only matters when your code has event handlers on an element and one of it ancestor or descendent elements.
7. When the event object is npassed into a function, it is often given the parameter name e (for event).
8. "stopPropagation()": Once you have handled an event using one element, you may want to stop that event from bubbling up to its ancestor
   elements (especially if there are separate event handlers responding to the same events on the containing elements). 
9. "preventDefault()": Prevents the default behavior nof such elements (e.g., to keep the user on the same page
    rather than following a link or being taken to a new page after submitting a form).
