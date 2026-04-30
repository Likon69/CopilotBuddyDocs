# WoWSubObject Class

Represents a WoW sub-object (chair, door, bobber, etc.). WoW 3.3.5a build 12340.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWSubObject

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWSubObject
```

The WoWSubObject type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BaseAddress](WoWSubObject/Properties/BaseAddress_2886B7653287.md) | Base address of the sub-object in memory. |
| Public property | [InteractDistance](WoWSubObject/Properties/InteractDistance_B5D82928291F.md) | Interaction distance with the sub-object. Offset +12 (0xC). |
| Public property | [OwnerObject](WoWSubObject/Properties/OwnerObject_96BFBA7E103F.md) | Owner GameObject of this sub-object. Offset +4 pour le GUID. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CanUse](WoWSubObject/Methods/CanUse_C7AA2CCC1EDB.md) | Checks if the sub-object can be used. Calls the virtual method CanUse() via vtable. |
| Public method | [CanUseNow](WoWSubObject/Methods/CanUseNow_B3CDAD8650B8.md) | Checks if the sub-object can be used now. |
| Public method | [CanUseNow(GameError)](WoWSubObject/Methods/CanUseNow_43DE492A9F22.md) | Checks if the sub-object can be used now with failure reason. |
| Public method | [Use](WoWSubObject/Methods/Use_BAD50C83B3CE.md) | Uses the sub-object (calls the Use method via vtable). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
