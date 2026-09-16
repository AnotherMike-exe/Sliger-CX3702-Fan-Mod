# Sliger CX3702 - Fan Mod

*A 3D-printable front panel adaptor that adds triple 120mm fan cooling to the Sliger CX3702 (and compatible face plates).*

<table>
<tr>
<td><img src="Assembly Images/ISO Overall.png" alt="Overall view of the assembled fan mod"></td>
<td><img src="Assembly Images/Full Assembly - Exploded.png" alt="Exploded view of the full assembly"></td>
</tr>
</table>

## Description

This is a 3D-printable spacer for the Sliger CX3702 front panel (and any
Sliger chassis sharing the same face plate and magnetic-washer mounting system). It
allows mounting three 120mm fans, for additional airflow.

## Usage

**Print settings:**

- Frame and standoff parts: PETG, 15% infill, supports enabled.
- Button: multi-material print, PETG/PLA.

**Files:**

| File                                     | Purpose                                                                |
| ---------------------------------------- | ---------------------------------------------------------------------- |
| `Sliger - CX3702 - Fan Mod.3mf`          | Orca Slicer print file. Holds every part, laid out and ready to slice. |
| `Sliger - CX3702 - Fan Mod - Frame.3mf`  | Frame part on its own.                                                 |
| `Sliger - CX3702 - Fan Mod - Button.3mf` | Button part on its own. Print as multi-material, PETG/PLA.             |
| `Sliger - CX3702 - Fan Mod.stp`          | STEP file, for other CAD tools.                                        |
| `Sliger - CX3702 - Fan Mod.stl`          | Combined STL mesh, for slicers without STEP or 3MF support.            |
| `Sliger - CX3702 - Fan Mod.3dm`          | Native Rhino source file.                                              |

Build steps:

1. Remove the four existing magnetic washers and their 3D-printed standoff/housings from the front panel.

2. Pull the magnetic washers out carefully — they're reused later, so avoid snapping them.

3. Install M3 x 30mm standoffs in each location that had a magnet. (I used 20mm and 6mm standoffs stacked, with a longer screw for mine) The cavity only has 30mm between the top of the faceplate's standoff and the top of the hole on the adaptor ring, so plan accordingly if you have long stems on your standoffs.
   
   <table>
   <tr>
   <td><img src="Assembly Images/Standoff Assembly - Exploded - Enlarged.png" alt="Exploded detail of the standoff assembly" width="400"></td>
   <td><img src="Assembly Images/Standoff Assembly - Assembled - Enlarged.png" alt="Assembled detail of the standoff assembly" width="400"></td>
   </tr>
   </table>

4. Press-fit the magnetic washers into the adaptor frame's washer pockets.

5. Mount the three 120mm fans to the adpator using their included screws.

6. Route the fan cables to the right of the last drive (left of the power button and USB ports) through the hole leading into the chassis. You'll likely need fan extenders to get to the headers with enough slack to still take off the panel easily.

7. Mount the frame to the standoffs — the screws pass through the magnetic washers into the standoffs, the same way the factory frame attached. (May need longer screws depending on your standoffs.)

8. Insert the power button extender into its hole in the adaptor frame.

   <table>
   <tr>
   <td><img src="Assembly Images/Button Assembly - Exploded - Enlarged.png" alt="Exploded detail of the button assembly" width="400"></td>
   <td><img src="Assembly Images/Button Assembly - Assembled - Enlarged.png" alt="Assembled detail of the button assembly" width="400"></td>
   </tr>
   </table>

9. Attach the assembled frame to the chassis exactly as the original factory frame
   attached.

**Hardware used:**

| Item                     | Value                                                                           |
| ------------------------ | ------------------------------------------------------------------------------- |
| Standoffs                | (4) M3 x 30mm Standoffs (shorter works with longer screws — see fit note above) |
| Standoff mounting screws | (4) M3 Phillips head (factory screw, reused)                                    |
| Fans                     | (3) 120mm                                                                       |
| Fan Extenders            | (3) PC fan cable extenders                                                      |

Fan cables route through the chassis pass-through hole between the last drive bay and
the power/USB area — stock fan cables may be too short, so 120mm fan extension cables
are recommended.

Assembly photos are in [`Assembly Images/`](Assembly%20Images/).

## Attributions

- Designed for the Sliger CX3702 chassis and compatible face plates — Sliger is not
  affiliated with this project.
- Released under [CC BY 4.0](LICENSE). Use, modify, and remix freely, for any purpose, with credit to the original designer.
