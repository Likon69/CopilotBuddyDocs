# InactivityDetector Class

Detects player inactivity and can trigger automatic logout.

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class InactivityDetector
```

The InactivityDetector type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [LogoutTime](InactivityDetector/Properties/LogoutTime_B5B3B5090241.md) | Gets the scheduled logout time. |
| Public property Static member | [TimeUntilLogout](InactivityDetector/Properties/TimeUntilLogout_3896FA26AD44.md) | Gets the time remaining until automatic logout. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [ForceLogout(bool)](InactivityDetector/Methods/ForceLogout_2768DCB7E941.md) | Forces the player to logout. |
| Public method Static member | [Initialize](InactivityDetector/Methods/Initialize_3DCC528BDEB3.md) | Initializes the inactivity detector with current settings. |
| Public method Static member | [OnPulse](InactivityDetector/Methods/OnPulse_1E0D78B467FD.md) | Called on each bot pulse to check for inactivity. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
