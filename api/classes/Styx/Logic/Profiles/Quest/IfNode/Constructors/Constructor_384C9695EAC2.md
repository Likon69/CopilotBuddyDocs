# IfNode.IfNode Constructor

Initializes a new instance of the IfNode class.

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public IfNode(Func<bool> condition, IEnumerable<OrderNode> body, IEnumerable<ElseIf> elseIfs, Else else)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | Func<bool> | The condition. |
| body | IEnumerable<OrderNode> | The body. |
| elseIfs | IEnumerable<ElseIf> | The else ifs. |
| else | [Else](../../Else.md) | The else. |

## See Also
[IfNode Class](../../IfNode.md)
[Styx.Logic.Profiles.Quest Namespace](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
