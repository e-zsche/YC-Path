# YC-Path

While most video synthesizers use an RGB to CVBS encoder IC for generating video signals the goal
of this project is to directly generate the luminance and chrominance signals used for analog
video signals.
of this project is to directly generate luminance and chrominance signals for analog video signals.

# System Overview

Module size specification is according to the doepfer eurorack standard.
<https://doepfer.de/a100_man/a100m_e.htm>
Module front plates are 3U in height and a multiple of 1HP wide with M3 mounting slots.

## Power Supply

The main power supply puts out ±5 V for all modules. Some older ICs run on +12V. To supply power
for these an auxilliary +12V rail is used.

First PSU Module uses Traco DC/DC Bricks. External Power is supplied via USB-C power delivery
at 20V.

TRACO TEN 10-2421:
- Vin: 18-36V
- Vout: +/- 5V
- Iout: +/- 1A

TRACO TSR 1-24120:
- Vin: 18-36V
- Vout: + 12V
- Iout: + 1A

