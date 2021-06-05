# Season of the Witch

The `Season of the Witch` is, at its core, a modulating digital delay pedal. The modulation can be accomplished via an LFO circuit, which uses the [StompLFO chip](https://electricdruid.net/datasheets/STOMPLFODatasheet.pdf) from [Electric Druid](https://electricdruid.net/product/stomplfo/), a TRS-capable expression pedal, or a 0-5V TS CV signal. The digital delay is driven by the [PT2399](https://www.electrosmash.com/pt2399-analysis), a common short-range delay chip. The range of usable delay times is approximately 35ms to ~500ms. Longer delay times are possible, but signal degradation is guaranteed beyond this range. Of course, if you were looking for normal-signal delay pedal, you probably would have bought a different one! 

The pedal includes standard delay controls: dry/wet `Blend`, amount of `Repeats` in the signal, the `Delay` time,  and a transparent `Boost` to add a little more body and drive to the signal, as well as two internal trimmers. Turn down the`Chaos` trimmer control to reign in or let loose the `Repeats`. The `Delay` internal trimmer controls how far the delay chip will be pushed: if you want dying computer noises, turn this setting _down_. Be warned, however, if the control signal goes too low, the delay chip will shut off completely. It also includes controls for the Modulating signal, which will be discussed in depth later: `Rate`, `Waveform` selection, and `Offset` and `Depth` controls for fine-tuned wave control.

There are three switches on the Season of the Witch as well: one for changing the delay time with the Control Signal, one for changing the amount of feedback with the Control Signal, and finally a phase switch for the feedback modulation -- in-phase, long delay times are paired with lots of feedback, and out-of-phase, short delay times are paired with lots of feedback.

When your signal combines with the Control Signal, the results can be otherworldly. Subtle variation of the Control Siganl produces warm, wavering sounds, much like a chorus pedal. Less than subtle variation produces wild, pitch-shifting, potentially-arpeggiated noises: changing the variation from gentle to almost unrecognizable.

---

## Controls

## Pedal Controls	

### Boost
Controls the amount of gain provided to the output of the blended signal. The boost is a transparent MOSFET boost inspired by the [AMZ Booster](http://www.muzique.com/schem/mosfet.htm). Maximum gain is nearly 40 dB, so use this wisely!

### Blend
Controls the amount of delayed signal in the output. Completely on will be nothing but delayed signal, completely off will be nothing but clean signal.

### Delay
Controls the delay time. The pedal is capable of self-oscillation at higher settings (depending on the `Chaos` setting).

#### Delay Trimmer
Internally, there is a trimmer for how far the delay signal can be controlled. Turn this _up_ for lower amounts of change in the delay time, and _down_ for more swing. **NOTE: If your delay signal dies, start here!**

### Repeats
Controls the amount of repeats in the signal. The pedal is capable of self-oscillation at higher settings (depending on the `Chaos` setting).

#### Chaos
Internally, there is a trimmer for the chaos avaiable in the `Repeats` knob. Turn it up to allow for easier self-oscillation, turn it down to avoid it altogether.

---

## Control-Signal controls

### Depth
Controls the maximum delay time - the maximum swing of the control signal.

### Offset / Delay-Time
Controls the minimum delay time.

> **NOTE**: `Offset` and `Depth` are interactive. They can be thought of as floor and ceiling for LED-brightness for the control signal, as well. By raising the offset, the lower limit of the "off" section of the wave can be raised. By lowering the depth, the upper limit of the "on" portion of the wave can be set.

### Rate
Controls the rate (frequency) of the LFO. The StompLFO provides rates from as slow as 20 s up to 40 ms (38 BPM to 1500 BPM, or 0.05 Hz to 25.6Hz).

### Waveform
Controls the waveform of the LFO, covering: Ramp Up, Ramp Down, Square, Triangel, Sine, Sweep, Random Levels and Random Slopes.
![Waveforms Ramp Up, Ramp Down, Square, Triangel, Sine, Sweep, Random Levels and Random Slopes](waveforms.png)

> **NOTE**: The `Rate` and `Waveform`  options only affect the LFO control, not the expression or CV control signals.

--- 

## Working with the Control Signals

You may have noticed that there are three Control signal options, but only one plug! The LFO is internal to the Season of the Witch, while both the Expression and CV share the same TRS jack. Expression pedals are expected to use a TRS cable as a voltage divider (therefore, a TS cable will not work appropriately) -- as an added benefit, the value of your expression pedal is irrelevant, so the Season of the Witch ought to be compatible with any-value TRS expression. CV sources are expected to provide a 0-5V signal over a TS cable (internal voltage is provided on the Ring of the TRS and may damage a TRS CV source!!).

With no controls plugged in, the LFO is the working Control Signal. Plugging any cable (TS or TRS) into the CV/Expression jack will cut-off the LFO signal and use whatever Control Signal is coming through the CV/Expression jack.

### LFO
There is a lot of variation within the LFO control. Not only do the 8 waveforms offer very different sounds for modulating, but each of the `Rate`, `Depth` and `Offset` controls can change the entire soudn with subtle variation. 

### Expression
For best use of the expression control, I advise picking your heel and toe settings before beginning play. Loosely, you can think of the `Offset` setting as mapping to the heel and the `Depth` setting mapping to the toe. Set the expression pedal to heel position, tweak the offset until you're happy with the beginning position. Then move to the full toe-down position, and change the `Depth` setting to set the amount of variation you'd like.

### CV
For best use of the CV control, the advice under `Expression` setting works as well: be sure you understand your minimum and maximum positions and how these affect the delay time and feedback. 

Interestingly, even within the variation there is still variation (#dune2021: plots within plots). For example, an "unusably seasick" wobble in delay time at a lower rate setting, can become a gooey, warm vibrato at higher `Rate` settings with enough dry signal `Blend`ed in.

## Uses and Common Settings
