# How to use these Abstractions

## Control

### MIDI file reader
*No inlets*

**Outlets**

*To be done*

**Controlers**
- `Open MIDI`: opens dialog box for choosing MIDI file and automatically reproduces it
- `Stop`: stops MIDI reproduction
- `Play`: plays MIDI file, already loaded
- Volume knob


## Envelopes

### ADSR
**Inlets**
- Left: numerical, amplitude of the signal
- Right: numerical, frequency of the signal

**Outlets**
- [vline~]

**Controlers**
- Attack: `range = (0.001, 3)` seconds, linear
- Decay: `range = (0.001, 3)` seconds, linear
- Sustain: `range = (0.1, 1)` amplitude, linear
- Release: `range = (0.001, 5)` seconds, linear

### Linear Random Envelope
