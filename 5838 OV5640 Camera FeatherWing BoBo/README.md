# OV5640 Camera FeatherWing BoBo

A single-sided FeatherWing that holds an [Adafruit OV5640 Camera Breakout](https://www.adafruit.com/product/5838) (either header layout) and wires it to a Feather, leaving SPI free for an SD card. Tested with Feather ESP32-S3, and built for a [forum wiring question](https://forums.adafruit.com/viewtopic.php?t=221951).

![Turntable render](<5838 OV5640 Camera FeatherWing BoBo.gif>)

## Files

| File | What |
|---|---|
| `.step` | Board with headers, for any CAD tool |
| `.3mf` | Board mesh, for test fits |
| `ov564-fw-bobo.kicad_pro`, `.kicad_sch`, `.kicad_pcb` | KiCad source |

## Parts

| Part | Qty |
|---|---|
| 1x16 male header, 2.54 mm | 1 |
| 1x12 female socket, 2.54 mm | 1 |
| 1x09 male header, 2.54 mm SMD | 1 |
| 2x09 male header, 2.54 mm SMD (double row) | 1 |
| 0805 resistor (R1) | 1 |

Thanks to Jerry Needell for the [reference design and example code](https://github.com/jerryneedell/mycamera).

Source: [mikeysklar/ov5640-featherwing-bobo](https://github.com/mikeysklar/ov5640-featherwing-bobo)
