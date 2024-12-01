Chai Levy - 313589038
# Sword-Duel Game
This is a player-versus-player game created for the 3rd weekly assignment of the Game Development Course at Ariel Univerisity.
* The game features 2 player gameplay and aims to create the core process of a fighting game.
* The players can move, jump, and attack.
* The goal is to beat the other player (red versus blue).
### Itch io link
* [https://chai9l.itch.io/game-dev-course-3-b](https://chai9l.itch.io/game-dev-course-3-b)
## Code locations and usage
* Input Mover - This script is responsible for the movement of the players.
* PlayerHealth - This script is responsible for the player's health, it connects the health bar to the player, and it also handles the take damage function that will decrease the player's health on a sword hit from the opposing player (Sword hit is broken down to Damage, Knockback direction)
* SwordDamage - This script is responsible for the damage and physics the sword object has. (The sword will knock back on hit as well as damage the other player hit by it).
* Attack - This script is responsible for tying the animation of the sword attack to the SwordParent object which is the parent of the sword.
## Player-1 Keybinds
* W,A,D for movement
* Spacebar to attack
## Player-2 Keybinds
* Arrow Keys for movement
* Numpad Enter to attack

 
## Acknowledgements

Sword Sprites:
* [datDev26](https://datdev.itch.io/)
