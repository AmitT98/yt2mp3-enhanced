# yt2mp3
Simple youtube video to mp3 converter using pytube and ffmpeg. Currently on tested on macOS.
Update: 29/6/2023
The idea is to build a full fledged application using Python frameworks that allows for
1) An interactive GUI to show top 10 searches relating to the keyword.
2) Ability to change the file type(mp3/aac/wav)
3) Ability to clip/trim the audio and as well as some effects(reverb/nightcore) post conversion.
4) Being able to ship the app in Windows as well.

Implementation ideas
=> 1 and 2 can be implemented using Tkinter or Pygame
=> 3 can be implemented using sounddevice, matplotlib or numpy.

Instructions to use:\
0. Install pytube[for download], ffmpeg[for conversion], soundfile and sounddevice[for trimming]
1. Find the url of the video you want<youtubeurl>.
2. Decide a name for your file<name>
3. write the code in terminal as, python3 new.py <youtubeurl> <name>
4. To trim the audio, first place it in music folder and then run trim.py


