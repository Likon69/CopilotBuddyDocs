# ForcedUseItem Class

Represents a forced use item step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedUseItem

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedUseItem : ForcedBehavior
```

The ForcedUseItem type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedUseItem(Func<WoWItem>, Func<WoWObject>, bool, uint, WoWPoint)](ForcedUseItem/Constructors/Constructor_DCD05A5F598D.md) | Initializes a new instance of the ForcedUseItem class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ForceUse](ForcedUseItem/Properties/ForceUse_0AF8AD1FA4D7.md) | Gets a value indicating whether force use. |
| Public property | [IsDone](ForcedUseItem/Properties/IsDone_AD5BCC7C29EB.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [ItemRetriever](ForcedUseItem/Properties/ItemRetriever_C951DFFE98AE.md) | Gets the item retriever. |
| Public property | [Location](ForcedUseItem/Properties/Location_29EA7B317169.md) | Gets the location. |
| Public property | [QuestId](ForcedUseItem/Properties/QuestId_E9F96E0256AB.md) | Gets the quest id. |
| Public property | [TargetRetriever](ForcedUseItem/Properties/TargetRetriever_DCC4F88AF4F1.md) | Gets the target retriever. |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedUseItem/Methods/CreateBehavior_8BF0E682B76F.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [OnStart](ForcedUseItem/Methods/OnStart_C85C34ACB0C6.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [ToString](ForcedUseItem/Methods/ToString_AE000C6CDDAA.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | [Dispose](ForcedBehavior/Methods/Dispose_999011160F69.md) | Disposes resources used by this behavior. (Inherited from ForcedBehavior.) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
