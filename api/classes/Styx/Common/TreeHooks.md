# TreeHooks Class

Port of HB 6.2.3 Styx.Common.TreeHooks. Singleton registry that plugins use to inject behaviors into the bot loop. Plugins call AddHook/InsertHook/RemoveHook/ReplaceHook to modify named hook locations. HookExecutor reads these at Start() time and rebuilds its PrioritySelector when the guard counter changes.

## Inheritance Hierarchy
System.Object
  Styx.Common.TreeHooks

## Namespace
[Styx.Common](../../../namespaces/Styx/Common.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed class TreeHooks
```

The TreeHooks type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [HookDescriptions](TreeHooks/Properties/HookDescriptions_5B25B97D4FD5.md) | Metadata for registered hooks. |
| Public property | [Hooks](TreeHooks/Properties/Hooks_1C737A49F4DA.md) | Hook location name → list of pending operations. |
| Public property Static member | [Instance](TreeHooks/Properties/Instance_89BEFFEFDB69.md) | HB 6.2.3: Lazy singleton. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [HooksCleared](TreeHooks/Events/HooksCleared_3E94F9814762.md) | HB 6.2.3: Fired when ClearAll() is called. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [AddHook(string, Composite)](TreeHooks/Methods/AddHook_EC3DFBD971CF.md) | HB 6.2.3: Append a composite to a named hook location. |
| Public method | [ApplyCompositeOperations(string, List<Composite>)](TreeHooks/Methods/ApplyCompositeOperations_20D126054836.md) | HB 6.2.3: Apply all registered operations to a composite list. Called by HookExecutor.Start() to build the final PrioritySelector. |
| Public method | [ClearAll](TreeHooks/Methods/ClearAll_FF31B17534C7.md) | HB 6.2.3: Clear all hooks and fire event. |
| Public method | [InsertHook(string, int, Composite)](TreeHooks/Methods/InsertHook_586DB4C260CD.md) | HB 6.2.3: Insert a composite at a specific index. |
| Public method | [RemoveHook(string, Composite)](TreeHooks/Methods/RemoveHook_95CEEF09B65F.md) | HB 6.2.3: Remove a specific composite from a hook location. |
| Public method | [ReplaceHook(string, Composite)](TreeHooks/Methods/ReplaceHook_1CF2FF0D5EED.md) | HB 6.2.3: Replace all operations at a location with a single composite. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Common Namespace](../../../namespaces/Styx/Common.md)
