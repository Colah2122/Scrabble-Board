Github URL: 
Github Repository: https://github.com/Colah2122/Scrabble-Board
The writeup: I was able to implement everything on the rubric except for one thing. 
I was unable to get the tile once it has been placed on the board to be able to be 
placed back on the rack.

• (4) letter tiles in the player’s “hand” are selected randomly from a data structure with the properdistribution of the letters (code!)
    Implemented random function randomly picking letter from data
• (4) letter tiles can be dragged-and-dropped onto target Scrabble squares
    Used jQuery drag and drop on divs containg images of the scrabble tiles 
• (4) program identifies which letter tile is dropped onto which Scrabble square
    Goes into data and gets correct letter 
• (4) board includes at least two bonus squares
    Board contains 2 double letter points spots
• (4) score is tallied correctly, including consideration of bonus square multipliers
    Once letter is dropped it updates the score correctly along with applying mulipliers correctly
• (3) any number of words can be played until the player wishes to quit or depletes all tiles
    After going through all tiles there is a prompt to click restart game and user can restart game
• (3) the board is cleared after each round so that a new word can be played
    Board is cleared every round by deleting pieces that are no longer in play
• (3) after playing a word, only the number of letter tiles needed to bring the player’s “hand” back to 7 tiles are selected
    Implemented correctly
• (3) score is kept for multiple words until the user restart a new game (implement next vs. restart)
    Score stays accurate throughout game
• (2) Tiles can only be dragged from the “rack” to Scrabble board. If the user drop them anywhere else, they will be bounced back to the “rack”.
    Bounce back effect works when not placed correctly
• (2) Once the tile is placed on the Scrabble board, it can be moved back to the “rack”.
    Not implemented
• (2) Except for the first letter, all sub-subsequent letters must be placed directly next to or below another letter with no space. Else, they will bounce back to the “rack”.
    Implemented correctly
• (2) user can always restart the game.
    User can select restart game button to restart anytime
