# Dwarven Wilds - v1.0.0 [47.05]

_NOT AN OFFICIAL OUTER WILDS PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOBIUS DIGITAL OR ANNAPURNA INTERACTIVE._

This mod for [Dwarf Fortress][Dwarf_Fortress] adds the unique creatures, civilizations, and materials seen and/or mentioned in [Outer Wilds][Source] and its DLC, Echoes of the Eye.

__Be warned__, Outer Wilds is a game whose fun comes from discovery and gaining knowledge through exploration of the world, and __over half of this mod's contents/modules would count as spoilers for either the main game or DLC__, and this would likely impact the enjoyability of the game.

__Therefore I highly recommend that you first play Outer Wilds (and/or its DLC, Echoes of the Eye) before using the spoilery modules of this mod.__ You don't need to play all the way to the end of the base game to find everything that is in this mod, and there are spoilerless instructions a couple of heading sections down that reveal what the "safe points" are for each module.

__The raw files comments have even more spoilers (including story ones!) than you would get just playing with/using this mod__, so be warned about that before you go digging around this mod's code (even the spoiler-free module files have some spoilery comments!). You should finish both the base game and DLC (like, see the actual ending) before reading the code in this mod.

This mod was created with the help of the [Dwarf Fortress RAW language server extension][LS], which is currently in beta, but I still recommend it for anyone wanting to make Dwarf Fortress mods, either for the first time or as a veteran.

If you want to check out my other mods, follow one of these links:
- DFFD downloads: https://dffd.bay12games.com/who.php?id=5705
- Github sources: https://github.com/Crabman-DF-Mods

## Installation

There are 7 folders here, each for a different portion of the mod:
- __Utility:__ contains materials, body parts and body plans shared by multiple other modules. Installing this module by itself will do nothing at all, and __the other modules depend on this one__.
- __Spoiler Free:__ contains the "hearthian" creatures/civ, and the "ghost matter" material (which aren't spoilers because you find out about them at the start of the game).
- __Nomai:__ contains the Nomai creatures/civ. Their existence/appearance is not a spoiler since they are seen at the start of the game in the hearthian museum before you even get in your spaceship, but some aspects of their culture (and therefore civ) are sort of spoilers.
- __Hollow's Lantern:__ contains content found on "Hollow's Lantern", the moon of the planet "Brittle Hollow".
- __Giant's Deep:__ contains content from the planet "Giant's Deep".
- __Dark Bramble:__ contains content from the planet "Dark Bramble".
- __Echoes of the Eye:__ contains content from the Echoes of the Eye DLC.

Decide which of these modules you want (__note, you always need "Utility", because the other modules depend on it__), and copy-paste all the files in the corresponding folder into `/raw/objects/`. If you ever decide to change to a different, more spoilery version, just dump that folder's files in as well (you'll probably want to generate a new world when doing this though).

## When to Install Each Module

If you want to know which modules you can install without spoilers:

