# More Out of Site

Points: 10

Solve:
Well that was embarrassing... Who knew there was more to a web site then what the browser showed? Not to worry, we're back with a new and improved Javascript version! `http://challenge.acictf.com:26425`

Hint:

The Javascript code in an `onInput` gets called anytime you interact with a text field.
Is there anyway to view the Javascript definition of this function? It should just be text and your browser has it somewhere (it is running it after all).

Steps:

Inspect the page source in your browser. Used Safari so `Command + Option + U`. In the _Sources_ tab look in the `flag_checker.js` file.

Flag: <!-- ACI{client_side_fail_f77c150b} -->
