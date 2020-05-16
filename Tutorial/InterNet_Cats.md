# InterNet Cats

Points: 4

Solve:\
It looks like some crazy cat-lady stole our last tutorial flag and is handing it out to anything that 'sounds' like a cat. Her **server** is `challenge.acictf.com`, and she is listening on **port** `41812`.


Hints:\
There is a useful program called `netcat` that sends the input it receives locally to a remote host and port and puts the data it receives from there onto the command line.\
The cat-lady does not care about capitalization.\
There are numerous ways to connect to the server to solve this problems, here are two we know of (replace the parts with braces, to include the braces, with the information from the problem description):\
With netcat: `nc {{server}} {{port}}`\
With telnet: `telnet {{server}} {{port}}`


Steps:\
I used netcat in a _terminal_ window on macos. `nc challenge.acictf.com 41812` with the input `meow`.

Flag: <!-- ACI{74bde9f9638deccf8ffd0d55a94} -->
