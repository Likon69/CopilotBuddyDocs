# NavigationProvider Class

WoD-style navigation provider contract used by Navigator. Direct port of HB 6.2.3 Styx.Pathing.NavigationProvider.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Pathing.NavigationProvider

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class NavigationProvider
```

The NavigationProvider type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [NavigationProvider](NavigationProvider/Constructors/Constructor_FD6CB2AFDAFE.md) | Initializes a new instance of the NavigationProvider class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsCurrent](NavigationProvider/Properties/IsCurrent_213131FA2B02.md) | Gets a value indicating whether is current. |
| Public property | [PathPrecision](NavigationProvider/Properties/PathPrecision_9279BA2FB6F8.md) | Gets or sets the path precision. |
| Public property | [StuckHandler](NavigationProvider/Properties/StuckHandler_7F8987F26591.md) | Gets or sets the stuck handler. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [AtLocation(WoWPoint, WoWPoint)](NavigationProvider/Methods/AtLocation_5D5F0E1B3EED.md) | Determines whether the target location has been reached. |
| Public method | [CanNavigateFully(WoWPoint, WoWPoint)](NavigationProvider/Methods/CanNavigateFully_A62AAAB41EBD.md) | Determines whether can navigate fully. |
| Public method | [CanNavigateWithin(WoWPoint, WoWPoint, float)](NavigationProvider/Methods/CanNavigateWithin_FC0C859C22C6.md) | Determines whether can navigate within. |
| Public method | [Clear](NavigationProvider/Methods/Clear_520ED4C96B35.md) | Clears the current contents. |
| Public method | [GeneratePath(WoWPoint, WoWPoint)](NavigationProvider/Methods/GeneratePath_E48A396AA4A1.md) | Generates a path. |
| Public method | [MoveTo(WoWPoint)](NavigationProvider/Methods/MoveTo_86484952AD2A.md) | Moves to to. |
| Public method | [OnRemoveAsCurrent](NavigationProvider/Methods/OnRemoveAsCurrent_D654D08391EF.md) | Handles the on remove as current operation. |
| Public method | [OnSetAsCurrent](NavigationProvider/Methods/OnSetAsCurrent_362ACCCC4BFC.md) | Handles the on set as current operation. |
| Public method | [PathDistance(WoWPoint, WoWPoint, float)](NavigationProvider/Methods/PathDistance_6312188E282D.md) | Executes the path distance operation. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
