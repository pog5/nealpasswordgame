# Neal'fun's Password Game
A breakdown on https://neal.fun/password-game/
(and also a reverse-engineering attempt)

# [Cheatsheet](CHEATS.md)

## A simplified list of the Rules:

1. At least 5 characters
2. A number
3. An uppercase letter
4. A special character
5. Digits summating to 25
6. A month
7. A roman numeral
8. One of `pepsi`, `starbucks` or `shell`
9. Roman numerals need to multiply to 35
10. The solution to a provided captcha ([Bypass])
11. Today's Wordle answer ([Bypass])
12. Two letter symbol from the periodic table.
13. Current phase of the moon as an emoji (one of :new_moon::first_quarter_moon::waxing_gibbous_moon::full_moon::crescent_moon::first_quarter_moon_with_face::full_moon_with_face::waxing_crescent_moon::waning_gibbous_moon::last_quarter_moon::waning_crescent_moon::new_moon_with_face::last_quarter_moon_with_face:) ([Bypass])
14. Name of country from Google Maps ([Bypass])
15. Needs a leap year (Just type `0`)
16. Calculate the best chess move, bypass below.
17. Paul the :egg:! Don't delete him by accident or you lose the game.
18. All atomic numbers in your password must add up to 200
- Before doing the next step, I suggest you copy your current password (to combat the fire in rule 20).
19. All vowels must be bolded (bold button unlocked)
20. Delete all of the :fire: before it deletes your password (more importantly Paul)
21. Add 4 of :man_lifting_weights: 
22. Needs to contain one of `"i am loved", "i am worthy", "i am enough"`
23. Egg hatches, feed him a :bug: every 20 seconds or paste in 3 :bug: every 50 seconds~.
24. Find a YouTube video with a given (randomly generated) length.
  - Good luck with this one, I just generated my own using ffmpeg and then uploaded it to youtube:
  - `ffmpeg -loop 1 -i image.png -c:v libx264 -t DURATIONINSECONDS -pix_fmt yuv420p -vf scale=320:240 out.mp4`
  - Change DURATIONINSECONDS to your desired video length in seconds. Change image.png to some valid image.
25. You need to pick 2 letters you will no longer be able to use
26. Your password must have twice as many italic letters as bold letters (italic button unlocked)
27. Atleast 30% of your password needs to be in 'Wingdings' (you get a font selector here)
28. You need to type the random color it generates in hex
29. All roman numbers need to be in Times New Roman
30. Font size of every digit must be equal to the square of the digit (font size picker unlocked)
31. Every instance of the same letter needs a unique font size
32. Password needs to contain password's length as a number
33. Password length also needs to be a prime number
34. (Automatically Checked off, look at the rule's number if you're asking why)
35. You need the current time in format HH:MM
36. ~~Copy-Paste~~ Re-type the password into another textbox, you have 2 minutes to do this.

[Bypass]: CHEATS.md
