# WoWMovementInfo Class

Represents movement information for a WoW unit. Contains position, speed, flags and other movement-related data.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWMovementInfo

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWMovementInfo
```

The WoWMovementInfo type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public struct | [WoWMovementInfo.CMovementData](WoWMovementInfo/CMovementData.md) | The raw CMovementData structure as stored in WoW memory. |
| Public enumeration | [WoWMovementInfo.MoveInfoOffsets](WoWMovementInfo/MoveInfoOffsets.md) | Offsets within the CMovementData structure for WoW 3.3.5a (Build 12340). |
| Public enumeration | [WoWMovementInfo.MovementFlag](WoWMovementInfo/MovementFlag.md) | Movement flags for WoW 3.3.5a. Ported from HB 4.3.4. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWMovementInfo(uint)](WoWMovementInfo/Constructors/Constructor_BBC8A7F02F69.md) | Creates a new WoWMovementInfo from a pointer to the movement data structure. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CanFly](WoWMovementInfo/Properties/CanFly_BC8ADAAF7F38.md) | Whether the unit can fly (has flight capability enabled). Ported from HB 4.3.4. |
| Public property | [CosAngle](WoWMovementInfo/Properties/CosAngle_C5E05E8CB7C1.md) | Cos of the strafe angle. |
| Public property | [CurrentSpeed](WoWMovementInfo/Properties/CurrentSpeed_87D7B362FE16.md) | Current movement speed. |
| Public property | [Destination](WoWMovementInfo/Properties/Destination_F485A9877CC6.md) | Movement destination (if using click-to-move or pathing). |
| Public property | [FallStartHeight](WoWMovementInfo/Properties/FallStartHeight_4DE7E820D1AC.md) | Height at which the fall started. |
| Public property | [FallTime](WoWMovementInfo/Properties/FallTime_3753EA837287.md) | Time spent falling (in milliseconds). |
| Public property | [FlyBackSpeed](WoWMovementInfo/Properties/FlyBackSpeed_81C190D07604.md) | Fly backward speed. |
| Public property | [FlySpeed](WoWMovementInfo/Properties/FlySpeed_359421A73FD7.md) | Fly speed. |
| Public property | [Heading](WoWMovementInfo/Properties/Heading_5B9369C3015A.md) | Current facing direction in radians. |
| Public property | [IsAscending](WoWMovementInfo/Properties/IsAscending_6858087EF465.md) | Whether the unit is ascending. |
| Public property | [IsDescending](WoWMovementInfo/Properties/IsDescending_E0D3008384E3.md) | Whether the unit is descending. |
| Public property | [IsFalling](WoWMovementInfo/Properties/IsFalling_03E6AAFBB666.md) | Whether the unit is falling. |
| Public property | [IsFlying](WoWMovementInfo/Properties/IsFlying_8C1AB891C653.md) | Whether the unit is flying. |
| Public property | [IsMoving](WoWMovementInfo/Properties/IsMoving_88DA779FA02F.md) | Whether the unit is currently moving. Uses movement flags like HB 4.3.4 instead of TimeMoved for accurate detection. This prevents false positives during facing/turning operations. |
| Public property | [IsStrafing](WoWMovementInfo/Properties/IsStrafing_80578F3EDCFA.md) | Whether the unit is strafing (left or right). |
| Public property | [IsSwimming](WoWMovementInfo/Properties/IsSwimming_492ED35DE0A8.md) | Whether the unit is swimming. |
| Public property | [IsValid](WoWMovementInfo/Properties/IsValid_312B5A901A1F.md) | Whether the movement info pointer is valid. |
| Public property | [JumpVelocity](WoWMovementInfo/Properties/JumpVelocity_A19181777833.md) | Jump velocity. |
| Public property | [JumpingOrShortFalling](WoWMovementInfo/Properties/JumpingOrShortFalling_E35853EA75FA.md) | Whether the unit is jumping or in a short fall. Ported from HB 4.3.4. |
| Public property | [LastFallHeight](WoWMovementInfo/Properties/LastFallHeight_F338E88CE20E.md) | Last recorded fall height. |
| Public property | [MovementFlags](WoWMovementInfo/Properties/MovementFlags_561FA8A73804.md) | Movement flags (Forward, Backward, Strafe, etc.). |
| Public property | [MovementFlags2](WoWMovementInfo/Properties/MovementFlags2_41AA1D73FDF2.md) | Secondary movement flags. |
| Public property | [MovingBackward](WoWMovementInfo/Properties/MovingBackward_B62F44EC9607.md) | Whether the unit is moving backward. |
| Public property | [MovingForward](WoWMovementInfo/Properties/MovingForward_421325E942DE.md) | Whether the unit is moving forward. |
| Public property | [Position](WoWMovementInfo/Properties/Position_27AF57DAE076.md) | Current position of the unit. |
| Public property | [RunBackSpeed](WoWMovementInfo/Properties/RunBackSpeed_D15F2F90DCA5.md) | Run backward speed. |
| Public property | [RunSpeed](WoWMovementInfo/Properties/RunSpeed_57022B733CF3.md) | Run speed. |
| Public property | [SinAngle](WoWMovementInfo/Properties/SinAngle_93A964CC8AFE.md) | Sin of the strafe angle. |
| Public property | [StrafingLeft](WoWMovementInfo/Properties/StrafingLeft_F96D01BBD4BA.md) | Whether the unit is strafing left. |
| Public property | [StrafingRight](WoWMovementInfo/Properties/StrafingRight_9AA1F362406E.md) | Whether the unit is strafing right. |
| Public property | [SwimBackSpeed](WoWMovementInfo/Properties/SwimBackSpeed_D133142D6A0C.md) | Swim backward speed. |
| Public property | [SwimSpeed](WoWMovementInfo/Properties/SwimSpeed_9A2E00AA8C3B.md) | Swim speed. |
| Public property | [TimeMoved](WoWMovementInfo/Properties/TimeMoved_D38C1554CF7A.md) | Time the unit has been moving (in milliseconds). 0 if the unit is not moving. |
| Public property | [TransportGuid](WoWMovementInfo/Properties/TransportGuid_087EE23388EB.md) | GUID of the transport the unit is on (if any). |
| Public property | [TurnSpeed](WoWMovementInfo/Properties/TurnSpeed_D18F48E21FED.md) | Turn speed (rotation rate). |
| Public property | [TurningLeft](WoWMovementInfo/Properties/TurningLeft_7B632DA355B9.md) | Whether the unit is turning left. |
| Public property | [TurningRight](WoWMovementInfo/Properties/TurningRight_878860A5BDCB.md) | Whether the unit is turning right. |
| Public property | [WalkSpeed](WoWMovementInfo/Properties/WalkSpeed_DBC12F606045.md) | Walk speed. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
