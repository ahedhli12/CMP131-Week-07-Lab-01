# CMP 131 – Python Programming

> **Required file location:** Keep every Python file directly in the repository root. Do not create a `src` folder.

## Week 7 – Lab 1: Shipping Charges and Loop Applications

**Total Points: 100**

- Program 1: Fast Freight Shipping Charges — 40 points
- Program 2: Calories Burned — 30 points
- Program 3: Sum of Numbers — 30 points

## Learning Objectives

After completing this lab, students should be able to:

- Accept and convert numeric user input.
- Validate input using conditional statements and loops.
- Use `if`, `elif`, and `else` statements.
- Use loops to repeat calculations.
- Use an accumulator to calculate a running total.
- Work with loop starting values, ending values, and increments.
- Format numeric and monetary output.
- Test programs using normal, boundary, and invalid values.
- Use comments to explain major program sections.

## Assignment Overview

Create three separate Python programs:

1. `shipping_charges.py` — calculate Fast Freight shipping charges based on package weight and distance.
2. `calories_burned.py` — use a loop to display calories burned at specific time intervals.
3. `sum_of_numbers.py` — use a loop and accumulator to total all integers from 1 through a positive integer entered by the user.

The instructor is not providing completed Python code or an exact output design. Students must design, write, and test their own programs.

# Program 1: Fast Freight Shipping Charges

**Points: 40**

Create `shipping_charges.py`.

Fast Freight uses these rates per 500 miles:

| Weight of Package | Rate per 500 Miles |
| --- | ---: |
| 2 kg or less | $1.10 |
| Over 2 kg but not more than 6 kg | $2.20 |
| Over 6 kg but not more than 10 kg | $3.70 |
| Over 10 kg but not more than 20 kg | $4.80 |

Your program must:

- Display a descriptive program title.
- Ask for package weight in kilograms.
- Accept weights greater than 0 and no more than 20 kilograms.
- Use a loop to reject invalid weights and ask again.
- Ask for shipping distance in miles.
- Accept distances from 10 through 3,000 miles.
- Use a loop to reject invalid distances and ask again.
- Use `if`, `elif`, and `else` to select the correct shipping rate.
- Calculate the shipping charge using: **rate × (distance ÷ 500)**.
- Display the package weight, shipping distance, rate, and total charge.
- Format monetary values with a dollar sign and two decimal places.

### Required Testing

Verify at least these cases:

- 2 kg and 500 miles → rate $1.10 and charge $1.10.
- 4 kg and 1,000 miles → rate $2.20 and charge $4.40.
- 8 kg and 1,500 miles → rate $3.70 and charge $11.10.
- 15 kg and 2,000 miles → rate $4.80 and charge $19.20.
- Invalid weight values such as 0 and 21 must be rejected.
- Invalid distance values such as 9 and 3001 must be rejected.

# Program 2: Calories Burned

**Points: 30**

Create `calories_burned.py`.

Running on a particular treadmill burns approximately **3.6 calories per minute**.

Use a loop to display the calories burned after:

- 5 minutes
- 10 minutes
- 15 minutes
- 20 minutes
- 25 minutes
- 30 minutes

Your loop must:

- Begin with 5 minutes.
- End with 30 minutes.
- Increase by 5 minutes each repetition.
- Calculate calories as **minutes × 3.6**.
- Display each result from inside the loop.

Do not write six separate calculation statements.

Expected calculated values are 18.0, 36.0, 54.0, 72.0, 90.0, and 108.0 calories.

# Program 3: Sum of Numbers

**Points: 30**

Create `sum_of_numbers.py`.

Ask the user to enter a positive integer. Use a loop and accumulator to calculate the sum of all integers beginning with 1 and ending with the number entered by the user.

Your program must:

- Convert the input to an integer.
- Reject zero and negative values.
- Use a validation loop until a value greater than zero is entered.
- Create an accumulator beginning at 0.
- Use a loop to process every integer from 1 through the entered number.
- Include the ending number in the total.
- Display the entered number and calculated sum.
- Not use Python's built-in `sum()` function.

Required checks include:

- 1 → 1
- 5 → 15
- 10 → 55
- 50 → 1275
- Negative numbers and zero must be rejected and requested again.

# Code Comments

Each Python file must include a comment header containing:

- Student name
- Course number
- Week number
- Lab number
- Assignment title
- Date

Use comments to identify major sections such as input, validation, conditions, loops, calculations, and final output.

# General Requirements

- Use meaningful variable names.
- Convert input to the correct data type.
- Use loops and conditional statements where required.
- Keep all Python files in the repository root.
- Make sure every program runs without errors.
- Test using the required values.
- Follow `AI-Use-Policy.md`.
- Complete `AI-Use-Report.md` honestly.

# Submission Requirements

Your repository must include:

- `CMP131-Week-07-Lab-01.md`
- `shipping_charges.py`
- `calories_burned.py`
- `sum_of_numbers.py`
- `AI-Use-Policy.md`
- `AI-Use-Report.md`

Before submitting:

1. Run and test all three programs.
2. Confirm filenames are correct.
3. Confirm all required files are in the repository root.
4. Complete the AI-use report.
5. Commit and push your latest work.
6. Verify the newest files on GitHub.
7. Submit through Blackboard Ultra as directed.

**Do not push your work to the instructor's starter repository.**
