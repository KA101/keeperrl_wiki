---
title: Map Editor Ideas
permalink: Map_Editor_Ideas/
layout: wiki
---

Hi,

There is a possibility that Alpha 26 will include a map editor. Please
provide your ideas here.

-   Please keep the standard rules about not submitting copyrighted
    content to the wiki. This includes any material of your own for
    which you want the copyright. (We are submitting our ideas into the
    public domain for Michal to use under an open source license)

Thanks!

Main menu screen
----------------

-   Play
-   Map Editor &lt;---(new, Click here to goto Tribe Editor)
-   Settings
-   Hiscores
-   Credits
-   Quit

Tribe/villain editor
--------------------

-   Purpose: Creating villains and allies for the campaign maps.
    Choosing villain triggers and attack strategy.

<!-- -->

-   Tribe name

<!-- -->

-   Tribe's loyalty - Dropdown based on TribeID:

  
\[Human/Elf/Darkelf/Dwarf/Gnome/Bandit/Shelob/Lizard/Greenskin/RetiredKeeper/Ant/Monster/Pest/Wildlife/Hostile/Peaceful\]

-   Tribe type: Drop down list - Only set to “allies” if the Tribe id is
    a valid ally.

  
\[Main villain/Minor villain/allies\]

-   Tribe image for displaying your new villain on campaign maps
    \[Select view ID from a list\]

<!-- -->

-   Attack Triggers: Dropdown.

  
\[Gold/Proximity/Throne/Stealing/Trespassing\]

-   Initial Biome (How your new map starts off before you edit it):
    Dropdown

  
\[Grassland, Forest, Mountain, 100% Sand, 100% grass, 100% water, 100%
lava, 100% rock...or procedurally generated villains that already exist
such as a “red dragon” map\]

-   Example: Create a new tribe called “River Pirates”, with a loyalty
    to bandits. Make them a minor villain, select the view id for
    bandits. Give them a trigger of gold and put them in a forest biome.

<!-- -->

-   Click the “Generate Terrain” Button to generate a forest biome map
    and move on to the Terrain Editor. (Note: Your new tribe has no
    creatures, tiles or furniture in it because it doesn't know what to
    put where yet).

Full Terrain editor
-------------------

-   Purpose - Edit every aspect of the map provided it still produces a
    valid save file!

<!-- -->

-   Select a tribe on the map - Drop down

  
\[River Pirates/Elves/Humans/Unclaimed\] &lt;---Example

-   Place existing furniture (to be owned by the selected tribe)

<!-- -->

-   Remove existing furniture on the map you don't want. Reuse existing
    UI.

<!-- -->

-   Claim tile - Claim tiles and furniture for your selected tribe.
    (Designating villain territory)

<!-- -->

-   Add creature to current tribe (Creature id drop down). Summon a
    creature belonging to the selected tribe ID. (Making creatures from
    the creature factory and assigning them to their villain tribe)

  
\[Keeper/Female Keeper/Adventurer/Female
Adventurer/Unicorn/Bandit/Ghost/Spirit/Lost
Soul/Succubus/Doppleganger/Witch/Witchman/Cyclops/Demon dweller/Demon
Lord/Minotaur/Soft Monster/Hydra/Shelob/Green dragon/Red
dragon/Knight/Jester/The
Duke/Archer/Priest/Warrior/Shaman/Peseant/Child/Child (Spider
food)/Halloween Kid/Clay Golem/Iron Golem/Lava Golem/Adamantium
Golem/Automaton/Zombie/Skeleton/Vampire/Vampire Lord/Mummy/Orc/Orc
Shaman/Harpy/Kobold/Gnome/Gnome
Chief/Goblin/Imp/Ogre/Chicken/Dwarf/Dwarf Female/Dwarf
Baron/Lizardman/Lizardman lord/Elf/Elven Archer/Elf Child/Elf Lord/Dark
elf/Dark elf warrior/Dark elf child/Dark elf
lord/Driad/Horse/Cow/Donkey/Pig/Goat/Jackal/Deer/Boar/Fox/Cave
Bear/Rat/Spider/Fly/Ant Worker/Soldier Ant/Ant
Queen/Snake/Raven/Vulture/Wolf/WereWolf/Dog/Fire
Sphere/Elementalist/Fire elemental/Air Elemental/Earth elemental/Water
Elemental/Ent/Angel/Kraken/Bat/Death\]

-   Option to retire the map (upload it).

<!-- -->

-   Example: Increase the size of the rivers. Make a secret cave along
    the side of a river that you must swim to or fly into. Select the
    tribe named “river pirates” and summon some bandits inside the cave.
    Claim the cave tiles for your new tribe. (tribe ID = bandit)

<!-- -->

-   Click on the creatures (example: the bandits) to edit them.

Creature editor
---------------

-   Purpose - Edit creatures that are on the map (either from the
    initial map generation or from summoning them)

<!-- -->

-   Rename

<!-- -->

-   Banish

<!-- -->

-   Control creature

<!-- -->

-   Press 'u' at any time to return to the terrain editor.

<!-- -->

-   Move it about

<!-- -->

-   Summon equipment for creature (F11?)

<!-- -->

-   Add/Remove permanent effect (Drop down list) (F10?)

<!-- -->

-   Add/Remove skill (Drop down list)

<!-- -->

-   Increase/Decrease stats (Click on stat)

<!-- -->

-   Add/Remove spell (Click on spell)

<!-- -->

-   Add/Remove training abilities (Click on training)

<!-- -->

-   Edit AI (Leader/Fighter/Civilian/Prisoner)

<!-- -->

-   Edit gender (m/f/it)

<!-- -->

-   Edit body size (huge/large/small/tiny)

<!-- -->

-   Restore and injure body parts

<!-- -->

-   Example. Create some bandits in the secret cave. Change their name
    to pirates and make them tougher. Give the pirate leader a bit
    higher attack. Give the pirates the swimming skill so they can leave
    the cave by crossing the river.

<!-- -->

-   Edit items in a creature's inventory (Click on them, to go to the
    item editor)

Item editor
-----------

-   Press 'u' at any time to return to the creature editor and again to
    return to the terrain editor.

<!-- -->

-   Change name of item

<!-- -->

-   Increase/Decrease item's attack (weapon)

<!-- -->

-   Increase/Decrease item's defense (armour)

<!-- -->

-   Edit lasting effect (ring, potion)

<!-- -->

-   Edit effect (Mushroom, scroll)

<!-- -->

-   Destroy item

<!-- -->

-   Example - take the pirate captain's sword. Name it a great pirate
    sword and increase the damage a bit.

Additional notes
----------------

-   It may help to have a dungeon master avatar when editing maps. He
    could be a place-holder who looks like a keeper but disappears when
    you retire the map.

<!-- -->

-   It could help to freeze the game turns so things stay where you put
    them.

<!-- -->

-   Instead of dropdowns the enums could each have an icon you can
    select them with. views for different: Tribe Ids, creature Ids, Item
    Ids, Effect Ids, Skill Ids, Spell Ids etc.

<!-- -->

-   Another way of adding and removing spells, skills and permanent
    effects might be to show them all and toggle them on/off

<!-- -->

-   Example: Rename a pirate to “blind old pirate”. Toggle blindness
    effect on the blind pirate - putting “blindness” in a red font when
    you click on it to show blindness is switched on. Make the blind
    pirate slower and give him an injured leg by clicking on “slow” and
    his intrinsic leg attack turning them red.
