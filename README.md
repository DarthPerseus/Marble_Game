# Marble_Game

Odd Even Marble Game is a fun, interactive text-based game designed for two players. Each player starts with 10 marbles and takes turns picking a number of marbles while the opponent guesses if the number picked is odd or even. The objective is to win all 20 marbles through correct guesses and strategic choices.

Rules
Starting Marbles: Each player begins with 10 marbles.
Turn-Based Play: Players take turns picking a number of marbles.
Guessing: The opponent must guess if the number of marbles picked is odd or even.
If the guess is correct, the player who picked must give those marbles to the opponent.
If the guess is incorrect, the opponent gives the player an equivalent number of marbles.
Winning the Game: The first player to accumulate all 20 marbles wins the game.
Game Flow
Introduction: The game welcomes the players and explains the rules.
Player Names: The game prompts both players to enter their names.
Gameplay: Players take turns picking marbles and guessing:
Player 1 picks a number of marbles.
Player 2 guesses if the number is odd or even.
Scores are updated based on the correctness of the guess.
Player 2 then picks a number of marbles.
Player 1 guesses if the number is odd or even.
Scores are updated again based on the correctness of the guess.
Endgame: The game continues until one player has all 20 marbles, and a winner is declared.
Game Analysis: A summary table is displayed showing the scores and guesses throughout the game.

Technical Details:

The code utilizes various Python modules:
time: Controls delays for the typing effect.
os: Clears the console screen.
sys: Enables flushing output to the console immediately.
pandas: Creates the game analysis DataFrame.
getpass: Hides user input for picking marbles.
Functions manage different aspects of the game:
typingprint: Displays text with a typing effect.
typinginput: Takes user input with a typing effect.
clear_screen: Clears the console screen.
get_player_names: Prompts for and returns player names.
compare_guess: Compares the player's guess with the actual answer.
update_scores: Updates player scores based on the guess.
play_turn: Handles a single player's turn, including picking marbles and handling guesses.
The main function starts the game, displays instructions, gets player names, manages the game loop, and presents the final results and analysis.
