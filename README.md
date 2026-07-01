# Summary

Flan's mod 1.12 patches containing minor improvements. Current list of imrpovements:
- Fix vehicle velocity recovery when a vehicle goes to NaNville (patch from Flan's mod Orion rework)
- Allow replacing vehicle engine by right-clicking on core parts(usually wheel)
- Allow crafting guns from different types of logs
- Fix Sentry Gun target detection (broken distance check and targeting unreachable entities), barrels position, guidance to target
- Rebalance Sentry Gun: add several firing modes, allow targeting mobs, make it targetable by _some_ mobs, readjust firing angles and lower fire rate.

# Applying patches:

- Install [Git](https://github.com/git-guides/install-git)
- clone the [Original git repository](https://github.com/FlansMods/FlansMod) or download and unzip the [source archive](https://github.com/FlansMods/FlansMod/archive/refs/heads/1.12.2.zip)
- Download the [flan.patch](https://github.com/le0nklcpp/flan-patch/raw/refs/heads/main/flan.patch) from this repository
- Run `git apply flan.patch` from Flan's mod directory
- Build the mod using the standard build instructions

# License

The patch file code is based on the original project source code, and therefore is distributed under the same license as the Flan's Mod. See LICENSE.txt for details
