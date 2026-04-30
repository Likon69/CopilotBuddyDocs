# AvoidanceManager Class

Manages dynamic avoidance of hostile mobs by creating temporary blackspots. Mobs can be added to avoid by Entry ID, and the system will automatically create and update blackspots as mobs move.

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class AvoidanceManager
```

The AvoidanceManager type exposes the following members.

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Add(uint)](AvoidanceManager/Methods/Add_8AA9FDB29156.md) | Adds a mob entry ID to the avoidance list. |
| Public method Static member | [AddAll(IEnumerable<uint>)](AvoidanceManager/Methods/AddAll_4294A16C1FDD.md) | Adds multiple mob entry IDs to the avoidance list. |
| Public method Static member | [Clear](AvoidanceManager/Methods/Clear_3D83B94E616C.md) | Clears all avoidance data. |
| Public method Static member | [IsAvoiding(uint)](AvoidanceManager/Methods/IsAvoiding_D295FBC91598.md) | Checks if a mob entry ID is being avoided. |
| Public method Static member | [Pulse](AvoidanceManager/Methods/Pulse_7C3E5033A6E2.md) | Updates avoidance blackspots based on current mob positions. Should be called periodically (e.g., in the bot's pulse). |
| Public method Static member | [Remove(uint)](AvoidanceManager/Methods/Remove_44C96954F146.md) | Removes a mob entry ID from the avoidance list. |
| Public method Static member | [RemoveAll(IEnumerable<uint>)](AvoidanceManager/Methods/RemoveAll_BC3090BC028D.md) | Removes multiple mob entry IDs from the avoidance list. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
