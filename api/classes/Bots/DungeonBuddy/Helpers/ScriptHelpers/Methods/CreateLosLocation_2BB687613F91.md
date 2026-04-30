# ScriptHelpers.CreateLosLocation Method

Creates the los location.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateLosLocation(CanRunDecoratorDelegate canRun, Func<WoWUnit> unitSelector, float range, Func<WoWPoint> loc)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| canRun | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The can run. |
| unitSelector | Func<WoWUnit> | The unit selector. |
| range | float | The range. |
| loc | Func<WoWPoint> | The loc. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
