# Dwarven Wilds - v0.1.1 [47.05]

_NOT AN OFFICIAL OUTER WILDS PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOBIUS DIGITAL OR ANNAPURNA INTERACTIVE._

This mod for [Dwarf Fortress][Dwarf_Fortress] adds the unique creatures, civilizations, and materials seen and/or mentioned in [Outer Wilds][Source] and its DLC, Echoes of the Eye.

__Be warned__, Outer Wilds is a game whose fun comes from discovery and gaining knowledge through exploration of the world, and __over half of this mod's contents would count as spoilers for both the main game and DLC__, and this would likely impact the enjoyability of the game.

__Therefore I highly recommend that you first play Outer Wilds (and its DLC, Echoes of the Eye) before using the full version of this mod.__ Strictly speaking you wouldn't need to play all the way to the end to find everything that is in this mod, but unfortunately I can't be specific about what "the safe points" are without that also being a spoiler.

__The raw files comments have even more spoilers (including story ones!) than you would get just playing with the mod__, so be warned about that before you go digging around this mod's code.

Technically one of the base game creatures/civs I have listed in the spoiler warning below is not a proper spoiler since you find out about them in the museum before you can even get in your spaceship, but their culture (and by extension their personalities) _is_ a spoiler, which is why they are absent from the spoiler free version of this mod.

This mod was created with the help of the [Dwarf Fortress RAW language server extension][LS], which is currently in beta, but I still recommend it for anyone wanting to make Dwarf Fortress mods, either for the first time or as a veteran.

If you want to check out my other mods, follow one of these links:
- DFFD downloads: https://dffd.bay12games.com/who.php?id=9116
- Github sources: https://github.com/Crabman-DF-Mods

## Installation

There are 3 folders here, each for a different version of the mod:

