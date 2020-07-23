# Faulty-calculator
#This program is used to design a faulty calculator which gives some wrong values for some specific operation otherwise it gives right values.
#Design a calculator which will solve all the prblm except the following ones:
#45+3=555,56+9=77,56/6=4
#and then return the result.

a=int(input("Enter the first Number:"))
b=int(input("Enter the second number:"))
operator=input("Enter the operator like +,-,*,/,//,**,%:")
if a==45 and b==3 and operator=='+':
    print("555")
elif a==56 and b==9 and operator=='+':
    print('77')
elif a==56 and b==6 and operator=='/':
    print('4')
elif operator=="+":
    print(a+b)
elif operator=="/":
    print(a/b)
elif operator=="-":
    print(a-b)
elif operator=="*":
    print(a*b)
elif operator=="**":
    print(a**b)
elif operator=="//":
    print(a//b)
elif operator=="%":
    print(a%b)
else:
    print("Error ,please re enter the numbers.")
