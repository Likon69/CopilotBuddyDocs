# WoWTotemInfo Class

Information about an active totem. WotLK 3.3.5a implementation using Lua.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWTotemInfo

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWTotemInfo
```

The WoWTotemInfo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWTotemInfo(int)](WoWTotemInfo/Constructors/Constructor_71EE683CF1EC.md) | Creates a totem info for a specific slot. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Active](WoWTotemInfo/Properties/Active_92B297F0D089.md) | Returns true if a totem is active in this slot. |
| Public property | [Duration](WoWTotemInfo/Properties/Duration_2C54F56C3CAB.md) | Gets the duration of the totem in seconds. |
| Public property | [Expired](WoWTotemInfo/Properties/Expired_BE7ED21796D4.md) | Returns true if the totem has expired. |
| Public property | [Expires](WoWTotemInfo/Properties/Expires_FD6E504CF9FB.md) | Gets the expiry DateTime for this totem (StartTime + Duration). |
| Public property | [Guid](WoWTotemInfo/Properties/Guid_711A9E9CC05F.md) | Gets the GUID of the totem unit. |
| Public property | [IconPath](WoWTotemInfo/Properties/IconPath_7C8FFC406D3B.md) | Gets the icon texture path for this totem's spell. |
| Public property | [Name](WoWTotemInfo/Properties/Name_31B64046AFC1.md) | Gets the name of the active totem. |
| Public property | [Slot](WoWTotemInfo/Properties/Slot_C2AB4B665B6F.md) | Gets the slot index (0=Fire, 1=Earth, 2=Water, 3=Air). |
| Public property | [Spell](WoWTotemInfo/Properties/Spell_2A86C6D438B5.md) | Gets the spell that created this totem. |
| Public property | [SpellId](WoWTotemInfo/Properties/SpellId_8752617386C5.md) | Gets the spell ID that created this totem. |
| Public property | [StartTime](WoWTotemInfo/Properties/StartTime_E1FC7648266D.md) | Gets the time when the totem was placed. |
| Public property | [TimeLeft](WoWTotemInfo/Properties/TimeLeft_B4D1756CE52B.md) | Gets the remaining time on the totem. |
| Public property | [Totem](WoWTotemInfo/Properties/Totem_B3D1B32D3B99.md) | Gets the WoWTotem enum value. |
| Public property | [Type](WoWTotemInfo/Properties/Type_60CA6A9B35D7.md) | Gets the totem type for this slot. |
| Public property | [Unit](WoWTotemInfo/Properties/Unit_47B4356741C1.md) | Gets the unit representing this totem. |
| Public property | [WoWTotem](WoWTotemInfo/Properties/WoWTotem_51A56E49661A.md) | Gets the WoWTotem enum value (Singular compatibility). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Destroy](WoWTotemInfo/Methods/Destroy_8392CC884B47.md) | Destroys this totem. |
| Public method | [ToString](WoWTotemInfo/Methods/ToString_BDA7865B17FB.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
