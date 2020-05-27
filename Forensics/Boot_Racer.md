# Boot Racer
Points: 150

Solve:
We've found one last floppy disk [image](https://challenge.acictf.com/static/bf8ed650465e3ad5f6c32e925be05c88/files.tar.gz) that boots, but it looks like we're just being toyed with at this point.


Hint:

Maybe the messages aren't lying. Are they printed at the same time?


Steps:

1. Switched to Kali linux.
2. Terminal `qemu-system-x86_64 -s -S floppy.img`
3. Another Terminal window `gdb vmlinux`
4. `(gdb) target remote localhost:1234`
5. `awatch *0x00007dc0`
6. Use `c` to `continue` until New value = 17217
7. `x/10s 0x7dc0` to step through.
8. Get out `ACI{fast_`
9. Then `I{fast_dbg}`

Notes:

[GDB x command](https://visualgdb.com/gdbreference/commands/x)

Flag: <!-- ACI{fast_dbg}  -->
