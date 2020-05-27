# Boot Racer
Points: 150

Solve:
We've found one last floppy disk [image](https://challenge.acictf.com/static/bf8ed650465e3ad5f6c32e925be05c88/files.tar.gz) that boots, but it looks like we're just being toyed with at this point.


Hint:

Maybe the messages aren't lying. Are they printed at the same time?


Steps:

Switched to Kali linux and used `qemu-system-x86_64 -s -S floppy.img` with `GDB`

Flag: <!-- ACI{fast_dbg}  -->
