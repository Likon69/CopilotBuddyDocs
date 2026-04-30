# ScriptHelpers.CreateLosLocation Method

Creates the los location.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateLosLocation(CanRunDecoratorDelegate canRun, Func<WoWPoint> locationToLos, Func<WoWPoint> objectLocationToLosAt, Func<float> objectRadius)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| canRun | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The can run. |
| locationToLos | Func<WoWPoint> | The location to los. |
| objectLocationToLosAt | Func<WoWPoint> | The object location to los at. |
| objectRadius | Func<float> | The object radius. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
