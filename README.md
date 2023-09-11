Description :
This Python program is a factorial calculator that allows the user to calculate the factorial of a non-negative integer. It includes error handling for invalid inputs (negative numbers or non-integers) and provides the option to perform factorial calculations repeatedly.

Features :
Recursive Factorial Calculation: The core functionality of the program is a recursive function that computes the factorial of a given non-negative integer.
Input Validation: The program ensures that the user enters a valid input by continuously prompting for input until a non-negative integer is provided. It handles negative numbers and non-integer inputs gracefully.
Repetitive Calculations: After calculating the factorial for one input, the program asks the user if they want to calculate another factorial. It continues this cycle until the user chooses to exit.

Usage:

git clone https://github.com/Sajitha7/factorial.git
cd factorial
python factorial.py

Enter a non-negative integer when prompted. If an invalid input is provided, the program will display an error message and prompt for a valid input.
The program will calculate and display the factorial of the entered number.
You can choose to calculate another factorial by entering "yes" when asked, or exit the program by entering "no."


Example:

Enter a non-negative integer to calculate its factorial: 5
The factorial of 5 is 120
Do you want to calculate another factorial? (yes/no): yes

Enter a non-negative integer to calculate its factorial: -2
Factorial is not defined for negative numbers. Please try again.

Enter a non-negative integer to calculate its factorial: 7
The factorial of 7 is 5040
Do you want to calculate another factorial? (yes/no): no


Requirements:
Python 3.x

License:
This code is licensed under the MIT License. Feel free to modify and use it in your projects.
