# SpellManager.CanCast Method

Determines whether can cast.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool CanCast(WoWSpell spell, WoWUnit target, bool checkRange, bool checkMovement)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spell | [WoWSpell](../../WoWSpell.md) | The spell. |
| target | [WoWUnit](../../../../WoWInternals/WoWObjects/WoWUnit.md) | The target. |
| checkRange | bool | The check range. |
| checkMovement | bool | The check movement. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