- __Full Mod:__ contains all this mods content, including all spoilery things from both the base game and DLC.
- __Only Base Game Spoilers:__ contains all the same content as Full Mod, _except_ the content from the Echoes of the Eye DLC.
- __Spoiler Free:__ contains none of the spoilery content; that is, it only has the "hearthian" creatures/civ, and the "ghost matter" material (which aren't spoilers because you find out about them at the start of the game).

Decide which of those versions you want, and copy-paste all the files in the corresponding folder into `/raw/objects/`. If you ever decide to change to a different, more spoilery version, you must make sure to overwrite any files that are shared between the versions (you should get a prompt asking you about overwriting files when you copy them in; say yes to all overwrites).

## Content

### Base Game

__Hearthians:__ intrepid blue-skinned creatures driven by intense curiosity; they have a natural knack for the acquisition of knowledge and tend to be quite friendly.

Their culture puts a heavy emphasis on community and exploration.

__Ghost Matter:__ a deadly transparent substance that cannot be seen easily with the naked eye; it will inflict a painful death on anybody who wanders into a cloud of it unwittingly. Beware of encountering it while mining!

<details>
  <summary>Spoiler warning</summary>
  
  __Nomai:__ 3 eyed, goatlike people who are natural scientists with great interest in understanding the world.
  
  Their culture harbors a deep respect for nature, and reinforces their natural interest in learning.

  __Star Platinum:__ strange ore that looks like rock embedded with glowing stars; in the dark it resembles the night sky. It can temporarily withstand the hottest flame in existence, dragonfire!

  __Giants Deep Jellyfish:__ gigantic orange jellyfish with electrified bodies and tentacles. They will assuredly make you sick if you try eating them, even if their electricity is removed.

  __Bramble Anglerfish:__ flying, blind fish that can survive without any oxygen, and which are big enough to swallow a small whale in principle (due to limitations in DF's engine though, they sadly can't do this, yet).
  
</details>

### Echoes of the Eye

<details>
  <summary>Spoiler warning</summary>
  
  __Owlk:__ large owl-like people with antlers and hooves, who dwell in wetland and forest cities, traveling primarily by river; they have a somewhat traditionalist nature, being slightly fearful, vengeful and reserved.
  
  Their culture emphasizes further the importance of tradition and the harmonious lives they so value. They invented a unique triangular board game, where the aim is "trapping" a specific game piece using 3 other pieces.
  
</details>

## Planned Content

### Base Game

__Sap Wine:__ this wine is brewed from sap tapped from trees, considered a delicacy by hearthians, or at least, by the ones who do the brewing...

__Marshmallows:__ delicious, soft and sugary confections that can be cooked above a fire. They are a traditional snack for hearthian travelers.

Most new objects/content listed below this point will unfortunately not be possible to implement faithfully until future updates for Dwarf Fortress come out to add the required features/mechanics:

<details>
  <summary>Spoiler warning</summary>
  
  __Dark Brambles:__ these plants will require the ability for "evil" plants to spread and overtake areas entirely, as well as for the seeds to have space-warping abilities like portals and "pocket dimensions" and being bigger on the inside and such. In other words, at least the Myth & Magic update (I would settle for it at least take over entire regions and threaten the integrity of the land or world, even if the space-warping doesn't happen).

  __Nomaian Magic:__ when Myth & Magic comes, nomai will be given the ability to see special things with their third eye (not sure what exactly yet, but something normal beings can't), and to have magic (artifact based, not innate) that can do the following:
  
  - Use telekinesis in their technology (in reference to their self-repairing rock signs and weird marble doors).

  - Teleport/make portals (in reference to their black/white hole warp drives).

  - Manipulate gravity, making floors with a fixed gravity direction (hopefully enabling nice weird architecture), and special gravity crystals that can be used to change the gravity of surfaces.

  - Magical projection stones that can project/send messages to distant, set locations with the required "projection stone" infrastructure.

  - Other projection stones that allow one to remotely view/astrally project to the correctly set locations, so you can see it as if you were truly there. (even walk around in a certain range)

  - They will have a cultural interest in learning all the magic they possibly can (that is procedurally generated in that world). Their special eye will most likely help in this regard most of the time.

  __Nomaian Staves:__ an item created by the nomai, with a built in ability to create writing, and to levitate objects/control things telekinetically. Obviously will need nomaian magic to be implemented. It will also be able to play music, and this feature will have to wait until Toady's plans to merge items into one object type are implemented.
  
</details>

### Echoes of the Eye

<details>
  <summary>Spoiler warning</summary>
  
  __Owlk Instruments:__ the owlks have a weird cultural instrument I want to add for their entity/civ as a hardcoded instrument (alongside generated ones). This won't require future DF updates unlike the other planned content; however, I have no idea how it works or what its parts are because I don't know anything about instruments, so it may be some time before I figure it out and implement it.

  __Owlk Magic:__ with the Myth & Magic update, owlks will be given access to a lot of magic:
  
  - Magic based on green flames and dreams/sleep, which will enable them to enter a shared "dream world" and keep their souls in green flames. They can reside in the dream world even after their physical body dies, so long as their flame is still lit.
  
  - Permanently "cloak" objects/areas, which makes them invisible/dark, silent (trapping all sounds inside the cloak), and can be used to hide other magical signals from escaping the cloak. To be clear, it's possible to uncloak the places, but by "permanent" I just mean it doesn't wear off or require active sustaining.
  
  - Make objects/mechanisms that are triggered or controlled by light. Ideally this wouldn't be actual magic, but such a construction will probably have to be implemented in DF using magic.

  - "Lanterns", which they will carry around as a matter of culture to so they can use mechanisms controlled by light. Also will tie in to the dream/flame magic, and have a variant that can narrow down/project light more narrowly.

  - Vision torches, allowing them to share memories or thoughts with one another, even in cases of a language or species barrier (not relevant now except for kobolds, but Toady likes languages and has said he wants to eventually make the game auto-generate them). They can plant the ideas inside the torch as well, so they won't need to actively be holding the torch to share the visions.

  - Placing memories and thoughts/ideas from vision torches into other objects (reels), which can be played/shown to a larger audience.
  
</details>

## License

The license the code in this project is licensed under can be found in the `LICENSE` file, but put simply:

You can do whatever you like with this mod yourself privately, but you may not reupload this mod (with or without modifications) anywhere without my permission. Forking the repo on Github is okay, as long as you don't publicly advertise or distribute your forked version on the likes of the Bay12 forums, DFFD, or Steam/Steam Workshop.

If you want to use this in a modpack or mod compilation, please ask first.

<!--Links-->
[LS]: https://gitlab.com/df-modding-tools/df-raw-language-server
[Dwarf_Fortress]: https://bay12games.com/dwarves
[Source]: https://store.steampowered.com/app/753640/Outer_Wilds/