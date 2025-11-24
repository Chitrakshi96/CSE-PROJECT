Expense Manager
A simple, modular Command Line Interface (CLI) application for managing personal expenses, featuring category-based tracking, data persistence, and spending analytics.
Project Overview The Expense Manager is a  financial tool build using python designed to help users monitor their daily spending.
Not like calculators, this application utilizes  classes for data management and business logic, making the code maintainable and extensible. It supports multiple sessions on a single machine by saving data to a local file, ensuring expense history is preserved.
Key Features Category-Based Tracking: Expenses are organized into 7 predefined categories (Food, Transportation, Entertainment, Utilities, Rent, Healthcare, Miscellaneous), stored in a dictionary for easy updates.
•	Data Persistence: All expenses are automatically saved to a local expenses json file. Data remains available even after restarting the application.
   •	Comprehensive Expense 
        •	Create: Add expenses with amounts and categories.
        •	Read: View a formatted dashboard of your expenses by category.
        •	Update: Modify existing expenses (e.g., adjust amounts).
        •	Delete: Remove unwanted expenses permanently.
    •	Spending Analytics: A built-in engine calculates total spending and provides category-wise breakdowns to analyze financial habits.
        •	Data Isolation: The system manages expenses per session, with options for future user-based isolation.
Technologies Used
•	Language: Python 3.6+
•	Core Libraries:
•	json: For database serialization/deserialization.
•	os: For file system integrity checks.
•	datetime: For timestamps (if extended).
Installation and Execution
Prerequisites
•	Python 3.x installed on your system.
Setup Steps
1.	Clone the Repository (or download the source files): bash git clone https://github.com/your-username/expense-manager.git cd expense-manager
2.	Verify File Structure: Ensure expense_manager.py (or your main script name) is present.
3.	Run the Application: bash python expense_manager.py
4.	First Run: The application will automatically initialize and create an expenses .json file in the root directory to serve as the database.
Instructions for Testing Since this is a CLI application, you can verify functionality by following this manual test script:
1. Expense Addition (Basic Test)
•	Action: Select Option 1 and add an expense (e.g., $50 to Food).
•	Expected Result: Success message and updated total.
•	Verification: Open expenses .json and verify the expense is stored with category and amount.
2. View Expenses & Totals (Display Test)
•	Action: Select Option 2 to view expenses.
•	Expected Result: A table showing categories and totals.
3. Analytics (Logic Test)
•	Action: Add multiple expenses and select Option 3 for analytics.
•	Expected Result: Displays total spending and category breakdowns (e.g., if 50 in Food, shows percentages).
4. Update/Delete (CRUD Test)
•	Action: Update an expense (Option 4) or delete one (Option 5).
•	Expected Result: Changes reflect in the data and views.
License This project is open-source and available for educational purposes.
In summary, this tool makes tracking expenses fun and effective, helping users stay on top of their money without needing complex software.
<img width="1334" height="493" alt="Screenshot 2025-11-24 231224" src="https://github.com/user-attachments/assets/d6ab2e27-ad61-4953-94be-8f3239dcf36b" />
<img width="1796" height="913" alt="Screenshot 2025-11-24 231112" src="https://github.com/user-attachments/assets/efad8d33-5d28-4c6a-874d-25912d421a21" />
<img width="1796" height="983" alt="Screenshot 2025-11-24 231052" src="https://github.com/user-attachments/assets/726ee6ef-603d-48e7-811a-a4bf8860fdc7" />
<img width="1349" height="994" alt="Screenshot 2025-11-24 231023" src="https://github.com/user-attachments/assets/bff3f7fd-bba0-4e74-9a68-814293e31d13" />

