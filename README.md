# 🎮 SQChamber (One in the Chamber MiniGame Engine)

> **⚠️ Note:** This script is not 100% complete and may contain some bugs or errors during development and usage.

---

## 📖 Overview
**SQChamber** is a PvP MiniGame engine designed entirely for **Vanilla Skript**, requiring zero external addons. It delivers the classic **One in the Chamber** gameplay experience featuring an advanced arena system, a smart control GUI, and fully integrated combat and kill mechanics.

---

## ⚙️ Customizable Options
The script includes fully flexible configuration options right at the top of the code to customize your experience:

* **`prefix`**: The chat prefix displayed before plugin messages (`&8[&cSQC&8] &r`).
* **`max_lives`**: The starting number of lives assigned to each player in a match (default: `3`).
* **`max_arena_players`**: The maximum allowed player limit for a single arena (default: `32`).
* **`game_time`**: The maximum duration of a match in seconds (default: `300` seconds / 5 minutes).
* **`post_game_wait`**: The waiting time in seconds after the match ends before returning players to the hub (default: `6` seconds).
* **`spawn_protection`**: The duration of spawn invulnerability in seconds upon respawning (default: `3` seconds, `0` to disable).
* **`start_freeze_time`**: The preparation countdown freeze time in seconds at the beginning of a match (default: `5` seconds).
* **`countdown_low`**: Countdown time in seconds when 25% of arena capacity is filled (default: `60`).
* **`countdown_mid`**: Countdown time in seconds when 50% of arena capacity is filled (default: `30`).
* **`countdown_full`**: Countdown time in seconds when 100% of arena capacity is filled (default: `10`).

---

## 🛠️ Admin Commands
All administration commands require the admin permission (`sqc.admin`):

* `/sqc sethub` - Set the main hub location to keep the return point.
* `/sqc delhub` - Delete the main hub location.
* `/sqc addarena <name> <max_players> [item_icon]` - Create a new arena specifying its max players and GUI icon.
* `/sqc delarena <name>` - Delete the arena and all its data completely.
* `/sqc pos1 <name>` - Set the first position (Pos1) of the arena boundaries at your location.
* `/sqc pos2 <name>` - Set the second position (Pos2) of the arena boundaries at your location.
* `/sqc setlobby <name>` - Set the arena waiting lobby point (must be within Pos1 and Pos2).
* `/sqc addspawn <name>` - Add a random spawn point for players inside the arena boundaries.
* `/sqc delspawn <name> [number]` - Remove a spawn point (the last point or a specific number).
* `/sqc clearspawns <name>` - Clear all spawn points for the arena at once.

---

## 👥 Player Commands
* `/sqc join [arena]` - Join a specific arena, or automatically join a random arena if left empty.
* `/sqc joining` - Open the interactive 6-row arena selector GUI, complete with a black stained glass border and a central Ender Eye for fast random joining.
* `/hub` or `/sqc leave` - Leave the current match and return to the main hub.
* `/sqc arenalist` - View available arenas, their status, and any missing requirements (such as a missing lobby or insufficient spawn points).

---

## 🌟 Gameplay Features & Engine Systems
* **One-Hit Kills**: Projectiles deal instant and fatal damage (999 damage).
* **Kill Rewards**: Killing any opponent fully heals you and rewards you with an extra arrow (`+1 Arrow`).
* **Killstreaks**: Global arena announcements for any player reaching multiple kill milestones (every 5 kills).
* **Glowing Target Leader**: The player holding the highest number of lives turns into a glowing target for everyone else to challenge.
* **Sudden Death / Overtime**: Triggers a 1-life tie-breaker mode if players are tied when the main timer expires.
* **Professional GUI**: A clean selection interface that prevents any interference with the player's personal inventory, while displaying incomplete arenas as "(Coming Soon)".

---

## 📂 Other Scripts By Me
Check out my other Minecraft Skript repositories:
* **SQDual:** [amajd3078/SQDual](https://github.com/amajd3078/SQDual) - Ultimate 1v1 Duel Engine for Minecraft Skript (Zero Addons Required).
* **SQKoth:** [amajd3078/SQKoth---King-of-the-hill](https://github.com/amajd3078/SQKoth---King-of-the-hill) - An advanced, lightweight, and lag-free King of the Hill script for Minecraft servers, featuring absolute coordinate conversion and zero addon dependencies.

---

## 📞 Support & Contact
If you encounter any bugs or want to follow updates, feel free to join my Discord server:
* **Discord:** [Discord Link](https://discord.gg/28pTmAYCwH)
* **GitHub:** [amajd3078](https://github.com/amajd3078)
