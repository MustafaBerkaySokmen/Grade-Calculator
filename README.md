# Grade Calculator

## Overview
The **Grade Calculator** is a Python program designed to calculate a student's final grade based on scores from labs, homework assignments, midterms, and the final exam. The program includes functions to drop the lowest scores and compute weighted averages.

## Features
- Accepts lab, homework, midterm, and final exam scores as input.
- Implements a function to drop the lowest scores before averaging.
- Computes a final grade based on weighted components.
- Provides an easy-to-use interface for testing different grading scenarios.

## Installation
To run this project, ensure you have **Python 3.x** installed on your system.

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/grade-calculator.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd grade-calculator
   ```
3. **Run the script:**
   ```bash
   python CalculateGrade.py
   ```

## Usage
1. The program contains two primary functions:
   - `drop_and_average(scores, n)`: Drops the lowest `n` scores and computes the average of the remaining scores.
   - `calculate_grade(labs, hws, mts, fin_exam)`: Computes the final grade based on weighted scores.
2. Users can modify the lists of scores in the `main()` function to test different inputs.
3. Running the script prints the computed course grade.

## Example Output
```
Course grade is: 85.6
```

## License
This project is licensed under the **MIT License**.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-new-feature`).
3. Commit and push your changes.
4. Open a pull request.

## Contact
For any questions or support, please open an issue on GitHub.

