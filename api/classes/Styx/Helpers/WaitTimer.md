# WaitTimer Class

Represents a wait timer.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.WaitTimer

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WaitTimer
```

The WaitTimer type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [WaitTimer.WaitTimerEventArgs](WaitTimer/WaitTimerEventArgs.md) | Represents a wait timer event args. |
| Public delegate | [WaitTimer.WaitTimerFinishedHandler](WaitTimer/WaitTimerFinishedHandler.md) | Represents a delegate for Wait Timer Finished Handler. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WaitTimer(TimeSpan)](WaitTimer/Constructors/Constructor_1C148B615F39.md) | Initializes a new instance of the WaitTimer class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [EndTime](WaitTimer/Properties/EndTime_68DDA0D598AD.md) | Gets the end time. |
| Public property Static member | [FiveSeconds](WaitTimer/Properties/FiveSeconds_4BB4DC6A232B.md) | Gets the five seconds. |
| Public property | [IsFinished](WaitTimer/Properties/IsFinished_19A1638D8423.md) | Gets a value indicating whether is finished. |
| Public property Static member | [OneMinute](WaitTimer/Properties/OneMinute_62A47F041C79.md) | Gets the one minute. |
| Public property Static member | [OneSecond](WaitTimer/Properties/OneSecond_1143DD7C1CC0.md) | Gets the one second. |
| Public property | [StartTime](WaitTimer/Properties/StartTime_1F3827016020.md) | Gets the start time. |
| Public property Static member | [TenSeconds](WaitTimer/Properties/TenSeconds_BE33E08EBEA4.md) | Gets the ten seconds. |
| Public property Static member | [ThirtySeconds](WaitTimer/Properties/ThirtySeconds_81269691673F.md) | Gets the thirty seconds. |
| Public property | [TimeLeft](WaitTimer/Properties/TimeLeft_58E85C6042DB.md) | Gets the time left. |
| Public property | [WaitTime](WaitTimer/Properties/WaitTime_B49EB52E8F5C.md) | Gets or sets the wait time. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [Finished](WaitTimer/Events/Finished_6A682E471D7A.md) | Occurs when finished. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Reset](WaitTimer/Methods/Reset_0E53AA0CECB5.md) | Resets the current state. |
| Public method | [Stop](WaitTimer/Methods/Stop_DB2032BEBCF9.md) | Stops the bot. |
| Public method | [Update](WaitTimer/Methods/Update_9985FA7DF56E.md) | Raises the Finished event when the wait timer has elapsed. |
| Public method | [Wait](WaitTimer/Methods/Wait_BA29A4180FB0.md) | Waits for the condition or timeout. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
