NAME:KATHIRVEL E
COMPANY:CODTECH IT
 SOLUTIONS PVT.LTD
ID:CT08DS9711
DOMAIN:C PROGRAMMING
DURATION:OCTOBER 30th, 2024 to NOVEMBER 30th, 2024
MENTOR:Muzammil Ahmed

OVERVIEW
This C code implements a simple quiz game that allows a user to answer multiple-choice questions. Here's an overview of its components and functionality:

Structure Definition
struct Question: This structure represents a quiz question, which consists of:
char question[256]: A string for the question text.
char options[4][100]: An array of strings representing four possible answer options (A, B, C, D).
char answer: A character representing the correct answer option (e.g., 'A', 'B', 'C', or 'D').
Functions
void displayQuestion(struct Question q):
This function takes a Question structure as an argument and displays the question along with its answer options. It iterates over the options and prints them formatted with corresponding letters (A, B, C, D).
Main Function
int main():
An array of Question structures named quiz is created, containing five quiz questions along with their respective options and correct answers.
The score variable is initialized to keep track of the user's correct answers.
The program prints a welcome message.
A loop iterates over each question in the quiz array, displaying the question and options using displayQuestion().
The user is prompted to enter their answer (A, B, C, or D). The input is read, and the character is converted to uppercase to ensure consistency in comparison.
The user's answer is checked against the correct answer stored in the quiz array. If the answer is correct, the score is incremented, and a congratulatory message is displayed. If the answer is incorrect, the correct answer is shown.
After all questions are answered, the total score and the total number of questions are displayed.
Summary
This program is a straightforward interactive quiz game where the user can answer a series of predefined questions related to electronics and electrical engineering concepts. The program evaluates the user's responses and provides feedback, culminating in a final score at the end of the quiz.

Key Points
The quiz consists of multiple-choice questions with four options.
The program uses structures to encapsulate question data.
User input is handled with error checking for character input, ensuring answers are in uppercase.
The quiz keeps track of the score and displays it at the end.
