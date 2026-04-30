# HealTargeting Class

Represents a heal targeting.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Targeting
    Styx.CommonBot.HealTargeting

## Namespace
[Styx.CommonBot](../../../namespaces/Styx/CommonBot.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class HealTargeting : Targeting
```

The HealTargeting type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [HealTargeting](HealTargeting/Constructors/Constructor_F5F9431BBB75.md) | Initializes a new instance of the HealTargeting class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Instance](HealTargeting/Properties/Instance_6CFCF8BA88A1.md) | Gets or sets the instance. |
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
| Protected method | [DefaultIncludeTargetsFilter(List<WoWObject>, HashSet<WoWObject>)](HealTargeting/Methods/DefaultIncludeTargetsFilter_A14525EF8B82.md) | Applies the default include-target filter. (Overrides Targeting.DefaultIncludeTargetsFilter().) |
| Protected method | [DefaultRemoveTargetsFilter(List<WoWObject>)](HealTargeting/Methods/DefaultRemoveTargetsFilter_28792A9C6A0A.md) | Applies the default remove-target filter. (Overrides Targeting.DefaultRemoveTargetsFilter().) |
| Protected method | [DefaultTargetWeight(List<TargetPriority>)](HealTargeting/Methods/DefaultTargetWeight_97BFBAC0E6A0.md) | Applies the default target weighting. (Overrides Targeting.DefaultTargetWeight().) |
| Protected method | [GetInitialObjectList](HealTargeting/Methods/GetInitialObjectList_DC48C0F12715.md) | Gets the initial object list. (Overrides Targeting.GetInitialObjectList().) |
| Public method | [Pulse](HealTargeting/Methods/Pulse_AD7F3225C58E.md) | Executes one bot pulse. (Overrides Targeting.Pulse().) |
| Public method | Clear | Clears the current contents. (Inherited from Targeting.) |
| Public method | IsNotWithinHotspotRange(WoWPoint, bool) | Indicates that a point lies outside the current hotspot collection range. (Inherited from Targeting.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.CommonBot Namespace](../../../namespaces/Styx/CommonBot.md)
