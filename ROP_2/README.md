## todo better notes

## ROP (part 2)

We can also exploit the libc that are being used to run the program. We can leak the puts address and search for it in a libc database and use functions from the libc.
With the libc in use we can create a second payload and call to system with the args (e.g /bin/sh). 
