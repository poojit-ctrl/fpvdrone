# DriftWing FPV Drone

DriftWing is that one FPV drone you design in your head during boring lectures and then actually build when you finally have the time and brainpower. It’s a freestyle rig that’s super lightweight, fully custom, and made to do flips, dives, and maybe crash a few times without crying.

This thing isn’t printed yet, btw. The model is locked and loaded in Fusion 360. Big shoutout to **@toby** on hc Slack for helping me pick the right motors and reviewing the design before it even existed IRL. Legend move.

---

## Frame Preview

| Image | Description |
|-------|-------------|
| <img width="1115" height="1079" alt="image" src="https://github.com/user-attachments/assets/5126aad3-5796-4767-bd78-72bf099c6734" /> | Full Fusion 360 render of the frame. All parts modeled to scale with 5" props |

---

## what came into my mind when i designed it

DriftWing was designed from scratch in Fusion 360 with the idea of keeping things modular, fixable, and crash-forgiving. The frame uses custom top and bottom plates that can either be 3D printed in PLA+ or laser-cut in carbon fiber if budget allows. The arms are separated for easier swaps when the inevitable faceplant happens. Every screw, standoff, and capacitor has its space.

It’s got that “I-built-this-in-my-room” energy but backed by a parts list that can punch with the big brands. The wiring is gonna be clean thanks to the 4-in-1 ESC stack, and the VTX and analog cam give it old-school FPV vibes without sacrificing clarity.

---
## diy transmitter and receiver 

| Image | Description |
|-------|-------------|
| <img width="981" height="645" alt="Screenshot 2025-07-13 180246" src="https://github.com/user-attachments/assets/4fc16777-131c-4189-bc38-7dc31b6c7912" /> | diy transmitter |

| Image | Description |
|-------|-------------|
| <img width="1309" height="874" alt="image" src="https://github.com/user-attachments/assets/ca5ec11d-e8d7-45e9-a816-e599d6939623" /> | diy receiver  |

| Image | Description |
|-------|-------------|
| <img width="865" height="878" alt="Screenshot 2025-07-18 004724" src="https://github.com/user-attachments/assets/be6ea970-3984-4e78-bb8d-0f8f582ead1a" /> | flight controller ( more layers cus so much routing) |

| Image | Description |
|-------|-------------|
| <img width="524" height="551" alt="image" src="https://github.com/user-attachments/assets/fefb87d7-052f-427f-a207-87b40bd5de80" /> | flight controller 3d render |
| Image | Description |
|-------|-------------|
| <img width="1032" height="646" alt="image" src="https://github.com/user-attachments/assets/623e0f86-d0e6-4a18-9411-f2992d433b41" /> | Transmitter 3d render |
| Image | Description |
|-------|-------------|
| <img width="1047" height="859" alt="image" src="https://github.com/user-attachments/assets/390dcff7-e58e-4e41-9ddf-fdb453155900" /> | Receiver 3d render |

---
## Tech Specs

- Motor-to-motor distance fits 5-inch props  
- 2207 2400KV motors (recommended by @toby)  
- 4-in-1 ESC (30A) with solder tabs facing up  
- Speedybeef405 FC
- Power distribution through a separate PDB  
- XT60 battery input with a 470uF cap for that ripple control  
- GPS module slot for Return-To-Home  
- Space for analog FPV cam + VTX  
- GoPro mount spot up front (optional but modeled in)  
- Foam landing pads and battery strap support

---

## Bill of Materials

This is everything it’ll take to bring DriftWing from file to flight. No receiver, transmitter or flight controller listed here because that’s gonna be DIY.

| Component                        | Qty | Unit Price (USD) | Total Price (USD) |
|----------------------------------|-----|------------------|-------------------|
| 2207 2400KV brushless motors     | 4   | $17.36           | $70.00            |
| 4-in-1 ESC 30A                   | 1   | $35.00           | $35.00            |
| Arms (petg-cf)(own expense)          | 1   | -                | -                 |
| Top Plate (petg-cf)(own expense)      | 1   | -                | -                 |
| Bottom Plate (petg-cf)(own expense)   | 1   | -                | -                 |
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
| GPS Module                       | 1   | $12.00           | $12.00            |
| Buzzer with LED                  | 1   | $2.00            | $2.00             |
| Foam Landing Pads                | 4   | $0.50            | $2.00             |
| Heat Shrink Tubing               | 1   | $1.00            | $1.00             |
| Silicone Wires (14AWG, 20AWG)    | 1   | $3.00            | $3.00             |
| Flight Stack Mounting Grommets   | 1   | $1.50            | $1.50             |
| Flight Controller                | 1   | 0(already have it)| $1.00             |
| Receiver                         | 1   | 0(already have it)| $3.00             |
| Transmitter                      | 1   | 0(already have it)| $1.50             |

