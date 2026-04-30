# PvPArea Class

Represents a PvP area.

## Inheritance Hierarchy
System.Object
  Styx.Logic.AreaManagement.Area
    Styx.Logic.AreaManagement.PolygonArea
      Styx.Logic.AreaManagement.PvPArea

## Namespace
[Styx.Logic.AreaManagement](../../../../namespaces/Styx/Logic/AreaManagement.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class PvPArea : PolygonArea
```

The PvPArea type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PvPArea(Vector2[])](PvPArea/Constructors/Constructor_96E2F295A0DB.md) | Initializes a new instance of the PvPArea class. |
| Public constructor | [PvPArea(string, Vector2[])](PvPArea/Constructors/Constructor_AE81B7514BBC.md) | Initializes a new instance of the PvPArea class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Name](PvPArea/Fields/Name_5AF75EB0894C.md) | The name of the PvP area. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Type](PvPArea/Properties/Type_B56E1DD829E8.md) | Gets the area type. (Overrides Area.Type.) |
| Public property | [LocalPlayerIsInBounds](PolygonArea/Properties/LocalPlayerIsInBounds_27E7EFA24928.md) | Gets whether the local player is within the polygon bounds. (Inherited from PolygonArea.) |
| Public property | [CircledHotspots](Area/Properties/CircledHotspots_92168F29FFF8.md) | Gets or sets the circled hotspots. (Inherited from Area.) |
| Public property | [Guid](Area/Properties/Guid_7400E53BA5F5.md) | Gets the guid. (Inherited from Area.) |
| Public property | [Hotspots](Area/Properties/Hotspots_CAB80FE74FF6.md) | Gets or sets the hotspots. (Inherited from Area.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [IsPointInPoly(WoWPoint)](PolygonArea/Methods/IsPointInPoly_A6A617929629.md) | Checks if a point is within the polygon. (Inherited from PolygonArea.) |
| Public method | [CycleToNearest](Area/Methods/CycleToNearest_0E714372D287.md) | Cycles to the nearest hotspot. (Inherited from Area.) |
| Public method | [Equals(Area)](Area/Methods/Equals_1D9675AEB03C.md) | Determines whether the specified object is equal to the current object. (Inherited from Area.) |
| Public method | [Equals(object)](Area/Methods/Equals_FF99EF6C2FAF.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from Area.) |
| Public method | [GetHashCode](Area/Methods/GetHashCode_98F42792A260.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from Area.) |
| Public method | [GetNextHotspot](Area/Methods/GetNextHotspot_B591D7B44C12.md) | Gets the next hotspot. (Inherited from Area.) |
| Public method | [GetRandomHotspot](Area/Methods/GetRandomHotspot_C799D92B1FB0.md) | Gets the random hotspot. (Inherited from Area.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.AreaManagement Namespace](../../../../namespaces/Styx/Logic/AreaManagement.md)
