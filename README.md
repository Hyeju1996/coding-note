# JavaScript Journal of daily.

this is organized of JavaScript study for priview.

# JavaScript 
---

# 01/10/2024- Varible

## How to make "Hello person name" with varible code.

### example: 

"Hello, John" 

```
var person = Jhon"
```


## Exersice: 

1.Declar varible named petDog and name Rex

 **solution:**
```
var petDog = " Rex.";
var petDog = " Pepper";

console.log(petDog);
console.log(petCat);
console.log("my pet dog's name is:" + petDog);

var catSound = "purr";
var dogSound = "woof";
---
console.log (pet dog + "says" + dogSound);
console.log (pet cat + "says" + CatSound);
```


1. Task1: solution to: Declare a new varible named `petDog` and give it the name `Rex`.

`solution:` 

```
var petDog = 'Rex'
console.log (PetDog)
console.log ("my pet dog;s name is" + PetDog)
```
`Result:`
`Rex`
`my pet dog's me is Rex.`

2. Task2: solution to: Declare a new varible named `petCat` and give it the name `Pepper`.

`solution:`

``` 
var petCat = 'Pepper'
console.log (petCat)
console.log ("my pet cat's name is" + petCat);
```


3. Task3 solution to: console.log the `petDog` varible.

`solution:`

```
**var** petDog = 'Rex' // Task 1 solution
console.log (petDog);
console.log ("my pet dog's name is:" + PetDog);
```

`result:` 
` my pet dog's name is Rex`

---
# operation 01/15/2024

`operation = example code:`

`var` person `=` "Jim";

## Assignment operator:

> [!NOTE]
> Assignment operator:

1. `+` | `Addition` | `2+3`
2. `-` | `subtract` | `3-2`
3. `/` | `division` | `35/5`
4. `*` | `multlication`| `7x4`

## coparsion operator:

1. `>` Greater then `3 >2`
2. `<` Less then  `2 < 3`
3. `==` Equal to `5 ==5`
4. `!` Not Equal to `5!=6`

## logical operators:

1. `&&` checks for both condition to be true `a > 5 && a <10`.
2. `!!` checks for at least one consition to `a > 5 || > 10`.
3. returns `fales` if the result is `true` `! (a > 5)`.

## strings- 01/15/2024

`strings: a collection of charictors enclosed in signle quetoes or double quotes.` 

`""` this `strings`

**Example:**

1. `'Hello there!'`
2. `'Hello there 123!'`
3. `'Hello its lovely Day'`
     
     **Result:**
      - `"it is lovely day"`  


## Booleans - 01/16/2024

- Use Booleans to dermine if two compared valued are the same.
 `Example:`
 
 ` 1 > 2 = true`
 ` 1 > 2 = fales`

 > [!NOTE]
 > Booleans only have 2 possible values: `True` and `Fales`.

**Example:** 
[^1]: 1 == 2 -> `Fales` 

```diff
var score = 100
undefine 
score = 
<< 100
```

# exersice - operators in depath

1. Additional operator: 
  - logical AND operator: `&&`.

**solve:**

```
var score = 8
console.log ("Mid-level skills:" score > 0 && score < 10);
```

## WHY THIS IS RIGHT?
1. created a valueble named score and set it to `8`.
2. Use `console.log ()` that inclouds the `strings`. ` " mid-level skills: True"`

> [!NOTE]
> The coding is so important of detailes. When you type code watch it carefully. and check everything. 

---


## Exersice: 
### task1: using the logical && operator. 

1. Create a varible named `score` and set it to `&`. 
2. Use `console.log()` that incloudes the `strings "Mid-level skills:"` and compares the `score` varibles to above `0` and below `10` using the `&&` operator. 
 - The expected output in the `console.log` should be `Mid-level skills: True`

 **solve:**

``` 
var score = '8';
console.log ('Mid-level skills', score > 0 && score < 10);
``` 
`result:` 
`"mid-level skills: True"`;

---


### Task2. Using the logical || operator. 

-  You need to code a new varible named `timeRemaiding` and set it to `0`. You need to code a new varibles named `energy` and set it to `10`. 

