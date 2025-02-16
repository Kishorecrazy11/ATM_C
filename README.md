Project Title: ATM System Simulation in C

Objective:
The objective of this project is to design and implement a simulated ATM system using the C programming language. The system will allow users to perform various banking transactions such as checking balances, 
withdrawing cash, depositing money, transferring funds, and updating account information. The system will focus on user authentication, data validation, and ensuring basic security measures like PIN verification.


Features of the ATM System:
User Authentication:

The system will prompt the user to enter their ATM card number and PIN.
The system will verify the ATM card number and PIN against stored credentials (hardcoded or from a file).
If the login fails, the user will be prompted to re-enter credentials or exit after a certain number of failed attempts.

Account Balance Inquiry:

After successful authentication, users can check their account balance.
The system will display the current balance of the user's account.

Cash Withdrawal:

Users can withdraw money from their account, given that their account has sufficient balance.
The system will provide multiple denominations (e.g., $20, $50, $100) and calculate the total amount requested.
It will check if the ATM has sufficient cash and if the user’s balance is adequate.

Cash Deposit:

Users can deposit cash into their account.
The system will update the user's balance immediately based on the deposited amount.

