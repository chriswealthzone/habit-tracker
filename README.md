Habit Tracker Application
Overview
The Habit Tracker is a Python-based command-line application that enables users to create, manage, and analyze their daily and weekly habits. The app demonstrates advanced Object-Oriented Programming (OOP) and Functional Programming (FP) paradigms, focusing on modularity, maintainability, and robust data persistence.
Features
•	User registration and secure login (password hashing with salt)
•	Creation and tracking of daily or weekly habits
•	Mark habits as completed with a timestamp and optional notes
•	Analytics dashboard: current and longest streaks, inactive habits, and progress statistics
•	Data persistence using SQLite
•	Automated testing with Pytest
•	Modular, well-documented codebase

Technology Stack
•	Python 3.7+
•	SQLite (built-in via sqlite3)
•	Pytest for testing
•	CLI (standard input/output)
•	Developed with PyCharm
Installation
Clone the repository:
git clone https://github.com/chriswealthzone/My_Habit_Tracker_App.git  
cd My_Habit_Tracker_App/habit_tracker  

(Optional) Create and activate a virtual environment:
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate  

Install dependencies (if needed):
pip install -r requirements.txt  

Usage
Run the application:
python cli.py  
Register or log in, then use the menu to manage your habits and view analytics.

Project Structure
My_Habit_Tracker_App/  
├── habit_tracker/  
│   ├── cli.py  
│   ├── storage.py  
│   ├── models.py  
│   └── ...  
├── tests/  
│   └── test_habit.py  
├── README.md  
└── requirements.txt  

Documentation
All modules and functions include Python docstrings.
See code comments for usage guidance.
Full details of the system design, architecture, and features are described in the abstract PDF.

CLI Output
====================================  
        HABIT TRACKER MAIN MENU        
====================================  
1. View All Habits  
2. Create New Habit  
3. Complete a Habit  
4. Analytics Dashboard  
5. Exit  
====================================  
Select an option (1-5):  

GitHub Repository
Project link: https://github.com/chriswealthzone/My_Habit_Tracker_App

Author
Christian Ebenezer
Mat Number: 102401240
Course Code: DLBDSOOFPP01
Tutor: Mirmehdi Seyedebrahimi
