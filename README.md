# calculation
it's easy to calculate with me
git clone https://github.com/nickson77/mini-calculator.git
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    return x / y

print("Mini Calculator")
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter operation number (1-4): ")

if choice == '1':
    result = add(num1, num2)
    print(f"Result: {result}")
elif choice == '2':
    result = subtract(num1, num2)
    print(f"Result: {result}")
elif choice == '3':
    result = multiply(num1, num2)
    print(f"Result: {result}")
elif choice == '4':
    result = divide(num1, num2)
    print(f"Result: {result}")
else:
    print("Invalid input")
