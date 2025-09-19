# grading
🎓 Python Grading Script
📌 Overview

This project is a simple Python program that assigns grades based on student marks.
It’s great for beginners learning conditional statements (if-elif-else).

🗂️ File

grading.py → Contains the grading function and example execution.

🔧 How It Works

Define a function grade(marks)

The program checks marks and assigns:

🏆 A → marks >= 90

🥈 B → marks >= 80

🥉 C → marks >= 70

❌ D → marks < 70

The result is displayed using print().

▶️ Example Usage
def grade(marks):
    if marks>=90:
        print("A")
    elif marks>=80:
        print("B")
    elif marks>=70:
        print("c")
    else:
        print("D")

grade(78)


Output:

c

🚀 Possible Improvements

🔤 Fix "c" → "C" for consistency

📥 Take user input instead of hardcoding values

📊 Add more grade categories (A+, F, etc.)

🧪 Write test cases for multiple scenarios
