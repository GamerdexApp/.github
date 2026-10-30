# Gamerdex

Free progress trackers for the games you play. Each tracker keeps your playthroughs, collections and plans in your browser. There is no account to make, and nothing is sent anywhere unless you turn on cloud sync, which saves your data to storage you own.

Start at [gamerdex.app](https://gamerdex.app) or open a tracker directly.

## Trackers

| Game | Site | Source |
| --- | --- | --- |
| Dinkum | [dinkum.gamerdex.app](https://dinkum.gamerdex.app) | [dinkum-tracker](https://github.com/GamerdexApp/dinkum-tracker) |
| Stardew Valley | [stardew-valley.gamerdex.app](https://stardew-valley.gamerdex.app) | [stardew-valley-companion](https://github.com/GamerdexApp/stardew-valley-companion) |
| Whiteout Survival | [whiteout-survival.gamerdex.app](https://whiteout-survival.gamerdex.app) | [whiteout-survival-tracker](https://github.com/GamerdexApp/whiteout-survival-tracker) |
| Supermarket Simulator | [supermarket-simulator.gamerdex.app](https://supermarket-simulator.gamerdex.app) | [supermarket-simulator-buddy](https://github.com/GamerdexApp/supermarket-simulator-buddy) |
| Clash of Clans | [coc.gamerdex.app](https://coc.gamerdex.app) | [clash-of-clans-tracker](https://github.com/GamerdexApp/clash-of-clans-tracker) |

## Cloud sync

Sync is optional and works the same way in every tracker. You connect Google Drive, Dropbox, OneDrive or a GitHub repository, and your data is written to a `Gamerdex` folder there. When two devices change the same playthrough, the merge keeps the higher progress.

- [gamerdex-sync](https://github.com/GamerdexApp/gamerdex-sync) is the shared library behind it, published on npm as [`@gamerdexapp/gamerdex-sync`](https://www.npmjs.com/package/@gamerdexapp/gamerdex-sync).
- [gamerdex-auth](https://github.com/GamerdexApp/gamerdex-auth) is a small service that exchanges sign-in codes for tokens. It stores no data.

## Get involved

Found a bug or a wrong number? Open an issue on the tracker's repository, or come talk to us on [Discord](https://discord.gg/NBTjUCvqev).

Gamerdex is an unofficial fan project. It is not affiliated with or endorsed by the developers or publishers of any game it covers. Game names and content belong to their owners.