**solve:** 

```
var timeRemainding = 0
var energy = 0
console.log ("Game over:", timeRemaing) = 0 || energy
```

### task 3: Using the modules operator, `%` to test if a given number is odd. 

1. The first varible, named `num1`, should be assighn a numver value of `2`. 
2. The second varibles, named `num2`, should be assigned a number value of `5`. 
3. The third value , `test1`, should be assigned the calculation of `num1 % 2`. 
 >[NOTE] 
 > exusing this code will return a number. 
4. The fourth varible, named `test2` , should be assigned the calculation of `num2 %2` 
>[NOTE]
> should be excusing this code will also return a number.

5. The fifth varible, named `rsult1`, should be assigned the result of comparing if the number stored in the `test1`  varible is not equal to `0`, in other words, this: `test1 == 0`. 

6. the sixth varible named `result2` should be assigned the result of comparing if the number stored in the `test2` varible is not equal to `0`, in other words, thisL `test1 == 0.`


**solve:**

```
var num1 = 2
var num2 = 5
var test1= num1 %2
var test2= num2 %2 
var test1= test1 == 0
var test2= test1 ==0
console.log ("Is," "Num1 an even number?" result1)
console.log ("Is," "Num2 an even number?" result 2)
```

## Conditional statement - 01/18/2024

# conditional Example:

In this reading, you will learn when to use the `if else` statement and use the `switch` statement. 

Both `if else` and `switch` are use to determine the program execution flow based on whether or not some conditions have been met.

This is why they are sometimes reffered to as `flow control statements`.

---

## Conditional statement - 01/18/2024

# conditional Example:

In this reading, you will learn when to use the `if else` statement and use the `switch` statement. 

Bith `if else` and `switch` are used to determine the program execution flow based on whether or not some conditions have been met.

This is why they are sometimes refered to as **flow control statements**. In other words, they control the flow of execution of your code, so that some code can be skipped, while other code can be executed.

At the heart of both flow control structures lies the evaluation of one or more conditions.

Generally, `if else` is better suited if there is a binary choice in the condition.

For example, `in plain English: if it's sunny, wear sunglasses. Otherwise, don't.`

In this case, using an if statement is an obvious choice.

When there are a smaller number of possible outcomes of truthy checks, it is still possible to use an if else 

statement, such as:

```
if(light == "green") {
    console.log("Drive")
} else if (light == "orange") {
    console.log("Get ready")
} else if (light == "red") {
    console.log("Dont' drive")
} else {
    //this block will run if no condition matches
    console.log("The light is not green, orange, or red");
}
```

To reinforce this point, here's an example of the earlier `if else conditional statement`, using the switch syntax: 

```
//converting the previous if-else example with switch-case
switch(light) {
   case 'green':
       console.log("Drive");
       break;
   case 'orange':
       console.log("Get ready");
       break;
   case 'red':
       console.log("Don't drive");
       break;
   default:
       //this block will run if no condition matches
       console.log('The light is not green, orange, or red');
       break;
}
```

---

# Exersice: 
In this exercise, you will practice working with `if else statements`. By the end of this exercise, you will be able to write an `if else statement` that determines your source of income based on your age. You will also be able to write a switch statement that determines your evening routine based on the day of the week.


**Complete the following steps to create: Are You Old Enough?**

1. Declare a varible age using the `var` keyword and set it to the number 10. 

2. Add an `if` statement that checks if the value of the `age` varible is greater than to the number `65` indside. 

3. Add an "`else if`", where you will check if the value of the age is less then `65` and greater than or qual to `18`. Inside this "`else if`" block, type `"console.log"` and then "Each " month you get salery".

4. Add another "`else if`"  and this time check if the value of the age is under **18**. inside the `"else if"` block, `"type console.log" and then "you get an allowance"` 

5. Add an "`else`" statement to captured any other value. Inside the block, type "console.log" and then "The value of the age varible is not numberical". 

**Try adjusting the age and executing the program to see how it will affect the output.**

## Code the days of the week program as a switch statement

