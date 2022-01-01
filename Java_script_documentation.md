# Operators in java_scrit

**arithmetic operators**:

 - Additins +
 - Subtraction -
 - Multiplication *
 - Divion /
 - Modulus %
 - Increment Operator ++
 - Decrement operator --
    
> if the increment operator is given before the variable, then the increment will be happen before executing the variable. if it is given after the variable increment will be happen after the execution.

**arithmetic assignment Operators**

```
+=, -=, *=, /=, %=
a+=b means a = a+b
```
**Comparision Operators**

-  == checks two values are equal or not
-  != checks two values are not equal or not
-  *>* checks left values is greater than right value.
-  **>=** checks left value is greater than or equal to right value.
-  <= checks left value is less than or equal to right value.

**Logical Operators**

 - Logical And - &&
 - Logical Or - ||
 - Logical Not - !

**Bitwise Operators:**

- Bitwise AND - & > if any one value is 0, it return false(0).
- Bitwise OR - | > if any one value is non-zero, it will returns true(1).
- Bitwise Not - ~ > it reuturns all the opposite values.
- Bitwise XOR - ^ > if both the values are different, it consider the value as true(1).
- Left Shift - << > it will move the binary to left for one value, consider the begining value as 0.
- Right Shift - >> > it will move the binary to right for one value and removes if any values at the end.

**Converting a number to binary code**

   - we need to right the 2 power values from 0 to 8 or more in the reverse order.
   - check the nearest value of your number in the list.
   - give 1 below that number.
   - then check the nearset value for remaining number again give 1 below that number.
   - repeat the same process till your number finishes.
   - then give 0's below all the remaining values.
  
  check this example for 10 and 5 binary values.
```
        128   64    32  16  8   4   2   1

10 -                        1   0   1   0
5 -                         0   1   0   1
```

**Assignment Operators (=)**

- these are used to assign the values to a variable.
- var a = 10;

**Conditional (ternary) Operator ?:**

it is used to give a condition and two statements, if a condition is true, it will execute the first statement, else the second statement.

 - condition ? statement1 : statement2

# Functions in JavaScript

 - A function is a group or collection of reusable code which can be called from anywhere in our program.
 - Advantages:
   - Saves lot of time in writing same code multiple times.
   - we can execute set of code (function) based on event/action performed.
   - we can execute a function whenever we need by calling it.
 - functions are executed by creating an event for it.

**Function format**
```
function functionname(optional Parameters)
{
    functoin code
}
```

# Array's in JavaScript

 Array's are used to store multiple values in a variable,
  - we can create array's in two ways
    - var a = new Array(1,3,5,6,7);
    - var a =[1,3,5,6,7];
  - to find the length of an array we use
    - document.write(a.length);
    - order of array is started with 0.
  - to access a specific element in an array
    - document.write(a[2]);

# Conditional Statements in JavaScript

  - if statements are used to check a condition is statisfying or not,
  - we can check the if statements with

```
   if(condition1)
   {
     document.write();
   }
```
 - if the above condition is not satisfying we can write another condition with
```
else if(condition2)
{
  document.write()
}
```
 - in this way we can give an many else if condition as we need.
 - at the end of the statemens we should provide an else statement to give an output when non of the conditions are satisfing. 
```
else
{
  document.write();
}
```

 **Switch case**
 - switch case is used to check the set of conditions
 - if a condition is satisfied, we can break the statement there.
 - if non of the conditions are satisfied, then we print the defalut statement.

**loops**
- **for loops**
  - for loops are used to run a set of statements repeatedly until the conditions satifisies.
```
for(initiolization; condition; iteration)
{
  statement
}  
```
**while loop**
```
initalization;
while(condition)
{
  statements
  iteration;
}
```
# date in JavaScript

 - new Date()
 - new Date(milliseconds)
   - it will consider from 1970 jan 01 to till now.
 - new Date(datestring)
 - new Date(year, month, date[hour, minute, second, millisecond])

# Objects in JavaScript

- object: collection of Properties
- we define object with key value pairs,
  - var person = {name:'rajasekhar', age:'24', email:'mrrajasekhar@gmail.com'}
  - we can also add functions in a object and access them whenever we need.