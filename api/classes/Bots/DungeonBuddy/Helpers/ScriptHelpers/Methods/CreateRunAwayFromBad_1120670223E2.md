# ScriptHelpers.CreateRunAwayFromBad Method

Crée un behavior pour fuir une zone dangereuse

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateRunAwayFromBad(CanRunDecoratorDelegate condition, float radius, uint objectEntryId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | Condition pour activer la fuite |
| radius | float | Rayon à éviter |
| objectEntryId | uint | Entry ID de l'objet/mob à fuir |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
