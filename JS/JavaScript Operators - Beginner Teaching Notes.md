# JAVASCRIPT OPERATORS
## Beginner-Friendly Teaching Notes

---

# 1. WHAT IS AN OPERATOR?

An operator is a special symbol or keyword used to perform an operation on values.

In simple language:

OPERATOR = SOMETHING THAT TELLS JAVASCRIPT TO PERFORM AN ACTION

Examples:

```javascript
10 + 20
```

Here:

`+` is an operator.

It tells JavaScript:

"Add these two numbers."


Another example:

```javascript
20 > 10
```

Here:

`>` is an operator.

It asks:

"Is 20 greater than 10?"


Another example:

```javascript
age = 20
```

Here:

`=` is an assignment operator.

It tells JavaScript:

"Store 20 inside age."


---

# 2. BASIC SYNTAX

General syntax:

```text
value operator value
```

Example:

```javascript
10 + 20
```

Here:

```text
10     -> first value
+      -> operator
20     -> second value
```

Result:

```text
30
```


Another example:

```javascript
50 > 20
```

Result:

```text
true
```


---

# Categories OF OPERATORS
    A. Binary ==> has two opearands/variable 
    B. Unary  ==> has single opearands/variable

# 3. TYPES OF OPERATORS IN JAVASCRIPT

The important JavaScript operators are:

1. Arithmetic Operators (Binary)
2. Assignment Operators (Binary)
3. Comparison Operators (Binary)
4. Logical Operators (binary/unary)
5. Increment and Decrement Operators (++/--) (Unary)
6. String Operators
7. Ternary Operator


For beginners, focus first on:

Arithmetic
Assignment
Comparison
Logical
Increment/Decrement
String
Ternary


---

# 4. ARITHMETIC OPERATORS

Arithmetic operators are used to perform mathematical calculations.

The main arithmetic operators are:

```text
+       Addition
-       Subtraction
*       Multiplication
/       Division
%       Remainder
**      Exponent
```


---

# 5. ADDITION +

The `+` operator is used to add numbers.

Example:

```javascript
let a = 10;
let b = 20;

let result = a + b;

console.log(result);
```

Output:

```text
30
```


Another example:

```javascript
let price1 = 100;
let price2 = 200;

let total = price1 + price2;

console.log(total);
```

Output:

```text
300
```


REAL WORLD EXAMPLE:

A customer buys:

Pen = 20
Notebook = 50

```javascript
let pen = 20;
let notebook = 50;

let total = pen + notebook;

console.log(total);
```

Output:

```text
70
```


---

# 6. SUBTRACTION -

The `-` operator subtracts one number from another.

Example:

```javascript
let a = 50;
let b = 20;

let result = a - b;

console.log(result);
```

Output:

```text
30
```


REAL WORLD EXAMPLE:

Bank balance:

```javascript
let balance = 5000;
let withdrawal = 1000;

let remaining = balance - withdrawal;

console.log(remaining);
```

Output:

```text
4000
```


---

# 7. MULTIPLICATION *

The `*` operator is used for multiplication.

Example:

```javascript
let price = 100;
let quantity = 5;

let total = price * quantity;

console.log(total);
```

Output:

```text
500
```


REAL WORLD EXAMPLE:

A shop sells:

1 item = Rs. 100

Customer buys:

5 items

Calculation:

```text
100 × 5 = 500
```


JavaScript:

```javascript
let price = 100;
let quantity = 5;

let total = price * quantity;

console.log(total);
```


---

# 8. DIVISION /

The `/` operator is used for division.

Example:

```javascript
let totalMarks = 500;
let subjects = 5;

let average = totalMarks / subjects;

console.log(average);
```

Output:

```text
100
```


Another example:

```javascript
let money = 1000;
let people = 4;

let share = money / people;

console.log(share);
```

Output:

```text
250
```


---

# 9. REMAINDER %

The `%` operator gives the remainder after division.

This is very important.

Example:

```javascript
10 % 3
```

3 goes into 10 three times.

```text
3 × 3 = 9
```

Remaining:

