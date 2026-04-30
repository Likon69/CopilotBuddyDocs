# PowerInfo Struct

FEAT-24: Structured power data for a unit's power type. Provides current/max values, percentages, regen rates, and cost modifiers.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct PowerInfo
```

The PowerInfo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PowerInfo](PowerInfo/Constructors/Constructor_E0E590A41D2E.md) | Initializes a new instance of the PowerInfo struct. |
| Public constructor | [PowerInfo(WoWPowerType, int, int, float, float, float, int, float)](PowerInfo/Constructors/Constructor_47FE69E604D6.md) | Initializes a new instance of the PowerInfo struct. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CostModifier](PowerInfo/Properties/CostModifier_AFED56BD6FDC.md) | Gets the cost modifier. |
| Public property | [CostMultiplier](PowerInfo/Properties/CostMultiplier_F5EDE166FD90.md) | Gets the cost multiplier. |
| Public property | [Current](PowerInfo/Properties/Current_498E88639C0A.md) | Gets the current. |
| Public property | [Max](PowerInfo/Properties/Max_07014EFB1BB9.md) | Gets the max. |
| Public property | [Percent](PowerInfo/Properties/Percent_B175AFB5F040.md) | Gets the percent. |
| Public property | [RegenFlat](PowerInfo/Properties/RegenFlat_7D9DAD178966.md) | Gets the regen flat. |
| Public property | [RegenInterrupted](PowerInfo/Properties/RegenInterrupted_6909C72E70EA.md) | Gets the regen interrupted. |
| Public property | [Type](PowerInfo/Properties/Type_6F8EE737CB0E.md) | Gets the type. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [ToString](PowerInfo/Methods/ToString_D03C722C7689.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
