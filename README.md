# Cis106-S1
Write the code for the following problems. Use separate functions for input, each type of processing, and output. Avoid global variables by passing parameters and returning results. Create test data to validate the accuracy of each program. Add comments at the top of the program and include references to any resources used.
Create a program that asks the user for a single line of text containing a first name and last name, such as Firstname Lastname. Use string functions/methods to parse the line and print out the name in the form last name, first initial, such as Lastname, F. Include a trailing period after the first initial. Handle invalid input errors, such as extra spaces or missing name parts.


Create a program that asks the user for a line of text. Use string functions/methods to delete leading, trailing, and duplicate spaces, and then print the line of text backwards. For example:
      the   cat   in   the   hat  
    tah eht ni tac eht
Use separate subroutines/functions/methods to implement input, each type of processing, and output. Avoid global variables by passing parameters and returning results.

Create a program that asks the user for a line of comma-separated-values. It could be a sequence of test scores, names, or any other values. Use string functions/methods to parse the line and print out each item on a separate line. Remove commas and any leading or trailing spaces from each item when printed.


Create a program that asks the user for a line of text. Then ask the user for the number of characters to print in each line, the number of lines to be printed, and a scroll direction, right or left. Using the given line of text, duplicate the text as needed to fill the given number of characters per line. Then print the requested number of lines, shifting the entire line's content by one character, left or right, each time the line is printed. The first or last character will be shifted / appended to the other end of the string. For example, if shifting the line to the left:
    Repeat this. Repeat this. 
    epeat this. Repeat this. R
    peat this. Repeat this. Re
Or if shifting the line to the right:
    Repeat this. Repeat this. 
     Repeat this. Repeat this.
    . Repeat this. Repeat this
