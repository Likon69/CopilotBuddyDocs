# Battlegrounds Class

FEAT-35: Battlegrounds management for 3.3.5a WotLK. Expanded from stub — uses Lua API for queue management. Ported from HB 4.3.4 Battlegrounds.cs.

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Battlegrounds
```

The Battlegrounds type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [BattlefieldInstanceRunTime](Battlegrounds/Properties/BattlefieldInstanceRunTime_4DBD6E910ADA.md) | How long the current BG has been running. |
| Public property Static member | [BattlefieldStartTime](Battlegrounds/Properties/BattlefieldStartTime_1DB7C937D6C5.md) | The start time of the current battleground instance. |
| Public property Static member | [BattlegroundStatuses](Battlegrounds/Properties/BattlegroundStatuses_4F5DDD5A9C1A.md) | Gets all BG queue statuses. |
| Public property Static member | [Current](Battlegrounds/Properties/Current_C97A3A3F525E.md) | Current battleground type based on MapId. |
| Public property Static member | [Finished](Battlegrounds/Properties/Finished_DD390CDB38E6.md) | Whether the current battleground has finished. Uses Lua GetBattlefieldWinner. |
| Public property Static member | [IsActive](Battlegrounds/Properties/IsActive_9EA420C770E5.md) | Whether bot is active in battleground mode. |
| Public property Static member | [IsInsideBattleground](Battlegrounds/Properties/IsInsideBattleground_E1B2CFBF7C6D.md) | Whether player is inside an active battleground. Computed from queue status — not a manual setter. |
| Public property Static member | [LandMarks](Battlegrounds/Properties/LandMarks_0E99C4A653E6.md) | Landmarks manager for battlegrounds. |
| Public property Static member | [QueuedInfos](Battlegrounds/Properties/QueuedInfos_6FD2374C1B40.md) | Gets queued battleground info for all queue slots (max 2 in WotLK). Uses Lua GetBattlefieldStatus. |
| Public property Static member | [WaitingForConfirmation](Battlegrounds/Properties/WaitingForConfirmation_13CAA3C6EAEF.md) | Whether waiting for a BG confirmation popup. |
| Public property Static member | [Winner](Battlegrounds/Properties/Winner_3CEA3CA2BE9F.md) | The winner of the current/last battleground. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AcceptBattlefieldPort(int, bool)](Battlegrounds/Methods/AcceptBattlefieldPort_E22BDAE9A111.md) | Accepts or declines a battlefield port at the given index. |
| Public method Static member | [AcceptBattlegroundConfirmation](Battlegrounds/Methods/AcceptBattlegroundConfirmation_DBBDA1210A0B.md) | Accepts a pending BG confirmation popup. |
| Public method Static member | [GetBGIndexWithStatus(BattlegroundStatus)](Battlegrounds/Methods/GetBGIndexWithStatus_D0EDEBA7888B.md) | Finds the first queue slot with the given status. Returns -1 if not found, or the 1-based index. |
| Public method Static member | [GetBattlefieldWinner](Battlegrounds/Methods/GetBattlefieldWinner_9BB23AECA54F.md) | Gets the BG winner (Horde=0, Alliance=1). |
| Public method Static member | [GetCurrentBattleground](Battlegrounds/Methods/GetCurrentBattleground_09A5A558FA71.md) | Determines the current battleground type from the player's MapId. WotLK BG map IDs: AV=30, WSG=489, AB=529, EotS=566, SotA=607, IoC=628. |
| Public method Static member | [GetProfileName(BattlegroundType)](Battlegrounds/Methods/GetProfileName_3C6F2AEC8015.md) | Gets a profile name for a BG type. |
| Public method Static member | [GetQueuedBattlegroundInfo(uint)](Battlegrounds/Methods/GetQueuedBattlegroundInfo_FC5D50B469BB.md) | Gets queue info for a specific slot via Lua. Index is 1-based (WoW Lua convention). |
| Public method Static member | [GetQueuedBattlegroundWaitTime(uint)](Battlegrounds/Methods/GetQueuedBattlegroundWaitTime_B75EB88011E4.md) | Gets the wait time for a queued battleground. |
| Public method Static member | [GetStatus(uint)](Battlegrounds/Methods/GetStatus_DD0D4E593636.md) | Gets the queue status for a specific slot. |
| Public method Static member | [IsQueuedForBattleground(BattlegroundType)](Battlegrounds/Methods/IsQueuedForBattleground_5581CA2DB090.md) | Whether the player is queued for a specific BG type. |
| Public method Static member | [JoinBattlefield(BattlegroundType, bool)](Battlegrounds/Methods/JoinBattlefield_30359B1C9303.md) | Joins a battleground queue via Lua. |
| Public method Static member | [LeaveBattlefield](Battlegrounds/Methods/LeaveBattlefield_CB5AC44B6FD9.md) | Leaves the current battleground. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
