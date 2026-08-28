# Adjustable Stand for the Spektrum iX14

A folding, indexed-position desk stand designed for the square carrying handle on the Spektrum iX14 transmitter.

The stand mounts without permanently modifying the radio, folds against the back for storage and uses a spring-loaded ball plunger with a detent mechanism to provide repeatable viewing positions.

## Which version should I build?

**Build V2 unless you specifically want to reproduce the original prototype.**

| Version | Status | Design | Recommendation |
| --- | --- | --- | --- |
| [V2](v2/) | Current design | Two compact assemblies mount around the individual handle rails, with independent pivots and a replaceable detent ring | **Recommended** - more compact, easier to align, leaves more of the handle open and is substantially more functional |
| [V1](v1/) | Legacy prototype | One external clamp spans the center of the handle and uses a common through-bolt pivot | Preserved for reference; development stopped after the concept was proven and moved to V2 |

V1 was successfully printed, assembled and used as a prototype, but it occupies more handle space, has a taller folded profile and is less convenient than V2. It is not the version recommended for a new build.

## V2 - recommended build

V2 is the refined internal-handle design and includes:

- Independent left and right handle-mounted case assemblies
- Self-aligning clamp clearance for radio-to-radio manufacturing variation
- Separate retained pivots that remain free after their hardware is tightened
- Replaceable, keyed detent ring that can be printed as a contrasting wear item
- Square keyed blocks that carry stand shear and twisting loads
- Reinforced heat-set-insert collars
- Directional caps marked `L` and `R`
- A 110 mm stand with paintable chamfers and editable multicolor text
- PETG-HF print profiles and tested Bambu Studio plate arrangements

Start here:

- [V2 assembly instructions](v2/documentation/assembly-instructions/assembly-instructions.md)
- [V2 printable assembly guide](v2/documentation/exploded-view/ix14-v2-assembly-guide.pdf)
- [V2 Bambu Studio profile](v2/bambu-studio-3mf/bambu-studio-profile.md)
- [V2 hardware buy list](<v2/buy-list/iX14 Stand v2 — Buy List.md>)
- [V2 STL files](v2/stl/)
- [V2 Bambu Studio project](v2/bambu-studio-3mf/ix14_v2_stand_all_objects.3mf)

> **Validation status:** the V2 printed parts, inserts, clamp fit, pivots, stand interface and complete mechanical assembly have been physically validated. Final detent behavior remains pending physical verification with the production M4 spring-loaded ball plunger.

## V1 - legacy prototype

V1 remains available as the original proof-of-concept design. Its directory contains the printable models, Bambu Studio project, hardware list and abbreviated assembly documentation needed to reproduce it.

- [V1 assembly instructions](v1/documentation/assembly-instructions/assembly-instructions.md)
- [V1 printable assembly guide](v1/documentation/exploded-view/ix14-v1-assembly-guide.pdf)
- [V1 hardware buy list](<v1/buy-list/iX14 Stand v1 — Buy List.md>)
- [V1 STL files](v1/stl/)
- [V1 Bambu Studio project](v1/bambu-studio-3mf/ix14_v1_stand_all_objects.3mf)

V1 was prototyped in PLA using largely default Bambu settings. No further V1 design development is planned; use V2 for the more practical final implementation.

## Repository organization

Each version is self-contained:

| Directory | Contents |
| --- | --- |
| `stl/` | Individual printable parts |
| `bambu-studio-3mf/` | Ready-to-slice Bambu Studio project and version-specific printing notes |
| `buy-list/` | Version-specific hardware requirements |
| `documentation/assembly-instructions/` | Detailed Markdown assembly instructions |
| `documentation/exploded-view/` | Printable PDF assembly guide and its linked page images |

Version-specific dimensions, hardware, slicer settings and assembly procedures live inside the corresponding version directory so that the root README does not become another stale copy of those details.

## Important safety information

- This is a desk and simulator stand, not a replacement carrying handle.
- Inspect every print, insert and fastener before use and periodically afterward.
- Confirm stability before placing the radio on an elevated, uneven or windy surface.
- Never force the stand beyond its intended range of motion.
- Read the repository [use-at-your-own-risk disclaimer](DISCLAIMER.md) before printing or using the design.

This is an independent project and is not affiliated with or endorsed by Horizon Hobby or Spektrum.

## License

This project is provided under the [Creative Commons Attribution-NonCommercial 4.0 International License](LICENSE).

You may print, copy, share and modify the files for noncommercial purposes with attribution. Changes must be identified. The original files and derivatives may not be sold or otherwise used commercially without separate permission from the creator.
