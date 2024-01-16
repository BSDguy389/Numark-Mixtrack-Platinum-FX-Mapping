# Numark-Mixtrack-Platinum-FX-Mapping
Mixxx DJ Controller Mapping for Numark-Mixtrack-Platinum-FX


Welcome to the Numark-Mixtrack-Platinum-FX-Mapping wiki!

This is a project based on the Numark Mixtrack Platinum from Matthew Nicholson. Thank you for your superb work Matthew! https://github.com/mixxxdj/mixxx/wiki/numark_mixtrack_platinum

This is an improved version for my personal needs.

Here are the changes I've made to the original mapping, using Mixxx's MIDI learning feature :

- Corrected an error in the original XML file that prevented the mapping to load, causing Mixxx to display an error message about line 5.
- FX BEATS knob : headphone mix min/max
- FX TAP button : starts/stops Auto DJ
- FX pads : the first 3 ones toggle FX unit 1 effect slots, the 4th, 5th and 6th ones toggle FX unit 2 effect slots
- Left and Right Hold/On switches : the left one activates/stops recording, the right one toggles Shuffle the content of Auto DJ queue
- CUE GAIN knob : headphones vol.
- CUE MIX knob : FX unit 2 Super Knob
- Performance Pads :
    - CUE : goes to CUE
    - AUTO LOOP : Sync and Reset Key
    - FADER CUTS : Adjust Beats Earlier
    - SAMPLE : Adjust Beats Later
    - STUTTER : Beat Roll 1/2
    - Previous Track : Beat Roll 1/4
    - Fast Backward : Hot CUE 1
    - Fast Forward : Hot CUE 2
- IN : Start of Loop
- OUT : End of Loop
- LOOP : Exit Loop

This mapping is fully set for the controller's four decks.
Only the VU meters and the % and pitch lines in the LCD screens don't work in the original mapping. BPM and Time are siplayed correctly in the LCD screens.

About SHIFT button : I couldn't make it work, Mixxx sees the SHIFT button as a MIDI signal in itself if I try to remap this button, can't use it to add secondary functions to buttons. It's still used to switch from deck 1 to deck 3 on the left side of the controller, and from deck 2 to 4 on the right side.
