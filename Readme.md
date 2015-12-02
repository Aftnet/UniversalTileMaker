#Universal Tile Maker

This script creates all the 39 PNG images that are used for Tile assets in a Universal Windows 10 application.
It is optimized to generate transparent tiles which will use the system's accent color as default and that look consistent with Microsoft's own apps.

##Requirements

Inkscape, either installed or standalone: the actual conversion from SVG to PNG is handled by it.

If not located in the default install location (C:\Program Files\Inkscape\inkscape.exe), edit
```
$inkScapePath = "C:\Program Files\Inkscape\inkscape.exe"
```
to point to the correct place.

##Usage

Edit "Icon Master.svg", replacing the five white placeholder logos with five copies of your logo having the same sizes as them.
- Pay particular attention to put each logo replacement in the same layer as the origial placeholder.
- Ensure each logo is centered on the provided orange plate.
- Do not change the orange plates' color, otherwise the generated PNGs will not have a transparent background
