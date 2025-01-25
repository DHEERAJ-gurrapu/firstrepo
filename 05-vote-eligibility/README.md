# README: Voting Eligibility Program

This program determines whether a user is eligible to vote based on their age.

## Features
- Accepts user input for age.
- Checks if the entered age qualifies the user to vote.
- Provides output based on eligibility criteria.

## How It Works
1. The program prompts the user to input their age.
2. It uses conditional statements to check the age against the voting eligibility threshold (18 years).
   - If the age is greater than 17, the program prints: `You are eligible to vote`.
   - If the age is less than 18, the program prints: `You are not eligible to vote`.

## Code
```python
age = int(input('Enter your age: '))  
if age > 17:  
  print('You are eligible to vote')  
if age < 18:  
  print('You are not eligible to vote')
```

## Usage
1. Copy the code into a Python editor or IDE.
2. Run the program.
3. Enter your age when prompted.
4. Read the output to see if you are eligible to vote.

## Note
- The program checks for both conditions (`age > 17` and `age < 18`), so it will provide an output regardless of the input.
- To improve efficiency and avoid redundant checks, consider using `if-else` instead of two separate `if` statements:

### Improved Version
```python
age = int(input('Enter your age: '))
if age > 17:
  print('You are eligible to vote')
else:
  print('You are not eligible to vote')
```

This updated version ensures only one condition is checked and provides a single output.
