# Bots.Gatherbuddy Namespace

Contains the gather bot implementation and related support types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [GatherBuddySettings](../../classes/Bots/Gatherbuddy/GatherBuddySettings.md) | Represents persistent settings for GatherBuddy. |
| Public class | [GatherBuddySettingsViewModel](../../classes/Bots/Gatherbuddy/GatherBuddySettingsViewModel.md) | ViewModel wrapping GatherBuddySettings for WPF binding. Slider values need double binding (WPF Slider uses double), while Settings uses int — this bridges the gap. |
| Public class | [GatherBuddySettingsWindow](../../classes/Bots/Gatherbuddy/GatherBuddySettingsWindow.md) | Settings window for GatherBuddy — WPF dark theme matching CB style. Bound to GatherBuddySettings.Instance via a ViewModel wrapper. Tab 1: General settings. Tab 2: Node Selection (herb/mineral checkboxes). |
| Public class | [GatherableNode](../../classes/Bots/Gatherbuddy/GatherableNode.md) | Represents a gatherable resource node (herb or mineral) in WoW 3.3.5a. |
| Public class | [GatherableNodes](../../classes/Bots/Gatherbuddy/GatherableNodes.md) | Defines the herb and mining node data used by GatherBuddy. |
| Public class | [GatherbuddyBot](../../classes/Bots/Gatherbuddy/GatherbuddyBot.md) | GatherBuddy - Full-featured gathering bot for WoW 3.3.5a (WotLK). Harvests herbs, minerals, chests, skins mobs along a waypoint route. Supports profile vendors, mailboxes, blackspots, sell/mail quality filters, full combat behaviors, death handling with spirit healer, and session timers. |
| Public class | [NodeSelectionItem](../../classes/Bots/Gatherbuddy/NodeSelectionItem.md) | Represents a single herb/mineral checkbox item in the Node Selection tab. |
| Public class | [NodeTracker](../../classes/Bots/Gatherbuddy/NodeTracker.md) | Manages tracking of harvested and blacklisted nodes. Prevents returning to already-harvested nodes before respawn. FEAT-40: Added persistent blacklist save/load. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [PathType](../../classes/Bots/Gatherbuddy/PathType.md) | Type of waypoint traversal pattern |

## See Also
[Namespace Index](../../index.md)
