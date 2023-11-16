# Warlock PF2e module for FoundryVTT
This module is a complete conversion of the warlock class from D&D to Pathfinder 2nd edition. The class takes inspiration from 3rd edition warlock, 5th edition warlock, as well as some elements from Pathfinder's witch class.

You can find a complete rundown of the class on its dedicated Scribe page: https://scribe.pf2.tools/v/1dlsL6bS-warlock

The Foundry module features the class, along with all its features, new feats, new spells, and a decent amount of automation. Additional features will be implemented on a case-by-case basis as time allows.

Since the class uses much of the verbiage of its D&D iterations and many recognizable mechanics, it is licensed under OGL, though it is fully compatible and compliant with the remastered ORC edition of Pathfinder 2e.

## Building
To make a custom build of the module, you'll need to have NPM installed for running the build script and the latest code checked out of the repository.

You can build the latest version of the module by running the following commands:
```bash
npm install
npm run build
```
You can also pack individual compendiums with the following sub-commands:
```bash
npm run pack:class
npm run pack:patrons
npm run pack:feats
npm run pack:spells
npm run pack:effects
npm run pack:abilities
```