# MailFrame.SendMailWithManyAttachments Method

Sends a mail with many attachments (splits into multiple mails if needed).

## Namespace
[Styx.Logic.Inventory.Frames.MailBox](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/MailBox.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public void SendMailWithManyAttachments(string recipient, int copper, params WoWItem[] attachments)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| recipient | string | The recipient. |
| copper | int | The copper. |
| attachments | [WoWItem](../../../../../../WoWInternals/WoWObjects/WoWItem.md)[] | The attachments. |

## See Also
[MailFrame Class](../../MailFrame.md)
[Styx.Logic.Inventory.Frames.MailBox Namespace](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/MailBox.md)
