# calculating_average
def calculate_average(numbers):
    if not numbers:
        return None
    
    total = sum(numbers)
    average = total / len(numbers)
    return average

# Example list of numbers
numbers = [5, 10, 15, 20, 25]

# Calculate the average
average = calculate_average(numbers)
print("Average:", average)
