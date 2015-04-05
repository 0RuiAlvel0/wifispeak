# Introduction #

This page is designed to be a quick, easy reference to run the software starting on version 09082010 for both client and server applications.

The applications run on a PC. However the stream can be read from any platform using VLC by choosing read network stream and using the address of the server and port 8080 (the server will indicate the IP address of the server.


# Details #

**unpack the XXXXXXXXserver.rar file. this folder contains the source code, include files, txt files for my reference to help me on the programming and, most importantly, the executable.**

**start the application and**

1. Choose stream input (lets choose file for now, directshow inputs like a mic are also possible and, in fact the all purpose of this project. If you would like to test the dshow inputs, just choose the corresponding option instead of the file option).
2. Choose an mp3 file from your collection (click on the 'open file' button
3. Note the IP address of the server and look for the speaker.spk file on the server folder
4. Open the file and add the client IP address in the list followed by |auto|auto, like this:

192.168.11.34|auto|auto

we are going to try the program on the same host computer so the client IP address to add to the file is the same as the server IP address. Later if you want to try the application on another computer on the network, just open the client application on the client, note the IP address and add it to the file like we have just done.

NOTE: one of the requirement of the project is that the speakers will declare themselves to the server and there will be no need to add them by hand to the file (i'm working on that now)

4.1 restart the server application to refresh the speaker file including the new speaker IP you just added.

5. Now, press the start button. After a few messages scroll by on the debug window, the stream is playing. To make sure, press the 'streaming?' button. That will open a message window with the message TRUE or FALSE, depending on what's happening.

6. [described before, open VLC at this moment and point it to open the http://IPADDRESSOFSERVER:8080, you should start hearing the stream](like.md) OR start the client application on the XXXXXXXXXclient folder. It should automatically pickup the IP address of the local machine. Press start, some mesages scroll on the decoder message window and you should then start hearing the stream.