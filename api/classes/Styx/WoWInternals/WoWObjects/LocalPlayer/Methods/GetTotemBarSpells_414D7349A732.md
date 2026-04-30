# LocalPlayer.GetTotemBarSpells Method

FEAT-39: Gets spells on a totem multi-cast bar for a given totem element. Note: Multi-cast totem bar (Call of the Elements) is Cataclysm+. In WotLK, this returns an empty list. Kept for API compatibility.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public List<WoWSpell> GetTotemBarSpells(int totemIndex)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| totemIndex | int | The totem index. |

## Return Value

Type: List<WoWSpell>
The result of the operation.

## See Also
[LocalPlayer Class](../../LocalPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
