# REBOUND v35 – Levels + Start Adventure Fix

Root cause fixed:
The level menu was trying to use the THEMES constant before THEMES had been initialized. That JavaScript error stopped the rest of the script, which is why the level buttons were blank and Start Adventure did nothing.

v35:
- Initializes the 25 level buttons only after theme data and handlers exist.
- Restores the visible level grid.
- Restores a working Start Adventure button.
- Keeps themed worlds, landscape resizing, PWA/Home Screen support, runner, rewards, coins and lives.
- Includes a Level 1 fallback if the menu ever hits an initialization error.
