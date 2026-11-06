# EYESPI Feather Base

A base board for a Feather with an 18-pin EYESPI FPC connector, so eInk and TFT displays plug straight in with an [EYESPI cable](https://www.adafruit.com/product/5239). It does the same job as the [EYESPI Breakout](https://www.adafruit.com/product/5613) without the wiring.

![Turntable render](<5613 EYESPI Feather Base.gif>)

## Files

| File | What |
|---|---|
| `.step` | Board with connectors, for any CAD tool |
| `.3mf` | Board mesh, for test fits |
| `feather-eyespi.kicad_pro`, `.kicad_sch`, `.kicad_pcb` | KiCad source |

## Wiring

| Feather | EYESPI pin | Function |
|---|---|---|
| SCK | 15 | SPI clock |
| MOSI | 14 | SPI data out |
| MISO | 13 | SPI data in |
| D11 | 11 | Reset |
| D10 | 12 | Data / command |
| D12 | 3 | Busy |
| D9 | 10 | Display CS |
| 3V3 | 18 | 3.3 V |
| GND | 16 | Ground |

## Parts

| Part | Qty |
|---|---|
| 18-pin 0.5 mm FPC connector | 1 |
| 1x16 male header, 2.54 mm SMD | 1 |
| 1x12 female socket, 2.54 mm SMD | 1 |
| 0805 0 ohm resistor | 1 |

Source: [mikeysklar/feather-eyespi](https://github.com/mikeysklar/feather-eyespi)
