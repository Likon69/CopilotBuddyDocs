# WoWItem Class

Represents a wow item.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWItem

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWItem : WoWObject
```

The WoWItem type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [WoWItem.WoWItemEnchantment](WoWItem/WoWItemEnchantment.md) | Represents a wow item enchantment. |
| Public class | [WoWItem.WoWItemRandomProperties](WoWItem/WoWItemRandomProperties.md) | Represents a wow item random properties. |
| Public class | [WoWItem.WoWItemRandomSuffix](WoWItem/WoWItemRandomSuffix.md) | Represents a wow item random suffix. |
| Public class | [WoWItem.WoWItemSpell](WoWItem/WoWItemSpell.md) | Represents a wow item spell. |
| Public class | [WoWItem.WoWItemStat](WoWItem/WoWItemStat.md) | Represents a wow item stat. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWItem(uint)](WoWItem/Constructors/Constructor_B473BFA3CE7E.md) | Initializes a new instance of the WoWItem class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BagIndex](WoWItem/Properties/BagIndex_1C1FD5C007C1.md) | Gets the bag index. |
| Public property | [BagSlot](WoWItem/Properties/BagSlot_0943A117C6C6.md) | Gets the bag slot. |
| Public property | [BuyPrice](WoWItem/Properties/BuyPrice_2B401B95DE99.md) | Gets the buy price. |
| Public property | [CanExpire](WoWItem/Properties/CanExpire_D01DC0BFAEDA.md) | Gets a value indicating whether can expire. |
| Public property | [CanProspect](WoWItem/Properties/CanProspect_AAB7322C4204.md) | Gets a value indicating whether can prospect. |
| Public property | [ContainerGuid](WoWItem/Properties/ContainerGuid_F1725990ABE9.md) | Gets the container guid. |
| Public property | [Cooldown](WoWItem/Properties/Cooldown_8BD68A69B840.md) | Gets the cooldown. |
| Public property | [CooldownTimeLeft](WoWItem/Properties/CooldownTimeLeft_12A2867FC7F0.md) | FEAT-43: Gets the remaining cooldown as a TimeSpan. Uses Lua GetItemCooldown which returns (startTime, duration, isEnabled). |
| Public property | [CreatePlayedTime](WoWItem/Properties/CreatePlayedTime_50C229AEBCE2.md) | Gets the create played time. |
| Public property | [CreatorGuid](WoWItem/Properties/CreatorGuid_B490ECBDF717.md) | Gets the creator guid. |
| Public property | [Distance](WoWItem/Properties/Distance_BFCEF0DACAFC.md) | Gets the distance. (Overrides WoWObject.Distance.) |
| Public property | [Distance2D](WoWItem/Properties/Distance2D_0C847B073F1D.md) | Gets the distance2d. (Overrides WoWObject.Distance2D.) |
| Public property | [Distance2DSqr](WoWItem/Properties/Distance2DSqr_2EAC33BB3E18.md) | Gets the distance2d sqr. (Overrides WoWObject.Distance2DSqr.) |
| Public property | [DistanceSqr](WoWItem/Properties/DistanceSqr_F7BC13E938D6.md) | Gets the distance sqr. (Overrides WoWObject.DistanceSqr.) |
| Public property | [Durability](WoWItem/Properties/Durability_D49DD4C4F7B9.md) | Gets the durability. |
| Public property | [DurabilityPercent](WoWItem/Properties/DurabilityPercent_23C9140CDD77.md) | Gets the durability percent. |
| Public property | [Duration](WoWItem/Properties/Duration_07D7DB0F8932.md) | Gets the duration. |
| Public property | [EquipSlot](WoWItem/Properties/EquipSlot_9D5FAEC8E080.md) | Gets the equip slot. |
| Public property | [Flags](WoWItem/Properties/Flags_3F1E62CFF898.md) | Gets the flags. |
| Public property | [GiftCreatorGuid](WoWItem/Properties/GiftCreatorGuid_2847AB88AFEF.md) | Gets the gift creator guid. |
| Public property | [HasEquipCooldown](WoWItem/Properties/HasEquipCooldown_85F421C499F0.md) | Gets a value indicating whether has equip cooldown. |
| Public property | [IsAccountBound](WoWItem/Properties/IsAccountBound_F3FD658B47F9.md) | Gets a value indicating whether is account bound. |
| Public property | [IsBroken](WoWItem/Properties/IsBroken_FC84F346DAC0.md) | Gets a value indicating whether is broken. |
| Public property | [IsCharter](WoWItem/Properties/IsCharter_93B2737D33A6.md) | Gets a value indicating whether is charter. |
| Public property | [IsConjured](WoWItem/Properties/IsConjured_8D79487B0B4E.md) | Gets a value indicating whether is conjured. |
| Public property | [IsEnchantScroll](WoWItem/Properties/IsEnchantScroll_15E1024E823D.md) | Gets a value indicating whether is enchant scroll. |
| Public property | [IsGift](WoWItem/Properties/IsGift_08858E48A696.md) | Gets a value indicating whether is gift. |
| Public property | [IsGiftWrapped](WoWItem/Properties/IsGiftWrapped_545B17854C96.md) | Gets a value indicating whether is gift wrapped. |
| Public property | [IsMillable](WoWItem/Properties/IsMillable_169820B53F1E.md) | Gets a value indicating whether is millable. |
| Public property | [IsOpenable](WoWItem/Properties/IsOpenable_D92A32A52028.md) | Gets a value indicating whether is openable. |
| Public property | [IsPvPItem](WoWItem/Properties/IsPvPItem_2CDF54AEAF85.md) | Gets a value indicating whether is pv p item. |
| Public property | [IsReadable](WoWItem/Properties/IsReadable_B0BCAD7F9FC3.md) | Gets a value indicating whether is readable. |
| Public property | [IsSoulbound](WoWItem/Properties/IsSoulbound_3A9E99940524.md) | Gets a value indicating whether is soulbound. |
| Public property | [IsThrownWeapon](WoWItem/Properties/IsThrownWeapon_04898B3F7BB3.md) | Gets a value indicating whether is thrown weapon. |
| Public property | [IsTotem](WoWItem/Properties/IsTotem_0D36AFB88BAD.md) | Gets a value indicating whether is totem. |
| Public property | [IsUniqueEquipped](WoWItem/Properties/IsUniqueEquipped_64585DA37F90.md) | Gets a value indicating whether is unique equipped. |
| Public property | [IsWand](WoWItem/Properties/IsWand_5F500A01D2D4.md) | Gets a value indicating whether is wand. |
| Public property | [IsWrappingPaper](WoWItem/Properties/IsWrappingPaper_DF98E24153D5.md) | Gets a value indicating whether is wrapping paper. |
| Public property | [ItemClass](WoWItem/Properties/ItemClass_9BB8A234CD62.md) | Gets the item class. |
| Public property | [ItemInfo](WoWItem/Properties/ItemInfo_9D271E8C3E3A.md) | Gets the item info. |
| Public property | [ItemLevel](WoWItem/Properties/ItemLevel_0293AB3D0B61.md) | Gets the item level. |
| Public property | [ItemSpells](WoWItem/Properties/ItemSpells_E15DA0F361C4.md) | Gets the item spells. |
| Public property | [ItemStats](WoWItem/Properties/ItemStats_008A4D5EAE08.md) | Gets the item stats. |
| Public property | [Link](WoWItem/Properties/Link_497E0D041738.md) | Gets the link. |
| Public property | [Location](WoWItem/Properties/Location_793572F4436B.md) | Gets the location. (Overrides WoWObject.Location.) |
| Public property | [MaxDurability](WoWItem/Properties/MaxDurability_8A71ECBDB0A8.md) | Gets the max durability. |
| Public property | [OwnerGuid](WoWItem/Properties/OwnerGuid_43D2F642A55B.md) | Gets the owner guid. |
| Public property | [PropertySeed](WoWItem/Properties/PropertySeed_054E5E2CAD34.md) | Gets the property seed. |
| Public property | [Quality](WoWItem/Properties/Quality_D1FD24346263.md) | Gets the quality. |
| Public property | [RandomProperties](WoWItem/Properties/RandomProperties_B113215A2A1C.md) | Gets the random properties. |
| Public property | [RandomPropertiesId](WoWItem/Properties/RandomPropertiesId_374B0D497492.md) | Gets the random properties id. |
| Public property | [RandomSuffix](WoWItem/Properties/RandomSuffix_44C2083771D6.md) | Gets the random suffix. |
| Public property | [RequiredLevel](WoWItem/Properties/RequiredLevel_339163773BF8.md) | Gets the required level. |
| Public property | [SellPrice](WoWItem/Properties/SellPrice_53B9B044C4E6.md) | Gets the sell price. |
| Public property | [SpellCharges](WoWItem/Properties/SpellCharges_07E53F6DD11B.md) | Gets the spell charges. |
| Public property | [StackCount](WoWItem/Properties/StackCount_376E0C82DD54.md) | Gets the stack count. |
| Public property | [TemporaryEnchantment](WoWItem/Properties/TemporaryEnchantment_5709BF69039C.md) | Gets the temporary enchantment. |
| Public property | [TriggersSpell](WoWItem/Properties/TriggersSpell_069BC918BFCD.md) | Gets a value indicating whether triggers spell. |
| Public property | [Usable](WoWItem/Properties/Usable_F42ACF492443.md) | Gets a value indicating whether usable. |
| Public property | [X](WoWItem/Properties/X_245E909C7988.md) | Gets the x. (Overrides WoWObject.X.) |
| Public property | [Y](WoWItem/Properties/Y_01CC59EB10EE.md) | Gets the y. (Overrides WoWObject.Y.) |
| Public property | [Z](WoWItem/Properties/Z_F00CF54442D8.md) | Gets the z. (Overrides WoWObject.Z.) |
| Public property | BaseAddress | Gets the base address. (Inherited from WoWObject.) |
| Public property | DescriptorGuid | Gets the descriptor guid. (Inherited from WoWObject.) |
| Public property | Entry | Gets the entry. (Inherited from WoWObject.) |
| Public property | Guid | Gets the guid. (Inherited from WoWObject.) |
| Public property | InLineOfSight | Whether this object is in line of sight from the player. Uses native CGWorldFrame::Intersect raycasting. Ported from HB 4.3.4 WoWObject — WoWUnit overrides with BoundingHeight-aware version. (Inherited from WoWObject.) |
| Public property | InLineOfSightOCD | HB 4.3.4 compat — was marked [Obsolete], just delegates to InLineOfSight. External bots (LazyRaider etc.) reference this. (Inherited from WoWObject.) |
| Public property | InteractRange | Gets the interact range. (Inherited from WoWObject.) |
| Public property | InteractRangeSqr | FEAT-28: Squared interact range for faster distance checks (avoids sqrt). (Inherited from WoWObject.) |
| Public property | InteractType | Gets the interact type. (Inherited from WoWObject.) |
| Public property | IsDisabled | Gets a value indicating whether is disabled. (Inherited from WoWObject.) |
| Public property | IsIndoors | Gets a value indicating whether is indoors. (Inherited from WoWObject.) |
| Public property | IsMe | Gets a value indicating whether is me. (Inherited from WoWObject.) |
| Public property | IsOutdoors | Whether this object is indoors. Override on LocalPlayer uses Lua for accuracy. FEAT-45: Made virtual so LocalPlayer can override. (Inherited from WoWObject.) |
| Public property | IsUnderground | Gets a value indicating whether is underground. (Inherited from WoWObject.) |
| Public property | IsValid | Gets a value indicating whether is valid. (Inherited from WoWObject.) |
| Public property | MeIsBehind | Gets a value indicating whether me is behind. (Inherited from WoWObject.) |
| Public property | MeIsSafelyBehind | Gets a value indicating whether me is safely behind. (Inherited from WoWObject.) |
| Public property | Name | Gets the name. (Inherited from WoWObject.) |
| Public property | ObjectFlags | Gets the object flags. (Inherited from WoWObject.) |
| Public property | QuestGiverStatus | Gets the quest giver status. (Inherited from WoWObject.) |
| Public property | Rotation | Gets the rotation. (Inherited from WoWObject.) |
| Public property | RotationDegrees | Gets the rotation degrees. (Inherited from WoWObject.) |
| Public property | Type | Gets the type. (Inherited from WoWObject.) |
| Public property | TypeFlags | Gets the type flags. (Inherited from WoWObject.) |
| Public property | WithinInteractRange | Gets a value indicating whether within interact range. (Inherited from WoWObject.) |
| Public property | WorldLocation | Alias for Location. Matches HB 4.3.4 API surface used by external plugins. (Inherited from WoWObject.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | OnInvalidate | Occurs when invalidate. (Inherited from WoWObject.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetDamageType(int)](WoWItem/Methods/GetDamageType_ABF68057DD72.md) | Gets the damage type. |
| Public method | [GetEnchantment(string)](WoWItem/Methods/GetEnchantment_A3AF116D0611.md) | Gets the enchantment. |
| Public method | [GetEnchantment(uint)](WoWItem/Methods/GetEnchantment_55CFBD988EA4.md) | Gets the enchantment. |
| Public method | [GetEnchantmentById(uint)](WoWItem/Methods/GetEnchantmentById_E5B19DE5F7D1.md) | Gets the enchantment by id. |
| Public method | [GetItemStats](WoWItem/Methods/GetItemStats_A64A99619A5F.md) | Gets the item stats. |
| Public method | [GetMaxDamage(int)](WoWItem/Methods/GetMaxDamage_F7AB3F8ED550.md) | Gets the max damage. |
| Public method | [GetMinDamage(int)](WoWItem/Methods/GetMinDamage_202876747CEF.md) | Gets the min damage. |
| Public method | [GetSocketColor(int)](WoWItem/Methods/GetSocketColor_B621F877703E.md) | Gets the socket color. |
| Public method | [GetSpell(int)](WoWItem/Methods/GetSpell_07B064857C50.md) | Gets the spell. |
| Public method | [GetStat(int)](WoWItem/Methods/GetStat_2BF2557E6A58.md) | Gets the stat. |
| Public method | [GetStatType(int)](WoWItem/Methods/GetStatType_5E6969E3E355.md) | Gets the stat type. |
| Public method | [GetStatValue(int)](WoWItem/Methods/GetStatValue_ED8FFA1D3880.md) | Gets the stat value. |
| Public method | [Interact](WoWItem/Methods/Interact_D3744D658B17.md) | Interacts with the object. (Overrides WoWObject.Interact().) |
| Public method | [PickUp](WoWItem/Methods/PickUp_4F975B750F5C.md) | Picks up the item. |
| Public method | [ToString](WoWItem/Methods/ToString_DDC1083C2744.md) | Returns a string that represents the current object. (Overrides WoWObject.ToString().) |
| Public method | [Use](WoWItem/Methods/Use_726CB6726F97.md) | Uses the . |
| Public method | [Use(bool)](WoWItem/Methods/Use_A6A00157326F.md) | Uses the . |
| Public method | [Use(ulong)](WoWItem/Methods/Use_C862DAEF9386.md) | Uses the . |
| Public method | [Use(ulong, bool)](WoWItem/Methods/Use_E78CCFB63B6A.md) | Uses the . |
| Public method | [UseContainerItem](WoWItem/Methods/UseContainerItem_91F6724291C3.md) | Uses the container item. |
| Public method | CompareTo(WoWObject) | Compares the current instance with another object. (Inherited from WoWObject.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from WoWObject.) |
| Public method | Equals(WoWObject) | Determines whether the specified object is equal to the current object. (Inherited from WoWObject.) |
| Protected method | GetDescriptorField(int) | Gets the descriptor field. (Inherited from WoWObject.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from WoWObject.) |
| Public method | GetObjectName | Gets the name of this WoW object from game memory. Uses Executor to call WoW's internal name retrieval function. Based on HB 3.3.5a WoWObject.GetObjectName() implementation. (Inherited from WoWObject.) |
| Public method | GetPosition | Gets the position. (Inherited from WoWObject.) |
| Public method | Interact(bool) | Interacts with the object. (Inherited from WoWObject.) |
| Public method | IsBehind(WoWObject) | Determines whether the target is behind. (Inherited from WoWObject.) |
| Public method | IsFacing(WoWObject) | Determines whether the target is facing the point. (Inherited from WoWObject.) |
| Public method | IsFacing(WoWPoint) | Determines whether the target is facing the point. (Inherited from WoWObject.) |
| Public method | IsSafelyBehind(WoWObject) | Determines whether the target is safely behind. (Inherited from WoWObject.) |
| Public method | IsSafelyFacing(WoWObject) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | IsSafelyFacing(WoWPoint) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | IsSafelyFacing(WoWObject, float) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | ToContainer | Converts to container. (Inherited from WoWObject.) |
| Public method | ToDynamicObject | FEAT-28: Cast this object to WoWDynamicObject (e.g., Blizzard, Rain of Fire ground effects). (Inherited from WoWObject.) |
| Public method | ToGameObject | Converts to game object. (Inherited from WoWObject.) |
| Public method | ToItem | Converts to item. (Inherited from WoWObject.) |
| Public method | ToPlayer | Converts to player. (Inherited from WoWObject.) |
| Public method | ToUnit | Converts to unit. (Inherited from WoWObject.) |
| Protected method | WriteDescriptor(uint, T) | Writes the descriptor. (Inherited from WoWObject.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
