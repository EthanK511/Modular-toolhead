# Ender 3 V2 Modular Quick‑Swap Toolhead (Pen + Light Cutter)

A Hack Club **Rework** project: a **custom modular toolhead system** for an Ender 3 V2 that allows quick swapping between:
- Normal printing (Sprite direct drive)
- A **pen/marker plotting module**
- A **light-duty cutting module (maybe)** designed for thin paper/vinyl (to be validated)

This project focuses on **original hardware modifications**:
- A **fixed toolhead backplate** on the carriage
- A **magnetic + alignment-pin quick-swap interface** for interchangeable front modules
- Purpose-built modules (pen + cutter) with repeatable alignment

## Printer baseline
- Ender 3 V2
- Sprite direct drive
- PEI build plate
- CR Touch

## Design decisions (initial)
- Pen up/down will be done via **Z-axis motion only** (spring/compliance in the pen mount; no servo).

## Safety notes
- A cutting tool can be dangerous. The cutter module will be designed with:
  - guarded blade geometry where possible
  - limited downward force / travel
  - an emergency-stop mindset (stay with the machine when testing)
- No high-voltage modifications.

## What “done” looks like (acceptance goals)
- [ ] Backplate + quick-swap interface mounts securely and repeatably
- [ ] Pen module can draw consistent lines (repeatable Z contact)
- [ ] Paper hold-down method works on the build plate without damaging it
- [ ] Documentation: drawing workflow + recommended settings
- [ ] Build guide + BOM + photos

## Repo structure
- `cad/` – CAD sources + exported STLs/STEPs
- `docs/` – build + usage + drawing workflow
- `bom/` – parts list and sources
- `JOURNAL.md` – time tracking log required by Rework

## Status
Repo scaffolded; beginning measurement + CAD design.