```text
1
```

Therefore:

```javascript
console.log(10 % 3);
```

Output:

```text
1
```


Another example:

```javascript
console.log(20 % 5);
```

Output:

```text
0
```


Because:

```text
20 ÷ 5 = 4

Remainder = 0
```


---

# 10. REAL WORLD USE OF %

The remainder operator is very useful for checking EVEN and ODD numbers.

If:

```text
number % 2 = 0
```

The number is EVEN.

If:

```text
number % 2 != 0
```

The number is ODD.


Example:

```javascript
let number = 10;

console.log(number % 2);
```

Output:

```text
0
```

So:

10 is EVEN.


Example:

```javascript
let number = 7;

console.log(number % 2);
```

Output:

```text
1
```

So:

7 is ODD.


We will use this later with `if` statements.


---

# 11. EXPONENT **

The `**` operator is used for power.

Example:

```javascript
let result = 2 ** 3;

console.log(result);
```

Output:

```text
8
```


Because:

```text
2 × 2 × 2 = 8
```


Another:

```javascript
console.log(5 ** 2);
```

Output:

```text
25
```


Because:

```text
5 × 5 = 25
```


---

# 12. ARITHMETIC OPERATOR SUMMARY

```text
+       Addition
-       Subtraction
*       Multiplication
/       Division
%       Remainder
**      Power
```


Example:

```javascript
let a = 20;
let b = 5;

console.log(a + b);   // 25
console.log(a - b);   // 15
console.log(a * b);   // 100
console.log(a / b);   // 4
console.log(a % b);   // 0
console.log(a ** b);  // 3200000
```


---

# 13. ASSIGNMENT OPERATORS

Assignment operators are used to assign values to variables.

The basic assignment operator is:

```text
=
```


Example:

```javascript
let age = 20;
```


Meaning:

Store `20` inside `age`.


---

# 14. BASIC ASSIGNMENT

Example:

```javascript
let balance = 5000;
```

We can change it:

```javascript
balance = 6000;
```

Now:

```text
balance = 6000
```


Another:

```javascript
let marks = 50;

marks = 75;

console.log(marks);
```

Output:

```text
75
```


---

# 15. += OPERATOR

`+=` means:

ADD AND ASSIGN


Example:

```javascript
let balance = 1000;

balance += 500;

console.log(balance);
```

Output:

```text
1500
```


This:

```javascript
balance += 500;
```

is similar to:

```javascript
balance = balance + 500;
```


REAL WORLD:

Bank balance:

```javascript
let balance = 5000;

balance += 2000;
```

New balance:

```text
7000
```


---

# 16. -= OPERATOR

`-=` means:

SUBTRACT AND ASSIGN


Example:

```javascript
let balance = 5000;

balance -= 1000;

console.log(balance);
```

Output:

```text
4000
```


Equivalent to:

```javascript
balance = balance - 1000;
```


---

# 17. *= OPERATOR

`*=` means:

MULTIPLY AND ASSIGN


Example:

```javascript
let price = 100;

price *= 5;

console.log(price);
```

Output:

```text
500
```


Equivalent:

```javascript
price = price * 5;
```


---

# 18. /= OPERATOR

`/=` means:

DIVIDE AND ASSIGN


Example:

```javascript
let money = 1000;

money /= 4;

console.log(money);
```

Output:

```text
250
```


Equivalent:

```javascript
money = money / 4;
```


---

# 19. %= OPERATOR

`%=` means:

REMAINDER AND ASSIGN


Example:

```javascript
let number = 10;

number %= 3;

console.log(number);
```

Output:

```text
1
```


Equivalent:

```javascript
number = number % 3;
```


---

# 20. ASSIGNMENT OPERATOR SUMMARY

```text
=       Assign
+=      Add and assign
-=      Subtract and assign
*=      Multiply and assign
/=      Divide and assign
%=      Remainder and assign
```


Example:

```javascript
let x = 10;

x += 5;   // 15
x -= 3;   // 12
x *= 2;   // 24
x /= 4;   // 6
x %= 4;   // 2
```


