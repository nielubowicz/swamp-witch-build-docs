# Eat the Rich

A double dose of distortion, Eat the Rich features two Dist+
circuits slammed back-to-back, around a modified BMP tone stack.
Includes the distinctive mids-bump from the Dist+, amplified!

# Parts
## Resistors
| Part | Value | Notes |
|----|:---:|-----|
| R1 | 10k | |
| R2 | 1M | Not featured on board - see notes |
| R3 | 4k7 | |
| R4 | 10k | |
| R5 | 3k3 | |
| R6 | 470k | |
| R7 | 100k | |
| R8 | 10k | |
| R9 | 1M | Not featured on board - see notes |
| R10 | 4k7 | |
| R11 | 10k | |

## Capacitors
| Part | Value | Notes |
|----|:---:|-----|
| C1 | 1n | |
| C2 | 10n | |
| C3 | 47n | |
| C4 | 1u | |
| C5 | 1n | |
| C6 | 15n | |
| C7 | 2n2 | |
| C8 | 1u | |
| C9 | 100n | |
| C10 | 1u | |
| C11 | 47p | |

## Diodes
| Part | Value | Notes |
|----|:---:|-----|
| D1 | 1n34a | |
| D2 | 1n34a | |
| D3 | 1n34a | |
| D4 | 1n34a | |

## ICs
| Part | Value | Notes |
|----|:---:|-----|
| U1 | TL022 | |

## Potentiometers
| Part | Value | Notes |
|----|:---:|-----|
| Gain1 | 1MC / 500kC | |
| Gain2 | 1MC / 500kC | |
| Vol1 | 100k | |
| Body1 | 25k | |
| Tone1 | 250kA | |

## Connections
| Part | Value | Notes |
|----|:---:|-----|
| J1 | 9V | Board features no-on-board reverse polarity protection |
| J2 | GND | |
| J3 | -9V | External Bipolar supply required - MAX1044 recommended |
| J4 | In | |
| J5 | Out | |

# Notes
`R2/R9` are not featured on the board, and numbering will reflect this.
`R2` and `R9` must be tied from Pin 3/5 (opamp non-inverting inputs) to GND.

`R9` may need to be tied to a variable-voltage bias instead of GND - this
is still a work in progress.
