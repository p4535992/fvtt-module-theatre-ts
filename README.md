# Theatre

Theatre is a mod for Foundry VTT that allows for a visual novel style RP experience for text, and text-voice hybrid games. The primary function of Theatre is to allow for graphical 'theatre-inserts' or 'standin-graphics' to appear on screen with an accompanying area for text beneath them. This follows the style of visual novels, and even provides a means to animate or decorate the text as it appears in the below box. It also provides an emote system to allow users to configure different graphics for the various emotive expressions. Most of the emotes additionally have a built in 'emote animation' that occurs when the emote is selected, which can be toggled off globally if undesired.

# About this fork

Currently under development. Don't use this.
## Setup

1. npm install
2. Copy `.vscode/settings.template.json` to `.vscode/settings.json` and do what it says in the file.
3. Copy `devEnv.template.json` to `devEnv.json` and do what it says in the file.
4. Run `npx gulp dev --sm`
5. Start FoundryVTT server
5. Launch  `FoundryVTT` under `Run and Debug`

# Installation (for this fork)

To install this module manually:
1. Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2. Click "Install Module"
3. In the "Manifest URL" field, paste the following url:
`https://raw.githubusercontent.com/watermelonwolverine/fvtt-module-theatre/master/module.json`
4. Click 'Install' and wait for installation to complete
5. Don't forget to enable the module in game using the "Manage Module" button

# Installation

It's always better and easier to install modules through in in app browser. Just search for "Theater"

To install this module manually:
1. Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2. Click "Install Module"
3. In the "Manifest URL" field, paste the following url:
`https://raw.githubusercontent.com/League-of-Foundry-Developers/fvtt-module-theatre/master/module.json`
4. Click 'Install' and wait for installation to complete
5. Don't forget to enable the module in game using the "Manage Module" button

### libWrapper

This module uses the [libWrapper](https://github.com/ruipin/fvtt-lib-wrapper) library for wrapping core methods. It is a hard dependency and it is recommended for the best experience and compatibility with other modules.

### Key Binds
Theatre inserts now supports keybinds through the keybind API. The default keybinds are as follows (on windows):

- **Add OWNED Actors to Stage**: ALT+ Enter
- **Add SELECTED Tokens to Stage**: Shift + Enter
- **Toggle Narrator Mode**: Control + N
- **Flip Portrait**: ALT+R
- **Nudge Portrait**: Alt + Z/C/S/X
- **Activate Staged Actor Number 1/2/3...**: Control + 1/2/3...
- **Remove Staged Actor Number 1/2/3...**: Control + Alt + 1/2/3...


### Usage

Right-click an Actor in the list, and select "Add to stage." The Character will now appear in the small bar at the bottom of the Chat window.

![img](/wiki/images/0aUQcD9.png)

![img](/wiki/images/8KKAY0G.png)

Right-Clicking that actor tile will cause the actor's image and name to appear in the bottom-left of the screen. You can apply Emotes to them via the Emote Selector button, just above the chat box. 

While the actor is selected in the small box, anything that is typed into Chat will be written as the Actor, and will also appear below the Actor insert on the left side.

Another button next to chat, the Megaphone, causes a black box to appear in the middle of the screen. Anything that the GM types to chat will appear in this box. This is good for describing a scene.

## For a detailed list of instructions, checkout the [WIKI](/wiki/instructions/home.md) or visit the original Repo by Ken L: https://gitlab.com/Ayanzo/theatre/-/wikis/home/Introduction%20to%20Theatre, these wiki are pretty old so be aware

### Contributors

The original and immense work is from `Ken L`, Theatre Inserts was then be picked up by `NoahZorbaugh`, and then by `U~Man` who maintained the day to day updates. `Brother Sharp` commissioned on behalf of the Japanese TRPG community the port of the module to Foundry VTT 0.7.7, done by `KaKaRoTo`. Update (0.8.6) by `elizeuangelo`. Latest Update (v9) by  `enso#0361`, Thanks!

The Japanese community will be placing bounties for maintaining theatre inserts through major updates. If you wish to contribute to the cause of keeping this module alive, please consider joining our Patreon. You won't be getting any perks, but your money will be used on this module. (https://www.patreon.com/onsekobo)

Contributions are most welcome, please do one Pull Request per feature.
