# Set-card-game
  ## Overview:
   The project was made using Java and demonstrate my concurent programming  skills,
	 In the code it is possible to see usage in Java's concurrency tools and data structures 
   such as - 'Synchronized' command, locks and Blocking Queues. In the game every entity is represented by adifferent thread(Dealer,players,timer etc.)
  ## The game:
The project presents a version of the popular card game, with some changes that allowed me to highlight my Multi-Threading programming skills. The game is played by up to 4 players, which can include up to 2 real players playing simultaneously with 2 "AI" players that generate random key presses. Alternatively, it can be a game with 4 artificial players. During the game, there is a timer displayed on the screen. When the timer ends, the "Dealer" replaces the cards on the table with fresh cards from the deck. The game ends when the deck is finished (cards that were part of a set do not go back to the deck).
   ### settings:
In the config.properties file, we can determine some of the game's features. For example:
- Set the number of players .
- Set a freeze penalty time for an incorrect set choice.
- Adjust the length of a single round before shuffling by setting the timer for the countdown .
