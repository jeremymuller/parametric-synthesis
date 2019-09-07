# Parametric Synthesis

Parametric synths in Pure Data based on Perry Cook &amp; Gary Scavone's Synthesis Toolkit ([STK](https://ccrma.stanford.edu/software/stk/)).

There are two versions of the patches:
1. As an abstraction to be used as an object in your patch.
2. As a GUI specifically designed to be used with [AUTOMATONISM](https://www.automatonism.com/)

**All inlets take input ranges from 0-127 in order to work nicely with MIDI. The left-most inlets can also take 'init' and 'rand' messages to set initial values or randomize, respectively.**

* blow~ inlets: pressure, pitch, noise

* bow~ inlets: pitch, _bow velocity_, bow pressure, bow position, noise  
_bow velocity_ = anything above 64 is one bowing direction while anything below 64 is the opposite direction.

* modal~ inlets:

* pluck~ inlets: `bang`/pitch/`double` string/`single` string, velocity, pick sound, position, dampening

* shake~ inlets:
