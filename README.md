# Rock, Paper, Scissors

- We import **"Random"** library 
- We ask the user to choose a game
- We loop through the list of choice and if not there print and error message 

### Logic of the game 

* __Rock__ beats Scissors because a rock can break scissors
* __Scissors__ beat paper because scissors can cut paper
* __Paper__ beat Rock because paper can wrap a rock

### How the winner is decided

* **if both players choose the same thing** : it's a tie
* **if one choice naturally defeats the other** : the winner is the one with the strongger choice according to the rules above
* **if neither of the first two conditions applies** : the remaining player loses
