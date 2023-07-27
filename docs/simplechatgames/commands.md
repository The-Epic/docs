---
title: Commands
parent: SimpleChatGames
layout: default
nav_order: 2
---

# SimpleChatGames Commands

- [Reward Commands](#reward-commands)
- [Leaderboard](#leaderboard)
- [Reload](#reload)
- [Skip](#skip)

## Reward Commands

The reward sub-command (`/cg reward`) allows you to configure various types of rewards for your players. After executing any of the following commands, kindly remember to [reload](#reload) the plugin to apply the changes.

### Setting Item Rewards

To add an item reward, please follow this guide:

1. Create or obtain the item intended for the reward.
2. Hold the item in your main hand (typically the right hand).
3. Run the command `/cg reward set item`.

### Adding Command Rewards

To include a command reward, please follow this guide:

1. Determine the desired command (e.g., `/give MyName diamond 16`).
2. Input the command as `/cg reward set command`, ensuring to replace the player's name with `%player_name%` and remove the beginning slash. For instance, if the command is `/give MyName diamond 16`, the adjusted command would be `/cg reward set command give %player_name% diamond 16`.

### Adding Economy Rewards

For economy rewards, it is required to have the Vault plugin installed. Confirm its on the server with the `/plugins` command.

1. Run the command `/cg reward set economy <value>`, where `<value>` denotes the desired amount. For example, `/cg reward set economy 100` would grant players 100 units of your chosen currency.

{: .note}
Should any of these commands indicate that the item was added but the reward remains disabled, please consult the guide on how to enable rewards.

### Enabling and Disabling Rewards

The enable and disable sub-commands facilitate reward management.

To enable a reward, run the command `/cg reward enable <reward>`, substituting `<reward>` with a valid option of "item," "command," or "economy."

To disable a reward, run the command `/cg reward disable <reward>` accordingly.

### Clearing Rewards

The `/cg reward clear` command is available to remove all defined rewards and subsequently disable them.

## Leaderboard

The leaderboard command (`/cg leaderboard`) displays the current rankings based on answered questions.

You have the option to execute the command as-is to view the existing leaderboard, which includes player names and their respective answers. Alternatively, you may specify a desired page number, such as `/cg leaderboard 2`, to access results for a specific page.

## Reload

The reload command (`/cg reload`) effectively refreshes the plugin, updating all game configurations, including the plugin's config and messages config. It is advised to execute this command after modifying rewards or altering questions, answers, messages, or game duration settings.

## Skip

The skip command (`/cg skip`) grants you the ability to bypass the current question and reveal its answer in the chat. Subsequently, the plugin will automatically present a new random question from the available game pool.