# Module 6 and 7

## Creating Objects from User Inputs

JavaScript allows us to add interactable elements to our websites. Using JavaScript we are able to add functions that act as tiny programs for us. As an example, if we have two empty `input` values in our HTML that we ask a user to enter their first and last name into, we use JavaScript to take the values they entered and have it return the combined inputs (plus other things if we desire). These functions can be triggered by a variety of sources; and the most important method we use is the `addEventLister()` method.

Not all functions require the user to specifically call them, we can have functions that act all on their own and can be called when the page loads.

### Variable Types in JavaScript

`var` is the keyword for storing data in a named *variable*. Var is the original keyword for variables, and is what should be used if you want your page to run on older browsers.

`let` is a newer keyword for variables, though it is one that you allow to be changed in your code.

`const` is another newer keyword for variables, though this one cannot be changed. If you declare a variable with *const*, you're not able to change it throughout your code.

### Declaring JavaScript Variables

Declaring Variables is a lot like simple math functions. Variables are great for functions as you can set them to mean something complicated and won't need to type out that complicated expression every time you want to use it; instead just use the keyword. As an example, some very simple declarations look like:

- `let x = 5;`
- `let y = 8;`
- `const name = "John";`
- `let z = y + x;`

All declarations need an `=` symbol in between what your *variable name* is and what you are *assigning* to that variable name. End it with a semi-colon.

## The Control Flow of Scripts

When running scripts, code is read from top-to-bottom. However, there are structures that can change the flow, such as conditionals and loops.

A conditional statement *(ie: an `if/else` statement)* will check to see if a specific condition is true, and depending on its answer will run the top-most command that is checked as true. This can result in code being skipped if it is considered *false*, or more code being skipped if a *true* statement is before it in the conditional.

Loops will also cause code to run through the same code until it meets a certain criteria. 

## JavaScript Functions

## JavaScript Operators

There are multiple sign-operators which do many things within JavaScript. Some of the most common are assigning values to variables, adding variables and/or values together, and comparing two variables and/or values.

`=` - The **assignment** operator. This will asign a value to a specified value, and will overwrite previous declaration if further in the code.

`+` - The **addition** operator. Similar to math, the *+* symbol will add two or more things together. It can also concatenate strings or numbers onto a previously assigned variable.

### Arithmetic Opertors

`+` - Addition
`-` - Subtraction
`*` - Multiplication
`**` - Exponentiation
`/` - Division
`%` - Modulus (Division Remainder)
`++` - Increment
`--` - Decrement

### Assignment Operators

`=` - Assignment
`+=` - Adding something onto an assigned variable.
`-=` - Remove something from an assigned variable.
`*=` - Multiplying something onto an assigned variable.
`/=` - Dividing something from an assigned variable.
`%=` - Getting the remainder from an assigned variable.
`**=` - Exponentially multiplying an assigned variable.

### Comparison Operators

`==` - Equal to
`===` - Equal value and equal type
`!=` - Not equal to
`!==` - Not equal value or not equal type
`>` - Greater than
`<` - Less than
`>=` - Greater than or equal to
`<=` - Less than or equal to

### Logical Operators

`&&` - Logical and
`||` - Logical or
`!` - Logical not
