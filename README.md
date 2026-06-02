# TOYOTA-MR2-AW11-ECU-89661-17030-SCHEMATIC
A full schematic of the 1980s MR2 ECU

## Introduction

A full schematic made from reversing a spare ECU. I ended up with an extra ECU when troubleshooting a problem. Not a bad thing to have some rare spares on hand for an ever rarer car.

---

## Why?

I am just curious honestly. I've been on a learning adventure with AVR micro controllers. Inside the old 80s ECU is a big MCU, much like the AVRs elder grandad. How did Toyota get electronic spark and fuel control
working on an MCU from the late 70s? I actually think it was Nippon Denso who designed and made it for Toyota. Maybe Toyota had a hand in development though.

There is already reverse engineering projects out there of the assembly code running on the microcontroller. They managed to hijack the bootup sequence and make the MCU run code from RAM that tells it to dump its
mask ROM over serial. I'll leave that to those people to figure out. I'm more a hardware person.

---

## Hardware

- MCU:
- D151801-1590 (Motorola 6801 Hardware Expanded)
  
- ICs:
- HC120 (Custom)
- HC151 (Custom)
- HC156 (Custom)
- HC157 (Custom)
- HC161 (Custom)
- MF0703E20 (Custom Output Driver)
- T2333 (Custom)
- TD62503P (7 bit High Side Switch)
- TC4069UBP (6 Channel Inverter)
- MB4053 (6 Channel ADC)

---

## Progress

### Done
- Figure out what the MCU is.
- Pin out of ECU drawn.
- 

### Working On
- Finishing tracing all tracks and vias.
- Find out as much as possible about each IC.

### Next
- Check everything drawn in schematic when finished.
- Add notes and descriptions as much as possible.
- Go through schematic and organise everything to be as readable as possible.
- PCB layout to replicate the real thing fairly closely.

---

## Photos

<img width="640" height="483" alt="Genuine-Toyota-Corolla-Gt-Engine-16-4Age-Control-810958995" src="https://github.com/user-attachments/assets/a825731e-1560-4fdb-939f-b472e2fd4f66" />

---

## Resources

- References

---
