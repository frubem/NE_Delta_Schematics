# LX782 TV/Composite Video board - BOM

| Component              | Qty | Type / Value                                            | Notes                                                                |
| ---------------------- | --- | ------------------------------------------------------- | -------------------------------------------------------------------- |
| C1, C2, C4             |  3  | 100nF/16V+ MLCC capacitor, 5mm pitch                    |                                                                      |
| C8		             |  1  | 100nF/25V+ MLCC capacitor, 5mm pitch                    | **RF section only.**                                                 |
| C3		             |  1  | 47uF/25V+ electrolytic capacitor, 2.5mm pitch           |                                                                      |
| C5		             |  1  | 100pF/25V+ MLCC capacitor, 5mm pitch                    | **RF section only.**                                                 |
| C6		             |  1  | 27pF/25V+ MLCC capacitor, 5mm pitch                     | **RF section only.**                                                 |
| C7		             |  1  | 10uF/25V+ electrolytic capacitor, 2.5mm pitch           | **RF section only.**                                                 |
| C9		             |  1  | 2.2nF/25V+ MLCC capacitor, 5mm pitch                    | **RF section only.**                                                 |
| C10		             |  1  | 5.6pF/25V+ MLCC capacitor, 5mm pitch                    | **RF section only.**                                                 |
| C11		             |  1  | 12pF/25V+ MLCC capacitor, 5mm pitch                     | **RF section only.**                                                 |
| CONN.1                 |  1  | pin header, 13P, 2.54mm pitch, right angle              |                                                                      |
| IC1                    |  1  | 74LS04 DIP-14                                           | 'HCT can be used                                                     |
| DS1 - DS14             |  14 | 1N4148                                                  |                                                                      |
| DZ1                    |  1  | 10V/1W zener diode, DO-35                               | 1N4740A is fine for this                                             |
| J1                     |  1  | RCA connector, yellow, merlin style                     | You can find these on [AliExpress](https://aliexpress.com/item/1005006135848173.html) or RCJ-042 on Mouser |
| L1                     |  1  | Handwound inductor                                      | **RF section only.**  Use 0.5mm copper wire, wind 7 spires on a 6mm diameter cilinder, pull the wire to make the inductor 13mm long. Make a center tap at 3.5 windings |
| P1                     |  1  | Video output selection. 3P, 2.54mm header               | If RF section is omitted, solder pin 1 and 2 together.               |
| R1                     |  1  | 1.5Kohm resistor, 1/4W                                  |                                                                      |
| R2                     |  1  | 3.3Kohm resistor, 1/4W                                  |                                                                      |
| R3                     |  1  | 820ohm resistor, 1/4W                                   |                                                                      |
| R4                     |  1  | 820ohm resistor, 1/4W                                   |                                                                      |
| R5                     |  1  | 3.9Kohm resistor, 1/4W                                  |                                                                      |
| R6                     |  1  | 6.8Kohm resistor, 1/4W                                  |                                                                      |
| R7                     |  1  | 1Kohm resistor, 1/4W                                    |                                                                      |
| R8                     |  1  | 47ohm resistor, 1/4W                                    |                                                                      |
| R9                     |  1  | 470ohm resistor, Bourns 3386 potentiometer              | If RF section is omitted, wire a 470ohm resistor across the two bottom pins. |
| R10                    |  1  | 390ohm resistor, 1/4W                                   | Original BOM calls for 390ohm, which generates too hot of a signal. It may be a typo and be originally 3.9K. It is advised to replace it with a 4.7Kohm                                                                     |
| R11                    |  1  | 120ohm resistor, 1/4W                                   |                                                                      |
| R12, R14               |  2  | 3.3Kohm resistor, 1/4W                                  | **RF section only.**                                                 |
| R13                    |  1  | 2.7Kohm resistor, 1/4W                                  | **RF section only.**                                                 |
| R15                    |  1  | 680ohm resistor, 1/4W                                   | **RF section only.**                                                 |
| TR1				     |  1  | BSX.29/BFR.99 TO-72                                     | **RF section only.**                                                                     |

The RF section builds a VHF modulator. Unless you want to connect it to a TV via the antenna port, it is useless to build.
