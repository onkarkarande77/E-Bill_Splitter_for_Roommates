# E-Bill Splitter_for_Roommates

## Description
E-Bill Splitter is a Java desktop application that helps manage and split expenses among multiple members. It calculates each person's share and determines who owes whom, with real-time updates from the database.

## Features
- Add and manage members  
- View members in a table (auto-updated)  
- Record expenses  
- Split amount equally among members  
- Calculate "who owes whom"  
- View recent expenses dynamically  
- Real-time database integration  

## Tech Stack
- Java (Core Java)
- Swing (GUI)
- JDBC
- MySQL

## How It Works
- Add members → displayed instantly in table  
- Enter expense details (amount, paid by, members)  
- System calculates per-person share  
- Displays who owes how much to whom  
- Data is stored and fetched from MySQL  

## Example
Amount = 1200  
Members = 4  
Paid By = Member 1  

Each person pays = 300  

Member 2 owes 300 to Member 1  
Member 3 owes 300 to Member 1  
Member 4 owes 300 to Member 1  

## Author
Onkar Karande
