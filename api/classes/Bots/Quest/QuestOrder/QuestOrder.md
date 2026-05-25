# QuestOrder Class

Manages the quest order - the list of ordered nodes to execute.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.QuestOrder

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class QuestOrder
```

The QuestOrder type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QuestOrder](QuestOrder/Constructors/Constructor_206F2B40F9E7.md) | Initializes a new instance of the QuestOrder class. |
| Public constructor | [QuestOrder(OrderNodeCollection)](QuestOrder/Constructors/Constructor_0D0908FD6CF5.md) | Initializes a new instance of the QuestOrder class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CurrentBehavior](QuestOrder/Properties/CurrentBehavior_9E28E17F7DD3.md) | The currently executing forced behavior. |
| Public property | [CurrentNode](QuestOrder/Properties/CurrentNode_3480A138D2B7.md) | The current node being processed. |
| Public property | [IgnoreCheckpoints](QuestOrder/Properties/IgnoreCheckpoints_7BC4F42F81A9.md) | Whether to ignore checkpoints in the quest order. |
| Public property Static member | [Instance](QuestOrder/Properties/Instance_546961D3DDB3.md) | Gets the instance. |
| Public property | [NavType](QuestOrder/Properties/NavType_E3544BA3F914.md) | Effective NavType for the current movement node. Priority: ForcedBehavior.NavType → Flightor.CanFly auto-detect. Legion: QuestOrder.NavType property (same cascade logic). |
| Public property | [Nodes](QuestOrder/Properties/Nodes_6C73EB09E1D6.md) | The collection of order nodes to execute. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [OnNoMoreNodes](QuestOrder/Events/OnNoMoreNodes_1A08A60FD6D6.md) | Event fired when there are no more nodes to process. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Advance](QuestOrder/Methods/Advance_62BB78F4DACA.md) | Advance to the next node. |
| Public method | [Advance(int)](QuestOrder/Methods/Advance_1629BA037D60.md) | Advance by a number of nodes. |
| Public method | [RemoveCompletedNodes(HashSet<uint>)](QuestOrder/Methods/RemoveCompletedNodes_BE4E4D51F3E4.md) | Removes nodes for quests that are already completed. |
| Public method | [SkipToCheckpoint(float)](QuestOrder/Methods/SkipToCheckpoint_79D665AA47E8.md) | Skips to the checkpoint matching the player's level. |
| Public method | [UpdateNodes](QuestOrder/Methods/UpdateNodes_662074B29C26.md) | Updates nodes based on current quest state. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
