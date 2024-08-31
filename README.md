# Pong Game

A classic Pong game implemented using [Raylib](https://www.raylib.com/) and C++. This game features a real-time two-player experience where you can challenge an AI opponent.

## Features

- **Real-time gameplay**: Smooth animation and responsive controls for an engaging gaming experience.
- **AI opponent**: Includes basic AI logic for a solo play option against the computer.
- **Scorekeeping**: Displays scores for both the player and the CPU.
- **Custom graphics**: Stylish visuals and animations using Raylib's drawing functions.

## Requirements

- **Raylib**: A C library for games and multimedia applications.
- **C++ Compiler**: A compatible compiler like `g++`.

## Installation

### Raylib Installation

1. **Clone the Raylib repository**:
    ```bash
    git clone https://github.com/raysan5/raylib.git
    ```

2. **Navigate to the Raylib directory**:
    ```bash
    cd raylib
    ```

3. **Build Raylib**:
    ```bash
    mkdir build
    cd build
    cmake ..
    make
    sudo make install
    ```

### Build the Pong Game

1. **Clone this repository**:
    ```bash
    git clone https://github.com/Priyammohit/PongGame.git
    ```

2. **Navigate to the PongGame directory**:
    ```bash
    cd PongGame
    ```

3. **Compile the Pong game**:
    ```bash
    g++ pong_game.cpp -o pong_game -lraylib -lGL -lm -lpthread -ldl
    ```

## Usage

1. **Run the game**:
    ```bash
    ./pong_game
    ```

2. **Controls**:
    - **Player Paddle**: Use the `UP` and `DOWN` arrow keys to move.
    - **AI Paddle**: Controlled by the game logic.

## Contributing

Feel free to contribute by submitting issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.


## Acknowledgements

- [Raylib](https://www.raylib.com/) for providing a powerful and easy-to-use library for game development.
- [Open Source Community](https://opensource.com/resources/what-open-source) for the invaluable resources and tools available for developers.
