This software calculates a password for resetting the clock in the
Game Boy Color games Pokémon Gold, Silver, and Crystal.

In Pokémon Crystal, note that a different button combination must be used to
access the reset dialog.

Also note that this reset mechanism does not appear to be present in the
Japanese releases (at least, the button combinations do not work to reach the
screen).

Fork of the (now-dead) repository
[https://git.github.com/woddfellow2/pkmn-gs-clockpassword.git](https://git.github.com/woddfellow2/pkmn-gs-clockpassword.git),
which I recovered from my (jailbroken) iPhone 4S, of all places.

It includes a Python 2.7 backport of the code which was absent in the original
author's repository.

I backported it because (at the time) I used iOS, and was out of cellular data
range for a long period of time. This script was the best option I saw.
Unfortunately, There was no readily available Python 3.x port to it which I
could find. Meanwhile, there was a Python 2.7 port for iOS (I believe it was
in the Telesphoreo repository from Saurik). So I backported the script.

This repository also features an updated readme which details how to reset your
password in Pokémon Crystal. The original author believed that this was not
possible without a cheating device, but it simply requires a more complicated
button combination than either Gold or Silver versions did.

Where to Get the Information
----------------------------
To get the player-character name, trainer ID number, and amount of held money,
enter the main menu by pressing START. Then select the option labelled with the
player character name (this should be above SAVE). The player character name,
trainer ID number, and amount of held money are at the top of the screen.

Using the Password
------------------
In Gold and Silver, at the title screen, press DOWN+SELECT+B. Select YES to
reset the clock. Enter the password at the password prompt. It resets the clock
upon receiving the correct password. Next time you select CONTINUE at the main
menu, it will ask for the day of week and the time.

In Crystal, the process to reach the reset dialogue is a little more
complicated. Perform the following sequence:

1. **Hold down** DOWN+SELECT+B.
2. While *still holding* SELECT, release DOWN+B.
3. Hold LEFT+UP.
4. Release SELECT.

Follow the Gold and Silver instructions after reaching the reset screen.

This page was a reference in the making of this software:
http://web.archive.org/web/20090902012638/http://geocities.com/thelegendarydogs/faqs/gsc/time/timereset.htm
