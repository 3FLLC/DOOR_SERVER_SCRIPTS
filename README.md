# DOOR_SERVER_SCRIPTS
These are plug-and-go scripts for my Modern Pascal CodeRunner engine - BBS Games!

Requirements:
<a href="../modernpascal/">Modern Pascal CodeRunner</a>

unzip the game engine you would like to use, includes full source so you can tweak colors and such.

Then edit your /etc/coderunner2.conf or c:\Windows\coderunenr.ini - increment the servers=# field and add a new listerner entry.

port=2321
blocking=off
nagle=off
onconnect=/BBS/MCSOFT/BJ212018.P

Save and restart your coderunner (DOOR SERVER) daemon - telnet to 127.0.0.1 port 2321 - viola!

* More games to come - this one took me 7 days to port from JPDOOR to CodeRunner. Now I have the hang of it, the other 20+ games should be much faster to release.

** NOTE ** There will be a revisit to all scripts once I know how to make MysticBBS and Synchronet work with my DOOR SERVER.
Ozz
