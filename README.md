# passgen

A simple password generator. It chooses several (defaults to 3) words from a word list and presents them as a password.

## Usage:
`passgen words delimiter minlength`

`passgen` : CorrectHorseBattery

`passgen 4 +` : Correct+Horse+Battery+Staple

`passgen 4 + 20` : Correct+Horse+Battery+Staple #Ensures the generated password is at least 20 characters long

The wordfile is a list of over 2000 long non-vulgar words obtained from:
Wordfile from: https://raw.githubusercontent.com/first20hours/google-10000-english/master/google-10000-english-usa-no-swears-long.txt
