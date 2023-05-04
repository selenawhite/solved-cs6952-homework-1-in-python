Download Link: https://assignmentchef.com/product/solved-cs6952-homework-1-in-python
<br>
<h1>1.     Testing Cases: 10 points</h1>

<strong>File: </strong>testing_cases.py

This program will handle a simple situation of reading the number of cases to be tested and will then iterate through each case, printing the case number as Case #: and echoing back the word input by the user. Your case numbers should start counting from 0. The case number printed out is a header so our autograder knows when to start grading a new case. The echoing of the user input is the code being tested by the grader.

For this problem, you should use input() function to read strings of characters from the standard input, and store them. Remember all the input from ‘input()’ function will be read as strings, you may need to convert input to int.For example, if you want to input number of cases your program will run:

number_of_case = int(input()) For output, use print() function.

<h2>Example Input</h2>

7 Hello!

Goose Dog

Chicken Duck

Hello

Computer Whoops!

<h2>Expected Output</h2>

Case 0:

Echo: Hello!

Case 1: Echo: Goose Dog Case 2: Echo: Chicken Case 3: Echo: Duck Case 4: Echo: Hello Case 5: Echo: Computer Case 6:

Echo: Whoops!

<h1>2.                  Find the Minimum and Maximum of a List of Numbers: 30 points</h1>

<strong>File: </strong>find_min_max.py

Write a program that reads some number of integers from the user and finds the minimum and maximum numbers in this list. The first number denotes number of cases. The input for each case consists of a single line containing list of integers. Your program will read in this list elements and find the minimum and maximum values and print them back out. Do not use any built-in functions to find the maximum and minimum in the list, e.g, max() and min().

<strong>Example Input:</strong>

4

100 -50 14 32 -5 124

-502 123 12 -42

10 -60 9993 -1230 412 510 -142 -23 90 0 13 -45

89 32 -82 16 0 -2 78

<strong>Expected output:</strong>

Case 0:

Min: -50

Max: 124 Case 1:

Min: -502 Max: 123 Case 2:

Min: -1230 Max: 9993 Case 3:

Min: -82

Max: 89

<h1>3.     Flip Flop: 30 points</h1>

<strong>File: </strong>flip_flop.py

We want to model the behavior of a strange sort of fish over some time. On seconds divisible by <em>a </em>it flips, on those divisible by <em>b </em>it flops and on those divisible by both it flips and flops. To simulate this behavior your program should print “flip” when it flips, “flop” when it flops and “flipflop” when it flips and flops. If the fish doesn’t do any action then you should just print out the current second.

Input to your program for each case will be the second to start at, the number of seconds to simulate and the values for <em>a </em>and <em>b</em>. Your program should then log the behavior of the fish by printing its action or the current time as specified above for the desired number of seconds. Note that 0 counts as divisible by any number, recall that 0 % x is always 0 for any value of x.

<h2>Example Input</h2>

3

0 16 3 5

10 10 2 7 4 20 12 4

<strong>Expected Output </strong>Case 0: flipflop

1 2 flip 4 flop flip 7 8 flip flop 11 flip 13 14 flipflop Case 1: flip 11 flip 13 flipflop 15 flip 17 flip 19 Case 2: flop 5 6 7 flop 9

10 11 flipflop 13 14 15 flop 17 18 19 flop 21 22 23

<h1>4.     Estimating <em>π </em>using Leibniz’s formula: 30 points</h1>

<strong>File: </strong>leibniz.py

The German mathematican Leibniz (1646 – 1716) discovered the following formula to approximate <em>π</em>:

<em>π/</em>4 = 1 <em>− </em>1<em>/</em>3 + 1<em>/</em>5 <em>− </em>1<em>/</em>7 + 1<em>/</em>9 <em>− </em>1<em>/</em>11 + <em>…</em>

Write a program to compute an approximation of <em>π </em>using the first <em>n </em>terms in Leibniz’s series, where 1 <em>≤ n ≤ </em>10000000 is input. Print your output in fixed-point notation, to up to 8 digits of accuracy. For example, to output the variable num in fixed point notation, to 4 digits of accuracy after the decimal point, do as follows: num = 13.94222222222 print(‘{:.4f}’.format(num))

<h2>Example input</h2>

6 1

100

1000

10000

100000

1000000

<h2>Example output</h2>

Case 0:

Pi estimated as: 4.00000000 Case 1:

Pi estimated as: 3.13159290 Case 2:

Pi estimated as: 3.14059265 Case 3:

Pi estimated as: 3.14149265 Case 4:

Pi estimated as: 3.14158265 Case 5:

Pi estimated as: 3.14159165