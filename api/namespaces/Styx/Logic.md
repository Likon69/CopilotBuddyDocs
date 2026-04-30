# Styx.Logic Namespace

Contains core gameplay logic types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [AlteracValleyLandmark](../../classes/Styx/Logic/AlteracValleyLandmark.md) | Represents an alterac valley landmark. |
| Public class | [ArathiBasinLandmark](../../classes/Styx/Logic/ArathiBasinLandmark.md) | Represents an arathi basin landmark. |
| Public class | [BattleForGilneasLandmark](../../classes/Styx/Logic/BattleForGilneasLandmark.md) | Represents a battle for gilneas landmark. |
| Public class | [Battlegrounds](../../classes/Styx/Logic/Battlegrounds.md) | FEAT-35: Battlegrounds management for 3.3.5a WotLK. Expanded from stub — uses Lua API for queue management. Ported from HB 4.3.4 Battlegrounds.cs. |
| Public class | [Blacklist](../../classes/Styx/Logic/Blacklist.md) | Represents a blacklist. |
| Public class | [BuyItemsEventArgs](../../classes/Styx/Logic/BuyItemsEventArgs.md) | Event args for buying items. |
| Public class | [EyeOfTheStormLandmark](../../classes/Styx/Logic/EyeOfTheStormLandmark.md) | Represents an eye of the storm landmark. |
| Public class | [FlightPaths](../../classes/Styx/Logic/FlightPaths.md) | FlightPaths - Manages taxi/flight path learning and usage Ported from HB 4.3.4 |
| Public class | [IsleOfConquestLandmark](../../classes/Styx/Logic/IsleOfConquestLandmark.md) | Represents an isle of conquest landmark. |
| Public class | [Landmarks](../../classes/Styx/Logic/Landmarks.md) | Manages map landmarks/POIs for 3.3.5a Offsets: NumMapLandmarks at 12488416 (0x00BE8260), LandmarkArray at 12488476 (0x00BE829C) |
| Public class | [LootTargeting](../../classes/Styx/Logic/LootTargeting.md) | Represents a loot targeting. |
| Public class | [MailItemsEventArgs](../../classes/Styx/Logic/MailItemsEventArgs.md) | Event args for mail items operation |
| Public class | [Mount](../../classes/Styx/Logic/Mount.md) | Represents a mount. |
| Public class | [MountHelper](../../classes/Styx/Logic/MountHelper.md) | Helper class for managing player mounts. |
| Public class | [MountHelper.MountWrapper](../../classes/Styx/Logic/MountHelper/MountWrapper.md) | Wrapper class for mount information. |
| Public class | [MountUpEventArgs](../../classes/Styx/Logic/MountUpEventArgs.md) | Event arguments for mount up events (HB 4.3.4 compatibility). |
| Public class | [RaFHelper](../../classes/Styx/Logic/RaFHelper.md) | Recruit-A-Friend helper for 3.3.5a |
| Public class | [SellItemsEventArgs](../../classes/Styx/Logic/SellItemsEventArgs.md) | Event args for selling items to vendor |
| Public class | [SequenceManager](../../classes/Styx/Logic/SequenceManager.md) | Manages bot action sequences with override support |
| Public class | [SotAGate](../../classes/Styx/Logic/SotAGate.md) | Strand of the Ancients gate (specialized landmark) |
| Public class | [StrandOfTheAncientsLandmark](../../classes/Styx/Logic/StrandOfTheAncientsLandmark.md) | Represents a strand of the ancients landmark. |
| Public class | [Targeting](../../classes/Styx/Logic/Targeting.md) | Represents a targeting. |
| Public class | [Targeting.TargetPriority](../../classes/Styx/Logic/Targeting/TargetPriority.md) | Represents a target priority. |
| Public class | [TaxiNodeInfo](../../classes/Styx/Logic/TaxiNodeInfo.md) | TaxiNodeInfo - Represents a flight path node from TaxiNodes.dbc Contains world location, name, and faction-specific mount information |
| Public class | [Vendors](../../classes/Styx/Logic/Vendors.md) | Provides functionality for interacting with vendors, trainers, and mailboxes. |
| Public class | [WoWLandMark](../../classes/Styx/Logic/WoWLandMark.md) | Represents a landmark/POI in WoW 3.3.5a (AreaPOI) |
| Public class | [WoWSkill](../../classes/Styx/Logic/WoWSkill.md) | Represents a skill known by the player. Ported from HonorBuddy 3.3.5a. |
| Public class | [XmlFlightNode](../../classes/Styx/Logic/XmlFlightNode.md) | Flight node data from XML |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [QueuedBattlegroundInfo](../../classes/Styx/Logic/QueuedBattlegroundInfo.md) | Battleground queue information structure for 3.3.5a |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [AlteracValleyLandmarkType](../../classes/Styx/Logic/AlteracValleyLandmarkType.md) | Represents values for Alterac Valley Landmark Type. |
| Public enumeration | [ArathiBasinLandmarkType](../../classes/Styx/Logic/ArathiBasinLandmarkType.md) | Represents values for Arathi Basin Landmark Type. |
| Public enumeration | [ArenaType](../../classes/Styx/Logic/ArenaType.md) | Arena types for WoW 3.3.5a |
| Public enumeration | [BattleForGilneasLandmarkType](../../classes/Styx/Logic/BattleForGilneasLandmarkType.md) | Represents values for Battle For Gilneas Landmark Type. |
| Public enumeration | [BattlefieldWinner](../../classes/Styx/Logic/BattlefieldWinner.md) | Battleground winner enum for 3.3.5a |
| Public enumeration | [BattlegroundJoinError](../../classes/Styx/Logic/BattlegroundJoinError.md) | Battleground join error codes for 3.3.5a |
| Public enumeration | [BattlegroundSide](../../classes/Styx/Logic/BattlegroundSide.md) | Battleground faction side for 3.3.5a |
| Public enumeration | [BattlegroundStatus](../../classes/Styx/Logic/BattlegroundStatus.md) | Battleground queue/instance status for 3.3.5a |
| Public enumeration | [BattlegroundType](../../classes/Styx/Logic/BattlegroundType.md) | Battleground types for WoW 3.3.5a |
| Public enumeration | [BotSequence](../../classes/Styx/Logic/BotSequence.md) | Bot action sequence types for 3.3.5a Note: Renamed from Sequence to BotSequence to avoid conflict with TreeSharp.Sequence |
| Public enumeration | [DestroyedGateFlags](../../classes/Styx/Logic/DestroyedGateFlags.md) | Strand of the Ancients destroyed gate flags (bitmask) |
| Public enumeration | [EyeOfTheStormLandmarkType](../../classes/Styx/Logic/EyeOfTheStormLandmarkType.md) | Represents values for Eye Of The Storm Landmark Type. |
| Public enumeration | [FlightPathReason](../../classes/Styx/Logic/FlightPathReason.md) | Reason for flight path action |
| Public enumeration | [Iconflags](../../classes/Styx/Logic/Iconflags.md) | Icon display flags for AreaPOI |
| Public enumeration | [IsleOfConquestLandmarkType](../../classes/Styx/Logic/IsleOfConquestLandmarkType.md) | Represents values for Isle Of Conquest Landmark Type. |
| Public enumeration | [LandmarkControlType](../../classes/Styx/Logic/LandmarkControlType.md) | Represents values for Landmark Control Type. |
| Public enumeration | [LandmarkType](../../classes/Styx/Logic/LandmarkType.md) | Represents values for Landmark Type. |
| Public enumeration | [MountType](../../classes/Styx/Logic/MountType.md) | Represents values for Mount Type. |
| Public enumeration | [SotAGateType](../../classes/Styx/Logic/SotAGateType.md) | Strand of the Ancients gate types |
| Public enumeration | [SotAObjective](../../classes/Styx/Logic/SotAObjective.md) | Strand of the Ancients objective type |
| Public enumeration | [SotaLandmarks](../../classes/Styx/Logic/SotaLandmarks.md) | Strand of the Ancients landmark IDs for 3.3.5a |
| Public enumeration | [StrandOfTheAncientsLandmarkType](../../classes/Styx/Logic/StrandOfTheAncientsLandmarkType.md) | Represents values for Strand Of The Ancients Landmark Type. |

