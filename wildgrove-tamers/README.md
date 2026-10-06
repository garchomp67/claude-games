# Wildgrove Tamers

A creature-catching adventure game that runs entirely in the browser. Pick a starter, explore a huge world, battle and catch creatures, beat 9 gyms and the Boss, and hunt down legendaries.

## Play

Open `index.html` in any modern browser. No install or build step.

- Move: arrow keys, `WASD`, or the on-screen pad
- Big map: tap the minimap or press `M`
- Progress saves automatically in the browser (localStorage, per website address)

## What's in it

- 647 creatures across 10 types (Plain, Ember, Tide, Bloom, Spark, Stone, Gale, Frost, Shade, Lava), including 100+ five-stage families and 8 legendaries
- A 360×285-tile world in 9 areas, plus the Underground Caves, Lava Island and Frostspire Mountain
- 9 gyms and a Boss, 90+ trainers, shops, coins, items, smashable gems, teleport holes and swimming
- Team & Grove Box management, a paged Grove Log, and an in-battle type chart

## Tech

One self-contained HTML file: vanilla JavaScript and Canvas 2D, no framework and no image files. Every creature, tile and effect is drawn in code, and the maps are generated from fixed seeds so the world is the same every time. The only external resource is two Google Fonts (with system-font fallbacks).
