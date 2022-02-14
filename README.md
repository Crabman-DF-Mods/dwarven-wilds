# Dwarven Wilds - v0.1.1 [47.05]

_NOT AN OFFICIAL OUTER WILDS PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOBIUS DIGITAL OR ANNAPURNA INTERACTIVE._

This mod for [Dwarf Fortress][Dwarf_Fortress] adds the unique creatures, civilizations, and materials seen and/or mentioned in [Outer Wilds][Source] and its DLC, Echoes of the Eye.

__Be warned__, Outer Wilds is a game whose fun comes from discovery and gaining knowledge through exploration of the world, and __over half of this mod's contents/modules would count as spoilers for either the main game or DLC__, and this would likely impact the enjoyability of the game.

__Therefore I highly recommend that you first play Outer Wilds (and/or its DLC, Echoes of the Eye) before using the spoilery modules of this mod.__ Strictly speaking you wouldn't need to play all the way to the end to find everything that is in this mod, but unfortunately I can't be specific about what "the safe points" are without that also being a spoiler.

__The raw files comments have even more spoilers (including story ones!) than you would get just playing with/using this mod__, so be warned about that before you go digging around this mod's code (even the spoiler-free module files have some spoilery comments).

This mod was created with the help of the [Dwarf Fortress RAW language server extension][LS], which is currently in beta, but I still recommend it for anyone wanting to make Dwarf Fortress mods, either for the first time or as a veteran.

If you want to check out my other mods, follow one of these links:
- DFFD downloads: https://dffd.bay12games.com/who.php?id=9116
- Github sources: https://github.com/Crabman-DF-Mods

## Installation

There are 4 folders here, each for a different portion of the mod:
- __Utility:__ contains materials, body parts and body plans shared by multiple other modules. Installing this module by itself will do nothing at all, and __the other modules depend on this one__.
- __Spoiler Free:__ contains the "hearthian" creatures/civ, and the "ghost matter" material (which aren't spoilers because you find out about them at the start of the game).
- __Nomai Spoilers:__ contains the Nomai creatures/civ. Their existence/appearance is not a spoiler since they are seen at the start of the game in the hearthian museum before you even get in your spaceship, but some aspects of their culture (and therefore civ) are spoilers.
- __Other Base Game Spoilers__ contains all the spoilery content from the base game, _except_ for the nomai creatures/civ.
- __Echoes of the Eye Spoilers:__ contains content from the Echoes of the Eye DLC, which is all 100% spoilers. I recommend finishing the DLC before you use this module.

Decide which of these modules you want (__note, you always need "Utility", because the other modules depend on it__), and copy-paste all the files in the corresponding folder into `/raw/objects/`. If you ever decide to change to a different, more spoilery version, just dump that folder's files in as well (you'll probably want to generate a new world when doing this though).

As for knowing when to enable a given module (if you want to avoid the spoilers):

The ending of the base game will be clear enough probably (it can only be done after solving "the big mystery", and the credits will run), so you'll know it's safe to enable "Nomai Spoilers" and "Other Base Game Spoilers" then. For Echoes of the Eye content, everything related to it will be in the lower right area of the rumor map and the "rumor boxes" are colored blue, so you should be able to tell you're finished with the DLC content when you have found several of the blue rumor boxes and none of them have that marker saying "there's more to discover here".

## Content

### Spoiler Free

__Hearthians:__ intrepid blue-skinned creatures driven by intense curiosity; they have a natural knack for the acquisition of knowledge and tend to be quite friendly.

Their culture puts a heavy emphasis on community and exploration.

