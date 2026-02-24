# 📘 README – Sets and Dictionaries in Python
🧠 ## Aim

To study and implement Sets and Dictionaries in Python and understand their operations, properties, and real-world applications.

# 🎯 Objectives

To understand the concept of Sets in Python.

To perform set operations such as union, intersection, and difference.

To understand Dictionaries and key-value pair storage.

To perform dictionary operations like adding, updating, deleting, and looping.

To compare sets and dictionaries with other data structures like lists.

# 📖 Theory
🔹 Sets in Python

A Set is an unordered collection of unique elements. Sets are useful when you want to store non-duplicate values and perform mathematical operations like union and intersection.

Characteristics:

Unordered

No duplicate values

Mutable

Defined using {} or set()

🔹 Dictionaries in Python

A Dictionary is a collection of data stored in key-value pairs. It is used when data needs to be associated with unique keys.

Characteristics:

Keys must be unique

Mutable

Fast lookup using keys

Defined using {key: value}

# 🛠 Implementation
✅ Set Example
# Creating sets
A = {1, 2, 3}
B = {3, 4, 5}

# Set operations
print("Union:", A.union(B))
print("Intersection:", A.intersection(B))
print("Difference:", A.difference(B))
✅ Dictionary Example
# Creating dictionary
student = {
    "name": "Alice",
    "age": 20,
    "course": "Computer Science"
}

# Accessing data
print(student["name"])

# Updating data
student["age"] = 21

# Adding new data
student["grade"] = "A"

# Looping
for key, value in student.items():
    print(key, ":", value)
▶ Procedure

Install Python 3.x.

Open a code editor (VS Code / IDLE / PyCharm).

Create a Python file (e.g., sets_dict.py).

Write the set and dictionary code.

Run the program using:

python sets_dict.py
📊 Applications
🔹 Sets

Removing duplicate values from a list

Performing mathematical set operations

Membership testing

🔹 Dictionaries

Storing student records

Phonebooks

Database-like key-value storage

Counting word frequency

# 🏁 Conclusion

This project helped in understanding the implementation and practical use of Sets and Dictionaries in Python. Sets are useful for handling unique elements and mathematical operations, while dictionaries are powerful for storing structured data using key-value pairs.
