# Blackspot Struct

Represents a blackspot - an area to avoid during navigation.

## Namespace
[Styx.Logic.Profiles](../../../../namespaces/Styx/Logic/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct Blackspot : IEquatable<Blackspot>
```

The Blackspot type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Blackspot](Blackspot/Constructors/Constructor_DD4EF14BB61B.md) | Initializes a new instance of the Blackspot struct. |
| Public constructor | [Blackspot(XElement)](Blackspot/Constructors/Constructor_3311DC36029A.md) | Initializes a blackspot from an XML element. Ported from HB 4.3.4 Styx.Logic.Profiles.Blackspot(XElement). |
| Public constructor | [Blackspot(WoWPoint, float, float)](Blackspot/Constructors/Constructor_1A94C0E5FB89.md) | Initializes a new blackspot. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Height](Blackspot/Fields/Height_09B89EF73595.md) | Gets or sets the height of the blackspot cylinder. |
| Public field | [Location](Blackspot/Fields/Location_A06E3BFDC1E5.md) | Gets or sets the center location of the blackspot. |
| Public field | [Radius](Blackspot/Fields/Radius_F44A83249DCD.md) | Gets or sets the radius of the blackspot. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Contains(WoWPoint)](Blackspot/Methods/Contains_59FA8548F561.md) | Checks if a point is within this blackspot. |
| Public method | [Equals(Blackspot)](Blackspot/Methods/Equals_4D1A7220CAB6.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](Blackspot/Methods/Equals_08E0C655EA25.md) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().) |
| Public method | [GetHashCode](Blackspot/Methods/GetHashCode_1F6756890D71.md) | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().) |
| Public method | [ToString](Blackspot/Methods/ToString_E7A0241815A4.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles Namespace](../../../../namespaces/Styx/Logic/Profiles.md)
