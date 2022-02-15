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

## [v1.0.0] - 2022-02-15

### Misc - 3 Added, 4 Changed

#### Added
- `CHANGELOG.md` file
- Info in `README.md` about all the planned content for the mod
- Instructions about when it's safe spoiler-wise to install each module of the mod

#### Changed
- Restructured the mod to be more "modular" so you can have say, the EOTE content but not the nomai, if you finished the DLC before the main game for example
- Updated `README.md` installation instructions, make sure to check those instructions!
- `README.md` formatting changes to make for easier reading
- Edited one of the `README.md` starting paragraphs to reflect that the DF RAW LS is out of alpha now

### Spoiler Free - 3 Added, 2 Changed

#### Added
- Hearthian civ sphere alignments; this means now they'll pay more for trade goods relating to the spheres of music, travelers, water, stars, wisdom, and courage, but less for things relating to treachery and war. This also supposedly makes them more often worship forces related to those things they like, and less often for the disliked things
- `SYMBOL` for hearthian names (all based off types of stone)
- Marshmallows! Created by hearthians using sugar and syrup

#### Changed
- Hearthian civs can now use underground crops, like sweet pods
- Made hearthian eggs more accurate to them being amphibians; no more hard shell, just jelly and yolk!

### Nomai - 1 Added, 4 Changed, 2 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Added
- Nomaian civ sphere alignments; this works the same as for hearthians (pay more or less depending on the alignments), but in their case, they have a preference for spheres of wisdom, truth, scholarship, festivals, reverly, travelers, and the stars, whereas they dislike lies

#### Changed
- Changed nomaian civ to speak dwarven language (just so they're distinct from hearthians in language)
- Made nomaian bones more fragile (less dense, and lower impact/compressive yields/fracture points)
- Adjusted the `SYMBOL` set that the nomai use; they will now name temples, libraries and their civilizations/misc stuff after the concepts of thought and truth, and also the mythic in the case of temples
- Nomai now have variations in their antler sizes/proportions, making them more unique from one another

#### Fixed
- Nomaian antler material and tissue is now properly described as "antler" instead of "horn"
- Typo in nomai description saying "horns" instead of "antlers" corrected
</details>

### Dark Bramble - 2 Added, 3 Changed, 1 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Added
- Gave anglerfish `[EXTRAVISION]` so that they're not basically helpless despite their size now
- Anglerfish tentacles and spiked rear fins, to be more accurate to their game anatomy!

#### Changed
- Made anglerfishes teeth much bigger/proportionally accurate
- Made anglerfish only spawn in "savage" oceans now
- Made anglerfish eggs more accurate to them being fish; no more hard eggshell, just jelly and yolk!

#### Fixed
- Fixed tissues for anglerfishes rod and lure; now the rod is made of skin, fat, muscle and bone, and the lure is a unique tissue
</details>

### Echoes of the Eye - 5 Added, 5 Changed, 1 Removed, 1 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Added
- Info in `README.md` about the owlk civ "board game" toy (was already in the mod, just not mentioned)
- Some more owlk civ sphere alignments; unlike hearthians and nomai, they already had some, but now they _also_ will pay extra for/worship the spheres of rivers and the moon, and less for goods relating to death, murder, rebirth, and suicide
- Rappigs. Huge, 4-eyed creatures resembling pigs with the ears and tails of rabbits
- Dragonfish. Large (bigger than a human!) fish capable of flight, and which can breathe air. They are named for their fins, which bear a striking resemblance to the wings of a dragonfly
- Chordochestrions; a one-stringed instrument played with a bow, and it has an old-fashioned music box built into it

#### Changed
- Edited owlk arm, hand, finger and leg sizes; all are a big bigger/longer
- Adjusted owlk colors; their nails and hooves now share the same color as their finger scales, and their feathers and skin now have more variety in shades of green, as well as greys
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

### Giant's Deep - 1 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Fixed
- Removed `MUSCULAR_ONLY` from jellyfishes electricic shock "unconsciousness" symptom
</details>

### Dark Bramble - 1 Fixed

<details>
  <summary>Spoiler warning</summary>

#### Fixed
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

### Hollow's Lantern
<details>
  <summary>Spoiler warning</summary>

- Star platinum metal and ore
</details>

### Giant's Deep
<details>
  <summary>Spoiler warning</summary>

- Giants Deep Jellyfish
</details>

### Dark Bramble
<details>
  <summary>Spoiler warning</summary>

- Bramble Anglerfish
</details>

### Echoes of the Eye
<details>
  <summary>Spoiler warning</summary>

- Owlk creature and civ
- "Echoes" boardgame, used by owlk civ
</details>

<!--Links-->
[Unreleased]: https://github.com/Crabman-DF-Mods/dwarven-wilds/compare/v1.0.0...HEAD
[v1.0.0]: https://github.com/Crabman-DF-Mods/dwarven-wilds/compare/v0.1.1...v1.0.0
[v0.1.1]: https://github.com/Crabman-DF-Mods/dwarven-wilds/compare/v0.1.0...v0.1.1
[v0.1.0]: https://github.com/Crabman-DF-Mods/dwarven-wilds/releases/tag/v0.1.0