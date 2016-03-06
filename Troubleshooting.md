
---

**No sound ?**

---


_1_- check the DSP on the output module, if it's not orange it means that pd will not calculate any audio, so click to toggle dsp.

_2_- most of those patchs come with an ALD envelope (Attack, Length, Decay) be sure to initialise it to produce sound. After the sound goes to the the mixer according to the Bus you selected (if on windows proceed to step 3), then it's routed to the ouput of the mixer object or directly to the output, so check if you have any direct output : if yes, you need to check Fx routing, if not check the patch (it may not work on your system)

_3_- the popup object isn't supported under Windows, so the AudioBus to send to will not be selected by the popup menu, you'll need to replace the AudioBuses by the one using numbers in /z\_usefull\_abs/AudioBuses.pd.


---

**Problem loading objects ?**

---


there is a few dependencies, check your console output to see if you miss something and email me any pb. There is also a few problems with certain objects considering OS (spigot~ and popup on windows, fluid~ on osx).

- Latest **stable** release of Pd-extended is recommended.

- Percolate library is needed for the Synth/Midi\_PercolateInstruments/ folder (sources http://puredata.hurleur.com/sujet-619-port-percolate). OSX sources are included.

- Soundhack externals located in FX/Soundhack check the sources for your operating system at : http://www.soundhack.com/externs.php . OSX sources are included.