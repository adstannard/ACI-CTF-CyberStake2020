# Bootcamp
Points: 20

Solve:
We found an old floppy-drive laying around and think that there may be a flag hidden on it somewhere. We managed to copy the drive [image](https://challenge.acictf.com/static/b4f3bf1877a48f13a5da5fadd3df60a9/files.tar.gz), but there doesn't appear to be any kind of filesystem on it. In fact, all of the data appears to be on the first sector of the disk.

Hint:

It looks like `file floppy.img` identifies it as a "DOS/MBR Boot Record"...
What happens if you try booting the image?
You probably don't have a real floppy drive that you can use, but what about a 'virtual' one?
`qemu-system-i386 floppy.img` is our favorite means of 'booting' floppies, but 'Virtual Box' and 'bochs' are other alternatives (and they are all free).


Steps:

First ran the floppy image in a MS-DOS Virtual Machine on Parallels. Also tried with Qemu for practice once running Kali linux.
Booting the image releaves the flag.

Flag: <!-- ACI{BoOt_MaGiC}  -->
