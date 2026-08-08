def add(a, b):
  return a + b
def subtract(a, b):
  return a - b
def multiply(a, b):
  return a * b
def divide(a, b):
  return a / b
def exp(a, b):
  return a ** b
print("Welcome to the calculator!")
button1 = input("Enter the first number: ")
button2 = input("Enter the second number: ")

def calculate():
  operation = input("Enter the operation (+, -, *, /, **): ")
  if operation == "+":
    result = add(float(button1), float(button2))
  elif operation == "-":
    result = subtract(float(button1), float(button2))
  elif operation == "*":
    result = multiply(float(button1), float(button2))
  elif operation == "/":
    result = divide(float(button1), float(button2))
  elif operation == "**":
    result = exp(float(button1), float(button2))
  else:
    print("Invalid operation!")
    return
  print(f"The result is: {result}")

calculate()
