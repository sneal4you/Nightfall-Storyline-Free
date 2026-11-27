# Nightfall Storyline FREE

Nightfall Storyline is an automation bot for Guild Wars: Nightfall. It plays the campaign quests and missions in order: travel, movement, party and hero setup, builds, combat, loot, inventory and mission transitions.

| Edition | Phases | Where to get it |
|---|---|---|
| FREE | 16 (from Chahbek Village to Blacktide Den) | This repository's [latest release](https://github.com/sneal4you/Nightfall-Storyline-Free/releases/latest) |
| FULL | 58 (the whole campaign, up to Abaddon's Gate) | Download page linked in your FULL license message |

## Features

- **Dervish and Ranger**: choose the profession of your character in the bot window.
- **First or second character**: works on a new account and on a character of an account that already has the heroes and skills unlocked.
- **One bot, one Guild Wars**: each bot is tied to its own Guild Wars client. Closing the bot (or a crash) closes only that client, never the clients of other accounts.
- **Automatic recovery**: after a disconnect, a stuck loading screen or a phase that keeps failing, the bot restarts itself and its Guild Wars and continues the campaign instead of standing still.
- **Summoning stone**: the bot asks for the Igneous Summoning Stone with `/bonus`. If your account does not get it, the bot simply continues without it.
- **Progress is saved**: if you stop the bot, it continues from the current phase next time.

## Requirements

- Windows 10 or 11.
- A Guild Wars account with the Nightfall campaign.
- The bot and the launcher run as administrator (Windows will ask for permission).

## Download

Download `NightfallStoryline-FREE.zip` from the [latest release](https://github.com/sneal4you/Nightfall-Storyline-Free/releases/latest) and extract it keeping its folders. You get the bot (`NightfallStoryline-FREE.exe`) and the `launcher` folder.

## Licenses

Both licenses are delivered on the [Nightfall Storyline Discord server](https://discord.gg/378MDSMdrF). Each license is valid for one device. Enter the key when the bot asks for it.

- **FREE**: react with ✅ to the pinned post in the role-requests channel to get the **Tester** role, then use `/license` in the licenses channel. The key arrives by direct message and does not expire.
- **FULL**: ask an administrator on the Discord server. The **Customer** role is given automatically about a minute after your license is registered; then use `/license` in the customers channel. You receive the key and the download link by direct message.

## How to use

1. Open `launcher\GW_Launcher.exe` and add your Guild Wars account.
2. Launch Guild Wars from the launcher, sign in and create a Dervish or Ranger character. Then close Guild Wars completely.
3. Run the bot and select the account.
4. At the top of the bot window, tick:
   - the profession: **Derviche** (Dervish) or **Ranger**;
   - **Skills (primer personaje)** for the first character of the account, or **Unlocked (segundo personaje)** if the account already finished the campaign with another character.
5. Press **START**. The bot opens Guild Wars and plays the campaign.

Run one bot per PC.

## Latest update (27 November 2026)

- The bot no longer stands still for hours when a phase keeps failing: after its retries it restarts itself and Guild Wars and resumes.
- Chahbek Village no longer loops when `/bonus` does not give the summoning stone.
- FULL edition: fixes for To Kill a Demon (Dehjah dialogue), Kodonur Crossroads (stuck in the city), Consulate Docks (Nerashi's gate), Ranger skill purchases and the Burning Arrow capture.

## Support

Report problems in the Discord server, with the phase and the time when it happened.