## Delegates

| | Name | Description |
| --- | --- | --- |
| Public delegate | [BuyItemsEventHandler](../../classes/Styx/Logic/BuyItemsEventHandler.md) | Event handler delegate for buying items from vendor. |
| Public delegate | [CanMountDelegate](../../classes/Styx/Logic/CanMountDelegate.md) | Delegate for checking if mount is allowed |
| Public delegate | [IncludeTargetsFilterDelegate](../../classes/Styx/Logic/IncludeTargetsFilterDelegate.md) | Represents a delegate for include targets filter. |
| Public delegate | [LocationRetriever](../../classes/Styx/Logic/LocationRetriever.md) | Represents a delegate for Location Retriever. |
| Public delegate | [MailItemsEventHandler](../../classes/Styx/Logic/MailItemsEventHandler.md) | Event handler delegate for mail items |
| Public delegate | [Mount.CanMountDelegate](../../classes/Styx/Logic/Mount/CanMountDelegate.md) | Represents a delegate for can mount. |
| Public delegate | [RemoveTargetsFilterDelegate](../../classes/Styx/Logic/RemoveTargetsFilterDelegate.md) | Represents a delegate for remove targets filter. |
| Public delegate | [TargetListUpdateFinishedDelegate](../../classes/Styx/Logic/TargetListUpdateFinishedDelegate.md) | Delegate that is called when the target list update finishes. |
| Public delegate | [VendorItemsEventHandler](../../classes/Styx/Logic/VendorItemsEventHandler.md) | Event handler delegate for vendor items |
| Public delegate | [WeighTargetsDelegate](../../classes/Styx/Logic/WeighTargetsDelegate.md) | Represents a delegate for weigh targets. |

## See Also
[Namespace Index](../../index.md)
