# Raspberry Pi Pico Libraries

A collection of C libraries I've written for, or ported to, Raspberry Pi Pico (RP2040) and Raspberry Pi Pico 2 (RP2350) with their SDK.

### Audio and music

[Sequencer Synth](https://github.com/TuriSc/Pico-Sequencer-Synth)  
A polyphonic, multitimbral DDS (Direct Digital Synthesis) library with a sequencer supporting up to 8 channels.

[I2S Audio Mixer](https://github.com/TuriSc/RP2040-I2S-Audio-Mixer)  
Audio mixer library allowing playback of audio samples through an I2S DAC. Multiple samples can play simultaneously, and their volume can be adjusted individually.

[pico_synth_ex](https://github.com/TuriSc/RP2040-pico_synth_ex)  
Polyphonic synth engine with envelope, filter and LFO.
Ported from [pico_synth_ex](https://github.com/risgk/pico_synth_ex) by Ryo Ishigaki.

[PWM DMA Audio](https://github.com/TuriSc/RP2040-PWM-DMA-Audio)  
Library that allows audio samples to be played through PWM.
Forked from [pico-audio-demo](https://github.com/moefh/pico-audio-demo) by Ricardo Massaro.

[PWM Tone](https://github.com/TuriSc/RP2040-PWM-Tone)  
Tone generation library. Plays melodies and chirping sounds via PWM through a buzzer or speaker.

[DFPlayer](https://github.com/TuriSc/RP2040-DFPlayer)  
Play Mp3 and Wav files and control a DFPlayer mini (or a clone like MP3-TF-16P).

### I/O

[Keypad Matrix](https://github.com/TuriSc/RP2040-Keypad-Matrix)  
Keypad matrix polling. Multiple keypads can be used simultaneously. It detects short and long key presses.

[Rotary Encoder](https://github.com/TuriSc/RP2040-Rotary-Encoder)  
Efficiently read rotary encoder signals.

[Button](https://github.com/TuriSc/RP2040-Button)  
Button debounce library. It generates interrupts after listening to GPIO_IRQ events. It allows to define multiple buttons simultaneously. Forked from [jkroso/pico-button.c](https://github.com/jkroso/pico-button.c).

[Menu System](https://github.com/TuriSc/Pico-Menu-System)  
Create hierarchical menu systems with action items and submenus, support for long menus, and customizable draw callback.

[Linear Hall Effect](https://github.com/TuriSc/Pico-Linear-Hall-Effect-Sensor)  
Read values from Linear Hall Effect Sensors like OH49E, with calibration and smoothing. Multiple sensors can be managed simultaneously.

[MUX74HC4067](https://github.com/TuriSc/Pico-MUX74HC4067)  
Read and write multiple signals with 74HC4067 multiplexer/demultiplexer. C port of [nlamprian/MUX74HC4067](https://github.com/nlamprian/MUX74HC4067/).

[WS2812B Animation](https://github.com/TuriSc/RP2040-WS2812B-Animation)  
Display animated effects on WS2812B LED strips and matrices, with custom charset and i18n font, and procedural effects.

[SSD1306](https://github.com/TuriSc/pico-ssd1306)  
OLED display library, fork of [daschr/pico-ssd1306](https://github.com/daschr/pico-ssd1306). I implemented display rotation and a few other features.

### Utilities

[Moving Average](https://github.com/TuriSc/RP2040-Moving-Average)  
Implementation of the moving average filter. Forked from [mhtb32/EfficientMovingAverage](https://github.com/mhtb32/EfficientMovingAverage).

[Battery Check](https://github.com/TuriSc/RP2040-Battery-Check)  
Measures the voltage level on the VSYS pin. Useful for low-battery detection. 

