<a href='http://picasaweb.google.com/lh/photo/RN4cUmOanah5vXPEJVP_oQ?feat=embedwebsite'><img src='http://lh4.ggpht.com/_TZMojZ6BS9g/THlTTfxVkrI/AAAAAAAAABg/ej5-crVkvEs/s800/Mixer.png' /></a>

It's based on the abs TrancheConsole\_abs available in /z\_usefull\_abs, there is a VU and a NoVu version (for CPU usage),the version in this patch is a copy/paste of the Mixer.pd available in the same folder. Each bus name is diplayed, under that a toggle let's you control the volume through your midi input hardware (you may need to change value of ctlin argument, according to your hardware). You can mute and solo each track, you can also enable/disable Vu. Sliders are from 0 to 1.2 linear.

You can send audio to any Bus creating an object **_throw~ BusX_** or using **_AudioBus_**.
You can choose to send each track directly to the output module by clicking the appropriate toggle or choose to wire some effects thus patching to the **Output Module**