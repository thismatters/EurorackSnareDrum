# Snare Drum


The circuit here is an implementation the circuit in the [Moritz Klien snare drum video](https://www.youtube.com/watch?v=hULEn2_4Unw) with all the trappings to make it a proper module. I recommend that video completely, please watch it. The circuit has 5 knobs, but I've limited myself to 4 knobs: Decay, Attack, Tone, and Pitch. The other knob is present as a screw-turn potentiometers accessible from the front panel for tuning Snappy.

The KiCAD project here uses the library/footprints [found in my companion repo](https://github.com/thismatters/EurorackKiCAD).


## Width

6hp on a standard 3U rack.

## Inputs

4 Jacks
- Gate
- Accent CV
- Snappy CV
- Pitch CV

4 Knobs:
- Decay
- Attack
- Tone
- Pitch

1 Screw Pot (accessible from front):
- Snappy

## Outputs

1 Jack for audio output.

## Vendors

There are part numbers in the [BOM](snare-drum.csv) for many of the parts (not for basic passives though) at the following vendors:

* [Mouser](https://www.mouser.com): Needs no introduction. Get your ICs from here (or [digikey](https://www.digikey.com)).
* [Tayda Electronics](https://www.taydaelectronics.com/): Good supplier for passive components; audio jacks, and potentiometers. Their audio jacks are slightly smaller than the thonkiconn from thonk.
* [Love My Switches](https://lovemyswitches.com/): Has [really good knobs](https://lovemyswitches.com/anodized-aluminum-knob-the-lo-fi-1-4-smooth-shaft-12-5mm-od/) to go on those potentiometers!
* [OSHPark](https://oshpark.com/): Fast and (relatively) cheap PCB manufacturer. Prototype run pending.


## Changelog
