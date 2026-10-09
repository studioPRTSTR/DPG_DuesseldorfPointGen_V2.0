# Dot Pattern Generator — Düsseldorf RRX Point Generator V2.0

A browser tool that generates dot patterns at real size (in millimetres).

## Principle

Each **point** is a large boundary circle filled with small circles. The small circles are laid out like a spray bar: rows of circles along a slanted line (the stagger angle), repeated at a fixed vertical spacing. Only the circles that fit completely inside the boundary are kept.

Points come in three sizes (100 % and two smaller sizes you set) and are arranged into:

- a **single point** with its dimensions
- a **5×3 grid** and a **gradient strip** that compare the three sizes
- **text**: the letters are covered with a grid of points, and each point shrinks from left to right across its letter
- a **letter** view that shows every small circle in one letter

Each view can be exported as a PNG, or printed or saved as a PDF on A4/A3 at a standard scale.

## Usage

Open `index.html` in a browser. Nothing needs to be installed.
