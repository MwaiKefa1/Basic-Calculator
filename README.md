# Basic-Calculator

``python
# Ask for the numbers
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Ask for the operation
operation = input("Enter the operation (+, -, *, /): ")

# Perform the calculation
if operation == "+":
 result = num1 + num2
 print(f"{num1} + {num2} = {result}")

elif operation == "-":
 result = num1 - num2
 print(f"{num1} - {num2} = {result}")

elif operation == "*":
 result = num1 * num2
 print(f"{num1} * {num2} = {result}")

elif operation == "/":
 if num2 != 0:
     result = num1 / num2
     print(f"{num1} / {num2} = {result}")
 else:
     print("Error: cannot divide by zero.")

else:
 print("Invalid operation. Please use +, -, *, or /.")

print("Thanks for using the calculator!")
