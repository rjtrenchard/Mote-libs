9/12/21

* Updated Mote-libs to account for new wardrobes, spells, and some spell class functionality.
* **spell_maps** has added GainStat, BoostStat, Enspell, MndEnfeeble, IntEnfeeble classes
* **spell_burstable** is a string list of all the spells that can get benefits from magic bursting.
* **has_equippable(name)** checks all equippable inventory for an item *name*.
* **gear.ElementalObi** will check for elemental obis as well as Hachirin-no-obi, defaulting to Hachirin-no-obi if it exists
* added **gear.DrainWaist**, which functions exactly like elemental obis but will default to **gear.default.drain_waist** instead.

