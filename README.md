# WULF - Web-based Ultima-Like Framework

WULF is a project that intends to create a framework based on open web technology that would allow easy creation of Ultima-like browser games.

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


- Run client from browser at `http://localhost:5000` (not working)
- OR run client with a separate server (e.g. Fenix) at an address like `http://localhost/WULF-client/`.

- [x] Create characters on server based on user
- [x] Create character at random x,y
- [x] Load simple map into server
- [x] Send map to client
- [x] Client display map
- [x] Send characters to clients and display
- [x] Basic game loop in server
- [x] Click for movement to x, y
- [x] Pass movement commands to server

## TO DO

- [ ] Bring in `Coords`
- [ ] Fix movement on server
- [ ] Move character on client
- [ ] KB input for movement
- [ ] Tell client when map content has changed
- [ ] Server send moves to client for animation

- [ ] Clean up client/servamo chat
- [ ] Bring client code into server for testing? or have a status / landing page?
- [ ] Add nvm
- [ ] Move sevamo, usernaming, etc. to their own libraries

## Wishlist (TBD)

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
