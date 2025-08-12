# Red_Star_Falling

A computer implementation of Mayfair's games discontinued "Red Star Falling" Hex wargame from 1981

Project structure:

Red_Star_Falling/
│
├── assets/                  # Images, icons, sounds, etc.
│   └── units/
│
├── ui/                      # Qt Designer .ui files
│   └── main_window.ui
│
├── src/                     # Python source code
│   ├── __init__.py
│   ├── main.py              # Entry point
│   ├── ui_main_window.py    # Auto-generated from main_window.ui
│   ├── game/                # Game logic
│   │   ├── __init__.py
│   │   ├── hex_map.py       # Hex grid logic
│   │   ├── unit.py          # Unit definitions
│   │   └── game_state.py    # Game state manager
│   └── gui/                 # GUI logic
│       ├── __init__.py
│       ├── main_window.py   # Main window controller
│       └── hex_view.py      # Custom QGraphicsView for hex map
│
├── tests/                   # Unit tests
│   └── test_hex_map.py
│
├── requirements.txt         # Python dependencies
├── README.md
└── .gitignore