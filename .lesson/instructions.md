# JavaScript Variables
  Welcome to the introduction to **J**ava**S**cript(JS). Previously you worked on HTML/CSS or the structure and design of a webpage. JS does the logic for a webpage. That is, it does all the calculations and decision making. In order to make these decisions you need it to remember things. 
  
  JS remembers and holds things(`Data Types`) in `variables`. Think of a variable as an empty box with a name on it. You can construct or `declare` this empty box with `let [name]`
  
```javascript
let number
let container 
let cat
```

## Task 1
In index.js declare three variables. You can call them almost anything you want but lets start with `box, letters, dog`
#
Now that you have these 3 variables you need to put something inside them. The things to hold are called `data` and the types are `Number`, `String`, `Boolean`, Array and Object. For now you are going to focus on the first 3.

When you put them into the box you call it `variable assignment` and it looks like this variable = [data]:

The `//` is called a single line comment and anything that appears behind it is further notes for you

```javascript
number = 23 //type of number
container = "Sean Combs" //type of string
cat = false //type of boolean
```
## Task 2
Assign your variables `box, letters, dog` the number, string and boolean `91, "Biggy", true`
##

In your index.js you have declared variables with the `let` command and then on a different line assigned something to those variables using `=`

As a shortcut you can choose to declare and assign all in one line with let [name] = [data]

```javascript
let number = 23
let container = "Sean Combs"
let cat = false
```

## Task 3
Declare and assign 3 variables with whatever name and data you like.
##

As the name suggests `variables` can change. When you want to change a variable you call it `variable reassignment`

```javascript
let number //variable declaration
number = 23 //variable assignment
number = 43 //variable reassignment
```

Since you know the computer reads your code from top to bottem it is easy to know that `number` was first nothing then 23 and finally 43. However, JS is not always that simple. You will not always be able to look at your code and know what every variable is. When you want to see what a variable is holding at any moment you use console.log(`variable`) 

```javascript
let number //variable declaration
console.log(number) // ->undefined
number = 23 //variable assignment
console.log(number) // ->23
number = 43 //variable reassignment
console.log(number) // ->43
```

## Task 4
1. Take the variables `box`, `letter` and `dog`. console.log() each of them,
2. `reassign` the 3 variables
3. console.log() the three variables.
4. add to your code `console.log("A message for me at run time")`

When you hit the `Run` button at the top of the page you should see their values printed in the panel on the right.

##

## Task 5
A big part of being a developer is knowing how to `debug code`. The following code has errors or `bugs` in it. Cut and Paste it into you index.js. Attempt to run your code. I won't run. In fact, the console is showing `red` text, also known as `throwing an error`. Try to read and understand what it says. Also notice that some of your code has `red` squiggly lines under it. There is probably an error at or near there. If you hover your mouse over those words it will give you an error code. Use all of what you know and the error information given to `debug` your code. `YOU WILL KNOW YOU ARE DONE WHEN YOUR CODE RUNS WITHOUT ANY ERRORS`.

and it give yous this output:

square

circle

triangle

27

27

```javascript
let box = "square"
console.log(box)
let box = "circle"
console.log(Box)
box = "triangle"
console.log(box)
let thing = 27
box = thiNg
console.log(thiNg)
console.log(box)
```