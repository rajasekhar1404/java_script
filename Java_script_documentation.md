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