# ScriptHelpers.CreatePullNpcToLocation Method

Creates the pull npc to location.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreatePullNpcToLocation(CanRunDecoratorDelegate canRun, Func<WoWUnit> unitSelector, Func<WoWPoint> pullToLocationSelector, int waitTimeAtPullLocationTimeout)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| canRun | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The can run. |
| unitSelector | Func<WoWUnit> | The unit selector. |
| pullToLocationSelector | Func<WoWPoint> | The pull to location selector. |
| waitTimeAtPullLocationTimeout | int | The wait time at pull location timeout. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
