# CommonCoroutines Class

Port of HB 6.2.3 Styx.CommonBot.Coroutines.CommonCoroutines. Provides async helper methods for lag-aware sleeps, Lua event waits, movement stops, and dismounting.

## Namespace
[Styx.CommonBot.Coroutines](../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class CommonCoroutines
```

The CommonCoroutines type exposes the following members.

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Dismount(string, bool)](CommonCoroutines/Methods/Dismount_A51E29D4DB6E.md) | HB 6.2.3: Dismount the character. If flying and descend=true, descends until grounded first. |
| Public method Static member | [MoveTo(WoWPoint, string)](CommonCoroutines/Methods/MoveTo_D2E089553A15.md) | HB 6.2.3: Navigate to a point with logging throttle. |
| Public method Static member | [SleepForLagDuration](CommonCoroutines/Methods/SleepForLagDuration_54E3625428BA.md) | HB 6.2.3: Sleep for latency + 100ms. Used after actions that need to wait for server response. |
| Public method Static member | [SleepForRandomReactionTime](CommonCoroutines/Methods/SleepForRandomReactionTime_1960FF2C87E0.md) | HB 6.2.3: Random reaction time sleep (200-1000ms, with 10% chance of 600-1000ms). Used to humanize bot actions. |
| Public method Static member | [SleepForRandomUiInteractionTime](CommonCoroutines/Methods/SleepForRandomUiInteractionTime_33CA81BDD3C7.md) | HB 6.2.3: Random UI interaction sleep (700-3000ms, with 10% chance of 1500-3000ms). Used when interacting with UI elements (vendor, quest turn-in, etc). |
| Public method Static member | [StopMoving(string)](CommonCoroutines/Methods/StopMoving_F04A7CFFAC15.md) | HB 6.2.3: Stop all movement and wait up to 4s for character to stop. Returns true if movement was stopped, false if already stationary. |
| Public method Static member | [WaitForLuaEvent(string, int, Func<bool>, Action)](CommonCoroutines/Methods/WaitForLuaEvent_EF1F0FE7FA4C.md) | HB 6.2.3: Wait for a Lua event with optional alternate condition. int overload — delegates to TimeSpan overload. |
| Public method Static member | [WaitForLuaEvent(string, TimeSpan, Func<bool>, Action)](CommonCoroutines/Methods/WaitForLuaEvent_19046B6E2E3D.md) | HB 6.2.3: Wait for a Lua event with optional alternate condition. Attaches event, optionally fires action, waits for event or condition, then detaches event. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.CommonBot.Coroutines Namespace](../../../../namespaces/Styx/CommonBot/Coroutines.md)
