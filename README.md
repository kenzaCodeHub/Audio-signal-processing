# Audio Signal Processing — Filtering with ThinkDSP

Hands-on exploration of audio signal processing fundamentals: waveform visualization, spectrum analysis, and frequency filtering using the [ThinkDSP](https://github.com/AllenDowney/ThinkDSP) library.

## What This Notebook Covers

1. **Waveform analysis**: load a WAV file, normalize, and visualize the time-domain signal
2. **Segmentation**: extract a 5-second segment and zoom into a 5ms window to observe individual oscillations
3. **Spectrum analysis**: compute the frequency spectrum (FFT) and plot frequencies up to 1000 Hz
4. **Low-pass filter**: remove frequencies above 2000 Hz to isolate bass and mid-range content
5. **High-pass filter**: remove frequencies below 50 Hz to eliminate low-frequency noise

## Tech Stack

Python, ThinkDSP, Google Colab

## Reference

Allen Downey — [Think DSP: Digital Signal Processing in Python](https://greenteapress.com/wp/think-dsp/)
