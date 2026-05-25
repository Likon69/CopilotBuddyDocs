# WoWGameObject Class

Represents a wow game object.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWGameObject

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWGameObject : WoWObject, IComparable<WoWGameObject>, IComparable<WoWUnit>, IComparer<WoWUnit>, IComparer<WoWGameObject>, ILootableObject
```

The WoWGameObject type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWGameObject(uint)](WoWGameObject/Constructors/Constructor_9E16D97CB525.md) | Initializes a new instance of the WoWGameObject class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AnimationProgress](WoWGameObject/Properties/AnimationProgress_0B22B9DFB804.md) | Gets the animation progress. |
| Public property | [ArtKit](WoWGameObject/Properties/ArtKit_043CBEDD94D2.md) | Gets the art kit. |
| Public property | [Bytes1](WoWGameObject/Properties/Bytes1_6123EBE81ED5.md) | Gets the bytes1. |
| Public property | [CanFish](WoWGameObject/Properties/CanFish_94E196D3F5BA.md) | Gets a value indicating whether can fish. |
| Public property | [CanHarvest](WoWGameObject/Properties/CanHarvest_B1C0254CC3DC.md) | Gets a value indicating whether can harvest. |
| Public property | [CanLoot](WoWGameObject/Properties/CanLoot_829B06C5497D.md) | Gets a value indicating whether can loot. |
| Public property | [CanMine](WoWGameObject/Properties/CanMine_4D691B82B4AF.md) | Gets a value indicating whether can mine. |
| Public property | [CreatedBy](WoWGameObject/Properties/CreatedBy_7BAE2FA0D942.md) | Gets the created by. |
| Public property | [CreatedByGuid](WoWGameObject/Properties/CreatedByGuid_4E0F1FAE8182.md) | Gets the created by guid. |
| Public property | [DisplayId](WoWGameObject/Properties/DisplayId_CA3325AB379D.md) | Gets the display id. |
| Public property | [DynamicFlags](WoWGameObject/Properties/DynamicFlags_3140C249DC20.md) | Gets the dynamic flags. |
| Public property | [Faction](WoWGameObject/Properties/Faction_37EDAC5A3B1F.md) | Gets the faction. |
| Public property | [FactionTemplate](WoWGameObject/Properties/FactionTemplate_C1A6A878289C.md) | Gets the faction template. |
| Public property | [FactionTemplateId](WoWGameObject/Properties/FactionTemplateId_043D066FB80C.md) | Gets the faction template id. |
| Public property | [Flags](WoWGameObject/Properties/Flags_DB2A3E862841.md) | Gets the flags. |
| Public property | [FlagsDynamic](WoWGameObject/Properties/FlagsDynamic_F73735AA6FDB.md) | Gets the flags dynamic. |
| Public property | [InUse](WoWGameObject/Properties/InUse_097D39DB7372.md) | Gets a value indicating whether in use. |
| Public property | [InteractRange](WoWGameObject/Properties/InteractRange_8EA7B001005E.md) | Gets the interact range. (Overrides WoWObject.InteractRange.) |
| Public property | [IsButton](WoWGameObject/Properties/IsButton_E15001AC0792.md) | Gets a value indicating whether is button. |
| Public property | [IsChest](WoWGameObject/Properties/IsChest_D369A3742CA4.md) | Gets a value indicating whether is chest. |
| Public property | [IsDoor](WoWGameObject/Properties/IsDoor_B9B2C1FD559E.md) | Gets a value indicating whether is door. |
| Public property | [IsHerb](WoWGameObject/Properties/IsHerb_C8D643F2BD56.md) | Gets a value indicating whether is herb. |
| Public property | [IsMailbox](WoWGameObject/Properties/IsMailbox_30C9C5CDB1D3.md) | Gets a value indicating whether is mailbox. |
| Public property | [IsMineral](WoWGameObject/Properties/IsMineral_B433079CF9A3.md) | Gets a value indicating whether is mineral. |
| Public property | [IsQuestGiver](WoWGameObject/Properties/IsQuestGiver_2CF311150758.md) | Gets a value indicating whether is quest giver. |
| Public property | [IsTransport](WoWGameObject/Properties/IsTransport_5C6DE6C35D53.md) | Gets a value indicating whether is transport. |
| Public property | [Level](WoWGameObject/Properties/Level_90019BB5C924.md) | Gets the level. |
| Public property | [Location](WoWGameObject/Properties/Location_C26CA984FFE2.md) | Gets the location. (Overrides WoWObject.Location.) |
| Public property | [LockType](WoWGameObject/Properties/LockType_C60A0BF4688D.md) | Gets the lock type. |
| Public property | [Locked](WoWGameObject/Properties/Locked_73BC19D4D005.md) | Gets a value indicating whether locked. |
| Public property | [Model](WoWGameObject/Properties/Model_8F7136C4E0A4.md) | Gets the model file path from GameObjectDisplayInfo DBC. BUG-23 fix: Was returning Name instead of actual model path. |
| Public property | [ParentRotation](WoWGameObject/Properties/ParentRotation_A4109D900F06.md) | Gets the parent rotation. |
| Public property | [RequiredSkill](WoWGameObject/Properties/RequiredSkill_0C458F19623F.md) | Gets the required skill level to interact with this object (herbs, minerals, chests). |
| Public property | [Rotation](WoWGameObject/Properties/Rotation_E210E1D0FC26.md) | Gets the rotation. (Overrides WoWObject.Rotation.) |
| Public property | [SpellFocus](WoWGameObject/Properties/SpellFocus_2EA04187B3BE.md) | Gets the spell focus. |
| Public property | [State](WoWGameObject/Properties/State_0DD88EE030E7.md) | Gets the state. |
| Public property | [SubObj](WoWGameObject/Properties/SubObj_A4F0098D3E7D.md) | Sub-object associated with this GameObject (chair, door, bobber, etc.). HB-compatible API: returns a `WoWSubObject` so callers can cast to specific sub-types (e.g. `WoWFishingBobber`). When a real sub-object pointer is unavailable we return an inert `WoWSubObject` with a zero base address to preserve runtime safety. |
| Public property | [SubType](WoWGameObject/Properties/SubType_F4563210658C.md) | Gets the sub type. |
| Public property | [Transport](WoWGameObject/Properties/Transport_B634AAA8AC2D.md) | Gets a value indicating whether transport. |
| Public property | [Triggered](WoWGameObject/Properties/Triggered_8C2B946D77D3.md) | Gets a value indicating whether triggered. |
| Public property | [WorldMatrix](WoWGameObject/Properties/WorldMatrix_FFBD0020F24B.md) | Gets the world matrix. |
| Public property | [X](WoWGameObject/Properties/X_03EFFC24F854.md) | Gets the x. (Overrides WoWObject.X.) |
| Public property | [Y](WoWGameObject/Properties/Y_C426BE9CA908.md) | Gets the y. (Overrides WoWObject.Y.) |
| Public property | [Z](WoWGameObject/Properties/Z_327A3DF77E15.md) | Gets the z. (Overrides WoWObject.Z.) |
| Public property | BaseAddress | Gets the base address. (Inherited from WoWObject.) |
| Public property | DescriptorGuid | Gets the descriptor guid. (Inherited from WoWObject.) |
| Public property | Distance | Gets the distance. (Inherited from WoWObject.) |
| Public property | Distance2D | Gets the distance2d. (Inherited from WoWObject.) |
| Public property | Distance2DSqr | Gets the distance2d sqr. (Inherited from WoWObject.) |
| Public property | DistanceSqr | Gets the distance sqr. (Inherited from WoWObject.) |
| Public property | Entry | Gets the entry. (Inherited from WoWObject.) |
| Public property | Guid | Gets the guid. (Inherited from WoWObject.) |
| Public property | InLineOfSight | Whether this object is in line of sight from the player. Uses native CGWorldFrame::Intersect raycasting. Ported from HB 4.3.4 WoWObject — WoWUnit overrides with BoundingHeight-aware version. (Inherited from WoWObject.) |
| Public property | InLineOfSightOCD | HB 4.3.4 compat — was marked [Obsolete], just delegates to InLineOfSight. External bots (LazyRaider etc.) reference this. (Inherited from WoWObject.) |
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
| Public method | [CanUse](WoWGameObject/Methods/CanUse_CD00822D9943.md) | Determines whether can use. |
| Public method | [CanUseNow](WoWGameObject/Methods/CanUseNow_896691489B49.md) | Determines whether can use now. |
| Public method | [CanUseNow(GameError)](WoWGameObject/Methods/CanUseNow_556141586C1A.md) | Determines whether can use now. |
| Public method | [Compare(WoWUnit, WoWUnit)](WoWGameObject/Methods/Compare_921211280635.md) | Compares the specified values. |
| Public method | [Compare(WoWGameObject, WoWGameObject)](WoWGameObject/Methods/Compare_207027639420.md) | Compares the specified values. |
| Public method | [CompareTo(WoWGameObject)](WoWGameObject/Methods/CompareTo_ACD0C5507566.md) | Compares the current instance with another object. |
| Public method | [CompareTo(WoWUnit)](WoWGameObject/Methods/CompareTo_F76C550C09FC.md) | Compares the current instance with another object. |
| Public method | [GetCachedInfo(GameObjectCacheEntry)](WoWGameObject/Methods/GetCachedInfo_ECA3E13DC22F.md) | Gets the cached game object info from WoW client memory. Reads the cache entry pointer at BaseAddress + 0x1A4 (420 decimal). Used by IsHerb, IsMineral, GetDataSlot, LockRecord. |
| Public method | [GetDataSlot(GameObjectDataSlot, int)](WoWGameObject/Methods/GetDataSlot_B3F73A4E7E96.md) | Gets the data slot. |
| Public method | [GetDataSlot(GameObjectDataSlot, bool)](WoWGameObject/Methods/GetDataSlot_57FDAEA5B1F7.md) | Gets the data slot. |
| Public method | [GetDataSlot(uint, int)](WoWGameObject/Methods/GetDataSlot_EF184DDAE1A3.md) | Gets the data slot. |
| Public method | [GetReactionTowards(WoWUnit)](WoWGameObject/Methods/GetReactionTowards_84AA4A6E44EF.md) | Gets the reaction towards. |
| Public method | [GetWorldMatrix](WoWGameObject/Methods/GetWorldMatrix_8C4DE23DF1E7.md) | World transform matrix. For transports (elevators, ships), reads the live matrix from game memory at BaseAddress + 0x1A8 (updated each frame by the client). For static objects, computes from position + rotation. Matches HB 3.3.5a's GetWorldMatrix(). |
| Public method | [GetWorldMatrix(bool)](WoWGameObject/Methods/GetWorldMatrix_13FD8B409F58.md) | Gets the world matrix. |
| Public method | [ToString](WoWGameObject/Methods/ToString_7ACF6639ADAC.md) | Returns a string that represents the current object. (Overrides WoWObject.ToString().) |
| Public method | CompareTo(WoWObject) | Compares the current instance with another object. (Inherited from WoWObject.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from WoWObject.) |
| Public method | Equals(WoWObject) | Determines whether the specified object is equal to the current object. (Inherited from WoWObject.) |
| Protected method | GetDescriptorField(int) | Gets the descriptor field. (Inherited from WoWObject.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from WoWObject.) |
| Public method | GetObjectName | Gets the name of this WoW object from game memory. Uses Executor to call WoW's internal name retrieval function. Based on HB 3.3.5a WoWObject.GetObjectName() implementation. (Inherited from WoWObject.) |
| Public method | GetPosition | Gets the position. (Inherited from WoWObject.) |
| Public method | Interact | Interacts with the object. (Inherited from WoWObject.) |
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
