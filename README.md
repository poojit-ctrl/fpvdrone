# DriftWing FPV Drone

This is **DriftWing**, a compact and lightweight FPV drone designed from scratch for speed, agility, and freestyle flying. With custom-designed plates and frame made from laser-cut carbon fiber or 3D printed PLA+ parts, this quad was built to be lightweight without compromising on rigidity. It's perfect for beginners looking to build their first FPV setup or tinkerers who love DIY drones.

DriftWing was designed in Fusion 360, assembled with patience, and tuned for performance. It supports both analog FPV setups and has enough headroom to strap on a GoPro mount (print it if you want it).

---

## Features

The DriftWing is designed around a minimalist but functional build. Four 2306 2400KV motors paired with 5-inch tri-blade props provide more than enough thrust. It rocks a 4-in-1 ESC for clean wiring and reduced weight, and is paired with a tried-and-tested F4 flight controller. The stack is modular, crash-friendly, and easy to maintain.

The analog FPV system is powered by a solid 700TVL camera and a 5.8GHz VTX, all wired through a custom power distribution board. The frame was modeled to keep the center of gravity tight and support different battery placements (top-mount or bottom-mount). There's even room for a GPS module for return-to-home failsafes.

---

## Design Preview

| Image | Description |
|-------|-------------|
| ![driftwing-3d](https://github.com/user-attachments/assets/driftwing-model.png) | Full 3D render of the drone in Fusion 360 |

---

## Bill of Materials

This is the complete breakdown of the parts used in this FPV drone build. The transmitter and receiver are not included here as they are being DIY-ed separately.

| Component                        | Qty | Unit Price (USD) | Total Price (USD) |
|----------------------------------|-----|------------------|-------------------|
| Brushless Motors (2306 2400KV)   | 4   | $17.36           | $70.00            |
| 4-in-1 ESC 30A                   | 1   | $35.00           | $35.00            |
| Flight Controller (F4)           | 1   | $25.00           | $25.00            |
| Carbon Fiber Arms                | 1   | -                | -                 |
| Top Plate (printing legion)      | 1   | -                | -                 |
| Bottom Plate (printing legion)   | 1   | -                | -                 |
| M3 Screws & Standoffs            | 1   | $6.00            | $6.00             |
| 5-inch Tri-blade Props           | 4   | $1.50            | $6.00             |
| XT60 Connector                   | 1   | $1.20            | $1.20             |
| Power Distribution Board         | 1   | $4.00            | $4.00             |
| Capacitor (35V 470uF)            | 1   | $1.50            | $1.50             |
| Battery Strap                    | 1   | $2.00            | $2.00             |
| LiPo Battery 4S 1500mAh 100C     | 1   | $25.00           | $25.00            |
| FPV Camera (Analog)              | 1   | $18.00           | $18.00            |
| Video Transmitter (VTX)          | 1   | $15.00           | $15.00            |
| Antenna (VTX)                    | 1   | $4.00            | $4.00             |
| GoPro Mount (printing legion)    | 0   | -                | -                 |
| GPS Module                       | 1   | $12.00           | $12.00            |
| Buzzer with LED                  | 1   | $2.00            | $2.00             |
| Foam Landing Pads                | 4   | $0.50            | $2.00             |
| Heat Shrink Tubing               | 1   | $1.00            | $1.00             |
| Silicone Wires (14AWG, 20AWG)    | 1   | $3.00            | $3.00             |
| Flight Stack Mounting Grommets   | 1   | $1.50            | $1.50             |

**Total Cost:** **$234.20**

---

## Files Included

- `frame_top.stl`  
- `frame_bottom.stl`  
- `driftwing_flight_stack.fcstd`  
- `drone_bom.csv`  
- `journal.md` – Build log with design thoughts  
- `driftwing.fusionarchive` – Fusion 360 full assembly

---

## How to Build

1. Print or cut the frame components  
2. Assemble the stack with the ESC and flight controller  
3. Solder the motors to ESC pads  
4. Mount the FPV camera and VTX  
5. Add the XT60 and capacitor to the PDB  
6. Install the firmware on your flight controller  
7. Test motor directions and gyro  
8. Mount the props and strap on a battery  
9. Goggles down, power up, and fly

---

## Licensing

This project is open-source under the MIT License.  
Feel free to remix, mod, or fork this and make your own freestyle flyer.

---

built in fusion 360 and printed in legion’s printer cave
