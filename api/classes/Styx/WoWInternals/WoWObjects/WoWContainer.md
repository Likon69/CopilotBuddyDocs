# WoWContainer Class

Represents an equipped bag container in the player's inventory. Ported from HB 4.3.4 WoWContainer — delegates all item access to an internal WoWBag constructed from BagStructure at containerBaseAddress + 1888 (3.3.5a offset).

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWItem
      Styx.WoWInternals.WoWObjects.WoWContainer

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWContainer : WoWItem
```

The WoWContainer type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWContainer(uint)](WoWContainer/Constructors/Constructor_D672362D493F.md) | Initializes a new instance of the WoWContainer class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Bag](WoWContainer/Properties/Bag_649A20DA8B91.md) | Internal WoWBag built from BagStructure at BaseAddress + 1888. HB 4.3.4: new WoWBag(ObjectManager.Wow.ReadStruct<Struct58>(base.BaseAddress + offset(4998))) HB 3.3.5a offset 4998 = 1888. |
| Public property | [BagIndex](WoWContainer/Properties/BagIndex_75F9BC720DE7.md) | Gets the bag slot index (0-10) this container occupies, or -1 if not found. Ported from HB 4.3.4 WoWContainer.BagIndex. |
| Public property | [BagType](WoWContainer/Properties/BagType_7AE563FA1609.md) | Gets the bag type from the item's SubClass. WotLK bag SubClass mapping: 0=Normal, 1=SoulShard, 2=Herb, 3=Enchanting, 4=Engineering, 5=Gem, 6=Mining, 7=Leatherworking, 8=Inscription, 9=Ammo. |
| Public property | [FreeSlots](WoWContainer/Properties/FreeSlots_A2678ABAE739.md) | Number of free slots. Ported from HB 4.3.4 WoWContainer.FreeSlots. |
| Public property | [IsEmpty](WoWContainer/Properties/IsEmpty_D8AA96613F7F.md) | Gets a value indicating whether is empty. |
| Public property | [IsFull](WoWContainer/Properties/IsFull_375E57D9F4DE.md) | Gets a value indicating whether is full. |
| Public property | [ItemGuids](WoWContainer/Properties/ItemGuids_9939C3454F43.md) | All item GUIDs (including empty slots as 0). Ported from HB 4.3.4. |
| Public property | [Items](WoWContainer/Properties/Items_2D5E415FF7A5.md) | All items in the container (non-null only). Ported from HB 4.3.4. |
| Public property | [PhysicalItemGuids](WoWContainer/Properties/PhysicalItemGuids_4C10D0226489.md) | GUIDs of physical (non-zero) items. Ported from HB 4.3.4. |
| Public property | [PhysicalItems](WoWContainer/Properties/PhysicalItems_6C477105EA4C.md) | Non-null items as an array. Ported from HB 4.3.4. |
| Public property | [Slots](WoWContainer/Properties/Slots_314224ADE3A3.md) | Number of slots in this container. Ported from HB 4.3.4 WoWContainer.Slots. |
| Public property | [UsedSlots](WoWContainer/Properties/UsedSlots_AC46B20B7BFC.md) | Number of occupied slots. Ported from HB 4.3.4 WoWContainer.UsedSlots. |
| Public property | BagSlot | Gets the bag slot. (Inherited from WoWItem.) |
| Public property | BuyPrice | Gets the buy price. (Inherited from WoWItem.) |
| Public property | CanExpire | Gets a value indicating whether can expire. (Inherited from WoWItem.) |
| Public property | CanProspect | Gets a value indicating whether can prospect. (Inherited from WoWItem.) |
| Public property | ContainerGuid | Gets the container guid. (Inherited from WoWItem.) |
| Public property | Cooldown | Gets the cooldown. (Inherited from WoWItem.) |
| Public property | CooldownTimeLeft | FEAT-43: Gets the remaining cooldown as a TimeSpan. Uses Lua GetItemCooldown which returns (startTime, duration, isEnabled). (Inherited from WoWItem.) |
| Public property | CreatePlayedTime | Gets the create played time. (Inherited from WoWItem.) |
| Public property | CreatorGuid | Gets the creator guid. (Inherited from WoWItem.) |
| Public property | Distance | Gets the distance. (Overrides WoWObject.Distance.). (Inherited from WoWItem.) |
| Public property | Distance2D | Gets the distance2d. (Overrides WoWObject.Distance2D.). (Inherited from WoWItem.) |
| Public property | Distance2DSqr | Gets the distance2d sqr. (Overrides WoWObject.Distance2DSqr.). (Inherited from WoWItem.) |
| Public property | DistanceSqr | Gets the distance sqr. (Overrides WoWObject.DistanceSqr.). (Inherited from WoWItem.) |
| Public property | Durability | Gets the durability. (Inherited from WoWItem.) |
| Public property | DurabilityPercent | Gets the durability percent. (Inherited from WoWItem.) |
| Public property | Duration | Gets the duration. (Inherited from WoWItem.) |
| Public property | EquipSlot | Gets the equip slot. (Inherited from WoWItem.) |
| Public property | Flags | Gets the flags. (Inherited from WoWItem.) |
| Public property | GiftCreatorGuid | Gets the gift creator guid. (Inherited from WoWItem.) |
| Public property | HasEquipCooldown | Gets a value indicating whether has equip cooldown. (Inherited from WoWItem.) |
| Public property | IsAccountBound | Gets a value indicating whether is account bound. (Inherited from WoWItem.) |
| Public property | IsBroken | Gets a value indicating whether is broken. (Inherited from WoWItem.) |
| Public property | IsCharter | Gets a value indicating whether is charter. (Inherited from WoWItem.) |
| Public property | IsConjured | Gets a value indicating whether is conjured. (Inherited from WoWItem.) |
| Public property | IsEnchantScroll | Gets a value indicating whether is enchant scroll. (Inherited from WoWItem.) |
| Public property | IsGift | Gets a value indicating whether is gift. (Inherited from WoWItem.) |
| Public property | IsGiftWrapped | Gets a value indicating whether is gift wrapped. (Inherited from WoWItem.) |
| Public property | IsMillable | Gets a value indicating whether is millable. (Inherited from WoWItem.) |
| Public property | IsOpenable | Gets a value indicating whether is openable. (Inherited from WoWItem.) |
| Public property | IsPvPItem | Gets a value indicating whether is pv p item. (Inherited from WoWItem.) |
| Public property | IsReadable | Gets a value indicating whether is readable. (Inherited from WoWItem.) |
| Public property | IsSoulbound | Gets a value indicating whether is soulbound. (Inherited from WoWItem.) |
| Public property | IsThrownWeapon | Gets a value indicating whether is thrown weapon. (Inherited from WoWItem.) |
| Public property | IsTotem | Gets a value indicating whether is totem. (Inherited from WoWItem.) |
| Public property | IsUniqueEquipped | Gets a value indicating whether is unique equipped. (Inherited from WoWItem.) |
| Public property | IsWand | Gets a value indicating whether is wand. (Inherited from WoWItem.) |
| Public property | IsWrappingPaper | Gets a value indicating whether is wrapping paper. (Inherited from WoWItem.) |
| Public property | ItemClass | Gets the item class. (Inherited from WoWItem.) |
| Public property | ItemInfo | Gets the item info. (Inherited from WoWItem.) |
| Public property | ItemLevel | Gets the item level. (Inherited from WoWItem.) |
| Public property | ItemSpells | Gets the item spells. (Inherited from WoWItem.) |
| Public property | ItemStats | Gets the item stats. (Inherited from WoWItem.) |
| Public property | Link | Gets the link. (Inherited from WoWItem.) |
| Public property | Location | Gets the location. (Overrides WoWObject.Location.). (Inherited from WoWItem.) |
| Public property | MaxDurability | Gets the max durability. (Inherited from WoWItem.) |
| Public property | OwnerGuid | Gets the owner guid. (Inherited from WoWItem.) |
| Public property | PropertySeed | Gets the property seed. (Inherited from WoWItem.) |
| Public property | Quality | Gets the quality. (Inherited from WoWItem.) |
| Public property | RandomProperties | Gets the random properties. (Inherited from WoWItem.) |
| Public property | RandomPropertiesId | Gets the random properties id. (Inherited from WoWItem.) |
| Public property | RandomSuffix | Gets the random suffix. (Inherited from WoWItem.) |
| Public property | RequiredLevel | Gets the required level. (Inherited from WoWItem.) |
| Public property | SellPrice | Gets the sell price. (Inherited from WoWItem.) |
| Public property | SpellCharges | Gets the spell charges. (Inherited from WoWItem.) |
| Public property | StackCount | Gets the stack count. (Inherited from WoWItem.) |
| Public property | TemporaryEnchantment | Gets the temporary enchantment. (Inherited from WoWItem.) |
| Public property | TriggersSpell | Gets a value indicating whether triggers spell. (Inherited from WoWItem.) |
| Public property | Usable | Gets a value indicating whether usable. (Inherited from WoWItem.) |
| Public property | X | Gets the x. (Overrides WoWObject.X.). (Inherited from WoWItem.) |
| Public property | Y | Gets the y. (Overrides WoWObject.Y.). (Inherited from WoWItem.) |
| Public property | Z | Gets the z. (Overrides WoWObject.Z.). (Inherited from WoWItem.) |
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
| Public property | IsIndoors | Whether this object is indoors. Override on LocalPlayer uses Lua for accuracy. FEAT-45: Made virtual so LocalPlayer can override. (Inherited from WoWObject.) |
| Public property | IsMe | Gets a value indicating whether is me. (Inherited from WoWObject.) |
| Public property | IsOutdoors | Whether this object is outdoors. Override on LocalPlayer uses Lua for accuracy. FEAT-45: Made virtual so LocalPlayer can override. (Inherited from WoWObject.) |
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
| Public method | [CountItemsByEntry(uint)](WoWContainer/Methods/CountItemsByEntry_3EA3A638C3A7.md) | Counts the items with the specified entry ID. |
| Public method | [FindFirstFreeSlot](WoWContainer/Methods/FindFirstFreeSlot_E89F6A825D53.md) | Finds the first free slot. |
| Public method | [FindItemByEntry(uint)](WoWContainer/Methods/FindItemByEntry_E35F4B5D851E.md) | Finds the item by entry. |
| Public method | [GetItemBySlot(uint)](WoWContainer/Methods/GetItemBySlot_A5F2AF395E45.md) | Returns the item at the given slot. Ported from HB 4.3.4. |
| Public method | [GetItemGuidBySlot(uint)](WoWContainer/Methods/GetItemGuidBySlot_87357152B6DB.md) | Returns the item GUID at the given slot. Ported from HB 4.3.4. |
| Public method | [ToString](WoWContainer/Methods/ToString_55967DE64B0B.md) | Returns a string that represents the current object. (Overrides WoWItem.ToString().) |
| Public method | GetDamageType(int) | Gets the damage type. (Inherited from WoWItem.) |
| Public method | GetEnchantment(string) | Gets the enchantment. (Inherited from WoWItem.) |
| Public method | GetEnchantment(uint) | Gets the enchantment. (Inherited from WoWItem.) |
| Public method | GetEnchantmentById(uint) | Gets the enchantment by id. (Inherited from WoWItem.) |
| Public method | GetItemStats | Gets the item stats. (Inherited from WoWItem.) |
| Public method | GetMaxDamage(int) | Gets the max damage. (Inherited from WoWItem.) |
| Public method | GetMinDamage(int) | Gets the min damage. (Inherited from WoWItem.) |
| Public method | GetSocketColor(int) | Gets the socket color. (Inherited from WoWItem.) |
| Public method | GetSpell(int) | Gets the spell. (Inherited from WoWItem.) |
| Public method | GetStat(int) | Gets the stat. (Inherited from WoWItem.) |
| Public method | GetStatType(int) | Gets the stat type. (Inherited from WoWItem.) |
| Public method | GetStatValue(int) | Gets the stat value. (Inherited from WoWItem.) |
| Public method | Interact | Interacts with the object. (Overrides WoWObject.Interact().). (Inherited from WoWItem.) |
| Public method | PickUp | Picks up the item. (Inherited from WoWItem.) |
| Public method | Use | Uses the . (Inherited from WoWItem.) |
| Public method | Use(bool) | Uses the . (Inherited from WoWItem.) |
| Public method | Use(ulong) | Uses the . (Inherited from WoWItem.) |
| Public method | Use(ulong, bool) | Uses the . (Inherited from WoWItem.) |
| Public method | UseContainerItem | Uses the container item. (Inherited from WoWItem.) |
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
