# D&D Ursina Adventure - Lost Mines of Phandelver

A full 3D D&D 5e RPG game featuring the Lost Mines of Phandelver one-shot adventure. Built with Ursina (Panda3D wrapper) and Python.

## Features

- **D&D 5e Combat System**: Full initiative system, attack rolls, saves, and damage calculations
- **Lost Mines of Phandelver**: Classic encounter-based adventure
- **3D First-Person Exploration**: Navigate through mines and dungeons
- **Character System**: Full ability scores, modifiers, and skills
- **Inventory System**: Equipment and item management
- **Turn-Based Combat**: Strategic encounter gameplay

## Requirements

- Python 3.8+
- Windows or Linux
- 2GB RAM minimum
- GPU with OpenGL support

## Installation

### Windows
Download and run `DnD_Ursina_Adventure_Setup.exe` from the releases page.

### Linux
```bash
chmod +x install.sh
./install.sh
```

### Manual Installation (All Platforms)
```bash
git clone https://github.com/72nd-street-productions/dnd-ursina-adventure.git
cd dnd-ursina-adventure
pip install -r requirements.txt
python src/main.py
```

## Controls

- **WASD**: Move
- **Mouse**: Look around
- **E**: Interact
- **I**: Inventory
- **C**: Character sheet
- **Space**: Attack (in combat)
- **1-4**: Use ability/spell slot

## Project Structure

```
dnd-ursina-adventure/
├── src/
│   ├── main.py                 # Entry point
│   ├── game.py                 # Main game loop
│   ├── character.py            # Character system (D&D 5e stats)
│   ├── combat.py               # Combat system
│   ├── encounters.py           # Lost Mines encounters
│   ├── map.py                  # 3D world/map
│   └── ui.py                   # UI/HUD
├── assets/
│   ├── models/                 # 3D models
│   ├── textures/               # Textures
│   └── audio/                  # Sound effects
├── installers/
│   ├── windows_installer.iss   # Inno Setup script
│   ├── linux_installer.sh      # Bash installer
│   └── setup.py                # Python setup
├── requirements.txt            # Dependencies
└── config.yaml                 # Configuration
```

## D&D 5e Mechanics Implemented

- **Ability Checks**: STR, DEX, CON, INT, WIS, CHA
- **Saving Throws**: All six ability saves
- **Skills**: All 18 skills with proficiency
- **Attack Rolls**: Melee and ranged with modifiers
- **Damage Rolls**: Weapon damage with critical hits
- **Armor Class**: Full AC calculation
- **Hit Points**: Constitution-based HP pool
- **Proficiency Bonus**: Scales with character level

## Encounters

1. **Goblin Ambush**: Initial encounter on the Sword Coast
2. **Cragmaw Castle**: Stronghold exploration
3. **Redbrand Hideout**: Town defense scenario
4. **Wave Echo Cave**: Final boss encounter with treasure

## License

MIT License - See LICENSE file for details

## Support

For issues, questions, or contributions, please open an issue on GitHub.
