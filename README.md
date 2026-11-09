# Slot machine reel bank

An interactive isometric cutaway of a slot machine's reel bank. Pull the handle to see how it works: the handle only closes a switch, the logic board's random number generator picks a number from 0–63 for each reel, each number is looked up on a 64-entry virtual reel that maps it to one of 22 physical stops, and stepper motors spin each reel to the stop that was already chosen.

Live page: https://dstraffon.github.io/slot-machine/

Built with the [Anatomy](https://github.com/wheresryan22/anatomy) isometric drawing kit (MIT). The odds table is an illustration of how virtual reels work, not the table of any real machine.
