# Fuzzelo

![Betsy the Buggalo](https://gamepedia.cursecdn.com/futuramaworldsoftomorrow_gamepedia_en/8/8a/Mission_The_Buggalo_Bond.png?version=6296effb747ab478a2fd876bd3014b79) 

The `Fuzzelo` is an MXR Dist+-based tremolo pedal, with the distortion knob replaced by an LFO-varied resistor. The LFO circuit uses the [StompLFO chip](https://electricdruid.net/datasheets/STOMPLFODatasheet.pdf) from [Electric Druid](https://electricdruid.net/product/stomplfo/). 

## Controls
### Volume 
Controls the output of the pedal. Does not change the gain or frequency response.

### Rate
Controls the rate (frequency) of the LFO. The StompLFO provides rates from as slow as 20 s up to 40 ms (38 BPM to 1500 BPM, or 0.05 Hz to 25.6Hz).

### Offset
Controls the offset or bias of the LFO wave. 

### Depth
Controls the amplitude of the LFO. At 0 depth, there is no change between minimum and maximum peaks during the LFO-period.

---

Note: `Offset` and `Depth` are interactive. They can be thought of as floor and ceiling for LED-brightness for the LFO, as well. By raising the offset, the lower limit of the "off" section of the wave can be raised. By lowering the depth, the upper limit of the "on" portion of the wave can be set.

---

### Waveform
Controls the waveform of the LFO, covering: Ramp Up, Ramp Down, Square, Triangel, Sine, Sweep, Random Levels and Random Slopes.
![Waveforms Ramp Up, Ramp Down, Square, Triangel, Sine, Sweep, Random Levels and Random Slopes](waveforms.png)

## Uses and Common Settings

### Full fuzz
Setting `Offset: 0, Depth: 0` yields an always-off signal, giving a cleanish tone.
Setting `Offset: 1, Depth: 0` yields an always-on signal, giving a full distored tone.
Setting Offset anywhere in between yields distortion of similar intensity.

### Choppy Tremolo
Setting `Offset: 0.25, Depth 0.25-0.3` yields a slight "breathing" LED, giving a very choppy
distorted/clean transition. Setting `Offset: 0.75` yields the opposite effect.

### Textured fuzz
Setting `Offset: 0.6, Depth: 0.25, Waveform: Random` yields a very subtly textured fuzz, 
with almost impercetible warble.
