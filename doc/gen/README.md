# PCB

Board size: 55.0x30.0 mm (2.17x1.18 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: None
- Layers: 2
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness [µm]| Material        | Er        | Loss tan     |
|----------------------|----------------------|------------------|---------------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |               |                 |           |              |
| F.Paste              | Top Solder Paste     |                  |               |                 |           |              |
| F.Mask               | Top Solder Mask      | Green            |            10 |                 |           |              |
| F.Cu                 | copper               |                  |            35 |                 |           |              |
| dielectric 1         | core                 |                  |          1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |            35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   | Green            |            10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |               |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |               |                 |           |              |

# Important sizes

Clearance: 0.22 mm (9 mils)

Track width: 0.25 mm (10 mils)

- By design rules: 0.2 mm (8 mils)

Drill: 0.3 mm (12 mils)

- Vias: 0.4 mm (16 mils) [Design: 0.3 mm (12 mils)]
- Pads: 0.3 mm (12 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.6/0.3 mm (24/12 mils)

- By design rules: 0.4/0.2 mm (16/8 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 202 (thru: 202 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.1 mm (4 mils)

- By design rules: 0.1 mm (4 mils)

Eurocircuits class: 6D
- Using min drill 0.25 mm for an OAR of 0.13 mm


# General stats

Components count: (SMD/THT)

- Top: 0/0 (NONE)
- Bottom: 52/1 (SMD + THT)

Defined tracks:

- 0.4 mm (16 mils)
- 0.5 mm (20 mils)

Used tracks:

- 0.25 mm (10 mils) (157) defined: no
- 0.4 mm (16 mils) (33) defined: yes
- 0.5 mm (20 mils) (64) defined: yes

Defined vias:


Used vias:

- 0.6/0.3 mm (24/12 mils) (Count: 202, Aspect: 2.7 A) defined: no

Holes (excluding vias):

- 0.2 mm (8 mils) (9)
- 1.5 mm (59 mils) (1)
- 1.7 mm (67 mils) (4)

Oval holes:


Drill tools (including vias and computing adjusts and rounding):

- 0.3 mm (12 mils) (9)
- 0.4 mm (16 mils) (202)
- 1.6 mm (63 mils) (1)
- 1.8 mm (71 mils) (4)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Total  |             150 |     116.10 |      0.58 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



