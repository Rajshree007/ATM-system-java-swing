# ATM-system-java-swing
🏧 ATM Management System (Java GUI + JDBC)
This is a Java-based desktop application simulating an ATM management system. It includes functionalities such as account creation, deposit, withdrawal, and balance checking. The application uses Swing for the GUI and connects to a MySQL database using JDBC.

✨ Features
🔐 Open a new account with user details

💰 Deposit money to an account

💸 Withdraw money from an account

🧾 Check account balance

💾 Connected to MySQL using JDBC

🖼️ User-friendly GUI with Swing components

📂 Project Structure
csharp
Copy
Edit
ATM_System/
│
├── Balance.java
├── Deposite.java
├── Withdraw.java
├── Openaccount.java
├── MyBank.java                 # Main file
├── *.class                     # Compiled class files
├── mysql-connector-j-8.1.0.jar  # JDBC connector
├── ATM_GUI.rar                # GUI assets
├── jdbc.docx                  # Documentation
├── HOW_TO_RUN.txt            # Instructions to run
├── Screenshot (###).png      # UI screenshots
├── Depositepack/
├── Withdrawpack/
├── Openaccountpack/
└── Checkbalancepack/
🛠️ Technologies Used
Java (Swing for GUI)

MySQL (Database)

JDBC (Database connectivity)

🖥️ Setup Instructions
Install MySQL and create a database and required tables.

Update your MySQL credentials in the Java files (inside MyBank.java or relevant files).

Compile the Java files:

bash
Copy
Edit
javac -cp ".;mysql-connector-j-8.1.0.jar" *.java
Run the main class:

bash
Copy
Edit
java -cp ".;mysql-connector-j-8.1.0.jar" MyBank
📸 Screenshots
See the included PNG files for screenshots of the application interface.

📌 Note
Ensure the MySQL JDBC driver .jar file is in the classpath during compilation and execution. The application expects a working local MySQL server with appropriate schema setup.

📄 License
This project is for educational purposes. Feel free to use and modify it.

