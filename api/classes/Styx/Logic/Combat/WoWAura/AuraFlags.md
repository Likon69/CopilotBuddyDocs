# WoWAura.AuraFlags Enumeration

Flags indicating the state and behavior of an aura.

## Namespace
[Styx.Logic.Combat](../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum WoWAura.AuraFlags
```

The WoWAura.AuraFlags type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [AuraFlags](AuraFlags/Constructors/Constructor_2D343D46D62F.md) | Initializes a new instance of the WoWAura.AuraFlags enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [AnyEffectActive](AuraFlags/Fields/AnyEffectActive_3CF2C4BCA089.md) | Any effect of the aura is active (FirstEffect \| SecondEffect \| ThirdEffect). |
| Public field | [Cancellable](AuraFlags/Fields/Cancellable_8E2C4FFEAA23.md) | The aura can be cancelled by the player. |
| Public field | [FirstEffect](AuraFlags/Fields/FirstEffect_288649CA850D.md) | First effect of the aura is active. |
| Public field | [Harmful](AuraFlags/Fields/Harmful_0184E4490ADC.md) | The aura is harmful (debuff). |
| Public field | [NoCaster](AuraFlags/Fields/NoCaster_901DB8F91605.md) | The aura has no caster (NPC buff, item buff, etc.). |
| Public field | [NoDuration](AuraFlags/Fields/NoDuration_CAF2700B7857.md) | The aura has no duration (permanent until cancelled/removed). |
| Public field | [None](AuraFlags/Fields/None_2560545D4BD4.md) | No flags set. |
| Public field | [SecondEffect](AuraFlags/Fields/SecondEffect_956ADFC29A37.md) | Second effect of the aura is active. |
| Public field | [ThirdEffect](AuraFlags/Fields/ThirdEffect_C1E98533E840.md) | Third effect of the aura is active. |
| Public field | [Unknown](AuraFlags/Fields/Unknown_171765C7D28E.md) | Unknown flag (often indicates passive). |

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
[Styx.Logic.Combat Namespace](../../../../../namespaces/Styx/Logic/Combat.md)