# note: in my submission i mentioned the bom as 234 ignore that as i made my own flight controller, thus the updated bom is 209.20 usd.
**Total Cost:** **$209.20**

---
## gallery 
<img width="981" height="1079" alt="Screenshot 2025-07-12 215111" src="https://github.com/user-attachments/assets/752988f6-cb8d-49e7-8392-f2438d42e4c4" />
<img width="981" height="644" alt="Screenshot 2025-07-12 135622" src="https://github.com/user-attachments/assets/236817ec-d83d-403d-b8bb-7c4622217863" />
<img width="981" height="818" alt="Screenshot 2025-07-12 131958" src="https://github.com/user-attachments/assets/1900212e-380a-4313-a3f4-d2a020007a7c" />
<img width="981" height="862" alt="Screenshot 2025-07-12 131504" src="https://github.com/user-attachments/assets/414e836d-0cd9-4bd4-956d-dc1142aaec27" />
<img width="981" height="886" alt="Screenshot 2025-07-12 130217" src="https://github.com/user-attachments/assets/aa2c4544-f619-4954-9f38-6569cffa42f0" />
<img width="981" height="1051" alt="Screenshot 2025-07-12 125817" src="https://github.com/user-attachments/assets/cca34340-c424-40d0-8ffc-c109fe400c9a" />
<img width="981" height="568" alt="Screenshot 2025-07-12 122857" src="https://github.com/user-attachments/assets/70aee77d-3a32-4e3b-8ba1-7e26c8b78881" />
<img width="981" height="1086" alt="Screenshot 2025-07-12 120719" src="https://github.com/user-attachments/assets/0a460d03-675e-4c1d-8bf5-c0fdfed002cb" />
<img width="981" height="797" alt="Screenshot 2025-07-12 120631" src="https://github.com/user-attachments/assets/c8f0e488-869a-4d08-9478-9687b1284239" />
<img width="981" height="968" alt="Screenshot 2025-07-12 120504" src="https://github.com/user-attachments/assets/3d0a2399-541d-4d82-81ca-cdf5ab78a782" />
<img width="981" height="988" alt="Screenshot 2025-07-12 113212" src="https://github.com/user-attachments/assets/49933f9b-2b42-48a5-9fd3-335ba26dca15" />
<img width="981" height="881" alt="Screenshot 2025-07-12 111911" src="https://github.com/user-attachments/assets/6f05af49-65a6-485e-a193-c278ff53a943" />
<img width="981" height="831" alt="Screenshot 2025-07-12 111439" src="https://github.com/user-attachments/assets/f8969d2c-79bb-4d4d-bd37-de2b335124ae" />
<img width="981" height="973" alt="Screenshot 2025-07-12 111144" src="https://github.com/user-attachments/assets/3e33787e-cb8b-45fd-b894-7d6499cec758" />
<img width="981" height="875" alt="Screenshot 2025-07-12 110707" src="https://github.com/user-attachments/assets/8b9c038f-0048-44fb-91fe-315ea6209833" />
<img width="981" height="686" alt="Screenshot 2025-07-12 183504" src="https://github.com/user-attachments/assets/ebb1b6f3-880c-4f25-9fbb-51a374bb8ad0" />
<img width="981" height="874" alt="Screenshot 2025-07-18 000305" src="https://github.com/user-attachments/assets/d84dcb4f-0db2-42d1-9c9a-f43ed47ce155" />
<img width="981" height="645" alt="Screenshot 2025-07-13 180246" src="https://github.com/user-attachments/assets/4fc16777-131c-4189-bc38-7dc31b6c7912" />
<img width="865" height="878" alt="Screenshot 2025-07-18 004724" src="https://github.com/user-attachments/assets/c89050ab-c419-4ed3-82ea-54b1f5f9fd1b" />





---

## Credits

- Designed by me (obviously)  
- Flight gear choices helped and pre-reviewed by **@toby** (hc slack)
- Modeled in Fusion 360  

---

## License

MIT License. Clone it, mod it, crash it, post the footage.

---

when it flies, it'll scream
