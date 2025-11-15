# ===========================  
# (i) List Operations  
# ===========================  
  
print("=== LIST OPERATIONS ===")  
# Creating a list of 10 students  
students = ["Ali", "Sara", "Omar", "Aisha", "Zain", "Fatima", "Hassan", "Amna", "Usman", "Maryam"]  
print("Original List:", students)  
  
# Addition of elements  
students.append("Bilal")  # Adding a single element  
students.extend(["Noor", "Sameer"])  # Adding multiple elements  
print("After Addition:", students)  
  
# Remove elements  
students.remove("Omar")  # Remove by value  
students.pop(0)  # Remove first element by index  
print("After Removal:", students)  
  
# Change elements  
students[1] = "Nadia"  # Replace element at index 1  
print("After Changing Elements:", students)  
  
# ===========================  
# (ii) Interchange List Items  
# ===========================  
  
print("\n=== INTERCHANGING LIST ITEMS ===")  
# Using temporary variable  
x = 5  
y = 10  
temp = x  
x = y  
y = temp  
print("With Temporary Variable: x =", x, ", y =", y)  
  
# Without using temporary variable  
x, y = y, x  
print("Without Temporary Variable: x =", x, ", y =", y)  
  
# Interchanging elements in the students list  
students[0], students[1] = students[1], students[0]  
print("After Swapping First Two Students:", students)  
  
# ===========================  
# (iii) Dictionary Operations  
# ===========================  
  
print("\n=== DICTIONARY OPERATIONS ===")  
# Creating a dictionary  
student_info = {  
    "Ali": {"age": 20, "grade": "A"},  
    "Sara": {"age": 21, "grade": "B"},  
    "Omar": {"age": 22, "grade": "A"},  
}  
print("Original Dictionary:", student_info)  
  
# Add elements  
student_info["Aisha"] = {"age": 20, "grade": "C"}  
print("After Addition:", student_info)  
  
# Remove elements  
del student_info["Omar"]  
print("After Removal:", student_info)  
  
# Copy dictionary  
student_copy = student_info.copy()  
print("Copied Dictionary:", student_copy)  
  
# Nested dictionary  
nested_dict = {  
    "Class 1": {"Ali": {"age": 20}, "Sara": {"age": 21}},  
    "Class 2": {"Omar": {"age": 22}, "Aisha": {"age": 20}}  
}  
print("Nested Dictionary:", nested_dict)  
