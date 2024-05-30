# BANKING_PROJECT
C++ Deep Dive
1. Account Management Module (Person A) What You’ll Do:
• Create and manage individual accounts.
• Write code that allows for deposits and withdrawals from accounts.
• Ensure each account has a unique number and manages its balance properly. Imagine you're responsible for keeping track of a list of customers at a bank. You need to make sure each customer has a unique account number, their name is recorded correctly, and their money balance is updated whenever they add or remove money. Responsibilities:
• Create the structure of an account with details like the account number, first name, last name, and balance.
• Make sure money can be added to (deposit) or taken out of (withdraw) the account.
• Handle situations where someone tries to withdraw more money than they have. Key Tasks:
• Define how an account is created with details like name and starting balance.
• Write methods to add money to the account.
• Write methods to withdraw money from the account.
• Ensure each new account gets a unique account number. 2. Bank Operations Module (Person B) What You’ll Do:
• Handle the overall operations of the bank, such as opening new accounts and keeping track of all accounts.
• Write code that allows the bank to provide balance information, process deposits and withdrawals, and close accounts.
• Manage saving and loading account data from a file.
Think of yourself as the manager of the bank’s system. You will oversee all the accounts, make sure new accounts can be opened, and existing accounts can be managed. You also ensure all the data is saved so it’s not lost when the system is turned off. Responsibilities:
• Create a way to open new accounts and store them in a list.
• Implement features to check account balances, add or withdraw money, and close accounts.
• Write methods to save all account information to a file and load it back when needed. Key Tasks:
• Define how new accounts are opened and stored.
• Write methods to check balances, deposit, and withdraw money for any account.
• Implement functionality to close accounts and remove them from the list.
• Ensure all account data is saved to a file and can be reloaded. 3. Main Interface and Integration Module (Person C) What You’ll Do:
• Create the main program that users interact with.
• Provide options for users to open accounts, make deposits, withdraw money, check balances, close accounts, and see all accounts.
• Integrate the account and bank operations so everything works smoothly. Imagine you are designing the bank’s ATM or online banking interface. You need to provide a simple menu that allows users to perform various actions like opening an account, checking their balance, depositing money, or closing an account. Responsibilities:
• Design a user-friendly menu that lets users choose different banking operations.
• Handle user input and connect it with the correct operations in the bank system.
• Ensure the whole system runs smoothly and user actions are processed correctly.
Key Tasks:
• Create a main menu with options like open account, deposit money, withdraw money, check balance, close account, and show all accounts.
• Write code to handle user choices and call the appropriate methods from the bank operations.
• Ensure proper flow of the program and handle any errors that might occur. Summary:
• Person A: Manages the creation and functionality of individual bank accounts.
• Person B: Oversees bank operations, including account management and data saving/loading.
• Person C: Develops the user interface and integrates account and bank operations. By dividing the tasks this way, each person has a balanced amount of work and can focus on a specific aspect of the banking system, ensuring smooth collaboration and project development.
