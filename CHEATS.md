# Script to automate everything
The script may not always succeed but theres a very high chance it does.
Install Tampermonkey or Violentmonkey then click on the link bellow
https://github.com/pog5/nealpasswordgame/raw/main/password-game-tas.user.js

## YouTube video of specific length
Use this spreadsheet's first column while adding `youtu.be/`: 
`https://drive.google.com/file/d/1UZdXQVfrnDnJ1WtWPsZiYCbO2BPsRCip/view`

If you are unable to find any links without messing up elements/digits, you can find one yourself by searching the follwing: 

Replace `DURATION` with your desired length in the format `MINUTES:SECONDS`: `[site:youtube.com "0:00 / DURATION"]`

## Initial Password
The password I use before all the random requirements begin is `94417!octoberXXXVshell`

## Wordle bypass
Probably the easiest one of them all.

Replace `DATE` with today's date in the format `YYYY-MM-DD`:
`https://neal.fun/api/password-game/wordle?date=DATE`

Alternatively, you can paste the following one-liner into the developer console (F12):
```js
d=new Date().toISOString().split('T')[0],fetch(`https://neal.fun/api/password-game/wordle?date=${d}`).then(r=>r.json()).then(d=>console.log(d.answer))
```

## Captcha bypass
There's no need for a bypass since the solution is self-evident, but here's a one-liner in case you are coding a solver yourself:
```js
document.querySelector('.captcha-img').src.match(/\w+(?=.png)/)[0]
```

## Chess Game bypass
For this, go to [Lichess's Board editor](https://lichess.org/editor).

Place a few of your pieces, fill in atleast 1 row into the chessboard.
Look down where it says FEN.

Now you want to copy the row you filled in's FEN information.

Example:
![image](https://github.com/pog5/nealpasswordgame/assets/62222436/3818af43-7eee-4e0c-8d2d-6b1a9c14ff9b)

Open up the file called [chess.jsonc](chess.jsonc) in this repository and press Control + F, then paste in your copied fen number, you should see the text you need to type in on the `sol` field.

You can also add [Chessvision.ai](https://chessvision.ai/) as a browser extension, then scan the webpage and turn on Stockfish.

## Google Maps bypass
Now this one gets a bit tricky.

Open up DevTools (Rightclick -> Inspect Element)

Click on the Inspect icon (![image](https://github.com/pog5/nealpasswordgame/assets/62222436/d078e662-a33b-4e42-8fb9-01216bce4e91))

Click on the frame of the Google Maps embed.

In DevTools, scroll up until you see something like this:

![image](https://github.com/pog5/nealpasswordgame/assets/62222436/0d842614-7f93-4c4b-8d94-eefdd10d9e48)

Double-Click on the URL then hit Control + C to copy it, then head over to [maps.jsonc](maps.jsonc), hit Control + F, paste in the URL and the text you need to type in to your password should be on the `text` field.

## Moon bypass (if you're lazy or working on script)
Add `🌑🌒🌓🌔🌕🌖🌗🌘` to your password. This is not the most elegant as your password now contains unnecessary characters, but it's definitely the easiest.
