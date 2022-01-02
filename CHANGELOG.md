# Changelog
__WARNING, SPOILERS FOR OUTER WILDS AND ECHOES OF THE EYE FROM ALL VERSIONS OF THE MOD WILL BE UNMARKED AND UNHIDDEN IN THIS FILE__

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

### Added
- `CHANGELOG.md` file

### Changed

### Removed

### Fixed

## [v0.1.1] - 2021-12-13
### Added
- Links to my other mods in `README.md`

### Changed
- Made `LICENSE` file more readable

### Fixed
- Removed `MUSCULAR_ONLY` from jellyfishes electricic shock "unconsciousness" symptom
- Fixed anglerfish `CREATURE_TILE`
- Removed empty argument from owlks horn length `BP_APPEARANCE_MODIFIER`

## [v0.1.0] - 2021-12-10
The initial public release. It contains the following:
- Full Mod, Only Base Game Spoilers, and Spoiler Free versions of the mod.
- Hearthian creature and civ
- Nomai creature and civ
- Owlk creature and civ
- Giants Deep Jellyfish
- Bramble Anglerfish
- Ghost matter
- Star platinum metal and ore

<!--Links-->
[Unreleased]: https://github.com/Crabman-DF-Mods/dwarven-wilds/compare/v0.1.1...HEAD
[v0.1.1]: https://github.com/Crabman-DF-Mods/dwarven-wilds/compare/v0.1.0...v0.1.1
[v0.1.0]: https://github.com/Crabman-DF-Mods/dwarven-wilds/releases/tag/v0.1.0