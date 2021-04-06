# What is this about?
Welcome, I invented a chess-like game (which is impossible to play over real board), but people have difficulties in understanding rules without seeing any example. So i decided to learn html and create a page with interactive demonstration instead of publishing a rulebook.

## Roadmap:
- <i am here>
* import font from google and define layout
* find out how to draw on canvas
* make javascript function (pieceName, coords) {draw piece}
* can i define piece geometry in css?
* define gamestate format, describing pieces positions, which player is up to move
* function (gamestate) {draws field}
* cookie for saving gamestate?
* function overlap(gamestate) {detects if pieces are drawn overlapping, return bool}
* function deletePieces(gamestate) {deletes underlying piece if two overlap (capture mechanic)}
* function win(gamestate) {return +1 if white wins, -1 if black, 0 -> continue game. No draw}
* tap the piece detection
* moving piece
* resctrictions on movement (basically i will implement core game-mechanics at the very last step)
  * pawn
  * knight
  * bishop
  * rook
  * queen
  * king

In parallel i will work on a personal [site](https://nikita-babich.github.io/site/) and test css/javascript features there. 
