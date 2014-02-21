pip_abstractions
================

Puredata patches for Game Audio.

=====================================================================
PIP ABSTRACTIONS - TINY PATCHES FOR MAKING GAME AUDIO WITH PD EASIER!
=====================================================================

This bite-sized set of patches is specifically geared towards making
sound for games with Puredata, using Unity and libpd, for example.
Pip abstractions are vanilla and thus libpd friendly.

Included is a basic set of abstractions that can be used by the experimentally-inclined
game composer/sound designer to quickly test out some interactive music ideas, play some samples as sound effects,experiment with real time generated music and patterns and generally just have fun trying out PD as an audio engine for games! 

This is by no means an "advanced" collection of über-patches, but a little set of building blocks to spark the interest of PD beginners and game audio people curious about this great program.

Contents:

- simple envelopes for shaping volume of synths and samples (adsr and such)

- channel strip abstraction with send levels

- mixer abstraction (basically more channels in one for getting started quickly)

- couple of super simple synths to start experimenting with realtime generated music in games

- drum machine that loads samples and can store and change patterns depending on game state

- small object to connect unity with pd via kalimba

- tool to pitch samples depending on position in a song (useful for Mario Galaxy style sound effects that change depending on the harmony in the loop!)

- Fade logics for creating interactive music based on layers (additive and crossfade layer)

- simple limiter for preventing ears to explode

- couple of metronome abstractions (also with subdivisions)

- little NES style synth for chiptunes project

- piano phase inspired mini sequencer

- random object without repeat
- 
- mega simple sampler

=================

Filippo
mail@fbpsound.com

P.S. In order to use PD with Unity, you should download Kalimba:

https://github.com/hagish/kalimba


Thanks to: the Puredata Forums and PDlist for an amazing and alive community, Sebi Dorda for coding Kalimba, Peter Brinkmann for making libpd, RJ-DJ for their amazing toolset, Cheetomoskeeto for the Youtube Tutorials (highly recommended!)

