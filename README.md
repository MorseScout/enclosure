# Morse Scout enclosure

This repository contains the milestone enclosure exports for the
[Morse Scout](https://morsescout.com/) project.

## Printable revision

The current printable **Chassis** and **Cover** are marked:

```text
V 1.12 2026-OCT-29
```

Check this marking if you already have copies of `chassis.stl` or `cover.stl`.
If either file has an older version marking, or no version marking, download
the current STL before printing.

## File formats

- `3mf/` contains the preferred files for 3D printing.
- `stl/` contains widely compatible mesh exports.
- `step/` contains neutral CAD interchange exports.

The parts were designed in millimetres. Check dimensions and orientation in
your slicer or CAD application before manufacturing. Printer-specific settings,
supports, tolerances, and material selection remain the responsibility of the
builder.

The available filenames differ slightly by format. In particular, the STEP
export contains the two knobs in the combined `knobs.step` file, while the mesh
formats provide separate encoder and potentiometer knobs.

## License

See [LICENSE](LICENSE) for the terms that apply to these files.
