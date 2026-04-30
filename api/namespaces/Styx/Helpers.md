# Styx.Helpers Namespace

Contains helper and utility types used throughout the bot.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [ActivitySetter](../../classes/Styx/Helpers/ActivitySetter.md) | Represents an activity setter. |
| Public class | [AllocatedMemory](../../classes/Styx/Helpers/AllocatedMemory.md) | Manages allocated memory chunks in the WoW process. Port from HB 3.3.5a Styx.Helpers.AllocatedMemory |
| Public class | [Arguments](../../classes/Styx/Helpers/Arguments.md) | Represents an arguments. |
| Public class | [AssemblyFactory](../../classes/Styx/Helpers/AssemblyFactory.md) | Factory for compiling assemblies from source files. |
| Public class | [BGBotSettings](../../classes/Styx/Helpers/BGBotSettings.md) | Represents settings for bg bot. |
| Public class | [BinaryExtensions](../../classes/Styx/Helpers/BinaryExtensions.md) | Extension methods for BinaryReader and BinaryWriter to handle struct serialization. |
| Public class | [CachedValue<T>](../../classes/Styx/Helpers/CachedValue_1.md) | Represents a cached value. |
| Public class | [CapacityQueue<T>](../../classes/Styx/Helpers/CapacityQueue_1.md) | A queue with a fixed capacity that automatically dequeues old items when full. |
| Public class | [CharacterSettings](../../classes/Styx/Helpers/CharacterSettings.md) | Character-specific settings. Ported from HB 3.3.5a CharacterSettings.cs. Settings stored in: Settings/CharacterSettings_{Name}.xml Instance is created via Initialize() after game attachment. |
| Public class | [CircularQueue<T>](../../classes/Styx/Helpers/CircularQueue_1.md) | Represents a circular queue. |
| Public class | [ClassCollection<T>](../../classes/Styx/Helpers/ClassCollection_1.md) | A collection of dynamically loaded classes that compiles and instantiates types inheriting from T. Ported exactly from HB 3.3.5a. |
| Public class | [CombatAssistSettings](../../classes/Styx/Helpers/CombatAssistSettings.md) | Combat assist settings for RAF/party following. Path: Settings/CombatAssistSettings_{Name}.xml Pattern from HB 3.3.5a. |
| Public class | [CommandLine](../../classes/Styx/Helpers/CommandLine.md) | Provides access to command-line arguments passed to the process. Ported from HB 4.3.4 Styx.Helpers.CommandLine. HbUser/HbPass removed — no auth in CopilotBuddy. |
| Public class | [DefaultValueAttribute](../../classes/Styx/Helpers/DefaultValueAttribute.md) | Represents a default value attribute. |
| Public class | [DictionaryExtensions](../../classes/Styx/Helpers/DictionaryExtensions.md) | Extension methods for Dictionary collections. |
| Public class | [DualHashSet<T1, T2>](../../classes/Styx/Helpers/DualHashSet_2.md) | A collection that contains two HashSets of different types. Allows checking membership against either type. |
| Public class | [EncryptedAttribute](../../classes/Styx/Helpers/EncryptedAttribute.md) | Attribute for encrypting settings. Ported from HB 4.3.4 (RijndaelManaged → Aes for .NET 10). |
| Public class | [EnumTypeConverter](../../classes/Styx/Helpers/EnumTypeConverter.md) | Value converter to support enum display names and localization. Ported from HB 4.3.4. Deobfuscated: Class442→EnumCacheEntry, Class443→CultureCacheEntry, Class444→ResourceLocalizer, Delegate5→LocalizerDelegate. |
| Public class | [Extensions](../../classes/Styx/Helpers/Extensions.md) | Extension methods for HB 3.3.5a |
| Public class | [FieldDisplayNameAttribute](../../classes/Styx/Helpers/FieldDisplayNameAttribute.md) | Represents a field display name attribute. |
| Public class | [FlagCheckedListBox](../../classes/Styx/Helpers/FlagCheckedListBox.md) | Represents a flag checked list box. |
| Public class | [FlagCheckedListBoxItem](../../classes/Styx/Helpers/FlagCheckedListBoxItem.md) | Represents a flag checked list box item. |
| Public class | [FlagEnumUIEditor](../../classes/Styx/Helpers/FlagEnumUIEditor.md) | Represents a flag enum ui editor. |
| Public class | [GatherbuddyHelper](../../classes/Styx/Helpers/GatherbuddyHelper.md) | Helper used by GatherBuddy to list and load GatherBuddy profile files. This is based on Honorbuddy 4.3.4's GatherbuddyHelper, but adapted to CopilotBuddy's local profile storage (Profiles/GatherBuddy/). |
| Public class | [InactivityDetector](../../classes/Styx/Helpers/InactivityDetector.md) | Detects player inactivity and can trigger automatic logout. |
| Public class | [IndexedList<T>](../../classes/Styx/Helpers/IndexedList_1.md) | Represents an indexed list. |
| Public class | [InfoPanel](../../classes/Styx/Helpers/InfoPanel.md) | Represents an info panel. |
| Public class | [KeyHelpers](../../classes/Styx/Helpers/KeyHelpers.md) | Helper methods for sending keyboard input to windows. |
| Public class | [KeyboardManager](../../classes/Styx/Helpers/KeyboardManager.md) | Provides keyboard input functionality for the WoW client. |
| Public class | [LevelbotSettings](../../classes/Styx/Helpers/LevelbotSettings.md) | LevelbotSettings delegates all UI-visible settings to CharacterSettings. Path: Settings/LevelbotSettings_{Name}.xml Pattern from HB 3.3.5a. |
| Public class | [LogMessage](../../classes/Styx/Helpers/LogMessage.md) | Represents a single log message with level, color, timestamp and content. |
| Public class | [Logging](../../classes/Styx/Helpers/Logging.md) | Logging system compatible with Honorbuddy WoD style. |
| Public class | [PVPSettings](../../classes/Styx/Helpers/PVPSettings.md) | PVP/Battleground settings. Path: Settings/PVPSettings_{Name}.xml Pattern from HB 3.3.5a. |
| Public class | [PerFrameCachedValue<T>](../../classes/Styx/Helpers/PerFrameCachedValue_1.md) | Exact port of HB 5.4.8/6.2.3 PerFrameCachedValue. Caches a value per EndScene frame using Executor.FrameCount. Multiple accesses in the same frame return the cached value (0 RPM). |
| Public class | [PerformanceTimer](../../classes/Styx/Helpers/PerformanceTimer.md) | Simple performance timer for measuring execution time of code blocks. Use in a using statement or call Start()/StopAndPrint() manually. |
| Public class | [QuestSettings](../../classes/Styx/Helpers/QuestSettings.md) | Quest bot settings. Path: Settings/QuestSettings_{Name}.xml Pattern from HB 3.3.5a. |
| Public class | [RangedDictionary<T>](../../classes/Styx/Helpers/RangedDictionary_1.md) | Dictionary that organizes items by range. |
| Public class | [SettingAttribute](../../classes/Styx/Helpers/SettingAttribute.md) | Represents a setting attribute. |
| Public class | [Settings](../../classes/Styx/Helpers/Settings.md) | Base class for all settings. Ported from HB 3.3.5a Settings.cs. Per-character settings use flat path: Settings/FileName_{Name}.xml Supports migration from old paths via oldSettingsPath parameter. |
| Public class | [StyxSettings](../../classes/Styx/Helpers/StyxSettings.md) | Global bot settings (not per-character). Stored in Settings/StyxSettings.xml. Pattern from HB 5.4.8 GlobalSettings. |
| Public class | [TimeCachedValue<T>](../../classes/Styx/Helpers/TimeCachedValue_1.md) | Simple wrapper that caches the result of a producer delegate for a fixed amount of time. Ported directly from HonorBuddy 3.3.5a. |
| Public class | [UISettings](../../classes/Styx/Helpers/UISettings.md) | Settings for UI window positions and sizes. Global (not per-character) — stored in Settings/UISettings.xml. Pattern from HB 5.4.8. |
| Public class | [Utilities](../../classes/Styx/Helpers/Utilities.md) | General utility methods for HB 3.3.5a |
| Public class | [WaitTimer](../../classes/Styx/Helpers/WaitTimer.md) | Represents a wait timer. |
| Public class | [WaitTimer.WaitTimerEventArgs](../../classes/Styx/Helpers/WaitTimer/WaitTimerEventArgs.md) | Represents a wait timer event args. |
| Public class | [WoWMathHelper](../../classes/Styx/Helpers/WoWMathHelper.md) | Provides helper methods for wow math. |
| Public class | [WoWPlayerExtensions](../../classes/Styx/Helpers/WoWPlayerExtensions.md) | Extension methods pour WoWPlayer/LocalPlayer. Permet d'appeler IsTank(), IsDps(), IsHealer() comme méthodes (les scripts DungeonBuddy les appellent avec parenthèses). Compatible HB 4.3.4 qui avait ces méthodes. IMPORTANT: Ces méthodes utilisent UnitGroupRolesAssigned() pour détecter le rôle LFG ASSIGNÉ, pas la classe du joueur. Un Paladin Holy ne doit PAS retourner IsTank()=true. Les properties WoWPlayer.IsTank/IsHealer (class-based) restent disponibles pour savoir si la classe PEUT jouer ce rôle. Référence HB 4.3.4: ScriptHelpers.cs L1308-L1501 |
| Public class | [XmlExtensions](../../classes/Styx/Helpers/XmlExtensions.md) | Extension methods for XML processing. |
| Public class | [XmlUtils](../../classes/Styx/Helpers/XmlUtils.md) | Represents an xml utils. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [Range](../../classes/Styx/Helpers/Range.md) | Represents a range value. |
| Public struct | [ValuePair<T1, T2>](../../classes/Styx/Helpers/ValuePair_2.md) | A simple pair of two values of different types. |

