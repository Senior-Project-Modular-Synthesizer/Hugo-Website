+++
draft = true
title = 'Module Types'
+++

A modular synth is made up of different modules, each with a simple function. This page covers the different types of modules and what they do.

## Oscillators
Oscillators are the sound source of a modular synth. They generate a waveform that can be shaped and modulated to create different sounds. The basic waveforms are sine, square, triangle, sawtooth, and noise. Each waveform sounds different.
    
{{< bordered-figure src="/img/Waveforms.png" alt="Waveforms" >}}

Think of waveforms as the most basic sound. They are the building blocks of all sounds.

### Voltage Controlled Oscillators (VCOs)
Voltage Controlled Oscillators (VCOs) are the most common type of oscillator. They generate a waveform with a frequency that can be controlled by a voltage. For every 1 volt increase, the frequency goes up an octave (which doubles the frequency).

### Frequency Modulation (FM) Oscillators
Frequency Modulation (FM) Oscillators are a type of oscillator that can modulate the frequency of another oscillator. 

## Filters
Filters are used to shape the sound by removing certain frequencies. The most common types of filters are low-pass, high-pass, band-pass, and notch filters. Each filter type removes different frequencies from the sound.

## Envelope Generators
Envelope generators are used to shape the amplitude of a sound over time. The most common type of envelope generator is the ADSR envelope, which stands for Attack, Decay, Sustain, and Release. Each stage of the envelope controls a different aspect of the sound's amplitude.
- Attack: How quickly the sound reaches its maximum amplitude.
- Decay: How quickly the sound drops to the sustain level.
- Sustain: The level of amplitude while the note is held.
- Release: How quickly the sound fades to silence after the note is released.
  
## Low-Frequency Oscillators (LFOs)
Low-Frequency Oscillators (LFOs) are used to modulate other parameters of the sound. They generate a waveform at a low frequency (usually below 20 Hz) that can be used to modulate parameters such as pitch, filter cutoff, and amplitude.

## Voltage Controlled Amplifiers (VCAs)
Voltage Controlled Amplifiers (VCAs) are used to control the amplitude of a sound. They take in an audio signal and a control voltage, and output the audio signal at a level determined by the control voltage.