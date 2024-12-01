# Raspberry Pi Pico Libraries

A collection of C libraries I've written for, or ported to, Raspberry Pi Pico (RP2040) and Raspberry Pi Pico 2 (RP2350) with their SDK.

### Audio and music

[Sequencer Synth](Sequencer%20Synth)  
A polyphonic, multitimbral DDS (Direct Digital Synthesis) library with a sequencer supporting up to 8 channels.

[I2S Audio Mixer](I2S%20Audio%20Mixer)  
Audio mixer library allowing playback of audio samples through an I2S DAC. Multiple samples can play simultaneously, and their volume can be adjusted individually.

[pico_synth_ex](pico_synth_ex)  
Polyphonic synth engine with envelope, filter and LFO.
Ported from [pico_synth_ex](https://github.com/risgk/pico_synth_ex) by Ryo Ishigaki.

[PWM DMA Audio](PWM%20DMA%20Audio)  
Library that allows audio samples to be played through PWM.
Forked from [pico-audio-demo](https://github.com/moefh/pico-audio-demo) by Ricardo Massaro.

[PWM Tone](PWM%20Tone)  
Tone generation library. Plays melodies and chirping sounds via PWM through a buzzer or speaker.

[DFPlayer](DFPlayer)  
Play Mp3 and Wav files and control a DFPlayer mini (or a clone like MP3-TF-16P).

### I/O

[Keypad Matrix](Keypad%20Matrix)  
Keypad matrix polling. Multiple keypads can be used simultaneously. It detects short and long key presses.

[Rotary Encoder](Rotary%20Encoder)  
Efficiently read rotary encoder signals.

[Button](Button)  
Button debounce library. It generates interrupts after listening to GPIO_IRQ events. It allows to define multiple buttons simultaneously. Forked from [jkroso/pico-button.c](https://github.com/jkroso/pico-button.c).

[Linear Hall Effect](Linear%20Hall%20Effect%20Sensor)  
Read values from Linear Hall Effect Sensors like OH49E, with calibration and smoothing. Multiple sensors can be managed simultaneously.

### Utilities

[Moving Average](Moving%20Average)  
Implementation of the moving average filter. Forked from [mhtb32/EfficientMovingAverage](https://github.com/mhtb32/EfficientMovingAverage).

[Battery Check](Battery%20Check)  
Measures the voltage level on the VSYS pin. Useful for low-battery detection. 

### Various
[WS2812B Animation](WS2812B%20Animation)  
Display animated effects on WS2812B LED strips and matrices, with custom charset and i18n font, and procedural effects.
