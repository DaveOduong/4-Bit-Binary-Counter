# 4-Bit Binary Counter

A simple Arduino project that displays a 4-bit binary counting sequence (0000–1111) using four LEDs. The LEDs represent binary bits and update every 750 ms.

## Components

* Arduino Uno
* 4 LEDs
* 4 × 220Ω Resistors
* Breadboard
* Jumper Wires

## Pin Connections

| LED         | Arduino Pin |
| ----------- | ----------: |
| Bit 0 (LSB) |         D12 |
| Bit 1       |         D11 |
| Bit 2       |         D10 |
| Bit 3 (MSB) |          D9 |

## How It Works

The program cycles through all 16 binary combinations, from **0000** to **1111**, displaying each value on the four LEDs with a 750 ms delay before repeating.

## Project Structure

```text
BinaryCounter/
├── BinaryCounter.ino
└── README.md
```

## Author

**Dave Odek**
