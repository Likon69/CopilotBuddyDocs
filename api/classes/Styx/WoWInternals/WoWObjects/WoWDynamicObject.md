# WoWDynamicObject Class

Represents a wow dynamic object.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWDynamicObject

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWDynamicObject : WoWObject
```

The WoWDynamicObject type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWDynamicObject(uint)](WoWDynamicObject/Constructors/Constructor_FE0F1F9E2486.md) | Initializes a new instance of the WoWDynamicObject class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AmIInRange](WoWDynamicObject/Properties/AmIInRange_CD3089CE0B75.md) | Gets a value indicating whether am i in range. |
| Public property | [CastTime](WoWDynamicObject/Properties/CastTime_F7EDF22DF7B3.md) | Gets the cast time. |
| Public property | [Caster](WoWDynamicObject/Properties/Caster_502F4F64614D.md) | Gets the caster. |
| Public property | [CasterGuid](WoWDynamicObject/Properties/CasterGuid_F95412C2F19B.md) | Gets the caster guid. |
| Public property | [DynObjType](WoWDynamicObject/Properties/DynObjType_7720E7A6A924.md) | Gets the dyn obj type. |
| Public property | [IsHostile](WoWDynamicObject/Properties/IsHostile_A236B2DBF9A8.md) | Gets a value indicating whether is hostile. |
| Public property | [IsMine](WoWDynamicObject/Properties/IsMine_42BE7C2B4E3F.md) | Gets a value indicating whether is mine. |
| Public property | [Location](WoWDynamicObject/Properties/Location_00CBC6F04A22.md) | Gets the location. (Overrides WoWObject.Location.) |
| Public property | [Radius](WoWDynamicObject/Properties/Radius_327F8E1D8F78.md) | Gets the radius. |
| Public property | [Spell](WoWDynamicObject/Properties/Spell_55DDB10ED1D7.md) | Gets the spell that created this dynamic object (HB 4.3.4 compatibility). |
| Public property | [SpellId](WoWDynamicObject/Properties/SpellId_FE10B3E7E6EA.md) | Gets the spell id. |
| Public property | [X](WoWDynamicObject/Properties/X_6391B30A63EC.md) | Gets the x. (Overrides WoWObject.X.) |
| Public property | [Y](WoWDynamicObject/Properties/Y_244B7E8E32C3.md) | Gets the y. (Overrides WoWObject.Y.) |
| Public property | [Z](WoWDynamicObject/Properties/Z_76914EBE02E4.md) | Gets the z. (Overrides WoWObject.Z.) |
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
| Public method | [IsPointInRange(WoWPoint)](WoWDynamicObject/Methods/IsPointInRange_65BA8CD4619B.md) | Determines whether is point in range. |
| Public method | [ToString](WoWDynamicObject/Methods/ToString_C07EBC547DBA.md) | Returns a string that represents the current object. (Overrides WoWObject.ToString().) |
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
