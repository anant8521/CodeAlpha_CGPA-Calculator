
# 📘 CGPA Calculator (C++)

This is a simple and interactive **CGPA (Cumulative Grade Point Average) Calculator** written in C++. It allows students to input their course grades and credit hours, and then calculates and displays their CGPA along with a detailed summary.

---

## 🚀 Features

- ✅ Accepts user input for course name, grade, and credit hours.
- ✅ Validates grade and credit entries.
- ✅ Converts letter grades (A+, A, B+, etc.) to grade points.
- ✅ Calculates and displays:
  - Total Credits
  - Total Grade Points
  - Final CGPA
- ✅ Shows course-wise summary in tabular format.
- ✅ User-friendly CLI interface with emojis for clarity.

---

## 🛠️ Technologies Used

- **Language:** C++
- **Libraries:**
  - `<iostream>` – Input/Output operations
  - `<iomanip>` – Formatting output (e.g., precision, alignment)
  - `<vector>` – Dynamic arrays
  - `<string>` – String handling
  - `<map>` – Grade to point mapping

---

## 🧮 Grade Mapping

| Grade | Grade Point |
|-------|-------------|
| A+    | 10.0        |
| A     | 9.0         |
| B+    | 8.0         |
| B     | 7.0         |
| C+    | 6.0         |
| C     | 5.0         |
| D     | 4.0         |
| F     | 0.0         |

---

## 📦 How to Run

1. **Copy** the `CGPA Calculator` C++ code into a `.cpp` file (e.g., `cgpa_calculator.cpp`).
2. **Compile** the file using a C++ compiler:
   ```bash
   g++ cgpa_calculator.cpp -o cgpa_calculator
   ```
3. **Run** the executable:
   ```bash
   ./cgpa_calculator
   ```

> 💡 You can also run it in an online compiler like [OnlineGDB](https://www.onlinegdb.com/) or [Programiz](https://www.programiz.com/cpp-programming/online-compiler).

---

## 📝 Sample Output

```
📘 CGPA Calculator
-------------------------
Enter the number of courses: 3

📚 Enter details for Course 1:
Course Name: Mathematics
Grade (A+, A, B+, B, C+, C, D, F): A
Credit Hours: 4

📚 Enter details for Course 2:
Course Name: Physics
Grade (A+, A, B+, B, C+, C, D, F): B+
Credit Hours: 3

📚 Enter details for Course 3:
Course Name: Programming
Grade (A+, A, B+, B, C+, C, D, F): A+
Credit Hours: 5

📋 Course-wise Grade Summary:
-----------------------------------------
  No.        Course Name     Grade   Credits
    1          Mathematics       A         4
    2               Physics      B+         3
    3           Programming     A+         5
-----------------------------------------
🎯 Total Credits: 12.00
🌟 Total Grade Points: 110.00
📈 Final CGPA: 9.17
```

---

## 📚 Future Enhancements

- Export results to a `.txt` or `.csv` file
- Add GUI interface using Qt or SFML
- Support for multiple semesters and overall CGPA
- Grade entry with percentage-to-grade conversion

---

## 👨‍💻 Author

**Anant Kiranmauli**  
🎓 Electrical Engineering Student  
📍 Government Polytechnic, Munger  
🧠 Focus: Coding, Logic, and Engineering Applications

---

## 📜 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
