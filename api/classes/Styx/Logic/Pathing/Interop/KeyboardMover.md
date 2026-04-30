# KeyboardMover Class

Keyboard-based player mover — uses SetFacing + MoveForward instead of ClickToMove. Useful as a fallback when CTM is unreliable (elevators, steep terrain, narrow pathways). HB 6.2.3 pattern: SetFacing toward target, then MoveForwardStart.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Pathing.Interop.KeyboardMover

## Namespace
[Styx.Logic.Pathing.Interop](../../../../../namespaces/Styx/Logic/Pathing/Interop.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class KeyboardMover : IMover
```

The KeyboardMover type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [KeyboardMover](KeyboardMover/Constructors/Constructor_7249D509BD4D.md) | Initializes a new instance of the KeyboardMover class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Facing](KeyboardMover/Properties/Facing_81662B3DBAA6.md) | Gets the facing. |
| Public property | [IsStuck](KeyboardMover/Properties/IsStuck_A08008F3E717.md) | Gets a value indicating whether is stuck. |
| Public property | [Location](KeyboardMover/Properties/Location_BA76A53400C6.md) | Gets the location. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Move(MovementDirection)](KeyboardMover/Methods/Move_9E032A7EB6EF.md) | Moves to . |
| Public method | [MoveInDirection(MoveDirection, bool)](KeyboardMover/Methods/MoveInDirection_988FD02AC5C5.md) | Moves to in direction. |
| Public method | [MoveStop](KeyboardMover/Methods/MoveStop_5CD4F731A773.md) | Moves to stop. |
| Public method | [MoveTowards(Vector3)](KeyboardMover/Methods/MoveTowards_B82D6388DB35.md) | Moves toward the target point by adjusting facing and pressing MoveForward. HB 6.2.3 pattern: smooth facing adjustment with proportional turn speed. |
| Public method | [PerformJump](KeyboardMover/Methods/PerformJump_78DAD85631A0.md) | Performs a jump. |
| Public method | [SetFacing(float)](KeyboardMover/Methods/SetFacing_D2E2AFC92DF2.md) | Sets the facing. |
| Public method | [StopMoving](KeyboardMover/Methods/StopMoving_9B6D39F3BBFD.md) | Stops the moving. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing.Interop Namespace](../../../../../namespaces/Styx/Logic/Pathing/Interop.md)
