# Over 9000 Exponential Power Booster

Two clean Mosfet boosts drive an LPB1 to power levels yet unseen - they're over 9000!
No clipping diodes are added to create this crunch; it occurs naturally

# Parts
## Resistors
| Part | Value | Notes |
|----|:---:|-----|
| R1 | 1M |
| R2 | 5k6 |
| R3 | 5k6 |
| R4 | 1M |
| R5 | 5k6 |
| R6 | 5k6 |
| R7 | 470k |
| R8 | 47k |
| R9 | 10k |
| R10 | 390 |
| PR1 | 68k | Should be 100k trimpot if you are unsure of bias voltage |
| PR2 | 100k |
| LEDR1 | 5k6 |

## Capacitors
| Part | Value | Notes |
|----|:---:|-----|
| C1 | 1n |
| C2 | 47p |
| C3 | 100u | Electrolytic |
| C4 | 1n |
| C5 | 47p |
| C6 | 100u | Electrolytic |
| C7 | 100n |
| C8 | 100n |
| PC1 | 100u | Electrolytic |
| PC2 | 100p |
| PC3 | 100u | Electrolytic |

## Transistors
| Part | Value | Notes |
|----|:---:|-----|
| Q1 | 2n5088 |
| Q2 | BS170 | [Equivalent Substitutes](https://alltransistors.com/mosfet/crsearch.php?&struct=MOSFET&polarity=N&pd=0.83&uds=60&ugsth=3&id=0.5&rds=5&caps=TO92) |
| Q3 | BS170 | [Equivalent Substitutes](https://alltransistors.com/mosfet/crsearch.php?&struct=MOSFET&polarity=N&pd=0.83&uds=60&ugsth=3&id=0.5&rds=5&caps=TO92) |

## Potentiometers
| Part | Value | Notes |
|----|:---:|-----|
| Gain1 | 10kC |
| Gain2 | 10kC |
| Vol1 | 100kA |

## Diodes
| Part | Value | Notes |
|----|:---:|-----|
| PD1 | 1n5819 | Schottky diode |
| LED1 | LED-C1-A2 |

## In/Outs
| Part | Value | Notes |
|----|:---:|-----|
| J1 | 9V |
| J2 | GND |
| J3 | GND |
| J4 | GND |
| J5 | GND |
| J6 | JO | 1/4" Jack Output |
| J7 | JI | 1/4" Jack Input |
| J8 | "JI  I  G  S  O  JO" | 3pdt Footswitch connector - Jack In/PCB in/Ground/Switch/PCB Out/Jack Out |


# Assembly Instructions
1. Gather all necessary parts and tools.
2. Populate parts. Start with short components and work up to taller ones.
2. a. Resistors
2. b. Power protection diode (PD1)
2. c. Film and MLCC (yellow ceramic) capacitors
2. d. Electrolytic capacitors
2. e. Transistors 
3. Board wires, including 6-wire ribbon cable
4. Drill enclosure
5. Add potentiometers and LED to the backside of the PCB, fit into the enclosure, and secure with washers and nuts.
5. b. Solder the mounted components in place.
6. Add power jack and input/output jacks, mount to enclosure.
7. Install footswitch into its daughterboard PCB (arrows should indicate direction of throw)
8. Solder ribbon cable to daughterboard, install footswitch into enclosure and secure with hardware.
9. Install backplate
10. Rock out.
