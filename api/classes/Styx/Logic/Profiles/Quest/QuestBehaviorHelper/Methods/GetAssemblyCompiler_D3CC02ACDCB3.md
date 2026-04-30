# QuestBehaviorHelper.GetAssemblyCompiler Method

Creates a function that returns the compiled assembly for the specified behavior. This is the main entry point used by CodeNode.FromXml().

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Func<Assembly> GetAssemblyCompiler(string behaviorName)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| behaviorName | string | Name of the behavior (e.g., "Message", "InteractWith", "Escort") |

## Return Value

Type: Func<Assembly>
A function that returns the compiled assembly when called.

## See Also
[QuestBehaviorHelper Class](../../QuestBehaviorHelper.md)
[Styx.Logic.Profiles.Quest Namespace](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
