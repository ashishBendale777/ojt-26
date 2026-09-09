JAVASCRIPT - VARIABLES AND DATA TYPES
=====================================

Audience: BCA Beginners
Topic: Variables and Data Types
Language: JavaScript


--------------------------------------------------
1. WHAT IS DATA?
--------------------------------------------------

Before understanding variables and data types, we should understand DATA.

Data simply means INFORMATION.

Examples:

Student name       -> "Rahul"
Student age        -> 20
Student marks      -> 85
Student passed     -> true
Student phone      -> "9876543210"

All of these are DATA.

In programming, we work with different kinds of data.

For example:

Name      = text
Age       = number
Marks     = number
Passed    = true/false


--------------------------------------------------
2. WHAT IS A VARIABLE?
--------------------------------------------------

Definition:

A variable is a named container used to store data in a program.

In simple language:

VARIABLE = A NAME GIVEN TO A VALUE

Example:

let age = 20;

Here:

age  -> variable name
20   -> value

We can imagine:

age
 |
 v
20


Another example:

let studentName = "Rahul";

Here:

studentName -> variable
"Rahul"     -> value


Another example:

let marks = 85;

marks -> variable
85    -> value


--------------------------------------------------
3. WHY DO WE NEED VARIABLES?
--------------------------------------------------

Suppose we want to use a student's age many times.

Without a variable:

console.log(20);
console.log(20);
console.log(20);

This is not convenient.

Using a variable:

let age = 20;

console.log(age);
console.log(age);
console.log(age);

Now we can use the variable "age" whenever we need the value.


--------------------------------------------------
4. REAL WORLD EXAMPLE OF A VARIABLE
--------------------------------------------------

Imagine a college has a student record.

Student Name: Rahul
Age: 20
Course: BCA
Marks: 85

In JavaScript we can store this information:

let name = "Rahul";
let age = 20;
let course = "BCA";
let marks = 85;

The variables are:

name
age
course
marks

The values are:

"Rahul"
20
"BCA"
85


--------------------------------------------------
5. BASIC VARIABLE SYNTAX
--------------------------------------------------

JavaScript provides three keywords for creating variables:

let
const
var

Basic syntax:

let variableName = value;

Example:

let age = 20;


Another example:

let name = "Rahul";


Another example:

let marks = 90;


General structure:

KEYWORD + VARIABLE NAME + = + VALUE;


Example:

let salary = 50000;

let
|
keyword

salary
|
variable name

=
|
assignment operator

50000
|
value


--------------------------------------------------
6. WHAT DOES "=" MEAN?
--------------------------------------------------

In JavaScript:

= means ASSIGNMENT.

It means:

"Put this value inside this variable."

Example:

let age = 20;

Read it as:

"Create a variable called age and store 20 inside it."

Another example:

let name = "Amit";

Read it as:

"Create a variable called name and store Amit inside it."


IMPORTANT:

Do not read:

age = 20

as:

"age is equal to 20"

For beginners, it is better to understand:

age = 20

means:

"store 20 in age."


--------------------------------------------------
7. LET
--------------------------------------------------

Definition:

let is used to create a variable whose value can be changed later.

Example:

let age = 20;

Later:

age = 21;

Now age contains:

21


Example:

let marks = 50;

marks = 75;

marks = 90;

The value changes from:

50
to 75
to 90


Example:

let city = "Pune";

city = "Mumbai";

Now city contains:

"Mumbai"


--------------------------------------------------
8. IMPORTANT RULE OF LET
--------------------------------------------------

A variable created using let can be changed.

Example:

let age = 20;

age = 25;

This is allowed.


But we normally cannot declare the same let variable again in the same scope.

Example:

let age = 20;

let age = 25;

This causes an error.


But this is allowed:

let age = 20;

age = 25;


Remember:

DECLARE -> create variable

ASSIGN -> put/change value


--------------------------------------------------
9. DECLARATION AND ASSIGNMENT
--------------------------------------------------

We can declare a variable first.

Example:

let age;

At this moment:

age has no useful value.

Then we can assign a value:

age = 20;


So:

let age;

age = 20;


We can also do both at the same time:

let age = 20;


This is called initialization.

Initialization means giving the variable its first value.


