# MountUpEventArgs Class

Event arguments for mount up events (HB 4.3.4 compatibility).

## Inheritance Hierarchy
System.Object
  System.EventArgs
    Styx.Logic.MountUpEventArgs

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class MountUpEventArgs : EventArgs
```

The MountUpEventArgs type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [MountUpEventArgs](MountUpEventArgs/Constructors/Constructor_BA5ED4960B87.md) | Initializes a new instance of the MountUpEventArgs class. |
| Public constructor | [MountUpEventArgs(bool, string)](MountUpEventArgs/Constructors/Constructor_68065E9D984D.md) | Initializes a new instance of the MountUpEventArgs class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Cancel](MountUpEventArgs/Properties/Cancel_B07B55ECFCC2.md) | Set to true to cancel the mount-up attempt (e.g. during elevator ride). HB 6.2.3 pattern: MeshNavigator.method_17 cancels mount while riding transport. |
| Public property | [Destination](MountUpEventArgs/Properties/Destination_9066127E5FA9.md) | The destination the bot is traveling to. |
| Public property | [IsFlying](MountUpEventArgs/Properties/IsFlying_8326DBDC3DE2.md) | Gets whether the mount is a flying mount. |
| Public property | [MountName](MountUpEventArgs/Properties/MountName_9976AAC98EA3.md) | Gets the name of the mount. |

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
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
