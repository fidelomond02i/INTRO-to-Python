# INTRO-to-Python

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Ask the user to input a mathematical operation
operation = input("Enter an operation (+, -, *, or /): ")

# Perform the operation based on the user's input
if operation == "+":
    result = num1 + num2
elif operation == "-":
    result = num1 - num2
elif operation == "*":
    result = num1 * num2
elif operation == "/":
    result = num1 / num2
else:
    print("Invalid operation")
    result = None

# Print the result
if result is not None:
    print(f"The result is: {result}")
