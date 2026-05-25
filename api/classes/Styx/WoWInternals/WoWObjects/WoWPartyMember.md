# WoWPartyMember Class

Represents a party/raid member. WotLK 3.3.5a implementation using Lua calls.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWPartyMember

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWPartyMember : IEquatable<WoWPartyMember>
```

The WoWPartyMember type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [WoWPartyMember.GroupRole](WoWPartyMember/GroupRole.md) | Group role flags. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWPartyMember(ulong, bool)](WoWPartyMember/Constructors/Constructor_F0E4693C778E.md) | Creates a party member from a GUID. |
| Public constructor | [WoWPartyMember(string, int, bool)](WoWPartyMember/Constructors/Constructor_160A94F282DB.md) | Creates a party member from a unit ID. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AFKFlagged](WoWPartyMember/Properties/AFKFlagged_5575AA2CF5EC.md) | Returns true if this member is AFK. |
| Public property | [AreaTableId](WoWPartyMember/Properties/AreaTableId_0301DEBDDE7F.md) | Gets the zone area ID. |
| Public property | [Class](WoWPartyMember/Properties/Class_73C25A023E67.md) | Gets the class. |
| Public property | [ContinentId](WoWPartyMember/Properties/ContinentId_FA6EA94D2C2F.md) | Gets the continent ID for this party member. Ported from HB 4.3.4 WoWPartyMember.ContinentId (memory struct field). WotLK Lua has no per-unit continent API; returns 0 as a safe stub. |
| Public property | [DNDFlagged](WoWPartyMember/Properties/DNDFlagged_8E17BA83E611.md) | Returns true if this member is DND. |
| Public property | [Dead](WoWPartyMember/Properties/Dead_105713CE9F16.md) | Returns true if this member is dead. |
| Public property | [FFAPvpFlagged](WoWPartyMember/Properties/FFAPvpFlagged_69F491EB40C0.md) | Gets a value indicating whether ffa pvp flagged. |
| Public property | [Ghost](WoWPartyMember/Properties/Ghost_C836B682C58B.md) | Returns true if this member is a ghost. |
| Public property | [GroupLeader](WoWPartyMember/Properties/GroupLeader_BE50F859122E.md) | Returns true if this member is the group leader. |
| Public property | [GroupNumber](WoWPartyMember/Properties/GroupNumber_F49820DB2D49.md) | Gets the raid subgroup number (1-8). |
| Public property | [Guid](WoWPartyMember/Properties/Guid_12D3252FCCD5.md) | Gets the GUID of this party member. |
| Public property | [Health](WoWPartyMember/Properties/Health_7D8769824BD8.md) | Gets the current health. |
| Public property | [HealthMax](WoWPartyMember/Properties/HealthMax_BED512601229.md) | Gets the maximum health. |
| Public property | [HealthPercent](WoWPartyMember/Properties/HealthPercent_3243BB0CE6BB.md) | Gets the health percentage. |
| Public property | [IsHealer](WoWPartyMember/Properties/IsHealer_5F6C4823FC92.md) | Returns true if this member is a healer. |
| Public property | [IsMainAssist](WoWPartyMember/Properties/IsMainAssist_094DAA11159F.md) | Returns true if this member is the main assist. |
| Public property | [IsMainTank](WoWPartyMember/Properties/IsMainTank_A9B9045EA116.md) | Returns true if this member is the main tank. |
| Public property | [IsOnline](WoWPartyMember/Properties/IsOnline_E5C8C0451B03.md) | Returns true if this member is online. |
| Public property | [IsTank](WoWPartyMember/Properties/IsTank_C9515E7BB366.md) | Returns true if this member is a tank (main tank or assigned tank role). |
| Public property | [Level](WoWPartyMember/Properties/Level_3458374E098C.md) | Gets the level. |
| Public property | [Location](WoWPartyMember/Properties/Location_1C227F3457D3.md) | Gets the location. |
| Public property | [Location3D](WoWPartyMember/Properties/Location3D_02F0D3C44379.md) | Gets the member's location. |
| Public property | [Name](WoWPartyMember/Properties/Name_21C704F344D2.md) | Gets the name of this party member. |
| Public property | [Power](WoWPartyMember/Properties/Power_BFFA476416B9.md) | Gets the current power (mana/rage/energy). |
| Public property | [PowerMax](WoWPartyMember/Properties/PowerMax_7BF667408631.md) | Gets the maximum power. |
| Public property | [PowerType](WoWPartyMember/Properties/PowerType_DE0AC84B6ADE.md) | Gets the power type. |
| Public property | [PvpFlagged](WoWPartyMember/Properties/PvpFlagged_F6AD4B1C6C0C.md) | Returns true if this member is flagged for PvP. |
| Public property | [RaidRank](WoWPartyMember/Properties/RaidRank_A382C2FA2687.md) | Gets the raid rank (0=member, 1=assist, 2=leader). |
| Public property | [Role](WoWPartyMember/Properties/Role_571D18D88045.md) | Gets the assigned role in LFG (WotLK 3.3.5a: UnitGroupRolesAssigned available since patch 3.3.0). Falls back to manual MT/MA assignment. |
| Public property | [UnitId](WoWPartyMember/Properties/UnitId_DD0115FFFCF7.md) | Gets the unit ID used for Lua calls. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Equals(WoWPartyMember)](WoWPartyMember/Methods/Equals_3802CE0195D2.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](WoWPartyMember/Methods/Equals_940DB24A38CC.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().) |
| Public method Static member | [FromPartyIndex(int)](WoWPartyMember/Methods/FromPartyIndex_229CAD408AC8.md) | Creates a WoWPartyMember from a party index (1-4). |
| Public method Static member | [FromRaidIndex(int)](WoWPartyMember/Methods/FromRaidIndex_800828622E86.md) | Creates a WoWPartyMember from a raid index (1-40). |
| Public method | [GetHashCode](WoWPartyMember/Methods/GetHashCode_537FADA51197.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().) |
| Public method | [HasRole(GroupRole)](WoWPartyMember/Methods/HasRole_0B1618C9EF36.md) | Returns true if the member has the specified role. |
| Public method | [ToPlayer](WoWPartyMember/Methods/ToPlayer_3D095BD62021.md) | Converts this party member to a WoWPlayer if in range. |
| Public method | [ToString](WoWPartyMember/Methods/ToString_3A0F936CC0D5.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
