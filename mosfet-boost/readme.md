# Mosfet Boost

From the [AMZ Mosfet boost](http://www.muzique.com/schem/mosfet.htm), this transparent
boost adds up to 35 dB in gain to your signal ... enough to smash any fuzz, distortion, or amp
into overdrive.

# Parts
## Resistors
| Part | Value | Notes |
|----|:---:|-----|
| R1 | 68k | Should be 100k trimpot if you are unsure of bias voltage |
| R2 | 100k |
| R3 | 1M |
| R4 | 5k6 |
| R5 | 5k6 |

## Capacitors
| Part | Value | Notes |
|----|:---:|-----|
| C1 | 10u | Electrolytic |
| C2 | 1n | |
| C3 | 47p | |
| C4 | 100u | Electrolytic |
| C5 | 100n | |

## Transistors
| Part | Value | Notes |
|----|:---:|-----|
| Q1 | BS170 | [Equivalent Substitutes](https://alltransistors.com/mosfet/crsearch.php?&struct=MOSFET&polarity=N&pd=0.83&uds=60&ugsth=3&id=0.5&rds=5&caps=TO92) |

## Potentiometers
| Part | Value | Notes |
|----|:---:|-----|
| Gain1 | 10kC | |

## In/Outs
| Part | Value | Notes |
|----|:---:|-----|
| J1 | 9V | There is no power conditioning on the board |
| J2 | GND | External reverse-polarity protection recommended |
| J3 | In  | PCB In |
| J4 | Out | PCB Out |
