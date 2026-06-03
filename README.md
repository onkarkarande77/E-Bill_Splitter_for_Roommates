# Roommate Expense Management System

## Overview

Roommate Expense Management System is a Java-based desktop application developed to manage and split shared expenses among roommates. The application helps track expenses such as rent, groceries, electricity bills, internet charges, and other household costs while automatically calculating each member's share and outstanding dues.

## Features

* Add and manage roommate profiles
* Record shared expenses
* Automatically split expenses among selected members
* Calculate individual balances and dues
* Track settlements between roommates
* View expense history and member details
* Real-time data storage and retrieval using MySQL

## Tech Stack

* Java (Core Java)
* Java Swing
* JDBC
* MySQL

## Project Structure

```text
src/
├── config/
├── model/
├── ui/
└── main/
```

## Database Tables

* Members
* Expenses
* Shares
* Settlements

The database is normalized to ensure efficient data storage and accurate calculations using SQL joins.

## How It Works

1. Register roommates in the system.
2. Add shared expenses with details such as amount and payer.
3. Select the members involved in the expense.
4. The application calculates each member's share automatically.
5. View balances, dues, and settlement information.
6. All data is stored and retrieved from MySQL using JDBC.

## Example

**Expense Amount:** ₹1200

**Number of Members:** 4

**Paid By:** Roommate 1

**Per Person Share:** ₹300

Settlement:

* Roommate 2 owes ₹300 to Roommate 1
* Roommate 3 owes ₹300 to Roommate 1
* Roommate 4 owes ₹300 to Roommate 1

## Installation

### Prerequisites

* Java JDK 8 or above
* MySQL Server
* Eclipse IDE (Optional)

### Setup

1. Clone the repository:

```bash
git clone https://github.com/onkarkarande77/Roommate-Expense-Management-System.git
```

2. Create the MySQL database and required tables.

3. Update database credentials in the JDBC configuration file.

4. Import the project into Eclipse.

5. Run the `Main.java` file.

## Learning Outcomes

* Object-Oriented Programming in Java
* GUI Development using Swing
* Database Connectivity using JDBC
* SQL Query Optimization and Joins
* Expense Sharing and Settlement Logic

## Author

**Onkar Karande**
