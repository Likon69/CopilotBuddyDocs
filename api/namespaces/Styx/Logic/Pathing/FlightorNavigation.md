# Styx.Logic.Pathing.FlightorNavigation Namespace

Contains flight navigation support types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [AerialBlackspotManager](../../../../classes/Styx/Logic/Pathing/FlightorNavigation/AerialBlackspotManager.md) | Manages polygon-based aerial blackspots that Flightor avoids during flight. Ported from HB 6.2.3 BlackspotManager; WotLK-only default data. |
| Public class | [Areas](../../../../classes/Styx/Logic/Pathing/FlightorNavigation/Areas.md) | Represents an areas. |
| Public class | [PolyNav](../../../../classes/Styx/Logic/Pathing/FlightorNavigation/PolyNav.md) | 2D polygon-aware path navigator. Given a continent boundary polygon and a set of hole polygons (aerial blackspots), routes a path between two points using a visibility graph and A*. Ported from HB 6.2.3 PolyNav. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [WoWFactionGroup](../../../../classes/Styx/Logic/Pathing/FlightorNavigation/WoWFactionGroup.md) | Player faction group — used as key for faction-specific aerial blackspots. |

## See Also
[Namespace Index](../../../../index.md)
