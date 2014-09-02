![Disorient frontage](https://farm6.staticflickr.com/5576/15120420272_2e28c9a568.jpg)
October First committee mission:
================================

Our goal is to enable artists, not to dictate art ideas.  We want to
present our creative collaborators with a menu of proven components
and to encourage them to incorporate these items into their designs early
in their artistic process.

Additionally, we want the "worker bees" to be able to quickly assemble
the art pieces on playa during the first few days of build week and then
enjoy the party.  Common components, connectors and modular design make
this easier.


Topics
======

![Playa Proven!](https://farm6.staticflickr.com/5569/14921564917_2c1db67795.jpg)
* Playa-proven control hardware
  -  LEDscape boards have worked well
  -  Toughbooks (not fast, but cheap)
  -  BeagleBone Blacks (no fans, no failures)
  -  Teensy (but not their USB ports)


* Flexible software
  -  LEDscape receiver (OPC, UDP, replay from card, etc)
  -  Processing?  Too slow on old toughbooks.
  -  Projection mapping?
  -  Audio/kinect/etc inputs?
  -  Visualization?
  -  Calibration?
  -  Communication between pieces?


* Common connectors: pick a few to standardize on
  -  Cat5: cheap, fairly robust, readily available, ok density (8 conductors)
  -  XLR: very robust, available, low density (3 conductors, huge plugs)
  -  Amphenol: not widely available, water proof, highly robust
  -  JST: cheap, not as available, decent density, not robust
  -  Molex: not readily available, not robust
  -  Screw terminals: high amperage, easy to adapt, slow to assemble
  -  USB: readily available, but insufficiently robust (mechanically
and electrically).  Just say no.


* Power supplies
  -  Need to find and test some sealed supplies.
  -  Just say no to fans?
  -  Higher voltage at the supply and regulate at each component?


* Enclosures
  -  Ammo boxes: cheap, not quite waterproof, but ok.
  -  Pelican cases: not cheap, very waterpoorf.
  -  Bare boards: suprisingly few failures


* Modular components
  -  Misumi extrusion ($/m ?), need library of brackets
  -  M3/M4/M5 hardware everywhere
  -  Avoid screwing to wooden structures -- too much MOOP.
  -  Pipe and u-bolt clamps
  -  How to build art pieces in modular ways (easier packing and assembly)


* No soldering on Playa
  -  even with flux it is difficult.
  -  and turns into a time sink


* Output technologies
  -  LED panels: we need to test outdoor models
  -  LED strips: if we can find good ones, otherwise just say no.
  -  Mechanical actuators: which are well sealed and which can we drive?
  -  DMX (traditional dimmer packs and new LEDs)
  -  Relays (for AC loads, etc)
  -  Projectors
  -  Lasers / pan-tilt stages
  -  Fire
  -  UAVs
  -  Difusers (soft and rigid)
  -  Edge lighted materials
  -  Fog/mist machines


* Interactivity
  -  Audio inputs from DJ
  -  Directional microphones for audience
  -  Kinnect / Depth sensors
  -  Video
  -  Proximity
  -  Touch
  -  Laser trip wire
  -  Communication between art pieces


* Connectivity
  -  Ethernet
  -  Ad-hoc wifi networks
  -  Multi-drop serial
  -  Support daisy chainable wiring when possible.
