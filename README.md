def add_numbers(num1, num2):
  """
  This function takes two numbers as input and returns their sum.
  """
  return num1 + num2

# Get input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Calculate the sum
sum_of_numbers = add_numbers(num1, num2)

# Print the result
print("The sum of", num1, "and", num2, "is", sum_of_numbers)
