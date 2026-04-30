# QuestLog.GetQuestInfo Method

Gets quest info at a log index. descriptor_ptr + (field * 4) — quest log starts at field 158, each entry is 5 fields (20 bytes). So byte offset = (158 + index * 5) * 4, NOT 158 + index * 5 * 4.

## Namespace
[Styx.Logic.Questing](../../../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public QuestLogEntry GetQuestInfo(int index)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The index. |

## Return Value

Type: [QuestLogEntry](../../QuestLogEntry.md)
The result of the operation.

## See Also
[QuestLog Class](../../QuestLog.md)
[Styx.Logic.Questing Namespace](../../../../../../namespaces/Styx/Logic/Questing.md)
