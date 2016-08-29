# pwdhash-poc
Proof of concept PwdHash alternative

## Overview

This is a proof-of-concept alteration to the [Stanford PwdHash](https://www.pwdhash.com/) tool. The main changes to the original are the following.

1. Changed the hash algorithm from HMAC-MD5 to PBKDF2-SHA256.
2. Added the option to store a user-specified salt and iteration count.
3. The effective 22-character password limit has been removed.

Due to the changes this version is incompatible with the earlier PwdHash versions.

You can test out the updated version at the [PwdHash-PoC](https://www.cl.cam.ac.uk/~dl551/pwdhash) website.

## Deploy

If you'd like to deploy your own version, just copy the files inside the ```site``` folder to your webspace. Everything else happens on the client.

## Contact

- David Llewellyn-Jones: http://www.cl.cam.ac.uk/~dl551
- Graham Rymer: https://www.cl.cam.ac.uk/people/#gr348
