# simple_atm_stimulaton-
simple atm stimulation in python 

ATM Machine Simulation
Overview
This is a simple Python-based ATM machine simulation. It allows users to perform basic banking operations such as checking balance, withdrawing money, and depositing money. This script is designed to emulate the functionality of an ATM machine in a console-based environment.

Features
Check Balance: View the current balance in the account.
Withdraw Balance: Withdraw a specified amount from the account balance.
Deposit Balance: Deposit a specified amount into the account balance.
Exit: Exit the ATM simulation.
Prerequisites
Python 3.x
Usage
Insert Card: The simulation starts with a prompt to "insert your CARD".
Enter PIN: Enter the ATM pin to access the account. The default PIN is 1234.
Select Options: Choose from the available options to check balance, withdraw, deposit, or exit.
How to Run
Ensure you have Python 3.x installed on your machine.
Download or clone this repository.
Navigate to the directory containing the script.
Run the script using the following command:
bash
Copy code
python atm_machine_stimulation.py
Script Details
The script atm_machine_stimulation.py performs the following tasks:

Prompts the user to "insert" their card (simulated with a print statement and a delay).
Requests the user to enter their PIN.
Validates the PIN. If the PIN is correct, it allows access to the ATM functionalities.
Displays a menu with options to check balance, withdraw money, deposit money, or exit.
Performs the selected operation and updates the account balance accordingly.
Continuously displays the menu until the user decides to exit.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
This script is created for educational purposes to simulate basic ATM functionalities in a console environment.
