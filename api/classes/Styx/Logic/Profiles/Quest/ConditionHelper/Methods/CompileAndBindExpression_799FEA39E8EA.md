# ConditionHelper.CompileAndBindExpression Method

Compile expression and return bound delegate using Roslyn

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool CompileAndBindExpression(out string[] buildErrors, out Func<bool> boundExpression)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| buildErrors | string[] | The build errors. |
| boundExpression | Func<bool> | The bound expression. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[ConditionHelper Class](../../ConditionHelper.md)
[Styx.Logic.Profiles.Quest Namespace](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
