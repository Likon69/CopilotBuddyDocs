# ForcedQuestTurnIn Class

Represents a forced quest turn in step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedQuestTurnIn

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedQuestTurnIn : ForcedBehavior
```

The ForcedQuestTurnIn type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedQuestTurnIn(uint, string, uint, string, WoWPoint)](ForcedQuestTurnIn/Constructors/Constructor_8335F6195970.md) | Initializes a new instance of the ForcedQuestTurnIn class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsDone](ForcedQuestTurnIn/Properties/IsDone_1732FFD73D74.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Location](ForcedQuestTurnIn/Properties/Location_4AEBE91800DC.md) | Gets the location. |
| Public property | [NpcId](ForcedQuestTurnIn/Properties/NpcId_27932265075D.md) | Gets the npc id. |
| Public property | [NpcName](ForcedQuestTurnIn/Properties/NpcName_D9B25127E6F6.md) | Gets the npc name. |
| Public property | [QuestId](ForcedQuestTurnIn/Properties/QuestId_1B49E99D1BF5.md) | Gets the quest id. |
| Public property | [QuestName](ForcedQuestTurnIn/Properties/QuestName_5C8ADFAF96E1.md) | Gets the quest name. |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |
| Public property | [NavType](ForcedBehavior/Properties/NavType_41A3D52F0288.md) | NavType for this behavior. null = auto-detect (Flightor.CanFly). Legion: ForcedBehavior.NavType (nullable). (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedQuestTurnIn/Methods/CreateBehavior_C3D464FB9AEE.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [OnStart](ForcedQuestTurnIn/Methods/OnStart_479360F43BFA.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [ToString](ForcedQuestTurnIn/Methods/ToString_5B87C8E130E8.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | [Dispose](ForcedBehavior/Methods/Dispose_999011160F69.md) | Disposes resources used by this behavior. (Inherited from ForcedBehavior.) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
