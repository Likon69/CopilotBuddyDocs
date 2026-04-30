# Flightor Class

Flightor - Flying movement and pathfinding Ported from HB 4.3.4, adapted for WotLK with Trinity mmap support

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Flightor
```

The Flightor type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [Flightor.MountHelper](Flightor/MountHelper.md) | Flying mount helper - manages mounting/dismounting |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CanFly](Flightor/Properties/CanFly_FFA5CA8485A1.md) | True if the local player is currently able to fly. Ported from HB 6.2.3 Flightor.CanFly, adapted for WotLK (no WoD zone-map infrastructure). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Clear](Flightor/Methods/Clear_35670E77D869.md) | Clear all cached path and anti-stuck state (WoD Flightor.Clear port). Called when the bot stops, or when blackspots/areas change. |
| Public method Static member | [DoAntiStuck](Flightor/Methods/DoAntiStuck_042B098FD6CB.md) | Stateful 3-step anti-stuck maneuver (WoD port). Steps: JumpAscend → StrafeLeft → StrafeRight → Backwards → reset. Each call advances one step; state resets when the bot moves > 10m. |
| Public method Static member | [MoveTo(WoWPoint)](Flightor/Methods/MoveTo_ED3D7C4BAAED.md) | Move to destination using flying mount |
| Public method Static member | [MoveTo(WoWPoint, float)](Flightor/Methods/MoveTo_49821D88750D.md) | Move to destination with minimum height |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