1. On the next line, define a new variable, name it `day`, and set its value to `"Sunday"`.
2. Start coding a `switch` statement, passing the `day` variable as the expression to evaluate.

3. Inside the switch, add cases for every day of the week, starting with `'Monday'`, and ending with `'Sunday'`. Make sure to use string values for days. Inside each case, for now, just add a `console.log` `('Do something')`, and add a break; on the line below.

4. At the very bottom of the switch statement, add the default case and add a console.log('There is no such day').

5. Finally, update the `console.log` calls for each case, based on whatever activity you have on each of the days.

> [!TIP]

> If you need to make sure that multiple conditions are true in an if statement, you can do so using the && operator

> In JavaScript, the correct syntax of the "greater than or equal to" operator is: >=.

> Don't forget to add a break at the very end of each case in a switch statement.


**solve:**

```
var score = 10;

if (score > 40) {
  console.log("You passed!")
} 
else {
  console.log("You fail!")
}
```

**Task1:** 

### Step1: Declare a variable age using the var keyword and set it to the number 10.


 ```
 var age = 10;
if (age>=65){

console.log('You get your income from your pension');

}else if (age < 65 && age >=18){

console.log('Each month you get a salary');

}else if (age < 18){

console.log('You get an allowance');

}else {

console.log('The value of the age variable is not numerical');

}
```

---

# Looping constructs 01/21/2024

## The for loop:

``` 
for (var i = 1; i<4; i++) {
    console.log(i);
}
```


1. var i =0; => set the value
2. i <3; => Specify the condition
3. i++ ; => increment the counter

## The while loop

```
var i =1;

while (i < 4){
    console.log(i);
    i=i+1;
}
```

>[!NOTE]
> In our everyday life,
there are times when we have to repeat
some activity again and again.

---

# While loops

**while loops**
- code that repeats as long as a specified condition is true. 

## Example code:

```
while counter = 3

while (counter > 0 ) {
    console.log (counter);
    counter = counter -1;
}

console.log ('Happy new year!');
```

### Repetitive task with loops (solutions)

Here are the solutions to the `for` and while `loop` exercise.

**Task1:**
``` 
for (var i =1 <= 5; i++) {
    console.log(i);
};
console.log('Counting completed');
```

### Task 2: 

```
for (var i = 5; i > 0; I ---) {
    console.log (i);
};
console.log('countdown finished!');
```

### task 3

``` 
var i = 1;
while (i <6) {
    console.log(i);
};
console.log('counting completed!');
```
>[!NOTE]

Name your increment variable i. Update the variable in the while loop using `i++.`

### Task 4:

Write a "while" loop that will perform the exact same repetitive code like the one below:

```
var i = 5;
while (i >0) {
    console.log(i);
    i = i -1;
};
console.log('counting complted!');
```

>[!Note] 
In the while loop, decrement the value of i using: `i = i - 1.`

### Task 5

```
var year = 2018;
while (year < 2023) {
    console.log (year);
    year++
};

```

---

# Nested loops

Make use of `nested loops` to display the summer month two years.

## Loops and nested loops

Let's say I want to output a custom multiplication table.

This is a perfect use case scenario for nested loops.

The outer loop's counter variable will act as the first number to be multiplied, and the inner loop counter variable will act as the second number to be multiplied.

### Example code:
```
// single loop
for (var firstNum = 0; firstNum < 2; firstNum++) {
    console.log(firstNum);
}
```
The output of the above code will be:

`0`
`1`

This means that my for loop starts at 0 and stops after 1.

So now I can code what will later become the inner loop, whose counter variable will be the second number in this multiplication:

``` 
///single loop
for (var secondNum = 0; secondNum < 10;) {
console.log(secondNum);

}
```

This time, the output is:

0
1
2
3
4
5
6
7
8
9

Now's the time to combine the first and the second loop:

```
// Nest loops - one inside  another

for (var firstNum = o; firstNum <2; firstNum++){
   for (var secondNum = 0; secondNum < 10; secondNum++) {
    console.log(firstNum + "," + secondNum);
   }
}

```

Now that I'm nesting the second for loop inside the first one, and that I'm console logging the values of both counter variables as the loops are progressing, the output looks like this:

