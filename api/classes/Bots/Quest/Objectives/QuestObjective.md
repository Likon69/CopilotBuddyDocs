# QuestObjective Class

Represents a quest objective.

## Inheritance Hierarchy
System.Object
  Bots.Quest.Objectives.QuestObjective

## Namespace
[Bots.Quest.Objectives](../../../../namespaces/Bots/Quest/Objectives.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class QuestObjective : IDisposable, IEquatable<QuestObjective>
```

The QuestObjective type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [QuestObjective(PlayerQuest, List<WoWQuestStep>, List<QuestObjective>)](QuestObjective/Constructors/Constructor_563B954A56E2.md) | Initializes a new instance of the QuestObjective class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Prerequisites](QuestObjective/Fields/Prerequisites_5A204F19EFFB.md) | Represents the prerequisites. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CanComplete](QuestObjective/Properties/CanComplete_39C5DC31F15C.md) | Gets a value indicating whether can complete. |
| Public property | [DonePrerequisites](QuestObjective/Properties/DonePrerequisites_D11A74A77CDB.md) | Gets a value indicating whether done prerequisites. |
| Public property | [IsCompleted](QuestObjective/Properties/IsCompleted_C35E9ADC4A5F.md) | Gets a value indicating whether is completed. |
| Public property | [OverridedQuestInfo](QuestObjective/Properties/OverridedQuestInfo_E4F702F739E3.md) | Gets the overrided quest info. |
| Public property | [Quest](QuestObjective/Properties/Quest_D66B2CF5DA9C.md) | Gets the quest. |
| Public property | [QuestArea](QuestObjective/Properties/QuestArea_A96895F38A48.md) | Gets the quest area. |
| Public property | [QuestSteps](QuestObjective/Properties/QuestSteps_E3D23239D227.md) | Gets the quest steps. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CreateBranch](QuestObjective/Methods/CreateBranch_F4A8E3A37D2D.md) | Creates the branch. |
| Public method | [Dispose](QuestObjective/Methods/Dispose_C4A782982E68.md) | Releases the resources used by the instance. |
| Public method | [Equals(QuestObjective)](QuestObjective/Methods/Equals_FC499A5ED6B7.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](QuestObjective/Methods/Equals_5332D554E407.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().) |
| Protected method | [GetClosestQuestStep](QuestObjective/Methods/GetClosestQuestStep_B938909B91E1.md) | Gets the closest quest step. |
| Protected method | [GetDistanceSortedQuestSteps](QuestObjective/Methods/GetDistanceSortedQuestSteps_4A08B4D512CA.md) | Gets the distance sorted quest steps. |
| Public method | [GetHashCode](QuestObjective/Methods/GetHashCode_CB9FD78FDE1A.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().) |
| Public method | [GetObjectiveLocation](QuestObjective/Methods/GetObjectiveLocation_B0FABF603E36.md) | Gets the objective location. |
| Public method | [IsPointInArea(Vector2)](QuestObjective/Methods/IsPointInArea_FCC4ADA9AB39.md) | Determines whether is point in area. |
| Public method | [IsPointInArea(Vector3)](QuestObjective/Methods/IsPointInArea_B8AA47256F66.md) | Determines whether is point in area. |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Quest.Objectives Namespace](../../../../namespaces/Bots/Quest/Objectives.md)
