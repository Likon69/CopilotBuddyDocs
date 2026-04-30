# Styx Namespace

Contains the core bot engine types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [BotBase](../classes/Styx/BotBase.md) | Represents a bot base. |
| Public class | [BotEvents](../classes/Styx/BotEvents.md) | Represents a bot events. |
| Public class | [BotEvents.Battleground](../classes/Styx/BotEvents/Battleground.md) | Represents a battleground. |
| Public class | [BotEvents.Battleground.SotA](../classes/Styx/BotEvents/Battleground/SotA.md) | Represents a sot a. |
| Public class | [BotEvents.BotChangedEventArgs](../classes/Styx/BotEvents/BotChangedEventArgs.md) | Represents a bot changed event args. |
| Public class | [BotEvents.Player](../classes/Styx/BotEvents/Player.md) | Represents a player. |
| Public class | [BotEvents.Player.LevelUpEventArgs](../classes/Styx/BotEvents/Player/LevelUpEventArgs.md) | Represents a level up event args. |
| Public class | [BotEvents.Player.MapChangedEventArgs](../classes/Styx/BotEvents/Player/MapChangedEventArgs.md) | Represents a map changed event args. |
| Public class | [BotEvents.Player.MobKilledEventArgs](../classes/Styx/BotEvents/Player/MobKilledEventArgs.md) | Represents a mob killed event args. |
| Public class | [BotEvents.Player.MobLootedEventArgs](../classes/Styx/BotEvents/Player/MobLootedEventArgs.md) | Represents a mob looted event args. |
| Public class | [BotEvents.Profile](../classes/Styx/BotEvents/Profile.md) | Represents a profile profile. |
| Public class | [BotEvents.Profile.NewProfileLoadedEventArgs](../classes/Styx/BotEvents/Profile/NewProfileLoadedEventArgs.md) | Represents a new profile loaded event args. |
| Public class | [BotEvents.Questing](../classes/Styx/BotEvents/Questing.md) | Represents a questing. |
| Public class | [BotManager](../classes/Styx/BotManager.md) | Manages bot loading, compilation, and selection. |
| Public class | [CantCompileException](../classes/Styx/CantCompileException.md) | Represents a cant compile exception. |
| Public class | [FrameLock](../classes/Styx/FrameLock.md) | Acquires continuous execution mode on the EndScene executor for the duration of its lifetime. While held, every call reuses the same hooked frame instead of waiting for a new one. Ported from HB 5.4.8/6.2.3 GreyMagic.FrameLock design: - Per-instance tracking via _wasAcquired (no static counter) - Exception-safe - Full IDisposable pattern with finalizer safety - _disposed guard prevents double-dispose Keeps a parameterless constructor (all call sites use new FrameLock()) and resolves the executor via . |
| Public class | [Global](../classes/Styx/Global.md) | Represents a global. |
| Public class | [Guard](../classes/Styx/Guard.md) | Represents a guard. |
| Public class | [HonorbuddyUnableToStartException](../classes/Styx/HonorbuddyUnableToStartException.md) | Represents a honorbuddy unable to start exception. |
| Public class | [InstanceNotFoundException](../classes/Styx/InstanceNotFoundException.md) | Exception thrown when an LFG dungeon instance cannot be found for a given mapId. HB 4.3.4: thrown by GetLfgDungeonIdFromMapId when no matching entry exists in LfgDungeons.dbc. |
| Public class | [InvalidExecutorException](../classes/Styx/InvalidExecutorException.md) | Represents an invalid executor exception. |
| Public class | [InvalidObjectPointerException](../classes/Styx/InvalidObjectPointerException.md) | Represents an invalid object pointer exception. |
| Public class | [InvalidProcessException](../classes/Styx/InvalidProcessException.md) | Thrown when the selected WoW process cannot be attached to. Ported from HB 4.3.4 InvalidProcessException. |
| Public class | [PulseFlagsExtensions](../classes/Styx/PulseFlagsExtensions.md) | Helpers for working with that mirror the convenience methods used throughout Honorbuddy. |
| Public class | [StyxWoW](../classes/Styx/StyxWoW.md) | Represents a styx wow. |
| Public class | [StyxWoW.Offsets](../classes/Styx/StyxWoW/Offsets.md) | Offsets class - mimics HB 4.3.4 Class493 for compatibility |
| Public class | [UserException](../classes/Styx/UserException.md) | Represents a user exception. |
| Public class | [WoWPulsator](../classes/Styx/WoWPulsator.md) | Represents a wow pulsator. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [BagType](../classes/Styx/BagType.md) | FEAT-16: Bag/container type classification. WotLK 3.3.5a bag subfamilies from ItemSubClass for Container class. |
| Public enumeration | [DifficultyColor](../classes/Styx/DifficultyColor.md) | Color-coded difficulty values for a unit relative to the player. |
| Public enumeration | [EmoteState](../classes/Styx/EmoteState.md) | Represents values for Emote State. |
| Public enumeration | [FactionId](../classes/Styx/FactionId.md) | IDs de factions pour WoW 3.3.5a build 12340. Utilisé pour identifier les factions dans le jeu. |
| Public enumeration | [GameError](../classes/Styx/GameError.md) | Represents values for Game Error. |
| Public enumeration | [GameObjectDataSlot](../classes/Styx/GameObjectDataSlot.md) | Represents values for Game Object Data Slot. |
| Public enumeration | [GameState](../classes/Styx/GameState.md) | Game state enumeration — matches HB 4.3.4 values. Read from memory at 0x00B6A9E0 (WotLK 3.3.5a). Note: ChangingFactionOrRace exists in WotLK (Faction Change 3.2.0, Race Change 3.3.3). ScanDllScanning is the Warden anti-cheat scan state. |
| Public enumeration | [GlueScreen](../classes/Styx/GlueScreen.md) | FEAT-16: Login/character selection screen states. Ported from HB 4.3.4 — values match WotLK 3.3.5a client. |
| Public enumeration | [GraphicsApi](../classes/Styx/GraphicsApi.md) | Represents values for Graphics Api. |
| Public enumeration | [InventoryType](../classes/Styx/InventoryType.md) | Represents values for Inventory Type. |
| Public enumeration | [MirrorTimerType](../classes/Styx/MirrorTimerType.md) | Represents values for Mirror Timer Type. |
| Public enumeration | [NpcFlags](../classes/Styx/NpcFlags.md) | NPC flags for WoW 3.3.5a (Build 12340). Read from UNIT_NPC_FLAGS descriptor. |
| Public enumeration | [PulseFlags](../classes/Styx/PulseFlags.md) | Represents flag values for Pulse Flags. |
| Public enumeration | [PvPState](../classes/Styx/PvPState.md) | Represents values for Pv P State. |
| Public enumeration | [QuestGiverStatus](../classes/Styx/QuestGiverStatus.md) | Quest giver status for NPCs showing quest availability. Values match WoW 3.3.5a client. |
| Public enumeration | [ShapeshiftForm](../classes/Styx/ShapeshiftForm.md) | Represents values for Shapeshift Form. |
| Public enumeration | [SheathType](../classes/Styx/SheathType.md) | Represents values for Sheath Type. |
| Public enumeration | [SkillLine](../classes/Styx/SkillLine.md) | Represents values for Skill Line. |
| Public enumeration | [SotAGateType](../classes/Styx/SotAGateType.md) | Represents values for Sot A Gate Type. |
| Public enumeration | [SotAObjective](../classes/Styx/SotAObjective.md) | Represents values for Sot A Objective. |
| Public enumeration | [SpellAttributes](../classes/Styx/SpellAttributes.md) | Represents values for Spell Attributes. |
| Public enumeration | [SpellAttributesEx](../classes/Styx/SpellAttributesEx.md) | Represents values for Spell Attributes Ex. |
| Public enumeration | [SpellAttributesEx2](../classes/Styx/SpellAttributesEx2.md) | Represents values for Spell Attributes Ex2. |
| Public enumeration | [SpellAttributesEx3](../classes/Styx/SpellAttributesEx3.md) | Represents values for Spell Attributes Ex3. |
| Public enumeration | [SpellAttributesEx4](../classes/Styx/SpellAttributesEx4.md) | Represents values for Spell Attributes Ex4. |
| Public enumeration | [SpellAttributesEx5](../classes/Styx/SpellAttributesEx5.md) | Represents values for Spell Attributes Ex5. |
| Public enumeration | [SpellAttributesEx6](../classes/Styx/SpellAttributesEx6.md) | Represents values for Spell Attributes Ex6. |
| Public enumeration | [SpellAttributesEx7](../classes/Styx/SpellAttributesEx7.md) | Represents values for Spell Attributes Ex7. |
| Public enumeration | [SpellAttributesEx8](../classes/Styx/SpellAttributesEx8.md) | Represents values for Spell Attributes Ex8. |
| Public enumeration | [StatTypes](../classes/Styx/StatTypes.md) | Represents values for Stat Types. |
| Public enumeration | [ThreatStatus](../classes/Styx/ThreatStatus.md) | Represents values for Threat Status. |
| Public enumeration | [UnitDynamicFlags](../classes/Styx/UnitDynamicFlags.md) | Unit dynamic flags for WoW 3.3.5a (Build 12340). Read from UNIT_DYNAMIC_FLAGS descriptor. |
| Public enumeration | [UnitFlags](../classes/Styx/UnitFlags.md) | Unit flags for WoW 3.3.5a (Build 12340). Read from UNIT_FIELD_FLAGS descriptor. |
| Public enumeration | [UnitFlags2](../classes/Styx/UnitFlags2.md) | Unit flags 2 for WoW 3.3.5a (Build 12340). Read from UNIT_FIELD_FLAGS_2 descriptor. |
| Public enumeration | [UnitNPCFlags](../classes/Styx/UnitNPCFlags.md) | Represents flag values for Unit NPC Flags. |
| Public enumeration | [WoWBagSlot](../classes/Styx/WoWBagSlot.md) | Represents values for WoW Bag Slot. |
| Public enumeration | [WoWCreatureSkinType](../classes/Styx/WoWCreatureSkinType.md) | Represents values for WoW Creature Skin Type. |
| Public enumeration | [WoWCreatureType](../classes/Styx/WoWCreatureType.md) | Represents values for WoW Creature Type. |
| Public enumeration | [WoWCursorType](../classes/Styx/WoWCursorType.md) | Represents values for WoW Cursor Type. |
| Public enumeration | [WoWEquipSlot](../classes/Styx/WoWEquipSlot.md) | Represents values for WoW Equip Slot. |
| Public enumeration | [WoWGameObjectType](../classes/Styx/WoWGameObjectType.md) | HB 4.3.4 WoWGameObjectType enum - exact copy from Styx namespace |
| Public enumeration | [WoWGender](../classes/Styx/WoWGender.md) | Represents values for WoW Gender. |
| Public enumeration | [WoWInteractType](../classes/Styx/WoWInteractType.md) | Represents values for WoW Interact Type. |
| Public enumeration | [WoWInventorySlot](../classes/Styx/WoWInventorySlot.md) | Represents values for WoW Inventory Slot. |
| Public enumeration | [WoWItemAmmoType](../classes/Styx/WoWItemAmmoType.md) | Represents values for WoW Item Ammo Type. |
| Public enumeration | [WoWItemArmorClass](../classes/Styx/WoWItemArmorClass.md) | Represents values for WoW Item Armor Class. |
| Public enumeration | [WoWItemBagFamily](../classes/Styx/WoWItemBagFamily.md) | Represents values for WoW Item Bag Family. |
| Public enumeration | [WoWItemBondType](../classes/Styx/WoWItemBondType.md) | Represents values for WoW Item Bond Type. |
| Public enumeration | [WoWItemClass](../classes/Styx/WoWItemClass.md) | Represents values for WoW Item Class. |
| Public enumeration | [WoWItemContainerClass](../classes/Styx/WoWItemContainerClass.md) | Represents values for WoW Item Container Class. |
| Public enumeration | [WoWItemGemClass](../classes/Styx/WoWItemGemClass.md) | Represents values for WoW Item Gem Class. |
| Public enumeration | [WoWItemGlyphClass](../classes/Styx/WoWItemGlyphClass.md) | Represents values for WoW Item Glyph Class. |
| Public enumeration | [WoWItemKeyClass](../classes/Styx/WoWItemKeyClass.md) | Represents values for WoW Item Key Class. |
| Public enumeration | [WoWItemMiscClass](../classes/Styx/WoWItemMiscClass.md) | Represents values for WoW Item Misc Class. |
| Public enumeration | [WoWItemProjectileClass](../classes/Styx/WoWItemProjectileClass.md) | Represents values for WoW Item Projectile Class. |
| Public enumeration | [WoWItemQuality](../classes/Styx/WoWItemQuality.md) | Represents values for WoW Item Quality. |
| Public enumeration | [WoWItemQuiverClass](../classes/Styx/WoWItemQuiverClass.md) | Represents values for WoW Item Quiver Class. |
| Public enumeration | [WoWItemRecipeClass](../classes/Styx/WoWItemRecipeClass.md) | Represents values for WoW Item Recipe Class. |
| Public enumeration | [WoWItemStatType](../classes/Styx/WoWItemStatType.md) | Represents values for WoW Item Stat Type. |
| Public enumeration | [WoWItemTradeGoodsClass](../classes/Styx/WoWItemTradeGoodsClass.md) | Represents values for WoW Item Trade Goods Class. |
| Public enumeration | [WoWItemWeaponClass](../classes/Styx/WoWItemWeaponClass.md) | Represents values for WoW Item Weapon Class. |
| Public enumeration | [WoWObjectType](../classes/Styx/WoWObjectType.md) | Represents values for WoW Object Type. |
| Public enumeration | [WoWObjectTypeFlag](../classes/Styx/WoWObjectTypeFlag.md) | Represents values for WoW Object Type Flag. |
| Public enumeration | [WoWPowerType](../classes/Styx/WoWPowerType.md) | Represents values for WoW Power Type. |
| Public enumeration | [WoWQuestType](../classes/Styx/WoWQuestType.md) | Represents values for WoW Quest Type. |
| Public enumeration | [WoWRace](../classes/Styx/WoWRace.md) | WoW Race IDs for WotLK 3.3.5a (build 12340) Note: Goblin (9) and Worgen (22) are Cataclysm races - not available in WotLK |
| Public enumeration | [WoWSocketColor](../classes/Styx/WoWSocketColor.md) | Represents values for WoW Socket Color. |
| Public enumeration | [WoWSpec](../classes/Styx/WoWSpec.md) | WotLK specialization IDs. In 3.3.5a these IDs map to the spec system introduced in Cata — present here for API compatibility with custom classes. Use SpecType for role-based detection (Tank/Healer/DPS) instead. |
| Public enumeration | [WoWStateFlag](../classes/Styx/WoWStateFlag.md) | Represents values for WoW State Flag. |
| Public enumeration | [WoWUnitClassificationType](../classes/Styx/WoWUnitClassificationType.md) | Represents values for WoW Unit Classification Type. |
| Public enumeration | [WoWUnitReaction](../classes/Styx/WoWUnitReaction.md) | Represents values for WoW Unit Reaction. |

