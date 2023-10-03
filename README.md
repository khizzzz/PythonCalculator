# PythonCalculator
Using Function :
def add(a,b):
    return a+b
def subtract(a,b):
    return a-b
def multiply(a,b):
    return a*b
def divide(a,b):
    if a or b == 0 :
        print("Invalid Number 0")
    else :
        return a/b
def calculator ():
    print("Consider me your Calculator")
    print("Select Operator")
    print("+","-","*","/")

    choice=input("Enter any Symbol, (+,-,*,/) :")
    num1=float(input("Enter the first number ="))
    num2=float(input("Enter the second number ="))

    if choice== '+':
        print("Result",add(num1,num2))
    elif choice == '-':
     print("Result",subtract(num1,num2))
    elif choice == '*':
        print("Result", multiply(num1, num2))
    elif choice == '/':
        print("Result", divide(num1,num2))

    else :
        print("Invalid Operator")
calculator()

