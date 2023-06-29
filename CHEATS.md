# Cheats
Or as I like to call them, bypasses.

## Chess Game bypass
For this, go to [Lichess's Board editor](https://lichess.org/editor).
Now, you have 2 routes, the semi-correct way and the cheater way.

### Semi-Correct way
Place all your pieces as shown on the image on neal's website then click this button on the right.

![image](https://github.com/pog5/nealpasswordgame/assets/62222436/b0b5586d-72db-4549-b1a0-62a0a21ec3bd)

Then enable Stockfish using the little switch in the top right:

![image](https://github.com/pog5/nealpasswordgame/assets/62222436/60dccb3b-2467-49be-a533-c1a4d03eb823)

In here, the first move should be what you want to type in.

![image](https://github.com/pog5/nealpasswordgame/assets/62222436/57c4d357-5526-47f8-b81f-ce8b222dc032)

Convert the symbol from a chess piece into a letter so for example it becomes Bfe6+.

### Cheater way
Place a few of your pieces, preferably atleast 1 row into the chessboard.
Look down where it says FEN.

Now you want to copy the row you filled in's FEN information:

![image](https://github.com/pog5/nealpasswordgame/assets/62222436/3818af43-7eee-4e0c-8d2d-6b1a9c14ff9b)

Open up the file called Chess.json in this repository and press Control + F, then paste in your copied fen number, you should see the text you need to type in on the `sol` field.
