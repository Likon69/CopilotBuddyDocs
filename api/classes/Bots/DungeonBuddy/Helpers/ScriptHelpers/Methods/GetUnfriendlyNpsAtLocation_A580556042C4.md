# ScriptHelpers.GetUnfriendlyNpsAtLocation Method

Gets the unfriendly nps at location.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static List<WoWUnit> GetUnfriendlyNpsAtLocation(Func<WoWPoint> locationSelector, float radius, Func<WoWUnit, bool> filter)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| locationSelector | Func<WoWPoint> | The location selector. |
| radius | float | The radius. |
| filter | Func<WoWUnit, bool> | The filter. |

## Return Value

Type: List<WoWUnit>
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
