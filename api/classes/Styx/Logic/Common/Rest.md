# Rest Class

Handles resting (eating/drinking) functionality.

## Namespace
[Styx.Logic.Common](../../../../namespaces/Styx/Logic/Common.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Rest
```

The Rest type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [NoDrink](Rest/Properties/NoDrink_951DFB230A6A.md) | Gets whether the player has no drink available. |
| Public property Static member | [NoFood](Rest/Properties/NoFood_C1ED216450E4.md) | Gets whether the player has no food available. |
| Public property Static member | [RestPercentageHealth](Rest/Properties/RestPercentageHealth_027665E84D18.md) | Gets or sets the health percentage threshold for resting. |
| Public property Static member | [RestPercentageMana](Rest/Properties/RestPercentageMana_42B901F3B2C7.md) | Gets or sets the mana percentage threshold for resting. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [DrinkImmediate](Rest/Methods/DrinkImmediate_1489BE6D5951.md) | Immediately uses drink to restore mana without waiting. Used by Singular for quick drinking. |
| Public method Static member | [Feed](Rest/Methods/Feed_5E3D6B2F8B4C.md) | Makes the player eat and drink to restore health and mana. |
| Public method Static member | [FeedImmediate](Rest/Methods/FeedImmediate_B2DB0C780BD5.md) | Immediately uses food to restore health without waiting. Used by Singular for quick eating. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Common Namespace](../../../../namespaces/Styx/Logic/Common.md)
