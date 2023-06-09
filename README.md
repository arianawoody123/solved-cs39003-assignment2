Download Link: https://assignmentchef.com/product/solved-cs39003-assignment2
<br>
<ol>

 <li>Write a C++ program file consisting of the following functions to create a library. You are not allowed to use any standard library function. Also, do not include the function main() in this file.</li>

</ol>

<ul>

 <li><strong>int printStringUpper (char *) – </strong>print a string of characters terminated by ‘ ’, where all the alphabetic characters are printed in uppercase. The return value is the number of characters printed (excluding the ‘’ character).</li>

 <li><strong>int readHexInteger (int *n) – </strong>read a signed hexadecimal integer in ‘%x’ format, convert it to decimal, and pass the value through the pointer parameter. The return value is GOOD (for success) or BAD (on failure).</li>

 <li><strong>int printHexInteger (int n) – </strong>print the (signed) decimal integer <em>n </em>in left-aligned hexadecimal form. A negative number must be preceded by the minus sign; whereas no prefix is required for non-negative numbers. For example, the number -65529 will be printed as –FFF9. On success, the function will return the number of characters printed, and on failure it will return BAD.</li>

 <li><strong>int readFloat (float *f) – </strong>read a floating point number in ‘%f’ format (for example, –123.456), where the value is passed through the pointer parameter. The return value is GOOD or BAD.</li>

 <li><strong>int printFloat (float f) – </strong>print the floating point number <em>f </em>in left-aligned form. Printing sign for a negative number is mandatory while for a positive number it is not required. There must be a mandatory decimal point in the output (for example, 25 will be printed as 25.). On success, the function will return the number of characters printed, and on failure it will return BAD.</li>

</ul>

Use the following header file for your C++ program.

<strong>/* Header file for Assignment 2: Name it as “toylib.h” </strong>*/

<strong>#ifndef </strong><strong>TOYLIB H</strong>

<strong>#define TOYLIB H</strong>

<strong>#define BAD -1 #define GOOD 1</strong>

<strong>int printStringUpper (char *);</strong>

1

<strong>int printHexInteger (int); int readHexInteger (int *); int readFloat (float *); int printFloat (float);</strong>

<strong>#endif</strong>

<ol start="2">

 <li>Name your source file as <em>ass2 roll.cpp </em>(where <em>roll </em>is your roll number), which must include only <strong>“toylib.h” </strong>as the header file, and should not contain the function <strong>main()</strong>. Write the <strong>main() </strong>function in a separate file, and use <strong>Makefile </strong>to test your library.</li>

</ol>

For submission, move the <strong>main.c</strong>, <strong>toylib.h</strong>, <strong>Makefile </strong>and <strong>ass2 roll.cpp </strong>in a folder <strong>asgn2 roll</strong>. Zip the folder and upload the file <strong>asgn2 roll.zip </strong>on the moodle server.

<strong>Marking scheme: </strong><em>Each function will carry equal weight. There will be a penalty of 10 marks if Makefile is not provided.</em>