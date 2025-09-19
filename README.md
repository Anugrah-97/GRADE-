# GRADE-
# Grade Function README

## Overview

This Python program defines a function `grade(marks)` that assigns a grade based on the marks provided. It uses conditional statements (`if`, `elif`, `else`) to categorize the marks into different grade levels.

## Code Explanation

```python
def grade(marks):
    if marks >= 90:
        print("A")
    elif marks >= 80:
        print("B")
    elif marks >= 70:
        print("C")
    else:
        print("D")

# Example usage
grade(78)
```

### Step-by-Step:

1. **Function Definition**: `grade(marks)` accepts one parameter `marks`.
2. **Conditions**:

   * If `marks >= 90`, it prints **"A"**.
   * If `marks >= 80`, it prints **"B"**.
   * If `marks >= 70`, it prints **"C"**.
   * Otherwise, it prints **"D"**.
3. **Example**: When calling `grade(78)`, the program outputs **"C"**, because 78 is greater than 70 but less than 80.

## Sample Outputs

| Marks | Output Grade |
| ----- | ------------ |
| 95    | A            |
| 84    | B            |
| 78    | C            |
| 60    | D            |

## How to Run

1. Copy the code into a Python file, e.g., `grade.py`.
2. Run the file in a terminal:

   ```bash
   python grade.py
   ```
3. The program will output the grade according to the given marks.

## Improvements (Optional)

* Accept user input for marks using `input()`.
* Return the grade instead of just printing it.
* Add validation to check if marks are within `0–100`.

---

This program demonstrates the use of **conditional statements** in Python for decision-making.