--------------------------------------------------
10. CONST
--------------------------------------------------

Definition:

const is used when we do not want to reassign a variable after initialization.

Example:

const pi = 3.14159;

We should not do:

pi = 4;

This causes an error.


Another example:

const collegeName = "ABC College";

Trying:

collegeName = "XYZ College";

causes an error.


--------------------------------------------------
11. WHEN SHOULD WE USE CONST?
--------------------------------------------------

Use const when the variable should not be reassigned.

Examples:

const pi = 3.14159;

const country = "India";

const collegeName = "ABC College";

const companyName = "Technoweit";


Use let when the value needs to change.

Example:

let age = 20;

age = 21;


Simple rule:

VALUE WILL CHANGE?
        |
       YES
        |
       let

VALUE WILL NOT BE REASSIGNED?
        |
       YES
        |
      const


--------------------------------------------------
12. LET VS CONST
--------------------------------------------------

let:

let age = 20;

age = 21;

Allowed.


const:

const age = 20;

age = 21;

Not allowed.


Example:

let score = 50;

score = 80;


Example:

const maxMarks = 100;

maxMarks = 200;

Not allowed.


--------------------------------------------------
13. VAR
--------------------------------------------------

var is the older way of creating variables in JavaScript.

Example:

var age = 20;


We can change it:

age = 21;


For modern JavaScript, generally prefer:

let
const

instead of:

var


Students should know var because they will see it in old JavaScript code and interviews.

For now remember:

var = old variable declaration keyword

let = modern variable declaration, value can change

const = modern variable declaration, variable cannot be reassigned


--------------------------------------------------
14. VARIABLE NAMING RULES
--------------------------------------------------

JavaScript variables have naming rules.


RULE 1:

A variable name can contain letters.

Example:

let name = "Rahul";


RULE 2:

A variable name can contain numbers.

Example:

let student1 = "Rahul";


But the variable name cannot START with a number.

Wrong:

let 1student = "Rahul";


Correct:

let student1 = "Rahul";


RULE 3:

Underscore is allowed.

Example:

let student_name = "Rahul";


RULE 4:

Dollar sign is allowed.

Example:

let $price = 500;


RULE 5:

Spaces are not allowed.

Wrong:

let student name = "Rahul";


Correct:

let studentName = "Rahul";


RULE 6:

JavaScript variable names are case-sensitive.

Example:

let age = 20;

let Age = 30;

These are two different variables.


Example:

let name = "Rahul";

let Name = "Amit";

These are different variables.


--------------------------------------------------
15. VARIABLE NAMING CONVENTION
--------------------------------------------------

JavaScript programmers commonly use camelCase.

Example:

let studentName = "Rahul";

let studentAge = 20;

let totalMarks = 450;

let mobileNumber = "9876543210";


Instead of:

studentname

student_name

student-name


camelCase is commonly preferred:

studentName

studentAge

totalMarks

mobileNumber


--------------------------------------------------
16. WHAT IS A DATA TYPE?
--------------------------------------------------

Definition:

A data type tells us what kind of data a value contains.

In simple language:

DATA TYPE = TYPE OF DATA


For example:

"Rahul"
|
Text
|
String


20
|
Number
|
Number


true
|
True/False
|
Boolean


So JavaScript needs to know what kind of value we are working with.


--------------------------------------------------
17. JAVASCRIPT DATA TYPES
--------------------------------------------------

JavaScript has several data types.

The major data types beginners should learn are:

1. String
2. Number
3. Boolean
4. Undefined
5. Null
6. BigInt
7. Symbol
8. Object

We can broadly divide them into:

PRIMITIVE DATA TYPES

and

NON-PRIMITIVE DATA TYPES


--------------------------------------------------
18. PRIMITIVE DATA TYPES
--------------------------------------------------

Primitive data types represent single/simple values.

Main primitive types:

String
Number
Boolean
Undefined
Null
BigInt
Symbol


For beginners, focus especially on:

String
Number
Boolean
Undefined
Null


--------------------------------------------------
19. STRING
--------------------------------------------------

Definition:

A String is a sequence of characters/text.

Examples:

"Rahul"

"Hello"

"India"

"BCA"

