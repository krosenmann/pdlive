These are patchs that uses data as input and or output (they do not produce audio signals). They are used to sequence actions read midi files, transform your keyboard into a virtual piano or do analysis of data (markov chain),or generate data (generating scales, or chords).


---

**Algo\_InterpolateChords.pd**



---

**Algo\_klangfarbenmelodie.pd**


---

**Algo\_MarkovChains.pd**


---

**Algo\_PianoPhase.pd**


---

**Algo\_ToneRow.pd**


---

**Bonk&Fiddle\_Analysis.pd**


---

**Chords2Notes.pd**


---

**DSControl.pd**


---

**Generating\_Scales.pd**

<a href='http://picasaweb.google.com/lh/photo/JEbnwB7iwnd4N5NjMf0a4g?feat=embedwebsite'><img src='http://lh4.ggpht.com/_TZMojZ6BS9g/THvLw_ahBiI/AAAAAAAAACc/IZydMkCxbgA/s800/GeneratingScales.png' /></a>

> enables you to generates scales according to predefined messages, first select your metro then bang one message, by default each bang 	will produce a couple note velocity, then the output goes into a ProbaGate to decides wether it passes on the message or not. After that a 	note and vel messages can be sent to any synth patch.


---

**Markov\_Analysis.pd**


---

**MIDI\_FX\_Apegiator.pd**

> an arpegiator that receives a midi note and ouputs 3 midi notes delayed and transposed.


---

**MIDI\_FX\_Chorder.pd**

> a midi note and output 4 midi notes according to a chording interface random arrangements could be used.


---

**MIDI\_FX\_CreateGlissando.pd**

<a href='http://picasaweb.google.com/lh/photo/Jtw2nVXmTT2K-Ov8_j-Rsw?feat=embedwebsite'><img src='http://lh6.ggpht.com/_TZMojZ6BS9g/THvLw1f3CTI/AAAAAAAAACg/QwepeAx_Vrc/s800/Glissando.png' /></a>

> create a glissando towards the input midi note 	over a controlable time.


---

**MIDI\_FX\_DrawingControlChange.pd**

> enable you to draw on a table the envelope of a control change parameter. This functioned is featured in the main patch.


---

**MIDI\_FX\_ProbaGate.pd**

<a href='http://picasaweb.google.com/lh/photo/QRtS3E63k4SY5LMdQOYOWA?feat=embedwebsite'><img src='http://lh3.ggpht.com/_TZMojZ6BS9g/THvL6zJkKmI/AAAAAAAAACw/Hz83wtAhogk/s800/ProbaGate.png' /></a>

> decides wether it will send the input midi note to the output using "probabilities".



---

**MIDI\_Generative\_HarmonicTrees.pd** :

> is a generator of midi notes synched to the MasterMetro, notes are sorted by an harmonic tree and then sent via the send object.


---

**MIDI\_KeybVsPiano-az-help.pd**

<a href='http://picasaweb.google.com/lh/photo/lh0gpJs5JiQOWJlt8Tu2aQ?feat=embedwebsite'><img src='http://lh6.ggpht.com/_TZMojZ6BS9g/THvLxD-O_UI/AAAAAAAAACk/BsNwOn3Yx04/s800/Keyboard.png' /></a>



---

**MidiFileSeq-help.pd**

<a href='http://picasaweb.google.com/lh/photo/6Y-8SOnnsGbdyA4hkEnSnQ?feat=embedwebsite'><img src='http://lh3.ggpht.com/_TZMojZ6BS9g/THvLxYH6dfI/AAAAAAAAACo/8kaXC7b1pu4/s800/MidiFile.png' /></a>

> this is a midi-file player, it pretty self explanatory, outlet corresponds to each message from left to right, top to bottom the first one is the 	equivalent to all others packed .



---

**Musical\_Score.pd**


---

**Musical\_Structure&Scales.pd**

> enables you to create musical structure and force playing into a chosen scale. You can choose a bar depth, the patch will then change 	scale every bar.


---

**OSC\_Android\_andOSC.pd**


---

**OSC\_Android\_Fingerplay.pd**


---

**pdL8-Matrix\_Sequencer.pd**

<a href='http://picasaweb.google.com/lh/photo/vMexFaigUtTbtlCyQeQWuA?feat=embedwebsite'><img src='http://lh3.ggpht.com/_TZMojZ6BS9g/TIkwdaGoOEI/AAAAAAAAAD8/nuQxKA4kQLk/s800/pdl8-matrix.png' /></a>


---

**pdL16-Note\_Sequencer.pd**

<a href='http://picasaweb.google.com/lh/photo/jcnKtCjqhBDq85_mkEDW7g?feat=embedwebsite'><img src='http://lh3.ggpht.com/_TZMojZ6BS9g/TIkwdiXrh0I/AAAAAAAAAEA/t2bZMgqmx3A/s800/pdl16-notesequencer.png' /></a>


---

**SEQ\_MIDI\_32StepNote+Vel.pd**

> is two 32 step sequencers synched together and to the MasterMetro, with velocity values. Notes and vel values for each step are sent 	via the send object.


---

**SEQ\_MIDI\_303seq.pd**

<a href='http://picasaweb.google.com/lh/photo/QI7QvpG8J-YID70W0Q_h5A?feat=embedwebsite'><img src='http://lh4.ggpht.com/_TZMojZ6BS9g/THvLwom-38I/AAAAAAAAACY/47RPgYwz_nw/s800/303Seq.png' /></a>


---

**SEQ\_MIDI\_Generative\_Probabilistic.pd**

> uses probability to decide wether a note is played or not in a score.


---

**SEQ\_MIDI\_Generative\_Random16Step.pd**

> is a 16 step sequencer with velocity, 	possibility to 	load pattern from files, randomise functions and a probability 	function to decide 	wether it will play a note or not.


---

**SEQ\_MIDI\_NoteSequencer.pd**

<a href='http://picasaweb.google.com/lh/photo/P7ZEzleEBMTZ343EcTxOEQ?feat=embedwebsite'><img src='http://lh4.ggpht.com/_TZMojZ6BS9g/THvL6o4un0I/AAAAAAAAACs/284Ll9JYfCQ/s800/NoteSequencer.png' /></a>



---

**SEQ\_MIDI\_pianoroll.pd**


---

**SEQ\_MIDI\_SynchroSequencers.pd**

> are remote controllers for your midi instruments you'll have to enter midi notes and velocity values for each notes, it's synched to the Master Metronome.


---

**SEQ\_MIDI\_TableSequencer16Steps.pd**



---

**SEQ\_QTrack.pd**

<a href='http://picasaweb.google.com/lh/photo/lcpXVCG5LU3RD0WE69YfcA?feat=embedwebsite'><img src='http://lh4.ggpht.com/_TZMojZ6BS9g/THvL6-q5v6I/AAAAAAAAAC0/gn59nOTGIig/s800/Qtrack.png' /></a>

