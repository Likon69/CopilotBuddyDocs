# SpellManager.GetSpellCooldownTimeLeft Method

Gets the remaining cooldown for a specific spell by walking the cooldown linked list via pure ReadProcessMemory. Zero Execute() overhead. Node layout (HB 4.3.4 Struct78): +0x04=Next, +0x08=SpellId, +0x10=StartTime, +0x14=SpellCooldown, +0x2C=GCDDuration.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static TimeSpan GetSpellCooldownTimeLeft(int spellId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spellId | int | The spell id. |

## Return Value

Type: TimeSpan
The result of the operation.

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
