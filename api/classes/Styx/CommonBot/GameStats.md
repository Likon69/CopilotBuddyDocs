# GameStats Class

Tracks game statistics like kills, deaths, XP/hour, etc. Provides data for the info panel in the UI.

## Namespace
[Styx.CommonBot](../../../namespaces/Styx/CommonBot.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class GameStats
```

The GameStats type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public delegate | [GameStats.InfoPanelUpdatedDelegate](GameStats/InfoPanelUpdatedDelegate.md) | Represents a delegate for info panel updated. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [BGsCompleted](GameStats/Properties/BGsCompleted_3A1EA6C78E2B.md) | Gets the b gs completed. |
| Public property Static member | [BGsLost](GameStats/Properties/BGsLost_667A267C1E17.md) | Gets the b gs lost. |
| Public property Static member | [BGsLostPerHour](GameStats/Properties/BGsLostPerHour_9EF1567595B8.md) | Gets the b gs lost per hour. |
| Public property Static member | [BGsPerHour](GameStats/Properties/BGsPerHour_89B5FA7F94F0.md) | Gets the b gs per hour. |
| Public property Static member | [BGsWon](GameStats/Properties/BGsWon_23779DA574A9.md) | Gets the b gs won. |
| Public property Static member | [BGsWonPerHour](GameStats/Properties/BGsWonPerHour_79F4A2D5A55C.md) | Gets the b gs won per hour. |
| Public property Static member | [Deaths](GameStats/Properties/Deaths_D713DBDA8CA7.md) | Gets the deaths. |
| Public property Static member | [DeathsPerHour](GameStats/Properties/DeathsPerHour_AE630A0D42B1.md) | Gets the deaths per hour. |
| Public property Static member | [HonorGained](GameStats/Properties/HonorGained_F48388764C6F.md) | Gets the honor gained. |
| Public property Static member | [HonorPerHour](GameStats/Properties/HonorPerHour_720A26AFB091.md) | Gets the honor per hour. |
| Public property Static member | [IsMeasuring](GameStats/Properties/IsMeasuring_850CACD55977.md) | Gets a value indicating whether is measuring. |
| Public property Static member | [Loots](GameStats/Properties/Loots_238CF642D822.md) | Gets the loots. |
| Public property Static member | [LootsPerHour](GameStats/Properties/LootsPerHour_0E6281A3C849.md) | Gets the loots per hour. |
| Public property Static member | [MobsKilled](GameStats/Properties/MobsKilled_EA0966E8F83E.md) | Gets the mobs killed. |
| Public property Static member | [MobsPerHour](GameStats/Properties/MobsPerHour_C63EE92E80EB.md) | Gets the mobs per hour. |
| Public property Static member | [TicksPerSecond](GameStats/Properties/TicksPerSecond_362977000BFF.md) | Gets the ticks per second. |
| Public property Static member | [TimeToLevel](GameStats/Properties/TimeToLevel_8F6FFF266A85.md) | Gets the time to level. |
| Public property Static member | [XPPerHour](GameStats/Properties/XPPerHour_3D2B0718AA04.md) | Gets the xp per hour. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnInfoPanelUpdated](GameStats/Events/OnInfoPanelUpdated_A5E665C70307.md) | Occurs when info panel updated. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [BGLost](GameStats/Methods/BGLost_7C7FF44A8A6A.md) | Records a battleground loss. |
| Public method Static member | [BGWon](GameStats/Methods/BGWon_BEE788025AAB.md) | Records a battleground win. |
| Public method Static member | [Died](GameStats/Methods/Died_19CC3D16912F.md) | Records a death. |
| Public method Static member | [KilledMob](GameStats/Methods/KilledMob_C3733EEEB4F5.md) | Records a mob kill. |
| Public method Static member | [LootedMob](GameStats/Methods/LootedMob_5109A2D11230.md) | Records a loot event. |
| Public method Static member | [Reset](GameStats/Methods/Reset_A86D9493DFDB.md) | Resets the current state. |
| Public method Static member | [StartMeasuring](GameStats/Methods/StartMeasuring_80461DFBE9F3.md) | Starts measuring statistics. |
| Public method Static member | [StopMeasuring](GameStats/Methods/StopMeasuring_94F82B4386B4.md) | Stops measuring statistics. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.CommonBot Namespace](../../../namespaces/Styx/CommonBot.md)
