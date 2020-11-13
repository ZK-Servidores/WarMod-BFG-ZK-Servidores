# WarMod [BFG] | ZK Servidores™
An automative service for CS:GO competition matches.

Modified from **[WarMod [BFG] v20.07.15.1214](https://bitbucket.org/warmod/warmod.bitbucket.org/src)**.

## Commands
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
**sm_cancelknife** | Cancels the knife round and the restart round. | !cancelknife, !ck |
**sm_warmup** | Force warmup for everyone. ***(Must be used after !forceend)*** | !warmup, !aquecimento |

All admins commands are in the `!admin` menu in the **WarMod Commands** category.

## Changelog
### 4.2.6 | Development;
- Updated cvars generated in `gamemode_competitive_server.cfg`;
- Updated cvars generated in the `cfg/warmod` folder;
- Fixed errors in translations;

## Credits
- [Versalite [BFG]](https://forums.alliedmods.net/member.php?u=171777) - Fork of the orignal plugin;
- [crashzk](https://github.com/crashzk) - Support for the latest SourceMod and other minor fixes;

static char g_teamName[][] = {	"3DMAX", 	"Astralis", 	"Astana Dragons", 	"Bravado Gaming", 	"BIG",	"Cloud9", 	"Counter Logic Gaming", 	"Clan Mystik", 	"Chaos Esports Club",	"compLexity Gaming", 	"Copenhagen Wolves", 	"dAT Team",		"Dexterity Team",	"Team Dignitas", 	"Epsilon eSports", 	"ENCE eSports",		"ESC Gaming", 	"FaZe Clan",	"Flipsid3 Tactics", 	"fnatic", 	"G2 Esports",	"g3nerationX",	"Gambit Esports",	"HellRaisers", 	"Immortals",	"INTZ eSports", 	"iBUYPOWER", 	"Team Wolf", 	"KaBuM.TD",		"Keyd Stars", 	"Team Liquid",	"London Conspiracy", 	"Luminosity Gaming", 	"Team LDLC.com", 	"TeamOne",	"LGB eSports", 	"mousesports", 	"MyXMG", 	"Natus Vincere", 	"Ninjas in Pyjamas", 	"Team EnVyUs", 	"PENTA Sports", 	"Planetkey Dynamics", 	"Reason Gaming", 	"SK Gaming", 	"Tempo Storm",	"Team SoloMid", 	"Titan", 	"Vox Eminor", 	"VeryGames", 	"Team Vitality",	"Virtus.Pro"};
static char g_teamTag[][] = {	"3DMAX", 	"Astralis", 	"Astana Dragons", 	"Bravado", 			"BIG",	"Cloud9", 	"CLG", 						"Clan Mystik", 	"Chaos",				"COL", 					"CPH Wolves", 			"dAT Team", 	"DeX",				"Dignitas", 		"Epsilon", 			"ENCE",				"ESC", 			"FAZE",			"Flipsid3", 			"fnatic", 	"G2 Esports",	"g3X",			"Gambit",			"HellRaisers", 	"Immortals", 	"INTZ",				"iBUYPOWER", 	"Team Wolf", 	"KaBuM.TD",		"Keyd Stars", 	"Liquid",		"Ldn-Con", 				"LG",					"Team LDLC", 		"One",		"LGB", 			"mousesports", 	"MyXMG", 	"Na`Vi", 			"NiP", 					"EnVyUs", 		"PENTA", 			"Planetkey", 			"Reason", 			"SK|", 			"TempoStorm",	"TSM", 				"Titan", 	"Vox Eminor", 	"VeryGames", 	"Vitality",			"Virtus.Pro"};
static char g_teamLogo[][] = {	"3dm", 		"astrl", 		"ad", 				"bravg", 			"big",	"c9", 		"clg", 						"cm", 			"Chaos",				"col", 					"cw", 					"dat", 			"dexte",			"dig", 				"eps", 				"ence",				"esc", 			"faze",			"flip", 				"fntc", 	"g2",			"g3ner",		"gambi",			"hlr", 			"immor", 		"intz",				"ibp", 			"indw", 		"kabum",		"keyd", 		"liqui",		"lc", 					"lumin",				"ldlc", 			"tone",		"lgb", 			"mss", 			"myxmg", 	"navi", 			"nip", 					"envy", 		"penta", 			"pkd", 					"rgg", 				"sk", 			"tmps",			"tsm", 				"tit", 		"ve", 			"vg", 			"vital,				"vp"};
