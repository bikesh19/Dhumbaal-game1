Dhumbaal Card Game
Welcome to the Dhumbaal Card Game! This is a digital version of the traditional card game implemented in C++ using SFML (Simple and Fast Multimedia Library).

Features
-Interactive Gameplay: Play against a bot in turn-based mode.
-Dynamic Card Selection: Select cards with the mouse to create valid sets.
-Game Rules Compliance: Ensures that only valid card combinations are accepted.
-Smooth Visuals: Clean and interactive graphics rendered using SFML.
-AI Opponent: A bot that makes logical moves based on its cards.

Game Rules
The objective of the game is to form valid sets of cards and strategically manage your hand to win the game.
-Valid Card Sets:
1.Same Value: All selected cards must have the same value (e.g., 3 of Hearts, 3 of Spades, 3 of Diamonds).
2.Consecutive Sequence: Cards must form a consecutive sequence and have the same suit (e.g., 5, 6, 7 of Spades).
-Gameplay Flow:
1.Players take turns.
2.On their turn, the player can:
Pick a card from the deck or thrown card pile.
Select and throw a valid set of cards into the thrown deck.
3The bot automatically plays after the player's turn.

Installation
Prerequisites:
C++ Compiler: Make sure you have a compiler supporting C++17 or higher.
SFML Library: Download and install SFML (version 2.5.1 or later).
Steps:
1.Clone this repository:
git clone https://github.com/yourusername/dhumbaal-card-game.git cd dhumbaal-card-game  
2.Compile the code:
g++ -o dhumbaal main.cpp -lsfml-graphics -lsfml-window -lsfml-system  
3.Run the executable:
./dhumbaal  

Controls
1.Mouse Left Click: Select or deselect cards from your hand.
2.Keyboard: Use specific keys for menu navigation (if applicable).

Project Structure
/  
├── assets/               # Contains images and resources for the game  
├── src/                  # Source code files  
│   ├── main.cpp          # Main game logic  
│   ├── game.cpp          # Core game mechanics  
│   ├── bot.cpp           # Bot logic implementation  
│   └── player.cpp        # Player actions and interactions  
├── include/              # Header files  
└── README.md             # This file  

Future Improvements
1.Add multiplayer support.
2.Enhance AI strategy for the bot.
3.Include animations for smoother gameplay experience.
4.Develop an online mode.
