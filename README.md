# operator
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
op = input("Enter operator (+, -, *, /): ")

if op == '+':
    print("Result:", a + b)
elif op == '-':
    print("Result:", a - b)
elif op == '*':
    print("Result:", a * b)
elif op == '/':
    if b != 0:
        print("Result:", a / b)
    else:
        print("Division by zero is not allowed")
else:
    print("Invalid operator")
 output
 Enter first number: 10
Enter second number: 5
Enter operator (+, -, *, /): /
Result: 2.0
