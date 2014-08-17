mabian
======

Script for building an installable live debian wheezy with mate as desktop enviroment 


Video: https://www.youtube.com/watch?v=-KrYcwrVSuI

Builds with this config:

https://drive.google.com/file/d/0B-ND9Y9VRn9oQUxzN0ZkZmhralk/edit?usp=sharing
sha1 d6bd4dabfa05b3306680a6491be38eda945f132d  mabian-20140817-amd64-non-free.hybrid.iso

https://drive.google.com/file/d/0B-ND9Y9VRn9oWkZHbG00UU0zbU0/edit?usp=sharing
sha1 c127f9cc92b56da680091fe707f6e9858244881a  mabian-20140817-i386-non-free.hybrid.iso

Write this image to a DVD or to a usb storage:

dd if=mabian-20140817-amd64-non-free.hybrid.iso of=/dev/sdX bs=4MB


You can add persistence by adding an ext-partition and a file called persistence.conf with following contents:

/ union

See http://live.debian.net/manual/3.x/html/live-manual.en.html#529 for details.

Thanks to debian team for this great linux distrubution and this wonderful live-build script.

Thanks to the mate desktop team for keeping this very good desktop alive.
