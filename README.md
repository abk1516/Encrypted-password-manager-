# Encrypted-password-manager-
Self project
Password-Manager

Instructions to run the code:

Make sure the system requirements are satisfied as mentioned in the Doc
Open up MySQL workbench and run the SQL file attached in the parent directory, or you can also run it via the MySQL command line if you know how to use MySQL dump
The database should be loaded. Try opening up the database and check that 2 tables are present.
Navigate to the code directory (the one where this file is present)
Go to Files > and open the metadata.txt file
Make sure the username: has a space after the colon symbol and then enter th username of the MySQL server on your machine Similarly, make sure the password: has a space after the colon symblo and then enter the password of the MySQL server on your machine.
Now we are ready to run the program_

Open your command line and navigate to the directory you see PasswordAuthenticator.jar file in
write the command "java -jar PasswordAuthenticator.jar" (without the quotes)
A file explorer should open up.
Inside the file explorer, navigate to the metadata.txt file that you just created and click on Open
Now we are in the main application.
BASIC FEATURES______

In the Welcome page, press EXIT to exit the application
Enter your details such as username: akshaj, password: gupta, etc. You can check all combinations in the users table of the database.
Then click on Login another menu should open up. The Logout and Exit buttons are self explanatory.
The View stored passwords will show you all the passwords that you have stored (i.e. pertaining to the details entered in step 2)
Click on any row and select copy to clipboard in order to copy the decrypted password into the clipboard.
Click on any row and select delete in order to delete that password
Click on add a new password in order to open up a different page, where you can enter all the required details. The asterisk fields are necessary.
From here you can click on View Existing Passwords, and the new password should be visible.
Clicking on Go Back will take us back to the option selection.
From here, you can directly go to adding new passwords by using the Store more passwords button.
ADVANCED FEATUES_______

In the login page enter admin for username and admin for password (i.e. in both the text fields)
