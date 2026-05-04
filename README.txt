HSSaveEditor Steam Deck Web v1.0.0
==================================

Offline web version for Steam Deck and other systems where the desktop app is not convenient.

What is included
----------------
- index.html: Offline browser-based Hero Siege .hss save editor.

How to use
----------
1. Close Hero Siege before editing or replacing save files.
2. Open index.html in a Chromium-based browser.
3. Select your Hero Siege .hss character save file.
4. Edit the values you want.
5. Use "Save Directly..." if your browser supports it.
6. If direct save is not supported, use "Download Edited .hss" and replace the original file manually.

Steam Deck note
---------------
Gold and Professions are not shown in this web build because those values are backed by shop.ini.
On Steam Deck, the browser file picker usually cannot access shop.ini reliably, so those fields are hidden to avoid confusing or broken edits.

Safety notes
------------
- Intended for offline/single-player saves only.
- Do not use with online characters, multiplayer, leaderboards, trading, or anti-cheat protected modes.
- Always close the game before replacing or overwriting save files.
- Keeping a backup of your original save is recommended.
