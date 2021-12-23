### Blackjack Game
Blackjack is a simple card game between a dealer and a player. The goals is to get 21 points, without going over 21 (busting). A player wins if they:
* get 21 points on the player's first two cards (called a "blackjack" or "natural"), without a dealer blackjack;
* reach a final score higher than the dealer without exceeding 21
* let the dealer draw additional cards until their hand exceeds 21 ("busted").

The game goes as follows:
* Both the dealer and the player get two cards from the deck. The first card from the dealer is visible to the player, the second is not.
* The player goes first, and is allowed to ask for another card (Hit), or end their turn (Stay). If the player goes over 21, the game is over and the dealer wins.
* Next the dealer gets to go. They flip their hidden card and must get new cards until they have at least 17 points. Then they stop once they reach or go beyond 17. If they go over 21, the player wins.
* If neither the player nor dealer go over 21, then whoever has the most points wins. If they have the same points, the game is a tie.

Number cards are worth the number listed on the card. Face cards (King, Queen, Jack) are worth 10 points. And Aces are worth 11 or 1 points (use the value that ensures you do not go over 21).

### Install and Run
You must have node.js running on your machine. Once you have cloned this project you can run `npm install` to install all the packages for this project. Then running `npm run dev` will run the dev version of this code, which will run this project with nodemon. Nodemon auto-restarts the node server every time you make a change to a file. Very helpful when you are writing and testing code.


