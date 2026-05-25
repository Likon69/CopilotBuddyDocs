# WoWCorpse Class

Represents a wow corpse.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWCorpse

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWCorpse : WoWObject
```

The WoWCorpse type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWCorpse(uint)](WoWCorpse/Constructors/Constructor_F1DC0306BCDC.md) | Initializes a new instance of the WoWCorpse class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Bytes2](WoWCorpse/Properties/Bytes2_CEFBD4A42022.md) | Gets the bytes2. |
| Public property | [DisplayId](WoWCorpse/Properties/DisplayId_5C18CEE18DA6.md) | Gets the display id. |
| Public property | [DynamicFlags](WoWCorpse/Properties/DynamicFlags_E024803CCC2D.md) | Gets the dynamic flags. |
| Public property | [Face](WoWCorpse/Properties/Face_052F5579B5CB.md) | Gets the face. |
| Public property | [Flags](WoWCorpse/Properties/Flags_CA31381EEB11.md) | Gets the flags. |
| Public property | [Gender](WoWCorpse/Properties/Gender_87B4B3634597.md) | Gets the gender. |
| Public property | [GuildId](WoWCorpse/Properties/GuildId_9B14C408CE44.md) | Gets the guild id. |
| Public property | [IsBones](WoWCorpse/Properties/IsBones_1AF18D27C122.md) | Gets a value indicating whether is bones. |
| Public property | [IsInMyParty](WoWCorpse/Properties/IsInMyParty_34E8EBBFD6B2.md) | Gets a value indicating whether is in my party. |
| Public property | [IsLootable](WoWCorpse/Properties/IsLootable_13236448553C.md) | Gets a value indicating whether is lootable. |
| Public property | [IsMine](WoWCorpse/Properties/IsMine_B6514930BC90.md) | Gets a value indicating whether is mine. |
| Public property | [IsOnlyBones](WoWCorpse/Properties/IsOnlyBones_A47E98DC93FA.md) | Gets a value indicating whether is only bones. |
| Public property | [Location](WoWCorpse/Properties/Location_BC22A2FBF39B.md) | Gets the location. (Overrides WoWObject.Location.) |
| Public property | [OwnerGuid](WoWCorpse/Properties/OwnerGuid_9934E82A2A2A.md) | Gets the owner guid. |
| Public property | [PartyGuid](WoWCorpse/Properties/PartyGuid_B246A1802A47.md) | Gets the party guid. |
| Public property | [Race](WoWCorpse/Properties/Race_C3702D466F14.md) | Gets the race. |
| Public property | [Skin](WoWCorpse/Properties/Skin_51458C557601.md) | Gets the skin. |
| Public property | [X](WoWCorpse/Properties/X_E3C0D400180F.md) | Gets the x. (Overrides WoWObject.X.) |
| Public property | [Y](WoWCorpse/Properties/Y_BB5171473465.md) | Gets the y. (Overrides WoWObject.Y.) |
| Public property | [Z](WoWCorpse/Properties/Z_532C1C161F49.md) | Gets the z. (Overrides WoWObject.Z.) |
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
| Public method | [GetEquipmentDisplay(int)](WoWCorpse/Methods/GetEquipmentDisplay_61ADE34A8047.md) | Gets the equipment display. |
| Public method | [ToString](WoWCorpse/Methods/ToString_0ED026608847.md) | Returns a string that represents the current object. (Overrides WoWObject.ToString().) |
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
