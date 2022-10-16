# Faulty_calculator
num1 = int(input("provide first number: "))
num2 = int(input("Provide second number: "))

multiply = num1 * num2
divide = num1 / num2
subtract = num1 - num2
add = num1 + num2

print("provide Operator from +,-,/,*")
operator = input("provide an operator: ") 

#Faulty Conditions
if (num1 == 43 and num2 == 3) and operator == "*":
    print(int(555))
elif (num1 == 56 and num2 == 9) and operator == "+":
    print(int(77))
elif (num1 == 56 and num2 == 6) and operator == "/":
    print(int(4))
elif operator == "*":
    print("Output: ",multiply)
elif operator == "/":
    print("Output: ",divide)
elif operator == "-":
    print("Output: ",subtract)
elif operator == "+":
    print("Output: ",add)
else:
    print("invalid operator")
