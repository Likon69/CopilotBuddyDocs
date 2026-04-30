# MailFrame Class

Mailbox frame wrapper for WoW.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Inventory.Frames.Frame
    Styx.Logic.Inventory.Frames.MailBox.MailFrame

## Namespace
[Styx.Logic.Inventory.Frames.MailBox](../../../../../../namespaces/Styx/Logic/Inventory/Frames/MailBox.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class MailFrame : Frame
```

The MailFrame type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [MailFrame](MailFrame/Constructors/Constructor_902C9E4DA9C7.md) | Initializes a new instance of the MailFrame class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](MailFrame/Fields/Instance_8F677BFA6A0C.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [HasNewMail](MailFrame/Properties/HasNewMail_FB3C4926E70F.md) | Gets whether there is new mail. |
| Public property | [MailCount](MailFrame/Properties/MailCount_D57999B9A447.md) | Gets the number of mail items in the inbox. |
| Public property | [SendMailItemGuids](MailFrame/Properties/SendMailItemGuids_E7A87D5B6116.md) | FEAT-33: Gets the GUIDs of items currently attached to the outgoing mail. Uses Lua to check ITEM_QUALITY_COLORS-based attachment slots (max 12 slots in WotLK). |
| Public property | [SendMailItems](MailFrame/Properties/SendMailItems_A98D4F1982A3.md) | FEAT-33: Gets the WoWItem objects attached to the outgoing mail. |
| Public property | [FrameName](../Frame/Properties/FrameName_395BA5AE7FD3.md) | The name of the frame in the WoW UI. (Inherited from Frame.) |
| Public property | [IsVisible](../Frame/Properties/IsVisible_9F5D19E4F04B.md) | Whether the frame is currently visible. (Inherited from Frame.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Close](MailFrame/Methods/Close_5F50AC4106D8.md) | Closes the mail frame. |
| Public method | [DeleteMail(int)](MailFrame/Methods/DeleteMail_AF7E89250ACB.md) | Deletes a mail item. |
| Public method | [GetMailAttachments(int)](MailFrame/Methods/GetMailAttachments_7C8727259DEB.md) | Gets all attachments from a mail item. |
| Public method | [Hide](MailFrame/Methods/Hide_6D297ADEA118.md) | Hides the mail frame. |
| Public method | [OpenAllMail](MailFrame/Methods/OpenAllMail_7E07D9CB71E9.md) | Opens all mail and collects attachments. |
| Public method | [OpenAllMailFrom(string)](MailFrame/Methods/OpenAllMailFrom_14ACCCFFBC49.md) | Opens all mail from a specific sender. |
| Public method | [ReturnMail(int)](MailFrame/Methods/ReturnMail_00240720A4A0.md) | Returns a mail item to sender. |
| Public method | [SendMail(string, string, string, int, WoWItem[])](MailFrame/Methods/SendMail_1C83CE2938DE.md) | Sends a mail with attachments. |
| Public method | [SendMailWithManyAttachments(string, int, WoWItem[])](MailFrame/Methods/SendMailWithManyAttachments_795FF1648123.md) | Sends a mail with many attachments (splits into multiple mails if needed). |
| Public method | [SwitchToSendMailTab](MailFrame/Methods/SwitchToSendMailTab_9E3CC5E14A54.md) | Switches to the send mail tab. |
| Public method | [Show](../Frame/Methods/Show_24F916F5163E.md) | Shows the frame. (Inherited from Frame.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory.Frames.MailBox Namespace](../../../../../../namespaces/Styx/Logic/Inventory/Frames/MailBox.md)
