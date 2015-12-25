# Oath-Applet
This project implement the HOTP/TOTP card functionality. Its primary use is to  generate OATH(Open AuTHentication ) HOTP/TOTP one-time-passwords.

INTRODUCTION
========
 This applet used in a One-Time Passcode (OTP) generator device. It generates a unique sequence of characters as an OTP every time its button is pressed.
This project implement the HOTP/TOTP card functionality. 



License 
=======
This program is released under the GPLv3+.

Discussion
=======

Have doubts? You can visit [Here](http://javacardos.com/javacardforum/viewforum.php?f=42) to get more scripts and leave your comments and suggestions.

Building
===

The easiest way is using [JCIDE](http://javacardos.com/javacardforum/viewtopic.php?f=26&t=43) open this project,  Click "Buid All Packages(F7)" to build the source code.

Usage:
===========
 Use [pyApduTool](http://javacardos.com/javacardforum/viewtopic.php?f=3&t=38) to Download this  applet to card, install, select and communicate with the card.


Additional Features:
=========
This Applet actually supports some pin policy enforcement.
Checks are made on the pin size, character set and mix of characters.
The exact pin policy depends on parameters provided at instantiation time.

Note:
======
Different versions of this Applet could be released, with different features disabled, in order to let you save space on the card if your application does not require those features at all.
