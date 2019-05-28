# 3320VCF
Kicad project files of a CEM3320/AS3320 based VCF. Part of a modular DIY synth project, other modules to follow in other project folders. 

Used the Audio.lib from https://kicad.github.io/symbols/Audio to extend the Kicad library for the AS3320 component.

Designed to work with +/- 15V, but will most likely work fine for +/- 12V as well

The PCB is 9.5 x 5.5 cm and has no PCB-mounting of potmeters, switches, jacks; these are all connected by pin header connectors

Stages 1 and 2 are switchable between HP and LP mode by SW1 and SW2. 
Stages 3 and 4 are fixed on LP mode.
These allow for the following filter modes:
- A: 24dB LP
- B: 12dB BP
- C: 6dB HP + 18dB LP
- D: 6dB LP + 6dB HP + 12dB LP

Background of the mode configurations: https://electricdruid.net/multimode-filters-part-1-reconfigurable-filters/ section Craig Anderton’s Multiple Identity Filter.

Capacitors on pin 4, 5, 11 and 16 should be 1% or less tolerance! 

F1 and F2 fuses are not really required and can be replaced by shorts.
