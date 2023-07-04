## YouTube video of specific length
Use this spreadsheet's first column while adding `youtu.be/`: https://drive.google.com/file/d/1UZdXQVfrnDnJ1WtWPsZiYCbO2BPsRCip/view

## Initial Password
The password I use before all the random requirements begin is `074914Kk!octoberXXXVshell`

## Wordle bypass
Probably the easiest one of them all.

Just replace the date placeholders with real values and head to this URL:
`https://neal.fun/api/password-game/wordle?date=YYYY-MM-DD`

## Chess Game bypass
For this, go to [Lichess's Board editor](https://lichess.org/editor).

Place a few of your pieces, fill in atleast 1 row into the chessboard.
Look down where it says FEN.

Now you want to copy the row you filled in's FEN information.

Example:
![image](https://github.com/pog5/nealpasswordgame/assets/62222436/3818af43-7eee-4e0c-8d2d-6b1a9c14ff9b)

Open up the file called [chess.jsonc](chess.jsonc) in this repository and press Control + F, then paste in your copied fen number, you should see the text you need to type in on the `sol` field.

## Google Maps bypass
Now this one gets a bit tricky.

Open up DevTools (Rightclick -> Inspect Element)

Click on the Inspect icon (![image](https://github.com/pog5/nealpasswordgame/assets/62222436/d078e662-a33b-4e42-8fb9-01216bce4e91))

Click on the frame of the Google Maps embed.

In DevTools, scroll up until you see something like this:

![image](https://github.com/pog5/nealpasswordgame/assets/62222436/0d842614-7f93-4c4b-8d94-eefdd10d9e48)

Double-Click on the URL then hit Control + C to copy it, then head over to [maps.jsonc](maps.jsonc), hit Control + F, paste in the URL and the text you need to type in to your password should be on the `text` field.
