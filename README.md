# LCR-adapter

To connect 4 wire (kelvin) probes to an handheld LCR some kind of adapter is necessary. The adapter  allows to reach the contacts inside the instrument slots used to insert the tested component leads.

, it shall provide  measurement method. All bench LCR make kelvin measuremnts, but handheld LCR sometimes not. An example is the Keysight U1730C series. 

To connect the probes to an handheld LCR 

User *Voltlog* designed a very nice adapter pcb for Hantek LCR meters, [it can be bought on tindie](https://www.tindie.com/products/voltlog/lcr-meter-kelvin-test-lead-adapter-pcb/).

I derived from his project a version suitable for other LCR models. I have also foreseen the way to mount the capacitors necessary for the measurement on the batteries.

The LCR adapter PCB is designed for theese LCR models:

- MCP BR2832
- B&K Precision 878B / 879B / 880
- Tonghui TH2822A / TH2822C / TH2822D / TH2822E
- Eucol U822, 
- Sourcetronic ST2822/ST2822A/ST2822C

**Use for battery measurements**

When using probes to measure battery internal resistance or impedance with the LCR, it is necessary to insulate the instrument from the battery voltage and avoid to damage the LCR. The PCB is provided for mounting of 2 electrolitic capacitors to perform this insulation.

Suggested values:
C1 470uF
C2 2.2 uF
