---
title: Installation
parent: SimpleChatGames
layout: default
nav_order: 3
---

# Installation

To begin using the SimpleChatGames plugin, follow these easy installation steps:

## Step 1: Downloading

Start by downloading the plugin from SpigotMC. You can find the plugin at [SimpleChatGames](https://www.spigotmc.org/resources/simplechatgames.108655/). Once downloaded, save it to your local `Downloads` folder.

## Step 2: Adding to Your Server

### Local Hosting (On Your Current Device)

1. Locate the downloaded plugin file in your `Downloads` folder.
2. Copy the file to your clipboard.
3. Navigate to your server's `plugins` folder.
4. Right-click on an empty space and choose "Paste" to move the file into the `plugins` folder.
5. Restart your server to complete the installation.

### Using a Hosting Company

1. Access your server's control panel.
2. Navigate to the files page.
3. Open the `plugins` folder.
4. Keep your device's file manager window open, and drag the downloaded plugin jar into the `plugins` folder in your browser.
5. Go back to the console page and click the "Restart" button. If the "Restart" button is not available, click the "Stop" button and wait for the console to clear, then click the "Start" button.

After following either of the above instructions, the plugin will be ready to use. If you want to reward your players for answering questions correctly, proceed to the next step.

## Step 3: Adding Rewards

### Item Reward

To set an item as a reward, hold the item you want to use in your hand and run the command `/cg reward set item`.

### Command Reward

You can configure multiple command rewards. For example, if you want to run the command `/give %player_name% diamond 16` as a reward, use the command `/cg reward set command give %player_name% diamond 16`. For other commands, type the command and use `%player_name%` where the name is required, without adding a starting slash.

### Currency Reward

**Note: This feature requires Vault to work. Make sure you have Vault installed along with an economy plugin that supports it.**

To add a currency reward, run the command `/cg reward set economy <value>`, replacing `<value>` with the desired amount.

{: .note}
Once you have followed any of the instructions above, run the command `/cg reload` to load the rewards and start using SimpleChatGames.