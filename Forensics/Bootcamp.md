# Bootcamp
Points: 20

Solve:
We found an old floppy-drive laying around and think that there may be a flag hidden on it somewhere. We managed to copy the drive [image](https://challenge.acictf.com/static/b4f3bf1877a48f13a5da5fadd3df60a9/files.tar.gz), but there doesn't appear to be any kind of filesystem on it. In fact, all of the data appears to be on the first sector of the disk.

Hint:

It looks like file floppy.img identifies it as a "DOS/MBR Boot Record"...
What happens if you try booting the image?
You probably don't have a real floppy drive that you can use, but what about a 'virtual' one?
qemu-system-i386 floppy.img is our favorite means of 'booting' floppies, but 'Virtual Box' and 'bochs' are other alternatives (and they are all free).
Steps:

The link shows the wikipedia page of file signatures or Magic Bytes / magic numbers. 
I opened the file in a hex editor _0xED 2_ on macos and saw the file started with "PK". This is a zip file so I renamed the file with .zip
Opening the zip reveals a text file with the flag.

Flag: <!-- ACI{BoOt_MaGiC}  -->