## Interfaces

| | Name | Description |
| --- | --- | --- |
| Public interface | [IRangeAble](../../classes/Styx/Helpers/IRangeAble.md) | Defines the contract for I Range Able. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [KeyboardManager.ActionBar](../../classes/Styx/Helpers/KeyboardManager/ActionBar.md) | Action bar enumeration. |
| Public enumeration | [KeyboardManager.ActionButton](../../classes/Styx/Helpers/KeyboardManager/ActionButton.md) | Action button enumeration. |
| Public enumeration | [LogLevel](../../classes/Styx/Helpers/LogLevel.md) | Log levels matching Honorbuddy WoD. |
| Public enumeration | [LogType](../../classes/Styx/Helpers/LogType.md) | Log type for the logging system. Ported from HB 4.3.4. |
| Public enumeration | [PluginSourceEnum](../../classes/Styx/Helpers/PluginSourceEnum.md) | Source of plugins to load. |

## Delegates

| | Name | Description |
| --- | --- | --- |
| Public delegate | [CircularQueue.EndOfQueue](../../classes/Styx/Helpers/CircularQueue_1/EndOfQueue.md) | Represents a delegate for End Of Queue. |
| Public delegate | [CircularQueue.StartOfQueue](../../classes/Styx/Helpers/CircularQueue_1/StartOfQueue.md) | Represents a delegate for Start Of Queue. |
| Public delegate | [GameDebugAddStringDelegate](../../classes/Styx/Helpers/GameDebugAddStringDelegate.md) | Represents a delegate for game debug add string. |
| Public delegate | [InfoPanelUpdatedDelegate](../../classes/Styx/Helpers/InfoPanelUpdatedDelegate.md) | Represents a delegate for info panel updated. |
| Public delegate | [Logging.LogMessageDelegate](../../classes/Styx/Helpers/Logging/LogMessageDelegate.md) | Delegate for log message events. |
| Public delegate | [WaitTimer.WaitTimerFinishedHandler](../../classes/Styx/Helpers/WaitTimer/WaitTimerFinishedHandler.md) | Represents a delegate for Wait Timer Finished Handler. |

## See Also
[Namespace Index](../../index.md)
