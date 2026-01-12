# 4.1 Answer each of the following questions.
a) All programs can be written in terms of three types of control structures: **sequence**, **selection** and **repetition**.
b) The **if...else** selection statement is used to execute one action when a condition is true or a different action when that condition is false.
c) Repeating a set of instructions a specific number of times is called **counter-controlled** repetition.
d) When it isn't known in advance how many times a set of statements will be repeated, a(n) **sentinel value** can be used to terminate the repetition.

# 4.2 Write four different C++ statements that each add 1 to integer variable x.
x++;
++x;
x += 1;
x = x + 1;

# 4.3 Write C++ statements to accomplish each of the following:

**a) In one statement, assign the sum of the current value of x and y to z and post increment the value of x.**
z = x++ + y;

**b) Determine whether the value of the variable count is greater than 10. If it is, print
"Count is greater than 10."**
if (count > 10) 
    cout << "Count is greater than 10.";

**c) Predecrement the variable x by 1, then subtract it from the variable total.**
total = total - --x;

**d) Calculate the remainder after q is divided by divisor and assign the result to q. Write this statement in two different ways.**
1)q = q % divisor;
2)q %= divisor;

# 4.4 Write C++ statements to accomplish each of the following tasks. 
**a) Declare variable sum to be of type unsigned int and initialize it to 0.**
unsigned int sum = 0;
**b) Declare variable x to be of type unsigned int and initialize it to 1.**
unsigned int x = 1;
**c) Add variable x to variable sum and assign the result to variable sum.** 
sum = sum + x;
**d) Print "The sum is: " followed by the value of variable sum.**
cout << "The sum is: " << sum;

# 4.5 Combine the statements that you wrote in Exercise 4.4 into a program that calculates and prints the sum of the integers from 1 to 10. Use the while statement to loop through the calculation and increment statements. The loop should terminate when the value of x becomes 11.

#include <iostream>
using namespace std;

int main() {
    // (a) Declare variable sum and initialize it to 0
    unsigned int sum = 0;

    // (b) Declare variable x and initialize it to 1
    unsigned int x = 1;

    // Use while statement to loop through calculation
    while (x <= 10) {
        // (c) Add variable x to variable sum
        sum += x;
        
        // Increment statement
        x++;
    }

    // (d) Print the final sum
    cout << "The sum is: " << sum;

    return 0;
}

# 4.6 State the values of each of these unsigned int variables after the calculation is performed. Assume that, when each statement begins executing, all variables have the integer value 5. 
**a) product *= x++;** 
product *= x++;
x++ is post-increment, so x is used first, then increased
**Calculation:**
product = product * x = 5 * 5 = 25
After the statement, x becomes 6
**Final values:**
product = 25
x = 6

**b) quotient /= ++x;**
quotient /= ++x;
++x is pre-increment, so x is increased first
x becomes 6
**Calculation:**
quotient = quotient / x = 5 / 6 = 0 (integer division)
**Final values:**
quotient = 0
x = 6

# 4.7 Write single C++ statements or portions of statements that do the following: 
**a) Input unsigned int variable x with cin and »>.** 
cin >> x;
**b) Input unsigned int variable y with cin and >>.**
cin >> y;
**c) Declare unsigned int variable i and initialize it to 1.**
unsigned int i = 1;
**d) Declare unsigned int variable power and initialize it to 1.**
unsigned int power = 1;
**e) Multiply variable power by x and assign the result to power.**
power *= x;
**f) Preincrement variable i by 1.**
++i;
**g) Determine whether i is less than or equal to y.**
i <= y;
**h) Output integer variable power with cout and <<.**
cout << power;

# 4.8 Write a C++ program that uses the statements in last Exercise to calculate x raised to the y power. The program should have a while repetition statement.
#include <iostream>
using namespace std;

int main() {
    unsigned int x, y;
    unsigned int i = 1;
    unsigned int power = 1;

    cin >> x;
    cin >> y;

    while (i <= y) {
        power *= x;
        ++i;
    }

    cout << power;

    return 0;
}

# 4.9 Identify and correct the errors in each of the following
**a)** while ( c <= 5 )
{
product *= c;
++C;
**Errors:**
Variable C is capitalized; C++ is case-sensitive, it should be c
Missing closing brace }
**Corrected Code:**
while (c <= 5)
{
    product *= c;
    ++c;
}

