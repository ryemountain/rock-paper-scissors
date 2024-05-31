Problem: create an implementation of Rock Paper Scissors in JavaScript, 
where the game is played entirely in the console. There is no need for a GUI.
Each game should last 5 rounds.

Subproblems:
1. Create a new function named getComputerChoice.
Write the code so that getComputerChoice will 
randomly return one of the following string values: “rock”, “paper” or “scissors”.

PLAN:
//Define a function getComputerChoice, with no input
//Create a variable, computerChoice, to store the computer choice
//Create and initialize a variable, randomNumber, with a random number between 0 and 1.
//Create a conditional statement which sets computerChoice to either "rock", "paper" or "scissors" depending on the value of randomNumber.  
//Return computerChoice
//Run the function and output the value to the console to test it before writing the rest of the game. 

2. Create a new function named getHumanChoice.
Write the code so that getHumanChoice will return one of the valid choices depending on what the user inputs.

PLAN:
//Define a function getHumanChoice, no input
//Create a variable called humanChoice to store human choice
//Create a variable called correctInput to control a while loop
//Create a while loop that runs until correctInput is not true
//Inside the loop, create a variable called humanInput to store human input and initialize it using a prompt
//Inside the loop, evaluate the 