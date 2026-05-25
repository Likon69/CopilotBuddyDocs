# AvoidancePriority Enumeration

HB 6.2.3 AvoidancePriority — weights the urgency of an avoid zone. Used by GetBestLocationOutsideCluster to bias the escape route scoring: high-priority avoids (e.g. instant-kill fire) dominate the score so the bot exits through them first, even if the path is longer. Values match HB 6.2.3 exactly: Low=1, Medium=10, High=100.

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum AvoidancePriority
```

The AvoidancePriority type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [AvoidancePriority](AvoidancePriority/Constructors/Constructor_C1C1612573C5.md) | Initializes a new instance of the AvoidancePriority enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [High](AvoidancePriority/Fields/High_94BEC41A9F3C.md) | Represents the high value. |
| Public field | [Low](AvoidancePriority/Fields/Low_C70B0EDC0020.md) | Represents the low value. |
| Public field | [Medium](AvoidancePriority/Fields/Medium_8F232483B6FB.md) | Represents the medium value. |

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
[Bots.DungeonBuddy.Avoidance Namespace](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
