# UM3561-Siren-Generator
Can play either a Police Siren, Ambulance Siren or Fire Engine Siren when triggered.



## Electronic Components
| Qty | Component | Buy |
| ------------- | ------------- | ------------- |
| 1 | UM3561 |[AliExpress](http://s.click.aliexpress.com/e/ckC9oWJA) |
| 1 | BC547 NPN Transistor |[AliExpress](http://s.click.aliexpress.com/e/bpL0Irsk) |
| 1 | 220KΩ Resistor |[AliExpress](http://s.click.aliexpress.com/e/bh4eqrQs) |
| 2 | 220Ω Resistor |[AliExpress](http://s.click.aliexpress.com/e/bh4eqrQs) |
| 1 | 5mm LED |[AliExpress](http://s.click.aliexpress.com/e/wuFpLXS) |
| 1 | SPDT Slider Switch |[AliExpress](http://s.click.aliexpress.com/e/bKFlazR2) |
| 1 | SP3T Slider Switch |[AliExpress](http://s.click.aliexpress.com/e/bZ3jBWuY) |
| 2 | 2-Pin Male Header Pins |[AliExpress](http://s.click.aliexpress.com/e/bIN5SJXw) |
| 1 | Speaker |[AliExpress](http://s.click.aliexpress.com/e/brMJh46c) |
| 1 | AA Battery Holder (2 Slot) |[AliExpress](http://s.click.aliexpress.com/e/c7Lm2Nm0) |
| 2 | AA Battery |[AliExpress](http://s.click.aliexpress.com/e/YMpokbA) |

| Tools | Buy |
|--|--|
|Soldering Iron|[AliExpress](http://s.click.aliexpress.com/e/E83bSJI) |
|Soldering Wire|[AliExpress](http://s.click.aliexpress.com/e/PdhB0nm) |

## Working
**UM3561:**

The UM3561 is a low-cost, low power CMOS LSI designed for use in toy applications. Since the integrated circuit
includes oscillating and selector circuits, a compact sound module can be constructed with only a few additional
components. The UM3561 contains a programmed mask ROM to electronically reproduce alarm sounds.



- Typical Operating Voltage = 3V
- 8-Pin DIP Package
- Power On Reset


**Circuit:**

Only one of the Siren tunes can be played at a time. This is determined on the basis of the position of the SP3T Slide switch.
The switch has three positions which will connect the common terminal with VCC, GND or NC in order to fulfill the Truth Table.



A dynamic speaker is driven with an external NPN transistor.
A SPDT switch is used to turn the circuit ON & OFF.





[![alt text][1.1]][1] [![alt text][2.1]][2] [![alt text][3.1]][3]




