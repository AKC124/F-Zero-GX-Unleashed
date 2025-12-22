Patch.bat will uncompress the contents of 1 and 3 into 2 and 4 respectively, then copy the FMIs from 2 to 4, then compress the vehicle files from 4 to 5.

Patch Pre-uncompressed skips the first step, only copying the FMIs from 2 and 4 and then compressing 4 into 5.

Example operation: patching enhanced/xtreme skins mix with QM-style boosters.

1. Copy vehicle_p and _e.lz.arcs from QM-style boosters to folder 1
2. Copy xtreme vehicles to your iso, THEN copy "enhanced" vehicles from this mod to your iso.
3. Copy the vehicle_p and _e.lz.arcs from your iso to folder 3
4. Run Patch.bat
5. Retrieve patched files from folder 5.