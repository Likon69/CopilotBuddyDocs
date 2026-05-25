# WoWObject Class

Represents a wow object.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWObject : IComparable<WoWObject>, IEquatable<WoWObject>
```

The WoWObject type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWObject(uint)](WoWObject/Constructors/Constructor_1B3ACA6778D0.md) | Initializes a new instance of the WoWObject class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BaseAddress](WoWObject/Properties/BaseAddress_492AAE85E67F.md) | Gets the base address. |
| Public property | [DescriptorGuid](WoWObject/Properties/DescriptorGuid_B26F316E4116.md) | Gets the descriptor guid. |
| Public property | [Distance](WoWObject/Properties/Distance_CE704472EEFF.md) | Gets the distance. |
| Public property | [Distance2D](WoWObject/Properties/Distance2D_711DA676678E.md) | Gets the distance2d. |
| Public property | [Distance2DSqr](WoWObject/Properties/Distance2DSqr_56513A6C016B.md) | Gets the distance2d sqr. |
| Public property | [DistanceSqr](WoWObject/Properties/DistanceSqr_0EED3CFC9635.md) | Gets the distance sqr. |
| Public property | [Entry](WoWObject/Properties/Entry_BB30729388DC.md) | Gets the entry. |
| Public property | [Guid](WoWObject/Properties/Guid_9EBAFBD4CA9C.md) | Gets the guid. |
| Public property | [InLineOfSight](WoWObject/Properties/InLineOfSight_A377F3429901.md) | Whether this object is in line of sight from the player. Uses native CGWorldFrame::Intersect raycasting. Ported from HB 4.3.4 WoWObject — WoWUnit overrides with BoundingHeight-aware version. |
| Public property | [InLineOfSightOCD](WoWObject/Properties/InLineOfSightOCD_9BDD4A778E20.md) | HB 4.3.4 compat — was marked [Obsolete], just delegates to InLineOfSight. External bots (LazyRaider etc.) reference this. |
| Public property | [InteractRange](WoWObject/Properties/InteractRange_99A80557DA01.md) | Gets the interact range. |
| Public property | [InteractRangeSqr](WoWObject/Properties/InteractRangeSqr_03A9554B5AE9.md) | FEAT-28: Squared interact range for faster distance checks (avoids sqrt). |
| Public property | [InteractType](WoWObject/Properties/InteractType_9EA6D2B14334.md) | Gets the interact type. |
| Public property | [IsDisabled](WoWObject/Properties/IsDisabled_CA00033E94A6.md) | Gets a value indicating whether is disabled. |
| Public property | [IsIndoors](WoWObject/Properties/IsIndoors_BFC833E84B34.md) | Gets a value indicating whether is indoors. |
| Public property | [IsMe](WoWObject/Properties/IsMe_591F6D9719B7.md) | Gets a value indicating whether is me. |
| Public property | [IsOutdoors](WoWObject/Properties/IsOutdoors_B015AB15D5D1.md) | Whether this object is indoors. Override on LocalPlayer uses Lua for accuracy. FEAT-45: Made virtual so LocalPlayer can override. |
| Public property | [IsUnderground](WoWObject/Properties/IsUnderground_E27ED67229BC.md) | Gets a value indicating whether is underground. |
| Public property | [IsValid](WoWObject/Properties/IsValid_4E903E878B2D.md) | Gets a value indicating whether is valid. |
| Public property | [Location](WoWObject/Properties/Location_ECF3EB3AA650.md) | Gets the location. |
| Public property | [MeIsBehind](WoWObject/Properties/MeIsBehind_397CD087104B.md) | Gets a value indicating whether me is behind. |
| Public property | [MeIsSafelyBehind](WoWObject/Properties/MeIsSafelyBehind_2244DCAB4964.md) | Gets a value indicating whether me is safely behind. |
| Protected property Static member | [Memory](WoWObject/Properties/Memory_3D3C31CF1FD9.md) | Gets the memory. |
| Public property | [Name](WoWObject/Properties/Name_2ED73C6FC932.md) | Gets the name. |
| Public property | [ObjectFlags](WoWObject/Properties/ObjectFlags_2A5DE384B24A.md) | Gets the object flags. |
| Public property | [QuestGiverStatus](WoWObject/Properties/QuestGiverStatus_106D54DD1695.md) | Gets the quest giver status. |
| Public property | [Rotation](WoWObject/Properties/Rotation_27CF84DC9C2A.md) | Gets the rotation. |
| Public property | [RotationDegrees](WoWObject/Properties/RotationDegrees_35D5A15A1EE2.md) | Gets the rotation degrees. |
| Public property | [Type](WoWObject/Properties/Type_B75E2D6A00EB.md) | Gets the type. |
| Public property | [TypeFlags](WoWObject/Properties/TypeFlags_53052F716CEF.md) | Gets the type flags. |
| Public property | [WithinInteractRange](WoWObject/Properties/WithinInteractRange_FD011C1E1AA3.md) | Gets a value indicating whether within interact range. |
| Public property | [WorldLocation](WoWObject/Properties/WorldLocation_1AFA4C2657C4.md) | Alias for Location. Matches HB 4.3.4 API surface used by external plugins. |
| Public property | [X](WoWObject/Properties/X_C64AF434BC97.md) | Gets the x. |
| Public property | [Y](WoWObject/Properties/Y_1BAC0E58AB6D.md) | Gets the y. |
| Public property | [Z](WoWObject/Properties/Z_FD00EC65E5A6.md) | Gets the z. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [OnInvalidate](WoWObject/Events/OnInvalidate_0488B27147AC.md) | Occurs when invalidate. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CompareTo(WoWObject)](WoWObject/Methods/CompareTo_B9F594AE34DB.md) | Compares the current instance with another object. |
| Public method | [Equals(object)](WoWObject/Methods/Equals_87ADC3D3DB3A.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().) |
| Public method | [Equals(WoWObject)](WoWObject/Methods/Equals_13ECB9CABD6F.md) | Determines whether the specified object is equal to the current object. |
| Protected method | [GetDescriptorField(int)](WoWObject/Methods/GetDescriptorField_134A15A13DF3.md) | Gets the descriptor field. |
| Public method | [GetHashCode](WoWObject/Methods/GetHashCode_8D8608D5A92C.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().) |
| Public method | [GetObjectName](WoWObject/Methods/GetObjectName_5AAFAAC1340C.md) | Gets the name of this WoW object from game memory. Uses Executor to call WoW's internal name retrieval function. Based on HB 3.3.5a WoWObject.GetObjectName() implementation. |
| Public method | [GetPosition](WoWObject/Methods/GetPosition_167A0C0B7807.md) | Gets the position. |
| Public method | [Interact](WoWObject/Methods/Interact_0532516B1E22.md) | Interacts with the object. |
| Public method | [Interact(bool)](WoWObject/Methods/Interact_E166198E5B7A.md) | Interacts with the object. |
| Public method | [IsBehind(WoWObject)](WoWObject/Methods/IsBehind_8C60C65DE906.md) | Determines whether the target is behind. |
| Public method | [IsFacing(WoWObject)](WoWObject/Methods/IsFacing_A832009980DB.md) | Determines whether the target is facing the point. |
| Public method | [IsFacing(WoWPoint)](WoWObject/Methods/IsFacing_C7C07841DC12.md) | Determines whether the target is facing the point. |
| Public method | [IsSafelyBehind(WoWObject)](WoWObject/Methods/IsSafelyBehind_2C146F2ECFF5.md) | Determines whether the target is safely behind. |
| Public method | [IsSafelyFacing(WoWObject)](WoWObject/Methods/IsSafelyFacing_DB5513A397BD.md) | Determines whether the target is safely facing the point. |
| Public method | [IsSafelyFacing(WoWPoint)](WoWObject/Methods/IsSafelyFacing_E5AF377C20A7.md) | Determines whether the target is safely facing the point. |
| Public method | [IsSafelyFacing(WoWObject, float)](WoWObject/Methods/IsSafelyFacing_682B8ED9E760.md) | Determines whether the target is safely facing the point. |
| Public method | [ToContainer](WoWObject/Methods/ToContainer_2BBB85EC8FA1.md) | Converts to container. |
| Public method | [ToDynamicObject](WoWObject/Methods/ToDynamicObject_0B3D998E0B57.md) | FEAT-28: Cast this object to WoWDynamicObject (e.g., Blizzard, Rain of Fire ground effects). |
| Public method | [ToGameObject](WoWObject/Methods/ToGameObject_D7DEAF4EE2DA.md) | Converts to game object. |
| Public method | [ToItem](WoWObject/Methods/ToItem_E53609786462.md) | Converts to item. |
| Public method | [ToPlayer](WoWObject/Methods/ToPlayer_BB5E28DE9BF2.md) | Converts to player. |
| Public method | [ToString](WoWObject/Methods/ToString_A851304933D2.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | [ToUnit](WoWObject/Methods/ToUnit_A89B65FFC386.md) | Converts to unit. |
| Protected method | [WriteDescriptor(uint, T)](WoWObject/Methods/WriteDescriptor_B0A8EB1C75A3.md) | Writes the descriptor. |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
