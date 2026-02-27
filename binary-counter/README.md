# Binary Counter – Wokwi Microcontroller Project

This project demonstrates a **4-bit binary counter** implemented using an Arduino and simulated in Wokwi.  
Four LEDs represent binary bits and count from **0 to 15**, displaying the binary equivalent of each number.

---

## Project Overview

The system uses:
- 4 LEDs connected to digital pins
- Arduino logic to increment a number
- Bitwise operations to display binary values
- A blinking sequence after counting completes

This project is useful for learning:
- Binary number representation
- Bitwise shifting
- Microcontroller digital output control
- Basic embedded programming concepts

---

## Files Included
```
binary-counter/
sketch.ino
diagram.json
```

| File | Description |
|-----|-------------|
| `sketch.ino` | Arduino code controlling the binary count |
| `diagram.json` | Circuit design for Wokwi simulation |

---

## How It Works

The program counts from **0 → 15**.  
For each number:
1. The value is converted to binary.
2. Each bit is sent to a corresponding LED.
3. LEDs light up according to the binary pattern.
4. After reaching 15, all LEDs blink 4 times.
5. The cycle repeats.

---

## How to Run This Project in Wokwi

1. Go to **https://wokwi.com/**
2. Create a **New Arduino Project**
3. Open `sketch.ino` from this folder and copy its contents.
4. Paste it into the Wokwi `sketch.ino` file.
5. Open `diagram.json` and copy its contents.
6. In Wokwi → **File → Import JSON**
7. Paste and confirm.
8. Click **Start Simulation**

The binary counter should now run.

---

## Learning Concepts Demonstrated

- Bit shifting (`>>`)
- Bit masking (`& 1`)
- Loops
- Arrays
- Functions
- Digital pin control

---

## Author

Created as part of a microcontroller practice project collection using Wokwi simulations.

---

## License

This project is open-source and free to use for learning purposes.
