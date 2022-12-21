# write a program to check whether a number entered is 3 digit number or not.
number=int(input("Enter a number"))
if(number<1000 and number>99):
    print("It is a 3 digit number")
else:
     print("It is not a 3 digit number")
