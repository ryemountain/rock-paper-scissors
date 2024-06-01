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
//Create a while loop that runs while correctInput is not true
//Inside the loop, create a variable called humanInput to store human input and initialize it using a prompt
//Inside the loop, evaluate if humanInput corresponds to "Rock", "Paper" or "Scissors". If it does, set correctInput to TRUE and set humanChoice to the value of humanInput. 
//Outside the loop, return the value of humanChoice
//Output the value in the console to test the function

3. Your game will keep track of the players score. You will write variables to keep track of the players score.

PLAN 
//initialize 2 variables, one for humanScore and one for computerScore, in the global scope. 

Step 4: Write the logic to play a single round

4.1 Implement a function to play a single round 

- Create a new function named playRound.
- Write the code for your playRound function to console.log a string value representing the round winner, such as: “You lose! Paper beats Rock”.
- Increment the humanScore or computerScore variable based on the round winner.
- Add two variables to store computer choice and human choice, using the functions for retrieving these values. 
- Add a call to the playRound function with the choice variables. 

//Create a function to play a single round, which takes the human choice and computer choice as arguments
//Create a conditional statement which states that
- if computer choice === human choice, do not increment any score. 
- if computerChoice > human choice, increment computer score.
- otherwise, increment human score.

For all three outcomes above, log the result.  

4.2 Make your function’s humanChoice parameter case-insensitive so that players can input “rock”, “ROCK”, “RocK”, or other variations.

Step 6: 
Write the logic to play the entire game
Your game will play 5 rounds. You will write a function named playGame that calls playRound to play 5 rounds, keeps track of the scores and declares a winner at the end.

