# A compilation of Pure Data abstractions I've created

## Databend

Loads any file as a sound (including binary files), slices it into a number of sections, and plays glitchy grains from those sections. See `test_patch.pd` for instructions.

## Drum sequencer

Quantizes played drums and samples in real time. Has velocity support and a metronome. See `test_patch.pd` for instructions.

## Recorder

Records multiple sounds (either mono or stereo) to its own file, just like a real recorder, so you can mix your composition later. Also displays the duration of the recording. See `test_patch.pd` for instructions.

#### Tip: some abstractions may not work properly without the `u` folder, which stands for `utils` and contains some useful tools that I often use to build patches.