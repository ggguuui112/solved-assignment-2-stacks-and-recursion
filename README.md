Download Link: https://assignmentchef.com/product/solved-assignment-2-stacks-and-recursion
<br>
<em>Write pseudo-code, not Java, for problems requiring code. You are responsible for the appropriate level of detail. Questions 1-11 deal with stacks Questions 12 and 13 give you some simple practice with recursion</em>

<ol>

 <li>a) Use the operations push, pop, peek and empty to construct an operation which sets<em> i</em> to the bottom element of the stack, leaving the stack unchanged. (hint: use an auxiliary stack.)</li>

 <li>b) Use the operations push, pop, peek and empty to construct an operation which sets<em> i</em> to</li>

</ol>

the third element from the bottom of the stack. The stack may be left changed.

<ol start="2">

 <li>Simulate the action of the algorithm for checking delimiters for each of these strings by using a stack and showing the contents of the stack at each point. Do not write an algorithm.

  <ol>

   <li>{[A+B]-[(C-D)]</li>

   <li>((H) * {([J+K])})</li>

  </ol></li>

 <li>Write an algorithm to determine whether an input character string is of the form</li>

</ol>

<h1>x  C y</h1>

where <em>x</em> is a string consisting only of the letters ‘<em>A</em>’ and ‘<em>B</em>’ and <em>y</em> is the reverse of the <em>x</em> (i.e. if <em>x=”ABABBA”</em> then <em>y</em> must equal <em>“ABBABA”</em>).  At each point you may read only the next character in the string, i.e. you must process the string on a left to right basis. You may not use string functions.

<ol start="4">

 <li>Write an algorithm to determine whether an input character string is of the form</li>

</ol>

<h1>a  D b D c D … D z</h1>

Where each string <em>a, b, …z</em> is of the form of the string defined in problem 4.  (Thus a string is in the proper form if it consists of any number of such strings from problem 4, separated by the character ‘<em>D</em>’, e.g. <em>ABBCBBADACADBABCBABDAABACABAA</em>.)  At each point you may read

only the next character in the string, i.e. you must process the string on a left to right basis. You may not use string functions..

<ol start="5">

 <li>Design and implement a stack in which each item on the stack is a varying number of integers. Choose a Java data structure to implement your stack and design push and pop methods for it. You may not use library functions.</li>

</ol>




<ol start="6">

 <li>Consider a language that does not have arrays but does have stacks defined as a data type. That is, one can declare</li>

</ol>

stack s;

The push, pop, empty, and peek operations are defined. Show how a one-dimensional array can be implemented by using these operations on two stacks. In particular, show how you can insert and delete into such an array.

<ol start="7">

 <li>Design a method for keeping two stacks within a single linear array s[SPACESIZE] so that neither stack overflows until all of memory is used and an entire stack is never shifted to a different location within the array. Write methods <em>push1, push2, pop1, and pop2 </em>to manipulate the two stacks.  (Hint:  the two stacks grow toward each other.)</li>

 <li>Transform each of the following expressions to prefix and postfix expressions.

  <ol>

   <li>(A+B)*(C$(D-E)+F)-G</li>

   <li>A+(((B-C)*(D-E)+F)/G)$(H-J)</li>

  </ol></li>

 <li>Transform each of the following expressions to infix expressions.

  <ol>

   <li>++A-*$BCD/+EF*GHI</li>

   <li>+-$ABC*D**EFG</li>

   <li>AB-C+DEF-+$</li>

   <li>ABCDE-+$*EF*-</li>

  </ol></li>

 <li>Apply the evaluation algorithm in the text to evaluate the following postfix expressions, where A=1, B=2, and C=3.

  <ol>

   <li>AB+C-BA+C$-</li>

   <li>ABC+*CBA-+*</li>

  </ol></li>

 <li>Write a prefix method to accept an infix string and create the prefix form of that string, assuming that the string is read from right to left and that the prefix string is created from right to left.</li>

 <li>If an array contains n elements, what is the maximum number of recursive calls made by the binary search algorithm?</li>

 <li>The expression m % n yields the remainder of m upon (integer) division by n. Define the greatest common divisor (GCD) of two integers x and y by:</li>

</ol>

gcd(x, y) = y   if ( y  x and x%y == 0)    gcd(x, y) = gcd(y, x)                                       if (x &lt; y )

gcd(x, y) = gcd(y, x%y)                  otherwise

Write a recursive method to compute gcd(x,y).