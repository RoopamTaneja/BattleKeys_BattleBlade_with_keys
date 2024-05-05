# BattleKeys : BattleBlade with Keys

## Project Description

BattleBlade is a multiplayer desktop game which comes with an integrated android controller app and was developed for a group course project for course CSN-254 : Software Engineering.

The game was initially developed to be playable with keys and the controller functionality was added on afterwards using websockets.

Aforementioned project : https://github.com/Project-Group-Software-Engineering/BattleBlade

The game with keypresses is however equally fun to play and is hereby presented.

## Features

- Fast and responsive fighting controls
- Multiple characters from different fictional universes like Marvel, DC, Pokemon, Dragon Ball etc
- Special in-game superpower mechanics


## Tech Stack

- Python
- Pygame


## Installation

1. Clone the repository and go to project directory

```bash
git clone git@github.com:RoopamTaneja/BattleKeys_BattleBlade_with_keys.git
cd BattleKeys_BattleBlade_with_keys
```

2. Make sure you have pygame installed in your system

```bash
pip install pygame
```

3. Run main.py and enjoy the game

```bash
python main.py
```

## Game Controls

- Press space to start the game.
- Both players navigate on the square of the character they wish to choose. Once both are satisfied, press 1 to start the game.
- Two attacks are available to each player : 
  - Attack 1 is a normal attack which decreases enemy's HP by 5.
  - Attack 2 is a special attack which decreases enemy's HP by 20 but once used it becomes unavailable for a long duration of time indicated by a timer.
- Two superpowers have also been provided in game:
  - First superpower boosts player's current HP by 80% of his current HP but only if his HP <= 50.
  - Second superpower makes the player invincible i.e his HP won't decrease at all for next 5 seconds.
- Both superpowers are available to both players however one player can use only one of them in a particular round.

- Keys for controlling players:
  - Player 1 :

  | Control       | Key     |
  | ------------- | ------- |
  | Movements     | w-a-s-d |
  | Attack 1      | r       |
  | Attack 2      | t       |
  | Health Boost  | f       |
  | Invincibility | x       |

  - Player 2 :
  
  | Control       | Key                |
  | ------------- | ------------------ |
  | Movements     | up-right-down-left |
  | Attack 1      | 1                  |
  | Attack 2      | 2                  |
  | Health Boost  | 3                  |
  | Invincibility | 4                  |

- Once any player takes an invincible lead, the game ends with the winner displayed and can be exited by pressing space.

### Made with ❤️ by team BattleBlade