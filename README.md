# Shardfall

A small mobile-first bullet-hell RPG demo, inspired by the co-op "realm" shooters
(Realm of the Mad God and its private servers). Everything here is original:
sprites, world, classes, enemies and names.

Open `index.html` in any browser. It is a single file with no build step, so it
also works when served from GitHub Pages and opened on a phone.

## How to play

- **Goal:** start on the south shore and fight inward. The island gets harder
  toward the middle: Driftsand Shore, Windmeadow, Thornwood, then the Ashen Core,
  where the Cinder Colossus boss lives. It comes back 75 s after it dies.
- **Permadeath:** when you die, the run ends and your Glory score is saved
  (best score is kept in the browser).
- **Loot:** enemies drop bags. Walk over one to pick it up. Better weapons and
  armor are equipped automatically. Potions refill your stock, and essences
  (from Thornwood and deeper) give +1 to a stat for good.
- **Leveling:** up to level 20. Each level raises your stats and refills HP and MP.
- **Camp:** the campfire on the shore heals you fast. HOME teleports you back
  there (20 s cooldown).

### Controls

| Action | Phone | Keyboard / mouse |
| --- | --- | --- |
| Move | Drag on the left half | WASD / arrows |
| Aim and fire | Drag on the right half | Hold mouse button |
| Auto-fire at nearest foe | AUTO button (on by default) | T |
| Class skill | Big orange button | Space |
| Health potion | POT | Q |
| Recall to camp | HOME | R |

### Classes

| Class | Weapon | Skill |
| --- | --- | --- |
| Pyromancer | Staff: two parallel fire bolts | Flare Nova: ring of 20 piercing bolts |
| Warden | Blade: short, wide 3-shot arc, high defense | Bulwark: heal, 4 s damage reduction, erases nearby shots |
| Hunter | Bow: long-range piercing arrow | Volley: fan of 7 heavy piercing arrows |