"JavaScript"


String can be written using:

Double quotes:

let name = "Rahul";


Single quotes:

let name = 'Rahul';


Backticks:

let name = `Rahul`;


All three can represent strings.


--------------------------------------------------
20. STRING EXAMPLES
--------------------------------------------------

let name = "Rahul";

let city = "Pune";

let country = "India";

let course = "BCA";

let message = "Welcome to JavaScript";


A string can contain numbers as text:

let mobile = "9876543210";


Notice:

let age = 20;

20 is a NUMBER.


But:

let age = "20";

"20" is a STRING.


This is a very important difference.


--------------------------------------------------
21. NUMBER
--------------------------------------------------

Definition:

Number is used for numeric values.

Examples:

let age = 20;

let marks = 85;

let price = 499;

let salary = 50000;

let temperature = 35;

let distance = 25.5;


JavaScript Number can contain:

Positive numbers:

100

Negative numbers:

-100

Decimal numbers:

10.5

Zero:

0


--------------------------------------------------
22. NUMBER EXAMPLES
--------------------------------------------------

let age = 21;

let marks = 85;

let price = 999.50;

let temperature = -5;

let balance = 0;


All are Number values.


--------------------------------------------------
23. STRING NUMBER VS NUMBER
--------------------------------------------------

This is very important.

Example:

let a = 10;

let b = "10";


a contains:

Number 10


b contains:

String "10"


They look similar, but their data types are different.


Example:

let age = 20;

let ageText = "20";


age -> Number

ageText -> String


--------------------------------------------------
24. BOOLEAN
--------------------------------------------------

Definition:

Boolean represents only two values:

true
false


Example:

let isStudent = true;

let isPassed = true;

let isMarried = false;

let isLoggedIn = false;


Boolean is commonly used for yes/no situations.


Example:

Is student present?

true


Is student absent?

false


Example:

let isAvailable = true;


Example:

let isAdmin = false;


Example:

let paymentCompleted = true;


--------------------------------------------------
25. BOOLEAN REAL WORLD EXAMPLE
--------------------------------------------------

Suppose a website wants to know whether a user is logged in.

let isLoggedIn = true;


If user logs out:

isLoggedIn = false;


Another example:

let hasDrivingLicense = true;


Another:

let isOnline = false;


Another:

let examPassed = true;


Remember:

true and false are Boolean values.

Do NOT write:

"true"

"false"

because those are Strings.


Correct:

let result = true;


String:

let result = "true";


These are different.


--------------------------------------------------
26. UNDEFINED
--------------------------------------------------

Definition:

undefined means a variable has been declared but has not been given a value.

Example:

let age;

Here age is:

undefined


Example:

let name;

console.log(name);


Output:

undefined


Another example:

let marks;

console.log(marks);


Output:

undefined


Think:

VARIABLE EXISTS

but

VALUE HAS NOT BEEN PROVIDED.


--------------------------------------------------
27. NULL
--------------------------------------------------

Definition:

null means we intentionally say that a variable has no value.

Example:

let selectedStudent = null;


This means:

"There is currently no selected student."


Another example:

let user = null;


Meaning:

"There is currently no user."


Another example:

let result = null;


Meaning:

"We currently have no result."


IMPORTANT DIFFERENCE:

undefined usually means:

"value has not been assigned"


null usually means:

"we intentionally set the value to nothing."


Example:

let age;

age is undefined.


Example:

let age = null;

age is null.


--------------------------------------------------
28. UNDEFINED VS NULL
--------------------------------------------------

undefined:

let student;

No value has been assigned.


null:

let student = null;

We intentionally assigned "no value."


Simple way to remember:

undefined
=
"I don't have a value yet."


null
=
"I intentionally have no value."


--------------------------------------------------
29. BIGINT
--------------------------------------------------

BigInt is used for very large integer numbers.

Example:

let population = 123456789012345678901234567890n;


Notice the:

n

at the end.

Example:

let bigNumber = 999999999999999999999999999999n;


For beginners:

BigInt = very large integer values.


Normal numbers:

let age = 20;


Very large integer:

let bigNumber = 12345678901234567890n;


--------------------------------------------------
30. SYMBOL
--------------------------------------------------

