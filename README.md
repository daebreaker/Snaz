# Issue report by fork

Exactly as stated, basically speaking. As for the problem in question, starting Snaz under certain conditions results in an immediate crash to desktop, worsened by PIDs that simply REFUSE to die. (Seeing you have programming skills, and that I also know this stuff, I'd think you'd be able to get to the bottom of this.)

For simplicity I will do a (slightly abridged) rough draft of Task Manager results:

Image Name..........PID........User Name.....CPU.....Memory....Description........

==============================================

sihost.exe................400........*REDACTED*.....00.........4,280 K......Shell Infras.........

Snaz.exe..................11712...............................00.........20 K...........................................

Snaz.exe..................12668...............................00.........20 K...........................................

svchost.exe............2948......*REDACTED*....00.........10,904 K....Host Process......

This is from running in Admin mode, normal run does likewise when last I checked. And this is on latest master build (1.12.6.0) with no specialized features activated (up to and including Spotify) so I'm at a complete loss.

As a reminder, this isn't a proposed document change per se (that's all you) but I was simply at a loss for giving you the heads up. Fingers crossed this crosses over - this is really starting to get annoying because it obviously bricks the Snaz install (even unload/reinstall/update - which shall get one last try - has been a complete waste!) You are free to decline this request version once delivered - I only did this so I could explain what I'm dealing with.

## UPDATE

ENDED UP BEING A 3RD-PARTY SYSTEM EXTENSION ISSUE, PLEASE DISREGARD. THANKS ANYWAY!!!

# END ISSUE REPORT

# Latest version 1.12.6.0

## Snaz

- [Wiki](https://github.com/JimmyAppelt/Snaz/wiki )
- [Project](http://jimmyappelt.be/preview/snaz)
- [Changelog](http://jimmyappelt.be/Downloads/Software/Snaz/releasenotes.txt)

### Download

- You can download snaz [on the main website](http://jimmyappelt.be/preview/snaz/) or [on the release page](https://github.com/JimmyAppelt/Snaz/releases) 

## Overview

Module | Short description
------------ | -------------
Time | system time
Date | system date
Countdown | countdown to specified time *(Live countdown. Ex. Stream live in: 0h 30m 12s)*
Chrono Down | countdown from value
Chrono Up | count up from value
Textline changer | changes textlines to a single file
Twitch | does twitch stuff *(most knows for Amount of current Twitch viewers)*
System Info | capture and stream data real time like cpu usage, ram, processes, up- and download speed
Dynamic Files | create a textfile or imagefile by choice and link it to any online source
Playing Now | song, artist album, album image (Spotify, Foobar2000, winamp, iTunes and VLC)


> Check the [documentation](https://github.com/JimmyAppelt/Snaz/wiki) for more detailed information

![sample-image](https://i.gyazo.com/985dabdbf42b9dc28ec9ac4f3bd71a6c.png)

