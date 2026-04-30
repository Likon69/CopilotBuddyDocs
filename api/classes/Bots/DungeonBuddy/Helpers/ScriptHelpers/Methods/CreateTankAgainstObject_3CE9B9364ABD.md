# ScriptHelpers.CreateTankAgainstObject Method

Creates the tank against object.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateTankAgainstObject(CanRunDecoratorDelegate canRun, Func<WoWPoint> objectLocationToTankAt, Func<float> objectRadius)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| canRun | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The can run. |
| objectLocationToTankAt | Func<WoWPoint> | The object location to tank at. |
| objectRadius | Func<float> | The object radius. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
