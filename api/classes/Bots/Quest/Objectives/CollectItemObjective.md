# CollectItemObjective Class

Represents a collect item objective.

## Inheritance Hierarchy
System.Object
  Bots.Quest.Objectives.QuestObjective
    Bots.Quest.Objectives.CollectItemObjective

## Namespace
[Bots.Quest.Objectives](../../../../namespaces/Bots/Quest/Objectives.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class CollectItemObjective : QuestObjective
```

The CollectItemObjective type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [CollectItemObjective(PlayerQuest, List<WoWQuestStep>, QuestObjective, List<QuestObjective>)](CollectItemObjective/Constructors/Constructor_F904A37D1F53.md) | Initializes a new instance of the CollectItemObjective class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CanComplete](CollectItemObjective/Properties/CanComplete_3489F2F74E49.md) | Gets a value indicating whether can complete. (Overrides QuestObjective.CanComplete.) |
| Public property | [IsCompleted](CollectItemObjective/Properties/IsCompleted_C3CD3F90A3EA.md) | Gets a value indicating whether is completed. (Overrides QuestObjective.IsCompleted.) |
| Public property | [Objective](CollectItemObjective/Properties/Objective_282136F96367.md) | Gets the objective. |
| Public property | DonePrerequisites | Gets a value indicating whether done prerequisites. (Inherited from QuestObjective.) |
| Public property | OverridedQuestInfo | Gets the overrided quest info. (Inherited from QuestObjective.) |
| Public property | Quest | Gets the quest. (Inherited from QuestObjective.) |
| Public property | QuestArea | Gets the quest area. (Inherited from QuestObjective.) |
| Public property | QuestSteps | Gets the quest steps. (Inherited from QuestObjective.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CreateBranch](CollectItemObjective/Methods/CreateBranch_5AE32687DB6C.md) | Creates the branch. (Overrides QuestObjective.CreateBranch().) |
| Public method | [Dispose](CollectItemObjective/Methods/Dispose_E666D5E96515.md) | Releases the resources used by the instance. (Overrides QuestObjective.Dispose().) |
| Public method | [GetObjectiveLocation](CollectItemObjective/Methods/GetObjectiveLocation_B3FBB6EA2805.md) | Gets the objective location. (Overrides QuestObjective.GetObjectiveLocation().) |
| Public method | [ToString](CollectItemObjective/Methods/ToString_C2A1F4276FE5.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
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
