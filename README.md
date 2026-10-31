# Shardfall

A small mobile-first bullet-hell RPG demo, inspired by the co-op "realm" shooters
(Realm of the Mad God and its private servers). The sprites (all 8x8 pixels),
classes, items, enemies and names are original.

Open `index.html` in any browser. It is a single file with no build step, so it
also works from GitHub Pages on a phone.

## Game loop

1. **Character select.** Your account holds up to 4 characters. Create one
   (Pyromancer, Warden or Hunter), play one, or delete one. Total account fame
   and a graveyard of fallen characters are shown here.
2. **Nexus.** A safe hub where you can't fight or take damage, and HP/MP refill
   fast. Walk into the **Realm Portal** at the north end.
3. **Realm.** A freshly generated island each time. It gets harder toward the
   middle: Driftsand Shore, Windmeadow, Thornwood, then the Ashen Core, where the
   **Cinder Colossus** boss lives. Press **NEXUS** (or walk into the portal by the
   shore camp) to get back to safety at any time.
4. **Permadeath.** When a character dies it is deleted. Its fame goes to your
   account and it's listed in the graveyard.

Characters save automatically: on entering the Nexus, on level-up, on every
inventory change, every 10 seconds, and when the page is hidden.

## Inventory and equipment

- 4 equipment slots (**Weapon, Ability, Armor, Ring**) and an 8-slot **backpack**.
- Enemies drop **loot bags**. The bag colour hints at what's inside: brown is
  low tier, purple mid, gold high, blue holds an elixir, white holds a unique.
- Standing on a bag shows a quick-loot strip. Tap an item to take it, or to
  equip it straight away when that slot is empty. The full **BAG** panel lets
  you inspect, compare, equip, unequip, take and drop items. Dropped items make
  a bag on the ground.
- Health and mana potions are picked up automatically (up to 9 of each).

| Slot | Pyromancer | Warden | Hunter | Tiers |
| --- | --- | --- | --- | --- |
| Weapon | Staff (twin bolts) | Blade (3-shot arc) | Bow (piercing) | T0–T6 |
| Ability | Orb: Flare Nova | Crest: Bulwark | Quiver: Volley | T0–T5 |
| Armor | Robe (+MP, +WIS) | Heavy plate (+HP) | Leather (+DEX, +SPD) | T0–T6 |
| Ring | any class | any class | any class | T0–T4 |

The boss can also drop **unique (UT)** items: Cinderheart Staff, Colossus
Cleaver, Ashfall Longbow, and Heart of the Colossus.

## Stats and elixirs

Eight stats: **Life, Mana, Attack, Defense, Speed, Dexterity, Vitality, Wisdom.**
Each class has its own starting values and maximums (shown when you create a
character). Leveling to 20 raises stats part of the way. **Elixirs** (one per
stat) drop in Thornwood, the Ashen Core and from the boss. Drink one from your
backpack to raise that base stat by 1 (Life/Mana by 5) up to the class maximum.
The Stats tab shows each stat against its cap, gear bonuses in green, and how
many stats are maxed.

## Controls

| Action | Phone | Keyboard / mouse |
| --- | --- | --- |
| Move | Drag on the left half | WASD / arrows |
| Aim and fire | Drag on the right half | Hold mouse button |
| Auto-fire at nearest foe | AUTO (on by default) | T |
| Ability | Big orange button | Space |
| Health / mana potion | HP / MP | Q / E |
| Return to Nexus | NEXUS | R |
| Inventory and stats | BAG | I or Tab |
| Back to character select | CHARS | |