- __Utility:__ you must always install this one to use the other modules. It has no spoilers (unless you read its code) because it doesn't do anything by itself, it just supplements the other modules.
- __Spoiler Free:__ as this module has no spoilers (it's all stuff you find right at the start of the game), you can enable this immediately.
- __Nomai:__ the spoilers in this module all pertain to the culture of the nomai (since their appearance/existence itself is not a spoiler), discovered through the writings they left behind. Enable this when you have read a lot of nomaian writings and feel like you understand their culture and what their interests are.
- __Hollow's Lantern:__ explore Hollow's Lantern (the moon floating around Brittle Hollow), you'll find information there about something you likely already saw on Timber Hearth (the starting planet), and this information is a spoiler.
- __Giant's Deep:__ this one is really simple, just visit Giant's Deep, and go anywhere underwater, then look down. You'll see all this module has to offer below you.
- __Dark Bramble:__ you should thoughrougly explore the Dark Bramble and Ember Twin planets before enabling this module. A good long comb through both should reveal everything (and all information about) the things you'll find in this module.
- __Echoes of the Eye:__ I recommend completing the DLC before enabling this module. Everything related to the DLC will be in the bottom-right area of the rumor map/shiplog, with blue colored "rumor boxes", but unfortunately there is no way to be specific about how you'll know you've completed it without it being some kind of spoiler. To say it vaguely, you will have found _at least_ 12 DLC shiplog/rumor boxes, and you will have solved some sort of thing you've been working towards in the DLC, and it won't involve the game credits rolling (only the base game ending and joke endings have credits).

## Content

### Spoiler Free

__Hearthians:__ intrepid blue-skinned creatures driven by intense curiosity; they have a natural knack for the acquisition of knowledge and tend to be quite friendly.

Their culture puts a heavy emphasis on community and exploration.

And they know how to make marshmallows! Delicious, soft and sugary confections that can be cooked above a fire (well, not actually because DF doesn't support that yet it seems, but still). A traditional snack for hearthian travelers.

__Ghost Matter:__ a deadly, transparent substance that cannot be seen easily with the naked eye; it will inflict a painful death on anybody who wanders into a cloud of it unwittingly. Beware of encountering it while mining!

### Nomai

<details>
  <summary>Spoiler warning</summary>

__Nomai:__ 3 eyed, goatlike people who are natural scientists with great interest in understanding the world.

Their culture harbors a deep respect for nature, and reinforces their natural interest in learning.
</details>

### Hollow's Lantern

<details>
  <summary>Spoiler warning</summary>

__Star Platinum:__ strange ore that looks like rock embedded with glowing stars; in the dark it resembles the night sky. It can temporarily withstand the hottest flame in existence, dragonfire!
</details>

### Giant's Deep

<details>
  <summary>Spoiler warning</summary>

__Giants Deep Jellyfish:__ gigantic orange jellyfish with electrified bodies and tentacles. They will assuredly make you sick if you try eating them, even if their electricity is removed.
</details>

### Dark Bramble

<details>
  <summary>Spoiler warning</summary>

__Bramble Anglerfish:__ flying, blind fish that can survive without any oxygen, and which are big enough to swallow a small whale in principle (due to limitations in DF's engine though, they sadly can't do this, yet).
</details>

### Echoes of the Eye

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

### Nomai

Be warned that there are more spoilers here than just the nomaian culture (mostly regarding their technology), so it's definitely a lot more spoilery than the current "Nomai" module content.

<details>
  <summary>Spoiler warning</summary>

__Nomaian Magic:__ when Myth & Magic comes, nomai will be given the ability to see special things with their third eye (not sure what exactly yet, but something normal beings can't), and to have magic (artifact based, not innate) that can do the following:

- Use telekinesis in their technology (in reference to their self-repairing rock signs and weird marble doors).

- Teleport/make portals (in reference to their black/white hole warp drives).

- Manipulate gravity, making floors with a fixed gravity direction (hopefully enabling nice weird architecture), and special gravity crystals that can be used to change the gravity of surfaces.

- Magical projection stones that can project/send messages to distant, set locations with the required "projection stone" infrastructure.

- Other projection stones that allow one to remotely view/astrally project to the correctly set locations, so you can see it as if you were truly there. (even walk around in a certain range)

- Memory statues/masks; basically, a way to transmit/store memories of a specific individual inside statues (and/or masks attached to said statues).

- They will have a cultural interest in learning all the magic they possibly can (that is procedurally generated in that world). Their special eye will most likely help in this regard most of the time.

__Nomaian Staves:__ an item created by the nomai, with a built in ability to create writing, and to levitate objects/control things telekinetically. Obviously will need nomaian magic to be implemented. It will also be able to play music, and this feature will have to wait until Toady's plans to merge items into one object type are implemented.
</details>

### Dark Bramble

<details>
  <summary>Spoiler warning</summary>

__Dark Brambles:__ these plants will require the ability for "evil" plants to spread and overtake areas entirely (maybe even whole dimensions/planes!), as well as for the seeds and main cores to have space-warping abilities like portals and "pocket dimensions" and being bigger on the inside and such. In other words, at least the Myth & Magic update (I would settle for it at least taking over entire regions and threatening the integrity of the land or world, even if the space-warping doesn't happen).
</details>

### Echoes of the Eye

<details>
  <summary>Spoiler warning</summary>

__Owlk Magic:__ with the Myth & Magic update, owlks will be given access to a lot of magic:

- Magic based on green flames and dreams/sleep, which will enable them to enter a shared "dream world" and keep their souls in green flames. They can reside in the dream world even after their physical body dies, so long as their flame is still lit.

- Permanently "cloak" objects/areas, which makes them invisible/dark, silent (trapping all sounds inside the cloak), and can be used to hide other magical signals from escaping the cloak. To be clear, it's possible to uncloak the places, but by "permanent" I just mean it doesn't wear off or require active sustaining. They will tend to often hide their sites using this. This would definitely _not_ be something nomai can see through with their third eye. 

- Produce illusions. Basically in reference to how the inside of the Stranger doesn't actually have a window, it has a "screen".

- Make objects/mechanisms that are triggered or controlled by light. Ideally this wouldn't be actual magic, but such a construction will probably have to be implemented in DF using magic.

- Make objects/mechanisms that are triggered or controlled by specific lights/candles being turned on, and these may have effects between the real world and their dream world (so a candle in their dream world may be able to control real mechanisms).

- "Lanterns/artifacts", which they will carry around as a matter of culture to so they can use mechanisms controlled by light. Also will tie in to the dream/flame magic, and have a variant that can narrow down/project light more narrowly.

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