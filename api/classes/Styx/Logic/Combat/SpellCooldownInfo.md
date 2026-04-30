# SpellCooldownInfo Struct

FEAT-17: Spell cooldown tracking information. Represents the cooldown state of a single spell at a point in time.

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct SpellCooldownInfo
```

The SpellCooldownInfo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [SpellCooldownInfo](SpellCooldownInfo/Constructors/Constructor_4FB0A21920EF.md) | Initializes a new instance of the SpellCooldownInfo struct. |
| Public constructor | [SpellCooldownInfo(int, TimeSpan, TimeSpan, DateTime)](SpellCooldownInfo/Constructors/Constructor_91B0B5E397AB.md) | Initializes a new instance of the SpellCooldownInfo struct. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Duration](SpellCooldownInfo/Properties/Duration_74D7E5D53E10.md) | Total cooldown duration. |
| Public property | [IsOnCooldown](SpellCooldownInfo/Properties/IsOnCooldown_5F2698AAE5EA.md) | Whether the spell is currently on cooldown. |
| Public property | [SpellId](SpellCooldownInfo/Properties/SpellId_D4E0B4F41AAC.md) | Spell ID. |
| Public property | [StartTime](SpellCooldownInfo/Properties/StartTime_5217AB62BB63.md) | When the cooldown started. |
| Public property | [TimeLeft](SpellCooldownInfo/Properties/TimeLeft_9D739476C579.md) | Time remaining on cooldown. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [ToString](SpellCooldownInfo/Methods/ToString_6DCD4AF96362.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
