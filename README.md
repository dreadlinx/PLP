Fun Calculator 🧮✨

Welcome to the Fun Calculator! This lightweight Python script performs basic arithmetic operations on two numbers with style and flair. Perfect for beginners learning Python or anyone who enjoys colorful math operations!
Features 🌟

    ➕ Addition

    ➖ Subtraction

    ✖️ Multiplication

    ➗ Division

    💫 Decimal-friendly operations

    🎉 Fun emoji-enhanced output

How to Use 🚀

    Ensure you have Python installed

    Run the script:
    bash

    python fun_calculator.py

    Enter your first number when prompted

    Enter your second number when prompted

    Marvel at your results!

Example Output 📊
text

Enter the first number: 8.5
Enter the second number: 2.5
Results of your two numbers:
Sum: 11.0
Difference: 6.0
Product: 21.25
Quotient: 3.4

Important Notes ⚠️

    🔢 The calculator accepts both integers and decimals

    🚫 Division by zero will crash the program (be careful!)

    💡 Perfect for simple calculations - not designed for complex math

Code Structure 🧱
python

# Get user input converted to float
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform calculations
sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2  # Will crash if num2 is 0!

# Display formatted results
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")
print(f"Difference: {difference_result}")
print(f"Product: {product_result}")
print(f"Quotient: {quotient_result}")
