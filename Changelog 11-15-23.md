# :bookmark_tabs:  Changelog 11/11/2023-Changelog 11/15/2023

<!-- ## :red_circle: Status `Unreleased` -->
## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
In this update we focused on various bug fixes, improving the systems invovled in unlocking items as well as making it more obvious that things were unlocked for the player.

________
:question: Curious about what else we're working on or future plans? Check out our Trello Board: https://trello.com/b/blG5fvE6/project-wwii
________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Reward Notifications
> We felt that when users unlocked weapons, perks, etc that it felt a bit obscure.
> Now when the player joins the game lobby, or after a round ends, a screen is shown with all items unlocked during a round.

### :white_check_mark: `Feature` Grenade Indicator
> It was very difficult to know if you were standing on-top of or near a grenade, so we added an indicator to show the direction of any nearby grenades.

### :white_check_mark: `Feature` Gunsmith
> Players can modify their weapons in the Gunsmith. This allows players to manage attachments on their weapons.

### :arrow_up_small: `Improvement` Rebuilt the minimap system from the ground up
> This also alleviates a lot of performance overhead caused by the old minimap system.

### :arrow_up_small: `Improvement` Made minimaps for all maps
### :arrow_up_small: `Improvement` Made look of in-game class selection more consistent with armory.
________

## :balance_scale: Changes

### :exclamation: `Change` Weapon and Perk changes
- Changed weapon unlock cost across the board
- Changed perk unlock cost acrosss the board
- Weapons and perks are automatically unlocked once their unlock level is reached

### :exclamation: `Change` Scoreboard and Killfeed use player Display Name now
________

## :bug: Bugfixes
- Fixed a bug which made grenade indicators never get removed if the player was in range during the explosion
- Fixed a bug which made the bots disappear randomly
- Fixed a bug where player counts were not shown in game mode selection in the lobby
- Fixed a bug where, after a new round started, a player's screen was heavily blurred
- Fixed several visual bugs with the scoreboard
- Fixed a bug where when shooting a player with the Juggernaut perk, the Juggernaut hitmarker was not displaying
- Fixed a bug where players couldn't ever change their class while in game
