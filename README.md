# Adafruit_CAD_Designs

Small printable accessories for Adafruit boards: brackets, clips, adapter frames, panel mounts and shims. None of these are sold in the Adafruit Store. They're quick designs made while using the boards, shared so you can print and remix them.

For accurate models of the boards themselves, see [Adafruit_CAD_Parts](https://github.com/adafruit/Adafruit_CAD_Parts).

## Layout

Each design has its own folder, named with the Adafruit product ID of the main board it fits, followed by the board and what the design does:

```
6536 Metro ESP32-P4 Touch Display 2 Adapter/
    README.md      what it is, print settings, hardware list
    <name>.3mf     ready to slice
    <name>.step    for any CAD tool
    <name>.FCStd   source, or .f3d for Fusion
    <name>.gif     small preview, under 1 MB
    <name>.jpg     still render or photo
```

Sorting by product ID keeps every accessory for one board together. A design that fits more than one board goes under the board it was made for, and its README links the others.

## License

MIT. See [LICENSE](LICENSE).