---

# 21. COMPARISON OPERATORS

Comparison operators are used to compare two values.

The result is always:

```text
true
```

or:

```text
false
```


Main comparison operators:

```text
==      Equal value
===     Equal value and type
!=      Not equal value
!==     Not equal value or type
>       Greater than
<       Less than
>=      Greater than or equal
<=      Less than or equal
```


---

# 22. GREATER THAN >

Example:

```javascript
console.log(20 > 10);
```

Output:

```text
true
```


Because:

20 is greater than 10.


Example:

```javascript
console.log(5 > 10);
```

Output:

```text
false
```


---

# 23. LESS THAN <

Example:

```javascript
console.log(10 < 20);
```

Output:

```text
true
```


Example:

```javascript
console.log(50 < 20);
```

Output:

```text
false
```


---

# 24. GREATER THAN OR EQUAL >=

Example:

```javascript
console.log(20 >= 20);
```

Output:

```text
true
```


Because 20 is equal to 20.


Example:

```javascript
console.log(25 >= 20);
```

Output:

```text
true
```


Both are true because:

25 is greater than 20.


---

# 25. LESS THAN OR EQUAL <=

Example:

```javascript
console.log(20 <= 20);
```

Output:

```text
true
```


Example:

```javascript
console.log(15 <= 20);
```

Output:

```text
true
```


---

# 26. EQUAL TO ==

`==` checks whether two values are equal after JavaScript may perform type conversion.

Example:

```javascript
console.log(10 == 10);
```

Output:

```text
true
```


Example:

```javascript
console.log(10 == 20);
```

Output:

```text
false
```


Important example:

```javascript
console.log(10 == "10");
```

Output:

```text
true
```


Why?

Because `==` allows type conversion.


For modern JavaScript programming, we generally prefer:

```text
===
```


---

# 27. STRICT EQUAL ===

`===` checks:

1. Value
2. Data type


Example:

```javascript
console.log(10 === 10);
```

Output:

```text
true
```


Example:

```javascript
console.log(10 === "10");
```

Output:

```text
false
```


Why?

First value:

```text
10
Number
```

Second value:

```text
"10"
String
```


Value looks similar, but data types are different.


Therefore:

```text
10 === "10"

false
```


IMPORTANT:

For beginners:

Prefer `===` instead of `==` when comparing values in normal JavaScript code.


---

# 28. NOT EQUAL !=

`!=` means:

NOT EQUAL


Example:

```javascript
console.log(10 != 20);
```

Output:

```text
true
```


Because 10 and 20 are different.


Example:

```javascript
console.log(10 != 10);
```

Output:

```text
false
```


---

# 29. STRICT NOT EQUAL !==

`!==` checks whether the value or data type is different.

Example:

```javascript
console.log(10 !== 20);
```

Output:

```text
true
```


Example:

```javascript
console.log(10 !== "10");
```

Output:

```text
true
```


Because:

10 -> Number

"10" -> String


They have different types.


---

# 30. COMPARISON SUMMARY

```text
>       Greater than
<       Less than
>=      Greater than or equal
<=      Less than or equal
==      Equal after type conversion
===     Strict equal
!=      Not equal after type conversion
!==     Strict not equal
```


---

# 31. REAL WORLD COMPARISON

Suppose:

```javascript
let age = 20;
```


Can the student vote if minimum age is 18?

```javascript
console.log(age >= 18);
```

Output:

```text
true
```


Another:

```javascript
let marks = 35;

console.log(marks >= 40);
```

Output:

```text
false
```


This can later be used with `if`.


---

# 32. LOGICAL OPERATORS

Logical operators are used to combine conditions.

Main logical operators:

```text
&&      AND
||      OR
!       NOT
```


---

# 33. AND &&

`&&` means:

AND


Both conditions must be true.

Example:

```javascript
console.log(true && true);
```

Output:

```text
true
```


Example:

```javascript
console.log(true && false);
```

Output:

```text
false
```


Example:

```javascript
console.log(false && true);
```

Output:

```text
false
```


Example:

