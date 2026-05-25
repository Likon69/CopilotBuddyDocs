# WorldObstacleManager Class

Provides world obstacle management functionality.

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class WorldObstacleManager
```

The WorldObstacleManager type exposes the following members.

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Initialize](WorldObstacleManager/Methods/Initialize_1FE9741BE774.md) | Registers common world obstacle types and wires Navigator callbacks. Safe to call multiple times — re-registers cleanly on each bot start. HB 6.2.3: AvoidanceNavigationProvider is set as NavigationProvider in DungeonBuddy.Start(). Here we use Navigator delegate injection (no NavigationProvider subclass needed). |
| Public method Static member | [Shutdown](WorldObstacleManager/Methods/Shutdown_C0738C8A7EFD.md) | Clears all registrations and unwires Navigator callbacks. Call from the bot's Stop() method. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy.Avoidance Namespace](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
