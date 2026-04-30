# INavigationProvider Interface

Defines the contract for I Navigation Provider.

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public interface INavigationProvider
```

The INavigationProvider type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [PathPrecision](INavigationProvider/Properties/PathPrecision_467FC9F0995B.md) | Gets or sets the path precision. |
| Public property | [StuckHandler](INavigationProvider/Properties/StuckHandler_9720BFBDBEB8.md) | Gets or sets the stuck handler. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [AtLocation(WoWPoint, WoWPoint)](INavigationProvider/Methods/AtLocation_42361B568E52.md) | Determines whether the target location has been reached. |
| Public method | [CanNavigateFully(WoWPoint, WoWPoint, int)](INavigationProvider/Methods/CanNavigateFully_CEB644ADACEB.md) | Determines whether can navigate fully. |
| Public method | [Clear](INavigationProvider/Methods/Clear_94BCC6D791A6.md) | Clears the current contents. |
| Public method | [GeneratePath(WoWPoint, WoWPoint)](INavigationProvider/Methods/GeneratePath_1B3152E00EE5.md) | Generates a path. |
| Public method | [MoveTo(WoWPoint)](INavigationProvider/Methods/MoveTo_09CE89E79BF5.md) | Moves to to. |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
