# Changelog
This file will document changes to this project.

Unfortunately, [Semantic Versioning](https://semver.org/) is not compatible with Dwarf Fortress raw mods because most changes would be `MAJOR` save incompatible changes, so this project uses a custom versioning convention instead; for a given version number `MAJOR.MINOR.PATCH`, increment the:
- `MAJOR` version for a large overhaul of many existing objects, or the addition of a new class of features/objects that were previously impossible. This would usually correspond with new major DF releases, and therefore is likely not compatible with existing saves, or even previous DF versions.
- `MINOR` version for new objects being added or large changes to existing objects; likely not save compatible.
- `PATCH` version for bug fixes, _small_ edits to objects, code cleanups, or documentation changes. Almost always compatible with previous saves.

The "Unreleased" heading is for changes that are in the repo but not in any published version (they are probably not ready yet).

The meaning of each subcategory of change is as follows:
- Added: A new file, section in a file, or object was created, or a feature added to an object. If a creature ID exists but is unimplemented/has `[DOES_NOT_EXIST]` and cannot be spawned even in the testing arena, this doesn't count as being added.
- Changed: An existing file or object/property has been edited/changed. Changes that will not be recorded include most code comments inside files, updates to `CHANGELOG.md` that are simply recording other changes, or `README.md` updating the mod version or promoting something from "planned content" to "content".
- Removed: An object, property, or section of a non-raw file was deleted.
- Fixed: A bug/error or a typo was fixed. If it's a fix, it will not be recorded under any of the above headings.

## [Unreleased]

### Misc - 2 Added, 4 Changed

#### Added
- `CHANGELOG.md` file
- Info in `README.md` about all the planned content for the mod

#### Changed
- Restructured the mod to be more "modular" so you can have say, the EOTE content but not the nomai, if you finished the DLC before the main game for example
- Updated `README.md` installation instructions, make sure to check those instructions!
- `README.md` formatting changes to make for easier reading
- Edited one of the `README.md` starting paragraphs to reflect that the DF RAW LS is out of alpha now

### Spoiler Free - 3 Added, 2 Changed

#### Added
- `SYMBOL` for hearthian names (all based off types of stone)
- Hearthian civ sphere alignments
- Marshmallows! Created by hearthians using sugar and syrup.

#### Changed
- Hearthian civs can now use underground crops, like sweet pods.
- Made hearthian eggs more accurate to them being amphibians; no more hard shell, just jelly!

### Nomai - 1 Added, 4 Changed, 2 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Added
- Nomaian civ sphere alignments

#### Changed
- Changed nomaian civ to speak dwarven language (just so they're distinct from hearthians that way)
- Made nomaian bones more fragile
- Adjusted the `SYMBOL` set that the nomai use; they will now name temples, libraries and their civilizations/misc stuff after the concepts of thought and truth, and also the mythic in the case of temples
- Nomai now have variations in their antler sizes/proportions, making them more unique

#### Fixed
- Nomaian antler material and tissue is now properly described as "antler" instead of "horn"
- Typo in nomai description saying "horns" instead of "antlers" corrected
</details>

### Other Base Game - 2 Added, 3 Changed, 1 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Added
- Gave anglerfish `[EXTRAVISION]` so that they're not basically helpless despite their size now
- Anglerfish tentacles and spiked rear fins, to be more accurate to the game!

#### Changed
- Made anglerfishes teeth much bigger/proportionally accurate
- Made anglerfish only spawn in "savage" oceans now
- Made anglerfish eggs more accurate to them being fish; no more hard eggshell, just jelly!

#### Fixed
- Fixed tissues for anglerfishes rod and lure; now the rod is made of skin, fat, muscle and bone, and the lure is a unique tissue
</details>

### Echoes of the Eye - 5 Added, 5 Changed, 1 Removed, 1 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Added
- Mentioned in `README.md` about the owlk civ "board game" toy (was already in the mod, just not mentioned)
- Some more owlk civ sphere alignments
- Rappigs. Huge, 4-eyed creatures resembling pigs with the ears and tails of rabbits.
- Dragonfish. Large (bigger than a human!) fish capable of flight, and which can breathe air. They are named for their fins, which bear a striking resemblance to the wings of a dragonfly.
- Chordochestrions; a one-stringed instrument played with a bow, and it has an old-fashioned music box built into it.

#### Changed
- Edited owlk arm, hand, finger and leg sizes; all are a big bigger/longer
- Adjusted owlk colors; their nails and hooves now share the same color as their finger scales, and their feathers and skin now have more variety in shades of green, as well as greys.
- Put scales on the owlks lower legs and forearms
- The owlk civ no longer uses spears or maces, but in return now have access to pickaxes (for digging), greataxes, two-handed swords (well, _they_ only use one hand), halberds, and pikes
- Adjusted the `SYMBOL` set that owlks will use; they will now name a lot of things based on the concepts of protection, the mythic, mystery, light, and darkness

#### Removed
- Removed feathers from owlks forearms

#### Fixed
- Removed `LENGTH` body appearance modifier from owlks
</details>

## [v0.1.1] - 2021-12-13

### Misc - 1 Added, 1 Changed

#### Added
- Links to my other mods in `README.md`

#### Changed
- Made `LICENSE` file more readable

### Other Base Game - 2 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Fixed
- Removed `MUSCULAR_ONLY` from jellyfishes electricic shock "unconsciousness" symptom
- Fixed anglerfish `CREATURE_TILE`
</details>

### Echoes of the Eye - 1 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Fixed
- Removed empty argument from owlks horn length `BP_APPEARANCE_MODIFIER`
</details>

## [v0.1.0] - 2021-12-10
The initial public release. It contains the following:
- Full Mod, Only Base Game Spoilers, and Spoiler Free versions of the mod.
- Hearthian creature and civ
- Ghost matter

### Nomai
- Nomai creature and civ

### Other Base Game
<details>
  <summary>Spoiler warning</summary>

- Giants Deep Jellyfish
- Bramble Anglerfish
- Star platinum metal and ore
</details>

### Echoes of the Eye
<details>
  <summary>Spoiler warning</summary>

- Owlk creature and civ
- "Echoes" boardgame, used by owlk civ
</details>

<!--Links-->
[Unreleased]: https://github.com/Crabman-DF-Mods/dwarven-wilds/compare/v0.1.1...HEAD
[v0.1.1]: https://github.com/Crabman-DF-Mods/dwarven-wilds/compare/v0.1.0...v0.1.1
[v0.1.0]: https://github.com/Crabman-DF-Mods/dwarven-wilds/releases/tag/v0.1.0