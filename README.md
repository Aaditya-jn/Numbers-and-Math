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

>>>-5 % -3
-2

```

```
ARITHMETIC EXPRESSIONS:







