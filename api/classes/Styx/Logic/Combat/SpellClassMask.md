# SpellClassMask Struct

Represents a 96-bit spell class mask (3 x 32-bit values). Used for spell family flags and effect class masks in WoW.

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct SpellClassMask
```

The SpellClassMask type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [SpellClassMask](SpellClassMask/Constructors/Constructor_13B283CC01D7.md) | Initializes a new instance of the SpellClassMask struct. |
| Public constructor | [SpellClassMask(uint, uint, uint)](SpellClassMask/Constructors/Constructor_5365211893B1.md) | Initializes a new instance of the SpellClassMask struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [FlagsHigh](SpellClassMask/Fields/FlagsHigh_19761245DD93.md) | Stores the flags high. |
| Public field | [FlagsLow](SpellClassMask/Fields/FlagsLow_69CBB245C5FE.md) | Stores the flags low. |
| Public field | [FlagsMid](SpellClassMask/Fields/FlagsMid_1064D8D59EC9.md) | Stores the flags mid. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsEmpty](SpellClassMask/Properties/IsEmpty_25EAE6C9069A.md) | Gets a value indicating whether is empty. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [HasFlag(uint)](SpellClassMask/Methods/HasFlag_F318CB904AEE.md) | Determines whether has flag. |
| Public method | [ToString](SpellClassMask/Methods/ToString_5465B50AA292.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
