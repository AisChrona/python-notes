# 1. Functions

# ➤ Simple Function
def greet():
    print("Hello!")

# ➤ Function with Parameters
def add(a, b):
    return a + b

print(add(3, 5))  # Output: 8

 # 2. List

 # ➤ List Basics
fruits = ["apple", "banana", "cherry"]
print(fruits[1])  # banana

# ➤ List Methods
fruits.append("grapes")
fruits.remove("banana")
fruits.sort()
print(fruits)

🧠 Lists are mutable — you can add/remove/change items.

# 3. Tuple

# ➤ Tuple Basics
coordinates = (10, 20)

# ➤ Accessing
print(coordinates[0])  # 10

🧠 Tuples are immutable — cannot change values once created.

 # 4. Dictionary

# ➤ Dictionary Basics
student = {"name": "Akshay", "age": 21}

# ➤ Accessing
print(student["name"])  # Akshay

# ➤ Adding new key
student["grade"] = "A"
print(student)

🧠 Dictionaries store data in key–value pairs.

 # 5. Input/Output

 # ➤ Taking input
name = input("Enter your name: ")
print("Hello", name)

# ➤ Taking integer input
age = int(input("Enter your age: "))
print("You are", age, "years old")

 ✅ Today I practiced functions, list, tuple, dictionary, and I/O.

