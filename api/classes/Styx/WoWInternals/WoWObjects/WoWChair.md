# WoWChair Class

Represents a chair in WoW. WoW 3.3.5a build 12340.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWSubObject
    Styx.WoWInternals.WoWObjects.WoWChair

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWChair : WoWSubObject
```

The WoWChair type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ChairSlots](WoWChair/Properties/ChairSlots_B3FF19732A08.md) | Number of available chair slots. Returns 1 by default - multi-slot chairs are rare in 3.3.5a. Full implementation would require reading GameObjectDataSlot.Data0. |
| Public property | [SlotPositions](WoWChair/Properties/SlotPositions_C98596E9C4E3.md) | Chair slot positions. Offset +16 (0x10), array de WoWPoint. |
| Public property | BaseAddress | Base address of the sub-object in memory. (Inherited from WoWSubObject.) |
| Public property | InteractDistance | Interaction distance with the sub-object. Offset +12 (0xC). (Inherited from WoWSubObject.) |
| Public property | OwnerObject | Owner GameObject of this sub-object. Offset +4 pour le GUID. (Inherited from WoWSubObject.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | CanUse | Checks if the sub-object can be used. Calls the virtual method CanUse() via vtable. (Inherited from WoWSubObject.) |
| Public method | CanUseNow | Checks if the sub-object can be used now. (Inherited from WoWSubObject.) |
| Public method | CanUseNow(GameError) | Checks if the sub-object can be used now with failure reason. (Inherited from WoWSubObject.) |
| Public method | Use | Uses the sub-object (calls the Use method via vtable). (Inherited from WoWSubObject.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
