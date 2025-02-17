# MathToPass

MathToPass is a Python script that helps students calculate the minimum score needed in their final exams to pass their courses. It uses object-oriented programming (OOP) principles to represent each course as a class with its unique grading structure.

## Features

- Calculates the score needed in the final exam for each course to achieve a passing grade (10/20).
- Includes support for the following courses:
  - **Cryptography**: Takes into account QCM1, QCM2, and CC scores.
  - **Algorithms**: Considers CC1 and CC2 scores.
  - **Automata**: Accounts for CC and QCM scores.
  - **PCOO**: Factors in CC and Project scores.

## How It Works

1. Each course is represented by a class (e.g., `Cryptographie`, `Algorithms`, `Automata`, `PCOO`).
2. Each class includes methods to calculate the weighted average of completed assessments and determine the required score for the final exam.
3. Input the scores and weights for each assessment in the course, and the script will output the minimum score required in the final exam to pass.

## Getting Started

### Prerequisites

- Python 3.x

### Running the Script

1. Clone this repository:
```bash
git clone https://github.com/TerminalGambit/MathToPass.git
```
2.	Navigate to the project directory:
cd MathToPass

3.	Run the main.py script:
python main.py

### Example Usage

The script will prompt you to input scores and weights for each course’s assessments. It will then calculate the minimum score required in the final exam for you to pass the course.

### Notes
	•	For courses where the project or certain grades are not yet available, you can input an estimated score and adjust it later if necessary.

### Contributions

Contributions are welcome! Feel free to submit a pull request or raise an issue for any improvements or additional features.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

Have fun calculating your way to success!
