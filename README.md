# SHA-512Half Commandline Utility

This is a simple Python 3 script that prints the SHA-512Half value of an input string. SHA-512Half is a secure hash function that uses the first half of the SHA-512 output. (This has the same security as SHA-256, but is faster to calculate on 64-bit processors.)

Usage:

```bash
$ ./sha512half "mDuo13 is cool"
F1607C25DC3660C878802A69C8EF8E11AE62172F3A6C40F5C6CD85AB5E407A87
```

You might need to set the script as executable (`chmod +x`) first, or edit the shebang if `/usr/env python3` doesn't point to your Python 3 interpreter.

