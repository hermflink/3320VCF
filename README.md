# 3320VCF
Kicad project files of a CEM3320/AS3320 based VCF

Used the Audio.lib from https://kicad.github.io/symbols/Audio to extend the Kicad library for the AS3320 IC.

Designed to work with +/- 15V, but will most likely work fine for +/- 12V as well

No PCB-mounting of potmeters, switches, jacks; all connected by pin header connectors

Stages 1 and 2 switchable between HP and LP by SW1 and SW2. 
Stages 3 and 4 fixed on LP.
These allow for the following filter modes:
- A: 24dB LP
- B: 12dB BP
- C: 6dB HP + 18dB LP
- D: 6dB LP + 6dB HP + 12dB LP

Background of the mode configurations: https://electricdruid.net/multimode-filters-part-1-reconfigurable-filters/ section Craig Anderton’s Multiple Identity Filter.

Capacitors on pin 4, 5, 11 and 16 should be 1% or less tolerance! 

F1 and F2 fuses are not really required and can be replaced by shorts.
