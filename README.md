## Project Loan Qualifier

The user of this python project will be able to see qualifying loans from a list of lenders. The application works by taking in a `daily_rate_sheet.csv` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans. The project will also prompt and ask the user if they want to save the qualifying loans as a new csv file. 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Go to your terminal and run conda activate dev to activate your conda dev environment.
You will install the following libraries and modules to run in Python codes you create.
Install Fire and Questionary by...
    pip install fire
    pip install questionary
    
## Usage

To use this application simply clone the repository and run the app.py
Once you 

When asked to enter a file path to a rate-sheet (.csv): imput data/daily_rate_sheet.csv
You will then be asked a seires of questions listed below.
- What's your credit score?
- What's your current amount of monthly debt?
- What's your total monthly income?
- What's your desired loan amount?
- What's your home value?
Once you answer these questions 

---

## Contributors

linkedin.com/in/john-sung-3675569

---

## License

MIT
