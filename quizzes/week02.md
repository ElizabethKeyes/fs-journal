# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, const, and var
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a subprogram or piece of code that will perform a pre-defined set of actions when called. Functions can also be dependent on various sets of conditions to be checked before running and can have values passed through to them. Functions will always return a value. If no return value is specified, it will return `undefined`.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID is an acronym that represents the 5 principles of object-oriented class design, as follows:

S - Single-responsibility principle: States that each class or function should serve one purpose. If a function is doing too many things, unexpected issues may arise or the code may be excessively complicated. Functions should be purpose built. If it needs to do more, create a separate function and call it within the first.

O - Open-closed principle: The code is open for extension, but closed for modification. For example, if we're drawing an array of elements to the screen, we should have a means of adding to that array without directly writing into it. There should be an add() function of some sort that is utilized so that we can extend the array without directly modifying it.

L - Liskov substitution principle: Objects of a superclass should be replaceable with objects of its subclass while still maintaining functionality.

I - Interface segregation principle: "Clients should not be forced to depend upon interfaces that they do not use". Similar to the Single-responsibility principle, the interface segregation principle is about dividing things up into smaller chunks to reduce the frequency of making changes, as well as their unintended side effects. 

D - Dependency Inversion Principle: Designed so that high-level modules with complex logic are easily reusable and unaffected by changes in low-level modules providing utility features. If you have values to reference, you could create a variable and add that value to the variable. Then include the variable in your function instead of the static value. This will make any changes needed much easier to accomplish, as well as ensuring they're happening in the same way throughout your code.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The pineapple has an index of two. Arrays are numbered beginning with zero, so the third item has an index of two.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if statements, else statements, and if else statements are all conditionals. They will check for a set of conditions/requirements before running the code inside.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
That is the loop counter or updating value. We increment or decrement this value to determine the number of times that the loop will run. To increase `i` by one on each iteration, we'd write i++.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. The first file accessed to render the DOM is the HTML file. If any other files are to be accessed, they need to be "pointed at" by the HTML.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Boolean, null, undefined, string, number, bigInt, symbol, object, function
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is defined when first writing a function and allows arguments to be passed through to it. The actual arguments are the values that are passed through when calling the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive data types are not objects and do not have methods, whereas reference data types do. An example of a primitive data type would be a boolean, string, or number while a reference data type would be an object, array, or function.
```