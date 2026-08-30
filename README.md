# Adjustable Stand for the Spektrum iX14

A folding, indexed-position desk stand designed for the square carrying handle on the Spektrum iX14 transmitter.

The stand mounts without permanently modifying the radio, folds against the back for storage, and uses a spring-loaded ball plunger with a detent mechanism to provide repeatable viewing positions.

V2 introduces **SMUT™** — **S**ide **M**ount **U**nit **T**echnology: a reusable side-mounted architecture that places independent retained pivots on the individual handle rails instead of relying on a single rear-mounted clamp.

## Which Version Should I Build?

**Build V2 unless you specifically want to reproduce the original prototype.**

| Version | Status | Design | Recommendation |
|---|---|---|---|
| [V2](v2/) | Current design | SMUT™ side-mount assemblies with independent pivots and a replaceable detent ring | **Recommended** — more compact, easier to align, leaves more of the handle open, and is substantially more functional |
| [V1](v1/) | Legacy prototype | CRAP™ rear-mount platform with one external clamp and a common through-bolt pivot | Preserved for reference; development stopped after the concept was proven and moved to V2 |

V1 was successfully printed, assembled, and used as a prototype, but it occupies more handle space, has a taller folded profile, and is less convenient than V2.

It is not the version recommended for a new build.

## Product Photos

Photographs of the actual printed and assembled stands are included with each version:

- [V1 product images](v1/documentation/product-images/) show the original prototype as separate components, assembled, folded, and extended.
- [V2 product images](v2/documentation/product-images/) show the recommended design as separate components, assembled, folded, extended through its usable range, and installed with handle clearance. The V2 collection also includes a direct V1-versus-V2 extension comparison.

These are photographs of physical builds, not CAD renders. For installation order and hardware placement, use the version-specific assembly instructions and printable assembly guide.

## V2 — Recommended SMUT™ Build

V2 is the first physically validated implementation of SMUT™ and includes:

- independent left and right handle-mounted case assemblies;
- self-aligning clamp clearance for radio-to-radio manufacturing variation;
- separate retained pivots that remain free after their hardware is tightened;
- replaceable, keyed detent ring that can be printed as a contrasting wear item;
- square keyed blocks that carry stand shear and twisting loads;
- reinforced heat-set-insert collars;
- directional caps marked `L` and `R`;
- a 110 mm stand with paintable chamfers and editable multicolor text;
- PETG-HF print profiles and tested Bambu Studio plate arrangements.

### Why SMUT™?

**Because rear-entry solutions are unnecessarily restrictive.**

By moving the pivot assemblies to the individual handle rails, SMUT™ preserves full carrying-handle access while providing independent retained pivots, positive indexed positioning, greater range of motion, and a more compact folded profile.

### Start Here

- [V2 assembly instructions](v2/documentation/assembly-instructions/)
- [V2 printable assembly guide](v2/documentation/exploded-view/)
- [V2 Bambu Studio profile](v2/bambu-studio-3mf/)
- [V2 hardware buy list](v2/buy-list/)
- [V2 STL files](v2/stl/)

> **Validation status:** The complete V2 assembly has been physically validated on the radio, including the printed parts, inserts, clamp fit, pivots, stand interface, production M4 × 8 spring-loaded ball plunger, positive detent engagement, full range of motion, folded position, and carrier fit.

## V1 — Legacy CRAP™ Prototype

V1 remains available as the original implementation of **CRAP™** — **C**audal **R**ear **A**nchoring **P**latform — and the project's proof-of-concept design.

Its directory contains the printable models, Bambu Studio project, hardware list, and abbreviated assembly documentation needed to reproduce it.

- [V1 assembly instructions](v1/documentation/assembly-instructions/)
- [V1 printable assembly guide](v1/documentation/exploded-view/)
- [V1 hardware buy list](v1/buy-list/)
- [V1 STL files](v1/stl/)

V1 was prototyped in PLA using largely default Bambu settings.

No further V1 design development is planned; use V2 for the more practical final implementation.

In architectural terms, development moved from CRAP™ to SMUT™.

## AI-Assisted Design and Development

This project was developed with AI assistance.

The stand began with a practical design goal: create a compact, folding stand for the Spektrum iX14 that could mount to the existing square carrying handle without permanently modifying the transmitter.

AI was used throughout the iterative development process to help:

- analyze physical measurements and fitment observations;
- translate design requirements into 3D geometry;
- generate and revise printable models;
- evaluate clearances, interfaces, pivots, detent geometry, and hardware placement;
- create prototype variations based on physical test results;
- organize the versioned design artifacts;
- generate and maintain assembly documentation.

The development process was highly iterative:

**measure → model → print → physically test → revise**

The generated geometry was not assumed to be correct simply because it looked correct in CAD.

Multiple physical prototypes and fitment iterations were used to refine the design, and the repository distinguishes between the original V1 proof-of-concept and the more functional V2 design that resulted from that process.

In other words: AI helped design it, but the printer and the actual radio got the final vote. :-)

## Repository Organization

Each version is self-contained.

| Directory | Contents |
|---|---|
| `stl/` | Individual printable parts |
| `bambu-studio-3mf/` | Ready-to-slice Bambu Studio project and version-specific printing notes |
| `buy-list/` | Version-specific hardware requirements |
| `documentation/assembly-instructions/` | Detailed Markdown assembly instructions |
| `documentation/exploded-view/` | Printable PDF assembly guide and its linked page images |
| `documentation/product-images/` | Photographs of the actual printed parts and completed assembly |

Version-specific dimensions, hardware, slicer settings, and assembly procedures live inside the corresponding version directory so that the root README does not become another stale copy of those details.

## Important Safety Information

- This is a desk and simulator stand, **not a replacement carrying handle**.
- Inspect every print, insert, and fastener before use and periodically afterward.
- Confirm stability before placing the radio on an elevated, uneven, or windy surface.
- Never force the stand beyond its intended range of motion.
- Read the repository [`DISCLAIMER.md`](DISCLAIMER.md) before printing or using the design.

This is an independent project and is not affiliated with or endorsed by Horizon Hobby or Spektrum.

## License

This project is provided under the [Creative Commons Attribution-NonCommercial 4.0 International License](LICENSE).

You may print, copy, share, and modify the files for noncommercial purposes with attribution.

Changes must be identified.

The original files and derivatives may not be sold or otherwise used commercially without separate permission from the creator.

## Why?

Because apparently the natural progression of:

**RC helicopters + 3D printing + AI + excessive iteration**

is spending an unreasonable amount of time designing a stand for a radio that already has a handle.

And that's pretty kewl. :-D
