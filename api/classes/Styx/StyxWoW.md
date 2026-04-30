# StyxWoW Class

Represents a styx wow.

## Namespace
[Styx](../../namespaces/Styx.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class StyxWoW
```

The StyxWoW type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [StyxWoW.Offsets](StyxWoW/Offsets.md) | Offsets class - mimics HB 4.3.4 Class493 for compatibility |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [AreaManager](StyxWoW/Properties/AreaManager_ABF1E721636E.md) | Gets the area manager. |
| Public property Static member | [Cache](StyxWoW/Properties/Cache_1EFD522F9424.md) | Gets the cache. |
| Public property Static member | [Camera](StyxWoW/Properties/Camera_658E79B95842.md) | FEAT-44: Provides access to the WoW camera. |
| Public property Static member | [Db](StyxWoW/Properties/Db_E1875583B1FE.md) | Gets the db. |
| Public property Static member | [GameGraphicsApi](StyxWoW/Properties/GameGraphicsApi_28CC8AE4F752.md) | Gets the graphics API currently in use by WoW. Uses GetCVar('gxAPI') — valid in WotLK 3.3.5a. |
| Public property Static member | [GameState](StyxWoW/Properties/GameState_CC825FFD129C.md) | FEAT-07: Gets the current game state from memory. WotLK 3.3.5a offset: 0x00B6A9E0 |
| Public property Static member | [GameVersion](StyxWoW/Properties/GameVersion_7566177EA1F6.md) | Gets the game version. |
| Public property Static member | [GlobalCooldown](StyxWoW/Properties/GlobalCooldown_2E096D8ACA99.md) | Gets a value indicating whether global cooldown. |
| Public property Static member | [GlueState](StyxWoW/Properties/GlueState_2AD4DD3FBA28.md) | FEAT-19: Gets the current glue (login) screen state. Returns GlueScreen.Unknown when in-game. |
| Public property Static member | [IsInGame](StyxWoW/Properties/IsInGame_FC702F5064EA.md) | Gets a value indicating whether is in game. |
| Public property Static member | [IsInWorld](StyxWoW/Properties/IsInWorld_78818C4D0B7B.md) | Gets a value indicating whether is in world. |
| Public property Static member | [Landmarks](StyxWoW/Properties/Landmarks_9B7B5E260A94.md) | Provides access to battleground/world landmarks. |
| Public property Static member | [LastHardwareAction](StyxWoW/Properties/LastHardwareAction_1DDF274B00F8.md) | Gets the last hardware action. |
| Public property Static member | [Me](StyxWoW/Properties/Me_EE9BC2D4A41A.md) | Gets the me. |
| Public property Static member | [Memory](StyxWoW/Properties/Memory_1D41EEAC2203.md) | Exposes the memory manager for convenience. Mirrors HB's StyxWoW.Memory property and simply proxies to the underlying ObjectManager.Wow instance. |
| Public property Static member | [Random](StyxWoW/Properties/Random_1DA7835B4484.md) | HB 6.2.3: Thread-safe Random instance for humanization. |
| Public property Static member | [StatusText](StyxWoW/Properties/StatusText_BF35138ED963.md) | Gets or sets the status text. |
| Public property Static member | [WoWClient](StyxWoW/Properties/WoWClient_54C36ED29CA7.md) | Gets the wow client. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Reset](StyxWoW/Methods/Reset_5549EDAC08D3.md) | Resets the current state. |
| Public method Static member | [ResetAfk](StyxWoW/Methods/ResetAfk_80487E33948C.md) | Resets the afk. |
| Public method Static member | [Sleep(int)](StyxWoW/Methods/Sleep_650EC5536F18.md) | HB 5.4.8 StyxWoW.Sleep — if called on the bot thread while a FrameLock is active, releases the frame lock before sleeping so WoW can render, then reacquires it on return. |
| Public method Static member | [Sleep(TimeSpan)](StyxWoW/Methods/Sleep_0481974C76A0.md) | HB 5.4.8 StyxWoW.Sleep(TimeSpan) — releases FrameLock during sleep. |
| Public method Static member | [SleepForLagDuration](StyxWoW/Methods/SleepForLagDuration_6E33E844B99A.md) | Sleeps for the current lag-adjusted duration. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx Namespace](../../namespaces/Styx.md)
