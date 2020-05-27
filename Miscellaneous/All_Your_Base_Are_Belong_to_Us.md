# All Your Base Are Belong to Us

Points: 50

Solve:
In honor of 30 years of terrible translations, we figured we'd give you a try at a series of (easier) translation problems. All you have to do is to translate bases by connecting to challenge.acictf.com:63596. In case you're new to network programs, we even have some Python [starter code](https://challenge.acictf.com/static/0b4faa5ee6ef62565c84675e6bf2a867/starter_code.py) you can use.


Hint:

You could do this by hand, but is it really worth that much effort?

While we only want the final encoding, it's probably easier to break that into separate decode and encode steps for each question.

Don't overthink 'raw' encoding...

Your code for encoding/decoding will probably be very similar for 4 out of 6 encodings.


Steps:

Python code to convert the input and output

Notes:

First attempted raw as the interim step but switched after first attempt failed to int (decimal). Wasteda lot of time for not identifying a trailing "/n" on my variable name. 

Flag: <!-- ACI{Somebody_set_up_us_the_bomb_74bf7f44} -->
