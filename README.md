# Land of Blooming Cloth

 A playable version of [Ewa and Haunted Automaton's strategy game](https://www.youtube.com/watch?v=hDCCdcRa41w) designed for the people of Ewa's River Basin. You can download a Mac build from the [releases page](https://github.com/BenCreating/land-of-blooming-cloth/releases).



Click and drag to place pieces on the board. Click on a piece to unfold it.



The AI uses a minimax algorithm with alpha-beta pruning. There are *lot* of possible moves every turn, so if you want it to be any good you will have to give it a lot of time.



**Game Rules:**

- The game is played on an 8x8 grid.
- Each player has twelve pieces, made of cloth.
- Each piece is folded into small squares that can be unfolded twice before play.
- On your turn you can either place a piece on an empty space, or unfold one of your pieces that is already on the board.
- Pieces that are covered by an unfolding cloth are locked and cannot be unfolded.
- Play continues until neither player can make a legal move
- The winner is the player with the most spaces covered by their pieces. Only count the top layer of cloth.

Written in [LiveCode](https://livecode.org). I've supplied the [code for the main game logic](https://github.com/BenCreating/land-of-blooming-cloth/blob/main/Game%20Logic), for anyone who wants to view it without downloading LiveCode.
