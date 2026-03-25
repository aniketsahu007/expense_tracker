# Smart Expense Tracker (CLI-Based AI Application)

## 1. Project Description

Smart Expense Tracker is a complete Command Line Interface (CLI) based application that allows users to manage daily expenses. The system uses Artificial Intelligence techniques such as classification and prediction to categorize expenses and forecast future spending.

---

## 2. Features

* Add expenses with description and amount
* Automatic category classification using AI logic
* View all stored expenses
* Predict future spending using linear regression
* Help command for user guidance
* Persistent storage using JSON files

---

## 3. Technologies Used

* Python 3.x
* NumPy (for prediction model)
* JSON (for data storage)

---

## 4. Project Structure

```id="str1"
ai-expense-tracker/
│── main.py
│── cli/menu.py
│── core/classifier.py
│── core/predictor.py
│── storage/filehandler.py
│── utils/validator.py
│── data/expense.json
│── requirements.txt
│── README.md
```

---

## 5. Installation and Setup

### Step 1: Install dependencies

```id="str2"
pip install -r requirements.txt
```

### Step 2: Run the application

```id="str3"
python main.py
```

---

## 6. Usage Instructions

The application runs in a terminal and provides the following menu:

```id="str4"
1. Add Expense
2. View Expenses
3. Predict Spending
4. Help
5. Exit
```

---

## 7. Example Execution

```id="str5"
Enter choice: 1
Enter amount: 500
Enter description: food at hotel
Added! Category: Food
```

---

## 8. Data Storage

* All expenses are stored in `data/expense.json`
* Data persists across multiple runs

---

## 9. Error Handling

* Invalid input handling
* Negative value validation
* Empty dataset handling

---

## 10. How It Works

1. User inputs expense details
2. System classifies category using keyword-based AI
3. Data is stored in JSON file
4. Linear regression predicts future expense

---

## 11. Future Enhancements

* Advanced machine learning models
* Graphical visualization
* Multi-user support

---

## 12. Author

Aniket Sahu
25BAI11514

---

## 13. License

This project is developed for academic purposes.
