This is a simple banking system project, made with python and OOP. (inspired by a online course about python on Udemy, it has the same idea and some similarities, but my version of implementation)

It consists of two classes - bank and client. 

Initially, an instance of the bank class is created, which has a name and a database, represented by a list of dictionaries.

After that, the user is given the options to create a new bank account, to open an existing one or to exit the program.

If the user chooses ot create an account, the user is prompted for a name and an initial deposit and the input is passed to the init method of the Client class. 

The unique user account number is a 5 digit number, automatically generated by using random number between 10000 and 99999. The account number serves as a password for the user to log into his account and do operation with it. 

After the instantiation of the Client object, it is been added to the bank class database.

After creating the account, the user can choose to create another or to enter an existing one. 

If the user chooses the second option, the user is prompted to authenticate with the name and the account number. The two arguments are passed to the authentication method of the bank class and if such credentials exist in the bank database, a variable called current_client is created from the existing client database.

After that, the usercan do operations with his account: withdraw, deposit, check balance or exit to the main menu. 


# Simple-Banking-System
