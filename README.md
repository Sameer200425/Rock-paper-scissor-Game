# Rock Paper Scissors Game

A fun, interactive console-based Rock Paper Scissors game written in Python with multiple difficulty levels and comprehensive features.

## 🎮 Features

- **Interactive Console Interface**: Clean, user-friendly command-line interface
- **Smart AI Opponent**: Computer player with adaptive difficulty
- **Score Tracking**: Keep track of wins, losses, and ties
- **Input Validation**: Robust input handling with helpful error messages
- **Shortcuts**: Quick commands for faster gameplay
- **Statistics**: Detailed game statistics and performance metrics
- **Modular Design**: Well-structured, maintainable code architecture

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Navigate** to the project directory
3. **Run the game**:

   ```bash
   python main.py
   ```

## 🎯 How to Play

### Basic Commands

- `rock` or `r` - Choose rock 🪨
- `paper` or `p` - Choose paper 📄
- `scissors` or `s` - Choose scissors ✂️
- `score` - View current score
- `quit` or `q` - Exit the game

### Game Rules

- Rock crushes Scissors
- Paper covers Rock
- Scissors cuts Paper

## 📁 Project Structure

```text
rock-paper-scissors/
├── main.py           # Main game entry point
├── game_logic.py     # Core game mechanics and rules
├── player.py         # Player classes (Human & Computer AI)
├── utils.py          # Utility functions and helpers
├── test_game.py      # Unit tests
└── README.md         # This file
```

## 🧪 Testing

Run the test suite to verify all components work correctly:

```bash
python test_game.py
```

The test suite includes:

- Game logic validation
- Player input handling
- Computer AI behavior
- Utility function testing

## 🤖 AI Difficulty Levels

### Random Mode (Default)

- Computer makes completely random choices
- Good for casual play

### Adaptive Mode

- Computer analyzes your playing patterns
- Attempts to counter your most common choices
- Provides a more challenging experience

## 🔧 Customization

### Changing AI Difficulty

Edit the `main.py` file and modify the computer player initialization:

```python
# For adaptive AI
computer = ComputerPlayer(difficulty='adaptive')

# For random AI (default)
computer = ComputerPlayer(difficulty='random')
```

### Adding New Features

The modular design makes it easy to extend:

- Add new game modes in `game_logic.py`
- Implement different AI strategies in `player.py`
- Add new utility functions in `utils.py`

## 🎨 Sample Gameplay

```text
    ╔══════════════════════════════════════╗
    ║        ROCK PAPER SCISSORS           ║
    ║                                      ║
    ║    🪨  Rock beats Scissors           ║
    ║    📄  Paper beats Rock              ║
    ║    ✂️   Scissors beats Paper          ║
    ║                                      ║
    ║         Let's Play!                  ║
    ╚══════════════════════════════════════╝

Welcome to Rock Paper Scissors!
Commands: 'rock', 'paper', 'scissors', 'score', 'quit'
--------------------------------------------------

Player, enter your choice: rock

You chose: rock
Computer chose: scissors
Result: You win!
------------------------------
```

## 🛠️ Requirements

- Python 3.6 or higher
- No external dependencies required

## 📊 Features in Detail

### Score Tracking

- Real-time score updates
- Round counting
- Win rate calculation
- Performance feedback

### Error Handling

- Graceful handling of invalid inputs
- Clear error messages
- Keyboard interrupt handling

### Code Quality

- Comprehensive docstrings
- Type hints where applicable
- Unit test coverage
- PEP 8 compliant formatting

## 🤝 Contributing

Feel free to contribute to this project by:

1. Forking the repository
2. Creating a feature branch
3. Making your changes
4. Adding tests for new features
5. Submitting a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Enjoy the Game

Have fun playing Rock Paper Scissors! Try to beat the adaptive AI and see how high you can get your win rate!
