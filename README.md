QuizGradingSystem
Overview

QuizGradingSystem is a Python-based application that automates the grading process for student quizzes. It compares student answers against a set of correct answers, calculates the total number of correct and incorrect responses, and identifies the specific questions that were answered incorrectly.
Features

    Reads student answers from a text file.
    Compares student answers to a predefined set of correct answers.
    Counts total correct and incorrect responses.
    Lists the question numbers for incorrectly answered questions.
    User-friendly output indicating pass/fail status based on correct responses.

Prerequisites

To run this Python program, you need:

    Python 3.x installed on your system.

Installation

    Clone the repository to your local machine:

    bash

git clone https://github.com/your-username/QuizGradingSystem.git

Navigate to the project directory:

bash

    cd QuizGradingSystem

    Ensure you have a text file named students.txt containing the students' answers (one answer per line).

Usage

    Run the QuizGradingSystem.py file:

    bash

    python QuizGradingSystem.py

    The program will read from students.txt and display the grading results.

Example

Suppose students.txt contains the following:

css

A
C
B
A
D
...

Output:

mathematica

Total Students: 5
Total Number Correct: 4
Total Number Incorrect: 1
Incorrect Question Numbers: [2]
You passed!

Error Handling

    The program handles the case where students.txt is not found, providing an appropriate error message.
    It also accounts for other exceptions to enhance robustness.

