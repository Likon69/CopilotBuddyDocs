# WoWPrice Class

Represents a WoW currency amount in gold, silver, and copper. Provides arithmetic operations and formatting for prices.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Inventory.WoWPrice

## Namespace
[Styx.Logic.Inventory](../../../../namespaces/Styx/Logic/Inventory.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWPrice : IComparable<WoWPrice>, IEquatable<WoWPrice>
```

The WoWPrice type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWPrice(long)](WoWPrice/Constructors/Constructor_549C3E29D836.md) | Creates a new WoWPrice from a copper amount. |
| Public constructor | [WoWPrice(long, long, long)](WoWPrice/Constructors/Constructor_15070919139C.md) | Creates a new WoWPrice from gold, silver, and copper amounts. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Copper](WoWPrice/Properties/Copper_D58CF45082A3.md) | Gets the copper component. |
| Public property | [Gold](WoWPrice/Properties/Gold_183DF749E692.md) | Gets the gold component. |
| Public property | [Silver](WoWPrice/Properties/Silver_BD614243DE1C.md) | Gets the silver component. |
| Public property | [TotalCoppers](WoWPrice/Properties/TotalCoppers_A9E389B9F16A.md) | Gets the total value in copper. |
| Public property Static member | [Zero](WoWPrice/Properties/Zero_83E571906849.md) | Creates a WoWPrice representing zero. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CompareTo(WoWPrice)](WoWPrice/Methods/CompareTo_34029C98C083.md) | Compares the current instance with another object. |
| Public method | [Equals(WoWPrice)](WoWPrice/Methods/Equals_E7E504AFDB77.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](WoWPrice/Methods/Equals_E479C91D7F9C.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().) |
| Public method Static member | [FromGold(long)](WoWPrice/Methods/FromGold_53F425E1EB45.md) | Creates a WoWPrice from a gold amount. |
| Public method Static member | [FromSilver(long)](WoWPrice/Methods/FromSilver_6A44C6622E3E.md) | Creates a WoWPrice from a silver amount. |
| Public method | [GetHashCode](WoWPrice/Methods/GetHashCode_FEB4EA018999.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().) |
| Public method | [ToColorString](WoWPrice/Methods/ToColorString_1CC03965E820.md) | Returns a formatted string with color codes (for use in WoW). |
| Public method | [ToString](WoWPrice/Methods/ToString_2B14B549E444.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory Namespace](../../../../namespaces/Styx/Logic/Inventory.md)
