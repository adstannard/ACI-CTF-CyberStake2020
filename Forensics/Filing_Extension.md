# Filing Extension

Points: 10

Solve:
We went to apply for a tax-filing extension with the IRS, and they replied with this image saying it contained the code we needed. Unfortunately, our computer refuses to display it and just says that it isn't a PNG... [flag.png](https://challenge.acictf.com/static/38516b189f1d7c3df4262a1a2d593fb7/flag.png)

Hint:

Is the extension the only way to tell a file's type?
Wouldn't it be awesome if there was a [list](https://en.wikipedia.org/wiki/List_of_file_signatures) of way to identify files.

Steps:

The link shows the wikipedia page of file signatures or Magic Bytes / magic numbers. 
I opened the file in a hex editor _0xED 2_ on macos and saw the file started with "PK". This is a zip file so I renamed the file with .zip
Opening the zip reveals a text file with the flag.

Flag: <!-- ACI{Something_witty_7e508cf0} -->
