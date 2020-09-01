# WarMod [BFG] | ZK Servidores™
An automative service for CS:GO competition matches.

Modified from **WarMod [BFG] v20.06.24.1348**.

## Players Commands
**CVARS** | **Description** | **Commands** |
:--------: | -------- | :--------: |
**sm_ready** | Mark the player as ready. | !ready, !r, !pronto |
**sm_notready** | Marks the player as not ready. | !notready, !nr, !unready, !ur, !aquecendo |
**sm_stay** | Choose to stay on the same team after winning the knife round. | !stay, !ficar |
**sm_swap** | Choose to switch teams after winning the round knife. | !swap, !switch, !trocar |
**sm_pause** | Ask for a pause in the game during freezetime. | !pause |
**sm_unpause** | Removes the pause from the game. | !unpause|
**sm_overtime** |  Asks to play overtime if the match is a draw. | !overtime, !ot |
**sm_veto** |  Ask veto to choose a map to play. ***(Types of veto works according to what is configured on the server)*** | !veto, !veto1, !veto2, !veto3, !veto5, !vetomaps,|

## Admin Commands
To use admins commands you must have the `ADMFLAG_CUSTOM1` privilege.

**CVARS** | **Description** | **Commands** |
:--------: | -------- | :--------: |
**sm_forcestart** | Force start of the game even without the players ready. | !forcestart, !fs |
**sm_forceend** | Forces the game to end no matter what the reason. | !forceend, !fe |
**sm_roundknife** | Remove all weapons except knife for a round knife before the live players choose the team. | !roundknife, !rk |
**sm_cancelknife** | Cancels the knife round and the restart round. | !cancelknife, !cancelroundknife, !ck, !crk |
**sm_warmup** | Force warmup for everyone. ***(Must be used after !forceend)*** | !warmup, !aquecimento |

All admins commands are in the `!admin` menu in the **WarMod Commands** category.

## Changelog
### 1.2.2
- Corrigido traduções Português-BR;
- Corrigido alguns logos de times não aparacer no score;

### 1.2.1
- Fixed team logos not appearing in the score;

### 1.2
- Added support for team logos in `.svg`;
- Updated **Logos & Names** of teams;
- Updated cvars generated in `gamemode_competitive_server.cfg`;
- Fixed errors in translations;

To view all changes go to [Changelog](https://github.com/zkservidores-clientes/WarMod-BFG-ZK-Servidores/blob/master/CHANGELOG.md)

## Credits
- [Versalite [BFG]](https://forums.alliedmods.net/showthread.php?t=225474) - Fork of the orignal plugin;
- [crashzk](https://github.com/crashzk) - Support for the latest SourceMod and other minor fixes;
