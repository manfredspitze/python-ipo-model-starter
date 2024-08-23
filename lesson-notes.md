# Lesson Notes
## The IPO Model of Programming

### Directions
- Read these notes and check out the related resources before you start writing any code for this lesson


### Related Resources
- [The Python input( ) Function](https://www.w3schools.com/python/ref_func_input.asp)
- [Python print( ) Function](https://www.w3schools.com/python/ref_func_print.asp)


### Notes

- IPO in IPO Model is short for:
  - input (I)
  - process (P)
  - output (O)
- You can get input from the user in several ways, but the built-in Python `input ( )` function is one of the most commonly used ways of getting input from the user
- Once you get data from the user, you can **process** that data, i.e., do something with or to that data
- Output is just another word for **results**

### Arranging Your Code Using the IPO Model

- Generally speaking, you can use the **IPO Model** to arrange/organize the code in your script
- The IPO Model doesn't work for all scripts, but it will work for many of the scripts you write
  - Start by getting input from the user (prompting the user for some input)
  - Then **manipulate** or do something with that input
  - Finally, write the code to show the results or the answer Python generated for you

 ### Example 1: IPO Model
```python
# Input
exam_score1 = 88
exam_score2 = 91

# Process the input by calculating the total number of points
total_points = exam_score1 + exam_score2

# Show the output (the total number of points earned on the two exams)
print(f'Total number of points earned: {total_points}')
```

 ### Example 2: IPO Model
 ```python
# Get number of inches from the user and then convert inches to centimeters
# Input
num_inches = input('Enter the number of inches to convert to centimeters:\n')
num_inches = float(num_inches) # Convert inches to a floating-point number

# Process
# Do the math to convert inches to centimeters
# CONVERSION_FACTOR is a Python constant, since it's capitalized and
# the value of 2.54 inches per centimeter will never change (remains constant)
CONVERSION_FACTOR = 2.54 # Each inch is equivalent to 2.54 centimeters
num_cm = num_inches * CONVERSION_FACTOR

# Output
# Show the results
print(f'{num_inches} inches is equivalent to {num_cm} centimeters.')
```



