# Challenge 2

At one of my recent meetings, a client requested a feature with which they would be able to save their qualified loan to a csv file. This project created a function to promt the user if they would like to save their data, and interpert their answer. Aditionally I created a function to save the data to a csv.
---

## Technologies

Technologies required to use my project are as follows:
Python 3.9
Python add-ons: sys, fire, questionary
Required libraries for this project are:
Folders:qualifier/filter, qualifier/utils
Files:daily_rate_sheet.csv, app.py

Make sure to update all systems to their most current version!

---

## Installation Guide

To install python add-ons enter in terminal:
```
pip install fire
```
Then:
```
pip install questionary
```

---

## Usage

First run the app.py file in the terminal, then you will be prompted in the way below.
Enter what the prompt asks and it will provide you with a csv of your qualified loans.
Example:
```
? Enter a file path to a rate-sheet (.csv): daily_rate_sheet.csv
? What's your credit score? 800
? What's your current amount of monthly debt? 1000
? What's your total monthly income? 10000
? What's your desired loan amount? 10000
? What's your home value?
The monthly debt to income ratio is 0.10
The loan to value ratio is 0.10.
Found 24 qualifying loans
? Would you like to save your list of qualifying loans? Yes
Your qualifying loans have been saved.
```

---

## Contributors

Contributors: Boris Gorelenkov
Email: bgorelen@gmail.com
LinkedIn:https://www.linkedin.com/in/boris-gorelenkov-449b571b9/

---