```javascript
console.log(false && false);
```

Output:

```text
false
```


Simple rule:

```text
TRUE && TRUE = TRUE

Anything else = FALSE
```


---

# 34. REAL WORLD AND EXAMPLE

Suppose a student can enter an exam only if:

Attendance >= 75

AND

Fees are paid.


JavaScript:

```javascript
let attendance = 80;
let feesPaid = true;

console.log(attendance >= 75 && feesPaid === true);
```

Output:

```text
true
```


Why?

Attendance condition:

```text
80 >= 75
true
```

Fees condition:

```text
true === true
true
```

Both are true.

Therefore:

```text
true && true = true
```


---

# 35. OR ||

`||` means:

OR


Only one condition needs to be true.


Example:

```javascript
console.log(true || false);
```

Output:

```text
true
```


Example:

```javascript
console.log(false || true);
```

Output:

```text
true
```


Example:

```javascript
console.log(false || false);
```

Output:

```text
false
```


Simple rule:

```text
At least one TRUE = TRUE

Both FALSE = FALSE
```


---

# 36. REAL WORLD OR EXAMPLE

Suppose a website allows login using:

Email

OR

Mobile number


Example:

```javascript
let emailProvided = true;
let mobileProvided = false;

console.log(emailProvided || mobileProvided);
```

Output:

```text
true
```


Because at least one is available.


---

# 37. NOT !

`!` means:

NOT


It reverses a Boolean value.


Example:

```javascript
console.log(!true);
```

Output:

```text
false
```


Example:

```javascript
console.log(!false);
```

Output:

```text
true
```


Simple rule:

```text
!true  -> false
!false -> true
```


REAL WORLD:

```javascript
let isLoggedIn = true;

console.log(!isLoggedIn);
```

Output:

```text
false
```


Because the user is logged in.


---

# 38. LOGICAL OPERATOR SUMMARY

```text
&&      AND
||      OR
!       NOT
```


AND:

```text
true && true = true
```

OR:

```text
true || false = true
```

NOT:

```text
!true = false
```


---

# 39. INCREMENT OPERATOR ++

`++` increases a number by 1.

Example:

```javascript
let count = 10;

count++;

console.log(count);
```

Output:

```text
11
```


This:

```javascript
count++;
```

is similar to:

```javascript
count = count + 1;
```


---

# 40. DECREMENT OPERATOR --

`--` decreases a number by 1.

Example:

```javascript
let count = 10;

count--;

console.log(count);
```

Output:

```text
9
```


Similar to:

```javascript
count = count - 1;
```


---

# 41. REAL WORLD ++ EXAMPLE

Suppose a website counts visitors.

```javascript
let visitors = 100;

visitors++;

console.log(visitors);
```

Output:

```text
101
```


Another visitor:

```javascript
visitors++;
```

Now:

```text
102
```


---

# 42. REAL WORLD -- EXAMPLE

Suppose a product has:

```text
10 items
```

One item is sold.

```javascript
let stock = 10;

stock--;

console.log(stock);
```

Output:

```text
9
```


---

# 43. PREFIX AND POSTFIX

Increment can be written in two ways:

```javascript
++count
```

or:

```javascript
count++
```


Decrement:

```javascript
--count
```

or:

```javascript
count--
```


These are called:

PREFIX

and

POSTFIX


For beginners, first understand:

```javascript
count++;
```

means:

increase count by 1.


---

# 44. IMPORTANT PREFIX/POSTFIX EXAMPLE

Consider:

```javascript
let x = 10;

let y = x++;

console.log(x);
console.log(y);
```

Output:

```text
11
10
```


Why?

`x++` means:

First use the old value.

Then increase it.


Now consider:

```javascript
let x = 10;

let y = ++x;

console.log(x);
console.log(y);
```

Output:

```text
11
11
```


`++x` means:

First increase.

Then use the new value.


For beginners:

```text
x++ -> use first, increase later

++x -> increase first, use later
```


---

# 45. STRING OPERATOR +

The `+` operator can also join strings.

This is called:

CONCATENATION


Example:

