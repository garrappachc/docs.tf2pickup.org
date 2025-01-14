---
title: Website settings
---

## Settings overview

Currently website settings lets you:

- configure map pool,
- configure whitelist,
- configure default player skill,
- force create player account,
- show site player skill table,
- scramble maps available to vote at the moment,
- edit rules.

![admin-panel](/img/content/admin-panel.png)

## Map pool settings

You can configure as much maps as you want to. You have to make sure the map is placed in the `maps` folder in the game servers, so they will be able to start the map. Values on left are map names without `.bsp` extension file and values on right are config names placed in the `cfg` folder (at the moment only ETF2L configs are available).

![set-map-pool](/img/content/set-map-pool.png)

## Defining a whitelist

Here you can set up a whitelist by defining a whitelist name or its ID from [whitelist.tf](https://whitelist.tf). If not defined, all items will be available on the pickup games.

![set-whitelist](/img/content/set-whitelist.png)

## Force create a player account

This lets you force create accounts, omitting registration requirements which are:

- having a public profile with public game progress, just like here:

![public-game-details](/img/content/public-game-details.png)

In case a player won't have the game details public, an error will show up after the first log-in:

![error-tf2-private-details](/img/content/error-tf2-private-details.png)

- having an ETF2L profile ([like this](https://etf2l.org/forum/user/48288/)),

If the player doesn't have an ETF2L profile registered then an error will show up after the first log-in.:

![error-tf2-insufficient-tf2-game-hours](/img/content/error-tf2-insufficient-tf2-game-hours.png)

- having more than 500 hours in the Team Fortress 2:

![tf2-in-game-hours](/img/content/tf2-in-game-hours.png)

In case a player won't have the sufficient amount of hours spent in the Team Fortress 2, an error will show up after the first log-in:

![error-tf2-insufficient-tf2-game-hours](/img/content/error-tf2-insufficient-tf2-game-hours.png)

All you need to do is to enter a player nickname and SteamID64 format value, for instance `76561198011558250`.

![force-create-user-account](/img/content/force-create-user-account.png)

When the profile is created, it will be completely empty like on this screenshot below:

![force-created-profile](/img/content/force-created-profile.png)

All user data will be filled up once the user for which an account was force created will log-in to the site.

:::tip

If a player comes in an issue where they cannot log in due to the errors shown above, let them know that they should wait a bit before they attempt to log in again, because otherwise they will end up with the same error for a short period of time.

:::

## Setting up player skills

See [here](/docs/the-most-common-tasks#setting-up-player-skills).

## Set up website rules

See [here](/docs/final-touches#adding-site-rules).
