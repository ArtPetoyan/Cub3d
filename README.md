# Cub3D

Cub3D is a simple 3D raycaster game inspired by classic titles such as Wolfenstein 3D. It is created as part of the curriculum at [42 School](https://www.42network.org/), focusing on graphics programming, C language fundamentals, and game logic.

## Features

- **Real-time 3D rendering** using raycasting
- **Basic movement and rotation** controls
- **Texture mapping** for walls
- **Configurable map files**
- **Bonus features** (if implemented): doors, sprites, minimap, mouse controls

## Screenshots

*(Add screenshots here if available)*

## Getting Started

### Prerequisites

- GCC compiler (or Clang)
- [MiniLibX](https://github.com/42Paris/minilibx-linux) graphics library
- Makefile

### Building

Clone the repository:

```bash
git clone https://github.com/ArtPetoyan/Cub3d.git
cd Cub3d
make
```

### Running

```bash
./cub3D <map_file.cub>
```

Map files are located in the `maps/` directory.

## Project Structure

```text
Cub3d/
├── src/              # Source code files
├── include/          # Header files
├── maps/             # Example map files
├── textures/         # Game textures
├── Makefile
└── README.md
```

## Usage

- `W`, `A`, `S`, `D`: Move player
- `Arrow keys`: Rotate camera/view
- `ESC`: Quit game

## Map File Format

Sample `.cub` file:

```
NO ./textures/wall_north.xpm
SO ./textures/wall_south.xpm
WE ./textures/wall_west.xpm
EA ./textures/wall_east.xpm
F 220,100,0
C 225,30,0

111111
100001
101101
100001
111111
```

## Contributing

Open to suggestions and improvements! Feel free to submit issues or pull requests.

## License

This project is for educational purposes. See [LICENSE](LICENSE) for more details.

## Authors

- ArtPetoyan

---

*Project developed at 42 School as a graphics learning experience.*
