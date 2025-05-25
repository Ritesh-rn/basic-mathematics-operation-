# basic-mathematics-operation-
# take two numbers as input from the user.
num1=float(input("Enter the firt number:"))
num2=float(input("Enter the secound number:"))
#performs the basic mathematical operation on these two numbers: 
addition=num1+num2
subtraction=num1-num2
multiplication=num1*num2
division=num1/num2
# displays the result of each opertion on the screen.
print(addition)
print(subtraction)
print(multiplication)
print(division)

# output 
Enter the firt number: 5
Enter the secound number: 9

14.0
-4.0
45.0
0.5555555555555556

# Creating personalize greeding
#step1: take user's first name and last name as input
first_name=input("Enter your first name:")
last_name=input("Enter your last name:")

#step2: concatenates  fist name and last name into a full name.
full_name=first_name+""+last_name

#step3: print a personalized greeting message unig the full name.
print("Hello,"+full_name+"! Welcome to the python programing.")

# output
Enter your first name: Ritesh
Enter your last name: Dawande

Hello,RiteshDawande! Welcome to the python programing.

