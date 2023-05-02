Download Link: https://assignmentchef.com/product/solved-comp2396b-assignment-1-postfix-to-infix-convertor
<br>
This assignment tests your basic programming skill in Java and refreshes the programming skills that you should have learnt in the first programming course.




You are asked to write a <strong>postfix to infix convertor</strong>. Although program design will not be evaluated in this assignment, you are encouraged to apply the object-oriented programming technique that you have learnt.

You are also required to write <strong>JavaDoc</strong> for all non-private classes and non-private class members. <strong><u>Programs without JavaDoc will not be marked.</u></strong>

<em> </em>You will be provided a skeleton file, PostfixReader.java, which consists of a simple main() method that <strong>controls the basic program flow</strong>; and a method that<strong> reads a line from input</strong> which is implemented for you. You will need to implement the doConversion() method that <strong>read an Postfix from input</strong> (using the provided readPostfix() method), convert that to <strong>infix</strong> and <strong>print</strong> it out. In addition, <strong>print</strong> the <strong>result</strong> of the input equation to <strong>the next line</strong>.

To support the <strong>postfix to infix conversion</strong>, you are required to implement the class Stack. You are <strong><u>not</u></strong> allowed to use any class provided in the packages in java.util.* or any other Java classes that provide the implementation of a stack from the Internet. Please refer to the Assignment1_Background Slides for the basic operations of a stack.

Your program should read in an arithmetic expression in <strong>postfix</strong> form, and output the same expression in <strong>infix</strong> form. Numbers and operators including parenthesis in the expression are separated by <strong>at least one single space</strong>. For example:

Input postfix: 12 23


Infix: ( 12 + 23 )

Result: 35

Input postfix: 34 56 *

Infix: ( 34 * 56 )

Result: 1904







Your program should support the <strong>five arithmetic operators</strong>, ^, +, -, * and /.  The ^ is the exponential operator and has the highest precedence. The precedence of operators * and / are higher than that of operators + and -. For example:







Input postfix: 1 2 + 3 *

Infix: ( ( 1 + 2 ) * 3 )

Result: 9

Input postfix: 8 64 4 2 ^ / –

Infix: ( 8 – ( 64 / ( 4 ^ 2 ) ) )

Result: 4







Your program should support <strong>negative values</strong>. There is no space between the negative sign and the number in negative values. For example:

Input postfix: 5 -2 2 *


Infix: ( 5 + ( -2 * 2 ) )

Result: 1







Your program should also detect the validity of postfix expressions. For example:

Input postfix: 2 + 3 *

Error: Invalid postfix

Input postfix: 1 3 5 * + 7 / –

Error: Invalid postfix


