**The "Game of Dice" is a game where two players roll 6 faced dice in a round-robin fashion. Each time a player rolls the dice their points increase by the number (1 to 6) achieved by the roll. The first player to accumulate M points wins the game.**
**Rules of the game**
* The order in which the users roll the dice is decided randomly at the start of the game.
* If a player rolls the value "6" then they immediately get another chance to roll again and move ahead in the game.
** Implementation Details**
* Implement a CLI which allows user to input M (points of accumulate) at the start of the game.
* Randomly assign the order in which players will roll the dice.
* When it's the turn for Player-X to roll the dice prompt a message like “Player-2 it is your turn (click ‘Roll’ button to roll the dice). For simplicity, we can assume that only the player having a current turn will click on the Button.
* Randomly simulate a dice roll, display the points, and add the points to the user’s score.
* If the user gets another chance because they rolled a ‘6’ then print an appropriate message to inform the user.
* If a user completes the game, print an appropriate message with results.
**Evaluation Criteria**
* Code correctness w.r.t. the specifications given above.
* Code quality in terms of readability, structure, and idiomatic correctness.
* The webpage could be very simple. No need to spend a lot of time on looks and style. The focus should be majorly on the proper functioning of the game.
**Submission Details**
* Please share a public Github repository with your solution and proper instructions on how to run the code in the README.md file OR you can share your code in a zip file along with a document with the instructions.