0, 0
0, 1
0, 2
0, 3
0, 4
0, 5
0, 6
0, 7
0, 8
0, 9
1, 0
1, 1
1, 2
1, 3
1, 4
1, 5
1, 6
1, 7
1, 8
1, 9

Now that I have a list of all the numbers that will be multiplied, having the actual result of this multiplication is as easy as updating the `console.log()` call:

```
//nested loops - one inside another
for (var firstNum = 0; firstNum < 2; firstNum++) {
    for (var secondNum = 0; secondNum < 10; secondNum++) {
        console.log(firstNum + " times " + secondNum + " equals " + firstNum * secondNum);
    }
}
```

The output now is:

`0 times 0 equals 0`
`0 times 1 equals 0`
`0 times 2 equals 0`
`0 times 3 equals 0`
`0 times 4 equals 0`
`0 times 5 equals 0`
`0 times 6 equals 0`
`0 times 7 equals 0`
`0 times 8 equals 0`
`0 times 9 equals 0`
`1 times 0 equals 0`
`1 times 1 equals 1`
`1 times 2 equals 2`
`1 times 3 equals 3`
`1 times 4 equals 4`
`1 times 5 equals 5`
`1 times 6 equals 6`
`1 times 7 equals 7`
`1 times 8 equals 8`
`1 times 9 equals 9`

This makes for some very interesting combinations.

For example, I can make a custom `division`table:

```
//nested loops - one inside another 
for (var i = 100; i > 10; i = i - 10) {
    for (var j = 10; j > 4; j = j - 5) {
        console.log(i + " divided by " + j + " equals " + i / j);
    }
}
```


Here's the output of the above `nested loop:`

`100 divided by 10 equals 10`
`100 divided by 5 equals 20`
`90 divided by 10 equals 9`
`90 divided by 5 equals 18`
`80 divided by 10 equals 8`
`80 divided by 5 equals 16`
`70 divided by 10 equals 7`
`70 divided by 5 equals 14`
`60 divided by 10 equals 6`
`60 divided by 5 equals 12`
`50 divided by 10 equals 5`
`50 divided by 5 equals 10`
`40 divided by 10 equals 4`
`40 divided by 5 equals 8`
`30 divided by 10 equals 3`
`30 divided by 5 equals 6`
`20 divided by 10 equals 2`
`20 divided by 5 equals 4`

Feel free to try out some other combinations of nested loop iterations, and see what kind of output you'll get.


--- 

## Uses of loops

In this reading, we'll discuss, at a very high level, the reasons to use loops in JavaScript.

Note that we will keep this discussion high-level because there are multiple "pieces of the puzzle" that are still missing from your understanding at this point.

This is why we will not get bogged-down in the detail of syntax and implementation, but instead, simply discuss how and why loops are used in everyday work of JavaScript developers.

Consider the following example: You work as a developer for an online store.

The store is selling letter cubes for toddlers, and the entire "Shop now" section of the site is organized in a layout where each cube on sale is displayed in a simple card component, with an image of the cube, the letter it teaches, a short description, and the price.

Cards are organized in rows, so that each row contains three cards - three different letters.

Each card is a preview of that specific letter cube on sale, and it's also a link to an entire page, dedicated to providing more info about the cubes, their teaching value, and providing the visitor with a way to complete their checkout process.

Now, here's a quick question: where would loops fit into displaying this grid of cards showcasing the letter cubes on sale?

To understand just how this works, let me code a basic prototype of how this might work.

Since you still don't have enough knowledge to display website layouts in browser with the help of JavaScript, for now I'll have to settle for using a simple string and the console.

```
var cubes = 'ABCDEFG';
//styling console output using CSS with a %c format specifier
for (var i = 0; i < cubes.length; i++) {
    var styles = "font-size: 40px; border-radius: 10px; border: 1px solid blue; background: pink; color: purple";
    console.log("%c" + cubes[i], styles)
}
```

[!NOTE]
In order to have the styles applied, try running this code snippet in your browser's console.

---

## The quize & isn't right. 
1. You can run JavaScript in a web browser's devtools console.

