🏦: __Bank_Management_System__   
This project is a simple yet effective implementation of a Bank Management System using C++. It allows users to perform various operations such as opening a new bank account, checking balance, depositing funds, withdrawing funds, closing accounts, and viewing all existing accounts.  

🔑:__Key Features__:  
__Account Management:__ Users can open a new account with a specified initial balance, check account balance, deposit funds, withdraw funds (with a minimum balance constraint), and close accounts.  
__Persistence:__ Account data is stored persistently in a file (Bank.data). This ensures that account information is preserved between program runs.  
__Exception Handling:__ The system incorporates exception handling with a custom InsufficientFunds exception, ensuring safe withdrawals when account balances are insufficient.  
__Object-Oriented Design:__ The code utilizes classes (Account and Bank) and object-oriented principles such as encapsulation and inheritance, demonstrating good software design practices.  
__File Handling:__ Input/output operations are handled using file streams (ofstream and ifstream) to read from and write to the data file.  

🖱️:__Usage:__  
__Open an Account:__ Users can create a new bank account by providing their first name, last name, and initial balance.  
__Check Balance:__ Account holders can check their current balance by entering their account number.  
__Deposit and Withdraw:__ Funds can be deposited or withdrawn from an existing account. Withdrawals are protected by a minimum balance requirement.  
__Close Account:__ Account holders can close their accounts, which deletes the account from the system.  
__Show All Accounts:__ Displays details of all existing accounts in the bank.  
