# Strafer settings storage

This page keeps the settings of [Strafer](https://gamebanana.com/mods/725040), a HUD mod for Deadlock.

Deadlock HUD mods cannot write files. Strafer opens this page in a hidden panel of the game (Steam's built-in
browser) and keeps its settings in that browser's local storage on the player's PC. The page only reads and writes
keys that start with `movement_compass/`, and nothing is sent anywhere.

The mod sends its requests as the fragment of the page address (`#<request>`) and the page answers through its title
(see the comments in `index.html`). Since the Deadlock update of October 1, 2026 these hidden panels open only https://
addresses, which is why the page is hosted here.