**Answer:** 
 - True. 
 Because the devtools console is useful for running JavaScript code. 

2. which of the following are valid comments in JavaScript? Select all that apply.
/coment1 is wrong answer. because writing JavaScript code isn't right.
**// coment 2 is correct answer.**

3. Which of the following are valid data types in JavaScript? Select all that apply.
**Answer:** 
 - string 
 - Numbers
 - booleans 

 4. Which of the following is the logical AND operator in JavaScript?

 **Answer:**
   - `&&`sign. 

5. Which of the following is the assignment operator in JavaScript?
  **Answer:** 
    - `===` this is the correct answer.

6. How many times will the following code print the word 'Hello'

```
 for(var i = 0; i <= 5; i++) {
    console.log("Hello");
  }
```

**incorrct answer:**
- 4. 

the right answer:




7. What will print out when the following code runs?

```
var i = 3;
  var j = 5;

  if(i == 3 && j < 5) {
    console.log("Hello");
  } else {
    console.log("Goodbye");
  }
  ```


**incorrect answer:** 
  - Hello

**correct answer**


# Function:
 
## Add two numbers

```
var a = 10;
var b = 20;
var c = a + b;

console.log(c);
```

## Function: 

```
Function addTwoNums(){
    //code goes here
}
```

### Other Example Function:

```
function addTwoNums() {
    var a = 10;
    var b = 20;
    var c = a + b;

console.log (c);

AddTwoNums(); 
}
```

### Other code:

``` 
functiom addTwoNums (a,b) {
    var c = a +b; 
    console.log (c);
}

add TwoNums(2,2);
add TwoNums(4,4);
```

**In console:**
`4`
`8`

# Array:

**Example:**

0,1,2,3,4

1 -> wheat

``` 
var carriage0 ="wheat";
```

`console.log (carriage0);`

console: wheat

## Array literal Syntax
`[]`

## Example of code: 

```
var train = ["wheat" , "barley", "potato", "salt", "rocks"];

console.log(train[0]);
```

console: wheat

## Example function/Array code:
- In this reading, you will learn how to build and call a function. The purpose of this reading is to provide you with an example of function declaration (build) and function invocation (call). In the next lesson you will be writing the code. By the end of this reading you should be able to: Code simple functions that can accept an array and iterate through it  

Let's start with giving our function declaration a name:


```
function listArrayItems(arr) {
     // ... code to be added...
    }

```

So, I've declared a `listArrayItems` function, and I've set it up to accept a single parameter, `arr - which stands for an array`.

Now, I'll need to code a for loop to loop over an array.

As covered in previous lessons in this course, a for loop needs the following information: 

1. the starting loop counter value as a temporary variable i 

2. the exit condition (the maximum value of the loop counter variable i, above which the loop no longer runs) 

3. how to update the value of i after each loop

Here's the information I'll use in this function declaration: 1. The loop's starting counter will be 0. The reason for setting it to zero is due to the fact that arrays are also counted from zero. 

This means that I'll have a one-to-one mapping of the current value of the i variable at any given time, corresponding to the same index position of any item in the arr array 2. 

The for loop's exit condition is when the value of i is equal or greater than arr.length. 

Since the arr.length counts the number of items in the array from one, and the array items are indexed from zero, this effectively means that as soon as i is equal to arr.length, the loop will finish and any other code after it will be run. 

This practically means that the exit condition for this for loop will be i < arr.length returning false. 


In other words, as long as i < arr.length is true, this for loop will continue to run. 3. To make sure that none of the items in the arr array are skipped, I have to increase the value of i by 1 after each loop.

Now that I know exactly how my for `loop `should behave, I can add it to my l`istArrayItems() function:`

```

function listArrayItems(arr) {
    for (var i = 0; i < arr.length; i++) {
        // ... code pending here ...
    }
}
```

Now all that I have left to decide is how I want to output each item from the received arr array.

It can be as simple as console logging the array item index of the current value of `i:`

```
function listArrayItems(arr) {
    for (var i = 0; i < arr.length; i++) {
        console.log(arr[i]) //display the array item where the index is euqal to i
    }
}
```
