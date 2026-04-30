# GrindObjective Class

Represents a grind objective.

## Inheritance Hierarchy
System.Object
  Bots.Quest.Objectives.QuestObjective
    Bots.Quest.Objectives.GrindObjective

## Namespace
[Bots.Quest.Objectives](../../../../namespaces/Bots/Quest/Objectives.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GrindObjective : QuestObjective
```

The GrindObjective type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GrindObjective(PlayerQuest, List<WoWQuestStep>, QuestObjective, List<QuestObjective>)](GrindObjective/Constructors/Constructor_8E11F6895F4A.md) | Initializes a new instance of the GrindObjective class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CanComplete](GrindObjective/Properties/CanComplete_0E6777E38F4B.md) | Gets a value indicating whether can complete. (Overrides QuestObjective.CanComplete.) |
| Public property | [IsCompleted](GrindObjective/Properties/IsCompleted_B3277FD93E5B.md) | Gets a value indicating whether is completed. (Overrides QuestObjective.IsCompleted.) |
| Public property | [Objective](GrindObjective/Properties/Objective_E4C140C28941.md) | Gets the objective. |
| Public property | DonePrerequisites | Gets a value indicating whether done prerequisites. (Inherited from QuestObjective.) |
| Public property | OverridedQuestInfo | Gets the overrided quest info. (Inherited from QuestObjective.) |
| Public property | Quest | Gets the quest. (Inherited from QuestObjective.) |
| Public property | QuestArea | Gets the quest area. (Inherited from QuestObjective.) |
| Public property | QuestSteps | Gets the quest steps. (Inherited from QuestObjective.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CreateBranch](GrindObjective/Methods/CreateBranch_5DFE35E501D9.md) | Creates the branch. (Overrides QuestObjective.CreateBranch().) |
| Public method | [Dispose](GrindObjective/Methods/Dispose_BB4607FC289D.md) | Releases the resources used by the instance. (Overrides QuestObjective.Dispose().) |
| Public method | [GetObjectiveLocation](GrindObjective/Methods/GetObjectiveLocation_77D4D911207B.md) | Gets the objective location. (Overrides QuestObjective.GetObjectiveLocation().) |
| Public method | [ToString](GrindObjective/Methods/ToString_CC0917352210.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(QuestObjective) | Determines whether the specified object is equal to the current object. (Inherited from QuestObjective.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from QuestObjective.) |
| Protected method | GetClosestQuestStep | Gets the closest quest step. (Inherited from QuestObjective.) |
| Protected method | GetDistanceSortedQuestSteps | Gets the distance sorted quest steps. (Inherited from QuestObjective.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from QuestObjective.) |
| Public method | IsPointInArea(Vector2) | Determines whether is point in area. (Inherited from QuestObjective.) |
| Public method | IsPointInArea(Vector3) | Determines whether is point in area. (Inherited from QuestObjective.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Quest.Objectives Namespace](../../../../namespaces/Bots/Quest/Objectives.md)
