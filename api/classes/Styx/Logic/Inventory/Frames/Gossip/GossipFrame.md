# GossipFrame Class

Handles the gossip/dialog frame with NPCs.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Inventory.Frames.Frame
    Styx.Logic.Inventory.Frames.Gossip.GossipFrame

## Namespace
[Styx.Logic.Inventory.Frames.Gossip](../../../../../../namespaces/Styx/Logic/Inventory/Frames/Gossip.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GossipFrame : Frame
```

The GossipFrame type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GossipFrame](GossipFrame/Constructors/Constructor_DCF74044DE43.md) | Initializes a new instance of the GossipFrame class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](GossipFrame/Fields/Instance_389A84B72F6F.md) | Singleton instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ActiveQuests](GossipFrame/Properties/ActiveQuests_6854B6FB6897.md) | Gets list of active (turn-in) quests from the NPC. |
| Public property | [AvailableQuests](GossipFrame/Properties/AvailableQuests_3A0E94D3798C.md) | Gets list of available quests from the NPC. |
| Public property | [GossipOptionEntries](GossipFrame/Properties/GossipOptionEntries_6E661D5A8BA2.md) | Gets list of gossip options. |
| Public property | [GossipText](GossipFrame/Properties/GossipText_419B40C5B76C.md) | Gets the gossip text. |
| Public property | [FrameName](../Frame/Properties/FrameName_395BA5AE7FD3.md) | The name of the frame in the WoW UI. (Inherited from Frame.) |
| Public property | [IsVisible](../Frame/Properties/IsVisible_9F5D19E4F04B.md) | Whether the frame is currently visible. (Inherited from Frame.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Close](GossipFrame/Methods/Close_D981A5D66ABA.md) | Closes the gossip frame. |
| Public method | [Hide](GossipFrame/Methods/Hide_1A1416D337DE.md) | Hides the gossip frame. |
| Public method | [SelectActiveQuest(int)](GossipFrame/Methods/SelectActiveQuest_22AC2C3452AE.md) | Selects an active quest by index. |
| Public method | [SelectAvailableQuest(int)](GossipFrame/Methods/SelectAvailableQuest_D937AA29E0AE.md) | Selects an available quest by index. |
| Public method | [SelectGossipOption(int)](GossipFrame/Methods/SelectGossipOption_63BFAD6A6C08.md) | Selects a gossip option by index. |
| Public method | [Show](../Frame/Methods/Show_24F916F5163E.md) | Shows the frame. (Inherited from Frame.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory.Frames.Gossip Namespace](../../../../../../namespaces/Styx/Logic/Inventory/Frames/Gossip.md)
