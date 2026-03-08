# EmbedXivModArchive

[![Version number](https://img.shields.io/badge/version-1.0.0-ff6262)](https://github.com/mashirochan/Vencord-EmbedXivModArchive)
[![Availability](https://img.shields.io/badge/availability-userplugin-orange)](https://github.com/mashirochan/Vencord-EmbedXivModArchive)

A simple plugin to embed XIV Mod Archive links from the popular MMORPG, FFXIV.

For any questions or bugs, please [Create an Issue](https://github.com/mashirochan/Vencord-EmbedXivModArchive/issues/new/choose).

<img width="450" height="430" alt="image" src="https://github.com/user-attachments/assets/bcb2f3d8-d76d-42f5-9e70-465ad148effc" />

## Features
* Native MessageAccessory embeds for XIV Mod Archive links
* Mod information including author, downloads, last updated, Dawntrail compatibility, etc.
* Convenient button to instantly download
* NSFW and NSFL content is spoilered and tagged accordingly
* Rate-limiting and caching to prevent excessive fetches to XIV Mod Archive

<img width="451" height="427" alt="image" src="https://github.com/user-attachments/assets/a9765b73-5848-4cc6-bee3-591a6f127292" />

## Installation

#### UserpluginInstaller

1. Install the [UserpluinInstaller userplugin](https://plugins.nin0.dev/userpluginInstaller/) via the steps in the "Manual" section
2. Find the EmbedXivModArchive userplugin thread in the Vencord Discord server
3. Click the "Install plugin" button that appears in the thread

#### Manual

1. Clone and set up a local build of Vencord: https://docs.vencord.dev/installing/
2. Create a folder called `userplugins` under the `src` folder in the Vencord project
3. In a terminal window under that new `userplugins` folder, run `git clone https://github.com/mashirochan/Vencord-EmbedXivModArchive`
4. Build Vencord with `pnpm build`
5. Inject Vencord with `pnpm inject`
