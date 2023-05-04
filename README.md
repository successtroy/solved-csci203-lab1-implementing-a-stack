Download Link: https://assignmentchef.com/product/solved-csci203-lab1-implementing-a-stack
<br>
For this exercise you are to write a program (in C, C++, Java or Python) that reads a text file containing a number of words and displays the words on the screen in reverse order using a stack. A pseudo‐code outline for the program is given below:

<strong>    Begin main </strong>

<strong>        display a prompt for the file name         read in the file name         try to open the file         if the file fails to open </strong>

<strong>            print an error message on the screen and exit          fi         do </strong>

<strong>            read in a word from the file             if the file read fails                 terminate (break) the loop             fi </strong>

<strong>            Push the word onto the stack         od         close the file         while the stack is not empty </strong>

<strong>            display the top stack word on the screen followed by a space             pop the top value from the stack </strong>

<strong>        elihw     End main </strong>

Do not implement the stack using a class or struct or with STL. The stack must be implemented using a fixed size array of words and an index integer for indicating the top of the stack. The stack array and index should be global variables. A word can be a string or a c‐string (i.e. a character array). You can assume no word is more than 20 characters long. The stack functions (i.e. push(), top(), pop(), isEmpty() ) should be implemented below the main() and prototyped above the main().

When you are finished, test your program using the provided text file named “Ex1.txt” and show your code and the output to your lab tutor to receive your mark.

When you are finished, test your program using the provided text file named “Ex1.txt” and submit it via moodle.


