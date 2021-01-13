# Read 02: HTML Text, CSS Introduction, and Basic JavaScript Instructions

# HTML Book

* Chapter 2: “Text”

1. The sup element is used to contain characters that should be superscript such
   as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.
2. The sub element is used to contain characters that should be subscript. It is commonly
   used with foot notes or chemical formulas such as H2 0.


* Chapter 10: Ch.10 “Introducing CSS”
1. child selector: matches an element that is a direct child of another
    - li>a {}
2. descendant selector Matches an element that is a descendent of another specified element 
   (not just a direct child of that element)
    - p a {}
3. Adjacent sibling selector Matches an element that is the next sibling of another
    - h1+p {}
4. Genereal sibling selector Matches an element that is a sibling of another, although it
   does not have to be the directly preceding element
    - h1~p {}



# JavaScript Book

* Chapter 2: “Basic JavaScript Instructions”

1. what is a variable?
    - a way to store information to be called later
2. Booleans 
    - True or False values
3. Storing a Boolean in a variable
    - let inStock;
      let shipping;
      instock = true;
      shipping = false;
4. shorthand for creating variables
    - let price, quantity, total;
      price = 5;
      quantity = 14;
      total = price * quantity;
    - let price = 5, quantity = 14;
      total = price * quantity;
5. creatig an array
    - const colors;
      colors = [white, orange, purple];
      const el = document.elementById('colors')
      el.textContent = colors[0]
    - new Array('white ',
                'black',
                'custom');
      var el = document.getElementByid( ' colors' );
      el.innerHTML = colors.item(O); 



* Chapter 4: “Decisions and Loops”

1. Can use expressions with comparison operators
2. logical operatots allow you to compare the results of more than one comaprison operator
    - logical operators: 
        * && logical and operator
            - tests more than one condition
            - if expressions evaluate to true then the expressions returns true if one returns false then the expressions will return false. 
        * || logical or operator
            - tests one condition
            - if either expressions evaluates to true then the expressions returns true, if both evaluate to false then the expressions is false
        * ! logical not operator
            - takes a boolean value and reverses it
            - reverses the state of an expression