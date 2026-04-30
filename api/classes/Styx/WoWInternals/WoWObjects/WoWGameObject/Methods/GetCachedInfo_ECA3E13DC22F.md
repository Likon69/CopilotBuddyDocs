# WoWGameObject.GetCachedInfo Method

Gets the cached game object info from WoW client memory. Reads the cache entry pointer at BaseAddress + 0x1A4 (420 decimal). Used by IsHerb, IsMineral, GetDataSlot, LockRecord.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool GetCachedInfo(out GameObjectCacheEntry info)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| info | GameObjectCacheEntry | The info. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[WoWGameObject Class](../../WoWGameObject.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
