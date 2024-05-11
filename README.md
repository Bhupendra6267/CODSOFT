# CODSOFT
This repository contains the TASKS provided by CODSOFT and which I have completed during my 4 weeks internship.
The tasks i have completed are for Java Development internship, so the code are written in Java

<h2>Task 1</h2>

<h3>Guessing Game</h3>
1. Generate a random number within a specified range, such as 1 to 100.<br>
2. Prompt the user to enter their guess for the generated number.<br>
3. Compare the user's guess with the generated number and provide feedback on whether the guess<br>
is correct, too high, or too low.<br>
4. Repeat steps 2 and 3 until the user guesses the correct number.<br>
5. Add the option for multiple rounds, allowing the user to play again.<br>
6. Display the user's score, which can be based on the number of attempts taken or rounds won.<br>

The windows are open for improvements, If you are using the code or found any better apporach. You are welcome here.

<h2>Task 2</h2> 

<h3>Grade Calculator</h3> 
Input: Take marks obtained (out of 100) in each subject. <br>
Calculate Total Marks: Sum up the marks obtained in all subjects.<br>
Calculate Average Percentage: Divide the total marks by the total number of subjects to get the
average percentage.<br>
Grade Calculation: Assign grades based on the average percentage achieved.<br>
Display Results: Show the total marks, average percentage, and the corresponding grade to the user<br>

<h4>Code Briefing</h4>
Purpose:<br>

This Java program calculates total marks, average percentage, and student grade based on input marks for subjects.<br>

Input Handling:<br>
* User enters the number of subjects and their marks.<br>
* Handles invalid inputs gracefully.<br>

Calculation:<br>
* Calculates total marks and average percentage.<br>
* Derives student grade based on the average percentage.<br>

Output:<br>
* Displays total marks, average percentage, and student grade.<br>

Usage:<br>
* Execute the program, follow prompts to input marks.<br>
* Obtain grade calculation as output.<br>

Termination:<br>
* Closes input scanner after data collection.<br>
* Exits with appropriate error messages on invalid input.<br>

Customization:<br>
* Program can be modified for additional features or input validation.<br>

<h2>Task 3</h2>

<h3>ATM Interface</h3>
Create a class to represent the ATM machine. <br>
Design the user interface for the ATM, including options such as withdrawing, depositing, and
checking the balance.<br>
Implement methods for each option, such as withdraw(amount), deposit(amount), and
checkBalance().<br>
Create a class to represent the user's bank account, which stores the account balance.<br>
Connect the ATM class with the user's bank account class to access and modify the account
balance.<br>
Validate user input to ensure it is within acceptable limits (e.g., sufficient balance for withdrawals).<br>
Display appropriate messages to the user based on their chosen options and the success or failure
of their transactions.<br>

<h4>Code Briefing</h4>

BankAccount Class: <br> 
* Represents a bank account with attributes for the balance.<br> 
* Contains methods for showing the balance, depositing money, and withdrawing money.<br> 

ATMmac Class (Extends JFrame):<br> 
* Represents an ATM machine GUI.<br> 
* Contains text fields and buttons for depositing, withdrawing, and viewing balance.<br> 
* Implements ActionListener for button actions.<br> 

Constructor:<br> 
* Sets up the GUI window with appropriate size, title, and layout.<br> 
* Creates panels for input, buttons, and output.<br> 

Input Panel:<br> 
* Contains a label for entering the amount and a text field.<br> 

Button Panel:<br> 
* Contains buttons for deposit, withdraw, and view balance.<br> 
* Each button has an ActionListener attached to perform actions on button click.<br> 

Action Listeners:<br> 
* Deposit: Parses the input amount and deposits it into the account.<br> 
* Withdraw: Parses the input amount and withdraws it from the account if sufficient balance is available.<br> 

View Balance: Displays the current balance.<br> 

Output Panel:<br> 
* Displays messages such as deposit success, withdrawal success, or balance.<br> 
* Uses a JTextArea within a JScrollPane for displaying messages.<br> 

showMessage Method:<br> 
* Updates the text area with the provided message.<br> 

Main Method:<br> 
* Creates an instance of the BankAccount class with an initial balance of $5000.<br> 
* Creates an instance of the ATMmac class, passing the BankAccount object to it.<br> 
* Displays the ATM machine GUI.<br> 
