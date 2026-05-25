# Bots.Gatherbuddy Namespace

Contains the gather bot implementation and related support types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [BagHelper](../../classes/Bots/Gatherbuddy/BagHelper.md) | Counts free bag slots restricted to the bag families relevant to each gather type. Port of HB 4.3.4 Bots.GatherBuddy.BagHelper. Normal bags (BagType.Normal) can hold anything, so they always count. Mining bags (BagType.Mining) only hold minerals — they count for mine slots, not herb slots. Herb bags (BagType.Herb) only hold herbs — they count for herb slots, not mine slots. |
| Public class | [GatherBuddySettingsViewModel](../../classes/Bots/Gatherbuddy/GatherBuddySettingsViewModel.md) | ViewModel wrapping GatherBuddySettings for WPF binding. Slider values need double binding (WPF Slider uses double), while Settings uses int — this bridges the gap. |
| Public class | [GatherBuddySettingsWindow](../../classes/Bots/Gatherbuddy/GatherBuddySettingsWindow.md) | Settings window for GatherBuddy — WPF dark theme matching CB style. Bound to GatherBuddySettings.Instance via a ViewModel wrapper. Tab 1: General settings. Tab 2: Node Selection (herb/mineral checkboxes). |
| Public class | [GatherableNode](../../classes/Bots/Gatherbuddy/GatherableNode.md) | Represents a gatherable resource node (herb or mineral) in WoW 3.3.5a. |
| Public class | [GatherableNodes](../../classes/Bots/Gatherbuddy/GatherableNodes.md) | Defines the herb and mining node data used by GatherBuddy. |
| Public class | [GatherbuddyBot](../../classes/Bots/Gatherbuddy/GatherbuddyBot.md) | The main gatherbuddy bot implementation. |
| Public class | [GatherbuddySettings](../../classes/Bots/Gatherbuddy/GatherbuddySettings.md) | Persistent settings for GatherBuddy. Saved to Settings/GatherBuddySettings_{Name}.xml Pattern from HB 3.3.5a. |
| Public class | [NodeSelectionItem](../../classes/Bots/Gatherbuddy/NodeSelectionItem.md) | Represents a single herb/mineral checkbox item in the Node Selection tab. |
| Public class | [NodeTracker](../../classes/Bots/Gatherbuddy/NodeTracker.md) | Manages tracking of harvested and blacklisted nodes. Prevents returning to already-harvested nodes before respawn. FEAT-40: Added persistent blacklist save/load. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [PathType](../../classes/Bots/Gatherbuddy/PathType.md) | Type of waypoint traversal pattern |

## See Also
[Namespace Index](../../index.md)
