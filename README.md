# simple__calculator
python calculator
num1=float(input("enter num1:"))
opperator=input("enter opperator:")
num2=float(input("enter num2:"))
if opperator=="+":
    print(num1+num2)
elif opperator=="-":
    print(num1-num2)
elif opperator=="/":
    print(num1/num2)
elif opperator=="*":
    print(num1*num2)
else:
    print("plz try again")
