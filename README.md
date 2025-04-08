# Game Boy ROM Launcher

A Python-based Game Boy ROM launcher with a modern UI that allows you to browse and launch Game Boy ROMs.

## Changes Made

The following changes were made to make the launcher work properly:

1. Updated Tkinter trace method syntax to be compatible with Python 3.13:
   - Changed `trace('w', callback)` to `trace_add('write', callback)`
2. Added virtual environment support for PyBoy installation
3. Updated Python path to use the virtual environment's Python interpreter

## Setup Instructions

1. Install Python 3.13 and Tkinter:
   ```bash
   brew install python@3.13 python-tk@3.13
   ```

2. Create and activate a virtual environment:
   ```bash
   python3.13 -m venv venv
   source venv/bin/activate
   ```

3. Install PyBoy:
   ```bash
   pip install pyboy
   ```

4. Run the launcher:
   ```bash
   python game_launcher.py
   ```

## Features

- Modern UI with a hacker aesthetic
- ROM search functionality
- Game launching capability
- Settings and keybind configuration
- Status display

## Controls

- Double-click or select a game and click "LAUNCH GAME" to start
- Use the search bar to filter games
- Access settings and keybinds through the respective buttons 