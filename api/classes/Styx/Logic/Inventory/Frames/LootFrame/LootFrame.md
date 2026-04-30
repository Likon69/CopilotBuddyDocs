# LootFrame Class

Handles the loot frame UI and looting operations.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Inventory.Frames.Frame
    Styx.Logic.Inventory.Frames.LootFrame.LootFrame

## Namespace
[Styx.Logic.Inventory.Frames.LootFrame](../../../../../../namespaces/Styx/Logic/Inventory/Frames/LootFrame.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class LootFrame : Frame
```

The LootFrame type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [LootFrame](LootFrame/Constructors/Constructor_C4EC754AA6C4.md) | Initializes a new instance of the LootFrame class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](LootFrame/Fields/Instance_8C268612686F.md) | Singleton instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsVisible](LootFrame/Properties/IsVisible_925CE46E035B.md) | Whether loot frame is visible (has a looting target). |
| Public property | [LootItems](LootFrame/Properties/LootItems_04F5E6800CA3.md) | Number of items available to loot. |
| Public property | [LootingObjectGuid](LootFrame/Properties/LootingObjectGuid_FFD6187DCF3A.md) | GUID of the object being looted. Address: 12560600 (0xBFA8D8) |
| Public property | [FrameName](../Frame/Properties/FrameName_395BA5AE7FD3.md) | The name of the frame in the WoW UI. (Inherited from Frame.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Close](LootFrame/Methods/Close_E6720E8F8A6E.md) | Closes the loot frame. |
| Public method | [GetItemId(int)](LootFrame/Methods/GetItemId_A01DB0A5A950.md) | Gets the item ID at the specified loot slot. Base address: 12560020 (0xBFA694), 32 bytes per slot |
| Public method | [GetLootSlots](LootFrame/Methods/GetLootSlots_D7F29A43D0E1.md) | BUG-21 fix: Returns structured loot slot info array instead of just a string. |
| Public method | [Loot(int)](LootFrame/Methods/Loot_7836CF2FDD34.md) | Loots a specific slot. |
| Public method | [LootAll](LootFrame/Methods/LootAll_88ACCBD353BC.md) | Loots all items and closes the loot frame. |
| Public method | [LootInfo(int)](LootFrame/Methods/LootInfo_5E64DD4A01FF.md) | Returns structured loot slot info for the specified slot (HonorBuddy-compatible). |
| Public method | [LootInfo(bool)](LootFrame/Methods/LootInfo_F61FFD9AB06D.md) | Gets loot information string. |
| Public method | [Hide](../Frame/Methods/Hide_171D97B1DB18.md) | Hides the frame. (Inherited from Frame.) |
| Public method | [Show](../Frame/Methods/Show_24F916F5163E.md) | Shows the frame. (Inherited from Frame.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory.Frames.LootFrame Namespace](../../../../../../namespaces/Styx/Logic/Inventory/Frames/LootFrame.md)
