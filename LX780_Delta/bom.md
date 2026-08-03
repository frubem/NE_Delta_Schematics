# LX780 DELTA motherboard - BOM

| Component              | Qty | Type / Value                                            | Notes                                                                |
| ---------------------- | --- | ------------------------------------------------------- | -------------------------------------------------------------------- |
| C1, C6                 |  2  | 100uF/25V+ electrolytic capacitor, 5mm pitch            |                                                                      |
| C2-C5, C17-C20, C22-C52 | 39  | 100nF/25V+ MLCC capacitor, 5mm pitch                   |                                                                      |
| C7                     |  1  | 10nF/25V+ MLCC capacitor, 5mm pitch                     | Note that the silkscreen value for this is missing in rev.0          |
| C8                     |  1  | 100uF/25V+ electrolytic capacitor, 3.5mm pitch          |                                                                      |
| C9-C16                 |  8  | 22nF/25V+ MLCC capacitor, 5mm pitch                     |                                                                      |
| C21                    |  1  | 10uF/25V+ electrolytic capacitor, 3.5mm pitch           |                                                                      |
| CONN.1 - 7             |  7  | 50P (2x25) female edge connector, 2.54mm pitch          | https://aliexpress.com/item/1005008354411366.html                    |
| CONN.8                 |  1  | 6P 3.96mm pitch header                                  | Pin 2 must be removed. E.g. https://www.mouser.it/ProductDetail/Molex/26-48-2065 |
| CONN.9                 |  1  | 13P 2.54mm pitch pinsocket, straight                    |                                                                      |
| CONN.10, CONN.12       |  2  | DIP-16 socket                                           | Used as keyboard/joystick connectors. My advice is to use turned pin sockets for these |
| CONN.11                |  1  | DSUB-9, female, horizontal                              |                                                                      |
| DS1, DS2               |  2  | 1N4148 diodes                                           |                                                                      |
| IC1, IC44, IC60        |  3  | 74LS00                                                  | IC1 can be replaced with an 'F variant, IC60 works fine with an 'HCT |
| IC2, IC40              |  2  | 74LS04                                                  | IC2 can be replaced with an 'HCT                                     |
| IC3, IC51              |  2  | 74LS02                                                  | IC51 can be replaced with an 'HCT                                    |
| IC4, IC7, IC69         |  3  | 74LS138                                                 |                                                                      |
| IC5                    |  1  | 74ALS04                                                 | Use an ALS or F or plain TTL here. LS provides an unstable clock     |
| IC6                    |  1  | 74LS32                                                  |                                                                      |
| IC8 - IC23             |  16 | 4164 DRAM                                               | Tested with HM4864P-2                                                |
| IC24, IC38             |  2  | 74LS245                                                 | Noticed improved stability and signal integrity using an 'HCT for IC24 |
| IC25, IC26, IC50, IC52 |  4  | 74LS374                                                 | 'HCT replacements work fine for all of these                         |
| IC27, IC28             |  2  | 2764 EPROM                                              | Tested with 27C64, 200ns                                             |
| IC29, IC42, IC45, IC47, IC48, IC54, IC57 |  7  | GAL16V8                               | Used ATF16V8BQL-15PU                                                 |
| IC30, IC46, IC71       |  3  | 74LS74                                                  |                                                                      |
| IC31, IC32, IC34, IC56 |  4  | 74LS153                                                 | Also tested with F family here, no issue                             |
| IC33                   |  1  | 74ALS153                                                | Use an ALS or F here. In my tests it resulted in a more stable DHR picture |
| IC35, IC36, IC72       |  3  | 74LS244                                                 | Improved signal integrity using 'HCT for IC35 and IC36               |
| IC37                   |  1  | 6502 DIP-40                                             | Currently using a 65C02                                              |
| IC39                   |  1  | 74LS125                                                 |                                                                      |
| IC41                   |  1  | 74LS173                                                 |                                                                      |
| IC43                   |  1  | 74LS20                                                  |                                                                      |
| IC49                   |  1  | 74LS165                                                 |                                                                      |
| IC53                   |  1  | 74LS157                                                 | Also tested with an 'ALS                                             |
| IC55                   |  1  | 2732                                                    | Tested with 27C32, 250ns                                             |
| IC58, IC64             |  2  | 74LS259                                                 |                                                                      |
| IC62                   |  1  | 6545 CRTC, DIP-40                                       |                                                                      |
| IC65, IC66             |  2  | 74LS251                                                 |                                                                      |
| IC67, IC68, IC73       |  3  | NE556                                                   |                                                                      |
| IC70                   |  1  | ua741                                                   | Op-Amp                                                               |
| J1, J2                 |  2  | SJ1-3513N audio jacks                                   | https://www.mouser.it/ProductDetail/490-SJ1-3513N                    |
| LS1                    |  1  | 2P 2.54mm pitch header, right angle                     |                                                                      |
| P1 - P4, P6 - P8       |  7  | 3P 2.54mm pitch header, straight                        |                                                                      |
| R1, R2, R7             |  3  | SIP 9 pin 1K resistor array, bussed                     |                                                                      |
| R3, R4                 |  2  | 470ohm resistor, 1/4W                                   |                                                                      |
| R5, R6                 |  2  | 33ohm resistor, 1/4W                                    |                                                                      |
| R8 - R11, R13, R14, R28|  7  | 1Kohm resistor, 1/4W                                    |                                                                      |
| R15 - R18              |  4  | 560ohm resistor, 1/4W                                   |                                                                      |
| R19, R21 - R24, R31    |  6  | 12Kohm resistor, 1/4W                                   |                                                                      |
| R20                    |  1  | 1Mohm resistor, 1/4W                                    |                                                                      |
| R25                    |  1  | 47Kohm resistor, 1/4W                                   |                                                                      |
| R26                    |  1  | 100ohm resistor, 1/4W                                   |                                                                      |
| R27                    |  1  | 27ohm resistor, 1/4W                                    |                                                                      |
| R29                    |  1  | 10Kohm resistor, 1/4W                                   |                                                                      |
| R30                    |  1  | 2.2Mohm resistor, 1/4W                                  |                                                                      |
| R32                    |  1  | 3.3Mohm resistor, 1/4W                                  |                                                                      |
| TR1                    |  1  | BC517 transistor, TO-92                                 |                                                                      |
| TR2                    |  1  | 2N2222A transistor, TO-92                               |                                                                      |
| XTAL1                  |  1  | 14.3180Mhz HC49 crystal                                 | https://www.mouser.it/ProductDetail/520-HCA1431-SX                   |

Some of the glue logic can be replaced with 'HCT variants. I've added notes where I found that the replacement works.
