# Lost Light
2D Rogue-Like Dungeon Crawler.

# Player
### Katana
Katana is the main character, he can either melee attack or reflect mage's projectiles to kill enemies.

# Enemy

### Zombie
Zombies can only melee attack Katana, and will walk towards him until death.

### Mage
Unlike Zombies, Mages don't have perception which allows them to track Katana, they have to find their own ways.
Thus, Mages have line of sight and will only cast skills towards Katana when he stands in their sight. Otherwise, they will patrol randomly inside the map.

### BOSS
BOSS can keep summoning Zombies in the world, and cast a skill which creates a volcano zone on the map, Katana will die instantly when standing on it.

# Game Control
Movement: WASD

Dash: Space

Reflect: Left Mouse Button

Reflect Direction: Cursor

Save Game Level: [ (Left Bracket)

Load Game Level: ] (Right Bracket)

# Dependencies
The game uses [entt library](https://github.com/skypjack/entt#packaging-tools) that helps manage ECS architechture.
It's required in order to compile and run the game. Installation process can be found [here](https://github.com/skypjack/entt#packaging-tools).