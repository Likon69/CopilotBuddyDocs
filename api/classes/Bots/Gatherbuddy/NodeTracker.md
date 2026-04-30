# NodeTracker Class

Manages tracking of harvested and blacklisted nodes. Prevents returning to already-harvested nodes before respawn. FEAT-40: Added persistent blacklist save/load.

## Namespace
[Bots.Gatherbuddy](../../../namespaces/Bots/Gatherbuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class NodeTracker
```

The NodeTracker type exposes the following members.

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Blacklist(WoWGameObject)](NodeTracker/Methods/Blacklist_806F3D3E4E47.md) | Blacklists a node using the default settings timer |
| Public method Static member | [Blacklist(WoWGameObject, TimeSpan)](NodeTracker/Methods/Blacklist_96565C6E2E76.md) | Blacklists a node for a given duration (failed harvest, ninja, etc.) |
| Public method Static member | [BlacklistPermanent(WoWGameObject)](NodeTracker/Methods/BlacklistPermanent_CC6503A3A3A8.md) | Permanently blacklists a node position (persisted across sessions). |
| Public method Static member | [CleanupExpired](NodeTracker/Methods/CleanupExpired_3A8C46C23F08.md) | Cleans up expired entries (call periodically) |
| Public method Static member | [IsNodeValid(WoWGameObject)](NodeTracker/Methods/IsNodeValid_DD457E7A19D1.md) | Checks if a node is valid for harvesting |
| Public method Static member | [LoadBlacklist](NodeTracker/Methods/LoadBlacklist_05DC6960A308.md) | FEAT-40: Loads the persistent blacklist from disk. |
| Public method Static member | [MarkHarvested(WoWGameObject)](NodeTracker/Methods/MarkHarvested_82232EAA90D3.md) | Marks a node as harvested (avoid returning before respawn) |
| Public method Static member | [Reset](NodeTracker/Methods/Reset_CD5D6D1B0DED.md) | Resets the current state. |
| Public method Static member | [SaveBlacklist](NodeTracker/Methods/SaveBlacklist_A9882ECFAD30.md) | FEAT-40: Saves the persistent blacklist to disk. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Gatherbuddy Namespace](../../../namespaces/Bots/Gatherbuddy.md)