Symbol is a special primitive data type used mainly for creating unique identifiers.

Example:

let id = Symbol("id");


Another:

let studentId = Symbol("student");


Every Symbol is unique.

Example:

let a = Symbol("id");

let b = Symbol("id");


Even though both use "id":

a and b are different Symbols.


For beginner students:

Symbol is mainly used when we need a unique value/identifier.

It is less commonly used in basic JavaScript programs.


--------------------------------------------------
31. OBJECT
--------------------------------------------------

Definition:

An object is used to store multiple related values together.

Example:

let student = {
    name: "Rahul",
    age: 20,
    course: "BCA"
};


Here student is an object.

It contains:

name
age
course


This is very useful in real applications.


Another example:

let car = {
    brand: "Toyota",
    model: "Fortuner",
    price: 4000000
};


Another:

let employee = {
    name: "Amit",
    age: 25,
    salary: 30000
};


--------------------------------------------------
32. ARRAY
--------------------------------------------------

Array is also an object type in JavaScript.

An array is used to store multiple values.

Example:

let marks = [80, 75, 90, 85];


Another:

let fruits = ["Apple", "Mango", "Banana"];


Another:

let students = ["Rahul", "Amit", "Priya"];


Think:

Object:

one student with many properties.


Array:

many values stored together.


--------------------------------------------------
33. FUNCTION
--------------------------------------------------

Functions are also treated as objects in JavaScript.

Example:

function greet() {
    console.log("Hello");
}


A function contains reusable instructions.

We will study functions separately.


--------------------------------------------------
34. HOW TO CHECK DATA TYPE?
--------------------------------------------------

JavaScript provides:

typeof


Syntax:

typeof variable


Example:

let age = 20;

console.log(typeof age);


Output:

number


Example:

let name = "Rahul";

console.log(typeof name);


Output:

string


Example:

let result = true;

console.log(typeof result);


Output:

boolean


--------------------------------------------------
35. TYPEOF EXAMPLES
--------------------------------------------------

let name = "Rahul";

console.log(typeof name);

Output:

string


let age = 20;

console.log(typeof age);

Output:

number


let isStudent = true;

console.log(typeof isStudent);

Output:

boolean


let marks;

console.log(typeof marks);

Output:

undefined


let data = null;

console.log(typeof data);

Output:

object


IMPORTANT:

typeof null gives:

object

This is a historical JavaScript behavior.

For beginners, simply remember this special case.


--------------------------------------------------
36. COMPLETE SIMPLE EXAMPLE
--------------------------------------------------

let studentName = "Rahul";
let age = 20;
let marks = 85;
let isPassed = true;
let address = null;
let phone;

console.log(studentName);
console.log(age);
console.log(marks);
console.log(isPassed);
console.log(address);
console.log(phone);


Data types:

studentName -> string
age          -> number
marks        -> number
isPassed     -> boolean
address      -> object (typeof behavior for null)
phone        -> undefined


--------------------------------------------------
37. CHANGING VARIABLE VALUES
--------------------------------------------------

Using let:

let marks = 50;

console.log(marks);

marks = 75;

console.log(marks);

marks = 90;

console.log(marks);


Output:

50
75
90


The same variable can hold different values at different times.


--------------------------------------------------
38. VARIABLE CAN CHANGE DATA TYPE
--------------------------------------------------

JavaScript is dynamically typed.

This means a variable can hold different types of values during execution.

Example:

let value = 10;

Initially:

value -> number


Then:

value = "Hello";


Now:

value -> string


Then:

value = true;


Now:

value -> boolean


Example:

let data = 100;

data = "Rahul";

data = true;

data = null;


This is allowed with let.


--------------------------------------------------
39. WHAT IS DYNAMIC TYPING?
--------------------------------------------------

Definition:

JavaScript is dynamically typed because we do not have to specify the data type of a variable when declaring it, and the variable can hold values of different types during execution.

Example:

let data = 100;

data = "Hello";

data = false;


We did not write:

number data

or:

string data


JavaScript automatically determines the type from the value.


--------------------------------------------------
40. JAVASCRIPT VS SOME OTHER LANGUAGES
--------------------------------------------------

In languages such as C++ or Java:

