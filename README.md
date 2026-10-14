🔥 keepinvformee — Minecraft Java Plugin

A lightweight Minecraft plugin that lets server OPs manage individual players' keep-inventory, invisibility, and visibility with simple commands.

📌 About

"keepinvformee" is a custom Minecraft Java plugin designed for Paper servers. It allows server operators (OPs) to enable keep-inventory for specific players and control whether individual players are visible to others.

The plugin is suitable for SMP servers, survival servers, and private Minecraft communities that need simple player-management commands.

✨ Features

- 🎒 Individual Keep Inventory: Enable keep-inventory for a specific player without enabling it for everyone.
- 👻 Player Invisibility: Make a selected player invisible to other players.
- 👁️ Player Visibility: Make a previously hidden player visible again.
- 🔒 OP-Only Commands: All three commands are restricted to server operators.
- ⚙️ Simple Commands: Easy-to-remember commands with a player username argument.
- 🌍 Multiplayer Friendly: Designed for Minecraft multiplayer servers.
- 🖥️ Paper Server: Intended for Paper-based Minecraft Java servers.

💻 Commands

Command| Description| Permission
"/keepinv <username>"| Enables keep-inventory for the specified player| OP only
"/invisible <username>"| Hides the specified player from other players| OP only
"/visible <username>"| Makes the specified player visible again| OP only

Example Usage

/keepinv Abhi
/invisible Abhi
/visible Abhi

Replace "Abhi" with the target player's username.

🔐 Permissions

All commands are intended for OP players only. Regular players should not be able to execute these commands.

📥 Installation

1. Download "keepinvformee.jar" from the repository's Releases section or file list.
2. Open your Minecraft server's "plugins" folder.
3. Upload "keepinvformee.jar".
4. Restart your Paper server.
5. Join as an OP and test the commands.

Aternos Installation

1. Open your Aternos server.
2. Go to Files and open the "plugins" folder, if manual plugin uploads are supported for your server setup.
3. Upload the JAR if the option is available.
4. Restart the server.

Note: Aternos restricts manual plugin JAR uploads on its standard hosting setup. If direct uploads are unavailable, the plugin may need to be installed through an accepted distribution or supported plugin listing.

🎯 Compatibility

- Platform: Minecraft Java Edition
- Server software: Paper
- Target version: Minecraft 26.2, as requested
- Java: Use the Java version required by your selected Paper build.

Compatibility should be confirmed by testing the JAR on the exact server version before production use.

⚠️ Important Notes

- "/keepinv" is intended to affect only the selected player, not the entire server.
- "/invisible" hides a player from other players; it does not necessarily make them undetectable to server administrators or plugins.
- "/visible" restores the selected player's visibility.
- Actual persistence across restarts and reconnects depends on the implementation.
- This project has not been verified on a live server.

📜 License

You may add a license such as MIT if you want others to reuse, modify, and distribute the source code. Do not claim a license until you have added it to the repository.

---

Plugin Name: keepinvformee
Category: Minecraft Java / Paper Plugin
Purpose: Individual keep-inventory and player visibility management
Created for: Minecraft SMP and survival servers
