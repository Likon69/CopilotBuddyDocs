# Mount Class

Represents a mount.

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Mount
```

The Mount type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public delegate | [Mount.CanMountDelegate](Mount/CanMountDelegate.md) | Represents a delegate for can mount. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [IsOutdoors](Mount/Properties/IsOutdoors_E795BD084B19.md) | Gets a value indicating whether is outdoors. |
| Public property Static member | [MountDistance](Mount/Properties/MountDistance_84E9EB072A3C.md) | Gets the mount distance. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnDismount](Mount/Events/OnDismount_DAFFCFD2F0F0.md) | Fired when the player dismounts (HB 4.3.4 compatibility). |
| Public event Static member | [OnMountUp](Mount/Events/OnMountUp_ACFB3DA19BEF.md) | Fired when the player mounts up (HB 4.3.4 compatibility). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AddCantMountSpot(WoWPoint)](Mount/Methods/AddCantMountSpot_86C9F93612AD.md) | Adds the cant mount spot. |
| Public method Static member | [AutoDetectMount](Mount/Methods/AutoDetectMount_5A32867BCB46.md) | Auto-detects and sets mount name if FindMountAutomatically is enabled. Ported from HB 4.3.4. |
| Public method Static member | [CanMount](Mount/Methods/CanMount_8A162FD10D15.md) | Determines whether can mount. |
| Public method Static member | [ClearCantMountSpots](Mount/Methods/ClearCantMountSpots_7CB8645F48C9.md) | Clears the cant mount spots. |
| Public method Static member | [ClearShapeshift](Mount/Methods/ClearShapeshift_7D6F3682C2D7.md) | Clears the shapeshift. |
| Public method Static member | [Dismount](Mount/Methods/Dismount_CED7E05E2031.md) | Dismounts. |
| Public method Static member | [Dismount(string)](Mount/Methods/Dismount_4AEDB3CA6B96.md) | Dismounts. |
| Public method Static member | [MountUp](Mount/Methods/MountUp_884EBD52E4E9.md) | Mounts up. |
| Public method Static member | [MountUp(CanMountDelegate)](Mount/Methods/MountUp_05C039EBFD8A.md) | Mounts up. |
| Public method Static member | [MountUp(LocationRetriever)](Mount/Methods/MountUp_37AB3E357F2B.md) | Mounts up. |
| Public method Static member | [MountUp(CanMountDelegate, LocationRetriever)](Mount/Methods/MountUp_92874AAF84F7.md) | Mounts up with a custom can-mount check and destination (HB 4.3.4). Returns true if mount was attempted. |
| Public method Static member | [Pulse](Mount/Methods/Pulse_A0350FC82BED.md) | Pulses mount state and fires events (call from main bot pulse). |
| Public method Static member | [RemoveCantMountSpotsNear(WoWPoint, float)](Mount/Methods/RemoveCantMountSpotsNear_240A036699C9.md) | Removes all cant-mount spots within yards of . Call after a successful mount or harvest to clean up stale entries. |
| Public method Static member | [ShouldDismount(WoWPoint)](Mount/Methods/ShouldDismount_EC778E0C696F.md) | Check if we should dismount for a given destination. Ported from HB 4.3.4. |
| Public method Static member | [ShouldMount(WoWPoint)](Mount/Methods/ShouldMount_5B4648321FBB.md) | Determines whether should mount. |
| Public method Static member | [StateMount](Mount/Methods/StateMount_ED6064197810.md) | Performs state-based mounting. |
| Public method Static member | [StateMount(LocationRetriever)](Mount/Methods/StateMount_F0E8C28E1E81.md) | Performs state-based mounting. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
