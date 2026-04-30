# ForcedQuestPickUp Class

Represents a forced quest pick up step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedQuestPickUp

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedQuestPickUp : ForcedBehavior
```

The ForcedQuestPickUp type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedQuestPickUp(uint, string, uint, string, WoWPoint, QuestObjectType?)](ForcedQuestPickUp/Constructors/Constructor_9B8BA8D4B078.md) | Initializes a new instance of the ForcedQuestPickUp class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [GiverId](ForcedQuestPickUp/Properties/GiverId_A3161AF69AAE.md) | Gets the giver id. |
| Public property | [GiverLocation](ForcedQuestPickUp/Properties/GiverLocation_D506CC0808CB.md) | Gets the giver location. |
| Public property | [GiverName](ForcedQuestPickUp/Properties/GiverName_4E6D1FCB78D8.md) | Gets the giver name. |
| Public property | [GiverType](ForcedQuestPickUp/Properties/GiverType_866E80C0062A.md) | Gets the giver type. |
| Public property | [IsDone](ForcedQuestPickUp/Properties/IsDone_C57C1CDF4BD2.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [QuestId](ForcedQuestPickUp/Properties/QuestId_792514CA42A2.md) | Gets the quest id. |
| Public property | [QuestName](ForcedQuestPickUp/Properties/QuestName_519A2A64DEE4.md) | Gets the quest name. |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedQuestPickUp/Methods/CreateBehavior_AAAFC24EC2C7.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [OnStart](ForcedQuestPickUp/Methods/OnStart_FF46A528470B.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [ToString](ForcedQuestPickUp/Methods/ToString_B520128E12A6.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | [Dispose](ForcedBehavior/Methods/Dispose_999011160F69.md) | Disposes resources used by this behavior. (Inherited from ForcedBehavior.) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