**b)** cin << value;
**Error:**
Wrong input operator used (<< instead of >>)
**Corrected code:*
cin >> value;

**c)** if ( gender == 1 )
cout < "Woman" << endl;
else;
cout << "Man" << endl;
**Errors:**
Wrong output operator (< instead of <<)
Extra semicolon after else (terminates the else)
Missing braces (recommended for clarity)
**Corrected code:**
if (gender == 1)
    cout << "Woman" << endl;
else
    cout << "Man" << endl;

# 4.10  What's wrong with the following while repetition statement?
while ( z >- 0 )
sum += z:
**There are two errors:**
Comparison operator is wrong
>- is not valid in C++
It should probably be >= (greater than or equal to)
Statement terminator is wrong
sum += z: ends with a colon, but it should end with a semicolon
**Corrected statement:**
while (z >= 0)
    sum += z;
# 4.11 (Correct the Code Errors) Identify and correct the error(s) in cach of the following:
**a)** if ( age >= 65 ); 
cout << "Age is greater than or equal to 65" << endl; 
else 
cout << "Age is less than 65 << endl";
**Error:**
There is a semicolon after the if condition, and the quotation marks in the else block are misplaced. 
**Corrected Code:**
if ( age >= 65 )
    cout << "Age is greater than or equal to 65" << endl;
else
    cout << "Age is less than 65" << endl;

**b)**  if ( age >= 65 ) 
cout << "Age is greater than or equal to 65" << endl; 
else; 
cout << "Age is less than 65 << endl"; 
**Error:**
There is a semicolon after the else keyword, and the quotation marks are misplaced. 
**Corrected Code:**
if ( age >= 65 )
    cout << "Age is greater than or equal to 65" << endl;
else
    cout << "Age is less than 65" << endl;

**c)** unsigned int x = 1; 
unsigned int total; 
while ( x <= 10 ) 
total += x; 
++x;
**Error:**
The total variable is uninitialized, and the while loop lacks braces { }, causing an infinite loop because only the first line after while is repeated. 
**Corrected Code:**
unsigned int x = 1;
unsigned int total = 0;
while ( x <= 10 ) {
    total += x;
    ++x;
}

**d)**  While ( x <= 100 ) 
total += x; ++x: 
**Error:**
The keyword While is capitalized (C++ is case-sensitive), the loop lacks braces, and there is a colon instead of a semicolon after ++x. 
**Corrected Code:**
while ( x <= 100 ) {
    total += x;
    ++x;
}

**e)** while ( y > 0 ) 
cout << y << endl; 
++y; 
**Error:**
This creates an infinite loop because the loop lacks braces, and y is being incremented (moving further away from 0) instead of decremented. 
**Corrected Code:**
while ( y > 0 ) {
    cout << y << endl;
    --y; 
}

# 4.12 (What Does this Program Do?) What does the following program print?
// What does this program print?

#include <iostream>
using namespace std;
int main()

{

unsigned int y = 0; // declare and initialize y

unsigned int x = I; // declare and initialize x

unsigned int total = 0; // declare and initialize total

while ( x <= 10 ) // loop 10 times

y = x * x; // perform calculation

cout << y << endl; // output result

total += y; // add y to total

++x; // increment counter x

} // end while

cout << "Total is " << total << endl; // display result

} // end main

**1. Issues in the code**

unsigned int x = I; → I is not defined. It should probably be 1 (the number one).
Corrected:

unsigned int x = 1;

The while loop body is missing braces {}. In C++, without braces, only the first statement after while is considered inside the loop. To include all statements (y = x*x;, cout << y;, total += y;, ++x;) we need braces:

while (x <= 10) {
    y = x * x;
    cout << y << endl;
    total += y;
    ++x;
}

**2. What the program does**

Initializes x = 1, y = 0, total = 0

Loops while x <= 10

In each iteration:

Calculates y = x * x (square of x)

Prints y

Adds y to total

Increments x

After the loop, prints total (sum of squares from 1² to 10²)

**3. Output of the program**

Squares of 1 to 10:

1
4
9
16
25
36
49
64
81
100

Sum of these squares (total):
1 + 4 + 9 + 16 + 25 + 36 + 49 + 64 + 81 + 100 = 385

**Final output:**

1
4
9
16
25
36
49
64
81
100
Total is 385
