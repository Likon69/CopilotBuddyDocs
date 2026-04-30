# QuestDescriptorData Struct

Quest data structure read from player unit descriptor fields. Contains quest identification, state flags, objective progress counters, and optional failure timer for timed quests. Size: 20 bytes (5 x uint32 equivalent)

## Namespace
[Styx.Logic.Questing](../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct QuestDescriptorData
```

The QuestDescriptorData type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QuestDescriptorData](QuestDescriptorData/Constructors/Constructor_3670EB409281.md) | Initializes a new instance of the QuestDescriptorData struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Flags](QuestDescriptorData/Fields/Flags_E031284B67C1.md) | Quest state flags (completed, failed, etc.). |
| Public field | [Id](QuestDescriptorData/Fields/Id_1D7BBCEC14E5.md) | The quest ID from quest database. |
| Public field | [ObjectivesDone](QuestDescriptorData/Fields/ObjectivesDone_5668E15B5790.md) | Progress count for each of the 4 possible objectives. Array of 4 ushort values representing completion counts. |
| Public field | [SecondsBeforeFailed](QuestDescriptorData/Fields/SecondsBeforeFailed_355626FD5B93.md) | For timed quests: seconds remaining before the quest fails. Zero for non-timed quests. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsCompleted](QuestDescriptorData/Properties/IsCompleted_591458E31ADE.md) | Gets whether the quest has been completed. |
| Public property | [IsFailed](QuestDescriptorData/Properties/IsFailed_20594367CA5A.md) | Gets whether the quest has failed. |
| Public property | [IsValid](QuestDescriptorData/Properties/IsValid_69473FFA1B8C.md) | Gets whether this quest slot contains valid quest data. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetObjectiveProgress(int)](QuestDescriptorData/Methods/GetObjectiveProgress_4810D98ABAA5.md) | Gets the progress for a specific objective index (0-3). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Questing Namespace](../../../../namespaces/Styx/Logic/Questing.md)