```javascript
let firstName = "Rahul";
let lastName = "Patil";

let fullName = firstName + " " + lastName;

console.log(fullName);
```

Output:

```text
Rahul Patil
```


Here `+` is not adding numbers.

It is joining strings.


---

# 46. STRING CONCATENATION

Example:

```javascript
let firstName = "Rahul";
let age = 20;

console.log("My name is " + firstName);
```

Output:

```text
My name is Rahul
```


Another:

```javascript
console.log("I am " + age + " years old");
```

Output:

```text
I am 20 years old
```


---

# 47. IMPORTANT + BEHAVIOR

Numbers:

```javascript
console.log(10 + 20);
```

Output:

```text
30
```


Strings:

```javascript
console.log("10" + "20");
```

Output:

```text
1020
```


Because strings are joined.


Very important:

```javascript
10 + 20
```

= 30


But:

```javascript
"10" + "20"
```

= "1020"


---

# 48. MIXING STRING AND NUMBER

Example:

```javascript
console.log("Age: " + 20);
```

Output:

```text
Age: 20
```


Another:

```javascript
console.log(10 + "20");
```

Output:

```text
1020
```


Because JavaScript converts the number to a string for string concatenation in this case.


This is one reason beginners should understand:

String

vs

Number


---

# 49. TEMPLATE LITERALS

Modern JavaScript provides a very convenient way to combine text and variables.

Use:

```text
`
```

Backtick.

Example:

```javascript
let name = "Rahul";
let age = 20;

console.log(`My name is ${name} and I am ${age} years old.`);
```

Output:

```text
My name is Rahul and I am 20 years old.
```


The syntax is:

```javascript
${variable}
```


Inside backticks.


---

# 50. TERNARY OPERATOR

The ternary operator is a short way to write a simple condition.

Syntax:

```javascript
condition ? valueIfTrue : valueIfFalse
```


Example:

```javascript
let age = 20;

let result = age >= 18 ? "Adult" : "Minor";

console.log(result);
```

Output:

```text
Adult
```


Explanation:

```text
age >= 18
```

is the condition.


If true:

```text
"Adult"
```


If false:

```text
"Minor"
```


---

# 51. TERNARY REAL WORLD EXAMPLE

```javascript
let marks = 75;

let result = marks >= 40 ? "Pass" : "Fail";

console.log(result);
```

Output:

```text
Pass
```


Another:

```javascript
let balance = 500;

let message = balance > 0 ? "Account has balance" : "Account is empty";

console.log(message);
```


Output:

```text
Account has balance
```


---

# 52. NULLISH COALESCING OPERATOR ??

`??` is used when we want a fallback value if the first value is:

```text
null
```

or:

```text
undefined
```


Example:

```javascript
let name = null;

let displayName = name ?? "Guest";

console.log(displayName);
```

Output:

```text
Guest
```


Because `name` is null.


Another:

```javascript
let name;

let displayName = name ?? "Guest";

console.log(displayName);
```

Output:

```text
Guest
```


---

# 53. OPTIONAL CHAINING ?.

Optional chaining is used to safely access properties that may not exist.

Example:

```javascript
let student = {
    name: "Rahul"
};

console.log(student.address?.city);
```

Instead of crashing because `address` does not exist, JavaScript returns:

```text
undefined
```


Basic idea:

```text
?.
```

means:

"Access this property only if the previous value exists."


This is useful with objects and APIs.

We will study it more when learning objects.


---

# 54. TYPE OPERATORS

The most common type operator is:

```javascript
typeof
```


It tells us the data type.


Example:

```javascript
let age = 20;

console.log(typeof age);
```

Output:

```text
number
```


Example:

```javascript
let name = "Rahul";

console.log(typeof name);
```

Output:

```text
string
```


Example:

```javascript
let passed = true;

console.log(typeof passed);
```

Output:

```text
boolean
```


---

# 55. IN OPERATOR

The `in` operator checks whether a property exists in an object.

Example:

```javascript
let student = {
    name: "Rahul",
    age: 20
};

