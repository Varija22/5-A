PROGRAM 1

Aim:
To write a C++ program that checks whether a given number is even or odd.

Tools Used:

Programiz (Online C++ compiler)

Visual Studio Code (with C++ extension and GCC compiler)

Theory:
A number is even if it is divisible by 2, i.e., the remainder when divided by 2 is zero.
A number is odd if it is not divisible by 2, i.e., the remainder is one.
The modulus operator % is used to get the remainder of a division operation in C++. Conditional statements are used to make the decision.

Algorithm:

1.Start the program.

2.Declare an integer variable.

3.Prompt the user to enter a number.

4.Read the number using cin.

5.Use the modulus operator % to check if the number is divisible by 2.

6.If the remainder is 0, display "Even".

Otherwise, display "Odd".

7.End the program.

Conclusion:
The program was successfully executed to check whether an entered integer is even or odd. It makes use of the modulus operator and conditional statements to determine and display the result.

PROGRAM 2
Aim: To write a C++ program that checks whether the entered character is a vowel or a consonant.

Tools Used:

Programiz (Online C++ compiler)

Visual Studio Code (with C++ extension and GCC compiler)

Theory: In the English alphabet, the vowels are: a, e, i, o, u (both lowercase and uppercase). Any alphabetic character that is not a vowel is considered a consonant. The program uses a series of if-else conditions to check if the entered character matches any vowel. Logical OR (||) is used to compare the input with each vowel option.

Algorithm:

1.Start the program.

2.Declare a character variable.

3.Prompt the user to enter a character.

4.Read the character using cin.

5.Use if-else conditions to compare the character with all vowels (both lowercase and uppercase).

If the character matches any vowel, print "Vowel".

Otherwise, print "Consonant".

6.End the program.

Conclusion: The program was successfully implemented and executed. It correctly identifies whether the entered character is a vowel or consonant using character comparison and conditional logic.


PROGRAM 3
Aim: To write a C++ program that takes three numbers as input and determines which one is the largest.

Tools Used:

Programiz (Online C++ compiler)

Visual Studio Code (with C++ extension and GCC compiler)

Theory: To compare three numbers, conditional (if) statements are used. The program checks which number is greater than the other two using nested if conditions. Logical comparisons help identify the largest number among the three inputs. This method does not handle equality cases explicitly unless added.

Algorithm:

1.Start the program.

2.Declare three integer variables.

3.Prompt the user to enter three numbers.

4.Read the values using cin.

5.Use if statements to compare:

If num1 is greater than both num2 and num3, then num1 is the largest.

Else if num2 is greater than both num1 and num3, then num2 is the largest.

Else if num3 is greater than both num1 and num2, then num3 is the largest.

6.Display the result.

7.End the program.

Conclusion: The program was successfully executed to identify the largest number among three given inputs using nested conditional statements. It demonstrates the use of basic comparison logic in C++.

PROGRAM 4
Aim
To perform basic arithmetic operations (Addition, Subtraction, Division, Multiplication) on two numbers using a switch-case statement.

Tools Used
Programiz

Theory
The program takes two floating-point numbers and an integer choice representing the desired arithmetic operation. The switch statement directs the program to perform the selected operation and display the result. The default case handles invalid operation inputs.

Algorithm
1.Start the program.

2.Input two numbers from the user.

3.Display the menu of operations and input the user’s choice.

4.Use a switch statement to:

Case 1: Add numbers

Case 2: Subtract numbers

Case 3: Divide numbers

Case 4: Multiply numbers

5.If choice is invalid, show an error message.

6.Output the result of the selected operation.

7.End the program.

Conclusion
The program demonstrates the use of switch-case for selecting arithmetic operations and handles basic floating-point calculations effectively.

PROGRAM 5
Aim
To display the name of the birth month based on user input using a switch-case statement.

Tools Used
Programiz

Theory
The switch statement allows multi-way branching. It compares the input against constant expressions (cases) and executes the corresponding block of code. If no match is found, the default case is executed.

Algorithm
1.Start the program.

2.Prompt the user to enter a number (1–12) representing their birth month.

3.Use a switch statement to match the number with the corresponding month name.

4.Print the month name.

5.If input is not between 1–12, print an error message.

End the program.

Conclusion
The program successfully maps numeric input (1–12) to corresponding month names using a switch-case construct, demonstrating control flow in C++

