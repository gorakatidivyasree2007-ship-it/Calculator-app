# Calculator-app
A simple Python calculator that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. It also handles division by zero and invalid operators.
a = float(input("Enter first number: "))
op = input("Enter operator (+, -, *, /): ")
b = float(input("Enter second number: "))

if op == "+":
    print("Result:", a + b)
elif op == "-":
    print("Result:", a - b)
elif op == "*":
    print("Result:", a * b)
elif op == "/" and b != 0:
    print("Result:", a / b)
else:
    print("Invalid operator or division by zero")
