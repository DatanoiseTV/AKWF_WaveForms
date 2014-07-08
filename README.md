AKWF-WaveForms
==============

AKWF Single-Shot Waveforms as Signed 16-bit Integer C-Headers for use in Wavetable Synthesis.

All samples are resampled From D2+2 (which equals 600 samples) to 256+1 Samples for use on the Teensy 3.1.
These audio waveforms have a period of 256 points, plus a 257th point that is a duplicate of the first point.
This duplicate is needed because the waveform generator uses linear interpolation between each point and the next point in the waveform.

![Waveforms](./preview.png?raw)

All waveforms visualized: http://www.adventurekid.se/AKRTfiles/AKWF/view/waveforms_index.html
