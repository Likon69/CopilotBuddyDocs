# WeightSet Class

Represents a set of stat weights for item evaluation.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Inventory.WeightSet

## Namespace
[Styx.Logic.Inventory](../../../../namespaces/Styx/Logic/Inventory.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WeightSet
```

The WeightSet type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WeightSet(string, Dictionary<Stat, float>)](WeightSet/Constructors/Constructor_2BEE24DA3259.md) | Creates a new weight set. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Name](WeightSet/Properties/Name_5CD4C2AFAA86.md) | Gets the name of this weight set. |
| Public property | [Weights](WeightSet/Properties/Weights_A81E90FA7945.md) | Gets the stat weights. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [EvaluateItem(WoWItem)](WeightSet/Methods/EvaluateItem_ADE3BCB379CA.md) | Evaluates an item's score based on this weight set. |
| Public method | [EvaluateItem(ItemInfo)](WeightSet/Methods/EvaluateItem_F6226FD79277.md) | Evaluates an item's score from ItemInfo. |
| Public method | [GetStatScore(Stat, float)](WeightSet/Methods/GetStatScore_E5F77045A1F6.md) | Gets the score for a stat with given points. |
| Public method | [GetStatScore(string, float)](WeightSet/Methods/GetStatScore_A8FF38F9D384.md) | Gets the score for a stat by name. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory Namespace](../../../../namespaces/Styx/Logic/Inventory.md)
