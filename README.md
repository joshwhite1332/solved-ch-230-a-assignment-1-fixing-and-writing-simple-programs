Download Link: https://assignmentchef.com/product/solved-ch-230-a-assignment-1-fixing-and-writing-simple-programs
<br>
<h1>Problem 1.1 <em>Compute division                                                                                     </em></h1>

Fix the program below such that it prints the correct result. Why is the result 0<em>.</em>000? Write your answer and explanations within comments.

#include &lt;stdio.h&gt;

int main() { double result; /<sup>∗ </sup>The result of our calculation <sup>∗</sup>/ result = (3 + 1) / 5;

printf(“The value of 4/5 is %lf
”, result); return 0;

}

<h1>Problem 1.2 <em>Wrong output                                                                                          </em></h1>

Fix the program below such that it prints the correct value. Why does the program print “The result is -1073745604”? (Values will vary). Write your answer and explanations within comments.

#include &lt;stdio.h&gt;

int main() { int result; /<sup>∗ </sup>The result of our calculation <sup>∗</sup>/ result = (2 + 7) <sup>∗ </sup>9 / 3;

printf(“The result is %d
”); return 0;

}

<h1>Problem 1.3 <em>A compile error</em>)</h1>

You will get compiler errors, when you try to compile the example code given below.

Read the error messages that the compiler produces and fix the errors such that your source code compiles successfully. Then fix the program to print the correct result. Explain within comments the reason of the errors and describe your fixes. include &lt;stdio.h&gt;

int main() { float result; /<sup>∗ </sup>The result of the division <sup>∗</sup>/ int a = 5; int b = 13.5; result = a / b;

printf(“The result is %d
”, result); return 0; }

<table width="315">

 <tbody>

  <tr>

   <td width="315"><strong>Problem 1.4 </strong><em>Simple arithmetics</em></td>

  </tr>

  <tr>

   <td width="315"> </td>

  </tr>

 </tbody>

</table>

Write a program which does the following:

<ol>

 <li>assigns 17 to x and 4 to y,</li>

 <li>prints the values of x and y,</li>

 <li>computes the sum of x and y and prints the result,</li>

 <li>computes the product of x and y and prints the result,</li>

 <li>computes the difference of x and y (x minus y) and prints the result,</li>

 <li>computes the division of x and y (x divided by y) and prints the result (the result should be a float),</li>

 <li>computes the remainder of the division of x and y in this order and prints the result.</li>

</ol>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<h1>Testcase 1.4: inputTestcase 1.4: output</h1>

x=17 y=4 sum=21 product=68 difference=13 division=4.250000 remainder of division=1

<h2>Problem 1.5 <em>Using printf for multiple data types and conversions                              </em></h2>

Write a program which:

<ol>

 <li>declares and initializes an integer variable x with 2138, and prints the value of x over 9 places,</li>

 <li>declares and initializes a float variable y with −52<em>.</em>358925, and prints the value of y over 11 places and with a floating point precision of 5,</li>

 <li>declares and initializes a char variable z with ’G’, and prints the character on the screen,</li>

 <li>declares and initializes a double variable u with 61<em>.</em>295339687, and prints the value of u with a floating point precision of 7.</li>

</ol>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<h1>Testcase 1.5: inputTestcase 1.5: output</h1>

x=              2138

y= -52.35892 z=G u=61.2953397

<h2>Problem 1.6 <em>Printing a char as character and as decimal value                                  </em></h2>

Write a program which declares and initializes a char variable c with ’F’ and prints on the screen the third character (within the alphabet) after c as a character and as the corresponding ASCII code using only arithmetic operations.