# Python - ATM Simulation Project using Google Colab


Simulating a user experience on an ATM using Python programming language:

1. Creating a card insert prompt for the user on whether card has been inserted, user input is taken via inetegr inputs and loops until 'yes' is prescribed.
2. PIN prompt, resticted to a length of 4 integer values. Error messages will appear if PIN is incorrect or does not meet the PIN length requisite. This will loop until a correct input has been applied.
3. Main Menu screen is followed swiftly after the PIN, displayng four options; display balance, withdraw funds, deposit funds, exit. Each option is assigned an integer value which the user is required to input, error messages will appear if an invalid input has been applied and loops until a valid input has been retrieved.
4. Display balance option shows a balance that will automatically update throughout the session (from withdrawals and deposits). Mini menu section follows on whether to go back to main menu or exit session.
5. Withdraw funds displays a number of options; £10, £20, £40, £60, £80, £100, other amount or exit. each option is assigned an integer value which the user is expected to input. Invalid inputs print error statements and prompt user again (loops until valid input applied).
6. Withdrawal options are calculated depending on available balance on simulation, if withdrawal option is more than balance an 'insufficient funds' will be displayed. If withdrawal request is less or equal to the balance, 'transaction successful' will appear and this withdrawal will be deducted from the balance.
7. Deposit funds option of main menu will prompt the user to input an integer more than 0, this will be added to the balance and a 'transaction successful' will be displayed.
8. Exit option will terminate the session and restart the session all over again. 
