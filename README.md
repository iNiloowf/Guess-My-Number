# Guess-My-Number
This is a JavaScript code that simulates a guessing game. In this game, the player is required to guess a secret number between 1 and 20.

The code uses strict mode and sets up three variables:

secretNumber: A random integer between 1 and 20.
score: The current score, which starts at 20 and decreases by 1 with each incorrect guess.
highscore: The highest score achieved by the player.
The code also defines a function called displayMessage that updates the message displayed on the web page.

The code then sets up two event listeners:

When the "check" button is clicked, the code checks if the player's guess is correct. If the guess is correct, the code updates the message, the background color of the web page, and the width and text content of the number displayed. If the player's score is higher than the previous high score, the high score is updated. If the guess is incorrect, the code updates the message and the player's score.
When the "again" button is clicked, the code resets the score, generates a new secret number, updates the message and text content on the web page, and resets the background color and width of the number displayed.
Overall, this code provides a simple and fun guessing game that can be played in a web browser.
