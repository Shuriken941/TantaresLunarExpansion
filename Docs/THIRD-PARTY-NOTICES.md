# Asset provenance — private personal-use build

This package was assembled for the requesting user's personal KSP installation. It is not a public release or a grant to redistribute Tantares assets.

## Tantares v28.0

- Author: Tantares / Leo Semprini and upstream contributors.
- Source: https://github.com/Tantares/Tantares/tree/v28.0
- Source commit: `687aea8a7331e8ddcdcf8e597ce3eb9235c573a9`.
- Official `tantares.zip` SHA-256: `0640fd75a6125469a86ac33c366b2c6896840ca582622bad4dace66297cfd51c`.
- Original source models: `GameData/Tantares/parts/core_lk_v2/lk_v2_crew_s0p5_1.mu` and `GameData/Tantares/spaces/core_lk_v2/lk_v2_crew_s0p5_1_interior.mu`.
- Private modified copies: `Models/lk_m_exterior.mu` and `Models/lk_m_interior.mu`. The reworked upper hull uses the original panels and UVs. The internal passage and its lining follow the forward-shifted cut. The original pilot station, windows and instruments are retained through the original INTERNAL configuration.
- Five original textures are included unchanged in the private build: exterior `a1.dds`, `n1.dds`, `basic_white.dds`; interior `i1.dds`, `w1.dds`. Local loading preserves the glass alpha channel and avoids unresolved texture aliases during model loading. These remain Tantares assets under the same private-use scope.
- Craft layouts were adapted from the official `[LK].craft` and `[Soyuz] LOK.craft` to use the new cabin, transfer compartment and matching APAS ports. The LOK companion is updated to actual v28 part names.

License evidence is inconsistent: CKAN metadata identifies CC-BY-NC-SA-4.0, while the official v28 archive `Readme.txt` says **All rights reserved.** This package does not resolve that inconsistency or assert a redistribution license. The private modifications are included at the user's express request for personal use. Seek clarification from the upstream rights holder before any public redistribution of these derived files.

## FreeIVA

- Source: https://github.com/FirstPersonKSP/FreeIva/tree/0.2.20.2
- Stable commit: `c013cb43ae19a8e0486cf472a68287d18f2f85f4`.
- `Models/lk_m_shell.mu` is derived from `GameData/FreeIva/Tantares/lk_v2_crew_s0p5_1.mu`; the roof was clipped to create a 0.56 m bore.
- The upstream folder license states: **The files in this directory are derived from Tantares by Leo Semprini, used under CC-BY-NC-SA-4.0: https://creativecommons.org/licenses/by-nc-sa/4.0/COPYING**.
- Attribution: Tantares / Leo Semprini; FreeIVA / FirstPersonKSP contributors; aperture modification by Tantares Lunar Expansion contributors.
- This derived shell is offered under the same [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) terms, subject to the upstream rights stated above.
- FreeIVA's plugin binary and generic assets are not bundled. Its generic assets must not be assumed to share the Tantares folder license.

## Original expansion work

The new transfer compartment mesh, texture and editable Blender file, configuration patches, validation/build scripts and documentation are original expansion work, licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). This grant applies only to that original work, not to the private Tantares model copies.

Geometry tools use the separately obtained `io_object_mu` parser/exporter: https://github.com/taniwha/io_object_mu at `ff04234928b2e66f92d2d1325225e9a29f0b415c`. Its source is not bundled. Pillow is a build-only dependency. No KSP, Unity, ModuleManager, B9PartSwitch, Shabby, Resurfaced or FreeIVA plugin binaries are included.