int age = 20;

Here we explicitly specify:

int


JavaScript:

let age = 20;


We don't write:

int

JavaScript determines that:

20 -> number


Another example:

Java:

String name = "Rahul";


JavaScript:

let name = "Rahul";


JavaScript automatically understands that:

"Rahul" -> string


--------------------------------------------------
41. CONST WITH OBJECT
--------------------------------------------------

This is an important concept.

Example:

const student = {
    name: "Rahul",
    age: 20
};


We cannot do:

student = {};

because const does not allow reassignment.


But we can change an object's property:

student.age = 21;


This is allowed.


Why?

Because the variable still points to the same object.

We are changing the object's content, not reassigning the variable.


For beginners, remember:

const prevents REASSIGNMENT of the variable.

It does not automatically make an object completely immutable.


--------------------------------------------------
42. CONST WITH ARRAY
--------------------------------------------------

Example:

const fruits = ["Apple", "Mango"];


This is not allowed:

fruits = ["Banana"];


But this is allowed:

fruits.push("Banana");


Because we are changing the contents of the same array.


Again:

const
does not mean:

"nothing inside can ever change."


It means:

"the variable cannot be reassigned."


--------------------------------------------------
43. COMMON BEGINNER MISTAKES
--------------------------------------------------

Mistake 1:

let 1name = "Rahul";


Wrong because variable names cannot start with numbers.


Mistake 2:

let student name = "Rahul";


Wrong because spaces are not allowed.


Mistake 3:

let age = "20";


This is a String, not a Number.


Mistake 4:

let result = "true";


This is a String, not Boolean.


Correct:

let result = true;


Mistake 5:

const age = 20;

age = 21;


Not allowed because const cannot be reassigned.


Mistake 6:

let age;

console.log(age);


Output:

undefined


This is not an error.

The variable exists but has no assigned value.


--------------------------------------------------
44. PRACTICE EXAMPLE 1
--------------------------------------------------

Create variables for:

Student name
Student age
Student course
Student marks
Student passed or not


Answer:

let studentName = "Rahul";
let studentAge = 20;
let course = "BCA";
let marks = 85;
let passed = true;


Identify the data types:

studentName -> string
studentAge  -> number
course      -> string
marks       -> number
passed      -> boolean


--------------------------------------------------
45. PRACTICE EXAMPLE 2
--------------------------------------------------

Create variables for a bank account.

Account holder:
Amit

Balance:
50000

Account active:
true


Answer:

let accountHolder = "Amit";
let balance = 50000;
let accountActive = true;


Data types:

accountHolder -> string
balance       -> number
accountActive -> boolean


--------------------------------------------------
46. PRACTICE EXAMPLE 3
--------------------------------------------------

Create variables for an employee.

Name:
Priya

Age:
25

Salary:
45000

Manager:
false


Answer:

let employeeName = "Priya";
let employeeAge = 25;
let salary = 45000;
let isManager = false;


--------------------------------------------------
47. PRACTICE EXAMPLE 4
--------------------------------------------------

Create variables for an online shopping product.

Product name:
Laptop

Price:
55000

Available:
true

Discount:
10


Answer:

let productName = "Laptop";
let price = 55000;
let available = true;
let discount = 10;


--------------------------------------------------
48. PRACTICE EXAMPLE 5
--------------------------------------------------

Create variables for a college.

College name:
ABC College

Students:
1200

Government college:
false


Answer:

let collegeName = "ABC College";
let totalStudents = 1200;
let governmentCollege = false;


--------------------------------------------------
49. QUICK DATA TYPE IDENTIFICATION
--------------------------------------------------

Ask students to identify the data type.

1.

let a = 100;


Answer:

number


2.

let a = "100";


Answer:

string


3.

let a = true;


Answer:

boolean


4.

let a = false;


Answer:

boolean


5.

let a;


Answer:

undefined


6.

let a = null;


Answer:

null


7.

let a = [10, 20, 30];


Answer:

object


8.

let a = {name: "Rahul"};


Answer:

object


9.

let a = 100000000000000000000n;


Answer:

bigint


--------------------------------------------------
50. IMPORTANT DIFFERENCE
--------------------------------------------------

These are NOT the same:

