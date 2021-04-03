**CreatureDifficultyFlags**
| Flag       | Flag       | Name                                                       | Original Description                      | Comment |
| :---       | :----      | :----                                                      | :----                                     | :---- |
| 1          | 0x00000001 | CREATURE_DIFFICULTYFLAGS_MOUNTABLE                         | Mountable                                 |  |
| 2          | 0x00000002 | CREATURE_DIFFICULTYFLAGS_NO_XP                             | No XP                                     | CREATURE_FLAG_EXTRA_NO_XP |
| 4          | 0x00000004 | CREATURE_DIFFICULTYFLAGS_NO_LOOT                           | No Loot                                   |  |
| 8          | 0x00000008 | CREATURE_DIFFICULTYFLAGS_UNKILLABLE                        | Unkillable                                |  |
| 16         | 0x00000010 | CREATURE_DIFFICULTYFLAGS_TAMEABLE                          | Tameable                                  | CREATURE_TYPE_FLAG_TAMEABLE |
| 32         | 0x00000020 | CREATURE_DIFFICULTYFLAGS_IMMUNE_TO_PC                      | ImmunePC                                  | UNIT_FLAG_IMMUNE_TO_PC |
| 64         | 0x00000040 | CREATURE_DIFFICULTYFLAGS_IMMUNE_TO_NPC                     | ImmuneNPC                                 | UNIT_FLAG_IMMUNE_TO_NPC |
| 128        | 0x00000080 | CREATURE_DIFFICULTYFLAGS_CAN_WIELD_LOOT                    | CanWieldLoot                              |  |
| 256        | 0x00000100 | CREATURE_DIFFICULTYFLAGS_SESSILE                           | Sessile                                   | Creature is rooted |
| 512        | 0x00000200 | CREATURE_DIFFICULTYFLAGS_NOT_SELECTABLE                    | Uninteractible                            | UNIT_FLAG_NOT_SELECTABLE |
| 1024       | 0x00000400 | CREATURE_DIFFICULTYFLAGS_NO_AUTOMATIC_REGEN                | No Automatic Regen                        | Creature does not regenerate mana or health. Creatures with that flag uses no UNIT_FLAG2_REGENERATE_POWER |
| 2048       | 0x00000800 | CREATURE_DIFFICULTYFLAGS_NO_CORPSE_UPON_DEATH              | Despawn Instantly                         | Creature instantly disappear when killed |
| 4096       | 0x00001000 | CREATURE_DIFFICULTYFLAGS_CORPSE_RAID                       | CorpseRaid                                |  |
| 8192       | 0x00002000 | CREATURE_DIFFICULTYFLAGS_CREATOR_LOOT                      | Creator Loot                              | Lootable only by creator(engineering dummies) |
| 16384      | 0x00004000 | CREATURE_DIFFICULTYFLAGS_NO_DEFENSE                        | No Defense                                |  |
| 32768      | 0x00008000 | CREATURE_DIFFICULTYFLAGS_NO_SPELL_DEFENSE                  | No Spell Defense                          |  |
| 65536      | 0x00010000 | CREATURE_DIFFICULTYFLAGS_BOSS                              | Raid Boss Mob                             | CREATURE_TYPE_FLAG_BOSS_MOB |
| 131072     | 0x00020000 | CREATURE_DIFFICULTYFLAGS_COMBAT_PING                       | Combat Ping                               |  |
| 262144     | 0x00040000 | CREATURE_DIFFICULTYFLAGS_WATER_BOUND                       | Aquatic (aka Water Only)                  |  |
| 524288     | 0x00080000 | CREATURE_DIFFICULTYFLAGS_CAN_PENETRATE_WATER               | Amphibious                                |  |
| 1048576    | 0x00100000 | CREATURE_DIFFICULTYFLAGS_NO_MELEE                          | No Melee (Flee)                           |  |
| 2097152    | 0x00200000 | CREATURE_DIFFICULTYFLAGS_VISIBLE_TO_GHOSTS                 | Visible to Ghosts                         | CREATURE_TYPE_FLAG_VISIBLE_TO_GHOSTS |
| 4194304    | 0x00400000 | CREATURE_DIFFICULTYFLAGS_PVP_ENABLING                      | PvP Enabling                              |  |
| 8388608    | 0x00800000 | CREATURE_DIFFICULTYFLAGS_DO_NOT_PLAY_WOUND_PARRY_ANIMATION | Do Not Play Wound Anim                    | CREATURE_TYPE_FLAG_DO_NOT_PLAY_WOUND_PARRY_ANIMATION |
| 16777216   | 0x01000000 | CREATURE_DIFFICULTYFLAGS_NO_FACTION_TOOLTIP                | No Faction Tooltip                        | CREATURE_TYPE_FLAG_NO_FACTION_TOOLTIP |
| 33554432   | 0x02000000 | CREATURE_DIFFICULTYFLAGS_IGNORE_COMBAT                     | Ignore Combat                             | CREATURE_FLAG_EXTRA_IGNORE_COMBAT, actually only changes react state to passive. Currently handled differently and indeed disallows combat |
| 67108864   | 0x04000000 | CREATURE_DIFFICULTYFLAGS_ONLY_ATTACK_PVP_ENABLING          | Only attack targets that are PvP enabling |  |
| 134217728  | 0x08000000 | CREATURE_DIFFICULTYFLAGS_SUMMON_GUARD_IF_IN_AGGRO_RANGE    | Calls Guards                              | Creature will summon a guard if player is within its aggro range (even if creature doesn't attack per se) |
| 268435456  | 0x10000000 | CREATURE_DIFFICULTYFLAGS_ONLY_SWIM                         | Can Swim                                  | UNIT_FLAG_SWIMMING |
| 536870912  | 0x20000000 | CREATURE_DIFFICULTYFLAGS_FLOATING                          | Floating <Don't Use>                      | Disables gravity |
| 1073741824 | 0x40000000 | CREATURE_DIFFICULTYFLAGS_MORE_AUDIBLE                      | More Audible: Caution, Expensive          | CREATURE_TYPE_FLAG_MORE_AUDIBLE |
| 2147483648 | 0x80000000 | CREATURE_DIFFICULTYFLAGS_LARGE_AOI                         | Large (AOI): Caution, Expensive           | UnitFlags2 0x200000 |
