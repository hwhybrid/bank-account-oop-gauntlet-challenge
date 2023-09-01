# bank-account-oop-gauntlet-challenge
Java fundamentals object oriented programming challenge.

BankAccount Gauntlet Challenge 
🗒️ OOP Challenge


For the first part of this gauntlet challenge, we are going to create a BankAccount class. This class will recreate some of the common account transactions that normally occur for a bank account such as displaying your account number, checking and savings amount, and total amount. Of course, there are also methods to invoke, such as depositing a check, checking your balance, and withdrawing money.

Objectives:
- Practice member variables
- Practice instance methods and getter and setters
- Implement static variables and methods.

Tasks:
- Create a BankAccount class.

- The class should have the following attributes: (double) checking balance, (double) savings balance.

- Create a class member (static) that has the number of accounts created thus far.

- Create a class member (static) that tracks the total amount of money stored in every account created.

- In the constructor, be sure to increment the account count.

- Create a getter method for the user's checking account balance.

- Create a getter method for the user's savings account balance.

- Create a method that will allow a user to deposit money into either the checking or savings, be sure to add to the total amount stored.

- Create a method to withdraw money from one balance. Do not allow them to withdraw money if there are insufficient funds.

- Create a method to see the total money from the checking and savings.

- Users should not be able to set any of the attributes from the class.

The next challenge in this gauntlet is to create a random 10-digit account number.
- Add the the following class attribute: account number. The type is up to you, can be a String, a Long, or another type.
- Create a private method that returns a random ten-digit account number.
- In the constructor, call the private method from above so that each user has a random ten-digit account.
