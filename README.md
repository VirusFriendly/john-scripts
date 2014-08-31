john-scripts
============

A collection of john the ripper modes and scripts.
John the ripper can be found http://www.openwall.com/john/

crimson4.conf - An external mode to provide a more efficent brute force for the 1st trillion guesses using entropy.
hex/hex.conf - An incremental mode to generate all possible 8 digit hexidecimal values
hex/hex_lower.chr - Charset file [0-9a-f] to support the hex incremental mode
hex/hex_upper.chr - Charset file [0-9A-F] to support the hex incremental mode

Install
=======
To add an incremental or external mode to john, append the mode to john's configuration.

example: cat *.conf >> john.conf

To add the charset files, copy them to john's base directory (typically /usr/share/john)

example: cp *.chr /usr/share/john
