# ScriptHelpers.CreateTankUnitAtLocation Method

Déplace le tank vers une position spécifique. Utilisé par les scripts: HoL, HoL Heroic, etc. Référence HB 4.3.4 ScriptHelpers.cs L2088

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateTankUnitAtLocation(Func<WoWPoint> locationSelector, float precision)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| locationSelector | Func<WoWPoint> | The location selector. |
| precision | float | The precision. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
