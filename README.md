# Assignment.py
Here a two program. The first one is to check even or odd number by taking input from the user. 
The second one is to calculate the sum of integers in a given range of numbers. 

# PROGRAM 1

number = int(input("Enter a number: "))
if number % 2 ==0:
    print(f"{number} is an even number.")
else: 
     print(f"{number} is an odd number.")

# PROGRAM 2

total_sum = 0

for number in range(1, 51):
    total_sum += number
print("The sum of integer from 1 to 50 is: ", total_sum)

