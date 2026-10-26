# Watch-3D

[![License](https://img.shields.io/badge/License-GPL%203.0-blue.svg)](https://opensource.org/license/gpl-3-0/)

3D files (STEP and STL) for the case of the [ZSWatch](https://github.com/ZSWatch/ZSWatch) (`zswatch@1` PCB from [Watch-HW](https://github.com/ZSWatch/Watch-HW)).

Print settings, other parts needed and the step-by-step assembly guide are on **[zswatch.dev/docs/getting-started/assembly](https://zswatch.dev/docs/getting-started/assembly)**.

## Directory Breakdown

- **`step/ZSWatch-Assembled.step`**: Full assembly (case, PCB, display, battery). Use it as the reference when modifying the case.
- **`stl/`**: Print-ready parts.

## Parts

| File | Qty | Description |
| --- | --- | --- |
| `stl/clock_housing.stl` | 1 | Main housing with strap lugs. Holds the display, buttons and PCB. |
| `stl/bottom.stl` | 1 | Back plate. |
| `stl/bottom_hr.stl` | 1 | Back plate for the heart rate extension board, with an opening in the middle. Use instead of `bottom.stl`. |
| `stl/bottom_hr_center.stl` | 1 | Cover glued into the opening of `bottom_hr.stl`. Heart rate extension only. |
| `stl/insert.stl` | 1 | Sits on the back of the display and holds the battery. |
| `stl/button.stl` | 4 | Buttons that sit in the side holes of the housing. |
| `stl/button_holder.stl` | 4 | U-shaped clips that hold the buttons in place during assembly. |

## Printing and Assembly

See the [assembly guide](https://zswatch.dev/docs/getting-started/assembly) for print settings, the other parts you need (battery, screws, strap) and the assembly steps.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## Maintainer

- [Jakob Krantz](mailto:mail@jakobkrantz.se)
