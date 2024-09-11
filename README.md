# Numbers-and-Math

```
INTRODUCTION: THERE ARE TWO MOST IMP DATA TYPES HERE IN THIS CHAPTER
INTEGER AND FLOATING NUMBERS.

>>>type(1)
<class 'int'>

>>>int("25")
25

>>>type(int("25"))
<class 'int'>

>>>float(2)
2.0

WHEN YOU REACH MAXIMUM FLOATING POINT NUMBER, PYTHON RETURNS A SPECIAL FLOAT VALUE CALLED inf . I THINK THIS INDICATES INFINITE.

>>>2e400    (2 * 10^400)
inf

>>>n = 2e400
>>>print(n)
inf
>>>print(type(n))
<class 'float'>

This number is of float data type.

```

```
ADDITION AND SUBTRACTION:

Addition of int to float results in float, similar for subtraction and multiplication. Adiition/Subtraction/multiplication of int and int results in int.
The two numbers on the left and right side of the + or - operator are called Operands.

Operands need not to be of same type always.

>>> 1.0 + 2
3.0   (float)

~DIVISION ALWAYS RETURNS A FLOATING VALUE. IF WE WANT INTEGER VALUE, TYPECASTE INT INTO IT.

>>>9 / 2
4.5

>>>5.0 / 2
2.5

>>>int(9 / 2)
4

~INTEGER DIVISION OPERATOR: // .  IN MY OPINION IT WORKS SAME AS GREATEST INTEGER FUNCTION(GIF)

>>>9 // 2
4
>>>8 //2
4
>>>-3 // 2
-2

~Modullo operator simply gives the remainder of the division.

>>>20 % 7
6
>>>7 % 5
2

To calculate the remainder r of dividing a number x by a number y, Python
uses the equation r = x - (y * (x // y)).


>>>-5 // -3                  
1
>>>-3 * 1
-3
>>>-5 -(-3)
-2


```

```
ARITHMETIC EXPRESSIONS:
An expression is something which contain numbers, operators and parentheses also.
To solve, we can use here BODMAS. BODMAS is applicable in python.
ALSO IN PYTHON, CALCULATION IS DONE FOM LEFT TO RIGHT.

```

```
CHALLENGE QUESTION:

Write a script called exponent.py that receives two numbers from the user and displays the ﬁrst number
raised to the power of the second number.

A sample run of the program should look like this (with example input that has been provided by the user included below):

Enter a base: 1.2
Enter an exponent: 3
1.2 to the power of 3 = 1.7279999999999998

Keep the following in mind:

1. Before you can do anything with the user’s input, you will have to
assign both calls to input() to new variables.
2. The input() function returns a string, so you’ll need to convert the
user’s input into numbers in order to do arithmetic.
3. You can use an f-string to print the result.
4. You can assume that the user will enter actual numbers as input.


>>>x = float(input("Enter a base: "))
>>>y = int(input("Enter an exponent: "))

>>>z = x**y
>>>print(f"{x} to the power of {y} = {z}")
1.2 to the power of 3 = 1.7279999999999998

```

```
INBUILT PYTHON ERROR:

Try to do this in IDLE:

>>>0.1 + 0.2
0.30000000000000004

THIS IS NOT A BUG, IT'S A FLOATING POINT REPRESENTATION ERROR
AND IT HAS NOTHING TO DO WITH PYTHON.

```

```
MATH FUNCTIONS AND NUMBER METHODS:

In this section, we will see three number methods.

round()     USED FOR ROUNDING OFF NUMBERS TO A CERTAIN DIGIT.
abs()       USED TO DETERMINE THE ABSOLUTE VALUE OF A NUMBER (MODULLUS FUNCTION ||)  
pow()       USED TO CALCULATE POWER. WE WILL ALSO SEE DIFF BTWN ** AND pow()

ROUND FUNCTION:

>>>round(2.7)
3

>>>round(2.4)
2

BUT WHAT IS NUMBER ENDS WITH .5, THEN:

Basically if there is (even.5) then rounding off will be (even) and if there is
(odd.5) then rounding off will be (odd + 1).       THAT'S SIMPLE...

IF WE WANT TO ROUND OFF TO A SPECIFIC DIGIT OF OURSELVES THEN E PASS TWO ARUMENTS;

>>>round(3.14159, 3)
3.142

>>>round(2.71828, 2)
2.72

ABSOLUTE FUNCTION:

This is modullus function in mathematics. | number |

If n is positive then the absolute of it is n itself.
If n is negative then the absolute value of it is also n.

~DENOTED BY abs(n)

POWER FUNCTION:

THIS WORKS SAME AS ** FUNCTION.
LET ME TELL YOU THE DIFFERENCE:

pow(x, y, z) = (x ** y) % z    THIS ** CANNOT DO.

















