# xsessionchoose

A small bash script for choosing a xsession.
Supports nvdia-xrun for NVIDIA Optimus Laptops.
It parses the ```/usr/share/xsessions``` directory like the Display Managers do.
Put ```. xsessionchoose``` into your /etc/profile so it gets executed on every login
on TTY1.