And they know how to make marshmallows! Delicious, soft and sugary confections that can be cooked above a fire (well, not actually because DF doesn't support that yet it seems, but still). A traditional snack for hearthian travelers.

__Ghost Matter:__ a deadly, transparent substance that cannot be seen easily with the naked eye; it will inflict a painful death on anybody who wanders into a cloud of it unwittingly. Beware of encountering it while mining!

### Nomai Spoilers

<details>
  <summary>Spoiler warning</summary>
  
  __Nomai:__ 3 eyed, goatlike people who are natural scientists with great interest in understanding the world.
  
  Their culture harbors a deep respect for nature, and reinforces their natural interest in learning.
  
</details>

### Other Base Game Spoilers

<details>
  <summary>Spoiler warning</summary>

  __Star Platinum:__ strange ore that looks like rock embedded with glowing stars; in the dark it resembles the night sky. It can temporarily withstand the hottest flame in existence, dragonfire!

  __Giants Deep Jellyfish:__ gigantic orange jellyfish with electrified bodies and tentacles. They will assuredly make you sick if you try eating them, even if their electricity is removed.

  __Bramble Anglerfish:__ flying, blind fish that can survive without any oxygen, and which are big enough to swallow a small whale in principle (due to limitations in DF's engine though, they sadly can't do this, yet).
  
</details>

### Echoes of the Eye Spoilers

<details>
  <summary>Spoiler warning</summary>
  
  __Owlk:__ large, long-lived owl-like people with antlers and hooved feet, who dwell in wetland and forest cities, traveling primarily by river; they have a somewhat traditionalist nature, being slightly fearful, vengeful and reserved.
  
  Their culture emphasizes further the importance of tradition and the harmonious lives they so value.
  
  They invented a unique triangular board game which can be played by a varying number of players, where the aim is to "trap" a specific dark game piece using the other pieces, while avoiding been "seen" by the dark piece. However, the owlk are very secretive about the exact rules.

  They also play strange instrument which has only one string, and is played with a bow. There is a music box inside, with a visible, large, rotating metal cylinder that plucks on the pins of a metal comb. The instrument has an eerie, yet sweet, smooth, graceful, strained, resonant, and wavering timbre.

  __Rappigs:__ exotic bald, nocturnal creatures resembling _massive_ pigs with the ears and tail of a rabbit. And when I say massive, I mean quite massive, like bigger than grizzly bears.

  __Dragonfish:__ large nocturnal fish capable of flight, that can breathe air. They are named for their fins, which bear a striking resemblance to the wings of a dragonfly.
  
</details>

## Planned Content

All the planned objects/content listed in this section will unfortunately not be possible to implement faithfully until future updates for Dwarf Fortress come out to add the required features/mechanics.

### Spoiler Free

__Sap Wine:__ this wine is brewed from sap tapped from trees and considered a delicacy by hearthians, or at least, that's what the ones who do the brewing say... This can't be implemented until tree tapping or something like it is supported, though honestly I might not even need to implement it myself when the time comes, since dwarves would surely do something alchoholic with tree sap.

### Nomai Spoilers

Be warned that there are more spoilers here than just the nomaian culture (mostly regarding their technology), so it's definitely a lot more spoilery than the current "Nomai Spoilers" content.

<details>
  <summary>Spoiler warning</summary>

  __Nomaian Magic:__ when Myth & Magic comes, nomai will be given the ability to see special things with their third eye (not sure what exactly yet, but something normal beings can't), and to have magic (artifact based, not innate) that can do the following:
  
  - Use telekinesis in their technology (in reference to their self-repairing rock signs and weird marble doors).

  - Teleport/make portals (in reference to their black/white hole warp drives).

  - Manipulate gravity, making floors with a fixed gravity direction (hopefully enabling nice weird architecture), and special gravity crystals that can be used to change the gravity of surfaces.

  - Magical projection stones that can project/send messages to distant, set locations with the required "projection stone" infrastructure.

  - Other projection stones that allow one to remotely view/astrally project to the correctly set locations, so you can see it as if you were truly there. (even walk around in a certain range)

  - They will have a cultural interest in learning all the magic they possibly can (that is procedurally generated in that world). Their special eye will most likely help in this regard most of the time.

  __Nomaian Staves:__ an item created by the nomai, with a built in ability to create writing, and to levitate objects/control things telekinetically. Obviously will need nomaian magic to be implemented. It will also be able to play music, and this feature will have to wait until Toady's plans to merge items into one object type are implemented.
  
</details>

### Other Base Game Spoilers

<details>
  <summary>Spoiler warning</summary>
  
  __Dark Brambles:__ these plants will require the ability for "evil" plants to spread and overtake areas entirely, as well as for the seeds to have space-warping abilities like portals and "pocket dimensions" and being bigger on the inside and such. In other words, at least the Myth & Magic update (I would settle for it at least taking over entire regions and threatening the integrity of the land or world, even if the space-warping doesn't happen).
  
</details>

### Echoes of the Eye Spoilers

<details>
  <summary>Spoiler warning</summary>

  __Owlk Magic:__ with the Myth & Magic update, owlks will be given access to a lot of magic:
  
  - Magic based on green flames and dreams/sleep, which will enable them to enter a shared "dream world" and keep their souls in green flames. They can reside in the dream world even after their physical body dies, so long as their flame is still lit.
  
  - Permanently "cloak" objects/areas, which makes them invisible/dark, silent (trapping all sounds inside the cloak), and can be used to hide other magical signals from escaping the cloak. To be clear, it's possible to uncloak the places, but by "permanent" I just mean it doesn't wear off or require active sustaining. This would definitely _not_ be something nomai can see through with their third eye. 
  
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