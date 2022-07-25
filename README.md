<div align="center">

# ladder-game
*Game statement* : There are 5 levels in the game, level 1 is the lowest, level 5 is the highest. A player starts at the bottom, each time a fair coin is tossed. If it turns up heads, the player moves up one level, if fails the players move down to the very bottom. Once at the top level, the player moves to the very bottom if a tail turns up and stays at the top if head turns up.
  
</div>

## Pseudocode 

- if(level is 1) --> player starts at bottom

- coin is tossed at *level 1*:
  - if **heads** --> moves to *level 2*
  - if **tails** --> stays on *level 1* 

- coin is tossed at *level 2*:
  - if **heads** --> moves to *level 3*
  - if **tails** --> moves on *level 1* 

- coin is tossed at *level 3*:
  - if **heads** --> moves to *level 4*
  - if **tails** --> moves to *level 1* 

- coin is tossed at *level 4*:
  - if **heads** --> moves to *level 5*
  - if **tails** --> moves to *level 1* 

- coin is tossed at *level 5*:
  - if **heads** --> won the game
  - if **tails** --> moves to *level 1*



## Resources
- [Coin Toss Game using JavaScript](https://dev.to/shantanu_jana/coin-toss-game-using-javascript-css-1cf0)
- [JavaScript Coin Toss Game](https://jsbeginners.com/coin-toss-game/)

###### To do
- add animations using javascript in this project.
