# optofilter
this is the v2 design. modules i am building are v1 as of 2017 august. 
changes:
~resonance pot is wired the right way around
~ptc fuses added on the power lines
~output jacks are wired correctly
~all capacitors, resistors increased in size to 1206 footprint for convenience
~minimum trace width increased for better conductivity i guess
~transistor footprint changed to smd mmbt3904 and mmbt3906
~jack pads expanded to allow for a wider variety of jacks to be used

to make the optocouplers, a green smd led shines from the cv board, and a matching NSL5152 sticks out toward it from the audio board. a little heatshrink tubing is used to isolate the led light a bit more. green leds were used because NSL5152 LDRs are most sensitive to light wavelengths near green. the coupling is not as close as a VTL5C3 or something, but i believe even buchla is using LDR/LED combos in a similar configuration. 

modulargrid: https://www.modulargrid.net/e/other-unknown-chartrearts-psilocybe-optocoupler-filter
youtube demo: https://www.youtube.com/watch?v=KrvsKUyxW6Y
etsy link: https://www.etsy.com/listing/453749594/psilocybe-optocoupler-filter-for-modular
