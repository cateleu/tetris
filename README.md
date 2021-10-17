Tetris
From NAND Gate to Tetris project

Terrence Leung
Feb 28, 2021

- using Jack compiler

Compile:
./JackCompiler.sh Tetris

Oct 17 In progress - TODO:show next tetrominos.
In progress - TODO:separate runable unit test
In progress - revise copyTwoDimensionArray functions.


Done:
Oct 17, 2021:
- add Score calculation.
Oct 13, 2021 
Tune control:
- if keep rotating, piece move up!
- press left/right the piece freeze in position
- only freeze in position on the edge of touching a bottom piece before embed.

- Fixed right rotation.
- Add 7 pieces rotation.
- Tune control.
Sept 25, 2021 add other remaining tetrominos.
- Fix: add right rotate.


Bug fixes:
Fixed - I block inserted into playground block
Fixed - right rotate edge test for Z and I block.
Fixed - dropFast for O
Fixed - at pos 12, should drop to 14 but it is not!
Fixed - now display at top!
Fixed - speed fast is ignored on row 0.
Fixed:rotate left screen flicker!
=============================


=============================
BUG:

drop faster close to bottom?

TODO:GameOver sometimes not detected gracefully.
TODO:(Fixed? to confirm)fix Utilities.initialize
TODO:cleanup unused/bad codes.

TODO:global variable class for parameters.
TODO:speed increases as progress.
TODO:randomize tetromino piece.

GOOD To have:
- rewind.
- add randomize block as progress.
