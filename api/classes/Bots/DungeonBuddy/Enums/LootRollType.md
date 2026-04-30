# LootRollType Enumeration

Controls how the bot rolls on group loot (START_LOOT_ROLL event). Values match the WoW API's RollOnLoot(rollId, type) argument: 1 = Need, 2 = Greed, 3 = Pass.

## Namespace
[Bots.DungeonBuddy.Enums](../../../../namespaces/Bots/DungeonBuddy/Enums.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum LootRollType
```

The LootRollType type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [LootRollType](LootRollType/Constructors/Constructor_C8972EED9B42.md) | Initializes a new instance of the LootRollType enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Greed](LootRollType/Fields/Greed_46607A0ECF46.md) | Represents the greed value. |
| Public field | [Need](LootRollType/Fields/Need_09201EEFCA04.md) | Represents the need value. |
| Public field | [Pass](LootRollType/Fields/Pass_972B115BC060.md) | Represents the pass value. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | CompareTo(object) | Compares the current instance with another object. (Inherited from Enum.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().). (Inherited from Enum.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().). (Inherited from Enum.) |
| Public method | GetTypeCode | Gets the type code. (Inherited from Enum.) |
| Public method | HasFlag(Enum) | Determines whether has flag. (Inherited from Enum.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides ValueType.ToString().). (Inherited from Enum.) |
| Public method | ToString(string) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(string, IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy.Enums Namespace](../../../../namespaces/Bots/DungeonBuddy/Enums.md)
