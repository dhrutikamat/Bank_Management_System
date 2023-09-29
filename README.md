# Bank_Management_System
This is our second year engineering project for amplifying our Database Management System skills.
Our Bank Management System is a web-based application designed to help manage banking operations efficiently. It is developed using various technologies like PHP, MySQL database for data storage, JavaScript for client-side functionality, HTML and CSS for the user interface, Bootstrap for responsive design, and additional features like Modals and Ajax for a smoother user experience. The primary purpose of this system is to manage banking operations, and it is designed to be user-friendly and easy to navigate.
Let's break down the key components and roles within the system:
1. Admin: The admin is a user type with higher privileges. They have control over the entire system and can perform tasks such as managing user accounts, monitoring transactions, setting system parameters, and generating reports.
2.User Types:
i) User Type 1 (Cashier): Cashiers are responsible for day-to-day banking operations. They can perform tasks like processing customer transactions (deposits, withdrawals, transfers), updating account balances, and generating receipts.
ii) User Type 2 (Member): Members are typically bank customers. They use the system to access their accounts, check balances, view transaction history, and perform various self-service banking operations.

Example:
Let's say you're a member of this bank management system. Here's how you might interact with it:
1. Logging In: You visit the bank's website and log in with your credentials (username and password).
2. Dashboard: After logging in, you are taken to your dashboard. Here, you can see your account balance, recent transactions, and other account-related information.
3. Transaction: You decide to transfer some money to your friend. You select the "Transfer Funds" option, enter your friend's account details, the amount, and confirm the transaction.
4. Confirmation: A modal dialog might appear to confirm the transaction details. This uses Bootstrap's modal feature to provide a clear and user-friendly confirmation before proceeding.
5. Transaction Completion: Once you confirm the transfer, Ajax may be used to update your account balance and transaction history without refreshing the entire page, providing a seamless user experience.
6. Receipt: After the transfer, you receive a digital receipt on the screen, and the transaction details are updated in your transaction history.

Meanwhile, the admin (User Type 1) has the capability to oversee all these transactions, manage user accounts, and ensure the smooth functioning of the system.
Overall, our Bank Management System is a prototype and it aims to provide a user-friendly and efficient platform for both bank employees (cashiers) and customers (members) to carry out their banking activities securely and conveniently.
