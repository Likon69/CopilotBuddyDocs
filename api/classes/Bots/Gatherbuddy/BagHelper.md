# BagHelper Class

Counts free bag slots restricted to the bag families relevant to each gather type. Port of HB 4.3.4 Bots.GatherBuddy.BagHelper. Normal bags (BagType.Normal) can hold anything, so they always count. Mining bags (BagType.Mining) only hold minerals — they count for mine slots, not herb slots. Herb bags (BagType.Herb) only hold herbs — they count for herb slots, not mine slots.

## Namespace
[Bots.Gatherbuddy](../../../namespaces/Bots/Gatherbuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class BagHelper
```

The BagHelper type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [EmptyHerbSlots](BagHelper/Properties/EmptyHerbSlots_068382C33CFE.md) | Free slots available for herbs: backpack + Normal bags + Herb bags. |
| Public property Static member | [EmptyMineSlots](BagHelper/Properties/EmptyMineSlots_EBF70EF545EB.md) | Free slots available for minerals: backpack + Normal bags + Mining bags. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Gatherbuddy Namespace](../../../namespaces/Bots/Gatherbuddy.md)
