# VendorManager Class

Manages vendor NPCs from profiles.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.VendorManager

## Namespace
[Styx.Logic.Profiles](../../../../namespaces/Styx/Logic/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class VendorManager
```

The VendorManager type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [VendorManager](VendorManager/Constructors/Constructor_04086CB3495D.md) | Creates an empty vendor manager. |
| Public constructor | [VendorManager(XElement)](VendorManager/Constructors/Constructor_46F8FC8686FB.md) | Creates a vendor manager from XML. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AllVendors](VendorManager/Properties/AllVendors_8EF812E71ECE.md) | Gets all vendors in the profile. |
| Public property | [Blacklist](VendorManager/Properties/Blacklist_66EB4EC50C4B.md) | Gets the blacklisted vendors. |
| Public property | [ForcedVendors](VendorManager/Properties/ForcedVendors_106204A87B9E.md) | Gets or sets forced vendors that override profile vendors. |
| Public property | [Vendors](VendorManager/Properties/Vendors_CB8C94E15D6E.md) | Gets vendors grouped by type, excluding blacklisted. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetClosestVendor](VendorManager/Methods/GetClosestVendor_885265D72EF8.md) | Gets the closest vendor of any type. |
| Public method | [GetClosestVendor(VendorType)](VendorManager/Methods/GetClosestVendor_9215A294D155.md) | Gets the closest vendor of a specific type. For Sell type, also accepts Repair and Ammo vendors (they can all buy items). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles Namespace](../../../../namespaces/Styx/Logic/Profiles.md)
