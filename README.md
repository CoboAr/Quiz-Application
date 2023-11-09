# Quiz-Application

## Requirements 
pip install requests

## What is Quiz Application?
It is a software designed like a Quiz asking the user 10 questions. It is implemented using tkinter library, html and requests python modules.

## How does it work?
The software sends a request to get data from the Open Trivia Database. It converts the data into a json file and stores it into a variable named question_data. QuizBrain class gets as an argument the list of questions, and keeps track of the right and wrong asnwers. If the user gives a correct answer the screen will turn green, the score will update and the next questions will get generated. If the user will give a wrong answer the screen will turn red, and the next question will get generated. QuizInterface creates the user interface. After 10 questions the Quiz will stop generating new questions.

## Demo

https://github.com/CoboAr/Quiz-Application/assets/144629565/5f404126-e534-4337-9962-112224abb864

Enjoy! And please do let me know if you have any comments, constructive criticism, and/or bug reports.
## Author
## Arnold Cobo