console.log("name" in student);
```

Output:

```text
true
```


Example:

```javascript
console.log("salary" in student);
```

Output:

```text
false
```


We will study this in detail with objects.


---

# 56. BITWISE OPERATORS

JavaScript also has bitwise operators.

Examples:

```text
&       AND
|       OR
^       XOR
~       NOT
<<      Left shift
>>      Right shift
>>>     Unsigned right shift
```


These operators work with numbers at the binary/bit level.

Example:

```javascript
console.log(5 & 1);
```

Output:

```text
1
```


For beginner-level JavaScript, you do not need to focus heavily on these initially.

They become useful in:

- Low-level programming
- Performance-related programming
- Flags
- Binary operations
- Some algorithms


---

# 57. OPERATOR PRECEDENCE

Sometimes an expression contains multiple operators.

Example:

```javascript
let result = 10 + 20 * 2;
```

What happens first?

Multiplication happens first.

```text
20 * 2 = 40
```

Then:

```text
10 + 40 = 50
```


Therefore:

```javascript
console.log(10 + 20 * 2);
```

Output:

```text
50
```


---

# 58. USE PARENTHESES TO MAKE IT CLEAR

Example:

```javascript
let result = (10 + 20) * 2;
```

First:

```text
10 + 20 = 30
```

Then:

```text
30 * 2 = 60
```


Output:

```text
60
```


Compare:

```javascript
10 + 20 * 2
```

Result:

```text
50
```


and:

```javascript
(10 + 20) * 2
```

Result:

```text
60
```


Simple rule:

When in doubt, use parentheses.


---

# 59. COMMON OPERATOR PRECEDENCE

For beginners, remember approximately:

1. Parentheses `()`
2. Exponent `**`
3. Multiplication `*`
4. Division `/`
5. Remainder `%`
6. Addition `+`
7. Subtraction `-`
8. Comparison
9. Logical operators
10. Assignment


Example:

```javascript
let result = 10 + 5 * 2;
```

First:

```text
5 * 2
```

Then:

```text
10 + 10
```

Result:

```text
20
```


---

# 60. COMPLETE EXAMPLE

```javascript
let price = 1000;
let quantity = 3;

let total = price * quantity;

console.log(total);
```

Output:

```text
3000
```


Now apply discount:

```javascript
let discount = 500;

total -= discount;

console.log(total);
```

Output:

```text
2500
```


Check whether total is greater than 2000:

```javascript
console.log(total > 2000);
```

Output:

```text
true
```


Check whether customer is eligible:

```javascript
let member = true;

console.log(total > 2000 && member === true);
```

Output:

```text
true
```


This single example uses:

```text
*
-=
>
&&
===
```


---

# 61. ANOTHER REAL WORLD EXAMPLE - STUDENT

```javascript
let marks = 75;
let attendance = 80;

let passedMarks = marks >= 40;
let goodAttendance = attendance >= 75;

let passed = passedMarks && goodAttendance;

console.log(passed);
```

Output:

```text
true
```


Explanation:

Marks:

```text
75 >= 40
true
```


Attendance:

```text
80 >= 75
true
```


Both must be true:

```text
true && true
```

Therefore:

```text
true
```


---

# 62. ANOTHER REAL WORLD EXAMPLE - BANK

```javascript
let balance = 10000;
let withdrawal = 3000;

balance -= withdrawal;

console.log(balance);
```

Output:

```text
7000
```


Check if enough balance remains:

```javascript
console.log(balance > 0);
```

Output:

```text
true
```


---

# 63. ANOTHER REAL WORLD EXAMPLE - SHOP

```javascript
let price = 500;
let quantity = 4;

let total = price * quantity;

console.log(total);
```

Output:

```text
2000
```


Check whether customer gets a discount:

```javascript
let discountAvailable = total >= 2000;

console.log(discountAvailable);
```

Output:

```text
true
```


---

# 64. QUICK OPERATOR CHEAT SHEET

```text
ARITHMETIC

+       Add
-       Subtract
*       Multiply
/       Divide
%       Remainder
**      Power


ASSIGNMENT

