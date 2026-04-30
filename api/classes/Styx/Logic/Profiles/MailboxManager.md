# MailboxManager Class

Manages mailbox locations from profiles.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.MailboxManager

## Namespace
[Styx.Logic.Profiles](../../../../namespaces/Styx/Logic/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class MailboxManager
```

The MailboxManager type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [MailboxManager](MailboxManager/Constructors/Constructor_D4F8F3C29B51.md) | Creates an empty mailbox manager. |
| Public constructor | [MailboxManager(XElement)](MailboxManager/Constructors/Constructor_B4E133B963ED.md) | Creates a mailbox manager from XML. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AllMailboxes](MailboxManager/Properties/AllMailboxes_5F66229B934E.md) | Gets all mailboxes in the profile. |
| Public property | [Blacklist](MailboxManager/Properties/Blacklist_E9595366E3B9.md) | Gets blacklisted mailboxes. |
| Public property | [ForcedMailboxes](MailboxManager/Properties/ForcedMailboxes_85225A58F314.md) | Gets or sets forced mailboxes that override profile mailboxes. |
| Public property | [Mailboxes](MailboxManager/Properties/Mailboxes_FF1CA7777C8E.md) | Gets mailboxes excluding blacklisted ones. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetClosestMailbox](MailboxManager/Methods/GetClosestMailbox_9987355F8E16.md) | Gets the closest mailbox to the player. |
| Public method | [GetClosestMailbox(WoWPoint)](MailboxManager/Methods/GetClosestMailbox_7524A9C3C8ED.md) | Gets the closest mailbox to a location. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles Namespace](../../../../namespaces/Styx/Logic/Profiles.md)
