# rasp-pi-btct-beta

Temp repo for testing with creating custom Raspbian Buster image for Bitcoin Token wallet version 1.1.  Will come up with a permanant, properly documented solution next (likely a fork of pi-gen with changes specific to btct).

Tested image on Pi 4b 4GB and Pi 3b (not tested on 3b+ yet).  In all cases, if the latest Raspbian Buster works on your device, this should also work.  It's a straight build from Raspbian official source using pi-gen (same tool they use to create official releases) with only the official Bitcoin Token v1.1 wallet added, and some cosmetic customizations.

After booting up, go through the setup wizard and reboot.

Click on the raspberry menu at the top left and you should find Bitcoin Token (this is the -QT wallet).  Click it and follow the prompts, letting it download the blockchain.  Note, the blockchain was not included in the image for security reasons, it's safer to download from scratch.

BE SURE TO ENCRYPT AND BACKUP YOUR WALLET!  If you forget your password, no one can help you.  If you are unsure what you are doing, come to the Discord server and ask -> https://discord.gg/4cAGCf4

I am go140point6#7708 on Discord and if you need help, call me out in the #raspberry-pi channel.  I WILL NEVER DM YOU AND ASK YOU FOR YOUR PASSWORD OR PRIVATE KEYS OR ANY OTHER INFORMATION.  If someone claiming to be me (or anyone) does, block them and report to the mods of whatever servers you have in common with the scammer.

READ THE PARAGRAPH ABOVE AGAIN!  NEVER GIVE OUT YOUR PASSWORD OR PRIVATE KEYS TO ANYONE UNLESS YOU LIKE HAVING ALL YOUR CRYPTO STOLEN FROM YOU.

### Instructions for etching

Use Etcher (https://www.balena.io/etcher/).  No need to unzip the image first, Etcher will do that for you.  Just download and point etcher to the .zip file.

Use a 16GB SD Card minimum, but recommend you go for 32 or 64GB, the blockchain will grow.  Get something with decent speed.

AGAIN: BE SURE TO ENCRYPT AND BACKUP YOUR WALLET!  SD Cards can and will go bad.  Back up your wallet and make sure you know the password.
