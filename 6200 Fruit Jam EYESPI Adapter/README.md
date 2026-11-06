# Fruit Jam EYESPI Adapter

Connects the 2x16 header on the [Adafruit Fruit Jam](https://www.adafruit.com/product/6200) to an 18-pin EYESPI connector, so EYESPI TFT and eInk displays plug in with an [EYESPI cable](https://www.adafruit.com/product/5239). Single sided, 3.3 V logic.

![Turntable render](<6200 Fruit Jam EYESPI Adapter.gif>)

## Files

| File | What |
|---|---|
| `.step` | Board with connectors, for any CAD tool |
| `.3mf` | Board mesh, for test fits |
| `fj-eyespi.kicad_pro`, `.kicad_sch`, `.kicad_pcb` | KiCad source |

## Parts

| Part | Qty |
|---|---|
| 18-pin 0.5 mm FPC connector, bottom contact | 1 |
| 2x16 male SMD header, 2.54 mm | 1 |

Tested with the [2.8" TFT with cap touch](https://www.adafruit.com/product/2090). Pin mapping and example code: [mikeysklar/fruitjam-eyespi](https://github.com/mikeysklar/fruitjam-eyespi)
