# Most Out of Site

Points: 20

Solve:
Alright, one more try. We had to think long and hard about how to keep you from viewing the flag. After a quick snack break, we had an epiphany. Your tricks won't work this time. [http://challenge.acictf.com:48690](http://challenge.acictf.com:48690)


Hint:

What on earth could [snack food](https://en.wikipedia.org/wiki/HTTP_cookie) have to do with this problem?
The browser must be storing these cookies somewhere...
If you're getting tired of using a browser, the Python [Requests](https://requests.readthedocs.io/en/master/) library is pretty useful for interacting with web servers.


Steps:

Inspect the page source in your browser. Used Safari so `Command + Option + U`. In the _Storage_ tab look in the `Cookies` file.

Notes:

Need to go back and try programmatically getting flag with python requests.

Flag: <!-- ACI{cookies_fail_too_cd680d37} -->
