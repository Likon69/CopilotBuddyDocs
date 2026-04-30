# Profile Class

Represents a profile profile.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Profiles.Profile

## Namespace
[Styx.Logic.Profiles](../../../../namespaces/Styx/Logic/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Profile : IEquatable<Profile>
```

The Profile type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Profile](Profile/Constructors/Constructor_5A86E4E74C32.md) | Initializes a new instance of the Profile class. |
| Public constructor | [Profile(string, Profile)](Profile/Constructors/Constructor_5450B74EFF3B.md) | Initializes a new instance of the Profile class. |
| Public constructor | [Profile(XContainer, Profile)](Profile/Constructors/Constructor_1DAD126557A2.md) | Initializes a new instance of the Profile class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AvoidMobs](Profile/Properties/AvoidMobs_2308268CD642.md) | Gets mobs that should be avoided. Falls back to parent profile if empty. |
| Public property | [Blackspots](Profile/Properties/Blackspots_6D800B1B86FF.md) | Gets blackspot areas to avoid. Falls back to parent profile if empty. |
| Public property | [ContinentId](Profile/Properties/ContinentId_261CA66FDF9F.md) | Map ID this profile is for. -1 = any continent. BUG-10: HB 4.3.4 uses ContinentId to filter profiles by map. |
| Public property | [Factions](Profile/Properties/Factions_079161419DB3.md) | Faction IDs to target. Inherits from parent if empty. |
| Public property | [FilePath](Profile/Properties/FilePath_73352FA994CE.md) | Gets the file path. |
| Public property | [ForceMail](Profile/Properties/ForceMail_CE992B4BDA58.md) | Gets items that should be force-mailed. Falls back to parent profile if empty. |
| Public property | [GrindArea](Profile/Properties/GrindArea_B08F2E965F5F.md) | Gets or sets the grind area. |
| Public property | [HotspotManager](Profile/Properties/HotspotManager_CD8AD3F6D288.md) | Gets or sets the hotspot manager. |
| Public property | [MailBlue](Profile/Properties/MailBlue_71A42C17C49A.md) | Whether to mail blue (rare) quality items. |
| Public property | [MailGreen](Profile/Properties/MailGreen_C400651F5B01.md) | Whether to mail green (uncommon) quality items. |
| Public property | [MailGrey](Profile/Properties/MailGrey_7946BD82BD88.md) | Whether to mail grey quality items. |
| Public property | [MailPurple](Profile/Properties/MailPurple_F77C7EE6076F.md) | Whether to mail purple (epic) quality items. |
| Public property | [MailQualities](Profile/Properties/MailQualities_5185F0458817.md) | Gets the list of item qualities that should be mailed. |
| Public property | [MailWhite](Profile/Properties/MailWhite_C1E3AC32F358.md) | Whether to mail white (common) quality items. |
| Public property | [MailboxManager](Profile/Properties/MailboxManager_1E8E5235E710.md) | Gets the mailbox manager for this profile. Falls back to parent profile. |
| Public property | [MaxLevel](Profile/Properties/MaxLevel_8A2A7294D5F0.md) | Gets or sets the max level. |
| Public property | [MinDurability](Profile/Properties/MinDurability_D7980C9E106E.md) | Gets the minimum durability percentage before repairing. Defaults to 0.4 (40%) if not set. |
| Public property | [MinFreeBagSlots](Profile/Properties/MinFreeBagSlots_D8526F42280D.md) | Gets the minimum free bag slots before selling. Defaults to 0 if not set. |
| Public property | [MinLevel](Profile/Properties/MinLevel_E91AC9364B27.md) | Gets or sets the min level. |
| Public property | [MinMailLevel](Profile/Properties/MinMailLevel_A2BEACF90DB6.md) | Gets the minimum level required to send mail. Defaults to 5 if not set. |
| Public property | [Name](Profile/Properties/Name_8546506CF2BD.md) | Gets or sets the name. |
| Public property | [Parent](Profile/Properties/Parent_16B403EF3766.md) | Gets or sets the parent. |
| Public property | [ProtectedItems](Profile/Properties/ProtectedItems_E55F31ABCA1D.md) | Gets protected items that should not be sold or mailed. Falls back to parent profile if empty. |
| Public property | [QuestBlacklist](Profile/Properties/QuestBlacklist_642A3EC31B75.md) | Blacklisted quest IDs. Quests in this set should be skipped. Inherits from parent if empty. |
| Public property | [QuestGiverBlacklist](Profile/Properties/QuestGiverBlacklist_19AAED482F73.md) | Blacklisted quest giver NPC IDs. NPCs in this set should not be interacted with for quests. Inherits from parent if empty. |
| Public property | [QuestOrder](Profile/Properties/QuestOrder_23149C5E6254.md) | Gets the quest order nodes for this profile. Falls back to parent profile if empty. |
| Public property | [Quests](Profile/Properties/Quests_A7BAA0FA460E.md) | Gets quest info objects defined in this profile. Falls back to parent profile if empty. |
| Public property | [SellBlue](Profile/Properties/SellBlue_6F7E01A67905.md) | Whether to sell blue (rare) quality items. Defaults to false. |
| Public property | [SellGreen](Profile/Properties/SellGreen_39F1A977C976.md) | Whether to sell green (uncommon) quality items. Defaults to false. |
| Public property | [SellGrey](Profile/Properties/SellGrey_834BC22A03B5.md) | Whether to sell grey quality items. Defaults to true. |
| Public property | [SellPurple](Profile/Properties/SellPurple_7ACD9881CD58.md) | Whether to sell purple (epic) quality items. Defaults to false. |
| Public property | [SellWhite](Profile/Properties/SellWhite_D5D84BC4EF2C.md) | Whether to sell white (common) quality items. Defaults to false. |
| Public property | [SubProfiles](Profile/Properties/SubProfiles_DCB15023908E.md) | Gets the sub profiles. |
| Public property | [TargetElites](Profile/Properties/TargetElites_83B4752B8469.md) | Gets whether to target elite mobs. Falls back to parent profile or false. |
| Public property | [TargetElitesValue](Profile/Properties/TargetElitesValue_28FB92EB22E3.md) | Whether to target elite mobs. If not set, inherits from parent profile. |
| Public property | [TargetMaxLevel](Profile/Properties/TargetMaxLevel_2C1790BF07A1.md) | Deprecated: target maximum level moved to GrindArea. Kept for backward compatibility with old profiles. |
| Public property | [TargetMinLevel](Profile/Properties/TargetMinLevel_F8E9BF32DA58.md) | Deprecated: target minimum level moved to GrindArea. Kept for backward compatibility with old profiles. |
| Public property | [VendorManager](Profile/Properties/VendorManager_DEB432A186C7.md) | Gets the vendor manager for this profile. Falls back to parent profile or creates empty one. |
| Public property | [XmlElement](Profile/Properties/XmlElement_29ABE909AE5F.md) | Gets the xml element. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnUnknownProfileElement](Profile/Events/OnUnknownProfileElement_E461AE4A3312.md) | Occurs when unknown profile element. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Equals(Profile)](Profile/Methods/Equals_077D4D176103.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](Profile/Methods/Equals_75FCC9589D94.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().) |
| Public method | [FindQuest(uint)](Profile/Methods/FindQuest_2B8CE088D777.md) | Finds quest info by ID. |
| Public method | [GetHashCode](Profile/Methods/GetHashCode_30FFCD6EAC17.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().) |
| Public method | [GetRootProfile](Profile/Methods/GetRootProfile_BD0FA29A3A55.md) | Gets the root profile in the hierarchy. |
| Public method | [GetScopeSortedProfiles](Profile/Methods/GetScopeSortedProfiles_7851D826EC43.md) | Gets the scope sorted profiles. |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles Namespace](../../../../namespaces/Styx/Logic/Profiles.md)
