# Loan Qualifier Application

This application uses credit score, debt to income, ltv, and max loan size to pair applicants to a bank that would offer them loan. It then has the functionality to save the qualifying loans as a CSV file.

---

## Technologies

Using Python 3.7

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with prompts to enter your financial information.
You will then be prompted for an output file path to save the csv.

You will be greeted with the following prompts.

![Loan Qualifier Prompts](images/Screen%20Shot%202022-06-29%20at%2010.20.26%20PM.png)


---

## Contributors

Sole Contributor - Josh Thompkins

---

## License

Everyone is free to view and work with this project, you may not alter text unless given explicit permission.
