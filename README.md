# LCR-adapter

To connect 4 wire (kelvin) probes to an handheld LCR some kind of adapter is necessary. The adapter  allows to reach the contacts inside the instrument slots used to insert the tested component leads.

<img src="/images/handheld-LCR-with-adapter-and-probes.jpg" alt="LCR with adapter PCB" title="LCR with adapter PCB" width=50% height=50%>

LCR must provide 4 wire measurement method. All bench LCR make kelvin measuremnts, but handheld LCR sometimes not. An example is the Keysight U1730C series. 

User *Voltlog* designed a very nice adapter pcb for Hantek LCR meters, [it can be bought on tindie](https://www.tindie.com/products/voltlog/lcr-meter-kelvin-test-lead-adapter-pcb/).

I derived from his project a version suitable for other LCR models. I have also foreseen the way to mount the capacitors necessary for the measurement on the batteries.

<img src="/images/handheld-LCR-adapter.jpg" alt="Adapter PCB" title="Adapter PCB" width=50% height=50%>

The LCR adapter PCB is designed for theese LCR models:

- MCP BR2832
- B&K Precision 878B / 879B / 880
- Tonghui TH2822A / TH2822C / TH2822D / TH2822E
- Eucol U822, 
- Sourcetronic ST2822/ST2822A/ST2822C

**Use examples**

LCR double contacts kelvin pobes

<img src="/images/lcr-adapter-pcb-doublepin-probes.jpg" alt="capacitors" title="LCR double contacts kelvin pobes" width=50% height=50%>

I designed theese DIY probes for battery impedance measurements, are available on my [my Tindie store](https://www.tindie.com/products/bitplus/4-wire-kelvin-double-contacts-probes-kit/).

Tester probes

<img src="/images/lcr-adapter-pcb-tester-probes.jpg" alt="LCR tester pobes" title="LCR tester pobes" width=50% height=50%>

The 4 wires are connectet on the back of the probe pins.

**Use for battery measurements**

When using probes to measure battery internal resistance or impedance with the LCR, it is necessary to insulate the instrument from the battery voltage and avoid to damage the LCR. The PCB is provided for mounting of 2 electrolitic capacitors to perform this insulation.

<img src="/images/lcr-adapter-pcb-insulation-capacitors.jpg" alt="capacitors" title="LCR insulation capacitors" width=50% height=50%>

Suggested values:

- C1 470uF
- C2 2.2 uF

When capacitor are not installed the pads shall be short-circuited.

**Case**

A case to be 3D printed is under development

<img src="/images/handheld-LCR-adapter-case.jpg" alt="case" title="LCR adapter case" width=50% height=50%>

**How to get one**

You can order the PCB from [my Tindie store](https://www.tindie.com/products/bitplus/lcr-kelvin-4-wires-probes-adapter-pcb/).
