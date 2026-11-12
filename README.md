# Inverse Filter Lab

A browser-based inverse filtering tool for voice pedagogy, made by Chadley Ballantyne, Stetson University. A companion to the Vowel Synth Lab.

Sing into the microphone (or load an audio file, or use the built-in demo voice), freeze a few cycles, and remove the vocal tract's resonances one at a time to see the glottal flow underneath.

- Five anti-resonance filters (fR1 to fR5), set by sliders or by dragging handles on the spectrum
- Auto estimate: linear prediction after a first-pass glottal tilt removal (a simplified IAIF), then fine-tuned to make the closed phase as flat as possible
- Glottal flow, flow derivative, input waveform and spectrum, synced to glottal closures
- Low-frequency correction for microphones that roll off the bass
- Demo voice with known resonances, using the same Liljencrants-Fant source as the Vowel Synth Lab

In the tradition of Sopran and Svante Granqvist's interactive inverse filtering.
