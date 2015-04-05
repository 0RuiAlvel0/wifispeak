Latest info (12.08.2011):

See the page below for details about this project. This project is currently closed by me, but it would be great if someone could pick up where I left off. While on the main project page, make sure you see the video for the wireless speakers in action!

Go here: http://supertechman.blogspot.com/2011/08/wifi-wireless-speakers-set.html

---------------------- ORIGINAL TEXT -------------------------
This project aims at the development of a server software designed to stream linein feeds or files to a network of wifi speakers that can be organized in groups on the server side and used to selectively play the stream being sent out.

It's main purpose is the development of an annunciator system for buildings where the speakers can be located anywhere withing wireless network coverage.

The server is designed to work on windows (other version may be developed later) and it has been developed on delphi by using a wrapper to connect to th libvlc.dll vlc API (where VLC = the famous open source media application).

The client is based on an arduino board, connected to a mp3 sheild (actually the stream will be ogg/vorbis but the shield can play that) and a wifi shield connected to an amplifier that feeds the speakers (power cable must be provided at this moment). The final goal is to design our own board.

Currently the server side delphi application is under development.

This project uses:

- libvlc API from <a href='http://www.videolan.org'>vlc</a>

&lt;BR&gt;


- <a href='https://code.google.com/p/utlibvlc/'>utlivlc</a> delphi wrapper by DsChAeK (see vc forum entry <a href='http://forum.videolan.org/viewtopic.php?f=32&t=78754'>here</a>.