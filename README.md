Shapeshifter Tips + Tricks
==========================

- Percussion mode: plug a gate signal into the 'sync' jack; simple envelope is triggered and modulated with decay control. In this mode
  you can also use the built-in delay, whose time is modulated by the pitch of oscillator 2. Osc 2 pitch can be modulated by
  the ratio control knob or MODB. Make sure LFO mode is enabled for OSC2.

- You can modulate the decay for all presets using the MODB bus. To enable this, press the DETUNE/DCAY button twice. 
  This will map the DECAY setting to the MODB signal. You can either use the MODB input or just play with the MODB 
  knob to vary the DECAY values while stepping through the presets.

- When you press SAVE while in preset step mode it will just take you out of step mode. You have to press SAVE again. 
  This will give you the confirmation display (Yes or No). Select Yes or No and then press SAVE once more.

- With osc2 in LFO mode, turn up the MODA attenuator knob. With nothing plugged into the MODA jack this phase modulates 
  osc2 with osc1, and makes out1 and out2 into a nice stereo mix. 

- Turn QUANT on and play with the RATIO knob to get nice FM sounds with INT. FM turned up. 

- Try different MULTI settings with the wavebank set to one of the Chip or 2Tone banks. 
  Play with (or modulate) the Shape controls. 

- With osc1 set to a sine wave (Basic1 bank, shape1 fully ccw) use an envelope to modulate the TILT parameter. This gives a nice acoustic bass. 

- When playing with the preset morph or stepping, make presets that are either very similar to each other, or very different from each other. 

- Different chords are cool when using preset morphing. 

- Reverse sync can make harsh sounds smoother 

- Hold sync gives nice gating effects 

- Put osc2 in lfo mode and use out2 as a modulator for everything and anything. 

- With osc2 in lfo mode use the ring mode combo mode to get cool envelope effects 
  (good in perc mode - the lfo is synced to the attack so osc2 becomes another envelope for osc1) 

- With OSC2 in LFO mode, patch it into Mod A while in Vocoder mode. Activate Chord mode. 
  Set the OSC2 Multi value to something greater than 1 and play with the ratio to get a nice complex modulation source. 
  It can sound even better if OSC1 is also in LFO mode. 

- With OSC2 in LFO mode patch it into the FOLD input. Now adjust the FOLD amount and take the output back to the FM1 (or any other mod input). 
  It creates really complex modulation that can vary in interesting ways depending on the amount of folding. 
  Some of the LFO wavebanks work really well for this. 

- With percussive mode active you get an overall amplitude decay on OUT1. You can use OSC2 in LFO mode as a second envelope if you select wavetablebank:LFO3. 
  It will cycle so make sure to dial in a frequency that works with your decay value of the percussive envelope. Patch OSC2 into FM1 to modulate the pitch. 
  Use a trigger at the sync input to trigger and sync both percussive envelopes (pitch and amplitude). 
  It makes great kick drums which you can morph into other percussive sounds.

- Euro synthpop bass sounds: 
  - Chord mode on, with chord type set to unison 
  - Detune set to 02       
  - Perc mode on 
  - Decay set to 62 
  - Overdrive set to max (99) 
  - Echo set to 35 (or as high as 45) 
  - Osc 2 set to LFO, with an unconnected cable plugged into Pitch2 
  - Adjust the Ratio knob to match the echo time to your song tempo 
  - set Quant off 

- Wavetable grains: set the Shapeshifter into Perc. Mode, and plug the Pulse output into the Sync input.

- Here's a quick n' dirty example of using the Shapeshifter as a LPF/BPF: 
  - The actual Osc sounds comes from an AFG, patched into the SS Mod A input. 
    This input is set to be the Vocoder Carrier signal. 
    The SS Osc A waveform functions as our Vocoder modulator and is set to a bright two tone waveform. 
    Percussion mode is used to give an envelope shape to Osc A, our Vocoder modulator and the freq of Osc A and it's waveshape are both modulated by an Env and an Lfo. 
    Although we don't hear Osc A from the SS, it's the changing amplitude, freq, and timbre of Osc A that imparts our AFG analog waveforms with the filter/phaser sounds. 

- All vocoders take some care to get good sound out of them. The choice of carrier waveform is important, and the input should be clean and undistorted (keep the levels down). 
  You want a carrier that has a lot of harmonics otherwise the low end gets emphasized.

- Try using an envelope follower (i.e. Maths) to modulate Shapeshifter, esp for vocoder tasks!

- ModA is specifically for audio modulation, it's AC coupled and sampled at a higher rate (98 KHz). You can use it as a modulator for the vocoder, 
  or you can route it to modulate the phase of OSC2 (Phasemod), combine it with OSC1 output (Combo in) or use it to address the wavetable of OSC2 - 
  the latter is similar to processing external signals with Piston Honda or Megawave (with the difference being that Megawave input is DC coupled so can be used as a quantizer, 
  not sure about PH). You can get interesting results similar to wavetable morphing by morphing the external audio, if you have an oscillator that does wave morphing. 
  Also cool for processing drums etc for distortion like effects.

- Running Maths ch1 self cycling into aux1 gate length 
  Maths ch4 into aux2 octave of the metropolis. 

- When you press combo twice (or any of the other right hand buttons), this adds that parameter to the MODB bus. 
  This means that the parameter is now being modulated by the MODB control and input, allowing voltage control. 
  The left numbers you see are the settings made with the rotary encoder, while the right numbers are the offsets to this setting made by the MODB modulation. 

- one way to use multi mode: try putting VCO2 in LFO mode (becomes LFO2) and the multi to something greater than 1. Now LFO2 will be a very complex but repeating shape, 
  like a complex multistage envelope. You can use sync to trigger this on beat. Have it modulate pitch or patch it out to modulate MOD B or the Fold parameters.
