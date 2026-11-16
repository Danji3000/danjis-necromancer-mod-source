# Danji's Necromancer Mod v1.1.0 - DLL source

Download **GitHub-Source-v1.1.0.zip** from this repository and extract it first.
The archive contains the complete source tree for all four native DLLs,
third-party notices, build scripts, SHA256 hashes and build verification results.
There are no compiled DLLs or game assets in this archive.

## Build after extracting

Use Windows x64, Python 3.12 (tested 3.12.14), and Zig 0.15.2.
Set the FP_ZIG environment variable to your zig.exe path, then run:

    py -3.12 build_all.py

Run this command from the extracted folder containing build_all.py.
Read README.md and BUILD_EN.txt inside the archive for full instructions.
All four verified rebuilds matched the distributed v1.1.0 DLLs byte-for-byte.

## Modules

- Deathblight
- NecromancerSpells
- StaffSummonRange
- IGetGud

## Review status

Published for transparency and security review of the Nexus quarantine.
False positives are suspected but not confirmed. Local scan results do not
establish vendor clearance. Third-party licensing notices are retained inside
the archive; no additional general redistribution license is specified.

Mod page: https://www.nexusmods.com/eldenring/mods/11615
