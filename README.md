# ATM-console-based-
Sample ATM Operations
# ATM Operations Console Application 🏧💳

## Overview 🌟

This is a **console-based ATM system** built with Python 🐍. It simulates basic ATM operations such as depositing money, withdrawing funds, generating a PIN, and checking mini statements. User details (including account balance and PIN) are stored using Python dictionaries 🗃️, and operations are controlled through **conditional statements** and **loops**.

---

## Features 🎉

- **Login** 🔐: Authenticate users via PIN.
- **Deposit** 💰: Deposit money into the account balance.
- **Withdraw** 💵: Withdraw funds, ensuring sufficient balance.
- **Mini Statement** 📃: View recent transactions.
- **PIN Generation** 🔄: Create or generate a new PIN upon account creation.
- 
- # ATM Operations Console Application 🏧💳
## Overview 🌟

This is a **console-based ATM system** built using Python 🐍. The ATM system allows users to perform the following operations:
- Deposit money into their account 💰
- Withdraw money 💵
- Check mini statements (view recent transactions) 📃
- Generate and validate a PIN 🔐

The project utilizes Python's **conditional statements** and **dictionary data type** to store and manage user data, including the account balance, PIN, and transaction history.

## Features 🎉

1. **User Authentication** 🔑:
    - Users must log in using their username and PIN for secure access.
    
2. **Deposit** 💰:
    - Users can deposit money into their account.
    - The system will update the user's balance and log the transaction.

3. **Withdraw** 💵:
    - Users can withdraw money from their account.
    - The system checks if the user has sufficient balance before allowing the transaction.

4. **Mini Statement** 📃:
    - Users can view a list of their recent transactions, such as deposits and withdrawals.

5. **PIN Generation** 🔄:
    - New users can create a PIN for their account.
    - Users can perform operations after successfully entering the correct PIN.

## Technologies Used ⚙️

- **Python**: The programming language used to implement the ATM system.
- **Dictionary Data Type** 🗃️: Used to store user details (balance, PIN, and transaction history).
- **Conditional Statements** 🧩: Utilized for decision-making during operations (deposit, withdrawal, PIN verification).
- **Console Interface** 🎮: Provides the user with a simple text-based interface for interaction.

## How to Run 🚀

### Steps to Run:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-/atm-operations.git
Welcome to the ATM System! 🏧
----------------------------------------
Please enter your PIN to continue:
1234

Main Menu:
1. Deposit 💰
2. Withdraw 💵
3. Mini Statement 📃
4. Exit 🚪
----------------------------------------
Select an option: 1

Enter deposit amount: 500
Deposit successful! Your new balance is: 500 💵

Main Menu:
1. Deposit 💰
2. Withdraw 💵
3. Mini Statement 📃
4. Exit 🚪
----------------------------------------
Select an option: 3

Your recent transactions:
1. Deposited: 500 💰
