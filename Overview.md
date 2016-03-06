# Introduction #

The principle is to open the main patch which is a Mixing board, where you'll find control for everything, it's where audio signal is caught from other patches through a system of AudioBuses (see the patch in z\_usefull\_abs, and troubleshooting if under windows). So you can catch the sound in the mixer then route it to some effects and then to the output or to be recorded.

Each patch that produces a sound ends by an AudioBus object that lets you send the output to any track in the mixer patch.


<a href='http://picasaweb.google.com/lh/photo/Dj8zT19-1cum_DQFmjQRMg?feat=embedwebsite'><img src='http://lh4.ggpht.com/_TZMojZ6BS9g/THk5DIjakJI/AAAAAAAAAA0/46PBqWamSSE/s800/MainBoard1.png' /></a>
<a href='http://picasaweb.google.com/lh/photo/lmIpvJHkg9fEq4mdV6a3fg?feat=embedwebsite'><img src='http://lh3.ggpht.com/_TZMojZ6BS9g/THk5DZfEB0I/AAAAAAAAAA4/3kJSxA3R-Wg/s800/MainBoard2.png' /></a>


Here's a snapshot of a patch with an AudioBus system, you can easily conform any of your patches by just sticking an audioBus at the outlet. (It's is the popup version, only Mac and Linux, the number version for windows is presented as a multi-routing system in the Mix&Fx window of pdlive). Notice that you have the choice to wether activate an AudioBus wether to go directly to dac (it can be usefull when you just want to hear a the output of the patch before using it)

<a href='http://picasaweb.google.com/lh/photo/eZf1BhwMnxK_mfrjvdtPkg?feat=embedwebsite'><img src='http://lh5.ggpht.com/_TZMojZ6BS9g/THk7jvQRaBI/AAAAAAAAABE/C6qFPj26z20/s400/BeatSlicer-AudioB.png' /></a>
This patched is used to chop audio files in a number of slices (0-16) then it will play each slice according to a metro choosing which slice to read from an array.

for more information on how it's done, my favorite sources : (these sites are amazing and will teach you many things about pd, sound synthesis ...)
http://obiwannabe.co.uk/
http://www.pd-tutorial.com/
http://puredata.hurleur.com/


Have Fun !