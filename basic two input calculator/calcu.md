```
print("WELCOME TO TWO INPUT CALCULATOR")
num_one=float(input("ENTER THE FIRST NUMBER="))
num_two=float(input("ENTER THE SECOND NUMBER="))
print("AVAILABLE OPERATORS")
print("1.ADDITION (+)")
print("2.SUBTRACTION (-)")
print("3.MULTIPLICATION (*)")
print("4.DIVISION (/)")
choice=input("ENTER YOUR CHOICE:(1/2/3/4/5): ")
if choice=="1":
    addition=num_one + num_two
    print("ADDITION OF TWO NUMBERS=",addition)
elif choice=="2":
    subtraction=num_one - num_two
    print("SUBTRACTION OF TWO NUMBERS=",subtraction)
elif choice=="3":
    multiplication=num_one * num_two
    print("MULTIPLICATION OF TWO NUMBERS=",multiplication)
elif choice=="4":
    if num_two !=0:
        division=num_one / num_two
        print("DIVISION OF TWO NUMBERS=",division)
    else:
    print("WE CAN'T DIVIDE THIS NUMBER")
else:
    print("INVALID CHOICE")```
