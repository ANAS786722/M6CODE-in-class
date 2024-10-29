# M6CODE-in-class
# Anas Mohammed
# 10-29-2024
# Problem 2: Ask the user to choose a day of the week and print a message.

# List of days of the week
days_of_week = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"]

# Ask the user to choose a day
user_day = input("Choose a day of the week: ")

# Print the message directly
print(f"It was a rainy {user_day} and the lightning flashed across the sky.")



# Anas Mohammed
# 10-29-2024
# Problem 3: Simulate a coin flip and track the percentage of heads.

import random

# Probability of heads
X = 70  
num_flips = 1000

# Initialize counts
heads_count = 0  

# Simulate coin flips
for _ in range(num_flips):
    if random.randint(1, 100) <= X:
        heads_count += 1  # Count heads

# Calculate percentage of heads
heads_percentage = (heads_count / num_flips) * 100  

# Print results
print("Heads appeared", heads_count, "times, which is", round(heads_percentage, 2), "%.")  




# Anas Mohammed
# 10-29-2024
# Problem 4: Calculate factorial using math module and a loop.

import math

# Get user input
num = int(input("Enter a non-negative integer: "))  # Input

# Calculate factorial using math module
math_factorial = math.factorial(num)

# Calculate factorial using a loop
loop_factorial = 1
for i in range(1, num + 1):
    loop_factorial *= i  # Multiply to get factorial

# Print results
print("Factorial using math:", math_factorial)
print("Factorial using loop:", loop_factorial)


# Anas Mohammed
# 10-29-2024
# Problem 1: Print 10 random integers between 25 and 35.

import random

rand_nums = []  # List to hold random numbers

for _ in range(10):
    num = random.randrange(25, 36)  # Random number between 25 and 35
    rand_nums.append(num)  # Add to list
    print(num)  # Print the random number

print("List of random numbers:", rand_nums)  # Print the list


