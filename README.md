Shell-Web-UI
============

A front and back end  for busybox httpd shell interface

I still need to add a security key or some other security check to the project.  At this point it's password protected and on a loop back device (to prevent remote sniffing), but one you've entered your username an password pretty much any website can take control of your device (unlikely, because they would need to know your setup, but if you leave the defaults then anyone could know).  This is pretty bad since it's ROOT access.

Right now I use incognito mode and close it out when I'm done.
