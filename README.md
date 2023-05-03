Download Link: https://assignmentchef.com/product/solved-cs135-project-4
<br>
<u>Project [4]: Interactive Programs</u>




<strong>Project Goals </strong>

The goals of this project are to:

<ol>

 <li>Get students familiar with switch statements</li>

 <li>Get students familiar with writing interactive programs</li>

 <li>Get students familiar with character input/output functions</li>

</ol>




<strong><u>Important Notes:</u> </strong>

<ol>

 <li><strong>Formatting: </strong>Make sure that you follow the precise recommendations for the output connate and formatting: for example, do not change the text in the first problem to differ from what is in the assignment. Your assignment will be auto-graded and any changes in formatting will result in a loss in the grade.</li>

 <li><strong>Comments: </strong>Header comments are required on all files and recommended for the rest of the program. Points will be deducted if no header comments are included.</li>

 <li><strong>Restriction: </strong>The use of goto statements anywhere within this program is prohibited. Points will be deducted if gotois used.</li>

</ol>




<strong>Problem 1 </strong>

Write an interactive program that implements a simple calculator. The program should allow the user to choose a

binary arithmetic operation and enter two terms to which to apply the operation. The program should then compute the result and display it to the user. Your calculator will have two modes: double-precision mode and integer mode. Double-precision mode will do calculations and output using variables of type double. Integer mode will do calculations and output using variables of type int. Your program should start in double-precision mode.

At the beginning, the program should output the following:

This program implements a calculator.

At every iteration, your program should ask the user for an option as follows:

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option:




Below is a description of what the program should do for each of the above options (items underlined are to be entered by the user):

<ol>

 <li>Perform addition. For this option, the program should ask the user to enter two terms to be added, as follows:</li>

</ol>




<h1>In double-precision mode:</h1>

Enter first term: <u>1</u>

Enter second term: <u>1</u>

The sum is: 2.000000000000000




In integer mode:

Enter first term: <u>1</u>

Enter second term: <u>1</u>

The sum is: 2




<ol start="2">

 <li>Perform subtraction. For this operation, the program should ask the user to enter two terms to be subtracted, as follows:</li>

</ol>




In double-precision mode:

Enter first term: <u>4</u>

<h1>Enter second term: <u>2</u></h1>

<h1>The difference is: 2.000000000000000</h1>




<h1>In integer mode:</h1>

Enter first term: <u>4</u>

<h1>Enter second term: <u>2</u></h1>

The difference is: 2




<ol start="3">

 <li>Perform multiplication. For this operation, the program should ask the user to enter two terms to be multiplied, as follows:</li>

</ol>




In double-precision mode:

Enter first term: <u>2</u>

Enter second term: <u>3</u>

The product is: 6.000000000000000




In integer mode:

Enter first term: <u>2</u>

Enter second term: <u>3</u>

The product is: 6




<ol start="4">

 <li>Perform division. For this operation, the program should ask the user to enter two terms to be divided, as follows:</li>

</ol>




In double-precision mode:

Enter first term: <u>5</u>

Enter second term: <u>2</u>

The quotient is: 2.500000000000000







In integer mode:

Enter first term: <u>5</u>

Enter second term: <u>2</u>

The quotient is: 2




If the second term entered by the user is 0, the program should print:

Cannot divide by zero!




<ol start="5">

 <li>Toggle the type of calculator. By default, the program should perform its calculations using doubleprecision. However, if the user chooses this option, the program should change the type of calculator: either from double to int or vis versa.</li>

</ol>




When switching from double-precision to integers the program should print the follow message:

Calculator now works with integers.




When switching from integers to double-precision the program should print the following message:

Calculator now works with doubles.




<ol start="6">

 <li>The program should end.</li>

</ol>

Your program should function as follows (items underlined are to be entered by the user):

This program implements a calculator.

Options: 1 – addition 2 – subtraction

<ul>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>1</u>

Enter first term: <u>1.525</u>

Enter second term: <u>3</u>

The sum is: 4.525000000000000

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>2</u> Enter first term: <u>4.873</u>

Enter second term: <u>3.1</u>

The difference is: 1.773000000000000

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>3</u>

Enter first term: <u>4.56</u>

Enter second term: <u>2.13</u> The product is: 9.712799999999998

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>4</u>

Enter first term: <u>5.15</u>

Enter second term: <u>9.8765</u> The quotient is: 0.521439781299043

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>4</u>

Enter first term: <u>7.13</u> Enter second term: <u>0</u> Cannot divide by zero! Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>18</u>

Invalid Option. Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program Please enter your option: <u>5</u> Calculator now works with integers. Options:</li>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>1</u>

Enter first term: <u>7</u>

Enter second term: <u>9</u>

<h1>The sum is: 16</h1>

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>4</u>

<h1>Enter first term: <u>5</u></h1>

Enter second term: <u>2</u>

The quotient is: 2

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>5</u> Calculator now works with doubles.

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option: <u>6</u>




<strong>Notes:  </strong>

<ul>

 <li>If the user enters an invalid command, the program should print the menu again and ask for a valid option, as follows:</li>

</ul>

Invalid Option.

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– toggle calculator type</li>

 <li>– exit program</li>

</ul>

Please enter your option:

<ul>

 <li>For all options, except division, you can assume the user will give valid input</li>

 <li>When the calculator is in double-precision mode it should output 15 digits after the decimal point.</li>

</ul>




Save your program as calc.c




<strong>Challenge for problem 1 </strong>(10 extra credit points):

Turn the calculator into a scientific calculator. Change your calculator as follows:

Options:

<ul>

 <li>– addition</li>

 <li>– subtraction</li>

 <li>– multiplication</li>

 <li>– division</li>

 <li>– exp(x)</li>

 <li>– log(x)</li>

 <li>– toggle calculator type</li>

 <li>– exit program Please enter your option:</li>

</ul>







<ol start="5">

 <li>Compute exp(x). For this option, the program should prompt the user to enter a single number as follows:</li>

</ol>




In double-precision mode:

Enter term: <u>4</u>

The result of exp(4.000000000000000) is: 54.598150033144236




In integer mode:

Cannot calculate with integers.




<ol start="6">

 <li>Compute log(x). For this option, the program should prompt the user to enter a single number as follows:</li>

</ol>




In double-precision mode:

Enter term: <u>4</u>

The result of log(4.000000000000000) is: 1.386294361119891




In integer mode:

Cannot calculate with integers.




This is the natural logarithm, it cannot be used with negative numbers. If the user enters a number that is less than or equal to zero, you program should print: Cannot take the log of that number!




<strong>Note: </strong>

<ul>

 <li>For this program you must use the exp() and log() functions from the math library. To do this:</li>

</ul>

o Add #include &lt;math.h&gt; in your calc_c.c file o Add -lm to the compilation command: gcc -o calc_c calc_c.c -lm




Save your challenge separately as calc_c.c


