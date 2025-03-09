# ASSIGNMENT-2
Module 3: Control Structures in Python
#Task 1: Check if a Number is Even or Odd
number = int(input("Enter a Number: "))
if number % 2 == 0:
    print(number, "is even number.")
else:
    print(number, "is odd number.")

# Task 2: Sum of Integers from 1 to 50 Using a Loop
sum = 0
for num in range(1, 51):
    sum += num
print("The sum of numbers from 1 to 50 is: " ,sum)    
