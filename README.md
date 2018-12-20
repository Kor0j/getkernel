# getkernel
Just a simple, unfancy script for updating xUbuntu's kernel from the Ubuntu Kernel Mainline PPA.

When I say unfancy, I mean it is seriously not fancy.It's not pretty, and it's certainly not fancy enough to grab a list of kernel candidates (yet,) it simply accepts user input (What kernel version) and downloads relevent files (image, headers, modules) using wgets and greps, then installs them. I'm publishing this at a good friend's recommendation in the hopes that others will find it useful too, and be able to expand on it.

How to use:

getkernel <kernel version> - Downloads the specified kernel version, and installs, asking for sudo permission.

Other options:

getkernel [-ih]

-i - Sets interactive mode, asks the user what kernel version, and for permission to install.

-h - Prints how to use, and exits.


TODO: Add more distributions, add more options (don't ask to install) 

