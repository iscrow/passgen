# passgen

A more advanced password generator. It creates easier to remember passwords based on a template of werd types and delimiters.

# passgen Usage
<pre>
passgen [pattern]
pattern can be any space delimited combination of:
delimiter, noun, adjective, verb_base, verb_past, verb_pastparticipate, verb_ies, verb_ing
For capital lettrs use Noun, Adjective, Verb_base, etc.

The different verb forms are as follows:
verb_base  verb_past  verb_pastparticiple  verb_ies  verb_ing
forsake    forsook    forsaken             forsakes  forsaking

Examples:

passgen 'adjective delimiter adjective delimiter noun'
passgen 'Noun delimiter Verb_ies delimiter Noun'

By using the word delimiter, passgen will chose one for you. Alternatively specify your own:

passgen 'verb_ing - adjective - noun'
</pre>


# passgen-legacy

A simple password generator. It chooses several (defaults to 3) words from a word list and presents them as a password.

## passge-legacy Usage:
`passgen words delimiter minlength`

`passgen` : CorrectHorseBattery

`passgen 4 +` : Correct+Horse+Battery+Staple

`passgen 4 + 20` : Correct+Horse+Battery+Staple #Ensures the generated password is at least 20 characters long

The wordfile is a list of over 7500 medium and long non-vulgar words obtained from:
https://github.com/first20hours/google-10000-english/

I continue to remove words that could be offensive to some. Please feel free to contribute with suggestions for words that you find less than appropriate.

