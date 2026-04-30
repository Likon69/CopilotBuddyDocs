# TreeRoot Class

Represents a tree root.

## Namespace
[Styx.Logic.BehaviorTree](../../../../namespaces/Styx/Logic/BehaviorTree.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class TreeRoot
```

The TreeRoot type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Current](TreeRoot/Properties/Current_ECDB2D09FE77.md) | Gets the current. |
| Public property Static member | [CurrentThreadIsBotThread](TreeRoot/Properties/CurrentThreadIsBotThread_66F098662696.md) | HB 5.4.8: True when the calling thread is the bot worker thread. |
| Public property Static member | [GoalText](TreeRoot/Properties/GoalText_179C89DC286D.md) | High-level goal text — displayed in the Info panel. Same as HB 4.3.4 (no event, polled by UpdateInfoPanel timer). |
| Public property Static member | [IsPaused](TreeRoot/Properties/IsPaused_1EADB9B6BBD4.md) | HB 6.2.3: true when State == Paused. |
| Public property Static member | [IsRunning](TreeRoot/Properties/IsRunning_376C078B26FB.md) | Gets a value indicating whether is running. |
| Public property Static member | [State](TreeRoot/Properties/State_B1B14D5490D0.md) | State machine for TreeRoot lifecycle — matches HB 6.2.3. Stop() sets Stopping; worker thread does cleanup then sets Stopped. |
| Public property Static member | [StatusText](TreeRoot/Properties/StatusText_FB0F001B6F21.md) | Current activity text — displayed in the StatusBar at the bottom of the UI. Fires OnStatusTextChanged event (same as HB 4.3.4). |
| Public property Static member | [TicksPerSecond](TreeRoot/Properties/TicksPerSecond_99AAD403878E.md) | Gets or sets the ticks per second. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnStatusTextChanged](TreeRoot/Events/OnStatusTextChanged_42DE1F26494B.md) | Event fired when StatusText changes — UI subscribes to update StatusBar. Same as HB 4.3.4's TreeRoot.OnStatusTextChanged. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Pause](TreeRoot/Methods/Pause_2A9D98DFABEC.md) | HB 6.2.3: Transition Running → Paused. |
| Public method Static member | [Restart](TreeRoot/Methods/Restart_43AAC8444DDD.md) | Restarts the timer. |
| Public method Static member | [Resume](TreeRoot/Methods/Resume_DCE168B4B962.md) | HB 6.2.3: Transition Paused → Running. |
| Public method Static member | [Start](TreeRoot/Methods/Start_44EE41642D7F.md) | Starts the bot. |
| Public method Static member | [Stop(string)](TreeRoot/Methods/Stop_D066245F0053.md) | Stop the bot. HB 6.2.3 pattern: ONLY sets State = Stopping. The worker thread detects the state change, finishes the current tick, then does the actual cleanup on its own thread — no race condition. NO Join() — HB 6.2.3 never joins the worker thread from Stop(). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.BehaviorTree Namespace](../../../../namespaces/Styx/Logic/BehaviorTree.md)
