Use of do while loop in python with while loop syntax

The most common technique to emulate a do-while loop in Python is to use an infinite while loop with a break statement wrapped in an if statement that checks a given condition and breaks the iteration if that condition becomes true:
For Example:
while True:
number = int(input("Enter a positive number: "))
print(number)
if not number > 0:
  break

  Output:
  Enter a positive number: 1
  1
  Enter a positive number: 4
  4
  Enter a positive number: -1
  -1

  BREAK AND CONTINUE

  break skips the loop
  continue skips the iteration and jumps to the next iteration
  