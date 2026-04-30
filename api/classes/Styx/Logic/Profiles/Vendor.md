# Vendor Class

Represents a vendor NPC in a profile.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Vendor

## Namespace
[Styx.Logic.Profiles](../../../../namespaces/Styx/Logic/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Vendor : IEquatable<Vendor>
```

The Vendor type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [Vendor.VendorType](Vendor/VendorType.md) | Vendor type enumeration. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Vendor(XElement)](Vendor/Constructors/Constructor_F8AA74A168E5.md) | Creates a vendor from XML. |
| Public constructor | [Vendor(WoWObject, VendorType)](Vendor/Constructors/Constructor_2E42B681783D.md) | Creates a vendor from a WoW object. |
| Public constructor | [Vendor(int, string, VendorType, WoWPoint)](Vendor/Constructors/Constructor_9B23A9BA5FC8.md) | Creates a vendor from parameters. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Entry](Vendor/Properties/Entry_69087F36DCE3.md) | Gets the NPC entry ID. |
| Public property | [Entry2](Vendor/Properties/Entry2_8A80420CEE2C.md) | Gets the secondary NPC entry ID. |
| Public property | [Location](Vendor/Properties/Location_B6A78C21378F.md) | Gets or sets the vendor location. |
| Public property | [Name](Vendor/Properties/Name_BE33FADB59F7.md) | Gets the NPC name. |
| Public property | [TrainClass](Vendor/Properties/TrainClass_981963C7E4A5.md) | Gets or sets the class this trainer trains (if applicable). |
| Public property | [Type](Vendor/Properties/Type_7665832C3D44.md) | Gets the vendor type. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Equals(Vendor)](Vendor/Methods/Equals_44242961FD90.md) | Determines whether this vendor equals another. |
| Public method | [ToString](Vendor/Methods/ToString_C56CFF0358D7.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles Namespace](../../../../namespaces/Styx/Logic/Profiles.md)
