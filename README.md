# Series-of-Digits-Program-by-Atharva-Singh

This Python script provides two main functionalities:

Print a series of digits from a sequence formed by concatenating numbers from 1 to a given number.

Find the number at a specified digit position in the same concatenated sequence.

How It Works
1. Print Series of Digits
The program asks you to enter a number, n.

It creates a string by concatenating numbers from 1 to n.

Example for n=5: "12345"

You specify how many digits of this sequence you want to print.

The program displays the required sequence up to the specified length.

2. Find Number at a Given Digit Position
The program allows you to find which number appears at a specific digit position in the concatenated sequence.

You enter the digit position you are interested in.

The program calculates and prints the number whose digit spans the specified position.

Example Output
text
Enter the number: 20
Enter the digit till you want the series to be printed: 30
The required seq is: 1234567891011121314151617181920
Enter the digit position: 30
Number at digit 30 is: 20
How to Run
Save the script as digit_printing.py.

Execute using Python:

text
python digit_printing.py
Code Features
Uses string concatenation to build sequences.

Employs loops and input handling for dynamic length and queries.

Demonstrates basic Python logic for both forward and reverse digit queries.
