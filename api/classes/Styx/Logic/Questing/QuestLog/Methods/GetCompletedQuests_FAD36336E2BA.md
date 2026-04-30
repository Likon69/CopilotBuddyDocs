# QuestLog.GetCompletedQuests Method

Gets a read-only collection of quest IDs that have been completed. Uses Lua QueryQuestsCompleted() which triggers QUEST_QUERY_COMPLETE event. Then reads the completed quest linked list from memory. Results are cached for 1 minute.

## Namespace
[Styx.Logic.Questing](../../../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public ReadOnlyCollection<uint> GetCompletedQuests()
```

## Return Value

Type: ReadOnlyCollection<uint>
The result of the operation.

## See Also
[QuestLog Class](../../QuestLog.md)
[Styx.Logic.Questing Namespace](../../../../../../namespaces/Styx/Logic/Questing.md)
