```python
# Print hello world
print('Hello world')

# Declare variables
x = 10
y = 3
f = 8. # float
z = 'words' # string
b = True # boolean

# Do math
x + y
x - y
x * y
x / y
x // y # Floor division
x + f # can add integer and float
x += f # Add and assign, x will become a float

x + z # Raises TypeError
x + b # Raises TypeError

# String concatenation
z + '! =)'
z + str(x) # Type casting

# Introduce types
type(x) # Et cetera...

# Lists
l = [False, 1, 2.0, 3]
print(l)
print(l[0]) # Print first element
print(l[-1]) # Print last element
print(l[1:3]) # Print open-ended slice
l.append('banana')
print(l)

# User input
answer = input('What is your name? ')
print('My name is', answer)

# If statements
num = 10
if num > 0:
    print('Positive')
else:
    print('Not positive')
# Try with a negative number

# For loops
for i in range(10):
    print(i)
for item in l:
    print('Item:', item)

# While loops
num = 67
while num > 0:
    if num % 2  == 0:
        num //= 2
    else:
        num = num * 2 + 3
    print(num)

# Try-catch blocks
i = 3
try:
    print(l[i])
except IndexError:
    print(i, 'is out of bounds')
# Try with a number >= 4

# Functions
def add_two(a):
    return a + 2

def minus_one(b):
    return b - 1

add_two(10)
minus_one(10)

# Two plus two is four,
# Minus one that's three quick maths!
minus_one(add_two(2))

# File I/O
with open('filename.txt') as f:
    # Don't forget to strip whitespace
    content = f.read().strip()
```
