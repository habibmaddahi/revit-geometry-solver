# Revit Geometry Solver

Lock two values you know and get Revit family formulas for everything else.

**Live site:** https://habibmaddahi.github.io/revit-geometry-solver/

Sheets:

- **A-101 Arc:** radius, included angle, chord, sagitta, arc length
- **A-102 Right triangle:** sides a, b, c and angles A, B
- **A-103 Array:** total length, panel count, gap and spacing, with different first and last panel thicknesses
- **A-104 Stair:** risers from floor-to-floor height, with IBC/IRC checks
- **A-105 Polygon:** side, radius to corners, apothem, across flats
- **A-106 Snap to module:** round a dimension down, to nearest or up to a module

Every formula uses Revit syntax and units, and you can rename the parameters to match your family.

## Updating the site

The whole app is a single `index.html` file. Edit it, commit, and push to `main`.
GitHub Pages rebuilds the site automatically, usually in about a minute.
