# Targeting Class

Represents a targeting.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Targeting

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Targeting
```

The Targeting type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [Targeting.TargetPriority](Targeting/TargetPriority.md) | Represents a target priority. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Targeting](Targeting/Constructors/Constructor_31BAFD7E99EF.md) | Initializes a new instance of the Targeting class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Protected property | [AllowEvents](Targeting/Properties/AllowEvents_0A83CBC4BF0C.md) | HB 4.3.4 compatibility: gates event subscription. Not enforced in CB (thread-safe Interlocked pattern used instead). |
| Public property Static member | [CollectionRange](Targeting/Properties/CollectionRange_4A1087A5A1B3.md) | Gets the collection range. |
| Public property | [DisplayTargetingExceptions](Targeting/Properties/DisplayTargetingExceptions_929E7FDECE10.md) | Gets or sets a value indicating whether display targeting exceptions. |
| Public property | [FirstUnit](Targeting/Properties/FirstUnit_28622F8B2204.md) | Gets the first unit. |
| Public property | [IncludeElites](Targeting/Properties/IncludeElites_91A5E456D9EB.md) | Gets or sets a value indicating whether include elites. |
| Public property | [IncludeWorldPlayers](Targeting/Properties/IncludeWorldPlayers_76EDBD45A57E.md) | Gets or sets a value indicating whether include world players. |
| Public property Static member | [Instance](Targeting/Properties/Instance_30E8D3C8DDC5.md) | Gets or sets the instance. |
| Public property | [KillBetweenHotspots](Targeting/Properties/KillBetweenHotspots_08864751C19B.md) | Gets a value indicating whether kill between hotspots. |
| Public property | [MaxTargets](Targeting/Properties/MaxTargets_F5A1EA526132.md) | Gets or sets the max targets. |
| Protected property | [ObjectList](Targeting/Properties/ObjectList_EBC532AC3AD5.md) | Gets the object list. |
| Public property Static member | [PullDistance](Targeting/Properties/PullDistance_6621F0FF2ED7.md) | Gets the pull distance. |
| Public property Static member | [PullDistanceSqr](Targeting/Properties/PullDistanceSqr_A926EC0D8A36.md) | Gets the pull distance sqr. |
| Public property | [TargetList](Targeting/Properties/TargetList_124127160DB9.md) | Gets the target list. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [IncludeTargetsFilter](Targeting/Events/IncludeTargetsFilter_FA5AEB788E93.md) | Occurs when include targets filter. |
| Public event | [OnTargetListUpdateFinished](Targeting/Events/OnTargetListUpdateFinished_22E6CC701FA5.md) | Occurs after target list update finishes. |
| Public event | [RemoveTargetsFilter](Targeting/Events/RemoveTargetsFilter_DE4BD5A7572B.md) | Occurs when remove targets filter. |
| Public event | [WeighTargetsFilter](Targeting/Events/WeighTargetsFilter_91F36B5F9B60.md) | Occurs when weigh targets filter. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Clear](Targeting/Methods/Clear_AB0B890551E6.md) | Clears the current contents. |
| Protected method | [DefaultIncludeTargetsFilter(List<WoWObject>, HashSet<WoWObject>)](Targeting/Methods/DefaultIncludeTargetsFilter_27B287B18723.md) | Applies the default include-target filter. |
| Protected method | [DefaultRemoveTargetsFilter(List<WoWObject>)](Targeting/Methods/DefaultRemoveTargetsFilter_2260D0B25F12.md) | Applies the default remove-target filter. |
| Protected method | [DefaultTargetWeight(List<TargetPriority>)](Targeting/Methods/DefaultTargetWeight_D8D550584611.md) | Weights each unit in the target list. Matches HB 4.3.4 structure. |
| Public method Static member | [GetAggroOnMeWithin(WoWPoint, float)](Targeting/Methods/GetAggroOnMeWithin_4969E9D8FC39.md) | Gets the aggro on me within. |
| Public method Static member | [GetAggroWithin(WoWPoint, float)](Targeting/Methods/GetAggroWithin_76043CC2C6F6.md) | Gets the aggro within. |
| Protected method | [GetInitialObjectList](Targeting/Methods/GetInitialObjectList_EB95AAAFF954.md) | Gets the initial object list. |
| Public method | [IsNotWithinHotspotRange(WoWPoint, bool)](Targeting/Methods/IsNotWithinHotspotRange_61E89E5F3167.md) | Indicates that a point lies outside the current hotspot collection range. |
| Public method Static member | [IsTooNearBlackspot(IEnumerable<Blackspot>, WoWPoint)](Targeting/Methods/IsTooNearBlackspot_4F707F1159C8.md) | Checks if a point is within any blackspot. HB 4.3.4 compatible - used by Quest Behaviors. |
| Public method | [Pulse](Targeting/Methods/Pulse_007143C765E9.md) | Executes one bot pulse. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
