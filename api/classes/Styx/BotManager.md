# BotManager Class

Manages bot loading, compilation, and selection.

## Inheritance Hierarchy
System.Object
  Styx.BotManager

## Namespace
[Styx](../../namespaces/Styx.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class BotManager
```

The BotManager type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [BotManager](BotManager/Constructors/Constructor_2F6C3BDE2248.md) | Initializes a new instance of the BotManager class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Bots](BotManager/Properties/Bots_CDBC352DB398.md) | Gets all loaded bots. |
| Public property Static member | [Current](BotManager/Properties/Current_4E95DF4CB505.md) | Gets the currently active bot. |
| Public property Static member | [Instance](BotManager/Properties/Instance_9D8C2257280E.md) | Singleton instance. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Add(BotBase)](BotManager/Methods/Add_9E70E86C8C71.md) | Adds a bot to the manager using its Name property. |
| Public method | [Add(string, BotBase)](BotManager/Methods/Add_AFDD01FC2B77.md) | Adds a bot to the manager. |
| Public method | [Clear](BotManager/Methods/Clear_4871EE200388.md) | Clears all bots. |
| Public method | [Contains(string)](BotManager/Methods/Contains_A4AD9C5785DC.md) | Checks if a bot exists. |
| Public method | [GetBotByName(string)](BotManager/Methods/GetBotByName_508C629D8BB4.md) | Gets a bot by name. |
| Public method | [GetBots](BotManager/Methods/GetBots_2E028AE51296.md) | Gets the internal bot dictionary. |
| Public method | [LoadBots(string)](BotManager/Methods/LoadBots_51087548835B.md) | Loads bots from a directory. Compiles .cs files and loads .dll assemblies. |
| Public method | [Remove(string)](BotManager/Methods/Remove_DCDE4739C03B.md) | Removes a bot by name. |
| Public method | [SetCurrent(BotBase)](BotManager/Methods/SetCurrent_228EA3DA2B47.md) | Sets the current active bot. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx Namespace](../../namespaces/Styx.md)
