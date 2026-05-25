# LocalPlayerMover Class

Implements player movement control via WoW API calls.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Pathing.Interop.LocalPlayerMover

## Namespace
[Styx.Logic.Pathing.Interop](../../../../../namespaces/Styx/Logic/Pathing/Interop.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class LocalPlayerMover : IMover
```

The LocalPlayerMover type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [LocalPlayerMover](LocalPlayerMover/Constructors/Constructor_68BD21C692C5.md) | Initializes a new instance of the LocalPlayerMover class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Facing](LocalPlayerMover/Properties/Facing_D2D59A3A0D36.md) | Gets the player's current facing angle. |
| Public property | [IsStuck](LocalPlayerMover/Properties/IsStuck_D31E2EB184D4.md) | Gets a value indicating whether the player is stuck (not moving). |
| Public property | [Location](LocalPlayerMover/Properties/Location_305FED34C5B6.md) | Gets the player's current location. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Move(MovementDirection)](LocalPlayerMover/Methods/Move_89B4BA8CB3B1.md) | Moves to . |
| Public method | [MoveInDirection(MoveDirection, bool)](LocalPlayerMover/Methods/MoveInDirection_2CA1082BCB61.md) | Moves the player in a specific direction (strafe, turn, etc). |
| Public method | [MoveStop](LocalPlayerMover/Methods/MoveStop_FD8162368365.md) | Stops all player movement (alias for StopMoving). |
| Public method | [MoveTowards(Vector3)](LocalPlayerMover/Methods/MoveTowards_71CF0F19EFC3.md) | Moves the player towards a specific point using click-to-move. HB 6.2.3 ClickToMoveMover: click the point directly, no look-ahead projection. The push-ahead offset is already applied by Navigator.method_26 before this call. |
| Public method | [PerformJump](LocalPlayerMover/Methods/PerformJump_4D5A20FD1F36.md) | Performs a jump action, waiting for the fall to complete. |
| Public method | [SetFacing(float)](LocalPlayerMover/Methods/SetFacing_BAEF32077BF9.md) | Sets the player's facing direction. |
| Public method | [StopMoving](LocalPlayerMover/Methods/StopMoving_C434529D4777.md) | Stops all player movement. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing.Interop Namespace](../../../../../namespaces/Styx/Logic/Pathing/Interop.md)
