This program is a student performance and comment generator.
It loads student data from a CSV file, analyzes grades and learning skills, generates personalized comments, and provides statistical insights (mean, median, quartiles).

It supports:

Loading students from a CSV (Learning Skills.csv)

Displaying student profiles with automatically generated comments

Adding new students interactively

Sorting students by name (Bubble Sort)

Searching students (Linear Search & Binary Search)

Calculating grade statistics (mean, median, Q1, Q3)

📂 Project Structure

Skill classes: Represent learning skills (Responsibility, Organization, etc.).

Student class: Stores student details, pronouns, grades, and generates comments.

Helper functions:

_calculate_median: Finds the median of a dataset

display_grade_statistics: Shows grade stats across all students

linear_search_student_by_name / binary_search_student_by_name: Search functionality

bubble_sort_students_by_name: Alphabetically sorts students

⚙️ Requirements

Python 3.8+

Libraries:

pip install pandas


A CSV file named Learning Skills.csv with the following columns:

Name:, Responsibility, Organization, Self-Regulation, Initative, Independent Work, Collaboration, Pronouns:, Grade:

▶️ How to Run

Place Learning Skills.csv in the project directory.

Run the script:

python main.py


Follow the prompts to:

Enter proficiency units (topics the student excels in)

Add weaknesses or extra comments

Add new students interactively

📊 Features

Comment Generator

Uses grade + learning skill levels (E, G, S, N) to generate natural-language comments.

Adds notes on student strengths, weaknesses, and extra teacher input.

Statistics Module

Calculates mean, median, Q1, and Q3 across student grades.

Student Search

Linear search (case-insensitive).

Binary search (after sorting).

Sorting

Bubble sort used to alphabetize student records.

📝 Example Usage

Sample CSV row:

Name:,Responsibility,Organization,Self-Regulation,Initative,Independent Work,Collaboration,Pronouns:,Grade:
Alice,E,G,S,G,E,N,she,85


Program Output:

--- Student Information ---
Student Name: Alice
Grade: 85
Pronouns: she
Responsibility: E
Organization: G
Self-Regulation: S
Initiative: G
Independent Work: E
Collaboration: N

Generated Comments:
She is doing amazing on: Algebra. This student has a thorough understanding of the subject. She completed all homework and submitted on time. She most of the time, their folder is neat and tidy and organized. She sometimes checks their progress and occasionally asks for help when needed. She actively asks questions about homework problems to understand better.
------------------------------------------

🚀 Future Improvements

Save generated comments back into a CSV or PDF.

GUI interface for easier input.

Add more natural-language variety to comment generator.
