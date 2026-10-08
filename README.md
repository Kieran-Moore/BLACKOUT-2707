# BLACKOUT: 2707

A private, Dwarf Fortress-inspired retro-futuristic colony simulation designed for an M1 iPad Pro.

## Embark 001
- 12 settlers from Haven
- Overgrown wasteland
- Relaxed difficulty
- Year 2707

## Run
Open `index.html` in a browser. No build tools, dependencies or network are required. For reliable iPad access, serve the folder from a static web host (for example GitHub Pages if visibility and hosting preferences permit). Browser storage for local `file://` pages can vary.

## Version 0.2
- Seeded procedural map with trees, rubble, rocks, water and stockpile
- Twelve individual autonomous settlers with simple needs
- Tile designation for chopping, salvage, stockpiles and walls
- Pathfinding, physical timber/scrap/food items, hauling and construction deliveries
- Time controls, event log and local save/load

## Known limitations
- Single surface Z-level only; no mining or multi-level construction yet
- Prototype scheduler and needs, no combat, farming or weather simulation
- Item carrying and material delivery are simplified; no detailed workshop or inventory system
- Saves are browser-local and may not persist in every iPad file-viewer context
- No iPad Safari test has yet been performed

## Next milestone
Add robust item reservation, storage capacity, workshop production and multiple Z-levels. Keep simulation logic separate from rendering when refactoring into modules.
