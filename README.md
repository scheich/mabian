mabian
======

Script for building an installable live debian wheezy with mate as desktop enviroment 


#Video

[![mabian GNU/Linux Video](http://img.youtube.com/vi/-KrYcwrVSuI/0.jpg)](http://www.youtube.com/watch?v=-KrYcwrVSuI)

# Features

* Supporting for 74 languages, based on avaible task-* packages in wheezy
* Including ln-files and myspell-dictionaries (if available) for iceweasel, libreoffice, icedove and iceowl
* Installable in live-session
* Display-Manager: Lightdm
* Desktop Enviroment: Mate
* Office Suite: LibreOffice
* Internet Browser: Iceweasel (Firefox)
* Instant Messaging: Pidgin and X-Chat
* Mail and calendar program: Icedove with Iceowl (Thunderbird with Lightning extension)
* Multimedia: VLC Player, Totem and TvTime
* Graphik: Pinta simple-scan
* Games: gnome-games
* Non-Free Stuff: Adobe Flash, libdvdcss2, mscorefonts, pipelight


# TODO

* make the script jessie compatible
* UEFI Boot
* more ..

# Downloads

## AMD64
https://drive.google.com/file/d/0B-ND9Y9VRn9oQUxzN0ZkZmhralk/edit?usp=sharing

```
sha1 d6bd4dabfa05b3306680a6491be38eda945f132d  mabian-20140817-amd64-non-free.hybrid.iso
```
## i386
https://drive.google.com/file/d/0B-ND9Y9VRn9oWkZHbG00UU0zbU0/edit?usp=sharing

```
sha1 c127f9cc92b56da680091fe707f6e9858244881a  mabian-20140817-i386-non-free.hybrid.iso
```

# Install

Burn this image to a DVD or write it to a usb-storage:

```
dd if=mabian-20140817-amd64-non-free.hybrid.iso of=/dev/sdX bs=4MB
```

## Persistence

You can add persistence by adding an ext4-partition with a file called persistence.conf with following contents:
```
/ union
```

See http://live.debian.net/manual/3.x/html/live-manual.en.html#529 for details.

#Thanks

Thanks to debian team for this great linux distribution and this wonderful live-build script.

Thanks to the mate desktop team for keeping this very good desktop alive.