=       Assign
+=      Add and assign
-=      Subtract and assign
*=      Multiply and assign
/=      Divide and assign
%=      Remainder and assign


COMPARISON

==      Equal
===     Strict equal
!=      Not equal
!==     Strict not equal
>       Greater than
<       Less than
>=      Greater than or equal
<=      Less than or equal


LOGICAL

&&      AND
||      OR
!       NOT


INCREMENT / DECREMENT

++      Increase by 1
--      Decrease by 1


STRING

+       Join strings


TERNARY

? :     Short condition


NULLISH

??      Fallback for null/undefined


OPTIONAL CHAINING

?.      Safely access property


TYPE

typeof  Check data type


OBJECT

in      Check whether property exists
```


---

# 65. MOST IMPORTANT OPERATORS FOR BEGINNERS

Do not try to memorize everything at once.

First master these:

```text
+
-
*
/
%

=
+=
-=

>
<
>=
<=
===
!==

&&
||
!

++
--

+
```

Then learn:

```text
?:
??
?.
```

Later:

```text
Bitwise operators
in
instanceof
```

---

# 66. CLASSROOM PRACTICE QUESTIONS

Ask students to predict the output BEFORE running the code.


QUESTION 1:

```javascript
console.log(10 + 20);
```

Answer:

```text
30
```


QUESTION 2:

```javascript
console.log(20 - 5);
```

Answer:

```text
15
```


QUESTION 3:

```javascript
console.log(5 * 4);
```

Answer:

```text
20
```


QUESTION 4:

```javascript
console.log(20 / 5);
```

Answer:

```text
4
```


QUESTION 5:

```javascript
console.log(10 % 3);
```

Answer:

```text
1
```


QUESTION 6:

```javascript
console.log(10 > 5);
```

Answer:

```text
true
```


QUESTION 7:

```javascript
console.log(10 < 5);
```

Answer:

```text
false
```


QUESTION 8:

```javascript
console.log(10 === 10);
```

Answer:

```text
true
```


QUESTION 9:

```javascript
console.log(10 === "10");
```

Answer:

```text
false
```


QUESTION 10:

```javascript
console.log(true && false);
```

Answer:

```text
false
```


QUESTION 11:

```javascript
console.log(true || false);
```

Answer:

```text
true
```


QUESTION 12:

```javascript
console.log(!true);
```

Answer:

```text
false
```


QUESTION 13:

```javascript
let x = 10;

x++;

console.log(x);
```

Answer:

```text
11
```


QUESTION 14:

```javascript
let x = 10;

x += 5;

console.log(x);
```

Answer:

```text
15
```


QUESTION 15:

```javascript
console.log("Hello " + "World");
```

Answer:

```text
Hello World
```


---

# 67. SMALL STUDENT TASK

Create a program for a student.

Store:

```text
Student name
Marks
Attendance
```

Then calculate:

1. Whether marks are greater than or equal to 40
2. Whether attendance is greater than or equal to 75
3. Whether the student passed both conditions
4. Print the result


Example:

```javascript
let studentName = "Rahul";
let marks = 70;
let attendance = 80;

let marksPassed = marks >= 40;
let attendancePassed = attendance >= 75;

let passed = marksPassed && attendancePassed;

console.log(studentName);
console.log(marksPassed);
console.log(attendancePassed);
console.log(passed);
```


Expected output:

```text
Rahul
true
true
true
```


---

# 68. FINAL CONCEPT

Remember this simple idea:

VARIABLE

stores data.

Example:

```javascript
let age = 20;
```


OPERATOR

performs an operation on that data.

Example:

```javascript
age + 5
```


So:

```text
VARIABLE + OPERATOR + VALUE
```

can be used to create useful expressions.

Example:

```javascript
let price = 500;
let quantity = 3;

let total = price * quantity;
```

Here:

```text
price       -> variable
500         -> value
quantity    -> variable
3           -> value
*           -> operator
total       -> variable
```

Result:

```text
1500
```


==================================================
END OF JAVASCRIPT OPERATORS
==================================================