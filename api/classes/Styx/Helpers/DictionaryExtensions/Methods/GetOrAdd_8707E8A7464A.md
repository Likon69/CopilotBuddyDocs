# DictionaryExtensions.GetOrAdd Method

Gets a value from the dictionary or adds a default value if the key doesn't exist.

## Namespace
[Styx.Helpers](../../../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static TValue GetOrAdd(Dictionary<TKey, TValue> dictionary, TKey key, Func<TValue> defaultValueFactory)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| dictionary | Dictionary<TKey, TValue> | The dictionary. |
| key | TKey | The key to look up. |
| defaultValueFactory | Func<TValue> | A function that creates the default value if the key doesn't exist. |

## Return Value

Type: TValue
The existing value or the newly added default value.

## See Also
[DictionaryExtensions Class](../../DictionaryExtensions.md)
[Styx.Helpers Namespace](../../../../../namespaces/Styx/Helpers.md)
