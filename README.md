# Quiz-game-in-Python
This is a simple quiz game in Python that consists of True or False questions. The code counts the score of the player and displays it at the end.

This code represents a simple quiz game. Here's how it works:

- The game starts with a welcoming message displayed to the player.
- The player is asked if they want to play by entering their response. If the response is anything other than "yes" (case-insensitive), the game ends.
- If the player chooses to play, the game begins, and the score counter (pt) is initialized to 0.
- Six true or false questions are asked one by one. The player inputs their answer for each question.
- For each correct answer, the message "Correctomundo!" is displayed, and the score counter is incremented by 1. Otherwise, the message "Incorrect." is shown.
- After all the questions are answered, the player's final score is displayed.

Here's a list of Python concepts used in the code:

- **Input/Output:** The input() function is used to prompt the player for their responses, and the print() function is used to display messages and the final score.

- **Conditional Statements:** The if and else statements are used to check the player's responses and determine if they are correct or incorrect.

- **String Manipulation:** The lower() method is used to convert the player's responses to lowercase, allowing for case-insensitive comparisons.

- **Variables:** Variables such as playing, ans, and pt are used to store and manipulate data throughout the code.

- **Arithmetic Operations:** The += operator is used to increment the score counter (pt) by 1.

- **Control Flow:** The quit() function is used to exit the game if the player chooses not to play. The game also progresses through the questions in a linear manner.

- **Lists:** Although not explicitly shown in the code provided, a list could be used to store the questions and iterate through them using loops for a more dynamic quiz experience.
