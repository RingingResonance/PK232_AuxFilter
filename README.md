# PK232_AuxFilter
An added filter stage for the PK232's packet modem descriminator based on the same circuit's existing filter design.

I don't have the best understanding of how this type of filter works so I copied that part of the schematic resistor-per-resistor
with the goal of helping the PK232 perform a little better when the incoming signal isn't full-quieting. Obviously this is for
models that don't have the DSP filter. This filter should be able to be used for other things by changing the resistor and capacitor
values to fit your needs. It would probably work on other TNC's.

Current resistor and capacitor values for Mark/Space:
VHF mode: 1200/2400 hz
HF mode: 2110/2310 hz