## Delegates

| | Name | Description |
| --- | --- | --- |
| Public delegate | [BotEvents.Battleground.BattlegroundEnterDelegate](../classes/Styx/BotEvents/Battleground/BattlegroundEnterDelegate.md) | Represents a delegate for battleground enter. |
| Public delegate | [BotEvents.Battleground.BattlegroundLeftDelegate](../classes/Styx/BotEvents/Battleground/BattlegroundLeftDelegate.md) | Represents a delegate for battleground left. |
| Public delegate | [BotEvents.Battleground.SotA.GateDestroyedDelegate](../classes/Styx/BotEvents/Battleground/SotA/GateDestroyedDelegate.md) | Represents a delegate for gate destroyed. |
| Public delegate | [BotEvents.Battleground.SotA.SwitchedSideDelegate](../classes/Styx/BotEvents/Battleground/SotA/SwitchedSideDelegate.md) | Represents a delegate for switched side. |
| Public delegate | [BotEvents.OnBotChangedDelegate](../classes/Styx/BotEvents/OnBotChangedDelegate.md) | Represents a delegate for on bot changed. |
| Public delegate | [BotEvents.OnBotStartDelegate](../classes/Styx/BotEvents/OnBotStartDelegate.md) | Represents a delegate for on bot start. |
| Public delegate | [BotEvents.OnBotStopDelegate](../classes/Styx/BotEvents/OnBotStopDelegate.md) | Represents a delegate for on bot stop. |
| Public delegate | [BotEvents.Player.LevelUpDelegate](../classes/Styx/BotEvents/Player/LevelUpDelegate.md) | Represents a delegate for level up. |
| Public delegate | [BotEvents.Player.MapChangedDelegate](../classes/Styx/BotEvents/Player/MapChangedDelegate.md) | Represents a delegate for map changed. |
| Public delegate | [BotEvents.Player.MobKilledDelegate](../classes/Styx/BotEvents/Player/MobKilledDelegate.md) | Represents a delegate for mob killed. |
| Public delegate | [BotEvents.Player.MobLootedDelegate](../classes/Styx/BotEvents/Player/MobLootedDelegate.md) | Represents a delegate for mob looted. |
| Public delegate | [BotEvents.Player.PlayerDiedDelegate](../classes/Styx/BotEvents/Player/PlayerDiedDelegate.md) | Represents a delegate for player died. |
| Public delegate | [BotEvents.Profile.NewProfileLoadedDelegate](../classes/Styx/BotEvents/Profile/NewProfileLoadedDelegate.md) | Represents a delegate for new profile loaded. |
| Public delegate | [BotEvents.Questing.QuestAcceptedDelegate](../classes/Styx/BotEvents/Questing/QuestAcceptedDelegate.md) | Represents a delegate for quest accepted. |

## See Also
[Namespace Index](../index.md)
