# WULF - Web-based Ultima-Like Framework

WULF is a project that intends to create a framework based on open web technology that would allow easy creation of Ultima-like browser games.

## Repos

* Server code: https://github.com/rocket-boots/WULF-server
* Client code: https://github.com/rocket-boots/WULF-client

## Philosophy

* Open, interactive, simulated world
  - Go anywhere
  - Time always passes
* Persistant, living characters
  - PCs become NPCs when their player is offline
  - NPC schedules
  - Bot-friendly (BPC)
  - Aging and mortality
* Everything happens in the fiction/simulation
  - Nothing should be indestructible or immortal, except by in-game mechanics
  - World-building is done by entities (gods, wizards)
* Framework needs to be easy to enhance
  - Modular components
  - Keep an eye towards future additions; don't prevent modification
  - JavaScript is a language that many developers know and that can be learned online
  - Open source
* Online-capable
  - Server-Client architecture
* Top-down 2D is sufficient
  - Simple graphics

## What Works Now

- Run client with a separate server (e.g. Fenix) at an address like `http://localhost/WULF-client/`.
- [x] Create characters on server based on user
- [x] Create character at random x,y
- [x] Load simple map into server
- [x] Send map to client
- [x] Client display map
- [x] Send characters to clients and display
- [x] Basic game loop in server
- [x] Click for movement to x, y
- [x] Pass movement commands to server
- [x] Bring in `Coords`
- [x] Fix movement on server
- [x] Move character on client
- [x] Terrain types / Advanced map data
- [x] Display as scroll-o-sprites graphics
- [x] Detect clicks on Pixi display
- [x] Remove text map
- [x] Clean-up Pixi Display code
- [x] Roguelike pixel font
- [x] Enter to focus chat
- [x] Switch server to ES6 modules
- [x] Pass terrain/item data to client
- [x] Different objects for items, blocks, terrain, characters
- [x] Merge in the entity types and add tile property with key
- [x] Tell client about items/blocks
- [x] Obstacle detection on server-side
- [x] Tell display about characters separately from terrain
- [x] Display characters on sub-tile format and hide covered tile

## TO DO

- [ ] Info about what actions can be done on which entities
- [ ] Smart click so that trees can be auto-chopped

- [ ] Actions row 1-9
- [ ] Right-click for simple actions menu

- [ ] Action: Pick up item

- [ ] KB input for movement (similar to rote?)

- [ ] Action: Pick up flower from sack
- [ ] Action: Place flower down
- [ ] Action: Pick up water
- [ ] Action: Drop water on flower to mix --> make dough
- [ ] Action: Drop dough in oven
- [ ] Oven cook dough to bread

- [ ] Action: chop tree
- [ ] Update map's passable array when there are updates to terrain, blocks, items, etc.
- [ ] Action: Plant seed

- [ ] Chat bubbles

- [ ] Tell client when map content has changed rather than constantly
- [ ] Server send moves to client for animation

- [ ] A-star on server-side - https://github.com/bgrins/javascript-astar
- [ ] Switch characters into NPC mode when player leaves

- [ ] Save Player data in client
- [ ] Save Player data and reload on restart
- [ ] Save character data and reload on restart
- [ ] Save map data and reload on restart

- [ ] Scroll to zoom

- [ ] Efficiency in redrawing sprites
- [ ] Clean up client/servamo chat
- [ ] Import RocketBoots modules properly
- [ ] Move pixi display to its own library
- [ ] Move sevamo, usernaming, etc. to their own libraries

- [ ] Combine server and client together in WULF package for testing (i.e., run client from browser at `http://localhost:5000`)
- [ ] Add nvm
- [ ] Convert server so it can run in the browser

- [ ] U4 option for tiles https://github.com/jahshuwaa/u4graphics
- [ ] Pixel fonts? https://github.com/byackley/pixelfonts

## Wishlist (TBD)

- Items:
  - 1-2 - hands
  - 3-4 - body (requires shirt)
  - 5-6 - legs/belt (requires pants or belt)
  - 7,8,9,0 - back (requires backpack)
- Clothing:
  - 1 - gloves
  - 2 - rings
  - 3 - arms (bracers)
  - 4 - torso
  - 5 - pants
  - 6 - shoes
  - 7 - back
  - 8 - head

* Map builder
* Load map by height map and terrain grid
* _...TBD..._

## New Project Britannia Wishlist from SSSH podcast #15 (2015)

* Multiple magic systems
* Mana-based magic
* Spells, item-based spellcasting
* Modular sky-dome
* Multiple camera views
* Character creation system
* Skill system - effected by class
* Moongates, including different types
* Vehicle controls - carts, horses, boats
* Regional maps
* Mono-scale and dual-scale maps
* Mono-scale and dual-scale transportation
* Conversation systems - keyword vs free text
* Quest triggers
* Journal
* Annotated map
* Buy/sell system
* Banking
* Containers of items
* NPC inventories
* NPC ownership / theft
* NPC schedules
* Virtures/karma tracking for PCs
* Readable Books, scrolls
* Spellbook
* Rune pouch
* Paperdoll in inventory
* Item interactivity
* Item volume and weight
