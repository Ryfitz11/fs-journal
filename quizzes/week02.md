# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?

```
let const and var
```
**2.** What is the definition of a function?

```
subprogram designed to perform a particular task
```
**3.** What are the `SOLID` principles?

```
S - Single-responsiblity Principle
O - Open-closed Principle
L - Liskov Substitution Principle
I - Interface Segregation Principle
D - Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?

```
2
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?

```
you.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:

```
if (condition1) {
  //  block of code to be executed if condition1 is true
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true
} else {
  //  block of code to be executed if the condition1 is false and condition2 is false
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
i++ 
```

```
incrumentor 
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?

```
Document Object Model
HTML
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```  
Boolean 
Null 
Undefined 
Number   
String 
Symbol
Dynamic
Primitive
Objects
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?

```
a parameter is the place holder and the argument is the data that is used in its place
```
**11.** What is the difference between a `primitive` value and a `reference` value?

```
numbers, booleans, strings, symbols, and special values null and undefined are all primitive values.
objects, arrays and functions are reference values.
```