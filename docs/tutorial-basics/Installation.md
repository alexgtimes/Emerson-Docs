---
sidebar_position: 1
---

# Installation
:::info[Disclaimer]

This documentation is in progress.

:::

1. Get the [license](https://www.roblox.com/game-pass/120573759/Emerson-PrintLink) and [model](https://create.roblox.com/store/asset/14996803013/Emerson-PrintLink)
2. Insert the model into your game
3. Go to Game Settings > Security and enable HTTP Requests & API Services in studio
4. Insert your group name and logo (optional) and then customise the settings to your liking
5. If you are using a group, we recommend using the whitelist.
6. For whitelists with individual players, follow the steps below.

```lua title="Emerson Printlink/Configuration/Settings.lua BEFORE"
		--["ArchieStatixx"] = {
		--	["CanLogin"] = true,
		--	["CanAddCredits"] = false,
		--},
```

```lua title="Emerson Printlink/Configuration/Settings.lua AFTER"
		["ArchieStatixx"] = {
			["CanLogin"] = true,
			["CanAddCredits"] = false,
		},
```
