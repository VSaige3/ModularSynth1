# CMOS VCO by René Schmitz

## Tech Specs
### Impedances
- Audio Output: ~500-700 (Estimated from inverter)
- CV Input: ~100k
These are well within Eurorack standards.

### I/O
- Any number of 1V/Oct CV (probably want like 2)
- 1 PWM CV (seems exponential)
- PW adjust pot
- Center freq adjust pot
- V/oct trimpot
- Triangle wave output
- Pulse wave output

### Construction Notes
- The inverter may become heated at high power
- T1 and T2 should be thermally connected (glued together)
  - attempting to replace BC548/BC558 with modern ones (2N3906/2N3904), as the originals are obsolete