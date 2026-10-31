# Student Records and Marks Analyzer 🎓

## 📌 About the Project

**Student Records and Marks Analyzer** is a Python-based command-line application designed to manage student records and analyze their academic performance.

The program collects student details, stores subject-wise marks, calculates total marks and averages, assigns result categories, and generates class-level summaries.

It uses Python's built-in data structures — Lists, Tuples, Sets, and Dictionaries — to organize and process student information efficiently.

This project is developed as part of **Python Technical Training – Module 3: Python Data Structures Mini Project**.

## 🎯 Objectives

- Understand and implement Python data structures.
- Store multiple student records using dictionaries.
- Manage subject-wise marks using lists.
- Use tuples for fixed subject names.
- Perform set operations for subject analysis.
- Calculate student totals, averages, and result categories.
- Generate class-level academic summaries.

## ✨ Features

- Add multiple student records.
- Store unique student IDs and student details.
- Record marks for three subjects.
- Validate student IDs and marks.
- Calculate total marks and average.
- Assign result categories automatically.
- Display all student records.
- Search for students using their IDs.
- Update subject-wise marks.
- Display unique subjects and passed subjects.
- Perform union, intersection, difference, and symmetric difference.
- Generate class performance summaries.
- Display highest and lowest student averages.

## 📚 Data Structures Used

| Data Structure | Purpose |
|---|---|
| List | Store student IDs and subject marks |
| Tuple | Store fixed subject names |
| Set | Find unique and passed subjects |
| Dictionary | Store student records and details |

### Example Data Model

```python
subjects = ("Python", "Maths", "DBMS")

student_records = {
    "S101": {
        "name": "Aman",
        "marks": [78, 65, 88]
    }
}
```

## 🏆 Result Categories

Students are classified according to their average marks.

| Average Marks | Result |
|---|---|
| 75 or above | Distinction |
| 40 – 74.99 | Pass |
| Below 40 | Fail |

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Application Type:** Command-Line Application
- **External Libraries:** None
- **Python Modules:** None required

### Python Concepts Used

- Lists and List Methods
- Tuples and Tuple Unpacking
- Sets and Set Operations
- Dictionaries and Nested Dictionaries
- List Indexing and Slicing
- Data Traversal
- Conditional Statements
- Loops
- Built-in Functions
- Type Conversion

## 📂 Project Structure

```text
student-records-marks-analyzer/
│
├── student_records.py
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/student-records-marks-analyzer.git
```

### 2. Navigate to the Project Folder

```bash
cd student-records-marks-analyzer
```

### 3. Run the Python Program

```bash
python student_records.py
```

## 💻 Example Output

```text
Subjects: ('Python', 'Maths', 'DBMS')

How many students? 2

Student ID: S101
Name: Aman
Python marks: 78
Maths marks: 65
DBMS marks: 88

Student ID: S102
Name: Riya
Python marks: 35
Maths marks: 72
DBMS marks: 61

----- STUDENT REPORT -----

S101 | Aman
Python: 78, Maths: 65, DBMS: 88
Total: 231
Average: 77.00
Result: Distinction

S102 | Riya
Python: 35, Maths: 72, DBMS: 61
Total: 168
Average: 56.00
Result: Pass

Unique subjects: {'Python', 'Maths', 'DBMS'}
Students recorded: 2
```

## 📊 Class Summary

The application calculates:

- Total number of students.
- Overall class average.
- Highest student average.
- Lowest student average.
- Unique subjects.
- Subjects passed by students.

## 📖 Learning Outcomes

Through this project, I practiced:

- Working with multiple Python data structures.
- Understanding mutable and immutable data types.
- Managing structured student information.
- Searching and updating dictionary records.
- Using list indexing, slicing, and traversal.
- Performing mathematical calculations on student marks.
- Applying set operations to compare subject results.

## 🔮 Future Improvements

- Add file handling to save student records permanently.
- Implement a graphical user interface.
- Add database integration.
- Generate downloadable student report cards.
- Add advanced academic performance analytics.

## 👨‍💻 Author

**Adeeb Hami**

B.Tech Student | AI & ML 

---

⭐ If you find this project useful, consider giving it a star!