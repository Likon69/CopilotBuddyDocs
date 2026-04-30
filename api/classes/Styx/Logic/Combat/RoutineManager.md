# RoutineManager Class

Manages combat routines - loads, compiles, and selects the appropriate routine. Follows HB pattern: Init() is called after WoW attachment when ObjectManager.Me is available. FEAT-37: Added CLI parsing, locking, improved selection.

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class RoutineManager
```

The RoutineManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Current](RoutineManager/Properties/Current_03F82A7E8E09.md) | Gets or sets the currently selected combat routine. HB 4.3.4: RoutineManager.Current setter allows CCs to assign themselves directly. |
| Public property Static member | [Routines](RoutineManager/Properties/Routines_AA656E48161D.md) | Gets all loaded routines. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Init](RoutineManager/Methods/Init_8148FE96C28E.md) | Initializes the RoutineManager. Called after WoW is attached and ObjectManager.Me is available. This is where routines are compiled and loaded, exactly like HB. |
| Public method Static member | [SetCurrent(string)](RoutineManager/Methods/SetCurrent_ADD5A73FD7E6.md) | Sets the current routine by name. Returns true if found. FEAT-37: Added return value and LegacySpellManager refresh. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
