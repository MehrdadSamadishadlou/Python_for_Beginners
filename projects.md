---
title: Projects
layout: template
filename: projects
--- 

> **IMPORTANT**  
> The first project deadline: Shahrivar 31st at 11:59 p.m.


# The First Project

Write a program that can play the following game with a computer.

The steps of the game are as follows:

First, the user selects a number between 1 and 99 and does not tell the computer (does not input the number).

The program is executed.

The program guesses and prints a number.

The printed number creates three possible scenarios:

1. The guessed number is larger than the user's secret number. The user types 's' to indicate their number is smaller. The program should guess a smaller number than its previous guess to end the game faster.

2. The guessed number is smaller than the user's secret number. The user types 'l' to indicate their number is larger. The program should guess a larger number than its previous guess to end the game faster.

3. The guessed number matches the user's secret number. The user types 'c' to indicate the program guessed correctly and the game ends.


In summary, the user selects a secret number. The program tries to guess it. Based on the user's input after each guess, the program adjusts its next guess to be a smaller or larger number, until eventually guessing correctly.


# Final Project: Student Grade Analysis

Overview:
This program analyzes student grade data from a CSV file containing 20 students' grades across 8 courses. The program allows the user to explore and output the data in various ways through a command line interface. 

Features:

- Class + mean: Prints the GPA mean for all students in a specified class to the terminal.

- All + class: Prints all students' names and GPAs to the terminal.

- All + alphabet: Writes a CSV file containing all students' names and GPAs, sorted alphabetically by name. 

- All + gpa: Writes a CSV file containing all students' names and GPAs, sorted by GPA.

- Student + name: Prints a specified student's name and GPA to the terminal.

- Best + number: Prints the top n students by GPA and their rank to the terminal. 

- Worst + number: Prints the bottom n students by GPA and their rank to the terminal.

- Invalid command: If the user's input doesn't match any of the above commands, print "Invalid Command" to the terminal.

- Finish: Exits the program.

Other Notes:
- The program reads in the grades CSV file at start-up before prompting the user for commands.
- Define a  function that takes pandas dataframe as input and returns a dictionary containing names and GPAs.
- All numeric outputs are rounded to 2 decimal places.
- The program continues prompting for commands until the user enters "Finish"


**You can download the grades file using the following link:**
<a href="https://drive.google.com/file/d/18g2BOMCJ5X-sVHnOBTnHRgu_WI5mgO3o/view?usp=sharing" target="_blank"><button>Student's Grades</button></a>

