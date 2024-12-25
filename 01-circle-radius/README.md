# Circle Calculations

This Python script calculates the **area** and **circumference** of a circle based on a user-provided radius.

## Usage

1. Run the script in a Python environment.
2. Enter the radius of the circle when prompted.
3. The script will compute and display:
   - The area of the circle.
   - The circumference of the circle.

## Code

```python
r = int(input('enter radius '))
a = 3.14 * r * r
c = 2 * 3.14 * r
print('area equal to', a)
print('circumference equal to', c)
