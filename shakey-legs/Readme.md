# Shakey Legs

The `Shakey Legs` is, at its core, a modulated digital delay pedal. The modulation is accomplished via an LFO circuit, which uses the [StompLFO chip](https://electricdruid.net/datasheets/STOMPLFODatasheet.pdf) from [Electric Druid](https://electricdruid.net/product/stomplfo/). The digital delay is provided by the PT2399, a common short-range delay chip. The range of usable delay times is approximately 35ms to ~500ms. Longer delay times are possible, but signal degradation is guaranteed beyond this range. Of course, if you were looking for normal-signal delay pedal, you probably would have bought a different one! 

The pedal includes standard delay controls: dry/wet `Blend`, amount of `Repeats` in the signal, and a transparent `Boost` to add a little more body and drive to the signal. It also includes controls for the LFO, which will be discussed in depth later: `Rate`, `Waveform` selection, and `Offset` and `Depth` controls for fine-tuned wave control.

## Controls
### Boost

### Blend

### Repeats

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

### Sound 1

### Sound 2

### Sound 3
