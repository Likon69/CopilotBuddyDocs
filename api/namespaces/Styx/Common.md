# Styx.Common Namespace

Contains common utility types used across the bot.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [AddCompositeListOperation](../../classes/Styx/Common/AddCompositeListOperation.md) | HB 6.2.3: Appends composite to end of list. |
| Public class | [CompositeListOperation](../../classes/Styx/Common/CompositeListOperation.md) | HB 6.2.3: Abstract base for hook operations. |
| Public class | [HookDescription](../../classes/Styx/Common/HookDescription.md) | HB 6.2.3: Metadata for registered hooks (name + description), identified by GUID. |
| Public class | [HookExecutor](../../classes/Styx/Common/HookExecutor.md) | Port of HB 6.2.3 Styx.Common.HookExecutor. A TreeSharp Action that reads TreeHooks at Start() time, rebuilds a PrioritySelector from registered operations, and ticks it. Uses a guard counter to detect when hooks change. |
| Public class | [InsertCompositeListOperation](../../classes/Styx/Common/InsertCompositeListOperation.md) | HB 6.2.3: Inserts composite at index (bounds-safe). |
| Public class | [MathEx](../../classes/Styx/Common/MathEx.md) | Extended math utilities. Ported from HB 4.3.4/5.4.8 |
| Public class | [ReplaceCompositeListOperation](../../classes/Styx/Common/ReplaceCompositeListOperation.md) | HB 6.2.3: Replaces entire list with a single composite. |
| Public class | [TreeHooks](../../classes/Styx/Common/TreeHooks.md) | Port of HB 6.2.3 Styx.Common.TreeHooks. Singleton registry that plugins use to inject behaviors into the bot loop. Plugins call AddHook/InsertHook/RemoveHook/ReplaceHook to modify named hook locations. HookExecutor reads these at Start() time and rebuilds its PrioritySelector when the guard counter changes. |

## See Also
[Namespace Index](../../index.md)
