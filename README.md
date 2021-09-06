Shell-Web-UI
============

A front and back end  for busybox httpd shell interface

I still need to add a security key or some other security check to the project.  At this point it's password protected and on a loop back device (to prevent remote sniffing), but one you've entered your username an password pretty much any website can take control of your device (unlikely, because they would need to know your setup, but if you leave the defaults then anyone could know).  This is pretty bad since it's ROOT access.

Right now I use incognito mode and close it out when I'm done.

View a video or the project here:
http://youtu.be/RWZRN8W1dOg


Alternatives
============
* https://github.com/meefik/websocket.sh also intended for BusyBox and uses plain shell and netcat
* https://github.com/shelld3v/wsshell written in Python but have a nice client in form of Chrome Extension
* https://github.com/joewalnes/websocketd Turn any program that uses STDIN/STDOUT into a WebSocket server
