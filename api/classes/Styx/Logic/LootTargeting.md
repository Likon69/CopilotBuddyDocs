# LootTargeting Class

Represents a loot targeting.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Targeting
    Styx.Logic.LootTargeting

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class LootTargeting : Targeting
```

The LootTargeting type exposes the following members.

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [AlreadyHarvested](LootTargeting/Fields/AlreadyHarvested_CC454A8734C8.md) | Stores the already harvested. |
| Public field | [AlreadyLooted](LootTargeting/Fields/AlreadyLooted_33DFCA6B0222.md) | Stores the already looted. |
| Public field | [AlreadySkinned](LootTargeting/Fields/AlreadySkinned_CCF7FAD34B1C.md) | Stores the already skinned. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [FirstObject](LootTargeting/Properties/FirstObject_67A65FBEB0E7.md) | Gets the first object. |
| Public property Static member | [HarvestHerbs](LootTargeting/Properties/HarvestHerbs_87F6D4BEDBE7.md) | Gets a value indicating whether harvest herbs. |
| Public property Static member | [HarvestMinerals](LootTargeting/Properties/HarvestMinerals_163F49AEEB3C.md) | Gets a value indicating whether harvest minerals. |
| Public property Static member | [Instance](LootTargeting/Properties/Instance_C5819C68CB70.md) | Gets the instance. |
| Public property Static member | [LootChests](LootTargeting/Properties/LootChests_9303912D9201.md) | Gets a value indicating whether loot chests. |
| Public property Static member | [LootFrameIsOpen](LootTargeting/Properties/LootFrameIsOpen_8D71E9D52A3D.md) | Gets a value indicating whether loot frame is open. |
| Public property Static member | [LootMobs](LootTargeting/Properties/LootMobs_25936CA8DAE3.md) | Gets a value indicating whether loot mobs. |
| Public property Static member | [LootRadius](LootTargeting/Properties/LootRadius_D6FFFE8A9860.md) | Gets the loot radius. |
| Public property | [LootingList](LootTargeting/Properties/LootingList_A9C9F16E4A2C.md) | Gets the looting list. |
| Public property Static member | [NinjaSkin](LootTargeting/Properties/NinjaSkin_8C50CA1F1750.md) | Gets a value indicating whether ninja skin. |
| Public property Static member | [SkinMobs](LootTargeting/Properties/SkinMobs_B435043EAFDD.md) | Gets a value indicating whether skin mobs. |
| Protected property | AllowEvents | HB 4.3.4 compatibility: gates event subscription. Not enforced in CB (thread-safe Interlocked pattern used instead). (Inherited from Targeting.) |
| Public property | DisplayTargetingExceptions | Gets or sets a value indicating whether display targeting exceptions. (Inherited from Targeting.) |
| Public property | FirstUnit | Gets the first unit. (Inherited from Targeting.) |
| Public property | IncludeElites | Gets or sets a value indicating whether include elites. (Inherited from Targeting.) |
| Public property | IncludeWorldPlayers | Gets or sets a value indicating whether include world players. (Inherited from Targeting.) |
| Public property | KillBetweenHotspots | Gets a value indicating whether kill between hotspots. (Inherited from Targeting.) |
| Public property | MaxTargets | Gets or sets the max targets. (Inherited from Targeting.) |
| Protected property | ObjectList | Gets the object list. (Inherited from Targeting.) |
| Public property | TargetList | Gets the target list. (Inherited from Targeting.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | IncludeTargetsFilter | Occurs when include targets filter. (Inherited from Targeting.) |
| Public event | OnTargetListUpdateFinished | Occurs after target list update finishes. (Inherited from Targeting.) |
| Public event | RemoveTargetsFilter | Occurs when remove targets filter. (Inherited from Targeting.) |
| Public event | WeighTargetsFilter | Occurs when weigh targets filter. (Inherited from Targeting.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [DefaultIncludeTargetsFilter(List<WoWObject>, HashSet<WoWObject>)](LootTargeting/Methods/DefaultIncludeTargetsFilter_9997206B6941.md) | Applies the default include-target filter. (Overrides Targeting.DefaultIncludeTargetsFilter().) |
| Protected method | [DefaultRemoveTargetsFilter(List<WoWObject>)](LootTargeting/Methods/DefaultRemoveTargetsFilter_1A56ABDA7524.md) | Applies the default remove-target filter. (Overrides Targeting.DefaultRemoveTargetsFilter().) |
| Protected method | [DefaultTargetWeight(List<TargetPriority>)](LootTargeting/Methods/DefaultTargetWeight_0DD828AC3F55.md) | Applies the default target weighting. (Overrides Targeting.DefaultTargetWeight().) |
| Protected method | [GetInitialObjectList](LootTargeting/Methods/GetInitialObjectList_6BC9D55E9C20.md) | Gets the initial object list. (Overrides Targeting.GetInitialObjectList().) |
| Public method | Clear | Clears the current contents. (Inherited from Targeting.) |
| Public method | IsNotWithinHotspotRange(WoWPoint, bool) | Indicates that a point lies outside the current hotspot collection range. (Inherited from Targeting.) |
| Public method | Pulse | Executes one bot pulse. (Inherited from Targeting.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
