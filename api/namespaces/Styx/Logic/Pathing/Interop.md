# Styx.Logic.Pathing.Interop Namespace

Contains pathing interop types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [KeyboardMover](../../../../classes/Styx/Logic/Pathing/Interop/KeyboardMover.md) | Keyboard-based player mover — uses SetFacing + MoveForward instead of ClickToMove. Useful as a fallback when CTM is unreliable (elevators, steep terrain, narrow pathways). HB 6.2.3 pattern: SetFacing toward target, then MoveForwardStart. |
| Public class | [LocalPlayerMover](../../../../classes/Styx/Logic/Pathing/Interop/LocalPlayerMover.md) | Implements player movement control via WoW API calls. |
| Public class | [WorldInfoProvider](../../../../classes/Styx/Logic/Pathing/Interop/WorldInfoProvider.md) | Provides information about world objects (game objects, units, etc). |
| Public class | [WorldObject](../../../../classes/Styx/Logic/Pathing/Interop/WorldObject.md) | Adapts a WoWGameObject to the IWorldObject interface. |

## Interfaces

| | Name | Description |
| --- | --- | --- |
| Public interface | [IMover](../../../../classes/Styx/Logic/Pathing/Interop/IMover.md) | Interface for player movement control. |
| Public interface | [IWorldInfoProvider](../../../../classes/Styx/Logic/Pathing/Interop/IWorldInfoProvider.md) | Interface for world information providers. |
| Public interface | [IWorldObject](../../../../classes/Styx/Logic/Pathing/Interop/IWorldObject.md) | Interface for world objects used in navigation. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [MoveDirection](../../../../classes/Styx/Logic/Pathing/Interop/MoveDirection.md) | Movement directions for player movement control. |
| Public enumeration | [WorldObjectType](../../../../classes/Styx/Logic/Pathing/Interop/WorldObjectType.md) | Types of world objects for navigation purposes. |

## See Also
[Namespace Index](../../../../index.md)
