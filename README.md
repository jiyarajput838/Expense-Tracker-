# Expense-Tracker-

## 1. Overview

The Expense Tracker helps users manage their daily spending through a menu-driven console interface.Users can enter an expense description, category, and amount. 

The application stores the records temporarily using an ArrayList and provides options to view expenses, calculate the total amount, search by category, and delete records.

This project is designed for beginners and demonstrates basic Java programming, object-oriented programming, collection handling, input validation, and exception handling.

## 2. Features

- Add expenses.
- View all expenses.
- Calculate total spending.
- Search by category.
- Delete expenses.
- Validate user input.

## 3. Technologies and Tools Used

- Java.
- `ArrayList`.
- `Scanner`.
- Object-oriented programming.
- VS Code, IntelliJ IDEA, Eclipse, or NetBeans.

## 4. Installation and Running

### 4.1 Prerequisites

Install JDK 8 or higher.

Check installation:

```bash
java -version
javac -version
```

### 4.2 Install Libraries

No external libraries are required. The project uses built-in Java classes.

### 4.3 Save the Project File

Save the source code as:

```text
ExpenseTracker.java
```

The filename must match:

```java
public class ExpenseTracker
```

### 4.4 Run the Program

Open the terminal in the project folder and execute:

```bash
javac ExpenseTracker.java
java ExpenseTracker
```

## 5. Testing Instructions

Test the following operations:

| Test | Expected result |
|---------------------------|--------------------------------|
| Add valid expense         | Expense is added               |
| View expenses             | All records are displayed      |
| Calculate total           | Correct total is shown         |
| Search category           | Matching expenses are displayed|
| Delete expense            | Selected expense is removed    |
| Enter empty data          | Error message appears          |
| Enter negative amount     | Amount is rejected             |
| Enter invalid menu option | Invalid choice message appears |
| Select Exit               | Program closes normally        |
