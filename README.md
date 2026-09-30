Lowkey a pretty nice QoL mod to have, you dont know when you may need it
Note: Auto refresh may result in a "Too many lobby requests" error. To bypass it, simply connect to a VPN. The error will go away in a few minutes otherwise
ChatGPT wrote everything after this:


# AutoRejoiner

AutoRejoiner is a standalone Among Us plugin for BepInEx IL2CPP. It adds lobby join retries, join history, cosmetic randomization, and filters for the public lobby browser.


## Features

### Join

- Enter or paste a six-character lobby code, then press **Start**. **Stop** cancels retries.
- **Stop if target lobby has started** defaults to ON. When OFF, a started lobby is retried every 10 seconds.
- A full lobby is retried every second. Other temporary join failures are retried every second. A single attempt times out after 45 seconds.
- The first attempt starts on the next game update; there is no intentional start delay.

### History

Stores up to the last 30 successful lobby joins, with lobby code, host, platform when available, region, and local join time. Entries can be joined, copied, or removed. History is stored in the BepInEx config folder.

### Randomize

- **Cycle now** toggles automatic cosmetic randomization once per second while in a lobby or game. Select which cosmetic categories to include with the toggles below it.
- **Randomize now** immediately randomizes all supported cosmetics except the player name.
- **Randomize name on leave** chooses a new name from the built-in name list after leaving a lobby.

### Lobby Finder

- Filter public lobby rows by host name and one or more host platforms.
- **Show lobby info** displays available host, code, platform, player count, and lobby age information.
- **Auto refresh lobbies** refreshes once per second while enabled. Frequent refreshes may trigger the game's “Too many lobby requests” error; the warning is shown in the mod UI. If you encounter it, stop refreshing and allow the service limit to clear. Network or VPN changes may affect connectivity but do not guarantee a fix( they do guarantee a fix, dont listen to this clanker)

Human back, credit time:
Original idea: Me. Was tired of manually entering a code every 10 seconds to join a lobby that has started
History idea: Sicko menu
Randomizers idea: Sicko menu
