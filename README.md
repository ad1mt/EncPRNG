EncPRNG is a Pseudo Random Number Generator using my own algorithm.
I use it for cryptography in my password manager EncView.

It also has some interesting features that other RNGs do not have:

1. Repetition detection.
2. Automatic re-seeding when repetition is detected.
3. Features 1 & 2 enable infinite period.
4. Can create an unlimited number of RNG instances, which are independent, 
and can be run simultaneously in different threads or processes.

I have included two small demo programs to encrypt and decrypt a file, which 
give an example of how to configure and use the RNG.

If you would like information about the algorithm, please contact me.

When I use the terms "infinite" and "unlimited" above, I really mean "almost".

No copyright, no guarantee, no license.