20
"20"

20 -> Number

"20" -> String


These are NOT the same:

true
"true"

true -> Boolean

"true" -> String


These are NOT the same:

null
undefined

null -> intentionally empty

undefined -> value not assigned


--------------------------------------------------
51. SIMPLE MEMORY TRICK
--------------------------------------------------

STRING

Text

Example:

"Rahul"


NUMBER

Numbers

Example:

25


BOOLEAN

True/False

Example:

true


UNDEFINED

No value assigned yet

Example:

let age;


NULL

Intentionally no value

Example:

let age = null;


BIGINT

Very large integer

Example:

12345678901234567890n


SYMBOL

Unique identifier

Example:

Symbol("id")


OBJECT

Collection of related data

Example:

{
    name: "Rahul",
    age: 20
}


--------------------------------------------------
52. VERY IMPORTANT INTERVIEW QUESTIONS
--------------------------------------------------

Question 1:

What is a variable?

Answer:

A variable is a named container used to store data.


Question 2:

What are the ways to declare variables in JavaScript?

Answer:

var
let
const


Question 3:

Difference between let and const?

Answer:

let allows reassignment.

const does not allow reassignment.


Question 4:

What is a data type?

Answer:

A data type tells us what kind of value a variable contains.


Question 5:

What is a String?

Answer:

A String is text or a sequence of characters.


Question 6:

What is a Boolean?

Answer:

Boolean contains either true or false.


Question 7:

What is undefined?

Answer:

undefined usually means a variable has been declared but has not been assigned a value.


Question 8:

What is null?

Answer:

null represents an intentionally empty or missing value.


Question 9:

How do you check the data type?

Answer:

Using typeof.


Example:

typeof age


--------------------------------------------------
53. ONE FINAL EXAMPLE
--------------------------------------------------

let studentName = "Rahul";
let age = 20;
let course = "BCA";
let marks = 85;
let isPassed = true;
let scholarship = null;
let mobileNumber;
const college = "ABC College";


Now ask students:

What is the variable?

studentName

What is its value?

"Rahul"

What is its data type?

string


What is the variable?

age

Value:

20

Data type:

number


What is the variable?

isPassed

Value:

true

Data type:

boolean


What is the variable?

scholarship

Value:

null

Data type:

null


What is the variable?

mobileNumber

Value:

undefined

Data type:

undefined


What is the variable?

college

Value:

"ABC College"

Data type:

string


--------------------------------------------------
54. CLASSROOM ACTIVITY
--------------------------------------------------

Give students these values:

"Hello"
100
25.5
true
false
null
undefined
"100"
[10, 20, 30]
{name: "Rahul"}

Ask them to identify:

1. Which are Strings?
2. Which are Numbers?
3. Which are Booleans?
4. Which is null?
5. Which is undefined?
6. Which are Objects?
7. What is the difference between 100 and "100"?


--------------------------------------------------
55. SMALL HOMEWORK
--------------------------------------------------

Create variables for the following:

1. Student information
2. Bank account
3. Employee
4. Mobile phone
5. Product
6. College
7. Movie
8. Hospital patient
9. Restaurant order
10. Online shopping cart


For every variable write:

Variable name
Value
Data type


Example:

let movieName = "3 Idiots";

Variable name:
movieName

Value:
"3 Idiots"

Data type:
string


--------------------------------------------------
56. FINAL SUMMARY
--------------------------------------------------

VARIABLE:

A named container for storing data.


let:

Used when the variable value can change.


const:

Used when the variable should not be reassigned.


var:

Older way of declaring variables.


DATA TYPE:

Defines what kind of data a value represents.


MAIN DATA TYPES:

String
Number
Boolean
Undefined
Null
BigInt
Symbol
Object


STRING:

Text

"Hello"


NUMBER:

Numeric value

100


BOOLEAN:

true / false


UNDEFINED:

Variable exists but no value has been assigned.


NULL:

Intentionally empty value.


BIGINT:

Very large integer.


SYMBOL:

Unique identifier.


OBJECT:

Collection of related data.


typeof:

Used to check the type of a value.


Example:

let age = 20;

console.log(typeof age);

Output:

number


==================================================
END OF TOPIC
==================================================