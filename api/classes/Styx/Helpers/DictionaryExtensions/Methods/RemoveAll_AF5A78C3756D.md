# DictionaryExtensions.RemoveAll Method

Removes all key-value pairs from the dictionary where the value matches the predicate.

## Namespace
[Styx.Helpers](../../../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void RemoveAll(Dictionary<TKey, TValue> dictionary, Func<TValue, bool> predicate)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| dictionary | Dictionary<TKey, TValue> | The dictionary to remove items from. |
| predicate | Func<TValue, bool> | The condition to match values for removal. |

## See Also
[DictionaryExtensions Class](../../DictionaryExtensions.md)
[Styx.Helpers Namespace](../../../../../namespaces/Styx/Helpers.md)
