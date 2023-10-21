# MIDI Fixed Note Length

A JSFX (Reaper) module to set fixed length of incoming notes; useful for lengthening MIDI signals from drum triggers for use with VST instruments.


## Inspired by

This effect is based on work [shared on the Cockos forums by user mwe](https://web.archive.org/web/20231021155326/https://forum.cockos.com/showpost.php?p=1220610&postcount=13).
That code is saved for reference in this repo as `mwe_original.jsfx`.


### Changes

The original by _mwe_ could only shorten notes, not lengthen them (original note off signals passed through).
This version will truly fix note length, even for shorter incoming signals.
