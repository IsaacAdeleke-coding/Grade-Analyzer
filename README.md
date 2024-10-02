# Grade Analyzer

## Overview
The **Grade Analyzer** is a simple console-based application designed to help teachers analyze student scores. It allows teachers to input student scores, calculate the class average, find the highest and lowest scores, and identify students who scored above average. The system also allows comparison of scores between students.

## Features
- **Input Student Scores**: Enter the names and scores of students manually.
- **Calculate Statistics**: 
  - Calculate and display the class average.
  - Display the highest and lowest scores.
- **Above Average Students**: List students who scored above the class average.
- **Compare Scores**: Compare scores between all students.
- **Menu-Driven Interface**: A simple interface to input data, display results, and exit the program.

## File Structure
- `GradeAnalysis.hpp` - Header file containing the class definition and method declarations.
- `GradeAnalysis.cpp` - Implementation file with method definitions for the `GradeAnalysis` class.
- `main.cpp` - The main program file, which provides the interface for interacting with the system.

## Installation & Usage

### Prerequisites
- A C++ compiler (e.g. Xcode)
  
### Compiling the Program
1. Clone or download the repository.
2. Open the terminal and navigate to the project folder.
3. Compile the program using the following command:
   ```bash
   g++ main.cpp GradeAnalysis.cpp -o grade_analyzer
