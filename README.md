# Python-Project
Problem 1:
You are required to build a numbering system converter that takes a number input from user
and from which base and to which base including the four studied numbering systems (decimal,
binary, octal, hexadecimal) and display the final result.
The program should display the following menus by the same order Menu 1 should be repeated
until the user choose to exit:
** numbering system converter **
A) insert a new number
B) Exit program
If user types A then show a message " Please insert a number" and take a number as
an input If user types B then exit the program. Else show an error message "please
select a valid choice" and show the same menu again to allow him to choose again.
After inserting the number menu 2 should appear as follows:
** Please select the base you want to convert a number from**
A) Decimal
B) Binary
C) octal
D) hexadecimal
3
Allow user to input his choice and if he types any other input return an error message "Please
select a valid choice".
After selecting from base Menu 3 should appear asking the user to choose to which base he
wants the number to be converted:
** Please select the base you want to convert a number to **
A) Decimal
B) Binary
C) octal
D) hexadecimal
Allow user to input his choice and if he types any other input other than A, B, C, D return an
error message "Please select a valid choice", and if the user choose the same choice as Menu
2 return the inserted number without any change. After selecting to base your program should
calculate the result and output to the screen and show menu 1 again.

Problem 2
You are required to build a Binary calculator that can do addition, subtraction and one's
complement and two's complement conversions. The program should display the following
menus by the same order Menu 1 should be repeated until the user choose to exit:
** binary calculator **
A) Insert new numbers
B) Exit
If user types A then take two numbers from the user If user types B the program should exit.
Else if user types any show an error message " please select a valid choice" and show the same
menu again to allow him to choose again. After selecting A choice ask the user to insert a number
(you should validate the inserted number is a valid binary number if user inputs invalid number as 1235
show an error message "please insert a valid binary number" after inserting the binary number.
4
menu 2 should appear as follows:
** please select the operation **
A) Compute one's complement
B) Compute two's complement
C) addition
D) subtraction
• If user chooses A then compute the one's complement value for the binary number and
show the result to the user and show menu 1 once again
• If user chooses B then compute the two's complement value for the binary number and
show the result to the user and show menu 1 once again
• If user chooses C or D, ask him to insert number 2 as follows: "please insert the second
number" and the same validation to check if the number if a valid binary number else ask
him to insert the second number again.
• In case the user chooses C then add the two numbers together and show the result to
user and show menu 1 again.
• In case the user chooses D then subtract the second number from the first and show the
result to user and show menu 1 again.
