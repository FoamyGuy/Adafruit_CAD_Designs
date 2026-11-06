# MAX98357 I2S Amp Feather Shim

A small passive shim that plugs the [Adafruit I2S 3W Class D Amp (MAX98357A)](https://www.adafruit.com/product/3006) straight into a Feather on A0, A1 and A2. No breadboard or jumper wires. 17.5 x 24.9 mm, single sided.

![Animated render](<3006 MAX98357 I2S Amp Feather Shim.gif>)

## Files

| File | What |
|---|---|
| `.step` | Bare board, for any CAD tool |
| `.3mf` | Board mesh, for test fits |
| `i2s-amp-shim.kicad_pro`, `.kicad_sch`, `.kicad_pcb` | KiCad source |

## Pinout

| Feather | Amp |
|---|---|
| 3V | Vin |
| GND | GND |
| A0 | BCLK |
| A1 | LRC |
| A2 | DIN |

```python
import audiobusio, board
i2s = audiobusio.I2SOut(bit_clock=board.A0, word_select=board.A1, data=board.A2)
```

## Parts

| Part | Qty |
|---|---|
| Right angle female socket, 1x05, SMD | 1 |
| Right angle female socket, 1x07, SMD | 1 |

Source: [mikeysklar/i2s-amp-shim](https://github.com/mikeysklar/i2s-amp-shim)
