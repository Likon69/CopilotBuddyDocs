# FactionStanding Struct

Represents a player's standing with a faction.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct FactionStanding
```

The FactionStanding type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [FactionStanding](FactionStanding/Constructors/Constructor_E05B3BC76FD5.md) | Initializes a new instance of the FactionStanding struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [FactionId](FactionStanding/Fields/FactionId_11DC05199793.md) | The faction ID this standing is for. |
| Public field | [Flags](FactionStanding/Fields/Flags_2723AF70C1C4.md) | Reputation flags for this faction. |
| Public field | [Reputation](FactionStanding/Fields/Reputation_1A1FA0EDD9A2.md) | Base reputation value. |
| Public field | [ReputationBonus](FactionStanding/Fields/ReputationBonus_8B20EA929E7E.md) | Bonus reputation from buffs, etc. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [TotalReputation](FactionStanding/Properties/TotalReputation_945015F9F22F.md) | Gets the total reputation (base + bonus). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [HasFlag(ReputationFlags)](FactionStanding/Methods/HasFlag_4D0B4A72CA4F.md) | Checks if the specified reputation flag is set. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
