# arduino-mp3-player
Dynamic playback of mp3 audio files using Arduino MP3 player shield

Augments existing Arduino code by implementing dynamic playback of an array of named audio files in a never-ending loop.

<hr>

Shout out to  Bill Porter and Michael P. Flaga for writing the initial MP3 player demo sketch this code is built from.
I commented the places where I added my code for dynamically-looped playback. Includes a commented out section for generic playback of numbered files.

Notes:
Works with Arduino SDFat library version 1.0.1 (Bill Greiman). MP3 player code from Sparkfun broke when using latest version of SDFat Arduino library (2.1.0)

MP3 Player Shield: https://www.sparkfun.com/products/12660 <br/>
Arduino used in project: https://www.sparkfun.com/products/13975 <br/>
Project this code was used for: https://blogs.uoregon.edu/soundscapesofsocioecologicalsuccession/
