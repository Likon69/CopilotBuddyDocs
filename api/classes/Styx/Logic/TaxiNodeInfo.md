# TaxiNodeInfo Class

TaxiNodeInfo - Represents a flight path node from TaxiNodes.dbc Contains world location, name, and faction-specific mount information

## Inheritance Hierarchy
System.Object
  Styx.Logic.TaxiNodeInfo

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class TaxiNodeInfo
```

The TaxiNodeInfo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [TaxiNodeInfo(Row)](TaxiNodeInfo/Constructors/Constructor_FC81391F4AED.md) | Create TaxiNodeInfo from DBC row |
| Public constructor | [TaxiNodeInfo(uint)](TaxiNodeInfo/Constructors/Constructor_DF8E0A83026A.md) | Create TaxiNodeInfo by ID |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AllianceMountCreatureId](TaxiNodeInfo/Properties/AllianceMountCreatureId_D661278DD642.md) | Creature ID for Alliance flight mount |
| Public property | [AllianceOnly](TaxiNodeInfo/Properties/AllianceOnly_977FF6A87DAF.md) | True if this is an Alliance-only flight path (no Horde mount) |
| Public property | [HordeMountCreatureId](TaxiNodeInfo/Properties/HordeMountCreatureId_526CEE3C932A.md) | Creature ID for Horde flight mount |
| Public property | [HordeOnly](TaxiNodeInfo/Properties/HordeOnly_E7F0113DCADA.md) | True if this is a Horde-only flight path (no Alliance mount) |
| Public property | [Id](TaxiNodeInfo/Properties/Id_C91A3A7C9967.md) | Node ID from TaxiNodes.dbc |
| Public property | [IsFlightPath](TaxiNodeInfo/Properties/IsFlightPath_CA3513D0BBFD.md) | True if this is a valid flight path (has at least one mount) |
| Public property | [IsValid](TaxiNodeInfo/Properties/IsValid_8012D68FA53C.md) | Whether this node is valid |
| Public property | [Location](TaxiNodeInfo/Properties/Location_0657EC468A0D.md) | World location of the flight master (real coordinates) |
| Public property | [MapId](TaxiNodeInfo/Properties/MapId_107B04EA6ACF.md) | Map/Continent ID where this node is located |
| Public property | [Name](TaxiNodeInfo/Properties/Name_865DED4F7B53.md) | Name of the flight path (e.g., "Stormwind, Elwynn") Read from string pointer in memory |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FindByName(string)](TaxiNodeInfo/Methods/FindByName_4B4522D96A28.md) | Find TaxiNodeInfo by name (partial match) |
| Public method Static member | [FromId(uint)](TaxiNodeInfo/Methods/FromId_DECDA5105CCF.md) | Get TaxiNodeInfo by ID |
| Public method Static member | [GetAll](TaxiNodeInfo/Methods/GetAll_4AC37E18B487.md) | Get all known taxi nodes |
| Public method | [ToString](TaxiNodeInfo/Methods/ToString_6BD07D6FBCF8.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
