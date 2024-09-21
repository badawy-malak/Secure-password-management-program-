# Secure-password-management-program-
## Introduction
Nowadays the digitalization of the world has prompted us to have access to hundreds of websites and
applications, and given the human nature the possibility of forgetting the passwords chosen for each
platform is extremely high. Thus, a secure password manager was created, it’s a program that allows its
users to store their passwords, delete any unnecessary entered password, view all their entries, and
generate a random password so that the user doesn’t have to go through the hassle of creating a password
himself.
This was done through the implementation of several C++ programming concepts, algorithms, and data
structures. Some of which are; utilization of switch-case statements, implementation of linked lists, and
performance of several string manipulation techniques among other characteristics.
## User Guide & Instructions
The following steps take place once the program is run. Firstly, the user is greeted with a welcome note
then initiates the process of asking the user what type of logging to the program they will use, there are
only two options one for existing users, the other is for new users.
### New User
The second option would be if the user is new to program and thus his/her account will begin the creation
process. Once the user chooses the first option (create an account!), the program redirects the user to enter
his name, username for when accessing the application, ,and the password. Next the user is asked if he/she
wants to continue all the way to the logging in procedure or would they rather exit the program.
### Existing user
If the user has an existing account, then they will choose the second option dedicated for user login. After
that the user will enter the credentials of the program, if the username is incorrect or the user incorrectly
chose to login instead of signing up then a message will appear that states the user is not found and asks if
the user wants to re-try the login process, go the signup, or exit the program. However, if the entered
password is incorrect then the program displays a message “Invalid password!” then allowing the user
one of the options as when the username is incorrect.
In the case that the login credentials are valid, then the program welcome the user and displays a list of
operations that can be executed upon the user request.
### Operations Available
After any successful logging in attempt a list is then displayed to the user, this list holds all the operations
that the user can perform to their data.
### Password Addition, Deletion, and Updating
The first option presented is the addition of a new password to the list, upon choosing this operation the
user is then asked to enter the website name associated with the password, and after that the password
itself. To make sure that the password is added to the list a confirmation message id displayed as
reassurance.The second option is to delete any password from the list, when
the user chooses this option, he/she is prompted to enter the website name corresponding with the
password to be deleted. And finally, a confirmation of deletion message is also displayed.
Another additional choice for the user to select the update a current password, this done throughout
asking the user to input the name of the website that the equivalent password will be updates, then the
user is required to enter the old passwords, following that the new password, and lastly, a reassurance note
will be displayed after successful password alteration.
### Password Generation & List Viewing
Next comes the option to generate a random password for the user, this is done after the user chooses the
website which the generated password will be linked to. Another possibility that can be chosen is to view
the entire list of passwords for that user.
### Program exit
The last course of action that can be taken by the user is to exit the program via typing the it’s equivalent
number in the input field.
