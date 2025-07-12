# DriftWing FPV Drone

DriftWing is that one FPV drone you design in your head during boring lectures and then actually build when you finally have the time and brainpower. It’s a freestyle rig that’s super lightweight, fully custom, and made to do flips, dives, and maybe crash a few times without crying.

This thing isn’t printed yet, btw. The model is locked and loaded in Fusion 360, but we’re waiting on a green signal for project approval and some grant money to get it out of CAD and into the air. Big shoutout to **@toby** on Slack for helping me pick the right motors and reviewing the design before it even existed IRL. Legend move.

---

## Frame Preview

| Image | Description |
|-------|-------------|
| ![driftwing-frame](https://github.com/user-attachments/assets/driftwing-model.png) | Full Fusion 360 render of the frame. All parts modeled to scale with 5" props. Waiting to get this printed/cut. |

---

## The Vibe

DriftWing was designed from scratch in Fusion 360 with the idea of keeping things modular, fixable, and crash-forgiving. The frame uses custom top and bottom plates that can either be 3D printed in PLA+ or laser-cut in carbon fiber if budget allows. The arms are separated for easier swaps when the inevitable faceplant happens. Every screw, standoff, and capacitor has its space.

It’s got that “I-built-this-in-my-room” energy but backed by a parts list that can punch with the big brands. The wiring is clean thanks to the 4-in-1 ESC stack, and the VTX and analog cam give it old-school FPV vibes without sacrificing clarity.

---

## Tech Specs

- Motor-to-motor distance fits 5-inch props  
- 2306 2400KV motors (recommended by @toby)  
- 4-in-1 ESC (30A) with solder tabs facing up  
- F4 Flight Controller, stack-mounted  
- Power distribution through a separate PDB  
- XT60 battery input with a 470uF cap for that ripple control  
- GPS module slot for Return-To-Home  
- Space for analog FPV cam + VTX  
- GoPro mount spot up front (optional but modeled in)  
- Foam landing pads and battery strap support

---

## Bill of Materials

This is everything it’ll take to bring DriftWing from file to flight. No receiver or transmitter listed here because that’s gonna be DIY.

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

## Status

Current status: **waiting for print time and funding approval**  
Files are locked, model is ready, and just vibing till the build can actually happen. Once the plates are cut and parts arrive, the full build log will drop in `journal.md`.

---

## File Dump

- `driftwing_frame_top.stl`  
- `driftwing_frame_bottom.stl`  
- `driftwing_stack_mount.fcstd`  
- `driftwing_bom.csv`  
- `journal.md` – WIP build diary  
- `driftwing_complete.fusionarchive`  

---

## Credits

- Designed by me (obviously)  
- Flight gear choices helped and pre-reviewed by **@toby** (Slack MVP)  
- Modeled in Fusion 360  
- Soon to be printed in **Legion’s 3D printer dungeon**

---

## License

MIT License. Clone it, mod it, crash it, post the footage.

---

when it flies, it'll scream
