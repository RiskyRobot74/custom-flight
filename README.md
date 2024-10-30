# Custom Flight Plugin

**Custom Flight** is a Paper Minecraft plugin designed to allow players to toggle flight mode easily in survival mode, even if they don't have creative privileges. With this plugin, server admins can empower specific players to fly at adjustable speeds, adding a unique dimension to survival gameplay without breaking immersion. This is ideal for builders, moderators, or any players needing temporary flight capabilities.

## Features

- **Toggle Flight Mode**: Players can enable or disable flight mode on the fly (pun intended) without needing creative mode.
- **Adjustable Flight Speed**: Players can set custom flight speeds, allowing for faster movement and enhanced control.
- **Player-Specific Permissions**: Admins can control who has access to flight commands via configurable permissions.
- **Survival-Friendly**: Designed to work seamlessly within survival mode without disrupting the natural gameplay mechanics.
- **Easy Command-Based Usage**: Simple and intuitive commands allow players to enable, disable, and customize flight effortlessly.

## Commands

The plugin provides the following command:

### `/fly`

The `/fly` command allows players to toggle their flight mode or another player’s, as well as set flight speed if desired.

- **Command Usage**: `/fly [player] [speed]`
  - **`[player]`**: (Optional) Specify the target player’s username. If omitted, the command will toggle flight mode for the sender.
  - **`[speed]`**: (Optional) Specify the flight speed (as an integer between 100 and 1000 for scale). For instance, `1000` represents maximum speed.

### Examples

- `/fly`: Toggles flight mode for the sender.
- `/fly Steve`: Toggles flight mode for player `Steve`.
- `/fly Steve 500`: Toggles flight mode for `Steve` with a custom speed of `500` (mid-range).

## Permissions

Control over the plugin is managed by the following permission:

- **`flyplugin.fly`**: Grants access to the `/fly` command.
  - **Default Setting**: This permission is set to `true` by default, allowing all players to toggle flight if you prefer open access.
  - **Example Usage**: Assign this permission specifically to trusted players or staff for moderation purposes.

## Installation

1. Download the `Custom Flight` plugin or mod JAR file and place it in your server’s or PCs `plugins` or `Mods` folder.
2. Restart or reload the server or Minecraft to initialize the plugin/mod.

## Known Issues and Troubleshooting

- **Command Not Recognized**: If `/fly` doesn’t work, ensure the `plugin.yml` file is correctly formatted and located at the root of the JAR.
- **Permissions Not Working**: Verify that your permissions plugin (e.g., LuckPerms) is installed and configured to recognize `flyplugin.fly`.
