# NBA Stats Project Python

This script retrieves NBA stats and data from the NBA API and displays them in the terminal.

## Requirements

- Python 3.x
- `requests` module (`pip install requests`)

## Usage

1. Clone the repository
2. Navigate to the project directory
3. Run the script using `python main.py`
4. The console will display team stats sorted by points per game.

## Code Explanation
- `get_links()` function retrieves links to data from the NBA API
- `get_scoreboard()` function retrieves current scores and game information and prints them to the console
- `get_stats()` function retrieves team stats and prints them to the console, sorted by points per game
- The script uses the `requests` module to make HTTP requests to the NBA API and the `pprint` module to format the output.

## Notes

The NBA API is subject to change, which may cause this script to fail or produce unexpected output.
