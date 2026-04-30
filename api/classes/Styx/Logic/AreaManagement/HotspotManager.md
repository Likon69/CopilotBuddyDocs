# HotspotManager Class

Manages hotspots for grinding/questing.

## Inheritance Hierarchy
System.Object
  Styx.Logic.AreaManagement.HotspotManager

## Namespace
[Styx.Logic.AreaManagement](../../../../namespaces/Styx/Logic/AreaManagement.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class HotspotManager
```

The HotspotManager type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [HotspotManager(IEnumerable<WoWPoint>)](HotspotManager/Constructors/Constructor_BE85E692528B.md) | Initializes a new instance of the HotspotManager class. |
| Public constructor | [HotspotManager(XElement)](HotspotManager/Constructors/Constructor_0EC5DA1B8183.md) | Initializes a new instance of the HotspotManager class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Blacklist](HotspotManager/Properties/Blacklist_C31120C2DB14.md) | Gets the blacklist. |
| Public property Static member | [CurrentHotSpot](HotspotManager/Properties/CurrentHotSpot_0E6B2544C683.md) | Gets the current hot spot. |
| Public property | [Hotspots](HotspotManager/Properties/Hotspots_AA132F92C335.md) | Gets the hotspots. |
| Public property Static member | [LastHotSpot](HotspotManager/Properties/LastHotSpot_B62B846FCB0B.md) | Gets or sets the last hot spot. |
| Public property Static member | [Timer](HotspotManager/Properties/Timer_204E07D5C875.md) | Gets or sets the timer. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [BlacklistPoint(WoWPoint, DateTime)](HotspotManager/Methods/BlacklistPoint_CCE025EB2763.md) | Adds the specified point to the blacklist. |
| Public method | [CycleToNearest](HotspotManager/Methods/CycleToNearest_A80D84226C56.md) | Cycles to the nearest hotspot. |
| Public method | [GetNextHotspot](HotspotManager/Methods/GetNextHotspot_0AB4FA7EC5D3.md) | Gets the next hotspot. |
| Public method | [GetRandomHotspot](HotspotManager/Methods/GetRandomHotspot_57EFC4DF69F2.md) | Gets the random hotspot. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.AreaManagement Namespace](../../../../namespaces/Styx/Logic/AreaManagement.md)
