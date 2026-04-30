# ScriptHelpers.CreateClearArea Method

Tue les PNJ hostiles dans un rayon autour d'une position. Référence HB 4.3.4 ScriptHelpers.cs L395

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateClearArea(Func<WoWPoint> centerLocationSelector, float radius, Func<WoWUnit, bool> unitSelector)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| centerLocationSelector | Func<WoWPoint> | The center location selector. |
| radius | float | The radius. |
| unitSelector | Func<WoWUnit, bool> | The unit selector. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
