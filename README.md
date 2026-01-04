⚡ Electricity Board Management System (Java)
A console-based Java application that simulates an Electricity Board Management System.
It allows Admin users to generate electricity bills and Customers to view, calculate penalties, and pay their bills using different payment modes.

📌 Features
👨‍💼 Admin Module
Generate electricity bill for a customer
Input customer details and meter readings
Automatic unit calculation
Slab-based billing system
Assign due date
Display generated bill details

👤 Customer Module
View bill details
Check overdue status
Automatic penalty calculation (5% for overdue bills)
Pay bill using:
Cash
Card
Online payment
Generate payment receipt

🧮 Billing Slab Rates
Units Consumed	Rate per Unit
0 – 100	₹1.5
101 – 200	₹2.0
201 – 300	₹3.0
Above 300	₹4.0

🛠️ Technologies Used
Java
Java Scanner Class
Object-Oriented Programming (Basic)
Console-based Input/Output

▶️ How to Run the Project
Prerequisites
Java JDK installed (Java 8 or above)
Any IDE (IntelliJ, Eclipse, VS Code) or Command Line

Steps
Clone the repository:
git clone https://github.com/your-username/Electricity-Bill-Management-System.git

Navigate to the project folder:
cd Electricity-Bill-Management-System

Compile the program:
javac ElectricityBill.java

Run the program:
java ElectricityBill

🧪 Sample Flow
Choose mode:
1 → Admin
2 → Customer
Admin generates bill using meter readings
Customer views bill, checks overdue status
Customer pays bill using preferred payment method

🚀 Future Enhancements
Database integration (MySQL)
User authentication (Admin & Customer login)
GUI using JavaFX or Swing
Real-time bill storage and retrieval
Online payment gateway simulation

📂 Project Structure
ElectricityBill.java
README.md
